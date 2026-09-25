<template>
  <div class="landing-page">
    <h1 style="font-size: 20px;">SELAMAT DATANG DI ONLINESOP KAMI</h1>
    <p>Belanja mudah, sekolah senang.</p>
    <button class="btn-grad">Click to Shop</button>
  </div>
  <div class="ini">
    <div class="container">
      <h1>Cerita</h1>
      <p>Onlineshop ini di kelola oleh siswa SMK YADIKA SOREANG jurusan PPLG, </p>
        <p>dengan tujuan untuk memberikan pengalaman belanja online yang terbaik bagi pelanggan kami,</p>
        <p>semoga bisa berbelanja dengan nyaman dan aman.</p>
      </div>
      <div class="foto">
        <h1>FOTO</h1>
      </div>
      </div>
    </template>
    <style scoped>
    .landing-page {
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 5rem;
        text-align: center;
        background-color: #4091ee;
        width: 100%;
        height: 100px;
        box-shadow: 0 9px 6px rgba(0, 0, 0, 0.1);
    }

    .foto {
      background-color: #77A1D3;
      text-align: center;
      padding-top: 90px;
      width: 25rem;
      height: 10rem;
      margin-top: 10px;
      border-radius: 10px;
    }

    .ini {
      display: flex;
      gap :20px;
      margin-left: 100px;
      margin-top:20px;
    }

     .btn-grad {
  background-image: linear-gradient(to right, #77A1D3 0%, #79CBCA 51%, #77A1D3 100%);
}

.btn-grad {
  margin: 10px;
  padding: 15px 45px;
  text-align: center;
  text-transform: uppercase;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  box-shadow: 0 0 20px #eee;
  border-radius: 10px;
  outline: none;
  border: none;
}

.btn-grad:hover {
  background-position: right center;
  color: #fff;
  text-decoration: none;
}
</style>