<script>
import Apptitle from './components/Apptitle.vue';
import Apphero from './components/Apphero.vue';
export default {
  data() {
    return {
      name: 'gioele',
    }
  },
  components: { Apptitle, Apphero, },
}
</script>

<template>
  <Apptitle />

  <Apphero />
</template>

<style>
h1 {
  text-align: center;
  margin-top: 10px;
  color: red;
}

.my-img {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>