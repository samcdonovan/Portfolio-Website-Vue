<template>

  <div id="img-me">
    <img src="../assets/bg-me-new.png" ALT="Image of me saying 'Hey there! I'm Sam and you've stumbled across my portfolio website'"/>

  </div>
  <div id="home-info">
    <p>Aspiring Software Engineer looking for a role in one of these fields:
      
      <ul>
      <li>Backend Developer</li>
      <li>Full Stack Developer</li>
      <li>Artificial Intelligence</li>
      </ul>
      </p>
  </div>

</template>

<script>
export default {
  name: "HomePage",
};
</script>

<style scoped>
#app {
  padding-bottom: 0vh;
  margin-bottom: 0vh;
}
#home-info {
  position: absolute;
  width: 38%;
  height: fit-content;
  float: right;
  border-style: solid;
  border-radius: 5px;
  text-align: left;
  padding: 1%;
  right: 5%;
  bottom: -15%;
  background-color: var(--nav-bg);
}

#img-me {
  position: relative;
  width: 100%;
  float: left;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: -10%;
}
#img-me img {
  position: relative;
  width: 70%;
  height: 70%;
}
@media (max-width: 960px) {
  #home-info {
    position: relative;
    width: 80%;
    height:fit-content;
    float: right;
    border-style: solid;
    border-radius: 5px;
    text-align: left;
    padding: 1%;
    bottom:-50px;
  }
  #img-me img {
    height: 100%;
    width: 95%;
  }
  #img-me {
    padding-bottom: 5%;
  }
}

</style>
