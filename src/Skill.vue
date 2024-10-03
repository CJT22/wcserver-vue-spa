<template>
    <div id="skill">
        <h3>Personal Skills:</h3>
        <ul>
            <li>- Communication</li>
            <li>- Leadership</li>
            <li>- Problem Solving</li>
        </ul>

        <h3>Web Development Languages:</h3>
        <ul>
            <li>- HTML</li>
            <li>- CSS</li>
        </ul>

        <h3>Other Programming Languages:</h3>
        <ul>
            <li>- Python</li>
            <li>- Java</li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'skill'
}
</script>

<style>
    h3:not(:first-child) {
        margin-top: 20px;
    }

    ul {
        list-style-type: none;
    }

    li {
        margin-top: 10px;
    }
</style>
