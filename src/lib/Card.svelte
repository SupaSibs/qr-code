<script lang="ts">
let src = "https://i.imgur.com/yFrM6bt.png"
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
 max-width: 100%;
  min-width: 80%;
  max-height: 70%;
}
  div {
 min-width: 30%;
  max-width: 60%;
  height: 80%;
  padding: 10px;
  background-color: template.$wh;
  border-radius: 10px;

}
    @media screen and (min-width: 530px) and (max-width: 650px) {
  div {
  max-width: 50%
  }
  }
  @media screen and (min-width: 650px) {
  div {
  max-width: 36%
  }
  }
  p {
  font-size: 15px;
  }
  h1 {
  font-size: 18px
  }

</style>