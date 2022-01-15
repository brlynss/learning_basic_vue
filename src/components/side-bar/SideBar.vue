<template>
  <div
    id="carouselExampleIndicators"
    class="carousel slide"
    data-bs-ride="carousel"
  >
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="https://i2.wp.com/harga.web.id/wp-content/uploads/penonton-konser.jpg?resize=680%2C300&ssl=1"
          class="d-block w-100"
          alt="..."
        />

        <div class="carousel-caption d-none d-md-block">
          <h5>BTS</h5>
          <p>BTS Kenalkan Edisi Khusus Light Stick</p>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://awsimages.detik.net.id/community/media/visual/2021/07/09/army.png?w=2560"
          class="d-block w-100"
          alt="..."
        />
        <div class="carousel-caption d-none d-md-block" style="color: black">
          <h5>ARMY</h5>
          <p>
            Lagu BTS 'Butter' Akhirnya Keluar: BTS Membayar Tribute kepada Fans
            mereka di Lagu
          </p>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://pyxis.nymag.com/v1/imgs/42b/2cd/e702703b5900f4fb54dcd52f7fcabc0c1d--22bts-life-goes-on-22.rsocial.h600.png"
          class="d-block w-100"
          alt="..."
        />
        <div class="carousel-caption d-none d-md-block" style="color: black">
          <h5>Life Goes On</h5>
          <p>
            BTS Hancurkan Internet (Lagi) Dengan Video untuk 'Life Goes On',
            Keluarkan Album Baru BE
          </p>
        </div>
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExampleIndicators"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleIndicators"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>
<script src="./side-bar.js"></script>
