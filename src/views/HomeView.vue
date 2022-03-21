<template>
<div>
 <HeroOne />
 <ListOne />
 <FaqOne />
 <NewsletterOne />

 </div>
</template>

<script>
import HeroOne from '@/components/HeroOne.vue';
import ListOne from '@/components/ListOne.vue';
import FaqOne from '@/components/FaqOne.vue';
import NewsletterOne from '@/components/NewsletterOne.vue';
export default{
components:{
  HeroOne,
  ListOne,
  FaqOne,
  NewsletterOne
}
}
</script>