<template>
  <header class="container">
      <div class="header-sx">
          <img src="../assets/img/dc-logo.png" alt="logo-dc">
      </div>
      <div class="header-dx">
          <ul>
              <li><a href="">characters</a></li>
              <li><a class="active" href="">comics</a></li>
              <li><a href="">movies</a></li>
              <li><a href="">tv</a></li>
              <li><a href="">games</a></li>
              <li><a href="">collectibles</a></li>
              <li><a href="">videos</a></li>
              <li><a href="">fans</a></li>
              <li><a href="">news</a></li>
              <li><a href="">shop</a></li>
          </ul>
      </div>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    @import "../assets/scss/partials/_variables.scss";

    header {
    height: 7em;
    display: flex;
    padding: 0;
        .header-sx {
            width: 30%;
        }
        .header-dx {
            width: 70%;
            align-items: center;
            justify-content: end;
            display: flex;
        }
    }
    ul {
        display: flex;
        li {
            display: flex;
            list-style-type: none;
            a {
                text-decoration: none;
                text-transform: uppercase;
                font-weight: bold;
                color: black;
                padding: 2.9em 0;
                margin: 0 1em;
            }
            .active {
                color: $blueDcomics;
                border-bottom: 3px solid $blueDcomics;
            }
        }
    }
</style>