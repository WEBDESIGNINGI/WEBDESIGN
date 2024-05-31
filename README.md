<!DOCTYPE html>
<html lang="en">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<head>
    <meta charset="UTF-8">
    <title>Biryani Bonanza</title>
    <link rel="stylesheet" href="styles.css">
</head>
<style>
    button {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}

@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}
    a {
    color: rgb(255 255 255);
    text-decoration: none;
    animation: head 1s ease-out 1;
}
  /* styles.css */
.containers {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between; /* Adjust as needed */
}

.cards {
    flex: 1 0 calc(33.33% - 20px); /* Adjust column width */
    margin: 10px;
    padding: 20px;
    border: 1px solid #ddd;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

 

.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between; /* Adjust as needed */
}

.card {
    flex: 1 0 calc(33.33% - 20px); /* Adjust column width */
    margin: 10px;
    padding: 20px;
    border: 1px solid #ddd;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

  
   

   
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem;
}

nav ul li a:hover {
    background-color: #555;
}

section {
    padding: 2rem;
    margin-top: 1rem;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
}

address {
    font-style: normal;
}
#home {
    background-image: url('home-bg.jpg');
    background-size: cover;
    background-position: center;
    padding: 20px 0;
    text-align: center;
    color: #fff;
}

.home-content {
    max-width: 800px;
    margin: 0 auto;
    background: rgba(0, 0, 0, 0.7);
    padding: 20px;
    border-radius: 10px;
}

.home-content h1 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.home-content p {
    font-size: 1.1rem;
    line-height: 1.6;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    margin-top: 100px;
    background-color: #f8c045;
    color: #333;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #cb202d;
    box-shadow: inset 0 0 0 0;
transition: ease-in-out 0.3s;
}
#home {
    background-image: url(DDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD.avif);
    background-size: cover;
    background-position: center;
    padding: 50px 0;
    text-align: center;
    color: #fff;
}

.home-content {
    max-width: 800px;
    margin: 0 auto;
    background: rgba(0, 0, 0, 0.7);
    padding: 20px;
    border-radius: 10px;
}

.home-content h1 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.home-content p {
    font-size: 1.1rem;
    line-height: 1.6;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    margin-top: 20px;
    background-color: #f8c045;
    color: #333;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #cb202d;
}
.menu 
{
    background-color: #f4f4f4;
    transition: #f4f4f4 0.3s ease-in;

} 
.flex-container
            {
                display: flex;
            }
            .flex-container>div
            {
                margin: 2px;
            }
            @keyframes example 
            {
  from {background-color: red;}
  to {background-color: yellow;}
}


</style>
<body style="background-color: #555;.flex-container">
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact Us</a></li>
                <li><a href="#vision">Our Vision</a></li>
                <a href="login1.html">Login</a>
            </ul>
        </nav>
    </header>
    <main>
            <section id="home">
                <div class="home-content">
                    
            
                    <h1><marquee>Welcome to Biryani Bonanza!</marquee></h1>
                    <p>Embark on a culinary journey with Biryani Bonanza, where tradition meets taste in every aromatic dish. Our menu is a mosaic of flavors, featuring an exquisite selection of biryanis, each telling the tale of its origin. From the royal Hyderabadi to the luxurious Gulab Jamuns, we bring you the authentic essence of India. Dive into our healthy desserts, and savor the richness of our chettinads and curries. At Biryani Bonanza, we believe in celebrating the diversity of Indian cuisine, prepared with love and served with pride. Join us at our table, where every meal is a feast for the senses.</p>
                    <a href="#menu" class="btn">Explore Our Menu</a>

                </div>
            </section>
            <section id="menu">
                <div class="container">
               
 
                   
                
                      
              
                     
                <div class="col-md-4 col-sm-6 col-xs-12 mt-3">
                    <div class="card" style="align-items: flex-start;">
                        <img src="./hyderabadi-biryani-recipe-chicken-500x375.jpg" alt="Hyderabadi Chicken Biryani" class="card-img-top img-fluid" width="500px" height="800px">
                        <div class="card-body">
                            <h2 class="card-title">Hyderabadi Chicken Biryani</h2>
                            <h1>₹350</h1>
                            <p>Indulge in the rich flavors of Hyderabadi Chicken Biryani at Biryani Bonanza. Our aromatic basmati rice, tender chicken, and secret blend of spices create a fine, exquisite masterpiece that's fit for royalty!</p>
                            <a href="#" class="btn btn-danger">Add +</a>
                        </div>
                    </div>
                </div>
                          
                <div class="col-md-4 col-sm-6 col-xs-12 mt-3">
                    <div class="card" style="align-items: flex-start;">
                        <img src="Chicken-Chettinad.jpg" alt="Chicken Chettinad" class="card-img-top img-fluid" width="500px" height="800px">
                        <div class="card-body">
                            <h2 class="card-title">Chicken Chettinad</h2>
                            <h1>₹120</h1>
                            <p>Experience the bold flavors of Chicken Chettinad! Our tender chicken, marinated in aromatic spices, dances on your taste buds. 🔥🍗 Discover the authentic taste of South India at our restaurant!</p>
                            <a href="#" class="btn btn-danger">Add +</a>
                        </div>
                    </div>
                </div>
                
                    
                
                 
                <div class="col-md-4 col-sm-6 col-xs-12 mt-3">
                    <div class="card" style="align-items: flex-start;">
                     <img src="./360_F_517968988_hFHjQT6Flfksjx8n0KxfvMtP2tqlmGKk.jpg" alt="" class="card-img-top img-fluid" width="500px" height="1000px">
                              <div class="card-body">
                             <h2 class="card-title">Hyderabadi Mutton Biryani</h2>
                             <h1>₹395</h1>
                              <p>Indulge in the aromatic flavors of Hyderabadi Mutton Biryani at Biryani Bonanza. Our amazing texmati rice, out-of-the-world mutton, and good blend of spices create a nice feeling which'll be really good for die-hard biryani fans!</p>  
                              <a href="#" class="btn btn-danger">Add +</a>  </div>
                            </div>
                          </div>
                        </div>
                          </div>
                        </div>
                    </div>
             
                    <div class="container">
                        <div class="rows">
                        <div class="col-md-3">
                            <div class="card" style="align-items: flex-start;">
                                  <img src="download (16).jpeg" alt="" class="card-img-top" width="100px" height="300px">
                            <h2 class="card-title">Gulab-Jamun</h2>
                                <h1>₹150</h1>
                                 <p>Indulge in the Sweet Magic of Gulab Jamun! Our deep-fried milk balls, soaked in saffron-infused syrup, melt in your mouth 🌹🍬</p>  
                                 <a href="" class="btn btn-danger" style=".btn:hover:hover">Add +</a>  </div></div></div>
                                  <section id="menu">
                       
              
                                    <div class="container">
                                        <div class="row">
                                        <div class="col-md-3">
                     
                        <div class="card">
                          <div class="cards"></div>
                        
                          <img src="Dhaba-Style-Chicken-Curry-2-500x500.jpg" alt="" class="card-img-top img-fluid" width="500px" height="800px">
                          <div class="card-body">
                         <h2 class="card-title">Chicken-Curry</h2>
                         <h1>₹25</h1>
                          <p>Experience the Bold Flavors of Chicken Curry! This is biriyani's best friend and the taste of south india'll be in your taste buds!</p>  
                          <a href="" class="btn btn-danger"style=".btn:hover:hover">Add +</a>  
                        </div>
                    </div>
                      </div>
                     
                  
        </section>
        <section id="contact">
           

        </section>
        <section id="vision">
            <div class="home">
                <style>
                     @keyframes example 
            {
  from {background-color: red;}
  to {background-color: yellow;}
}
button {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}
                </style>
 <div class="button">Vision: To nourish not only appetites but also hearts. At our restaurant, we believe in more than just serving delicious food. For every biryani ordered, we pledge to donate a meal to underprivileged children. Because when you dine with us, you’re not just savoring flavors—you’re sharing love and hope. And for me, it’s not just about helping; it’s about creating a world where kindness is the main course. 🌟🍲
        </div>
        </section>
        <section id="login">
         <div class=".home-content" style="text-decoration: none;"></div>
         <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <style>a</style>
        </section>  
    </main>
    <footer>
        <address>
            A 20, Ground Floor, Rajouri Garden, Andheri, Mumbai-83540552
        </address>
        <p>Follow Us On [Social Media Links]</p>
        <p>© 2024 Sky Gate Hospitality PVT. LTD. All Rights Reserved. | <a href="wildflower-terms-and-conditions.png">Terms & Conditions</a></p>
    </footer>
</body>
</html>

