<template>
  <div>
    <div id="hero-carousel" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators bottom-0">
        <button
          type="button"
          data-bs-target="#hero-carousel"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#hero-carousel"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-bs-target="#hero-carousel"
          data-bs-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active ">
          <img src="~/assets/images/image.jpg" class="d-block w-100" />
          <div class="carousel-caption top-0 mt-5  d-none d-md-block">
            <span class="text-collection mt-5">New collection 1</span>
            <h2 class="slider-title">Menswear 2020</h2>
            <div class="buttons-slider">
              <button type="button" class="btn btn-outline-success me-3">
                Shop sale
              </button>
              <button class="btn btn-success" type="submit">
                Shop the menswear
              </button>
            </div>
          </div>
        </div>
        <div class="carousel-item active">
          <img src="~/assets/images/image.jpg" class="d-block w-100" />
          <div class="carousel-caption top-0 d-none d-md-block">
            <span class="text-collection mt-5">New collection 2</span>
            <h2 class="slider-title">Menswear 2020</h2>
            <div class="buttons-slider">
              <button type="button" class="btn btn-outline-success me-3">
                Shop sale
              </button>
              <button class="btn btn-success" type="submit">
                Shop the menswear
              </button>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <img src="~/assets/images/image.jpg" class="d-block w-100" />
          <div class="carousel-caption top-0 d-none d-md-block">
            <span class="text-collection"> New collection 3</span>
            <h2 class="slider-title">Menswear 2020</h2>
            <div class="buttons-slider">
              <button type="button" class="btn btn-outline-success me-3">
                Shop sale
              </button>
              <button class="btn btn-success" type="submit">
                Shop the menswear
              </button>
            </div>
          </div>
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#hero-carousel"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#hero-carousel"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>
