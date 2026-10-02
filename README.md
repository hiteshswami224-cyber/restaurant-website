<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Spice Garden Restaurant</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#111;
    color:white;
}

header{
    background:#000;
    padding:15px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:1000;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:#ff9800;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    transition:0.3s;
}

nav a:hover{
    color:#ff9800;
}

.hero{
    height:100vh;
    background:url("https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=1600&q=80");
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

.hero-content{
    background:rgba(0,0,0,0.6);
    padding:40px;
    border-radius:15px;
}

.hero h1{
    font-size:60px;
    margin-bottom:15px;
}

.hero p{
    font-size:20px;
    margin-bottom:25px;
}

.btn{
    background:#ff9800;
    color:white;
    text-decoration:none;
    padding:12px 25px;
    border-radius:6px;
    font-weight:bold;
}

section{
    padding:80px 8%;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    color:#ff9800;
    font-size:40px;
}

.about{
    max-width:800px;
    margin:auto;
    text-align:center;
    line-height:1.8;
}

.menu{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:25px;
}

.card{
    background:#1e1e1e;
    border-radius:12px;
    overflow:hidden;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card-content{
    padding:20px;
}

.card h3{
    margin-bottom:10px;
}

.price{
    color:#ff9800;
    font-size:22px;
    margin-top:10px;
}

.reviews{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.review{
    background:#1e1e1e;
    padding:20px;
    border-radius:10px;
}

.contact{
    text-align:center;
}

.contact p{
    margin:10px 0;
}

footer{
    background:black;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
    <div class="logo">🍽 Spice Garden</div>

    <nav>
        #aboutAbout</a>
        #menuMenu</a>
        #reviewsReviews</a>
        #contactContact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Welcome to Spice Garden</h1>
        <p>Delicious Food • Great Atmosphere • Best Service</p>
        #menuView Menu</a>
    </div>
</section>

<section id="about">
    <h2 class="section-title">About Us</h2>

    <div class="about">
        <p>
            Spice Garden is a modern restaurant offering
            delicious food, premium quality ingredients,
            and an unforgettable dining experience.
            We bring together traditional flavours and
            modern cooking techniques.
        </p>
    </div>
</section>

<section id="menu">
    <h2 class="section-title">Our Menu</h2>

    <div class="menu">

        <div class="card">
            https://images.unsplash.com/photo-1565299624946-b28f40a0ca4e?auto=format&fit=crop&w=800&q=80
            <div class="card-content">
                <h3>Cheese Pizza</h3>
                <p>Loaded with premium cheese and fresh toppings.</p>
                <div class="price">₹299</div>
            </div>
        </div>

        <div class="card">
            https://images.unsplash.com/photo-1568901346375-23c9450c58cd?auto=format&fit=crop&w=800&q=80
            <div class="card-content">
                <h3>Classic Burger</h3>
                <p>Juicy burger with fresh vegetables and sauces.</p>
                <div class="price">₹149</div>
            </div>
        </div>

        <div class="card">
            https://images.unsplash.com/photo-1621996346565-e3dbc646d9a9?auto=format&fit=crop&w=800&q=80
            <div class="card-content">
                <h3>Pasta</h3>
                <p>Italian style creamy pasta made fresh daily.</p>
                <div class="price">₹249</div>
            </div>
        </div>

    </div>
</section>

<section id="reviews">
    <h2 class="section-title">Customer Reviews</h2>

    <div class="reviews">

        <div class="review">
            ⭐⭐⭐⭐⭐<br><br>
            Amazing food and excellent service.
        </div>

        <div class="review">
            ⭐⭐⭐⭐⭐<br><br>
            Best restaurant in town. Highly recommended.
        </div>

        <div class="review">
            ⭐⭐⭐⭐⭐<br><br>
            Great ambience and tasty dishes.
        </div>

    </div>
</section>

<section id="contact">
    <h2 class="section-title">Contact Us</h2>

    <div class="contact">
        <p>📍 Jodhpur, Rajasthan</p>
        <p>📞 +91 9876543210</p>
        <p>📧 info@spicegarden.com</p>
    </div>
</section>

<footer>
    Demo Project Created For Portfolio Purpose
</footer>

</body>
</html>
