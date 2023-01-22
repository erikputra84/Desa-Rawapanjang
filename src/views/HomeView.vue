<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <P class="text=lg font-semibold mt-4">Visi</P>
      <p>Desa Rawapanjang BERKAH (Bersih, Kuat dan Sejahtera)</p>
      <p class="text=lg font-semibold mt-4">Misi</p>
      <ul>
        <li>01	Menjadikan Desa Yang BERSIH Masyarakat, Lingkungan dan Pemerintahannya.</li>
        <li>02	Menjadikan Desa Yang KUAT Budaya, Ekonomi, Sosial dan Kesehatan.</li>
        <li>03	Menjadikan Desa yang SEJAHTERA Masyarakatnya.</li>
      </ul>
      <p class="text=lg font-semibold mt-4">Tujuan</p>
      <ul>
        <li>1.1	Terwujudnya Pemerintahan yang Bersih dan Transparan</li>
        <li>1.2	Terwujudnya Masyarakat Yang Memiliki Prilaku Budaya Hidup Bersih</li>
        <li>1.3	Terwujudnya Lingkungan Yang Bersih, Aman, Nyaman dan Asri</li>
        <li>1.4	Terwujudnya Pemerintahan yang Kuat Perangkat dan Kelembagaannya</li>
        <li>1.5	Terwujudnya Pemerintah Desa Digitalisasi Pelayanan, Administrasi dan Media Informasinya</li>
        <li>1.6	Terwujudnya Masyarakat Yang Kuat Jasmani, Agama, Sosial, Budaya, Pendidikan dan Ekonominya</li>
        <li>1.7	Terwujudnya Pengembangan Potensi Desa Secara Baik dan Benar</li>
        <li>1.8	Terwujudnya Pemerintah Yang Berkeadilan Sosial Bagi Seluruh Masyarakat</li>
        <li>1.9	Terwujudnya Masyarakat yang Sejahtera</li>
      </ul>

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/struktur-desarawapanjang.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
