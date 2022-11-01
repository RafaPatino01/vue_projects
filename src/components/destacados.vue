<script setup>
defineProps({
  title: { type: String },
  id1: { type: String },
  id2: { type: String },
  id3: { type: String },
  name1: { type: String },
  name2: { type: String },
  name3: { type: String },
  descr1: { type: String },
  descr2: { type: String },
  descr3: { type: String },
  url1: { type: String },
  url2: { type: String },
  url3: { type: String }
})
</script>

<template>
  <br><br><br>
  <div class="row mt-5 h-100 w-100 px-5" id="destacados">
    <div class="container px-3">
      <h2> {{title}} </h2>
      <div class="row">
        
        
        <div class="col-sm-4 px-3" style="position: relative; margin-top: 148px;">
          <div class="">
            <div class="card w-100 round-border shadow-lg" style="background-color: rgb(200,200,200);">
              <svg viewBox="0 0 100 100" version="1.1" xmlns="http://www.w3.org/2000/svg" style="background-color: rgb(176, 176, 176, 0);" class="round-border">
                <defs>
                  <pattern :id="id1" patternUnits="userSpaceOnUse" width="100" height="100" >
                    <image :xlink:href="url1" x="-25" width="150" height="100" />
                  </pattern>
                </defs>
                <polygon points="50 1 95 25 95 75 50 99 5 75 5 25" :fill="'url(#' + id1 + ')'"/>
              </svg>
            <div class="card-body bg-gray round-border">
              <h5 class="card-title">{{name1}}</h5>
              <p class="card-text">{{descr1}}</p>
            </div>
            </div>
          </div>
        </div>

        <div class="col-sm-4 px-3" style="position: relative; margin-top: 148px;">
          <div class="">
            <div class="card w-100 round-border shadow-lg" style="background-color: rgb(200,200,200);">
              <svg viewBox="0 0 100 100" version="1.1" xmlns="http://www.w3.org/2000/svg" style="background-color: rgb(176, 176, 176, 0);" class="round-border">
                <defs>
                  <pattern :id="id2" patternUnits="userSpaceOnUse" width="100" height="100" >
                    <image :xlink:href="url2" x="-25" width="150" height="100" />
                  </pattern>
                </defs>
                <polygon points="50 1 95 25 95 75 50 99 5 75 5 25" :fill="'url(#' + id2 + ')'"/>
              </svg>
            <div class="card-body bg-gray round-border">
              <h5 class="card-title">{{name2}}</h5>
              <p class="card-text">{{descr2}}</p>
            </div>
            </div>
          </div>
        </div>

        <div class="col-sm-4 px-3" style="position: relative; margin-top: 148px;">
          <div class="">
            <div class="card w-100 round-border shadow-lg" style="background-color: rgb(200,200,200);">
              <svg viewBox="0 0 100 100" version="1.1" xmlns="http://www.w3.org/2000/svg" style="background-color: rgb(176, 176, 176, 0);" class="round-border">
                <defs>
                  <pattern :id="id3" patternUnits="userSpaceOnUse" width="100" height="100" >
                    <image :xlink:href="url3" x="-25" width="150" height="100" />
                  </pattern>
                </defs>
                <polygon points="50 1 95 25 95 75 50 99 5 75 5 25" :fill="'url(#' + id3 + ')'"/>
              </svg>
            <div class="card-body bg-gray round-border">
              <h5 class="card-title">{{name3}}</h5>
              <p class="card-text">{{descr3}}</p>
            </div>
            </div>
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
