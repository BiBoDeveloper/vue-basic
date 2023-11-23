<template>
  <div>
    <ul>
        <PersonComponent v-for="(item, index) in employees"
        :key="index"
        :name="item.name"
        :salary="item.salary" />
    </ul>
  </div>
</template>

<script>
import PersonComponent from './PersonComponent.vue'

export default {
    name:"ListData",
    components: {
        PersonComponent
    },
    employees: [
        {name:"BiBo", salary:40000},
        {name:"Pele", salary:50000},
        {name:"Phong", salary:30000},
        {name:"Toto", salary:60000},
        {name:"dada"},
      ]
}
</script>

<style>

</style>