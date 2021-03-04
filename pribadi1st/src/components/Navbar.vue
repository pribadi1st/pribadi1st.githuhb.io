<template>
    <div class="navbar">
        <div class="navbar-item">
            Home
        </div>
        <div class="navbar-item">
            My Profile
        </div>
        <div class="navbar-item">
            Experience
        </div>
        <div class="navbar-item">
            Contact
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.navbar{
    display: flex;
    flex-direction: row;
    justify-content: flex-end;

    .navbar-item{
        margin: 15px 20px;
    }
}
</style>