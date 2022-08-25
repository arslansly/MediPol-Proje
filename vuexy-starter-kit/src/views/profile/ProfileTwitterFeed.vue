<template>
  <div class="demo-inline-spacing">
    
    <b-button variant="relief-primary">
    
      Doktor SÜLEYMAN
    </b-button>
    <b-button variant="relief-secondary">
      Doktor DİLAN
    </b-button>
    <b-button variant="relief-success">
      Doktor Clodia
    </b-button>
    
  </div>
</template>

<script>
import { BButton } from 'bootstrap-vue'
import ButtonGroupSize from '@/views/components/button-group/ButtonGroupSize.vue';

export default {
  components: {
    BButton,
    ButtonGroupSize
},
}
</script>