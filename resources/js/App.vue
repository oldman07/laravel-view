<template>
    <h1>hi from vue 3</h1>
    <Hello />
</template>

<script>

import Hello from './components/Hello.vue';

export default {
    name: 'App',
    components: {Hello}
}
</script>