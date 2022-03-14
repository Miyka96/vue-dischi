<template>
    <header>

        <div>
            <figure>
                <!-- <img class="logo" src="../assets/img/logo.png" alt=""> -->
            </figure>
        </div>

    </header>
</template>

<script>
    export default {
       name: 'MainHeader',
       
    }
</script>

<style lang="scss" scoped>

header {
    height: 70px;
    background-color: #2E3A46;
    display: flex;
    justify-content: space-between;
    align-items: center;

    .logo {
        margin-left: 20px;
        height:45px;
    }
}

</style>