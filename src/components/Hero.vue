<template>
  <div>
    <!-- Hero Section Begin -->
    <section class="hero-section">
      <carousel class="hero-items" :items="1" :nav="false" :autoplay="true">
        <div
          class="single-hero-items set-bg"
          style="background-image: url('/img/hero-1.jpg')"
        >
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Kopi Gesing</span>
                <h1>E-Commerce Penyedia biji dan produk kopi</h1>
                <p>
                  Biji Kopi dari Desa Gesing (Kualitas kopi no.1 Pemenang kompetisi di Indonesia)
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div
          class="single-hero-items set-bg"
          style="background-image: url('/img/hero-2.jpg')"
        >
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Kopi Gesing</span>
                <h1>Pusat pemasok Produk Kopi</h1>
                <p>
                  Jaringan bisnis Kopi di Cafe & Industri Kuliner.
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
        <div
          class="single-hero-items set-bg"
          style="background-image: url('/img/hero-3.jpg')"
        >
          <div class="container">
            <div class="row">
              <div class="col-lg-5">
                <span>Kopi Gesing</span>
                <h1>We're Smart Cofee</h1>
                <p>
                  Smart Coffe: (Digital Smart Shopping All About Coffe)
                </p>
                <a href="#" class="primary-btn">Shop Now</a>
              </div>
            </div>
          </div>
        </div>
      </carousel>
    </section>
    <!-- Hero Section End -->
  </div>
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "Hero",
  components: {
    carousel,
  },
};
</script>
