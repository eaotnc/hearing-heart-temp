<template>
  <div>
    <div class="top-section">
      <div class="top-text">
        ร่วมสมัครเป็นนักฟังเชิงลึก
        <br />
        ร่วมพัฒนาสัมคมให้น่าอยู่ไปกับเรา
        <div class="top-bt">
          เกี่ยวกับ Course
        </div>
      </div>

      <div class="interesting">
        <div class="header">
          คุณกำลังสนใจอะไรอยู่?
        </div>
        <div class="card-group">
          <div class="interesting-card">
            <div class="text">
              สนใจเป็นนักฟังเชิงลึก
            </div>
            <div class="botton">
              สมัครเป็นนักฟังเชิงลึก
            </div>
          </div>
          <div class="interesting-card">
            <div class="text">
              สนใจเป็นผู้ระบายปัญหา
            </div>
            <div class="botton">
              เริ่มต้นระบายปัญหาสกับเรา
            </div>
          </div>
          <div class="interesting-card">
            <div class="text">
              สงสัยว่าจะเป็นผู้ป่วยจิตเวช
            </div>
            <div class="botton">
              เริ่มต้นทดสอบเลย
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="new-users-section">
      <div class="topper">
        <div class="header">
          นักฟังเชิงลึกในระบบของเรา
        </div>
        <div class="about-bt">
          เกี่ยวกับนักฟังเชิงลึก
        </div>
      </div>
      <div class="user-group">
        <div class="user-card">
          <div class="name">
            Eao Thanatcha
          </div>
          <div class="rating">
            53 rating
          </div>
        </div>
        <div class="user-card">
          <div class="name">
            Eao Thanatcha
          </div>
          <div class="rating">
            53 rating
          </div>
        </div>
        <div class="user-card">
          <div class="name">
            Eao Thanatcha
          </div>
          <div class="rating">
            53 rating
          </div>
        </div>
        <div class="user-card">
          <div class="name">
            Eao Thanatcha
          </div>
          <div class="rating">
            53 rating
          </div>
        </div>
        <div class="user-card">
          <div class="name">
            Eao Thanatcha
          </div>
          <div class="rating">
            53 rating
          </div>
        </div>
      </div>
    </div>

    <div class="user-count">
      <div class="header">
        ระบบนิเวศของเรา
      </div>
      <div class="count-group">
        <div class="count-item">
          <div class="number">
            5,122
          </div>
          <div class="text">
            สมาชิกในระบบ
          </div>
        </div>
        <div class="count-item">
          <div class="number">
            612
          </div>
          <div class="text">
            นักฟังในระบบ
          </div>
        </div>
        <div class="count-item">
          <div class="number">
            13,221
          </div>
          <div class="text">
            การสนทนา
          </div>
        </div>
      </div>
    </div>
    <div class="blog">
      <div class="header-blog">
        <div class="header">
          บทความของเรา
        </div>
        <div class="right-bt">
          ดูเพิ่มเติม
        </div>
      </div>

      <div class="blog-section">
        <div class="blog-item">
          <div class="header">
            บทความ
          </div>
          <div class="desc">
            rorem Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Cupiditate alias nihil commodi. Dolore, eaque dolorem. Omnis
          </div>
        </div>
        <div class="blog-item">
          <div class="header">
            บทความ
          </div>
          <div class="desc">
            rorem Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Cupiditate alias nihil commodi. Dolore, eaque dolorem. Omnis
          </div>
        </div>
        <div class="blog-item">
          <div class="header">
            บทความ
          </div>
          <div class="desc">
            rorem Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Cupiditate alias nihil commodi. Dolore, eaque dolorem. Omnis
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "homepage"
};
</script>
<style lang="scss" scoped>
.botton {
  cursor: pointer;
}
.top-section {
  position: relative;
  width: 100%;
  background: rgb(224, 134, 134);
  color: white;
  height: 470px;
}
.top-text {
  padding-top: 200px;
  text-align: center;
  font-size: 25px;
  font-weight: 500;
}
.top-bt {
  margin: auto;
  margin-top: 20px;
  width: fit-content;
  padding: 15px 20px;
  height: 60px;
  border-radius: 40px;
  background: rgb(240, 206, 163);
  font-size: 18px;
  cursor: pointer;
}
.interesting {
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
  position: absolute;
  bottom: -400px;
  max-width: 1100px;
  padding: 20px;
  background: #fff;
  border-radius: 10px;
  color: black;
  box-shadow: 0px 8px 31px -15px rgba(0, 0, 0, 0.37);

  .header {
    font-weight: 500;
    font-size: 25px;
    margin: 10px;
    text-align: center;
  }
  .card-group {
    display: flex;
    justify-content: center;
  }
  .interesting-card {
    width: 320px;
    height: 350px;
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
    background: rgb(253, 214, 141);
    box-shadow: 0px 8px 31px -15px rgba(0, 0, 0, 0.37);

    .text {
      text-align: center;
      color: white;
      font-size: 20px;
      margin: 20px;
    }
    .botton {
      text-align: center;
      padding: 20px;
      background: white;
      color: black;
      width: 100%;
      height: 60px;
      border-radius: 30px;
    }
  }
}

.new-users-section {
  max-width: 1100px;
  padding: 20px;
  margin: auto;
  margin-top: 400px;

  .topper {
    display: flex;
    justify-content: space-between;
    .header {
      padding-top: 10px;
      font-size: 25px;
      font-weight: 500;
    }
    .about-bt {
      width: fit-content;
      height: 50px;
      padding: 10px 20px;
      color: white;
      font-size: 18px;
      background: pink;
      border-radius: 40px;
    }
  }
  .user-group {
    display: flex;
    justify-content: space-evenly;
  }
  .user-card {
    width: 200px;
    height: 200px;
    margin: 20px;
    box-shadow: 0px 8px 31px -15px rgba(0, 0, 0, 0.37);
    text-align: center;
    .name {
      font-size: 18px;
      font-weight: 500;
    }
    .rating {
      font-size: 18px;
    }
  }
}

.user-count {
  max-width: 1100px;
  height: 300px;
  margin: auto;
  padding: 30px;
  border-radius: 10px;
  background-image: url("../static/userCount.jpg");
  background-position: 50% 50%;
  background-size: cover;
  color: white;
  .header {
    font-size: 28px;
    text-align: center;
  }
  .count-group {
    display: flex;
    justify-content: space-between;
    padding-top: 50px;
  }
  .count-item {
    text-align: center;
    width: 150px;
    margin: 30px;
    .text {
      font-size: 18px;
    }
    .number {
      font-size: 45px;
    }
  }
}

.blog {
  max-width: 1100px;
  margin: auto;
  padding-top: 20px;

  .header-blog {
    display: flex;
    justify-content: space-between;
    .header {
      font-weight: 500;
      font-size: 25px;
    }
    .right-bt {
      width: fit-content;
      padding: 10px 20px;
      height: 50px;
      border-radius: 40px;
      background: rgb(240, 206, 163);
      font-size: 18px;
      cursor: pointer;
      color: white;
    }
  }

  .blog-section {
    display: flex;
    justify-content: space-evenly;
    .blog-item {
      padding: 20px;
      margin: 10px;
      width: 320px;
      height: 400px;
      border-radius: 10px;
      box-shadow: 0px 8px 31px -15px rgba(0, 0, 0, 0.37);
      .header {
        font-size: 20px;
        font-weight: 20px;
      }
      .desc {
        font-weight: 200;
        font-size: 18px;
      }
    }
  }
}
.footer {
  width: 100%;
  background: #484848;
  margin-top: 40px;

  .footer-group {
    max-width: 1100px;
    display: flex;
  }
  .link-group {
  }
}
</style>
