<template>
  <div class="bg-black py-4">
    <div class="container mx-auto flex justify-between items-center">
      <div>
        <img class="w-24 h-24" src="../assets/logo.png" alt="logo" />
      </div>
      <ul class="text-white flex gap-x-6 text-2xl">
        <li class="cursor-pointer hover:border-b hover:border-b-white">О нас</li>
        <li class="cursor-pointer hover:border-b hover:border-b-white">Контакты</li>
        <li class="cursor-pointer hover:border-b hover:border-b-white">Адрес</li>
      </ul>
      <div class="flex text-white text-2xl gap-x-6">
        <button @click="showModal = true">Войти</button>
        <button @click="showModal2 = true">Зарегистрироваться</button>
      </div>
    </div>
    <div class="modal-vue">
  <!-- overlay -->
  <div class="overlay" v-if="showModal" @click="showModal = false"></div>
  <!-- modal -->
  <div class="modal text-xl" v-if="showModal">
    <button class="close" @click="showModal = false">x</button>
    <div class="flex my-4"><span>Введите логин:</span> <input v-model="Login" class="border" type="text"></div>
    <div class="flex my-4"><span>Введите пароль:</span> <input v-model="Password" class="border" type="text"></div>
    <button @click="checkUser" class="float-right text-white bg-blue-500 py-2 rounded-lg px-4">Войти</button>
  </div>
</div>


<div class="modal-vue">
  <!-- overlay -->
 <div class="overlay" v-if="showModal2" @click="showModal2 = false"></div>

<div class="modal text-xl" v-if="showModal2">
    <button class="close" @click="showModal2 = false">x</button>
    <div class="flex my-4"><span>Введите логин:</span> <input class="border" type="text"></div>
    <div class="flex my-4"><span>Введите пароль:</span> <input class="border" type="password"></div>
    <button class="float-right text-white bg-blue-500 py-2 rounded-lg px-4">Зарегистрироваться</button>
  </div>
</div>
  </div>
</template>

<script setup>
import { useRouter, useRoute } from 'vue-router'
import {ref} from 'vue'

const router = useRouter()
const route = useRoute()
const username = ref('Gel')
const userpassword = ref('Gelas')
const showModal = ref(false)
const showModal2 = ref(false)
const isLoggedIn = ref(false)
const Password = ref('')
const Login = ref('')

const checkUser = () => {
    if(Login == 'ge' && Password == 'ge') {
        console.log('welcome');
    } else{console.log('fsafsa')}
}
</script>

<style scoped>
.modal-vue .overlay {
  position: absolute;
  z-index: 9998;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, .5);
}

.modal-vue .modal {
  position: absolute;
  width: 600px;
  z-index: 9999;
  left: 50%;
  top: 50%;
  transform: translate(-50%,-50%);
  margin: 0 auto;
  height: 300px;
  padding: 20px 30px;
  background-color: #fff;
}

.modal-vue .close{
  position: absolute;
  top: 10px;
  right: 10px;
}
</style>
