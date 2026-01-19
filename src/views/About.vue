`2<template>
  <div style="margin-bottom: 80px;">
    <h1>Welcome!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Niks</strong>, an aspiring Game Developer and Game Designer.<br/>
        I spend my days playing video games, learning Game Development, and Music Creation.
      </div>

      <div style="margin-top: 20px;">I've worked on  <router-link to="/game-projects">stuff</router-link>, on <router-link to="/other-projects">other stuff</router-link>, and took part in <router-link to="/resume">a few things</router-link> as well.</div>

      <div style="margin-top: 40px;">I'm <strong>currently looking for a job</strong> as a Game Developer, Game Tester, or Game Designer. You can reach me at <a href="mailto:ragudopaulnikko@gmail.com">ragudopaulnikko@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/niks.png" alt="Avatar of Niks" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>