<script>
export default {
  props: {
    titulo: {
      default: "Titulo Padrão",
    },
    nomes: {
      type: Array,
    },
  },
};
</script>
<template>
  <Article class="block">
    {{ titulo }}
    <hr />
    <ul>
      <li v-for="(nome, i) of nomes" :key="i">
        {{ nome }}
      </li>
    </ul>
  </Article>
</template>
<style></style>
