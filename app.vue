<template>
  <div>
    <NuxtLink to="home">Home</NuxtLink>
    <NuxtLink to="cart">Cart</NuxtLink>
    <NuxtPage />

    <input type="text" />

    <h2>KopiShop Kekinian</h2>
    <h3>Menu :</h3>
    <ul>
      <li>Es Kopi Susu <button>Add</button></li>
      <li>Es Kopi Coklat <button>Add</button></li>
      <li>Es Kopi Vanila <button>Add</button></li>
    </ul>

    <hr />

    <div style="padding: 10px; border: solid 1px #ccc">
      <h2>Pesanan Anda</h2>
      <ul>
        <li>Croissant x 2 <button>Batal</button></li>
        <li>Kopi Vanila (Hot) x 1<button>Batal</button></li>
        <li>Nasi Goreng x 4<button>Batal</button></li>
      </ul>

      <button>Checkout</button>
    </div>
  </div>
</template>
