<script lang="ts">


</script>


<nav class="nav">
  <ul>
    <li class="title"><strong >HaatyMeal</strong></li>
  </ul>
  <ul>
    <li><a href="/register">Register</a></li>
    <!-- <li><a href="#">Link</a></li> -->
    <li><a class="button" href="/login" role="button">Login</a></li>
  </ul>
</nav>

<slot></slot>

<!-- <footer>
  <h1>
    copywrite @Keilatechnologies
  </h1>
</footer> -->


<style lang="scss">
  @import '../styles/app.scss';

  nav{
    padding: 0 16px;
    background-color: black;

    a{
      color: $text2;
    }

    a.button{
      background-color: $text1;
      color: #000;
      border: none;
    }

    li.title{
      color: #fff;
      font-weight: bold;
      font-size: 25px;
      color: $text1; 
    }
}

// footer {
//     position: fixed;
//     left: 0;
//     bottom: 0;
//     width: 100%;
//     height: 50px;
//     background-color: #000;
//     color: white;
//     text-align: center;
// }


</style>