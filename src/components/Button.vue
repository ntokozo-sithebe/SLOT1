<template>
    <div>
        <button class="mybtn"> 
            <slot name="click"></slot>
        </button>
        <div>
            <button>
                <slot name="logo"> </slot>
            </button>
        </div>
        

    </div>
</template>

<script>
    export default {
        name: 'ButtonComp'
    }
</script>

<style scoped>

</style>