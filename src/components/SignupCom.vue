<template>

    <h2>Sign Up</h2>
    <div class="register">
        <input type="text" placeholder="Enter Your Name">
        <input type="text" placeholder="Enter Your Email">

        <input type="text" placeholder="Enter Your Password">
        <button>Sign up</button>
    </div>
</template>
<script>
export default {
    name: 'SignUpCom',
}
</script>
<style>
.register input {
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin: 0 auto 30px auto;
    border: 1px solid black;
    /* border: none; */
}

.register button {
    width: 320px;
    height: 40px;
    border: 1px solid skyblue;
    color: white;
    background-color: skyblue;
    cursor: pointer;
}
</style>