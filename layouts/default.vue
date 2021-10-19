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
        <v-icon>fas fa-search</v-icon>
      </div>
    </div>
    <div class="nav-section">
      <nuxt-link to="/">
        <img
          class="main-logo"
          src="../static/hearing-heart-logo.png"
          alt="hearing-heart-logo"
        />
      </nuxt-link>
      <div class="search-box">
        <v-text-field
          solo
          label="ค้นหา..."
          append-icon="mdi-magnify"
        ></v-text-field>
      </div>
      <div class="nav-item-group">
        <nuxt-link to="/" class="nav-item">
          หน้าหนัก
        </nuxt-link>
        <nuxt-link to="/" class="nav-item">เวชพันธมิตร</nuxt-link>
        <nuxt-link to="/" class="nav-item">วาระแห่งชาติ</nuxt-link>
        <nuxt-link to="/" class="nav-item">สื่อ</nuxt-link>
        <nuxt-link to="/" class="nav-item">เกี่ยวกับเรา</nuxt-link>
        <nuxt-link to="/" class="nav-item">บทความ</nuxt-link>
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
  margin: 5px;
  display: flex;
  justify-content: space-between;
  font-size: 14px;
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
  font-weight: 300;
}
.nav-section {
  display: flex;
  height: 90px;
}
.main-logo {
  width: 150px;
  margin: 0 20px;
  margin-top: 15px;
  height: 65px;
}

.search-box {
  padding-top: 20px;
  width: 200px;
}
.nav-item-group {
  display: flex;
  margin-left: auto;
  padding: 20px;
}
.nav-item {
  color: black;
  font-size: 18px;
  text-decoration: none;
  margin: 0 20px;
}
.nav-item:hover {
  color: burlywood;
}
</style>
