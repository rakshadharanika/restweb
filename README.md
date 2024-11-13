# Ex.07 Restaurant Website
### NAME   : V RAKSHA DHARANIKA
### REF NO : 212223230167

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
### INDEX.HTML :
```PY
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Lemon</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Main Page Container with Background -->
  <div class="index-page">
    <header>
      <h1>Little Lemon</h1>
      <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </header>

    <!-- Banner Section -->
    <div class="banner">
      <h2>Welcome to Little Lemon!</h2>
      <p>Discover the freshest flavors and unique dishes crafted with passion.</p>
      <p>Enjoy 30% Off This Weekend on selected items!</p>
    </div>

    <!-- Main Content Area -->
    <div class="main-content">
      <div class="content-box">
        <h3>Our New Menu</h3>
        <p>Explore a range of delicious options made with fresh ingredients.</p>
        <a href="menu.html">See our new menu</a>
      </div>
      <div class="content-box">
        <h3>Book a Table</h3>
        <p>Reserve a spot for a memorable dining experience.</p>
        <a href="book.html">Book your table now</a>
      </div>
      <div class="content-box">
        <h3>Opening Hours</h3>
        <p>Mon-Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
      </div>
    </div>

    <footer>
      <p>&copy; 2024 Little Lemon | Developed by V Raksha Dharanika</p>
    </footer>
  </div>
</body>
</html>



```
### MENU.HTML :
```PY
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Lemon</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Main Page Container with Background -->
  <div class="index-page">
    <header>
      <h1>Little Lemon</h1>
      <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </header>

    <!-- Banner Section -->
    <div class="banner">
      <h2>Welcome to Little Lemon!</h2>
      <p>Discover the freshest flavors and unique dishes crafted with passion.</p>
      <p>Enjoy 30% Off This Weekend on selected items!</p>
    </div>

    <!-- Main Content Area -->
    <div class="main-content">
      <div class="content-box">
        <h3>Our New Menu</h3>
        <p>Explore a range of delicious options made with fresh ingredients.</p>
        <a href="menu.html">See our new menu</a>
      </div>
      <div class="content-box">
        <h3>Book a Table</h3>
        <p>Reserve a spot for a memorable dining experience.</p>
        <a href="book.html">Book your table now</a>
      </div>
      <div class="content-box">
        <h3>Opening Hours</h3>
        <p>Mon-Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
      </div>
    </div>

    <footer>
      <p>&copy; 2024 Little Lemon | Developed by V Raksha Dharanika</p>
    </footer>
  </div>
</body>
</html>


```
### ADMINISTRATION.HTML :

```PY
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Lemon</title>
  <link rel="stylesheet" href="style.css">
  <style>
  
    body {
      background-color: lightgrey;
      color: black;
      font-family: Arial, sans-serif;
      margin: 0;
    }

    .index-page {
      background-color: white;
      padding: 20px;
    }

    header {
      background-color: darkgreen;
      padding: 20px;
      text-align: center;
      color: white;
    }

    header h1 {
      margin: 0;
    }

    nav a {
      color: lightyellow;
      text-decoration: none;
      margin: 0 10px;
    }

    nav a:hover {
      color: yellow;
    }

   
    .banner {
      background-color: tomato;
      color: white;
      padding: 30px;
      text-align: center;
    }

   
    .main-content {
      display: flex;
      justify-content: space-around;
      margin-top: 20px;
    }

    .content-box {
      background-color: lightblue;
      padding: 20px;
      border: 2px solid darkblue;
      border-radius: 8px;
      text-align: center;
      width: 25%;
    }

    .content-box h3 {
      color: darkblue;
    }

    .content-box a {
      color: blue;
      text-decoration: underline;
    }

    footer {
      background-color: darkslategrey;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
 
  <div class="index-page">
    <header>
      <h1>Little Lemon</h1>
      <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
      </nav>
    </header>
 
    <div class="banner">
      <h2>Welcome to Little Lemon!</h2>
      <p>Discover the freshest flavors and unique dishes crafted with passion.</p>
      <p>Enjoy 30% Off This Weekend on selected items!</p>
    </div>

   
    <div class="main-content">
      <div class="content-box">
        <h3>Our New Menu</h3>
        <p>Explore a range of delicious options made with fresh ingredients.</p>
        <a href="menu.html">See our new menu</a>
      </div>
      <div class="content-box">
        <h3>Book a Table</h3>
        <p>Reserve a spot for a memorable dining experience.</p>
        <a href="book.html">Book your table now</a>
      </div>
      <div class="content-box">
        <h3>Opening Hours</h3>
        <p>Mon-Fri: 2pm - 10pm<br>Sat: 2pm - 11pm<br>Sun: 2pm - 9pm</p>
      </div>
    </div>

    <footer>
      <p>&copy; 2024 Little Lemon | Developed by V Raksha Dharanika</p>
    </footer>
  </div>
</body>
</html>

```
### CONTACT.HTML :
```PY


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Little Lemon - Contact Us</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Little Lemon</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <h2><center> Contact Us  </center></h2>
  <p><center>   Address: 123 Main Street, velachery, India</center></p>
  <p><center>  Phone: 8939003166   </center></p>
  <p><center>    Email: rakshadharanika@gmai.com </center></p>

  <footer>
    <p>&copy; 2024 Little Lemon | Developed by V Raksha Dharanika</p>
  </footer>
</body>
</html>


```
### STYLE.CSS:
```PY


.index-page {
    background-image: url('images/WhatsApp\ Image\ 2024-11-13\ at\ 20.45.09_f80c0a9c.jpg'); 
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    padding: 60px 20px;
    color: white;
    min-height: 100vh; 
}


header {
    text-align: center;
    padding: 20px;
    background-color: rgba(0, 0, 0, 0.6); 
    border-radius: 8px;
}

header h1 {
    font-size: 2em;
    color: lightgoldenrodyellow;
}

header nav a {
    margin: 0 15px;
    color: white;
    text-decoration: none;
    font-weight: bold;
}

header nav a:hover {
    color: lightcoral;
}


.banner {
    text-align: center;
    padding: 20px;
    margin-top: 20px;
    background-color: rgba(0, 0, 0, 0.6); 
    border-radius: 8px;
}

.banner h2 {
    font-size: 2.5em;
    color: gold;
}

.banner p {
    font-size: 1.2em;
    color: white;
}


.main-content {
    display: flex;
    justify-content: space-around;
    margin-top: 30px;
}

.content-box {
    background-color: rgba(255, 255, 255, 0.8); 
    color: dimgray;
    width: 30%;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    text-align: center;
}

.content-box h3 {
    font-size: 1.5em;
    color: darkgreen;
}

.content-box p {
    font-size: 1em;
    color: gray;
}

.content-box a {
    text-decoration: none;
    font-weight: bold;
    color: orangered;
}

.content-box a:hover {
    color: darkred;
}


footer {
    text-align: center;
    margin-top: 50px;
    padding: 10px;
    background-color: rgba(0, 0, 0, 0.6); 
    border-radius: 8px;
    color: white;
}
.menu-page {
    background-image: url('your-menu-bg.jpg'); 
    background-size: cover;
    background-position: center;
    padding: 60px 20px;
    color: white;
}


.menu-items {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
}


.menu-item {
    background-color: rgba(255, 255, 255, 0.9);
    padding: 15px;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    color: dimgray;
}

.menu-item img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
}

.menu-item h3 {
    margin: 10px 0;
    font-size: 1.3em;
    color: tomato;
}

.menu-item p {
    font-size: 0.9em;
    color: gray;
}

.menu-item p:last-of-type {
    font-weight: bold;
    color: black;
}





```


## OUTPUT:
### INDEX.HTML :
![image](https://github.com/user-attachments/assets/c2e44d63-10be-4af1-97d2-483e0dd8c753)


### MENU.HTML :
![image](https://github.com/user-attachments/assets/9965f8b3-c20c-42f5-9eb4-885607fc868f)

### ADMINISTRATION.HTML :
![image](https://github.com/user-attachments/assets/a83ef917-79ca-431c-9a95-cf9bd6d4caac)

### CONTACT.HTML :
![image](https://github.com/user-attachments/assets/6845c508-e475-4fb5-b2ce-822650aa96ad)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
