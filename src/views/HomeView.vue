<script setup>
import Mg from '../assets/sample.jpg';
</script>
<template>
<div class="image-container" style="position: relative; height: 65vh;">
  <img :src="Mg" class="img-fluid w-100" style="height: 100%;" alt="...">
  <div class="text-overlay d-flex justify-content-center align-items-center position-absolute top-50 start-50 translate-middle text-center text-white">
    <div style="margin-right: 50px;">
      <h1 class="display-4">WELCOME TO JACK MACHINE</h1>
      <p class="lead mb-4">At Jack Machine, we believe in pushing the boundaries of technology and design to create innovative solutions...</p>
      <a href="#" class="btn btn-primary">Learn More</a>

    </div>
  </div>
</div>

  <br>
  <div class="projects container my-5">
  <h2 class="text-center mb-4">Our Works</h2>
  <div class="row">
    <div class="col-sm-12 col-md-4 mb-4">
      <div class="card shadow-sm">
        <img :src="img" alt="Jackport Machine Image" class="card-img-top" />
        <div class="card-body">
          <h5 class="card-title">Jackport Machine Design & Manufacturing</h5>
          <p class="card-text">We specialize in designing and building high-quality jackport machines, tailored to meet industry needs with precision and durability.</p>
          <button class="btn btn-primary">Learn More</button>
        </div>
      </div>
    </div>

    <div class="col-sm-12 col-md-4 mb-4">
      <div class="card shadow-sm">
        <img :src="img" alt="Jackport Machine Image" class="card-img-top" />
        <div class="card-body">
          <h5 class="card-title">Jackport Machine Design & Manufacturing</h5>
          <p class="card-text">We specialize in designing and building high-quality jackport machines, tailored to meet industry needs with precision and durability.</p>
          <button class="btn btn-primary">Learn More</button>
        </div>
      </div>
    </div>

    <div class="col-sm-12 col-md-4 mb-4">
      <div class="card shadow-sm">
        <img :src="img" alt="Jackport Machine Image" class="card-img-top" />
        <div class="card-body">
          <h5 class="card-title">Jackport Machine Design & Manufacturing</h5>
          <p class="card-text">We specialize in designing and building high-quality jackport machines, tailored to meet industry needs with precision and durability.</p>
          <button class="btn btn-primary">Learn More</button>
        </div>
      </div>
    </div>
  </div>
</div>
<section class="our-services py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-4">Our Services</h2>
      <div class="row">
        <!-- Web Development Card -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="https://via.placeholder.com/150" class="card-img-top" alt="Web Development">
            <div class="card-body">
              <h5 class="card-title">Web Development</h5>
              <p class="card-text">Build modern and responsive websites tailored to your needs.</p>
            </div>
          </div>
        </div>

        <!-- API Integration Card -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="https://via.placeholder.com/150" class="card-img-top" alt="API Integration">
            <div class="card-body">
              <h5 class="card-title">API Integration</h5>
              <p class="card-text">Integrate third-party APIs seamlessly into your application.</p>
            </div>
          </div>
        </div>

        <!-- Consultation Card -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="https://via.placeholder.com/150" class="card-img-top" alt="Consultation">
            <div class="card-body">
              <h5 class="card-title">Consultation</h5>
              <p class="card-text">Expert advice on tech solutions and problem-solving.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

</template>
<style scoped>
.image-container {
  position: relative;
  height: 65vh;
}

.text-overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
  font-size: 24px;
  font-weight: bold;
  white-space: nowrap;
  overflow: hidden;
  width: 0;
  animation: typing 4s steps(30) 1s forwards, blink 0.75s step-end infinite;
  text-align: center; /* Ensures text is aligned center horizontally */
}
.text-overlay h1 {
  margin: 0;
  font-size: 36px;
}
.text-overlay p {
  margin-right: 45px;
  font-size: 16px;
  width:20px;
}

@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}

.our-services {
  background-color: #f8f9fa;
}

.card {
  border: 1px solid #ddd;
  border-radius: 8px;
}

.card-title {
  font-weight: bold;
}

.card-text {
  color: #555;
}

.card-img-top {
  height: 150px;
  object-fit: cover;
  border-bottom: 1px solid #ddd;
}

</style>
<script>
import img from '../assets/WhatsApp Image 2025-01-26 at 08.51.39_2d9a4709.jpg';
</script>
