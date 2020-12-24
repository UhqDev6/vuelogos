<template>
    <div class="logos-wrapper">
        <h2 class="title-header">This Logos</h2>
        <div class="item-logos">
            <img class="item-logo" src="../assets/google-seeklogo.com.svg" alt="Google">
        </div>
         <div class="item-logos">
            <img class="item-logo" src="../assets/gmail.svg" alt="Google">
        </div>
         <div class="item-logos">
            <img class="item-logo" src="../assets/drive.svg" alt="Google">
        </div>
         <div class="item-logos">
            <img class="item-logo" src="../assets/google-seeklogo.com.svg" alt="Google">
        </div>
         <div class="item-logos">
            <img class="item-logo" src="../assets/gmail.svg" alt="Google">
        </div>
         <div class="item-logos">
            <img class="item-logo" src="../assets/drive.svg" alt="Google">
        </div>
    </div>
</template>

<script>
export default {
    name : 'Logos'
}
</script>


<style scoped>
    .title-header {
        margin-bottom: 80px;
        text-align: left;
    }
    .logos-wrapper {
        width : 66%;
        overflow:hidden;
        margin : auto;
    }

    .item-logos {
        width: 150px;
        height: 150px;
        float: left;
        margin-right: 70px;
        margin-bottom: 70px;
    }

    .item-logo {
        height: 150px;
        width: 150px;
    }
</style>