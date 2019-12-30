<template>

    <header >
        <div class="d-flex flex-column flex-md-row align-items-center p-3 px-md-4 mb-3 bg-white border-bottom shadow-sm">
        <h5 class="my-0 mr-md-auto font-weight-normal">AddisTodo</h5>
        <nav class="my-2 my-md-0 mr-md-3">
            <a class="p-2 text-dark" href="#">About</a>
        
            <a class="p-2 text-dark" href="#">Support</a>
        </nav>
        <a class="btn btn-outline-primary" href="#">Sign in</a>
    </div>
    </header>
</template>


<script>
export default {
    name: "Header"
}
</script>


<style scoped>
    .header {
        background: #333;
        color: #fff;
        text-align: center;
        padding: 10px;
    }
    .header a {
        color: #fff;
        padding-right: 5px;
        text-decoration: none;
    }
</style>