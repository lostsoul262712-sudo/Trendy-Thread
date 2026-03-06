<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Trendy Thread | Fashion Beauty Electronics</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins;
}

body{
background:#f4f6f9;
}

header{
background:#111;
color:white;
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 8%;
}

.logo{
font-size:24px;
font-weight:700;
}

nav a{
color:white;
margin:0 15px;
text-decoration:none;
}

.hero{
background:linear-gradient(120deg,#ff512f,#dd2476);
height:60vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
color:white;
text-align:center;
}

.hero h1{
font-size:48px;
}

.search-box{
margin-top:20px;
}

.search-box input{
padding:10px;
width:250px;
border:none;
border-radius:5px;
}

.container{
padding:60px 8%;
}

.section-title{
font-size:32px;
margin-bottom:25px;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:12px;
overflow:hidden;
box-shadow:0 8px 20px rgba(0,0,0,0.08);
transition:0.3s;
}

.card:hover{
transform:translateY(-5px);
}

.card img{
width:100%;
}

.card-content{
padding:18px;
}

.card h3{
margin-bottom:10px;
font-size:18px;
}

.card p{
font-size:14px;
margin-bottom:10px;
}

.btn{
display:inline-block;
background:#ff2d55;
color:white;
padding:8px 14px;
text-decoration:none;
border-radius:6px;
}

footer{
background:#111;
color:white;
text-align:center;
padding:25px;
margin-top:50px;
}

</style>

</head>

<body>

<header>

<div class="logo">Trendy Thread</div>

<nav>
<a href="#">Home</a>
<a href="#fashion">Fashion</a>
<a href="#beauty">Beauty</a>
<a href="#electronics">Electronics</a>
</nav>

</header>


<section class="hero">

<h1>Trendy Thread</h1>
<p>Best Fashion, Beauty & Tech Deals</p>

<div class="search-box">
<input type="text" placeholder="Search products...">
</div>

</section>


<div class="container" id="fashion">

<h2 class="section-title">Fashion</h2>

<div class="products">

<div class="card">
<img src="https://via.placeholder.com/300">
<div class="card-content">
<h3>Stylish Women's Handbag</h3>
<p>Trendy design perfect for daily use</p>
<a class="btn" href="YOUR_AMAZON_LINK">View Deal</a>
</div>
</div>

<div class="card">
<img src="https://via.placeholder.com/300">
<div class="card-content">
<h3>Men Casual Watch</h3>
<p>Premium design fashion watch</p>
<a class="btn" href="YOUR_AMAZON_LINK">View Deal</a>
</div>
</div>

</div>
</div>


<div class="container" id="beauty">

<h2 class="section-title">Beauty</h2>

<div class="products">

<div class="card">
<img src="https://via.placeholder.com/300">
<div class="card-content">
<h3>Vitamin C Face Serum</h3>
<p>Bright glowing skin formula</p>
<a class="btn" href="YOUR_AMAZON_LINK">View Deal</a>
</div>
</div>

<div class="card">
<img src="https://via.placeholder.com/300">
<div class="card-content">
<h3>Professional Makeup Kit</h3>
<p>Complete beauty set</p>
<a class="btn" href="YOUR_AMAZON_LINK">View Deal</a>
</div>
</div>

</div>
</div>


<div class="container" id="electronics">

<h2 class="section-title">Electronics</h2>

<div class="products">

<div class="card">
<img src="https://via.placeholder.com/300">
<div class="card-content">
<h3>Wireless Earbuds</h3>
<p>Noise cancellation & deep bass</p>
<a class="btn" href="YOUR_AMAZON_LINK">View Deal</a>
</div>
</div>

<div class="card">
<img src="https://via.placeholder.com/300">
<div class="card-content">
<h3>Smart Watch</h3>
<p>Fitness & health tracking</p>
<a class="btn" href="YOUR_AMAZON_LINK">View Deal</a>
</div>
</div>

</div>
</div>


<footer>

<p>© 2026 Trendy Thread | Affiliate Store</p>

</footer>

</body>
</html>
