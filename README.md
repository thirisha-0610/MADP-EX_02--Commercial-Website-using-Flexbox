# Ex02 Commercial Website
## Date: 28/4/25
# Name: THIRISHA A

# Reg no: 212223040228

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
# index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Recipe App - Home</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
  <header class="header">
    <img src="logos.png" alt="Profile Image" class="header-image">
    <h1 class="logo">I<span>nfiniti</span>C<span>ook</span></h1>
    <div class="navbar">
      <a href="index.html">Home</a>
      <a href="Login.html">Login</a>
      <a href="myrecipes.html">My Orders</a>
      <a href="profile.html">Profile</a>
    </div>
  </header>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <div class="input-group my-4">
          <input type="text" class="form-control" placeholder="Search recipes...">
          <div class="input-group-append">
            <button class="btn btn-outline-secondary" style="background-color: black;color: aliceblue;" type="button">Search</button>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="sambar.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Sambar</h5>
            <p class="card-text">Sambar is a South Indian lentil and mixed vegetable stew that’s comfort food at its best. It’s hearty, super flavorful, and loaded with vegetables, spices, and herbs.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="mushroom.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Mushroom</h5>
            <p class="card-text">Mushroom 65 is a popular South Indian vegetarian appetizer made with crispy fried mushrooms coated in a spicy and flavorful batter. Mushroom – 200 gms. Slice the button mushrooms in half and set them aside. Combine rice flour, corn flour, besan flour, and all-purpose flour in a mixing bowl.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="mangolassi.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Mango Lassi</h5>
            <p class="card-text">Mango is a delightful fruit! 🥭 Whether you’re enjoying it fresh, blending it into smoothies, or using it in cooking, mangoes bring a burst of tropical flavor.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="burger.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Burger</h5>
            <p class="card-text">Burgers are a classic comfort food, and making them at home is both fun and rewarding.It was the most favourite snack for the  World and Most flavorful.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="vegroll.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Veg Roll</h5>
            <p class="card-text">The taste of a vegetable roll is typically fresh and crisp, with flavors varying based on the fillings and the dipping sauce used. The combination of herbs, vegetables, and sometimes a hint of sweetness or spiciness from the sauce creates a vibrant and satisfying flavor profile.Vegetable roll is a type of dish that consists of fresh vegetables, often wrapped in rice paper or a thin crepe, and is typically served with a dipping sauce.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="bisbillabath.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Bisibelebath</h5>
            <p class="card-text">It is a traditional rice and lentil-based recipe known for its vibrant flavor, taste, and spice blend masala. In other words, Bisi Bele Bath is a spicy khichdi recipe with an additional purposed-based spice mix and a range of vegetables. It is particularly prepared for the morning breakfast but not limited to it and can be an ideal lunch box or tiffin box one-pot meal recipe. It is generally served as it is without any sides or condiments.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="pulao.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Pulao</h5>
            <p class="card-text">Pulao is a delightful one-pot Indian dish made with fragrant basmati rice, vegetables, and aromatic spices. It’s a versatile recipe that you can customize with your favorite veggies.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="coffee.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Coffee</h5>
            <p class="card-text">Coffee is a delightful beverage brewed from roasted coffee beans. It’s darkly colored, slightly acidic, and has a distinctive, somewhat bitter flavor. The stimulating effect of coffee primarily comes from its caffeine.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="chiken65.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Chicken 65</h5>
            <p class="card-text">Chicken 65 is a South Indian deep-fried chicken appetizer that originated in Hotel Buhari in Chennai. It’s a crowd-pleaser and has found a top place on restaurant menus.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="naan.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Naan</h5>
            <p class="card-text">Naan is a delightful Indian flatbread that pairs perfectly with curries or can be enjoyed on its own.It's a Punjabi food with variety of flavors In different styles.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="idli.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Idli</h5>
            <p class="card-text">Idli is a soft, pillowy steamed savory cake made from fermented rice and lentil batter. The lentils used in making the idli batter are urad dal (hulled black gram).Black gram is also known as matpe beans, urad beans. To make idli the off white colored husked/hulled black gram is used – it can be split or whole.The lentils and rice are soaked first and then later ground separately.</p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card recipe-card">
          <img src="C:\Users\thiri\Desktop\website\website\chapathi.jng.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Chapathi</h5>
            <p class="card-text">Chapati Recipe with tips & tricks to make them perfect & super soft every time! There is nothing better than a freshly made flatbread. With the freshest flavor and perfect texture, these homemade Chapati are the absolute best! Once you master the technique of making soft Chapati, you will never buy them from the stores. Serve them with dal, curries, stew or use them to make wraps, rolls, quesadillas, kothu roti or chapati noodles.
 
            </p>
            <a href="sambar.html" class="btn btn-primary">$40</a>
            <button class="btn btn-secondary">Place Order</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer class="footer">
    <div class="brand-name">Thirisha  © 2025 SSS restaurant . All rights reserved </div>
    <ul class="social-icons">
        <li><a href="https://wa.me/9025383772" target="_blank"><i class="fab fa-whatsapp"></i></a></li>
        <li><a href="https://instagram.com/thirisha.2005" target="_blank"><i class="fab fa-instagram"></i></a></li>
        <li><a href="mailto:thirisha0610@gmail.com"><i class="fas fa-envelope"></i></a></li>
        <li><a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i></a></li>
    </ul>
</footer>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@1.16.0/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
# STYLE.CSS:

```
.recipe-card 
{
  margin-bottom: 40px;
  padding: 15px;
}
.navbar 
{  
  width: 100%;
  padding: 35px 0;
  background-color: black;
}
.navbar a 
{
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}
.navbar a:hover 
{
  background-color: #ffffff;
  color: rgb(0, 0, 0);
}
.footer 
{
  background-color: #333;
  color: white;
  padding: 20px 0;
  text-align: center;
}
.footer .brand-name 
{
  font-size: 18px;
  margin-bottom: 10px;
}
.footer .social-icons 
{
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: center;
}
.footer .social-icons li 
{
  margin: 0 10px;
}
.footer .social-icons a 
{
  color: white;
  text-decoration: none;
  font-size: 20px;
}
.footer .social-icons a:hover 
{
  color: #ddd;
}
.logo 
  {
    color: #152bd2;
    font-size: 40px;
    font-weight: 700;
    letter-spacing: 3px; 
    font-family: 'Courier New', Courier, monospace;       
  }
  span 
  {
    color: rgb(252, 250, 250);
  }
  html
  {
    font-size: 72.5%;
    word-wrap: break-word;
    scroll-behavior: smooth;
  } 
  .header 
  {
    display: flex;
    align-items: center;
    background-color: #000000;
    padding: 10px;
    border-bottom: 1px solid #ddd;
  }
  .header-image
  {
    width:50px;
    height:50px;
    border-radius: 30%;
    margin-right: 20px;
    background-color: black;
  }
  @media (max-width: 768px) 
  {
    body
     {
      padding-top: 56px;
    }
  }
```

## OUTPUT

![Screenshot (79)](https://github.com/user-attachments/assets/f15101a0-e4db-4ade-9677-a191e25dfa4d)

![Screenshot (81)](https://github.com/user-attachments/assets/bf15f783-b253-441c-9fc7-7f4e0184f6bf)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
