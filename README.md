
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
      
                    *{
     margin: 0;
     padding: 0;
     box-sizing: border-box;
}
body{
  font-family: 'Benne', serif;
}
.navber{
      display: flex;
      align-items: center;
      padding: 20px;
}
.nav{
    flex: 1;
    text-align: right;
 }
 nav ul{
      display: inline-block;
      list-style-type: none;
}
nav ul li{ 
       display: inline-block;
       margin-right: 20px;
} 
a{
    text-decoration: none;
    color:#555;
}
p{
    color:#555;
 }
.container{
     max-width: 1300px;
     margin: auto;
     padding-left: 25px;
     padding-right: 25px;
}
.row{
     display: flex;
     align-item: center;
     flex-wrap: wrap;
     justify-content: space-around;
}
.col-2{
    flex-basis: 50%;
    min-width: 300px;
}
.col-2 img{
        max-width: 100%;
        padding: 50px 0;
}
.col-2 h1{
       font-size: 50px;
       line-height: 60px;
       margin: 25px 0;
}                
.btn{
    display: inline-block;
    background: #ff523b;                   
    color: #fff;
    padding: 8px 30px;
    margin: 30px 0;
    border-radius: 30px;
    transition: background 0.5s;
}

.btn:hover{
      background: #563434;
}
.header{
     background: radial-gradient(#fff,#ffd6d6);
} 
.header. row{
        margin-top: 70px;
}
.categories{
     margin: 70px 0;   
}
.col-3{
    flex-basis: 30%;
    min-width: 250px;
    margin-bottom: 30px;
}
.col-3 img{
    width: 100%;    
}
.small-container{
        max-width: 1080px;
        margin: auto;
        padding-left: 25px;
        padding-right: 25px;  
}
.col-4{
     flex-basis: 25%;
     padding: 10px;
     min-width: 200px;
     margin-bottom: 50px;
}    transition: transform 0.5s;

.col-4 img{
      width: 100%;
}    
.title{
    text-align: center;
    margin: 0 auto 80ox;
    positon: relative;
    line-height: 60px;
    color: #555;
 }  
.title:after{
    content: '#';
    background: #ff523b;
    width: 80px;
    height: 5px;
    border-radius: 5px;
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
 }
 h4{
   color: #555;
   font-weight: normal;
  }   
 .col-4 p{
       fint-size: 140px;  
       }
 .col-4:hover{
         transform: translateY(-5px);
  }
.menu-icon{
     width: 28px;
     margin-left: 20px;
     display: none;
 }
/*-------- media query for menu ---------*/
 @media only screen and (max-width: 800px){
    nav ul{
        position: absolute;
        top: 70px;
        left: 0;
        background: #333;
        width: 100%;
        overflow: hidden;
        transition: max-height 0.5s;
  }   
   nav ul li{
       display: block;
       margin-top: 10px;
       margin-bottom: 10px;
     }
     nav ul li a{
        color: #fff;
    }
   .menu-icon{
         display: block;
         cursor: pointer;
   }  
   }  
  /*----media query for less than 600 screen size-----*/
     @media only screen and (max-width: 600px){
    .row{
       text-align: center;
    }
   .col-2, .col-3, .col-4{
        flex-basis: 100%;
        
   }
   }              
                                       
                                             
                                             
      
    
