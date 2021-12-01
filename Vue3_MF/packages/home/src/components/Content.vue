<template>
  <div>
    <div>Client text: {{ text }}</div>
    <div style="color: red;">{{ title }}</div>
  </div>
</template>
<script>
export default {
  props: {
    text: {
      type: String
    }
  },
  data() {
    return {
      title: "Remote Component in Action..",
    };
  },
};
</script>
