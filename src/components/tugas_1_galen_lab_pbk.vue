<template>

    

    
    <div class="main-container">

       
       <header class="header">
        <a href="" class="logo">Portofolio.</a>

        <nav class="navbar">
            <a href="#">Home</a>
            <a href="#">Skill</a>
            <a href="#">About</a>
        </nav>
       </header>


    
    <section class="profile">
   
    <div class="profile-info" >
        <h3>Hi, Saya Adalah</h3>
        <h1>Galen Abiyyu Rasyid</h1>
        <h4>Mahasiswa Universitas Islam Riau </h4><br>
       <p>Saya lahir di Pekanbaru, 8 Februari 2004. sakrang umur saya 20 tahun. Sekarang saya bertempat tinggal di pekanbaru jalan bawal no 20 kec marpoyan damai kelurahan wonorejo Saat ini saya sedang berkuliah Universitas Islam Riau Fakultas Teknik Informatika.
        saat ini saya masih semester 4 dan saya memiliki minat dalam web developer.  </p>
    </div>
    <div class="profile-image">
        <img src="../assets/pas foto.jpg" alt="Foto Profil">
    </div>
    </section>

    <br>
    <hr>
    <br>
    <br>
    <div class="profile2">
        <div class="work">
            <h1>Pegalaman</h1>
            <p>Saya Pernah mengikuti
            lomba musik tradisional seprovinsi dan mewakili riau, Lomba teater, Lomba powerlifting seprovinsi Riau</p>
        </div>
        <div class="contact">
            <h1>Contact</h1>
            <div class="contact-img">
            <a href=""><img src="../assets/github.png" alt=""></a>
            <a href=""><img src="../assets/instagram.png" alt=""></a>
            <a href=""><img src="../assets/youtube.png" alt=""></a>
            <a href=""><img src="../assets/whatsapp.png" alt=""></a>
            </div>
        </div>
    </div>   
    
    <br>
    <br>

    <div class="hobby">
        <h1>Hobby</h1>
    </div>

<br>
    <div class="grid-container">
    <div class="item"><img src="../assets/coding.jpg" alt="Gambar 1"><br>Coding</div>
    <div class="item"><img src="../assets/olahraga.jpg" alt="Gambar 2"><br>Olahraga</div>
    <div class="item"><img src="../assets/sunmori.jpg" alt="Gambar 3"><br>Sunmori</div>
    <div class="item"><img src="../assets/traveling.jpg" alt="Gambar 4"><br>Traveling</div>
</div>



</div>

    
</template>

<script>
export default{


}
</script>

<style scoped>

.background{
    background-color: black;
}



h1{
    font-weight: 700;
    font-size: xx-large;
}

h3{
    font-weight: 600;
}

h4{
    font-weight: 600;
}


.header{
    position: fixed;
    top: 0;
    left: 0;
    width: 85%;
    padding: 20px 10%;
    background: rgb(37, 37, 37);
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

.header a{
    color: white
}

.logo{
    font-size: 25px;
    text-decoration: none;
    color: aliceblue;
    font-weight: 600;
}



.navbar a{
    margin-left: 30px;
    text-decoration: none;
    font-weight: 700;
    transition: 0.5s;

}

.navbar a:hover{
    color: green;
    border: 2px solid;
}

.profile {
    display: flex;
    align-items: center;
    padding-top: 90px;
    margin-top: 0%;
    margin-right: 40px;
    margin-left: 10px;
   
   padding-left: 80px;
   
}

.profile-image {
    margin-right: -000px;
    padding-left: 100px;
    padding-right: 100px;
    

}

.profile-image img {
    width: 200px; /* Sesuaikan lebar gambar sesuai kebutuhan */
    height: auto;
    border-radius: 50%;
}

.profile-info {
    text-align: left;
    color: white;
}

.profile-info h2 {
    margin-bottom: 10px;
}


.profile2{
    display: flex;
    align-items: center; 
    padding-bottom: 10px;
    color: white;
    margin-right: 100px;
    margin-left: 100px;
}

.profile2 .contact{
    
    padding-left: 50px;
}

.contact img {
    display: flex; /* Menggunakan flexbox */
    align-items: center;
    width: 40px;
    margin-left: 30px;
   
}

.contact h1{
    margin-left: 100px;
}

.contact-img{
   
    display: flex; /* Menggunakan flexbox */
    align-items: center;
   

}

.hobby{
    display: flex;
    justify-content: center; /* Untuk menengahkan elemen */
    background: rgb(37, 37, 37);
    align-items: center;
    padding-right: 0px;
}

.grid-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 10px; /* Ruang antara item */
}

.item {
    position: relative;
    overflow: hidden;
    color: white;
    font-weight: 900;
}

.item img {
    width: 70%;
    height: 70%;
    display: block;
    transition: transform 0.3s ease; /* Animasi saat hover */
    margin-left: 50px;
}

.item:hover img {
    transform: scale(1.1); /* Membesarkan gambar saat hover */
}

.gambar2 img{
    
    max-width: 100px;

    
}



</style>

