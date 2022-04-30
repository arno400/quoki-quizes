# quoki-quizes
A quizes and olympiad website for the students

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>quoki Tech</title>
  <!-- Boostrape CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

  <!-- Default CSS File  -->
  <link rel="stylesheet" href="css/style.css">

  <!-- Font Awesome CDN  -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

<style>
/* Google Fonts: Poppins*/
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700&display=swap');


*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
    text-transform: capitalize;
    transition: 0.2s ease-in;
}
:root{
  --primary-color: #f9ab00;
  --box-shadow: .5rem .5rem  0 #10221b;
  --border: .2rem  solid #10221b;
    --text-color-1:#444;
    --text-color-2:#666;
    --bg-color-1:#fff;
    --bg-color-2:#eee;
}
.btn {
  margin-top: 1rem;
  display: inline-block;
  border: 0.2rem solid #10221b;
  color: #10221b;
  cursor: pointer;
  background: none;
  font-size: 1.7rem;
  padding: 1rem 3rem;
}

.btn:hover {
  background: #10221b;
  color: #fff;
}

.footer{
  padding: 2rem 9%;
}
.services{
  padding: 2rem 9%;
}
.rooms{
  padding: 2rem 9%;
}
.packages{
  padding: 2rem 9%;
}
.pricing{
  padding: 2rem 9%;
}
.heading {
  text-align: center;
  margin-bottom: 5rem;
  margin-top: 5rem;
  padding-top: 0rem;
  font-size: 4rem;
  color: #10221b;
}
html{
  font-size: 62.5%;
  overflow-x: hidden;
  scroll-padding-top: 7rem;
  scroll-behavior: smooth;
  
}
::selection{
    background-color:#1a191f;
    color: #fff;
}
::-webkit-scrollbar{
    width: 12px;
}

::-webkit-scrollbar-thumb{
    background-color: #1a191f;
}



html{
    scroll-behavior: smooth;
}


a{
    text-decoration: none;
    color: #000;
}

/* Navbar Section Starts  */

header{
  padding: 1rem 5%;
  background-color: #1a191f;
}
 

header .navbar-brand span{
  color: var(--primary-color);
}
header .navbar-brand{
  font-size: 2.5rem;
  color: #fff;
}

header .navbar-nav li a{
  color: #fff !important;
  text-align: center;
  font-size: 2rem;
}

.fa-bars{
  color: #fff ;
  font-size: 2rem !important;
}

.navbar-toggler{
  outline: none !important;
}










/* Navbar Section Ends  */

/* home section starts  */

.home{
  height: 95vh;
}
.home #list1{
  /* background: rgba(209, 137, 137, 0.7) url(https://preview.colorlib.com/theme/montana/img/banner/xbanner.png.pagespeed.ic.Fz8_Hc8pX8.jpg); */
  background: rgba(74, 123, 126, 0.7) url(https://i.postimg.cc/GmfKDmXb/h1-hero.jpg);
  background-size: cover;
  background-blend-mode: multiply;
  background-position: center center;
}


.home .item{
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 5rem;
  flex-wrap: wrap;
  height: 95vh;
  padding: 0rem 9%; 
}

.home .item .content h1{
  font-size: 6rem;
  padding-top: 2rem;
  text-align: center;
  color: #fff;
}

.home .item .content h1 span{
  color: var(--primary-color);
}
.home .item .content p{
  font-size: 2rem;
  padding: 1rem 0;
  padding-bottom: 2rem;
  max-width: 70rem;
  color: #fff;
  text-align: center;
  margin: auto;

}

.home .item .buttons{
  height: 5rem;
  text-align: center;
}
.home .item .content .home-btn1{
  padding: 0.8rem 2.5rem;
  background-color: hsl(0, 94%, 66%);
  color: #fff;
  font-size: 2rem;
  border-radius: 2rem;
  transition: 0.2s linear;
  text-decoration: none;
}
.home .item .content .home-btn1:hover{
  border: 2px solid #fff;
  background-color: transparent;
  color: #fff;
}
.home .item .content .home-btn2{
  padding: 0.8rem 3rem;
  border: 2px solid #fff;
  background-color: transparent;
  color: #fff;
  font-size: 2rem;
  border-radius: 2rem;
  margin-left: 1rem;
  text-decoration: none;
}



/* Member Ship Section Starts  */
.pricing{
  margin-bottom: 2rem;
}
.pricing .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  gap:1.5rem;
}

.pricing .box-container .box{
  background:var(--bg-color-1);
  border-radius: .5rem;
  padding:2rem;
  text-align: center;
  border: var(--border);
  box-shadow: var(--box-shadow);
}

.pricing .box-container .box h3{
  padding:1rem;
  background: var(--bg-color-2);
  border-radius: .5rem;
  font-size: 2rem;
  color:var(--text-color-1);
}

.pricing .box-container .box .price{
  padding-top: 2rem;
}

.pricing .box-container .box .price span{
  font-size: 2rem;
  color:var(--text-color-2);
}

.pricing .box-container .box .price .amount{
  font-size: 5rem;
  color:var(--text-color-1);
  font-weight: bolder;
}

.pricing .box-container .box ul{
  padding: .5rem 0;
  list-style: none;
}

.pricing .box-container .box ul li{
  padding: 1rem 0;
  font-size: 1.7rem;
  color:var(--text-color-2);
}

/* Member Ship Section Ends */

/* Footer Section Starts  */
.footer {
  background: #f3f3f3;
}

.footer .box-container {
  display: -ms-grid;
  display: grid;
  -ms-grid-columns: (minmax(25rem, 1fr))[auto-fit];
      grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
  gap: 1.5rem;
}

.footer .box-container .box h3 {
  font-size: 2.2rem;
  color: #222;
  padding: 1rem 0;
}

.footer .box-container .box p {
  font-size: 1.5rem;
  color: #666;
  padding-bottom: .5rem;
}

.footer .box-container .box a {
  font-size: 1.4rem;
  color: #666;
  padding: 1rem 0;
  display: block;
}

.footer .box-container .box a:hover {
  color: var(--primary-color);
}

.footer .box-container .box a:hover i {
  padding-right: 2rem;
}

.footer .box-container .box a i {
  padding-right: .5rem;
  color: var(--primary-color);
}

.footer .box-container .box form input[type="email"] {
  width: 100%;
  padding: 1rem 1.2rem;
  font-size: 1.6rem;
  color: #222;
  margin: 1rem 0;
  text-transform: none;
}

.footer .box-container .box .payment {
  width: 100%;
  margin-top: 2rem;
}

.credit {
  background: var(--primary-color);
  color: #fff;
  font-size: 2rem;
  height: 5rem;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Footer Section Ends */
</style>
</head>


<body>
  <!-- navbar starts here  -->
  <header>
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand" href="index.html">Quoki Tech</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <i class="fa fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link " href="index.html">Home </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="about.html"> About Us </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="products.html"> Our Products </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="Membership.html"> Membership </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="Events.html"> Events </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="course.html"> Our Courses </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="tel:123 456 7890"> Contact Us </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>


  <!-- navbar starts ends -->


  <!-- home section starts  -->
  <section class="home">



    
  <!-- footer section starts  -->

<section class="footer">

  <div class="box-container">

      <div class="box">
          <h3>quick links</h3>
          <a href="index.html"> <i class="fas fa-arrow-right"></i> Home </a>

          <a href="about.html"> <i class="fas fa-arrow-right"></i> About Us </a>

          <a href="products.html"> <i class="fas fa-arrow-right"></i>Our products</a>

          <a href="tel:123 456 7890"> <i class="fas fa-arrow-right"></i> Contact Us</a>

      </div>

      <div class="box">
          <h3>extra links</h3>

          <a href="Membership.html"> <i class="fas fa-arrow-right"></i> Membership</a>

          <a href="Events.html"> <i class="fas fa-arrow-right"></i> Events</a>

          <a href="course.html"> <i class="fas fa-arrow-right"></i>Our Courses</a>

      </div>

      <div class="box">
          <h3>follow us</h3>
          <a href="#"> <i class="fab fa-facebook-f"></i> facebook </a>
          <a href="#"> <i class="fab fa-twitter"></i> twitter </a>
          <a href="#"> <i class="fab fa-instagram"></i> instagram </a>
          <a href="#"> <i class="fab fa-linkedin"></i> linkedin </a>
          <a href="#"> <i class="fab fa-pinterest"></i> pinterest </a>
      </div>

      <div class="box">
          <h3>newsletter</h3>
          <p>subscribe for latest updates</p>
          <form action="">
              <input type="email" placeholder="enter your email">
              <input type="submit" value="subscribe" class="btn">
          </form>
          <img src="image/payment.png" class="payment" alt="">
      </div>

  </div>

</section>


<!-- footer section ends -->

  <!-- Boostrap JS CDN  -->
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"
    integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js"
    integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13"
    crossorigin="anonymous"></script>





</body>

</html>
























