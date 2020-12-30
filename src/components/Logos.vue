<template>
    <div class="logos-wrapper ">
        <h2 class="title-header">Find Best Logo</h2>
        <div class="item-logos">
            <img class="logo" alt="SB logo" src="../assets/sb.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Google logo" src="../assets/google.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Ms logo" src="../assets/ms.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="SB logo" src="../assets/sb.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Google logo" src="../assets/google.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Ms logo" src="../assets/ms.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="SB logo" src="../assets/sb.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Google logo" src="../assets/google.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Ms logo" src="../assets/ms.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="SB logo" src="../assets/sb.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Google logo" src="../assets/google.png">
        </div>
        <div class="item-logos">
            <img class="logo" alt="Ms logo" src="../assets/ms.png">
        </div>
    </div>
</template>

<script>
export default {
  name: 'Logos',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.title-header {
    margin-bottom: 80px;
    text-align: left;
}
.logos-wrapper {
    width: 62%;
    overflow: hidden;
    margin: auto;
}

.item-logos {
    float: left;
    margin-right: 70px;
    margin-bottom: 70px;
    width: 150px;
    height: 150px;
}

.item-logos .logo {
    width: 150px;
    height: 150px;
}
</style>