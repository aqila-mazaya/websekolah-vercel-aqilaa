<template>
    <div class="Team-card">
    <div class="ava">
        {{ nama.charAt(0).toUpperCase() }}
    </div>

    <div class="team-info">
        <h3>{{ nama }}</h3>
        <p>{{ jabatan }}</p>
    </div>
    </div>
</template>

<script setup>
   defineProps({
    nama: {
        type: String,
        required: true
    },
   }) 
</script>

<style scoped>
.team-card {
    display: flex;
    align-items: center;
    gap: 16px;
    padding: 16px;
    background-color: bisque;
    border-radius: 12px;
    box-shadow: 0 4px 12px whitesmoke;
}

.ava {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background-color: azure;
    display:flex;
    align-items: center;
    font-size: 24px;
    font-weight: bold;
}

.team-info h3 {
    margin: 0 0;
    color:beige;
}
.team-info p {
    margin: 0;
    color:beige;
}
</style>