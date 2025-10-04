# Ex.07 Restaurant Website
## Date:4/10/2025

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
```
rest.html

<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="container">
           
                
                 <div class="name">
                    Celeste Dining
                </div>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            <div class="pic">
                <div class="txt">
                Taste the divine...
                </div>
            </div>
            <div class="footer">
                <footer>&copy; Harish P(25015017)</footer>
            </div>
        </div>
    </body>
</html>

style1.css

body{
     background-color: peachpuff;
     height: 100%;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
     background-color: peachpuff;
    width: 100%;    

}
.name{
    font-size: 30px;
    font-weight: bold;
   
    position: absolute;
    left: 5%;
    margin-top: 15px;
    
      
}
.menu{
    position: absolute;
    left: 75%;
    margin-top: 20px;
    font-size: 18px;
    
    display: flex;
    gap: 20px;
    
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:blue;
}

.footer{
    margin-top: 700px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}
.pic
{
    width: 1500px;
    height:650px;
    background: url(rest.png) no-repeat;
    background-size: cover;
    margin-top: 50px;
    position: absolute;
}
.txt{
     color: white;
    font-size: 32px;
     position: absolute;
    left: 40%;
    margin-top: 15px;
    -webkit-text-stroke: 1px black;
}

menu.html

<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style2.css">
    </head>
    <body>
       
       <h1>Our Menu</h1><br>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            
             <div class="container">
            <div class="item">
                <img src="biriyani.png" alt="Biriyani">         
                <h3>Biriyani</h3>         
                <p class="price">Rs.300</p>         
                
            </div>
             <div class="item">
                <img src="friedrice.png" alt="Friedrice">         
                <h3>Friedrice</h3>         
                <p class="price">Rs.250</p>         
                
            </div>
             <div class="item">
                <img src="noodles.png" alt="Noodles">         
                <h3>Noodles</h3>         
                <p class="price">Rs.250</p>         
                
            </div>
            <div class="item">
                <img src="parotta.png" alt="Parotta">         
                <h3>Parotta</h3>         
                <p class="price">Rs.150</p>         
                
            </div>
            <div class="item">
                <img src="momo.png" alt="Momo">         
                <h3>Momo</h3>         
                <p class="price">Rs.120</p>         
                
            </div>
            <div class="item">
                <img src="pasta.png" alt="Pasta">         
                <h3>Pasta</h3>         
                <p class="price">Rs.250</p>         
                
            </div>
            <div class="item">
                <img src="pizza.png" alt="Pizza">         
                <h3>Pizza</h3>         
                <p class="price">Rs.270</p>         
                
            </div>
            <div class="item">
                <img src="tandoori.png" alt="Tandoori">         
                <h3>Tandoori</h3>         
                <p class="price">Rs.270</p>         
                
            </div>
            </div>
            </div>
           
            <div class="footer">
                <footer>&copy; Harish P(25015017)</footer>
            </div>
    </body>
</html>

style2.css

body{
     background-color: peachpuff;
     height: 100%;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
     background-color: peachpuff;
    width: 100%;  
    gap: 20px; 
    
    align-items: center; 

}

h1{
    text-align: center;
    margin-top: 7px;
}
.menu{
   position: absolute;
    left: 42%;
   
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:blue;
}
.footer{
    margin-top: 25px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}

.item{
   margin-top: 60px;
    width: 220px;     
    background-color: cyan;     
    border: 1px solid red;    
     padding: 10px;     
    
       box-sizing: border-box;     
       border-radius: 8px;     
       box-shadow: 0 2px 5px rgba(0,0,0,0.1);     
       text-align: center;   
}
h3{
    font-size: 20px;
}
.price{
    font-size: 19px;
}
img{
    height: 200px;
    width:175px;
    border-radius: 8px;

}

admin.html

<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style3.css">
    </head>
    <body>
       
       <h1>Administration</h1><br>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            
             <div class="container">
            <div class="admin">
                <img src="mypic.jpg.jpg" alt="CEO">         
                <h3>CEO</h3>         
                  
                
            </div>
             <div class="admin">
                <img src="rajini.png" alt="Manager">         
                <h3>Manager</h3>         
                      
                
            </div>
             <div class="admin">
                <img src="kamal.png" alt="Senior chef">         
                <h3>Senior chef</h3>         
                         
                
            </div>
            <div class="admin">
                <img src="surya.png" alt="SousChef-1">         
                <h3>Sous Chef-1</h3>         
                       
                
            </div>
            <div class="admin">
                <img src="jenna.png" alt="SousChef-2">         
                <h3>Sous Chef-2</h3>         
                        
                
            </div>
             <div class="footer">
                <footer>&copy; Harish P(25015017)</footer>
            </div>
        </div>
        </body>
        </html>

style3.css

body{
     background-color: peachpuff;
     height: 100%;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
     background-color: peachpuff;
    width: 100%;  
    gap: 20px; 
    
    align-items: center; 

}

h1{
    text-align: center;
    margin-top: 7px;
}
.menu{
   position: absolute;
    left: 39%;
   
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:blue;
}
.footer{
    margin-top: 900px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}

.admin{
   margin-top: 60px;
    width: 220px;     
    background-color: cyan;     
    border: 1px solid red;    
     padding: 10px;     
    
       box-sizing: border-box;     
       border-radius: 8px;     
       box-shadow: 0 2px 5px rgba(0,0,0,0.1);     
       text-align: center;   
}
h3{
    font-size: 20px;
}

img{
    height: 200px;
    width:175px;
    border-radius: 8px;
}

contactus.html

<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style4.css">
    </head>
    <body>
       
       <h1>Contact Us</h1><br>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            <div class="container">
                <div class="address">
                    <h2>Contact Us</h2><br>
                    Visit us at:<br>
                    123 Angel Street,Heaven land,India.<br>
                    Phone:123-4567-8901<br>
                    Email:celestedining@gmail.com
                </div>
                 <div class="footer">
                <footer>&copy; Harish P(25015017)</footer>
            </div>
            </div>
            </body>
            </html>

style4.css

body{
     background-color: peachpuff;
     height: 100%;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
     background-color: peachpuff;
    width: 100%;  
    gap: 20px; 
    
    align-items: center; 

}

h1{
    text-align: center;
    margin-top: 7px;
}
.menu{
   position: absolute;
    left: 39%;
   
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:blue;
}
.footer{
    margin-top: 1200px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}
.address{
    text-align: center;
    position: absolute;
    left: 40%;
    margin-top: 500px;
    font-size: 20px;
    width: 300px;     
    background-color: crimson;     
       border: 2px solid blue;
     padding: 15px;     
    
       box-sizing: border-box;     
       border-radius: 8px;     
}

```

## OUTPUT:
![alt text](<Screenshot (50).png>)
![alt text](<Screenshot (51).png>)
![alt text](<Screenshot (52).png>)
![alt text](<Screenshot (53).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
