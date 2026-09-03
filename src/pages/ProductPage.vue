<script setup>
import ProductCard from '../components/ProductCard.vue'
const daftarProduk = [
 { id: 1, nama: 'Seragam Sekolah', harga: 17500000, gambar:
'https://i.pinimg.com/736x/97/52/7d/97527da643d68f48147ecb0762b53820.jpg' },
 { id: 2, nama: 'Buku Sekolah', harga: 4300000, gambar:
'https://i.pinimg.com/736x/c9/db/7d/c9db7d558d48d1206df96ede7204f066.jpg' },
 { id: 3, nama: 'Tas Sekolah', harga: 1900000, gambar:
'https://i.pinimg.com/736x/6a/2a/5d/6a2a5d32d5ac432dfe3d5245edbb075b.jpg' },
 { id: 4, nama: 'sepatu sekolah', harga: 3400000, gambar:
'https://i.pinimg.com/736x/9c/44/51/9c4451fe7dab6f644c29f878d4b6fff5.jpg' },
]
</script>
<template>
 <main>
 <h1>Produk Kami</h1>
 <div class="grid">
 <ProductCard
 v-for="produk in daftarProduk"
 :key="produk.id"
 :nama="produk.nama"
 :harga="produk.harga"
 :gambar="produk.gambar"
 />
 </div>
 </main>
</template>
<style scoped>
/* .grid {
 display: flex;
 gap: 16px;
 flex-wrap: wrap;
} */
</style>
