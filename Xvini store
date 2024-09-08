<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر الملابس النسائية</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            color: #333;
            background: linear-gradient(to bottom, #000, #fff);
            background-attachment: fixed;
            overflow-x: hidden;
        }
        .header {
            background: linear-gradient(to right, #000, #333);
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }
        .header h1 {
            margin: 0;
            font-size: 2.5em;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7);
        }
        .nav {
            margin: 10px 0;
        }
        .nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
            font-size: 1.1em;
            position: relative;
        }
        .nav a::after {
            content: "";
            position: absolute;
            left: 0;
            bottom: -5px;
            width: 100%;
            height: 2px;
            background: #fff;
            transform: scaleX(0);
            transition: transform 0.3s ease;
        }
        .nav a:hover::after {
            transform: scaleX(1);
        }
        .hero {
            background: linear-gradient(to bottom, rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.5)), url('hero-image.jpg') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
            position: relative;
            overflow: hidden;
            animation: slideIn 2s ease-out;
        }
        @keyframes slideIn {
            from {
                transform: translateY(-100%);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }
        .hero h2 {
            font-size: 3em;
            margin: 0;
            z-index: 1;
            animation: fadeIn 2s ease-out;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
            background: #fff;
        }
        .product {
            background: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 30%;
            margin-bottom: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, box-shadow 0.3s;
            overflow: hidden;
            animation: fadeInUp 1s ease-out;
        }
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        .product:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        }
        .product img {
            width: 100%;
            border-bottom: 1px solid #ddd;
        }
        .product-info {
            padding: 15px;
        }
        .product-info h3 {
            margin: 0;
            font-size: 1.5em;
            color: #333;
        }
        .product-info p {
            margin: 5px 0;
            font-size: 1.1em;
        }
        .footer {
            background: linear-gradient(to right, #333, #000);
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        .footer a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        .cart {
            position: fixed;
            right: 20px;
            top: 20px;
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            padding: 15px;
            z-index: 1001;
            animation: slideInRight 0.5s ease-out;
        }
        @keyframes slideInRight {
            from {
                transform: translateX(100%);
                opacity: 0;
            }
            to {
                transform: translateX(0);
                opacity: 1;
            }
        }
        .cart h4 {
            margin: 0;
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .cart-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }
        .cart-item p {
            margin: 0;
        }
        .contact {
            padding: 20px;
            background: #f4f4f4;
            text-align: center;
        }
        .contact h2 {
            margin: 0;
            font-size: 2em;
            color: #333;
        }
        .contact form {
            max-width: 600px;
            margin: 20px auto;
        }
        .contact input, .contact textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact button {
            background: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            transition: background 0.3s ease;
        }
        .contact button:hover {
            background: #555;
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>متجر الملابس النسائية</h1>
        <nav class="nav">
            <a href="#home">الرئيسية</a>
            <a href="#products">المنتجات</a>
            <a href="#contact">اتصل بنا</a>
        </nav>
    </header>
    <section class="hero">
        <h2>أحدث موديلات الملابس النسائية</h2>
    </section>
    <section id="products" class="products">
        <div class="product">
            <img src="product1.jpg" alt="منتج 1">
            <div class="product-info">
                <h3>منتج 1</h3>
                <p>سعر: 1000 ج.س</p>
            </div>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="منتج 2">
            <div class="product-info">
                <h3>منتج 2</h3>
                <p>سعر: 1500 ج.س</p>
            </div>
        </div>
        <!-- أضف المزيد من المنتجات هنا -->
    </section>
    <section id="contact" class="contact">
        <h2>مكتب الاستعلامات</h2>
        <form action="submit_form.php" method="post">
            <input type="text" name="name" placeholder="اسمك" required>
            <input type="email" name="email" placeholder="بريدك الإلكتروني" required>
            <textarea name="message" rows="4" placeholder="رسالتك" required></textarea>
            <button type="submit">إرسال</button>
        </form>
    </section>
    <div class="cart">
        <h4>عربة التسوق</h4>
        <!-- مثال على عناصر العربة، يمكن تحديثه ديناميكيًا عبر جافا سكريبت -->
        <div class="cart-item">
            <p>منتج 1</p>
            <p>1000 ج.س</p>
        </div>
        <div class
