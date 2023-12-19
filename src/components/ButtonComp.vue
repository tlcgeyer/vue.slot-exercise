
<template>
    <button class="btn btn-dark mx-5">
        <slot name="deText"></slot>
    </button>

    <button class="btn btn-dark" >
        <slot name="deClick"></slot>
    </button>
</template>

<script>

export default {
    name : 'ButtonComp'
}
</script>

