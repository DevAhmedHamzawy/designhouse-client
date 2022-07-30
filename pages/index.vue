<template>

  <div>
      <navigation />
      <div class="wapper">

      </div>
      <thefooter />
  </div>
  

</template>

<script>
import navigation  from './layouts/header.vue'
import thefooter from "./layouts/footer.vue";

export default {
  components: { navigation, thefooter },
  name: 'IndexPage',
 
}
</script>
