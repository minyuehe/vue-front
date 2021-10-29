<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your home"/>
    <LoginForm />
    <el-button>默认按钮</el-button>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import LoginForm from '@/components/LoginForm.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    LoginForm
  }
}
</script>
