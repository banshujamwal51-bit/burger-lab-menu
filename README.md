<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Burger Lab Menu</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background:#2b2438;
    color:white;
}

.container{
    display:grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap:20px;
    padding:20px;
}

.section{
    background:#3a3250;
    padding:15px;
    border-radius:10px;
}

.section h2{
    background:#ffd600;
    color:black;
    text-align:center;
    padding:6px;
    border-radius:20px;
    margin-top:0;
}

.item{
    display:flex;
    justify-content:space-between;
    margin:5px 0;
}

.price{
    color:#ffd600;
}

.footer{
    background:#ffb300;
    color:black;
    text-align:center;
    padding:15px;
    font-weight:bold;
}
</style>
</head>

<body>

<div class="container">

<!-- LEFT COLUMN -->
<div class="section">
<h2>BURGERS</h2>
<div class="item"><span>Aloo Tikki Burger</span><span class="price">40</span></div>
<div class="item"><span>Veggie Burger</span><span class="price">60</span></div>
<div class="item"><span>Cheesy Burger</span><span class="price">70</span></div>
<div class="item"><span>Crispy Burger</span><span class="price">80</span></div>
<div class="item"><span>Spicy Burger</span><span class="price">80</span></div>
<div class="item"><span>Paneer Burger</span><span class="price">110</span></div>

<h2>PASTA</h2>
<div class="item"><span>Red Sauce Pasta</span><span class="price">90</span></div>
<div class="item"><span>White Sauce Pasta</span><span class="price">90</span></div>
<div class="item"><span>Hot & Spicy Pasta</span><span class="price">110</span></div>
<div class="item"><span>Mix Pasta</span><span class="price">120</span></div>
<div class="item"><span>Baked Pasta</span><span class="price">130</span></div>
</div>

<!-- MIDDLE COLUMN -->
<div class="section">
<h2>WRAPS</h2>
<div class="item"><span>Veg Wrap</span><span class="price">90</span></div>
<div class="item"><span>Signature Veg Wrap</span><span class="price">130</span></div>
<div class="item"><span>Mexican Wrap</span><span class="price">130</span></div>
<div class="item"><span>Makhani Wrap</span><span class="price">140</span></div>

<h2>SHAKES</h2>
<div class="item"><span>Mango / Vanilla</span><span class="price">80</span></div>
<div class="item"><span>Strawberry / Oreo</span><span class="price">100</span></div>
<div class="item"><span>Kitkat</span><span class="price">110</span></div>
<div class="item"><span>Cold Coffee</span><span class="price">110</span></div>
<div class="item"><span>Choco Frappe</span><span class="price">110</span></div>

<h2>FRIES</h2>
<div class="item"><span>French Fries</span><span class="price">80</span></div>
<div class="item"><span>Masala Fries</span><span class="price">90</span></div>
<div class="item"><span>Peri Peri Fries</span><span class="price">90</span></div>
<div class="item"><span>Creamy Fries</span><span class="price">110</span></div>
</div>

<!-- RIGHT COLUMN -->
<div class="section">
<h2>PIZZA MANIA</h2>
<div class="item"><span>Onion Pizza</span><span class="price">59</span></div>
<div class="item"><span>Capsicum Pizza</span><span class="price">70</span></div>
<div class="item"><span>Mushroom Pizza</span><span class="price">70</span></div>

<h2>SPECIAL VEG</h2>
<div class="item"><span>Cheese Chilly</span><span class="price">270</span></div>
<div class="item"><span>Paneer Exotic</span><span class="price">270</span></div>
<div class="item"><span>Spicy Fire Pizza</span><span class="price">270</span></div>
</div>

</div>

<div class="footer">
FREE HOME DELIVERY 📞 86278-16659 | 86270-16659
</div>

</body>
</html>
