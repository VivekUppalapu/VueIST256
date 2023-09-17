<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div>
  <div class="wrap">
    <div class="container">
      <div class="header">
        <h3> THE MCU </h3>
      </div>
      <img class="image" src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwallpapercave.com%2Fwp%2Fwp4884720.png&f=1&nofb=1&ipt=b86f47823ab6a8f5936b05270477294e1a27ee2b3b934a7789d434a72869fb8a&ipo=images">
      <div class="descrip">
        <p> Growing up, I was a huge MCU fan. I watched all of the movies, some more than others, and I think that the picture that sums up how I feel about it is this one, which is the final battle in Endgame. I just felt pure joy seeing all these characters together.</p>
      </div>
      <button class="Detail">
        Details</button>
    </div>
  </div>
      <div class="allbtns">
        <button class="duplicateBtn"> Duplicate Card</button>
        <button class="changeBckgrnd"> Change Background </button>
        <button class="ChangeTitle"> Change Title</button>
        <button class="Delcrd"> Delete Card </button>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.wrap{
    width: 400px;
    border: 2.5px solid black;
    background-color: red;
  }
  .image{
    width: 400px;
    
  }
  .header{
     text-align: center;
  }
  .header h3{
    font-size: 40px;
    color: blue;
  }
  .descrip
  {
    font-size: 16px;
    font-weight: bold;
    color: white;
  }
  .allbtns button
  {
    font-size: 15px;
    background-color: white;
    color: teal;
  }
  .Detail
  {
    font-size: 17px;
    color: purple;
    background-color: white;
  }
  
  
</style>
