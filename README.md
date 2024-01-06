# LAB-01-FSD
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Food Company</title>

    <style>
        body {
            margin: 0;
            font-family: 'Bell MT', Tahoma, Geneva, Verdana, sans-serif;
        }

        header {
            background-color: red; /* Orange color */
            color: white;
            text-align: center;
            padding: 15px;
        }

        .hero-section {
      height: 100vh; 
      background-image: url('https://i.pinimg.com/564x/49/50/c4/4950c49ef2e04cc84d2f7539dad6de38.jpg'); /* Replace 'your-image.jpg' with the path to your image */
      background-size: cover; 
      background-position: center; 
      color: black; 
      text-align: center;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }

    .hero-text {
      font-size: 2em;
    }
        .product-section {
            padding: 30px;
            text-align: center;
        }

        .product-card {
            display: inline-block;
            margin: 20px;
            text-align: left;
            max-width: 300px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .product-image {
            width: 100%;
            height: auto;
            border-radius: 10px 10px 0 0;
        }

        .product-info {
            padding: 15px;
        }

        .product-title {
            font-size: 1.2em;
            margin-bottom: 10px;
            color: black;
        }

        .product-description {
            font-size: 1em;
            color: rgb(241, 10, 10);
        }
    </style>
</head>
<body>

    <header>
        <h1>TastyTwist</h1>
        <p>COMING SOON</p>
    </header>

    <div class="hero-section">
        <img src="https://i.pinimg.com/564x/33/ef/8b/33ef8b9c0b902154a6cd4103a21275ef.jpg" alt="Delicious Food">
        <p>Delicious Food, Delivered to Your Doorstep</p>
        <p>Experience the ultimate culinary delight with our diverse menu options.</p>
      <p>Savor the convenience and indulge in a gastronomic journey from the comfort of your home.</p>
    </div>

    <div class="product-section">

        <!-- Product Card 1 -->
        <div class="product-card">
            <img class="product-image" src="https://img.onmanorama.com/content/dam/mm/en/food/features/images/2021/10/17/pizza.jpg.transform/576x300/image.jpg" alt="Product Image">
            <div class="product-info">
                <h3 class="product-title">Gourmet Pizza</h3>
                <p class="product-description">A mouthwatering blend of fresh ingredients on a crispy crust.</p>
                
            </div>
        </div>

        <!-- Product Card 2 -->
        <div class="product-card">
            <img class="product-image" src="https://www.hotelmousai.com/blog/wp-content/uploads/2021/11/Chinise-food-768x527.jpg" alt="Product Image">
            <div class="product-info">
                <h3 class="product-title">Chinese Platter</h3>
                <p class="product-description">Exquisite chinese rolls made with the finest ingredients.</p>
                
            </div>
        </div>

        <!-- Product Card 3 -->
        <div class="product-card">
            <img class="product-image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS-FKTLm8lNzY7piCbPOakhW1ikQTsTj2O9Dg&usqp=CAU" alt="Product Image">
            <div class="product-info">
                <h3 class="product-title">Veg/Chicken Burger</h3>
                <p class="product-description">Exquisite burgers made with the finest ingredients.</p>
    </div>

</body>
</html>
