<template>
  <div class="solSagBosluk custom-slider">
    <v-carousel cycle height="600" hide-delimiter-background show-arrows-on-hover>
      <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src"></v-carousel-item>
    </v-carousel>
  </div>
</template>
<script>
export default {
  data() {
    return {
      items: [
        {
          src:
            "https://www.tudors.com/Uploads/Slider/ds01-461.jpg?t=20211022085134"
        },
        {
          src:
            "https://www.tudors.com/Uploads/Slider/ofise-ozel-478.jpg?t=20211015085311"
        },
        {
          src:
            "https://www.tudors.com/Uploads/Slider/kislik-aksesuar-482.jpg?t=20211008111610"
        },
        {
          src:
            "https://www.tudors.com/Uploads/Slider/ds02-462.jpg?t=20210915133844"
        },
        {
          src:
            "https://www.tudors.com/Uploads/Slider/https-wwwtudorscom-online-ozel-473.jpg?t=20211025084032"
        },
        {
          src:
            "https://www.tudors.com/Uploads/Slider/qwd-487.jpg?t=20211021145111"
        }
      ]
    };
  }
};
</script>
<style scoped>
.solSagBosluk{
    margin-left: 14.15%;
    margin-right: 14.15%;
}
</style>