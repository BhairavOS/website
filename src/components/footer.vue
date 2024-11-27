<template>
  <footer class="footer-footer">
    <div class="footer-container1">
      <div class="footer-container2">
        <span class="footer-text10">SOFT</span>
        <span>Copyright © 2021 Soft by Creative Tim.</span>
      </div>
      <div class="footer-container3">
        <div class="footer-container4">
          <span class="footer-text12 Large">Company</span>
          <span class="footer-text13 Large">About Us</span>
          <span class="footer-text14 Large">Careers</span>
          <span class="footer-text15 Large">Press</span>
        </div>
        <div class="footer-container5">
          <span class="footer-text16 Large">Pages</span>
          <span class="footer-text17 Large">Login</span>
          <span class="footer-text18 Large">Register</span>
          <span class="footer-text19 Large">About</span>
        </div>
        <div class="footer-container6">
          <span class="footer-text20 Large">Products</span>
          <span class="footer-text21 Large">Free</span>
          <span class="footer-text22 Large">PRO</span>
          <span class="footer-text23 Large">Latest</span>
        </div>
      </div>
    </div>
    <img alt="image" src="/waves-white.svg" class="footer-image" />
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {},
}
</script>

<style scoped>
.footer-footer {
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  background-image: linear-gradient(310deg,#141727,#3a416f);
}
.footer-container1 {
  color: var(--dl-color-gray-white);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-tripleunit);
  z-index: 1;
  max-width: 1320px;
  justify-content: space-between;
}
.footer-container2 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.footer-text10 {
  font-weight: 700;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-container3 {
  display: flex;
  justify-content: space-between;
}
.footer-container4 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.footer-text12 {
  font-weight: 700;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text13 {
  color: var(--dl-color-gray-800);
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text13:hover {
  color: var(--dl-color-gray-white);
}
.footer-text14 {
  color: var(--dl-color-gray-800);
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text14:hover {
  color: var(--dl-color-gray-white);
}
.footer-text15 {
  color: var(--dl-color-gray-800);
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text15:hover {
  color: var(--dl-color-gray-white);
}
.footer-container5 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  margin-left: var(--dl-space-space-sixunits);
  flex-direction: column;
}
.footer-text16 {
  font-weight: 700;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text17 {
  color: var(--dl-color-gray-800);
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text17:hover {
  color: var(--dl-color-gray-white);
}
.footer-text18 {
  color: var(--dl-color-gray-800);
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text18:hover {
  color: var(--dl-color-gray-white);
}
.footer-text19 {
  color: var(--dl-color-gray-800);
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text19:hover {
  color: var(--dl-color-gray-white);
}
.footer-container6 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  margin-left: var(--dl-space-space-sixunits);
  flex-direction: column;
}
.footer-text20 {
  font-weight: 700;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text21 {
  color: var(--dl-color-gray-800);
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text21:hover {
  color: var(--dl-color-gray-white);
}
.footer-text22 {
  color: var(--dl-color-gray-800);
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text22:hover {
  color: var(--dl-color-gray-white);
}
.footer-text23 {
  color: var(--dl-color-gray-800);
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-halfunit);
}
.footer-text23:hover {
  color: var(--dl-color-gray-white);
}
.footer-image {
  top: 0px;
  left: auto;
  right: 0px;
  width: 100%;
  height: 100%;
  opacity: 0.7;
  position: absolute;
  object-fit: cover;
}
@media(max-width: 991px) {
  .footer-container1 {
    padding: var(--dl-space-space-doubleunit);
  }
}
@media(max-width: 767px) {
  .footer-container1 {
    flex-direction: column;
  }
  .footer-container2 {
    align-items: center;
    margin-bottom: var(--dl-space-space-doubleunit);
  }
  .footer-container5 {
    margin-left: var(--dl-space-space-doubleunit);
  }
  .footer-container6 {
    margin-left: var(--dl-space-space-doubleunit);
  }
}
</style>
