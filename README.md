<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>zy Mock with Video Background</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* supaya video tidak menghalangi konten */
    video.bg-video {
      position: fixed;
      right: 0;
      bottom: 0;
      min-width: 100%;
      min-height: 100%;
      object-fit: cover;
      z-index: -1;
    }
  </style>
</head>
<body class="relative min-h-screen text-white">
  <!-- Video background -->
  <video autoplay muted loop class="bg-video">
    <source src="walper.mp4" type="video/mp4">
    Browser kamu tidak mendukung video background.
  </video>

  <!-- Header -->
  <header class="bg-black/50 backdrop-blur-sm">
    <div class="container mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-orange-400">zy<span class="text-white">Mock</span></h1>
      <nav class="flex gap-4">
        <a href="#" class="hover:text-orange-300">Home</a>
        <a href="#" class="hover:text-orange-300">Top Up</a>
        <a href="#" class="hover:text-orange-300">Voucher</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="container mx-auto px-4 py-16 text-center">
    <h2 class="text-4xl font-extrabold">Top Up Instan bokep Favoritmu </h2>
    <p class="mt-4 text-lg text-gray-200">Aman, cepat, dan mudah. Pilih bokep favoritmu sekarang🙏🗿.</p>
    <div class="mt-6 flex justify-center gap-4">
      <button class="bg-blue-500 px-6 py-3 rounded-xl font-bold shadow-lg">Top Up Sekarang</button>
      <button class="bg-white/20 px-6 py-3 rounded-xl">Lihat Promo</button>
    </div>
  </section>

  <!-- Produk Grid -->
  <section class="container mx-auto px-4 py-10 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="bg-black/60 p-4 rounded-xl shadow-lg">
      <img src="https://scontent-cgk2-1.xx.fbcdn.net/v/t1.6435-9/97360970_146364976943431_5929515300625055744_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=a5f93a&_nc_eui2=AeEacw3AyQEsPrx-v4Po4QelzXjKv8CaVUHNeMq_wJpVQRwJwI3UnCcYLczIs2IBKF8smAtGyqltWTEGbwXw60uk&_nc_ohc=Rd-XKU1EhTwQ7kNvwFAYROm&_nc_oc=AdlvFdQ9VNN5382zz_3539A_q0E5tv3oXb6PfyBpyLBf2_qZyBXpJglaVwix7RZDSpg&_nc_zt=23&_nc_ht=scontent-cgk2-1.xx&_nc_gid=XHuJfjnk5rawT_bf-GZ48Q&oh=00_Afbe1AfN5eBN49WXfkShrQE9d882zRCTP5FZTCo85mmeRA&oe=68E3B42F" class="rounded-lg" />
      <h3 class="mt-4 font-bold">Mobile Legends Diamonds</h3>
      <p class="text-orange-400 font-semibold">Rp 25.000</p>
      <button class="mt-3 w-full bg-blue-500 py-2 rounded-lg">Beli</button>
    </div>
    <div class="bg-black/60 p-4 rounded-xl shadow-lg">
      <img src="https://images.unsplash.com/photo-1511512578047-dfb367046420?auto=format&fit=crop&w=800&q=60" class="rounded-lg" />
      <h3 class="mt-4 font-bold">PUBG UC</h3>
      <p class="text-orange-400 font-semibold">Rp 50.000</p>
      <button class="mt-3 w-full bg-blue-500 py-2 rounded-lg">Beli</button>
    </div>
    <div class="bg-black/60 p-4 rounded-xl shadow-lg">
      <img src="https://play-lh.googleusercontent.com/yIL0QDE5mv74MD1FK_UA8WglI9HVuvzz5CQJ71ESAyOrgd1YdHrrqgEkDOodlxrz_8cf2p1jmnErHyPJhszi=w526-h296-rw" class="rounded-lg" />
      <h3 class="mt-4 font-bold">Free Fire Diamonds</h3>
      <p class="text-blue-400 font-semibold">Rp 15.000</p>
      <button class="mt-3 w-full bg-blue-500 py-2 rounded-lg">Beli</button>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-black/50 py-4 text-center text-sm">
    © 2025 azril — hanya skedar gabut🗿
  </footer>
</body>
</html>

