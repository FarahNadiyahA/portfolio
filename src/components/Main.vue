<template>
  
  <div class="hero">
    <!-- <img class="background" src="@/assets/img/background.svg" />  Shadows version -->
    <div></div>
    <div class="hero__container">
      <div class="hero__main">
        <h5 class="hero__title">Farah Nadiyah Aulia</h5>
        <h3 class="hero__sub-title">Teknologi Informasi-Universitas Brawijaya</h3>
        <a
          class="hero__btn"
          href="mailto:farahaulianad@gmail.com"
          subject="subject text"
          target="__blank"
          title="Farah Nadiyah e-mail"
          >Message Me</a
        >
        <h3 class="hero__sub-title"></h3>
        <h3 class="hero__sub--title">I'm Farah Nadiyah Aulia, UI/UX Designer. 
          I'm specialist in UI design and UX writing. 
          I can managing day to day team operation with considerable experience to read trends. </h3>
      </div>
      <div class="hero__footer">
        <li class="hero__links">
          <!--
          <ul>
            <a
              class="hero__link"
              href="https://drive.google.com/file/d/1JMHQ70LbFCwserHUpR5q7XoI68ul7MFv/view"
              target="__blank"
              title="Farah Nadiyah Resume"
              >Resume</a
            >
          </ul>
          -->
          <ul>
            <a
              class="hero__link"
              href="https://github.com/FarahNadiyahA"
              target="__blank"
              title="Farah Nadiyah GitHub"
              >Github</a
            >
          </ul>
          <ul>
            <a
              class="hero__link"
              href="https://www.linkedin.com/"
              target="__blank"
              title="Farah Nadiyah LinkedIn"
              >LinkedIn</a
            >
          </ul>
          
        </li>
        <div class="hero__copyright">© 2023 Farah Nadiyah Aulia</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
  components: {},
};
</script>

<style scoped>
.background {
  position: absolute;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.hero__container {
  background: radial-gradient(circle at top left, #000000, transparent), 
              radial-gradient(circle at top right, #000000, transparent), 
              radial-gradient(circle at bottom, #000000, transparent),
              #90bde4;
  display: flex;
  justify-content: space-between;
  flex-direction: column;
  position: relative;
  max-width: 1480px;
  height: 100vh;
  margin: 0px auto;
  padding: 0px 20px 0px 20px;
}
.hero__main {
  max-width: 678px;
  width: 100%;
  margin: 0 auto;
  padding-top: 8%;
  display: flex;
  flex-direction: column;
  text-align: center;
  align-items: center;
}
.hero__title {
  font-size: 64px;
  font-weight: 700;
  line-height: 91px;
}
.hero__sub-title {
  background: linear-gradient(45deg, #6202fd, #00ffff, #f700ff);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 24px;
  font-weight: 400;
  line-height: 45px;
  padding-top: 10px;
}
.hero__sub--title {
  
  font-size: 18px;
  font-weight: 400;
  line-height: 45px;
  padding-top: 10px;
}
.hero__btn {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 120px;
  height: 40px;
  background-color: #385486e3;
  border-radius: 8px;
  color: #fff;
  font-size: 14px;
  margin: 48px auto 0px;
}
.hero__btn:hover {
  opacity: 0.8;
  transition: 0.5s;
}
.hero__footer {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin-bottom: 30px;
  max-height: 200px;
  height: 100%;
}
.hero__links {
  display: flex;
  margin: auto;
  max-width: 536px;
  width: 100%;
  justify-content: space-between;
  font-size: 20px;
  line-height: 18px;
  font-weight: 400;
}
.hero__link:hover {
  transition: 0s;
  font-weight: 700;
}
.hero__copyright {
  font-size: 10px;
  margin: auto;
  margin: 0 auto;
}
@media (max-width: 707px) {
  .hero__main {
    padding-top: 50px;
  }
}
@media (max-width: 555px) {
  .hero__main {
    padding-top: 40px;
  }
  .hero__title {
    line-height: 70px;
  }
  .hero__title {
    font-size: 65px;
    line-height: 60px;
  }
  .hero__sub-title {
    font-size: 26px;
  }
  .hero__btn {
    margin: 40px auto 70px;
  }
}
@media (max-width: 480px) {
  .hero__title {
    font-size: 45px;
    line-height: 40px;
  }
  .hero__btn {
    margin-bottom: 40px;
  }
  .hero__links {
    flex-direction: column;
    align-items: center;
    gap: 15px;
  }
  .hero__copyright {
    font-size: 8px;
    margin-top: 25px;
  }
}
</style>