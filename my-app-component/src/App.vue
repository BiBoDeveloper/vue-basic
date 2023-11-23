<template>
  <div>
   <header>
     <h1>Management Employees System</h1>
   </header>
  <FormComponent />
  <ListData />
 </div>
</template>

<script>
import FormComponent from './components/FormComponent.vue'
import ListData from './components/ListData.vue'

export default {
  name: 'App',
  components: {
    FormComponent,
    ListData
  },
  data() {
    return {
      
    }
  }
}
</script>

<style>

</style>
