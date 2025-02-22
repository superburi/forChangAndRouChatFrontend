<script setup>



</script>
<template>

    <div class="input-wrapper" >
        <input class="input" type="text" placeholder="在這裡輸入訊息..." >
        <button class="submit-message-btn" >傳送</button>     
    </div>

</template>
<style scoped>

    .input-wrapper {
        border: none;
        border-radius: 10px;
        display: flex;
        align-items: center;
        overflow: hidden;
        background-color: #3a3a3a; /* 之前是用 #4d4d4d */
    }

    
    .input {
        
        color: white;
        font-size: medium;
        flex: 0 0 80%;
        height: 100%;
        box-sizing: border-box;
        background-color: transparent;
    }

    .submit-message-btn {

        background-color: #3399FF;
        color: white;
        font-size: medium;
        font-weight: bold;
        flex: 0 0 20%;
        height: 100%;
        border: none;
        border-radius: 10px 0 0 10px;
        box-sizing: border-box;

    }
    

</style>