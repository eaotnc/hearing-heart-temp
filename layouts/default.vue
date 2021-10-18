<template>
  <div class="default-layout">
    <div class="top-section">
      <div class="top-left">
        <div class="left-item">
          Platform สร้างนักฟังเชิงลึกแห่งประเทศไทย
        </div>
        <div class="left-item">นักฟังเชิงลึกคืออะไร</div>
        <div class="left-item">สำหรับองค์กร</div>
      </div>
      <div class="top-user-info">
        Thanatcha@gmail.com
      </div>
    </div>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </div>
</template>

<script>
export default {
  name: "default-layout",
  data() {
    return {};
  }
};
</script>
<style lang="scss" scoped>
div,
h1,
h2,
h3,
h4,
input,
textarea,
button,
span,
label,
p,
a {
  font-family: "Prompt", sans-serif !important;
}

.top-section {
  display: flex;
  justify-content: space-between;
}
.top-left {
  display: flex;
  justify-content: space-between;
  font-size: 14px;
  margin: 5px;
  color: rgb(63, 63, 63);
  cursor: pointer;
  text-decoration: underline;
}
.left-item {
  margin: 10px;
}
.top-user-info {
  display: flex;
  padding: 10px;
  width: 320px;
  height: 50px;
  background-color: #eca986;
  border-radius: 0 0 0 10px;
}
</style>
