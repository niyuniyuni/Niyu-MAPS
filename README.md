<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Niyu MAPS</title>

<body>
    <div class="banner">
        <div class="main">
            <div class="navbar">
                <div class="icon">
            </div>
<header>
    <h1>Niyu MAPS</h1>
    <nav>
        <ul>
            <li><a href="#home">HOME</a></li>
            <li><a href="#maps">MAPS</a></li>
            <li><a href="#about">ABOUT US</a></li>
            <li><a href="#contact">CONTACT</a></li>
        </ul>
    </nav>
</header>

<section id="home">
    <h2>Hello Geographer, Welcome to Niyu MAPS! ^-^</h2>
    <p>Niyu MAPS menyediakan peta penggunaan lahan Kecamatan Tandes dan Kecamatan Lakarsantri, Kota Surabaya, Jawa Timur.</p>
</section>

<section id="maps">
    <h2>MAPS</h2>
    <div class="maps">
    <iframe src="https://www.google.com/maps/d/embed?mid=1-Hi0pGilPqzjb0JSQ0s_odExGBOOy_Q&ehbc=2E312F" width="880" height="550"></iframe>
</div>

<script>
    function toggleImage() {
        var image = document.getElementById("myImage");
        
        // Toggle the image's display property
        if (image.style.display === "none") {
            image.style.display = "block";
        } else {
            image.style.display = "none";
        }
    }
</script>
</section>

<section id="about">
    <h2>Tentang Kami</h2>
    <p>Niyu MAP adalah webGIS yang menyediakan peta penggunaan lahan Kecamatan Tandes dan Lakarsantri, Kota Surabaya.</p>
    <p>Peta ini merupakan peta hasil kerja kelompok kami, kelompok 4 2022 A dengan pengerjaan melalui tetes darah, keringat, dan air mata. -_-</p>
</section>

<section id="contact">
    <h2>Mau Tanya-tanya lebih lanjut?</h2>
    <p>Hubungi kami melalui:</p>
    <p>Phone : 0822345678910 | IG : @niyu.map</p>
    <h2><marquee>SEMOGA SEMUA ANAK PEND. GEOGRAFI ANGKATAN 2022 MENDAPAT NILAI A DI SEMESTER 3 INI, AMIIIIN. ^-^</marquee></h2>
    <h2>T_T</h2>
</section>

</body>
<footer>
    <p>&copy; 2023 Niyu MAP. Powered by Google Maps.</p>
</footer>

<style>
    header {
        background-color: #be7617;
        color: rgb(245, 166, 77);
        padding: 1em;
        text-align: center;
        font-family: Verdana;
        font-weight: bold;
    }

    body {
        font-family: Verdana, Geneva, Tahoma;
        color:#fad5a5;
        margin: 0;
        padding: 0;
        width: 100%;
        height: 100%;
        background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(https://coolwallpapers.me/picsup/2638513-pirates-4k-free-wallpaper-in-hd.jpg);
        background-size: cover;
        background-position: center;
        background-repeat:repeat;
        text-align: center;

    }
    .contact {
        margin-bottom: 50%;
        padding-bottom: 50%;
    }

    .container {
        width: 80%;
        margin: 0 auto;
        padding: 20px;
        text-align: center;
    }

    button {
        padding: 10px 20px;
        font-size: 16px;
        cursor: pointer;
    }

    nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

section {
    padding: 0%;
}

.maps {
    border: 1px solid #ddd;
    padding: 10px;
    margin: 10px;
    text-align: center;
}

.product img {
    max-width: 100%;
    height: auto;
}
 .about {
    background-color:rgb(245, 166, 77);
 }

footer {
    background-color: #be7617;
    color: rgb(245, 166, 77);
    text-align: center;
    padding: 0;
    position: center;
    bottom: 0;
    width: 100%;
    height: 10%;
}
</style>
