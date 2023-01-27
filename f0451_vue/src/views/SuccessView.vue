<template>
    <div class="page-success">
        <div class="columns is-multiline">
            <div class="column is-12">
                <h1 class="title">Thank you</h1>
                <p>Open your e-mail</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SuccessView',
    mounted() {
        document.title = 'Success'
    },
}
</script>