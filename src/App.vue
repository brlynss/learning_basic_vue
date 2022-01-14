<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">bangtan</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>

            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Dropdown
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Something else here</a>
                </li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled">Disabled</a>
            </li>
          </ul>
          <form class="d-flex">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Search"
              aria-label="Search"
            />
            <button class="btn btn-outline-success" type="submit">
              Search
            </button>
          </form>
        </div>
      </div>
    </nav>
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
              Lagu BTS 'Butter' Akhirnya Keluar: BTS Membayar Tribute kepada
              Fans mereka di Lagu
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
    <div class="row">
      <nav class="col-md-2 d-none d-md-block bg-light sidebar">
        <div class="sidebar-sticky">
          <ul class="nav flex-column">
            <li class="nav-item">
              <a class="nav-link active" href="index.html">
                <span data-feather="home"></span>
                Home <span class="sr-only">(current)</span>
              </a>
            </li>
            <div class="dropdown-divider"></div>
            <li class="nav-item">
              <a class="nav-link" href="bangtan.html">
                <span data-feather="file"></span>
                BTS
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="army.html">
                <span data-feather="shopping-cart"></span>
                ARMY
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="life-goes-on.html">
                <span data-feather="users"></span>
                Life Goes On
              </a>
            </li>
          </ul>
        </div>
      </nav>
      <main role="main" class="col-md-9 ml-sm-auto col-lg-10 pt-3 px-4">
        <div class="container">
          <div class="py-5 ">
            <h2>Sejarah Bangtan (BTS)</h2>
            <p class="lead">
              BTS merupakan salah satu boy band asal Korea Selatan yang
              fenomenal. Saat ini Bangtan Sonyeondan menjadi grup musik kenamaan
              seantero dunia. Perjalanan karir grup dengan 7 member ini tidak
              mulus begitu saja. Perjuangan yang berat telah mereka lewati.
              Dikutip dari Time, pada 2010 lalu agensi yang menaungi BTS, Big
              Hit merekrut RM sebagai rapper. Kemudian agensi juga merekrut Jin,
              Suga, J-Hope, Jimin, V dan Jungkook karena bakat menyanyi, menari
              dan rap mereka. Tiga tahun kemudian, BTS mulai melakukan single
              debut "No More Dream" yang isinya mengritik tekanan sosial di
              Korea. Seperti ekspektasi tinggi pada anak sekolah, kesehatan
              mental hingga dukungan untuk hak-hak LGBTQ. Dari berbagai sumber,
              disebutkan Big Hit saat itu bukanlah agensi besar. Namun saat
              debut, semangat BTS sangat membara. Hingga mereka merilis video
              klip We Are Bullettproff PT.2 yang berhasil mencuri perhatian
              pecinta musik Kpop. Mereka bertujuh dulunya tinggal di sebuah dorm
              kecil dan tidur di ranjang susun, sangat sederhana. Namun hal ini
              pula yang membentuk kekompakan mereka hingga sekarang. Agensi yang
              menaungi BTS memang memahami cara untuk membuat BTS menjadi lebih
              tenar dibanding sebelumnya. Mereka merilis album Dark and Wild
              sampai mulai tur pertama ke Jepang lalu mulai menggelar tur-tur
              berikutnya di banyak negara. Tahun 2015 BTS berhasil menyabet
              banyak penghargaan mulai dari World Rookie Award Gaon Chart Music
              Award, Disk Bonsang Golden Disc Awards sampai Best World Performer
              Mnet Asian Music Awards. Di tahun yang sama BTS juga berada di
              posisi ketiga dalam Billboard's World Digital Chart dan tampil di
              Billboard studios. Pada 2016 BTS sukses dengan album barunya WINGS
              dan langsung menduduki posisi puncak Billboard. Mereka merupakan
              artis Korea pertama dengan penjualan album tertinggi yang dicatat
              Billboard. Untuk pre order penjualan album fisik WINGS sebanyak
              500.000 dan jumlah penjualan digital sebanyak 600.000. Tahun ini
              pula BTS mengantongi penghargaan best album of the years di ajang
              melon music awards. Nama BTS terus mendunia, mereka berkolaborasi
              dengan penyanyi seperti Halsey, DJ Aoki, Lil Nas X, Sia, Nicky
              Minaj, Becky G, Zara Larsson, Charli XCX dan Lauv.
            </p>
          </div>
        </div>
      </main>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  data() {
    return {
      message: "Hello World"
    };
  },
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
}
</style>
