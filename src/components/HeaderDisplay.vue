<template>
  <header class="header">
    <h2>Weather Application</h2>
    <p>{{ username }}님 반갑습니다.</p>
  </header>
</template>

<script>
export default {
  name: "HeaderDisplay",
};
</script>

<style scoped>
.header {
  background: linear-gradient(15deg, #8e2de2, #4a00e0);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1em;
}
.header h2 {
  color: #ffffff;
}
.header p {
  font-size: 12px;
  color: #ffffff;
}
</style>
