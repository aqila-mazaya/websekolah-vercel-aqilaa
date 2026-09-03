    <script setup>
      import teamCard from '../components/TeamCard.vue'
    
      const daftarTim = [
        {
          nama: 'albiru sabir',
          jabatan: 'founder & manager',
        },
        { 
          nama: 'alie san',
          jabatan: 'marketing',
        },
        { 
          nama: 'an pradipt',
          jabatan: 'customer service'
        }
      ]
    </script>
<template>
  <div class="about-page">
    <section class="banner">
    <h1>tentang kami</h1>
    <p>ayo kenali tentang kami</p>
    </section>

    <section class="story">
      <div class="text">
        <h2>cerita kami</h2>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.
           Voluptatibus rem praesentium nulla animi nam quis molestias voluptatem itaque minima!
           Fuga ad minima aperiam perspiciatis laboriosam quo quibusdam accusantium illum. Dolores!</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.
           Amet consequuntur iusto mollitia illum exercitationem hic nostrum suscipit quasi
           doloremque cumque ipsa nihil sed eveniet, et aliquam reprehenderit a doloribus deleniti.</p>
      </div>

      <div class="image">
        <div class="image-placeholder">
         <img src="https://i.pinimg.com/736x/42/d4/9b/42d49ba494e44110cf95ffea9fc3a59d.jpg" alt="image">
        </div>
      </div>
    </section>

    <section class="team">
      <h2>tim kami</h2>
      <p class="team-description">berkenalan dengan anggota kami yang bekerja sama untuk mengembangkan toko kami</p> 
      
  <div class="team-list">
    <TeamCard
      v-for="anggota in daftarTim"
      :key="anggota.nama"
      :nama="anggota.nama"
      :jabatan="anggota.jabatan" />
      </div>
  </section>
  </div>
</template>


<style scoped>
  /* .about-page {
    min-height: 100vh;
    background-color: antiquewhite;
  }

  .banner h1 {
    margin: 0 0 10px;
    font-size: 40px;
  }
  .banner p {
    margin: 0;
    font-size: 18px;
  }

  .team-list {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 1.5rem;
  padding: 1rem;
}
  .story {
    display: flex;
    align-items: center;
    gap: 40px;
    max-width: 1100px;
    margin: 0 auto;
    padding: 70px 20px;
  }
  .image {
   display:flex;
   align-items: center;
   gap: 30px;
   padding: 3rem 1.5rem;
   flex-wrap: wrap;
  }
  .image .text {
    flex: 1;
    min-width: 250px;
    text-align: center;
  }

  .text h2,
  .team h2 {
    margin-bottom: 20px;
    color:rgb(172, 172, 105);
    font-size: 30px;
  }
  .text p {
    color:rgb(121, 121, 90);
    line-height: 1.8;
    margin-bottom: 15px;
  }

  .image-placeholder {
    min-height: 300px;
    border-radius: 20px;
    background-color: bisque;
    display: flex;
    align-items: center;
    justify-content: center;
    color:hsl(60, 15%, 66%);
    font-size: 20px;

  
  }

  .team {
    max-width: 1100px;
    margin: 0 auto;
    padding: 20px 20px 70px;
  }

  .team-description {
   color:rgb(170, 152, 125);
   margin-bottom: 30px;
  }
  .team-list {
    grid-template-columns: 1fr;
    display: grid;
    gap: 20px;
  }

  @media (max-width: 768px) {
    .story {
      flex-direction: column;
    }
    .team-list {
      grid-template-columns: 1fr;
    }
    .banner h1 {
      font-size: 32px;
    }
  } */
</style>