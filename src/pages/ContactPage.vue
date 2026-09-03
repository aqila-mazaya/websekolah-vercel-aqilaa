<script setup></script>
<template>
    <div class="yy">
    <section class="banner">
      <h1>hubungi aja</h1>
    </section>
    <section class="contact">
    <div class="info-kontak">
      <h2>info kontak</h2>
      <P>🗺 Jl.Justapayggaenaks</P>
      <p>📱 0243-2206-5866</p>
      <p>📬 @hcjdhakpiks_</p>
      <p>🗓 buka senin-kamis, 11.00-15.00</p>
    </div>
    <div class="formulir">
      <h2>ada pesan?</h2>
    <form>
    <div class="field">
      <label for="nama">nama</label>
      <input id="nama" type="text" placeholder="nama lengkap"/>
    </div>
    <div class="field">
      <label for="email">email</label>
      <input id="email" type="email" placeholder="email"/>
    </div>
    <div class="field">
      <label for="pesan">pesan</label>
      <textarea id="pesan" rows="4" placeholder="tulis pesan.."></textarea>
    </div>

      <button type="button">kirim</button>
    </form>
    </div>
    </section>
    </div>
</template>

<style scoped>
/* .yy {
    background: rgb(105, 157, 170);
    color:bisque;
    text-align: center;
    padding: 3rem 1rem;
}

.contact {
    display: flex;
    gap: 2rem;
    padding: 3rem 1rem;
    flex-wrap: wrap;
}

.info-kontak {
    flex: 1;
    min-width: 250px;
}

.info-kontak p{
    margin: 5px;
    display: flex;
    font-size: 16px;
}

.formulir {
    flex: 1;
    min-width: 280px;
    background: #456fa0;
    padding: 1.5rem;
    border-radius: 12px;
    box-shadow: bisque;
}

.field {
    margin-bottom: 1rem;
    display: flex;
    flex-direction: column;
}

.field label {
    margin-bottom: 0.4rem;
    font-weight: 600px;
    font-size: 0.9rem;
}

input,
textarea {
    padding: 0.6rem 0.8rem;
    border-radius: 8px;
    border: 1px solid bisque;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 15px;
}

input:focus,
textarea:focus {
    outline: none;
    border-color: blanchedalmond;
}

button {
    background: rgb(58, 86, 133);
    color:antiquewhite;
    border: none;
    padding: 0.7rem 3rem;
    border-radius: 999px;
    font-size: 1rem;
    font-weight: 600;
    cursor: pointer;
    margin-top: 0.5rem;
}

button:hover {
   opacity: 0.9;
} */

 </style>