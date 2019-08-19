<template>
    <div>
        <button class="btn" :class="color">
            {{name}}
        </button>
    </div>
</template>

<script>
export default {
    props: {
        name: {
            type: String,
            required: true
        },
        color: {
            type: String,
            required: true
        },
    }
}
</script>

<style>
.btn {
    width: 150px;
    height: 50px;
    outline: none;
}
</style>

