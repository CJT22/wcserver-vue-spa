<template>
    <div id="profile">
        <h2>{{ msg }}</h2>

        <div id="title">
            <img src="./assets/my_photo.jpg" alt="Picture of Chester Tayag">

            <h1>Chester Jonathan Tayag</h1>
            <h2 id="no-bottom">Bachelor of Science in Information Technology</h2>
            <h2 id="no-top">with Area of Specialization in Web Development</h2>

        </div>

        <br>

        <h3>My Objective:</h3>
        <p>"To become a prominent web developer, always learning, improving</p>
        <p>one's craft, and adapting to the ever-shifting tides of technology."</p>
    </div>
</template>

<script>
    export default {
        name: 'profile',
        data () {
            return {
                msg: 'Welcome to my resumé! My name is...'
            }
        }
    }
</script>

<style>
    #title {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 0;
    }

    img {
        margin-top: 30px;
        border-radius: 50px;
        max-width: 350px;
        transition: 0.3s;
    }

    img:hover {
        transform: scale(1.05);
        box-shadow: 5px 5px rgba(0, 0, 0, 0.4);
    }

    h1 {
        margin: 15px;
        font-size: 2.5rem;
    }

    #no-bottom {
        margin-bottom: 0;
    }

    #no-top {
        margin-top: 0;
    }
</style>