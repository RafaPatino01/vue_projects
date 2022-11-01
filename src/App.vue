<script setup>
import MainPage from './components/MainPage.vue'
import destacados from './components/destacados.vue'
import noticias from './components/noticias.vue'
</script>

<template>
    <div>
      <MainPage/>
      <destacados title="Empresarios" 
      id1="artista1"
      id2="artista2"
      id3="artista3"
      name1="Emilio Azcárraga Vidaurrete"
      name2="Héctor Sulaimán"
      name3="Cynthia Grossman"
      descr1="Fundador deTelesistema Mexicano"
      descr2="Socio en la empresaIvanhoe Energy, Inc.,empresa Canadienselistada en el NYSE."
      descr3="Una de las principalesaccionarias de ArcaContinental"
      url1="src/assets/azcarraga.jpeg"
      url2="src/assets/hector.jpeg"
      url3="src/assets/cyntia.jpeg"
      />
      <br><br>
      <destacados title="Artistas" 
      id1="artista4"
      id2="artista5"
      id3="artista6"
      name1="Rigo Tovar"
      name2="Roberto Cantora"
      name3="Cecilia Suárez"
      descr1="Cantante"
      descr2="Cantante y Compositor"
      descr3="Actríz"
      url1="src/assets/rigo.jpeg"
      url2="src/assets/roberto.jpeg"
      url3="src/assets/cecilia.jpeg"
      />
      <destacados title="Deportistas" 
      id1="artista7"
      id2="artista8"
      id3="artista9"
      name1="Rodolfo Pizarro"
      name2="José Sulaimán"
      name3="Alan Pulido"
      descr1="Futbolista"
      descr2="Boxeador"
      descr3="Futbolista"
      url1="src/assets/pizarro.jpeg"
      url2="src/assets/sulaiman.jpeg"
      url3="src/assets/alan.jpeg"
      />
      <noticias title="Noticias"/>
    </div>
</template>

<style scoped>
div {
  height: 100%;
}
</style>
