<script setup>
defineProps({
  title: { type: String }
})
</script>

<template>
  <br><br><br>
  <div class="row mt-5 h-100 w-100 px-5" id="destacados">
    <div class="container px-3">
      <div class="row">
        <div class="col-6 p-5">
          <h2> {{title}} </h2>
          <img src="/src/assets/news.png" class="w-100 mt-3" alt="">
        </div>

        <div class="col-6 p-5">
          <div class="w-100 bg-primary round-border p-3 mb-4">
            <h4 class="text-warning">Suleimán acompaña a gobernador</h4>
            <p class="text-white mt-3">
              El empresario libanés y presidente del Consejo Mundialde Boxeo, hijo del ex boxeador, José Sulaimán, MauricioSulaimán, acompañó al Gobernador Alejandro MuratHinojosa a la presentación del Cinturón Guerrero JaguarZapoteco.
            </p>
          </div>
          <div class="w-100 bg-primary round-border p-3 mb-4">
            <h4 class="text-warning">Destaca Cecilia Suárez en España</h4>
            <p class="text-white mt-3">
              ras el estreno de la nueva serie del director mexicano,Manolo Caro, La Sagrada Familia, el personaje de CeciliaSuarez ha dejado buena impresión en el viejo continente.
            </p>
          </div>
          <div class="w-100 bg-primary round-border p-3 mb-4">
            <h4 class="text-warning">Destaca Cecilia Suárez en España</h4>
            <p class="text-white mt-3">
              ras el estreno de la nueva serie del director mexicano,Manolo Caro, La Sagrada Familia, el personaje de CeciliaSuarez ha dejado buena impresión en el viejo continente.
            </p>
          </div>
        </div>

      </div>
      
      
    </div>
    
  </div>
</template>

<style scoped>
svg {
  position: relative; margin-top: -140px;
}
.row {
  height: 100%;
}
h2 {
  color: BLACK;
  font-size: 45px;
  font-weight: 900;

}
 .bg-gray {
  background-color: rgb(200, 200, 200);
 }
.btn-danger {
  background-color: rgb(255, 72, 0);
}

.round-border {
  border-radius: 25px;
}

.card-title {
  color: rgb(236, 79, 22);
  font-weight: 600;
  
}
</style>
