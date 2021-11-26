<template>
  <footer>
    <div class="footer">
      <div class="about-us">
        <div>
          <h5 class="fw-600">About Us</h5>
        </div>
        <div>
          <h5 class="fw-600">Privacy Policy</h5>
        </div>
        <div>
          <h5 class="fw-600">Contact Us</h5>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  min-height: 60px;
  background: white;
  display: flex;
  justify-content: end;
  padding-top: 17px;
}
.about-us {
  display: flex;
  width: 500px;
  justify-content: space-evenly;
}
.fw-600 {
  font-weight: 600;
}
</style>
