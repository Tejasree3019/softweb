# Ex.07 Restuarant Website
## Date:12-11-2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<html>
<head>
    <link href="design.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">        
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
    </script>
  
  <title>Siji Minfu chinese Restaurant</title>
  <style>
    
    .navi
    {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }

    .banner {
      background-image: url("bg.jpeg"); 
      background-size: cover;
      background-position: center;
      height: 250px;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      color: rgb(21, 21, 21);
      text-shadow: 2px 2px 6px rgba(15, 14, 14, 0.7);
      word-spacing: 30;
    }

    .banner h1 {
      font-family: 'TIMES NEW ROMAN';
      font-size: 50px;
      margin: 0;
      font-weight: bold;
    }
    
    .box-section {
      display: flex;
      flex-direction: row;
      justify-content: flex-start;
      gap: 50px;
      margin-top: 40px;
      margin-left: 40px;   
      margin-right: 40px;
    }

    .info-box {
      background-color:rgb(135, 141, 108); /* Dark red */
      color: rgb(244, 244, 244);
      width: 700px;
      height: 380px;
      display: flex;
      font-family: 'times new roman';
      font-weight: bold;
      border-radius: 10px;
      font-size: 17px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    
    .menu-content h3 {
      margin-left: 30;
      font-size: 17px;
      margin-bottom: 4px;
    }
    
    .menu-content h2 {
      margin-left: 50;
      font-size: 17px;
      margin: top 1px;
      font-family:'times new roman';
      font-weight: bold;
    }

    .menu-content p {
      margin-left: 50;
      font-size: 17px;
      margin-bottom: 10px;
      font-weight: normal;
    }
    
    .image {
      margin-left: 100;
    }
  </style>
</head>
<body>
    <div class="navi">
    <nav class="navbar navbar-expand-sm bg-dark">
            <ul class="navbar-nav">
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="home.html">HOME</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="menu.html">MENU</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="team.html">DEMON SLAYER TEAM</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="contact.html">CONTACT US</a>
                </li>
            </ul>
        </nav>
    </div>

  <div class="banner">
  
    <h1>SIJI MINFU CHINESE RESTAURANT</h1> 
  </div>
  
    <div class="box-section">
        <div class="info-box">
          <div class="menu-content">
            <center>
                <br>
              <h2>OUR SPECIALITIES:</h2>
            <center><img class="image" src="Dan Dan Noodles.jpg" height="190" width="190"></center>
            <h3 style="margin-top: 4;">*  Dan Dan Noodles</h3>
              <p>Spicy, numbing, savory, Sichuan, minced pork, chili oil, sesame paste. </p>
              <h3 style="margin-top: 4;">*  Lo Mein</h3>
              <p>Stir-fried, soy sauce, savory, soft noodles,Chinese cuisine, customizable protein.</p>
              
            </center>
          </div>
        </div>
          
        <div class="info-box">
          <div class="menu-content">
            <center>
            <br>
              <h2>BOOK YOUR TABLE:</h2>
            <center><img class="image" src="tables.jpg" width="190" height="190"></center>
              <h3 style="margin-top: 9;">Skip the wait, savor the taste book your seats today!</h3>
              <p style="margin-top: 9;"> Experience authentic Chinese dining</p>
              <p style="margin-top: 9;"> Reservations recommended for dinner service</p>
            </center>
          </div>
        </div>
        
        <div class="info-box">
          <div class="menu-content">
            <center>
                <br>
              <h2>OPENING HOURS :</h2>
            <center><img class="image" src="timing.jpg" width="190" height="190"></center>
              <h3 style="margin-top: 9;">Our Service Hours</h3>
              <p style="margin-top: 9;">Day : Monday - Sunday</p>
              <p style="margin-top: 9;">Timings : 11:00 am to 10:00 pm</p>
              <p style="margin-top: 9;">Open on all Days</p>
            </center>
          </div>
        </div>
      </div>
</body>
<footer style="background-color:#333;height:150px;width:100%;color:white;text-align:center;font-family:'Times New Roman', Times, serif;font: size 15px;margin-top:30px;">
    <h2 style="font-size:large;">Email : Sijuminfurestaurant@gmail.com</h2>
    <h2 style="font-size:medium;">Contact Number: +86 10-1234-5678</h2><br>
    <h2 style="font-size:medium;">Address: 北京市东城区王府井大街1号 (1 Wangfujing Street, Dongcheng District, Beijing 100006, China)</h2>
    <h2 style="font-size:medium;">----------中華之魂 (Zhōnghuá zhī hún - Spirit of China)----------</h2>
</footer>
</html>

menu.html

<html>
<head>
    <link href="design.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">        
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
    </script>
  
  <title>Menu - Siju Minfu Chinese Restaurant</title>
  <style>
    .navi {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    
    .menu-section {
      background-color: #39b5b1;
      padding: 30px;
      color: #fff;
      text-align: center;
      font-family: 'times new roman';
      font-weight: bold;
    }

    .menu-title {
      color: white;
      font-size: 32px;
      margin-bottom: 30px;
      font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-weight: bold;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      justify-items: center;
    }

    .menu-card {
      background-color: white;
      color: black;
      border-radius: 8px;
      overflow: hidden;
      width: 200px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      text-align: center;
      border: 1px solid #D4AF37;
    }

    .menu-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .menu-card h3 {
      font-size: 18px;
      margin: 10px 0 5px;
      color: #8B0000;
    }

    .menu-card p {
      font-size: 14px;
      padding: 0 10px 10px;
    }
  </style>
</head>
<body>
    <div class="navi">
    <nav class="navbar navbar-expand-sm bg-dark">
            <ul class="navbar-nav">
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="home.html">HOME</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="menu.html">MENU</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="team.html">Golden Pagodas TEAM</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="contact.html">CONTACT US</a>
                </li>
            </ul>
        </nav>
    </div>
    
    <div class="menu-section">
      <h2 class="menu-title">OUR CHINESE MENU</h2>
      <div class="menu-grid">
        <div class="menu-card">
          <img src="Dragon Pearl Dumplings.jpg" alt="Dragon Pearl Dumplings">
          <h3>Dragon Pearl Dumplings</h3>
          <p>Delicate parcels of juicy prawn wrapped in translucent silk, bursting with ocean-fresh flavor.</p>
        </div>
        <div class="menu-card">
          <img src="Ramen.jpg" alt="Ramen">
          <h3>"Samurai Slurp Ramen"</h3>
          <p>Rich, slow-simmered broth with springy noodles, tender meats, and umami in every slurp-worthy bite</p>
        </div>
        <div class="menu-card">
          <img src="Golden Silk Rolls.jpg" alt="Wagyu">
          <h3>Golden Silk Rolls</h3>
          <p>Crispy, golden wraps filled with a savory medley of vegetables and spices, rolled to perfection</p>
        </div>
        <div class="menu-card">
          <img src="Fire Dragon Chicken.jpg" alt="Tempura">
          <h3>Fire Dragon Chicken</h3>
          <p>Fiery, crispy chicken tossed in a bold chili-garlic glaze, roaring with flavor in every bite.</p>
        </div>
        <div class="menu-card">
          <img src="Szechuan Heat Tofu Bowl.jpg" alt="Udon">
          <h3>Szechuan Heat Tofu Bowl</h3>
          <p>Silky tofu drenched in a fiery, numbing Szechuan sauce, served over a bed of fragrant rice</p>
        </div>
        <div class="menu-card">
          <img src="Cloud Puff Bao.jpg" alt="Yakitori">
          <h3>Cloud Puff Bao</h3>
          <p>Soft, pillowy steamed buns embracing savory fillings for a heavenly bite every time.</p>
        </div>
        <div class="menu-card">
          <img src="Velvet Harmony Sauce.jpg" alt="Bento">
          <h3>Velvet Harmony Sauce</h3>
          <p>A rich, glossy gravy blending savory and umami flavors to perfectly elevate any dish.</p>
        </div>
        <div class="menu-card">
          <img src="Imperial Pearl Delight.jpg" alt="Matcha">
          <h3>Imperial Pearl Delight</h3>
          <p>Exquisite Chinese delicacy served on a natural palm leaf, crowned with luxurious caviar for a royal touch. </p>
        </div>
        <div class="menu-card">
          <img src="Emperor's Pork Noodles.jpg" alt="Sashimi">
          <h3>Emperor's Pork Noodles</h3>
          <p>Tender pork slices tossed with hand-pulled noodles in a savory, aromatic sauce that commands attention</p>
        </div>
        <div class="menu-card">
          <img src="Golden Lotus Egg Tar.jpg" alt="Tart">
          <h3>Golden Lotus Egg Tar</h3>
          <p>Buttery, flaky crust cradling a smooth, velvety custard that melts in every bite.</p>
        </div>
        <div class="menu-card">
          <img src="Silken Mango Bliss.jpg" alt="Pudding">
          <h3>Silken Mango Bliss</h3>
          <p>Creamy, refreshing mango pudding with a tropical sweetness that delights the palate</p>
        </div>
        <div class="menu-card">
          <img src="“Silk Cloud Mochi.jpg" alt="Mochi">
        <h3>“Silk Cloud Mochi</h3>
          <p>Soft rice cakes filled with sweet red bean paste</p>
        </div>
      </div>
    </div>
</body>
<footer style="background-color:#333;height:150px;width:100%;color:white;text-align:center;font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;font-size:5px;margin-top:30px;">
    <h2 style="font-size:medium; margin-top:4px;">Email : Sijuminfurestaurant@gmail.com</h2>
    <h2 style="font-size:medium;">Contact number : +86 10-1234-5678</h2><br>
    <h2 style="font-size:medium;">Address: 北京市东城区王府井大街1号 (1 Wangfujing Street, Dongcheng District, Beijing 100006, China)</h2>
    <br>
    <h2 style="font-size:medium;">----------中華之魂 (Zhōnghuá zhī hún - Spirit of China)----------</h2>
</footer>
</html>

team.html

<html>
<head>
    <link href="design.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">        
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
    </script>
  
  <title>Golden Pagodas Team - Siju Minfu Chinese Restaurant</title>
  <style>
    .navi {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    
    .menu-section {
      background-color: #2da3ba;
      padding: 30px;
      color: #fff;
      text-align: center;
      font-family: 'times new roman';
      font-weight: bold;
      
    }

    .menu-title {
      color: white;
      font-size: 32px;
      margin-bottom: 30px;
      font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-weight: bold;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      justify-items: center;
    }

    .menu-card {
      background-color: white;
      color: black;
      border-radius: 8px;
      overflow: hidden;
      width: 200px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      text-align: center;
      border: 1px solid #D4AF37;
    }

    .menu-card img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }

    .menu-card h3 {
      font-size: 18px;
      margin: 10px 0 5px;
      
      color: #8B0000;
    }

    .menu-card p {
      font-size: 14px;
      padding: 0 10px 10px;
    }
  </style>
</head>
<body>
    <div class="navi">
    <nav class="navbar navbar-expand-sm bg-dark">
            <ul class="navbar-nav">
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="home.html">HOME</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="menu.html">MENU</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="team.html">Golden Pagodas Team</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="contact.html">CONTACT US</a>
                </li>
            </ul>
        </nav>
    </div>
    
    <div class="menu-section">
      <h2 class="menu-title">Golden Pagodas Team</h2>
      <div class="menu-grid">
        <div class="menu-card">
          <img src="Chef Liang Wei.jpg" alt="Tanjiro">
          <h3>Chef Liang Wei</h3>
          <p>Head Chef Master of wok hei,known for his lightning-fast stir-fries that capture fire and flavor</p>
        </div>
        <div class="menu-card">
          <img src="Chef Han Bo.jpg" alt="Nezuko">
          <h3>Chef Han Bo</h3>
          <p>Specializes in hand-pulled noodles and dumpling artistry, blending tradition with precision</p>
        </div>
        <div class="menu-card">
          <img src="Chef Mei Lin.jpg" alt="Zenitsu">
          <h3>Chef Mei Lin</h3>
          <p>Expert in Cantonese dim sum, crafting delicate bites with elegance and finesse</p>
        </div>
        <div class="menu-card">
          <img src="Chef Su Jing.jpg" alt="Inosuke">
          <h3>Chef Su Jing</h3>
          <p>Queen of Sichuan spice, balancing bold heat with deeply layered umami</p>
        </div>
        <div class="menu-card">
          <img src="Chef Lian Hua.jpg" alt="Shinobu">
          <h3>Chef Lian Hua</h3>
          <p>Dessert innovator, famous for reinventing classic Chinese sweets with modern flair</p>
        </div>
        <div class="menu-card">
          <img src="Chef Xiu Yan.jpg" alt="Giyu">
          <h3>Chef Xiu Yan</h3>
          <p>Seafood specialist, known for her intuitive seasoning and coastal culinary heritage</p>
        </div>
      </div>
    </div>
</body>
<footer style="background-color:#333;height:150px;width:100%;color:white;text-align:center;font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;font-size:5px;margin-top:30px;">
    <h2 style="font-size:medium; margin-top:4px;">Email : Sinjuminfurestaurant@gmail.com</h2>
    <h2 style="font-size:medium;">Contact number : +86 10-1234-5678</h2><br>
    <h2 style="font-size:medium;">Address: 北京市东城区王府井大街1号 (1 Wangfujing Street, Dongcheng District, Beijing 100006, China)</h2>
    <br>
    <h2 style="font-size:medium;">----------中華之魂 (Zhōnghuá zhī hún - Spirit of China)----------</h2>
</footer>
</html>

contact.html


<html>
<head>
    <link href="design.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">        
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
    </script>
  
    <title>Contact Us - Siju Minfu Chinese Restaurant</title>
    <style>
    .navi {
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    
    body {
        background-image: url("cccc.jpg");
        background-size: cover;
    }
    
    .contact-section h1 {
        font-size: 32px;
        color: #070707;
        margin-bottom: 30px;
        text-align: center;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-weight: bold;
    }

    .contact-box {
        background-color: #bc6c60;
        color: white;
        padding: 20px;
        margin: 0 auto;
        width: 700px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(220, 187, 187, 0.3);
        margin-top: 50px;
        border: 2px solid #D4AF37;
    }

    .contact-box p {
        font-size: 16px;
        margin: 10px 0;
        margin-top: 20px;
    }
    </style>
</head>
<body>
    <div class="navi">
    <nav class="navbar navbar-expand-sm bg-dark">
            <ul class="navbar-nav">
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="home.html">HOME</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="menu.html">MENU</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="team.html">GOLDEN PAGODAS TEAM</a>
                </li>
                <li class="nav-item bg-dark mx-3">
                    <a class="nav-link text-white" href="contact.html">CONTACT US</a>
                </li>
            </ul>
        </nav>
    </div>
    
    <div class="contact-section">
        <br>
        <h1>CONTACT US</h1>
        <div class="contact-box">
            <p><strong>Restaurant:</strong> Siju Minfu Chinese Restaurant</p>
            <p><strong>Address:</strong> 北京市东城区王府井大街1号 (1 Wangfujing Street, Dongcheng District, Beijing 100006, China)</p>
            <p><strong>Phone:</strong> +86 10-1234-5678</p>
            <p><strong>Email:</strong> Sijuminfurestaurant@gmail.com</p>
            <p><strong>Reservations:</strong> Recommended for dinner service</p>
            <p><strong>Private Events:</strong> Available for traditional tea ceremonies and kaiseki dinners</p>
        </div>
    </div>
</body>
<footer style="background-color:#545252;height:150px;width:100%;color:white;text-align:center;font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;font-size:5px;margin-top:30px;">
    <br><h2 style="font-size:medium; margin-top:4px;">Email : Sijuminfurestaurant@gmail.com</h2>
    <h2 style="font-size:medium;">Contact number :+86 10-1234-5678</h2><br>
    <h2 style="font-size:medium;">Address: </h2>
    <br>
    <h2 style="font-size:medium;">----------中華之魂 (Zhōnghuá zhī hún - Spirit of China)----------</h2>
</footer>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2025-11-12 113233.png>)

![alt text](<Screenshot 2025-11-12 113255.png>)

![alt text](<Screenshot 2025-11-12 113314.png>)

![alt text](<Screenshot 2025-11-12 113339.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
