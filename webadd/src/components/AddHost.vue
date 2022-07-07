<template>
  <div id="zabbix">

    <a href="https://thegioididong.com/">
      <img src="../assets/mwg.png" alt="LogoThegioididong">
    </a>
    <h1>Menu Page</h1>
    <div class="input">
      <input type="text" v-model="name" placeholder="Hostname">
      <input type="IP" v-model="IP" placeholder="x.x.x.x">
    </div>
    <!-- <input type="text" v-model="name">
    <input type="IP" v-model="IP" hint="IP Address"> -->
    <div v-show="hint">
      {{ name }}
      {{ IP }}
    </div>
    <button @click="hint = ! hint">An/Hien Input</button>

  </div>
</template>

<script>
export default {
  data(){
    return{
      name: '',
      IP: '',
      hint: true,
    }
  },

}
</script>

<style scoped>

img{
  float:initial; width:200px; height:100px;
}
h1{
  color: #000;
}
button {
  font-weight: bold; font-size: 25px;
}
input{
  font-size: 25px;
}
.hint{
  color: red; font-size: 50px;
}
</style>