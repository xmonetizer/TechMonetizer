<template>
  <div id="welcome">
    <p>
      <a href="https://MetaEngine.web.app/" title="meta engine web app"> meta </a> social cloud 
      <a href="https://TerraDevs.web.app/" title="Terra Devs web app"> terra </a>
      <a href="https://XLrDNA.web.app/" title="xl rDNA web app"> xl </a>
      <a href="https://JSrDNA.web.app/" title="js rDNA web app"> js </a>
      <a href="https://DevEngineXL.web.app/" title="dev engine web app"> devops </a>
      <a href="https://MigrationsPM.web.app/" title="migrations pm web app"> migration </a>
      <a href="https://EngineXL.web.app/" title="engine xl web app"> engine </a>
      </p>
    <h1>engines @ AI speed</h1>
    <p><span class="red-text">develop</span> > <span class="yellow-text">monetize</span> > <span class="blue-text">repeat</span> 24/7 - 3rd gen DNA OS</p>
    <div class="cta">
      <router-link to="/signup">Sign Up</router-link>
      <router-link to="/signin">Sign In</router-link>
    </div>
  </div>
</template>

<style scoped>
.red-text {
  color: red;
}
.yellow-text {
  color: orange;
}
.blue-text {
  color: blue;
}

#welcome {
  width: 80%;
  margin: auto;
}

h1 {
  text-align: center;
}

p {
  text-align: center;
}

.cta {
  width: 300px;
  margin: auto;
  text-align: center;
}

.cta a {
  margin: 10px;
  text-decoration: none;
  display: inline-block;
  border: 1px solid #6aa84f;
  border-radius: 3px;
  width: 100px;
  padding: 10px;
  box-sizing: border-box;
  color: #6aa84f;
}

.cta a:hover,
.cta a:active {
  background-color: #6aa84f;
  color: white;
}
</style>