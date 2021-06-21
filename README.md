<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ongkon's Creation</title>
    <link rel="stylesheet" href="no2.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Dekko&family=Viaoda+Libre&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.3/css/fontawesome.min.css">
    <body>
    <div class="header">
    <div class="container">
    <div class="navber">
        <div class="logo">
            <img src="logos.png" width="80px">
       </div>
       <nav>
       <ul id="MenuItems">
           <li><a href="#">home</a></li>
           <li><a href=""#>Products</a></li>
           <li><a href="#">About</a></li>
           <li><a href="#">Contact</a></li>
           <li><a href="#">Account</a></li>
       </nav>
       <img src="cart.png" width="20px" height="20px">
         <img src="menu.jpg" class="menu-icon" oneclick="menutoggle()">
       </ul>
       
   </div>
    <div class="row">
    <div class="col-2">
    <h1>Welcome!</h1>
    <p>Hi,i'm Ongkon.<br>This is my first experimental website.Usually you can find lots of <br>photographs,drawings in this website.</p>
    <a href="" class="btn">Explore Now &#8594;</a>
    
    </div>
    <div class="col-2">
         <img src="logo.png">
    </div>
   </div>
   </div>
   </div>
   
<!-------- featured categories -------->
   
<div class="categories">
   <div class="small-container">
     <div class="row">
     <div class="col-3">
     <img src="category-1.jpg">
     </div>
       <div class="col-3">
     <img src="category-2.jpg">
   </div>
     <div class="col-3">
     <img src="category-3.jpg">
     </div>
     </div>
<!-------- featured products -------->
    <div class="small-container">
    <h2 class="tilte">Featured Products</h2>
    <div class="row">
      <div class"col-4">
      <img src="img.jpg" width="100x" height="100px">
      <h4>Plant</h4>
      <p>$1.00</p>
      <div class="rating">
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star-o"></i>
    <div class"col-4">
    <img src="img.jpg" width="150x" height="150px">
    <h4>Plant</h4>
    <p>$1.00</p>
    <div class="rating">
    <i class="fa fa-star"></i>
    <i class="fa fa-star"></i>
    <i class="fa fa-star"></i>
    <i class="fa fa-star"></i>
    <i class="fa fa-star-o"></i>
    </div>
    </div>
  </div>
  </div>
  </div>
  </div>
  </div>
  <!-------js for toggle menu------->
  <script>
    var MenuItems = document.getElementById("MenuItems");
       MenuItems.style.maxheight = "0px";
     function menutoggle(){
     if(MenuItems.style.maxheight == "0px")
         {
            MenuItems.style.maxheight = "200px";
         }
         else
         {
            MenuItems.style.maxheight = "0px";   
         }
      }
     </script>
  </body>
  </head>
  </html>
      
      
    
