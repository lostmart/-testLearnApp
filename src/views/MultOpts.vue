<template>
  <div class="container">
    <h2>Mult questions</h2>
    <h3>{{ exData.question }}</h3>
    <ul>
      <li>
        <button>en la panaderia</button>
      </li>
    </ul>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "MultOptions",
  components: {},
  setup() {
    const exData = {
      question: "donde esta la panaderia?",
    };
    return { exData };
  },
});
</script>

<style scoped>
ul {
  margin-top: 1em;
}
</style>