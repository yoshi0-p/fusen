<template>
 <div class="header flex">
   <div class="flex">
     <p @click="$router.push('/signup')">新規登録</p>
     <p>|</p>
     <p @click="$router.push('/')">ログイン</p>
   </div>
 </div>
</template>

<style scoped>

.header {
 margin: 20px;
  text-align:center;
}
.logo {
 width: 150px;
 cursor: pointer;
}
.flex {
 display: flex;
 justify-content: space-between;

}
</style>