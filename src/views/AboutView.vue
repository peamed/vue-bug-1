<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>
<script lang="ts">
import { Options, Vue } from "vue-class-component";
@Options({
  name: "Abome",

  mounted() {
    console.log(33311113);
  },
})
export default class AboutView extends Vue {}
</script>
