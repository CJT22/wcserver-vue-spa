<template>
  <div id="app">
    <profile></profile>
    <div>
      <education></education>
      <skill></skill>
    </div>
  </div>
</template>

<script>
  import Profile from './Profile'
  import Education from './Education'
  import Skill from './Skill'

  export default {
    name: 'app',
    components: {
      Profile,
      Education,
      Skill
    }
  }
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: linear-gradient(to bottom right, #4E65FF, #92EFFD);
    font-family: "Inter", sans-serif;
    font-optical-sizing: auto;
    font-weight: 400;
    font-style: normal;
  }

  #app {
    /* font-family: 'Avenir', Helvetica, Arial, sans-serif; */
    margin: 30px;
    padding: 50px;
    border: solid 5px #020202;
    border-radius: 50px;
    box-shadow: 10px 10px rgba(0, 0, 0, 0.4);
    background-color: #FFFDFA;
    color: #020202;
  }

  div {
    margin-top: 30px;
  }

  p {
    margin-top: 10px;
  }

  @media (orientation: landscape) {
    #app {
      display: flex;
    }

    div {
      margin-top: 0;
    }

    #app > div:not(:first-child) {
      margin-left: 70px;
    }

    h3 {
      margin-top: 20px;
    }
  }
</style>
