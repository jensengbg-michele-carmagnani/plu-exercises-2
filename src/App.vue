<template>
    <main>
        <p> The toggle button: </p>
        <OnOff></OnOff>
        <Counter></Counter>
		<Options></Options>
    </main>
</template>

<script>
import OnOff from './components/onoff/OnOff.vue'
import Counter from './components/counter/Counter.vue'
import Options from './components/options/Options.vue'

export default {
    name: 'App',
    components: {
        OnOff, Counter, Options
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
