<template>
  <div class="home">
    <section class="hero">
      <div class="hero-content">
        <h1>Welcome to Boquette Flower's</h1>
        <p>Rangkaian bunga besar seperti ini memang lagi tren ya, cocok banget buat ngucapin hari spesial pimpinan, kerabat, atau sanak saudara yang lagi punya acara. Jangan salah rangkaian bunga ini dibuat dari 100% bunga segar dan bisa di custom sesuai dengan keinginan kamu.</p>
      </div>
    </section>

    
  </div>
</template>

<style scoped>
.home {
  background: linear-gradient(to left, #d441a8, #e4906f, #ff15b9 );
  padding: 40px;
  font-family: bold;
}

.hero {
  background: url('/path/to/hero-image.jpg') center/cover no-repeat;
  color: #0b0606;
  text-align: center;
  padding: 60px 0;
  background-size: cover;
}

.hero-content {
  max-width: 600px;
  margin: 0 auto;
}

h1 {
  font-size: 3rem;
  margin-bottom: 20px;
}

p {
  font-size: 1.5rem;
  margin-bottom: 20px;
  text-align: justify;
}

.featured-products {
  margin-top: 40px;
  text-align: center;
}

.product-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.product-card {
  margin: 20px;
  padding: 20px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 5px;
  text-align: center;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.product-card img {
  max-width: 100%;
  height: auto;
  margin-bottom: 10px;
} 

.product-card h3 {
  font-size: 2rem;
}

.product-card p {
  font-size: 1.5rem;
  margin-top: 10px;
}
</style>