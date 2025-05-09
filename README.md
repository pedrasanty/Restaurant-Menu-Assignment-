# Restaurant-Menu-Assignment-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu Assignment</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 30px;
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
    }

    .menu {
      width: 400px;
      height: 550px;
      padding: 20px;
      margin: 10px;
      border: 3px solid #333;
      color: white;
      box-sizing: border-box;
      overflow-y: auto;
    }

    .breakfast {
      background-image: url('https://images.unsplash.com/photo-1504754524776-8f4f37790ca0');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
    }

    .lunch {
      background-image: url('https://images.unsplash.com/photo-1562967916-eb82221dfb36');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
    }

    .dinner {
      background-image: url('https://images.unsplash.com/photo-1605478002471-d8503f3f0036');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
    }

    h2 {
      border-bottom: 2px solid white;
      padding-bottom: 10px;
      margin-bottom: 15px;
      text-align: center;
    }

    ul {
      list-style-type: none;
      padding-left: 0;
    }

    li {
      margin-bottom: 10px;
      font-weight: bold;
      text-shadow: 1px 1px 2px #000;
    }
  </style>
</head>
<body>

  <div class="menu breakfast">
    <h2>Breakfast Menu</h2>
    <ul>
      <li>Pancakes with Syrup</li>
      <li>Scrambled Eggs</li>
      <li>Bacon Strips</li>
      <li>Fresh Fruit Bowl</li>
      <li>Orange Juice</li>
      <li>Coffee</li>
    </ul>
  </div>

  <div class="menu lunch">
    <h2>Lunch Menu</h2>
    <ul>
      <li>Grilled Chicken Sandwich</li>
      <li>Caesar Salad</li>
      <li>Tomato Soup</li>
      <li>Sweet Potato Fries</li>
      <li>Iced Tea</li>
      <li>Lemonade</li>
    </ul>
  </div>

  <div class="menu dinner">
    <h2>Dinner Menu</h2>
    <ul>
      <li>Steak with Mashed Potatoes</li>
      <li>Grilled Salmon</li>
      <li>Roasted Vegetables</li>
      <li>Pasta Alfredo</li>
      <li>Red Wine</li>
      <li>Chocolate Lava Cake</li>
    </ul>
  </div>

</body>
</html>
