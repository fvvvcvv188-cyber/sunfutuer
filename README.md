# sunfutuer<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجري الإلكتروني</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background: #333; color: #fff; padding: 1rem; text-align: center; }
        .container { display: flex; flex-wrap: wrap; justify-content: center; padding: 20px; }
        .product-card { 
            background: #fff; border: 1px solid #ddd; margin: 10px; 
            padding: 15px; width: 250px; text-align: center; border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product-card img { max-width: 100%; height: auto; border-radius: 5px; }
        .price { color: #27ae60; font-weight: bold; font-size: 1.2rem; }
        button { 
            background: #e67e22; color: white; border: none; 
            padding: 10px 20px; cursor: pointer; border-radius: 5px; margin-top: 10px;
        }
        button:hover { background: #d35400; }
    </style>
</head>
<body>

<header>
    <h1>مرحباً بك في متجري الجديد</h1>
</header>

<div class="container">
    <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="منتج">
        <h3>اسم المنتج الأول</h3>
        <p>وصف مختصر جداً عن المنتج ومميزاته.</p>
        <p class="price">150 ريال</p>
        <button>إضافة للسلة</button>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="منتج">
        <h3>اسم المنتج الثاني</h3>
        <p>وصف مختصر جداً عن المنتج ومميزاته.</p>
        <p class="price">200 ريال</p>
        <button>إضافة للسلة</button>
    </div>
</div>

</body>
</html>
