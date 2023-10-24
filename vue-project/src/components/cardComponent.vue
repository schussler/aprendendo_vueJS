<template>
  <div class="p-3 mt-3 bg-primary">
    <h3>{{ name }}</h3>
    <hr>
    <h4>{{ descricao }}</h4>

  </div>
</template>


<script>
export default ({
  name: 'cardComponent',
  data() {
    return {
      // nome: 'Douglas Schussler',
      // descricao: 'Eu sou o'
    }
  },
  props: {
    name: String,
    descricao: String
  }
})

</script>

<style scoped></style>