<template lang="pug">
  div
    v-container(class="pa-16"
      align="center"
      justify="center"
    )
      v-flex(class="pa-16"
        align="center"
        justify="center"
      )
        v-row
          v-col(align="center"
            justify="center")
            v-btn(elevation="10" dark color="#8b2639" x-large class="justify-center" href="https://bgpu.ru/sveden/education/eduAccred/").text-h4 Образовательные программы
        v-row
          v-col(align="center"
            justify="center")
            v-btn(elevation="10" dark color="#8b2639" x-large class="justify-center" href="https://bgpu.ru/sveden/document/").text-h4 Нормативные документы
        v-row
          v-col(align="center"
            justify="center")
            v-btn(elevation="10" dark color="#8b2639" x-large class="justify-center" href="https://bgpu.ru").text-h4 Сайт университета
</template>

<script>
export default {
  name: 'AButtonPanel'
}
</script>

<style scoped>

</style>
