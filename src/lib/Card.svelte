<script lang="ts">
let src = "/src/assets/image-qr-code.png"
</script>

<div>
<img {src} alt="qr code">
  <h1>Improve your front-end skills by building projects.</h1>
<p>
  Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
</p>

</div>

<style lang="scss">
   @use "../styles/template" as template;
img {
  
}
  div {
 min-width: 60%;
  max-width: 60%;
  height: 50%;
  background-color: template.$wh;
  border-radius: 10px
}
  
  p {
  font-size: 15px;
  }
  h1 {
  font-size: 18px
  }
</style>