<template>
  <div>
    <h3>Welcome {{name}}!</h3>
    <p>Gender: {{gender}}</p>
    <p>Position: {{position}}</p>
  </div>
</template>

<script>
export default {
  name: "Playground",
  data: function () {
    return {
      name: "Rajendra",
      gender: "Male",
      position: "Senior Developer",
    };
  },
}
</script>

<style scoped>

</style>
