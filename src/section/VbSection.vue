<template lang="html">
    <section :class="classes">
        <slot></slot>
    </section>
</template>

<script>
export default {
    props: {
    },
    computed: {
        classes() {
            return {
                'section': true,
            }
        }
    }
}
</script>

<style lang="css">
</style>
