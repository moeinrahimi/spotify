<template>
<div class="columns is-gapless">
    <div class="sidebar">
      <div id="sidebar-logo">
        <img src="./assets/spotify-logo.png" alt="">
      </div>
      <div id="sidebar-menu">
        <div class="sidebar-menu-data">
        <i class="fa fa-search"><a class="link" href="">Search</a></i>
        </div>
        <div class="sidebar-menu-data">
        <i class="fa fa-home"><a class="link" href="">Home</a></i>
        </div>
        <div class="sidebar-menu-data">
        <i class="fa fa-book-open"><a class="link" href="">Your Library</a></i>
        </div>
        
        
      </div>
    </div>
    
  <div class="column">
    <div class="main">
      Auto
    </div>
    
    </div>
</div>
</template>

<script>
require('./assets/bulma.css')
export default {
  name: 'app',

}
</script>

<style>
body{
  background-image: linear-gradient(rgb(143, 50, 10), rgb(14, 5, 1) 85%);
}
.sidebar{
  background-color: rgba(0,0,0,.5);
  height:100vh;
  width:220px;
  display: flex;
  flex-direction: column;
  padding:30px;
}
#sidebar-logo{
  width:35px;
  height:35px;
  padding-bottom: 50px;
  /* margin : 10px; */
}
#sidebar-logo img{
  width:35px;
  height:35px;
}
#sidebar-menu{
  display : flex;
  flex-direction: column;
  /* margin : 10px; */

}
.sidebar-menu-data{
  margin-top:5px;

}
.sidebar-menu-data i:hover{
  color:#fff

}
.sidebar-menu-data a{
  margin-left:10px;
}
.sidebar-menu-data i{
  color :hsla(0,0%,100%,.6)
}
.link{
  transition-property: color;
transition-duration: .2s;
transition-timing-function: linear;
color:hsla(0,0%,100%,.6);
}

.main{
  background: red;
}
</style>
