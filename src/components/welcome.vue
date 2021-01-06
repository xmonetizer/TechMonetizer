<template>
  <div id="welcome">
    <p>
      <a href="https://TeamMonetizer.web.app/" title="Team Interests Monetizer"> team </a> 
      <a href="https://SIMonetizer.web.app/" title="Social Interests Monetizer"> social </a>
      <a href="https://TerraMonetizer.web.app/" title="Terra Interests Monetizer"> terra </a>
      <a href="https://devMonetizer.web.app/" title="Devs Interests Monetizer"> dev </a>
      <a href="https://w3Monetizer.web.app/" title="W3 Monetizer"> web </a>
      <a href="https://DevEngineXL.web.app/" title="DevOps XL Engine"> office </a>
      <a href="https://TechMonetizer.web.app/" title="Tech Monetizer"> cloud </a>
      <a href="https://TimeMonetizer.web.app/" title="Time Monetizer"> monetizer </a>
      <a href="https://SprintMonetizer.web.app/" title="Sprint Monetizer"> engine </a>
      </p>
    <h1>monetize @ AI speed</h1>
    <p><span class="red-text">socialize</span> > <span class="yellow-text">innovate</span> > <span class="blue-text">monetize</span> 24/7 - 3rd gen DNA OS</p>
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