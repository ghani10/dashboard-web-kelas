<script setup>
import navigation from '/src/components/navbar.vue'
import carousel from '/src/components/carousel.vue'
import card from '/src/components/card.vue'
import footered from '/src/components/footer.vue'
</script>

<template>
  <nav>
    <navigation class="min-h-fit ">
    </navigation>
  </nav>


  <!--Hero Section-->
  <section>
    <div class="hero bg-base-200 min-h-fit mx-auto ">
        <div class="hero-content flex-col lg:flex-row-reverse relative">
          <img 
          src="/src/assets/hero.webp" 
          alt=""
          class="max-w-lg rounded-lg shadow-2xl">
          <div class="p-5 mr-20 mx-auto">
                <h1 class="text-sm font-medium text-[#E2E2B6]">05TPLK002</h1>
                 <h1 class="text-5xl font-bold text-white">Portofolio Kelas</h1>
                 <p class="py-6">
                 Teknik Informatika adalah jurusan yang sangat banyak sekali prospek karir dan inovasi. 
                 Kami dengan ini menyampaikan informasi tentang Teknik Informatika. Dengan Website ini kami berharap bisa belajar dan berkembang bersama !
                 </p>
             <button class="btn bg-[#021526] text-white hover:bg-slate-950">Let's Eksplore</button>
            </div>
        </div>
    </div>
  </section>

  <section>
    <div class="divider"></div>
  </section>


  <section>
    <div class="container mx-auto px-10">
      <h2 class="text-3xl font-black text-white">Tentang Kami</h2>
      <p class="mt-2 text-sm font-medium">Kami Merupakan Mahasiswa Kelas Karyawan Yang berusaha Dan Belajar Dengan Tekun. Kami Juga Berusaha Saling Membantu Sesama Mahasiswa Dengan Tujuan Berbagi Ilmu Pengetahuan
        <br>
      </p>
      <p class="mt-2 text-md font-semibold text-blue-200">Let's Deeper With Me</p>
    </div>
    <div class="container mt-2 mx-auto p-5">
      <carousel class="mx-auto max-w-screen-2xl"></carousel>
    </div>
  </section>

  <section>
    <div class="divider"></div>
  </section>

  <section>
    <div class="container mx-auto px-10">
      <h2 class="text-3xl font-bold text-white">Portfolio Kami</h2>
    </div>
    <div class="flex flex-wrap gap-4 mx-5 my-10">
      <div class="">
        <card></card>
      </div>
      <div>
        <card></card>
      </div>
      <div class="">
        <card></card>
      </div>
      <div>
        <card></card>
      </div>
      <div class="">
        <card></card>
      </div>
      <div>
        <card></card>
      </div>
      <div class="">
        <card></card>
      </div>
      <div>
        <card></card>
      </div>
    </div>
  </section>

  <footer>
    <footered/>
  </footer>
  


  


  
</template>

