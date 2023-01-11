<template>
  <div>
    <h1>Get Badge From Github</h1>
    <form @submit.prevent="sendForm">
      <div class="field-wrapper">
        <label>Input Name Repository</label>
        <input type="text" placeholder="Repository" />
      </div>
      <button>Submit</button>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  methods: {
    sendForm() {},
  },
};
</script>

<style scoped></style>
