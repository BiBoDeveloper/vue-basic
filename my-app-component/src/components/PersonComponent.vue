<template>
  <div>
    <h1>Name {{ name }} Salary {{ salary }}</h1>
  </div>
</template>

<script>
export default {
    name: "PersonComponent",
    props : {
      name : {
        type: String,
        required: true
      },
      salary : {
        type: Number,
        default: 15000
      }
    }
    
}
</script>

<style>

</style>