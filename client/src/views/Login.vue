<template>
  <div>
    <Login/>
  </div>
</template>

<script>

import Login from '@/components/Home.vue'

export default {
  name: 'login',
  components: {
    Login
  },
  // created: function () {
  //   const len = localStorage.length
  //   if (len !== 1) {
  //     let users = JSON.parse(localStorage.user).status
  //     if (users === 'success') {
  //       this.$router.push('/account')
  //     } else {
  //       this.$router.push('/login')
  //     }
  //   } else {
  //     this.$router.push('/login')
  //   }
  // }
}
</script>
