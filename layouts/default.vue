<template>
    <div>
        <Navbar />
        <router-view></router-view>
    </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
export default {
  name: 'DefaultLayout',
  components: {Navbar},
  data () {
    return {

    }
  }
}
</script>
