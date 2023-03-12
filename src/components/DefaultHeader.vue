<template>
  <ul class="navbar">
    <li class="list-inline-navbar"><a class="active" href="#home">Home</a></li>
    <li class="list-inline-navbar"><a href="#news">News</a></li>
    <li class="list-inline-navbar"><a href="#contact">Contact</a></li>
    <li class="list-inline-navbar"><a href="#about">About</a></li>

    <li class="list-inline-navbar2"><a class="active" href="#home">Home</a></li>
    <li class="list-inline-navbar2"><a href="#news">News</a></li>
    <li class="list-inline-navbar2"><a href="#contact">Contact</a></li>
    <li class="list-inline-navbar2"><a href="#about">About</a></li>
  </ul>
  <ul class="navbar2"></ul>
</template>

<script>
export default {
  name: "DefaultHeader",
};
</script>
<style>
* {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: transparent;
}
.searchIcon {
  top: 1%;
}
.navbar .search-container {
  position: fixed;
  left: 40%;
  top: -3.5%;
}

.navbar input[type="text"] {
  padding: 6px;
  margin-top: 8px;
  font-size: 17px;
  border: none;
  color: #ccc;
}

.navbar .search-container button {
  float: center;
  padding: 6px 10px;
  margin-top: 8px;
  margin-right: 16px;
  background: #333;
  font-size: 17px;
  border: none;
  cursor: pointer;
}

.navbar .search-container button:hover {
  background: #333;
}

@media screen and (max-width: 600px) {
  .navbar .search-container {
    float: none;
  }
  .navbar a,
  .navbar input[type="text"],
  .navbar .search-container button {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  .navbar input[type="text"] {
    border: 1px solid #ccc;
  }
}
.navbar {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}
.navbar2 {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}
.list-inline-navbar {
  float: left;
}
.list-inline-navbar2 {
  float: right;
}

.list-inline-navbar a {
  display: block;
  color: #ccc;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
.list-inline-navbar2 a {
  display: block;
  color: #ccc;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
.navbar a:hover {
  background-color: #333;
}
</style>
