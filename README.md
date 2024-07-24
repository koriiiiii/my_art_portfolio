# my_art_portfolio<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Art Portfolio</title>
    <style>
        body { font-family: Arial, sans-serif; }
        .gallery { display: flex; flex-wrap: wrap; gap: 10px; }
        .gallery img { max-width: 100%; height: auto; }
        .item { flex: 1 1 30%; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
    </style>
</head>
<body>
    <header>
        <h1>My Art Portfolio</h1>
    </header>
    <main>
        <section class="gallery">
            <!-- 添加艺术作品图片 -->
            <div class="item"><img src="path/to/your/image1.jpg" alt="Artwork 1"></div>
            <div class="item"><img src="path/to/your/image2.jpg" alt="Artwork 2"></div>
            <!-- 添加更多图片 -->
        </section>
    </main>
</body>
</html>
