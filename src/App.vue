<template>
<h1>This is a robo</h1>
<HomePage />
<RobotBuilder />
</template>

<script>
import RobotBuilder from './build/RobotBuilder';
import HomePage from './components/HomePage';

export default {
    name: 'App',
    components: {
        HomePage,
        RobotBuilder
    }
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>

