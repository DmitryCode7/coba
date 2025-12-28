<template>
    
    <div class="block__active">
        <h3>
            Recent Activity
        </h3>
        <BaseComit></BaseComit>
        <BaseComit></BaseComit>
        <BaseComit></BaseComit>
        <BaseComit></BaseComit>
    </div>
    
    
</template>

<script>
    import BaseComit  from '@/components/BaseComit.vue';

    export default {
        name: 'BaseActivity',
        components: {
            BaseComit
        }
    }
</script>

<style>

    .block__active {
        background-color: #FFFFFF;
        max-width: 400px;
    }

    
</style>