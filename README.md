# Ex.07 Restaurant Website
# Date:22-11-20224
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
main.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to BERRY BLISS</h1>
        <nav>
            <ul>
                <li><a href="C:\Users\admin\Documents\menu.html">Menu</a></li>
                <li><a href="C:\Users\admin\Documents\about us.html">About Us</a></li>
                <li><a href="C:\Users\admin\Documents\about us.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h2>Experience the Best Cuisine</h2>
        <p>Join us for a delightful dining experience.</p>
    </section>
    
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\menu.html"><img src="C:\Users\admin\Documents\d.jpg" alt="sizzling brownie"></a>
            <h3>Desserts</h3>
        </div>
        <div class="menu-item">
           <a href="C:\Users\admin\Documents\menu.html"><img src="C:\Users\admin\Documents\cd.jpg" alt="Margherita Pizza"></a> 
            <h3>Cold Drinks</h3>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\menu.html"> <img src="C:\Users\admin\Documents\b.jpg" alt="Caesar Salad"></a>
            <h3>Beverages</h3>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 My Restaurant. All rights reserved.</p>
    </footer>
</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1>Welcome to BERRY BLISS</h1>
    </header>
    <section id="menu">
        <h2>Desserts</h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\brownies.jpg"  alt="sizzling brownie">
            <h3>sizzling brownie</h3>
            <p>₹120</p>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\cake.html"><img src="C:\Users\admin\Documents\cake.jpg" alt="Caesar Salad"></a> 
            <h3>Cake</h3>
        </div>
        <div class="menu-item">
            <a href= "C:\Users\admin\Documents\falooda.html"> <img src="C:\Users\admin\Documents\falooda.jpg" alt="Grilled Salmon"></a>
            <h3>Falooda</h3>
        </div>
        <div class="menu-item">
            <img src= "C:\Users\admin\Documents\tiramusu.jpg" alt="Grilled Salmon">
             
            <h3>Tiramusu</h3>
            <p>₹120</p>


        </div>
        <div class="menu-item">
            <a href= "C:\Users\admin\Documents\ice cream.html"><img src= "C:\Users\admin\Documents\ic.jpg" alt="Grilled Salmon"></a>
            <h3>Ice Cream</h3>
        </div>
    </section>
    <section id="menu">
        <h2>Cold Drinks</h2>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\cold drinks.html"><img src="C:\Users\admin\Documents\cold drinks.jpg" alt="sizzling brownie"></a>
            <h3>Carbonate Drinks</h3>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\lassi.html"><img src="C:\Users\admin\Documents\lassi.jpg" alt="Margherita Pizza"></a>
            
            <h3>Lassi</h3>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\fresh juice.html"> <img src="C:\Users\admin\Documents\fresh juice.jpg" alt="Caesar Salad"></a>
           
            <h3>Fresh Fruit Juice</h3>
        </div>
        <div class="menu-item">
            <a href="C:\Users\admin\Documents\Milkshake.html"><img src= "C:\Users\admin\Documents\milkshake.jpg" alt="Grilled Salmon"></a>
            
            <h3>Milkshake</h3>
        </div>
    </section>
    <section id="menu">
        <h2> Beverages</h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\hot chocolate.jpg" alt="sizzling brownie">
            
            <h3>Hot chocolate</h3>
            <p>₹150</p>

        </div>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\tea.jpg" alt="Margherita Pizza">
            <p>₹30</p>
          
            <h3>tea</h3>
             
        </div>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\coffee.jpg" alt="Caesar Salad">
           
            <h3>coffee</h3>
            <p>₹50</p>
        </div>
        <div class="menu-item">
             <img src="C:\Users\admin\Documents\cold  coffee.jpg" alt="Grilled Salmon">
           
            <h3>Cold coffee</h3>
            <p>₹150</p>
        </div>
    </section>

</body>
</html>

about us.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section id="about">
        <h2>About Us</h2>
        <p>We are dedicated to serving fresh, high-quality food in a warm and welcoming atmosphere. Our chefs use the finest ingredients to create mouthwatering dishes that you'll love.</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@myrestaurant.com</p>
        <p>Phone: (123) 456-7890</p>
        <p>Address: 123 Main St, Hometown, USA</p>
    </section>
    <section id="table">
    <table style="background-color: beige; width: 100%; height: 500px;">
        <tr>
            <th style="font-size: xx-large;"><b>Follow us on:</b>
                <br>
          
                <a href="https://www.youtube.com/"><img src="youtube.jpg" title="youtube" style="width: 100px; height: 80px;"></a>
                <br>
                
                <a href="https://www.youtube.com/"><img src="insta.jpg" title="Instagram" style="width: 100px; height: 80px;"></a>
                <br>
                
                <a href="https://www.youtube.com/"><img src="fb.png" title="Face Book" style="width: 100px; height: 80px;"></a>
            </th>
        </tr>
    </table>
    </section>
</body>
</html>
cakes.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desserts</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1>Cakes</h1>
    </header>
    <section id="menu">
        <h2>BLack Forest Cake <br><p>₹1500</p><br><p>This Black Forest Cake combines rich chocolate cake layers <br>with fresh cherries, cherry liqueur, and a simple whipped cream frosting.</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\black forest.jpg"  alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>White Forest Cake <br><p>₹1200</p><br><p>This White Forest Cake combines rich  White cake layers <br>with fresh cherries, cherry liqueur, and a simple whipped cream frosting.</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\WHITE-FOREST.jpg"alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Red Velvet Cake <br><p>₹1700</p><br><p>Red velvet cake is a moist, rich, and vibrantly colored layer<br> cake that's often topped with cream cheese frosting. </p></h2>
        <div class="menu-item">
            <img src= "C:\Users\admin\Documents\red velvet.jpg" alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Chocolate Cake <br><p>₹1200</p><br><p>This Chocolate Cake combines rich chocolate cake layers <br>with fresh cherries, cherry liqueur, and a simple whipped cream frosting.</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\cho.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>
falooda.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desserts</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1> FaloodaSS</h1>
    </header>
    <section id="menu">
       <h2>Dry Fruit Falooda<br><p>₹150</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\dry friut.jpg"  alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Fruit Falooda<br><p>₹100</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\fruit faloo.jpg"alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2> Chocolate Falooda<br><p>₹120</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\chocolate falooda.jpg"  alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Butter Scotch Falooda<br><p>₹110</p></h2>
         <div class="menu-item">
            <img src="C:\Users\admin\Documents\butterscotch.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>

icecream.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desserts</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1> Ice Cream</h1>
    </header>
    <section id="menu">
       <h2>Chocolate Ice Cream<br><p>₹150</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\chocolate ice cream.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Vannila Ice Cream<br><p>₹100</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\vannila.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Mango Ice Cream<br><p>₹120</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\mango.jpg"  alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Butter Scotch Ice Cream<br><p>₹110</p></h2>
         <div class="menu-item">
            <img src="C:\Users\admin\Documents\bs icecream.jpg"alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>

carbonatedrinks.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cold Drinks</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1> Carbonate Drinks</h1>
    </header>
    <section id="menu">
       <h2>Coke<br><p>₹50</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\coke.jpg"alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>spirit<br><p>₹40</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\sprit.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Fanta<br><p>₹40</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\fanta.jpg"  alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Soda<br><p>₹50</p></h2>
         <div class="menu-item">
            <img src="C:\Users\admin\Documents\soda.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>
lassi.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cold Drinks</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1> Lassi</h1>
    </header>
    <section id="menu">
       <h2>Mango Lassi<br><p>₹150</p></h2>
        <div class="menu-item">
            <img src= "C:\Users\admin\Documents\m lassi.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Strawberry Lassi<br><p>₹140</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\s lassi.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Chocolate Lassi<br><p>₹140</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\cho lassi.jpg"  alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Kesar Lassi<br><p>₹150</p></h2>
         <div class="menu-item">
            <img src= "C:\Users\admin\Documents\k lassi.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>

fresh juice.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cold Drinks</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1>Fresh Fruit Juice</h1>
    </header>
    <section id="menu">
       <h2>Orange Juice<br><p>₹50</p></h2>
        <div class="menu-item">
            <img src= "C:\Users\admin\Documents\o juice.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Lemon Juice<br><p>₹40</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\l jucie.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2> WaterMelon Juice<br><p>₹40</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\w juice.jpg"alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Apple Juice<br><p>₹150</p></h2>
         <div class="menu-item">
            <img src="C:\Users\admin\Documents\a juice.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>
milkshake.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cold Drinks</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1>Milkshake</h1>
    </header>
    <section id="menu">
       <h2>Mango Milkshake<br><p>₹150</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\m ms.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Strawberry Milkshake<br><p>₹140</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\s ms.jpg" alt="sizzling brownie">
        </div>
    </section>
    <section id="menu">
        <h2>Chocolate Milkshake<br><p>₹140</p></h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Documents\c ms.jpg" alt="sizzling brownie">
             
        </div>
    </section>
    <section id="menu">
        <h2>Vannila Milkshake<br><p>₹150</p></h2>
         <div class="menu-item">
            <img src= "C:\Users\admin\Documents\v ms.jpg" alt="sizzling brownie">
            
        </div>
    </section>

</body>
</html>
styles.css

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: bisque;
    color: #140a0a;
}

header {
    background-image: url("bb2.jpg");
    color: #0b063d;
    text-align: center;
    padding: 40px;
    font-family:'Times New Roman';
    background-size: contain;
    font-size: x-large;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #040c06;
    text-decoration: none;
    font-size: x-large;
    background-color: #ffffff;
}

#hero {
    background-image: url("avout.png");
    color: rgb(6, 15, 45);
    padding: 50px 0;
    text-align: center;
    font-size: x-large;
    background-size: cover;
}

#hero .btn {
    background: #35424a;
    color: #a70fe8;
    padding: 8px 15px;
    text-decoration: none;
}

#menu {
    padding: 15px;
    margin: 30px;
    background: #0e0558;
    border-radius: 8px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    color: white;
}

.menu-item {
    text-align: center;
    margin: 15px;
}

.menu-item img {
    width: 250px;
    height: 250px;
    border-radius: 8px;
}

h2 {
    margin-bottom: 15px;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: aliceblue;
    border-radius: 8px;
    color: rgb(174, 12, 109);
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #35424a;
    color: #ffffff;
    position: relative;
    bottom: 0;
    width: 100%;
}

styles1.css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: bisque;
    color: #140a0a;
}

header {
    background-image: url("bb2.jpg");
    color: #0b063d;
    text-align: center;
    padding: 70px;
    font-family:'Times New Roman';
    background-size: contain;
    font-size: x-large;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #040c06;
    text-decoration: none;
    font-size: x-large;
    background-color: #ffffff;
}

#hero {
    background-image: url("avout.png");
    color: rgb(6, 15, 45);
    padding: 100px 0;
    text-align: center;
    font-size: x-large;
    background-size: cover;
}

#hero .btn {
    background: #35424a;
    color: #a70fe8;
    padding: 10px 20px;
    text-decoration: none;
}

#menu {
    padding: 50px;
    margin: 50px;
    background: #0e0558;
    border-radius: 8px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    color: white;
}

.menu-item {
    text-align: center;
    margin: 15px;
}

.menu-item img {
    width: 250px;
    height: 250px;
    border-radius: 8px;
}

h2 {
    margin-bottom: 15px;
}

section {
    padding: 40px;
    margin: 40px;
    background-color: aliceblue;
    border-radius: 8px;
    color: rgb(174, 12, 109);
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #35424a;
    color: #ffffff;
    position: relative;
    bottom: 0;
    width: 100%;
}

```

# OUTPUT:
![Screenshot (70)](https://github.com/user-attachments/assets/f45b304f-9253-4d28-9ea4-0f3422ca963e)

![Screenshot (71)](https://github.com/user-attachments/assets/a9bbdb4f-7d09-4305-833c-dfc6e88910d9)
![Screenshot (72)](https://github.com/user-attachments/assets/b89ba7cd-6f6e-4dc1-aeec-3675c77f65c7)
![Screenshot (73)](https://github.com/user-attachments/assets/b5d6a854-6131-41ef-b3ea-2b18d8764e09)
![Screenshot (74)](https://github.com/user-attachments/assets/1f8a5cfa-a19d-4cff-8e92-f6837040ea86)
![Screenshot (75)](https://github.com/user-attachments/assets/8476fac8-9cc3-46f8-a80c-5218f5a85625)
![Screenshot (76)](https://github.com/user-attachments/assets/eb8fae26-6de7-4338-b316-02e7768ae77d)
![Screenshot (77)](https://github.com/user-attachments/assets/2c64d996-c0cd-46ba-ab1e-4f7768d7562d)
![Screenshot (78)](https://github.com/user-attachments/assets/3cedf715-4e4a-4f8e-917f-22c22dcb233f)
![Screenshot (79)](https://github.com/user-attachments/assets/25c59a08-5b9d-411e-bde0-1e6ae6d0b1f3)
![Screenshot (80)](https://github.com/user-attachments/assets/a78e334f-83d8-4328-b8a8-a70b573a6a43)
![Screenshot (81)](https://github.com/user-attachments/assets/138a2630-a561-4423-bf77-6fcb728d6563)
![Screenshot (82)](https://github.com/user-attachments/assets/0b7bd518-d4df-4c1f-b08f-ce0b8c80036e)
![Screenshot (83)](https://github.com/user-attachments/assets/273d476d-1a52-4f22-b0e3-83e894dcfc1a)
![Screenshot (84)](https://github.com/user-attachments/assets/106c6cec-0b68-4acc-a272-e7ecea291b64)
![Screenshot (85)](https://github.com/user-attachments/assets/c4e148ac-d9b0-4bfb-aef4-bb3a8f66e777)
![Screenshot (86)](https://github.com/user-attachments/assets/0088c9fa-2255-4ed2-acf3-c70c465e7c24)
![Screenshot (87)](https://github.com/user-attachments/assets/60d812e8-8904-4902-83dd-4e2cbaef4519)
![Screenshot (88)](https://github.com/user-attachments/assets/a2ecdb07-1df1-4151-848a-4ac98c63848f)
![Screenshot (89)](https://github.com/user-attachments/assets/14193bb6-55c4-4798-8906-0010c9a39680)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
