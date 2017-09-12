<template>
<nav class="navbar navbar-toggleable-md navbar-light bg-faded">
  <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <a class="navbar-brand" href="#">Navbar</a>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
       <router-link class="nav-link" :to="{path : '/hello2'}">入口</router-link>
      </li>
      <li class="nav-item">
       <router-link class="nav-link" :to="{path : '/static'}">樣板</router-link>
      </li>
      <li class="nav-item">
       <router-link class="nav-link" :to="{path : '/chatroom'}">聊天室</router-link>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="text" placeholder="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
  <!-- <nav class="navbar navbar-toggleable-md navbar-light bg-faded sticky-top">
    <a class="navbar-brand" href="#">Navbar</a>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <router-link class="nav-link" :to="{ path: '/hello2' }">入口頁面</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" :to="{ path: '/static' }">樣板頁面</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" :to="{ path: '/chatroom' }">聊天室</router-link>
        </li>
      </ul>
    </div>
    
  </nav> -->
</template>

<script>
export default {
  name: 'navbar',
  data() {
    return {
      data: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.sticky-top {
  background-color: #616161;
}
</style>