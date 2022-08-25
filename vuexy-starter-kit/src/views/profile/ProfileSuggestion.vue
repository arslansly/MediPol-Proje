<!-- <template>
  <b-card>
    <h5>Doktorlar</h5>

     user suggestion  
    <div
      v-for="(data,index) in suggestions"
      :key="data.avatar"
      class="d-flex justify-content-start align-items-center"
      :class="index == 0 ? 'mt-2' : 'mt-1'"
    >
      <b-avatar
        :src="data.avatar"
        class="mr-50"
        size="40"
      />
      <div class="user-page-info">
        <h6 class="mb-0">
          {{ data.name }}
        </h6>
        <small class="text-muted">{{ data.mutualFriend }}</small>
      </div>
      <b-button
        v-ripple.400="'rgba(186, 191, 199, 0.15)'"
        variant="primary"
        class="btn-icon ml-auto"
        size="sm"
      >
        <feather-icon icon="UserPlusIcon" />
      </b-button>
    </div>
     user suggestion  
  </b-card>
</template>

<script>
import {
  BCard, BAvatar, BButton,
} from 'bootstrap-vue'
import Ripple from 'vue-ripple-directive'

export default {
  components: {
    BCard,
    BAvatar,
    BButton,
  },
  directives: {
    Ripple,
  },
  props: {
    suggestions: {
      type: Array,
      default: () => [],
    },
  },
}
</script> -->

 
<template>
  <div class="media-list">
    <b-media vertical-align="top">
      <template #aside>
        <b-img
          :src="require('@/assets/images/portrait/small/avatar-s-1.jpg')"
          blank-color="#ccc"
          width="64"
          alt="placeholder"
        />
      </template>
      <h4 class="media-heading">
        Doktor SÜLEYMAN
      </h4>
      <b-card-text class="mb-0">
        Uzman doktor Süleyman ARSLAN, 1978 doğumlu, İstanbul Tıp Fakültesi'nden mezun diyetisyen uzmanımız. Uzmanlık alanı sağlıklı kilo vermek olup, kişiye özel diyet listesi yapmaktadır.
      </b-card-text>
    </b-media>
    <b-media vertical-align="top">
      <template #aside>
        <b-img
          :src="require('@/assets/images/portrait/small/avatar-s-6.jpg')"
          blank-color="#ccc"
          width="64"
          alt="placeholder"
        />
      </template>
      <h4 class="media-heading">
        Doktor DİLAN
      </h4>
      <b-card-text class="mb-0">
        Uzman doktor Dilan SOYLU, 1988 doğumlu, Üsküdar Üniversitesi Tıp Fakültesi'nden mezun diyetisyen uzmanımız. Uzmanlık alanı sağlıklı kilo almak olup, kişiye özel diyet listesi yapmaktadır.
      </b-card-text>
    </b-media>
    <b-media vertical-align="top">
      <template #aside>
        <b-img
          :src="require('@/assets/images/portrait/small/avatar-s-3.jpg')"
          blank-color="#ccc"
          width="64"
          alt="placeholder"
        />
      </template>
      <h4 class="media-heading">
        Doktor Clodia
      </h4>
      <b-card-text class="mb-0">
        Uzman doktor Clodia Z., 1978 doğumlu, Oxford'dan mezun diyetisyen uzmanımız. Uzmanlık alanı sağlıklı yaşam, kişiye özel diyet listesi yapmaktadır.
      </b-card-text>
    </b-media>
  </div>
</template>

<script>
import { BMedia, BImg } from 'bootstrap-vue'

export default {
  components: {
    BMedia,
    BImg,
  },
}
</script>
 
