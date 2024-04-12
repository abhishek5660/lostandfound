# lostandfound

HTML 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lost and found</title>
    <!-- 
    - favicon
  -->
    <link rel="shortcut icon" href="./icon.svg" type="image/svg+xml">
    <!-- 
    - custom css link
  -->
    <link rel="stylesheet" href="./assets/css/style.css">
    <!-- .5
        6
    - google font link   
  -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&family=Source+Sans+Pro:wght@600;700&display=swap" rel="stylesheet">
</head>
<body id="top">
    <!-- 
    - #HEADER
  -->
    <header class="header" data-header>
        <div class="container">
            <div class="overlay" data-overlay></div>
            <a href="#">
                ✿
                <h1 class="logo">LOST & FOUND</h1>
            </a>
            <nav class="navbar" data-navbar>
                <div class="navbar-top">
                    <a href="#" class="logo">Lost & Found</a>
                    <button class="nav-close-btn" aria-label="Close Menu" data-nav-close-btn>
            <ion-icon name="close-outline"></ion-icon>
          </button>
                </div>
                <ul class="navbar-list">
                    <li class="navbar-item">
                        <a href="" class="navbar-link" data-navbar-link>Home</a>
                    </li>
                    <li class="navbar-item">
                        <a href="http://127.0.0.1:5500/PROJECT-1/lostitem.html" class="navbar-link" data-navbar-link>Lost item</a>
    </li>
</li>
<li class="navbar-item">
    <a href="http://127.0.0.1:5500/PROJECT-1/founditem.html" class="navbar-link" data-navbar-link>Found item</a>
</li>
                    <li class="navbar-item">
                        <a href="http://127.0.0.1:5500/PROJECT-1/auth.html" class="navbar-link" data-navbar-link>login</a>
                    </li>
                </li>  
                    <li class="navbar-item">
                        <a href="http://127.0.0.1:5500/PROJECT-1/.html" class="navbar-link" data-navbar-link>Contact Us</a>
              </li>
            </ul>                   
            </nav>
            <nav>
            <a href="http://127.0.0.1:5500/PROJECT-1/popup.html" class="btn">
                <ion-icon name="chevron-forward-outline" aria-hidden="true"></ion-icon>
                <span>User Profile</span>
            </a>
            <button class="nav-open-btn" aria-label="Open Menu" data-nav-open-btn>
        <ion-icon name="menu-outline"></ion-icon>
      </button>
        </div>
    </header>
    <main>
        <article>
            <!-- 
        - #HERO
      -->
            <section class="hero" id="home">
                <div class="container">
                    <div class="hero-content">
                        <p class="hero-subtitle">The Lost and Found App makes your life easier.</p>
                        <h2 class="h2 hero-title">LOST ITEM SOLUTION</h2>
                        <p class="h2 hero-text">
                            Returning Lost Items Back To Their Owners Quickly And Seamlessly.
                        </p>
                        <button class="btn"><a href="http://127.0.0.1:5500/PROJECT-1/googlemap.html" class="navbar-link" data-navbar-link>Location</button></a>
                    </div>
                    <figure class="hero-banner">    
                        <img src="https://i.pinimg.com/originals/42/0d/73/420d73f8499b2ae96eb3aab67973598d.jpg" width="494" height="329" loading="lazy" alt="hero-banner" class="w-80 banner-animation">
                    </figure>
                </div>
            </section>
            <!--        
        - #ABOUT
            -->
            <section class="section about" id="about">
                <div class="container">
                    <figure class="about-banner">
                        <img src="https://codewithsadee.github.io/desinic/assets/images/about-banner.png" width="700" height="532" loading="lazy" alt="about banner" class="w-100 banner-animation">
                    </figure>
                    <div class="about-content">
                        <h2 class="h2 section-title underline">Why Our Lost&Found</h2>
                        <p class="about-text">
                            The world right now is distracted. People are always checking their phones every few minutes or lost in thought about personal and career problems. The management of your lost and found department can break or build your customers’ trust. Lost and found software provides a solution. It makes the management of these items smooth, without breaking your budget.
                        </p>
                        <p class="about-text">
                            Losing a property, especially if it’s of sentimental value, causes emotional turmoil. The last thing your agitated customer needs is false hope.
                        </p>
                        <ul class="stats-list">
                            <li class="stats-card">
                                <p class="h3 stats-title">000</p>
                                <p class="stats-text">Satisfied Clients</p>
                            </li>
                            <li class="stats-card">
                                <p class="h3 stats-title">2024</p>
                                <p class="stats-text">Project Lunched</p>
                            </li>
                            <li class="stats-card">
                                <p class="h3 stats-title">00</p>
                                <p class="stats-text">Years Completed</p>
                            </li>
                        </ul>
                    </div>
                </div>
            </section>
            <!-- 
        - #SERVICE
      -->\
            <section class="section service" id="services">
                <div class="container">
                    <h2 class="h2 section-title underline">HOW IT WORKS ?</h2>
                    <ul class="service-list">
                        <li>
                            <div class="service-card">
                                <div class="card-icon">
                                    <ion-icon name="telescope-outline"></ion-icon>
                                </div>
                               <a href="http://127.0.0.1:5500/PROJECT-1/auth.html"> <h3 class="h3 title">Create an account</h3></a>
                                <p class="text">
                                    Initially, you have create an account to get started
                                </p>
                                <button class="card-btn" aria-label="Show More">
                  <ion-icon name="chevron-forward-outline"></ion-icon>
                </button>
                            </div>
                        </li>
                        <li>
                            <div class="service-card">                              
                                <div class="card-icon">
                                    <ion-icon name="desktop-outline"></ion-icon>
                                </div>
                                <h3 class="h3 title">lost/Find items</h3>        
                                <p class="text">
                                List your item on the wall by falling certain details and image. That's it!
                                </p>
                                <button class="card-btn" aria-label="Show More">
                  <ion-icon name="chevron-forward-outline"></ion-icon>
                </button> 
                            </div>
                        </li>
                        <li>
                            <div class="service-card">  
                                <div class="card-icon">
                                    <ion-icon name="globe-outline"></ion-icon>
                                </div>
                               <a href="http://127.0.0.1:5500/notification.html"> <h3 class="h3 title">Get Notified</h3></a>
                                <p class="text">
                                    Once anyone posts an item, we make our registed users aware about the same by sending notifications.
                                </p>
                                <button class="card-btn" aria-label="Show More">
                  <ion-icon name="chevron-forward-outline"></ion-icon>
                </button>
                            </div>
                        </li>
                    </ul>
                </div>
            </section>
            <!-- 
        - #FEATURES
      -->
    <section class="section features" id="features">
                <div class="container">
                    <h2 class="h2 section-title underline">Our Features</h2>
                    <ul class="features-list">
                        <li>
                            <div class="features-card">
                                <div class="icon">
                                    <ion-icon name="bulb-outline"></ion-icon>
                                </div>
                                <div class="content">
                                    <h3 class="h3 title">LOST ITEM</h3>
                                    <p class="text">
                                        Common law defines lost property as personal property that was unintentionally left by its true owner. For example, a wallet that falls out of someone's pocket is lost. At common law, a person who found lost personal property could keep it until and unless the original owner comes forward.
                                    </p>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div class="features-card">
                                <div class="icon">
                                    <ion-icon name="color-palette-outline"></ion-icon>
                                </div>
                                <div class="content">
                                    <h3 class="h3 title">Feedback</h3>
                                    <p class="text">
                                        The plot was predictable, something that made the movie boring and in many moments I was just trying to find a reason to continue watching it. loremipsum   loremipsum   loremipsum   loremipsum   loremipsum   loremipsum   loremipsum 
                                    </p>
                                </div>
                            </div>
                        </li>
                    </ul>
                    <figure class="features-banner">
                        <img src="https://codewithsadee.github.io/desinic/assets/images/feautres-banner.png" width="369" height="318" loading="lazy" alt="Features Banner" class="w-100 banner-animation">
                    </figure>
                    <ul class="features-list">
                        <li>
                            <div class="features-card">
                                <div class="icon">
                                    <ion-icon name="code-slash-outline"></ion-icon>
                                </div>
                                <div class="content">
                                    <h3 class="h3 title">FOUND ITEM</h3>
                                    <p class="text">
                                        You can use phone, email, or social media to contact the guest, or wait for them to contact you. You should verify their identity and ownership of the item, and ask them how they prefer to receive it. 
                                    </p>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div class="features-card">
                                <div class="icon">
                                    <ion-icon name="rocket-outline"></ion-icon>
                                </div>
                                <div class="content">
                                    <h3 class="h3 title">Testing & Lunching</h3>
                                    <p class="text">
                                        Visual Studio Code is a free coding editor that helps you start coding quickly. Use it to code in any programming language, without switching editors. Visual Studio Code has support for many languages, including Python, Java, C++, JavaScript, and more.
                                    </p>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
            </section>
            <!-- 
        - #BLOG
      -->
            <section class="section blog" id="blog">
                <div class="container">
                    <h2 class="h2 section-title underline">Our Blog & News</h2>
                    <ul class="blog-list">
                        <li>
                            <div class="blog-card">
                                <figure class="banner">
                                    <a href="">
                    <img src="https://media.istockphoto.com/id/1739381148/vector/lost-items-icon-lost-and-found.jpg?s=612x612&w=0&k=20&c=cfMKPPNCCI-R95iEBcALlkCbgBVPj5smE7RG1aRRAcU=" width="750" height="350" loading="lazy"
                      alt="Vestibulum massa arcu, consectetu pellentesque scelerisque." class="img-cover">
                  </a>
                 </figure>
                <div class="content">
                        <h3 class="h3 title">
                                        <a href="#">
                                            Lost And Found Real-Time Object Detection
                    </a>
                                    </h3>
                                    <p class="text">
                                        We are proud to present the first working prototype of our “Real Time Object Detection? function.
                                    </p>
                                    <div class="meta">
                                        <div class="publish-date">
                                           <ion-icon name="time-outline"></ion-icon>
                                          <time datetime="2022-03-07"> 9 feb, 2024 </time>
                                        </div>
                                        <button class="comment" aria-label="Comment">
                      <ion-icon name="chatbubble-outline"></ion-icon>
                      <data value="15">15</data>
                                        </button>
                                        <button class="share" aria-label="Share">
                      <ion-icon name="share-social-outline"></ion-icon>
                    </button>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div class="blog-card">
                                <figure class="banner">
                                    <a href="#">
                    <img src="https://media.istockphoto.com/id/477273563/vector/lost-found-box.jpg?s=612x612&w=0&k=20&c=D63_IrCalWqRLpYCnBA5b5QTfhxwbSggkxLiw7vQGGs=" width="750" height="350" loading="lazy"
                      alt="Quisque egestas iaculis felis eget placerat ut pulvinar mi." class="img-cover">
                  </a>
                                </figure>
                                <div class="content">               
                                    <h3 class="h3 title">
                                        <a href="#">
                                            Why is it called lost and found?
                    </a>
                                    </h3>
                                    <p class="text">
                                        It's items that someone lost and someone else found. The title helps people who have lost items to find out where they might find them.
                                    </p>
                                    <div class="meta">
                                        <div class="publish-date">
                                            <ion-icon name="time-outline"></ion-icon>
                                            <time datetime="2022-03-07">9 feb, 2024</time>
                                        </div>
                                        <button class="comment" aria-label="Comment">
                      <ion-icon name="chatbubble-outline"></ion-icon>
                      <data value="15">15</data>
                    </button>
                                        <button class="share" aria-label="Share">
                      <ion-icon name="share-social-outline"></ion-icon>
                    </button>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div class="blog-card">
                                <figure class="banner">
                                    <a href="#">
                    <img src="https://media.istockphoto.com/id/471374521/photo/lost-and-found-box.jpg?s=612x612&w=0&k=20&c=KHDtL0ZoQ-AoX_WIMRtXPc7R5CkJN_rC1atNsHjZdaQ=" width="750" height="350" loading="lazy"
                      alt="Fusce sem ligula, imperdiet sed nisi sit amet, euismod posuere." class="img-cover">
                  </a>
                                </figure>
                                <div class="content">
                                    <h3 class="h3 title">
                                        <a href="#">
                                            Can I found a person by photo?
                    </a>
                                    </h3>
                                    <p class="text">
                                        It is possible to try and find a person using a photo, but it may be difficult without additional information. 
                                    </p>
                                    <div class="meta">
                                        <div class="publish-date">
                                            <ion-icon name="time-outline"></ion-icon>
                                            <time datetime="2022-03-07">9 feb, 2024</time>
                                        </div>
                                        <button class="comment" aria-label="Comment">
                      <ion-icon name="chatbubble-outline"></ion-icon>
                      <data value="15">15</data>
                    </button>
                                       <button class="share" aria-label="Share">
                      <ion-icon name="share-social-outline"></ion-icon>
                    </button>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div class="blog-card">
                                <figure class="banner">
                                    <a href="#">
                    <img src="https://www.hillelementary.com/wp-content/uploads/2018/05/lostandfound.jpg" width="750" height="350" loading="lazy"
                      alt="Donec feugiat mollis nisi in dignissim. Morbi sollicitudin quis." class="img-cover">
                  </a>
                                </figure>
                                <div class="content">
                                    <h3 class="h3 title">
                                        <a href="https://en.wikipedia.org/wiki/Lost_and_found#:~:text=The%20first%20modern%20lost%20and,the%20office's%20director%20in%202001.">
                                            Who started lost and found?
                    </a>
                                    </h3>
                                    <p class="text">
                                        The first modern lost and found office was organized in Paris in 1805.
                                    </p>
                                    <div class="meta">
                                        <div class="publish-date">
                                            <ion-icon name="time-outline"></ion-icon>
                                            <time datetime="2022-03-07">9 feb, 2024</time>
                                        </div>
                                        <button class="comment" aria-label="Comment">
                      <ion-icon name="chatbubble-outline"></ion-icon>
                      <data value="15">15</data>
                    </button>
                                        <button class="share" aria-label="Share">
                      <ion-icon name="share-social-outline"></ion-icon>
                    </button>
                                    </div>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
            </section>
        </article>
    </main>
    <!-- 
    - #FOOTER
  -->
    <footer class="footer">
        <div class="footer-top section">
            <div class="container">
                <div class="footer-brand">
                    <a href="#" class="logo">The Lost & Found</a>
                    <p class="text">
                        We created this app for anyone to handle Lost and Found. Over the last couple of years,
                         our team has built a Software and App using the latest web technologies in cooperation
                          with industry leaders from hospitality, aviation and public transportation.
                    </p>
                    <ul class="social-list">
                        <li>
                            <a href="https://www.facebook.com/" class="social-link">
                                <ion-icon name="logo-facebook"></ion-icon>
                            </a>
                        </li>
                        <li>
                            <a href="https://www.instagram.com/accounts/login/?hl=en" class="social-link">
                                <ion-icon name="logo-instagram"></ion-icon>
                            </a>
                        </li>
                        <li>
                            <a href="https://twitter.com/i/flow/login" class="social-link">
                                <ion-icon name="logo-twitter"></ion-icon>
                            </a>
                        </li>
                    </ul>
                </div>
                <ul class="footer-list">
                    <li>
                        <p class="footer-list-title">Our links</p>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Home</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">About Us</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Service</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Team</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Blog</a>
                    </li>
                </ul>
                <ul class="footer-list">
                    <li>
                        <p class="footer-list-title">Our site</p>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Strategy & Research</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Web Development</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Web Solution</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Lost and found</a>
                    </li>
                </ul>
                <ul class="footer-list">
                    <li>
                        <p class="footer-list-title">Other links</p>
                    </li>
                    <li>
                        <a href="#" class="footer-link">FAQ</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Portfolio</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Privacy Policy</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Terms & Conditions</a>
                    </li>
                    <li>
                        <a href="#" class="footer-link">Support</a>
                    </li>
                </ul>
                <ul class="footer-list">
                    <li>
                        <p class="footer-list-title">Contact Us</p>
                    </li>
                    <li class="footer-item">
                        <div class="footer-item-icon">
                            <ion-icon name="call"></ion-icon>
                        </div>
                        <div>
                            <a href="tel:7018594320" class="footer-item-link">+91 7018594320</a>
                            <a href="tel:8219472136" class="footer-item-link">+91 8219472136</a>
                            <a href="tel:8894384777" class="footer-item-link">+91 8894384777</a>
                        </div>
                    </li>
                    <li class="footer-item">
                        <div class="footer-item-icon">
                            <ion-icon name="mail"></ion-icon>
                        </div>
                        <div>
                            <a href="abhishek1013.be22@chitkarauniversity.edu.in" class="footer-item-link">abhishek1013.be22@chitkarauniversity.edu.in</a>
                            <a href="kartik1193.be22@chitkarauniversity.edu.in" class="footer-item-link">kartik1193.be22@chitkarauniversity.edu.in</a>
                            <a href="aditya1021.be22@chitkarauniversity.edu.in" class="footer-item-link">aditya1021.be22@chitkarauniversity.edu.in</a>
                        </div>
                    </li>
                    <li class="footer-item">
                        <div class="footer-item-icon">
                            <ion-icon name="location"></ion-icon>
                        </div>
                        <address class="footer-item-link">
              Himachal pradesh, India.
            </address>
                    </li>
                </ul>
            </div>
        </div>
        <div class="footer-bottom">
            <p class="copyright">
                &copy; 2024 <a href="#" class="copyright-link">thriceteam</a>.All Right Reserved
            </p>
        </div>
    </footer>
    <!-- 
    - #GO TO TOP
  -->
    <a href="#top" class="go-top  active" aria-label="Go To Top" data-go-top>
        <ion-icon name="arrow-up-outline"></ion-icon>
    </a>
    <!-- 
    - custom js link
  -->
    <script src="./assets/js/script.js"></script>
    <!-- 
    - ionicon link
  -->
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
</body>
</html>
