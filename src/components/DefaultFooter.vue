<template>
  <div class="footer-basic">
    <ul class="list-inline">
      <li class="list-inline-item"><a href="#">For you</a></li>
      <li class="list-inline-item"><a href="#">Movies</a></li>
      <li class="list-inline-item"><a href="#">TV Shows</a></li>
      <li class="list-inline-item"><a href="#">Favorites</a></li>
      <li class="list-inline-item"><a href="#">My List</a></li>
      <li class="list-inline-item"><a href="#">User Settings</a></li>
    </ul>
    <div class="social">
      <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
      <a href="#"><ion-icon name="logo-youtube"></ion-icon></a>
      <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
      <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
    </div>
  </div>
</template>

<script>
export default {
  name: "DefaultFooter",
};
</script>
<style>
ion-icon {
  color: white;
  margin-top: 20%;
}
.footer-basic {
  position: fixed;
  display: flex;
  justify-content: space-around;
  bottom: 0;
  width: 100%;
  padding: 40px 0;
  background-color: #4b4c4d;
  color: white;
}
.list-inline {
  display: flex;
}
.footer-basic ul {
  padding: 0;
  list-style: none;
  text-align: center;
  font-size: 18px;
  line-height: 1.6;
  margin-bottom: 0;
}

.list-inline-item {
  padding: 0 10px;
}

.footer-basic ul a {
  color: inherit;
  text-decoration: none;
  opacity: 0.8;
}

.footer-basic ul a:hover {
  opacity: 1;
  color: white;
}

.footer-basic .social {
  display: flex;
  text-align: center;
  right: 10%;
}

.footer-basic .social > a {
  font-size: 24px;
  width: 40px;
  height: 40px;
  line-height: 40px;
  display: inline-block;
  text-align: center;
  border-radius: 50%;
  border: 1px solid #ccc;
  margin: 0 8px;
  color: inherit;
  opacity: 0.75;
}

.footer-basic .social > a:hover {
  opacity: 0.9;
  color: white;
}
</style>
