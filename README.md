<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="blogdesign.css">

        <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>

        <title>My Personal blog</title>
    </head>
    <body>
        <header class="l-header">
            <nav class="nav bd-grid">
                <div>
                    <a href="#" class="nav__logo">Sairam</a>
                </div>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav_item"><a href="#home" class="nav_link active-link">Home</a></li>
                        <li class="nav_item"><a href="#about" class="nav_link">About</a></li>
                        <li class="nav_item"><a href="#skills" class="nav_link">Skills</a></li>
                        <li class="nav_item"><a href="#contact" class="nav_link">Contact</a></li>
                    </ul>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class='bx bx-menu'></i>
                </div>
            </nav>
        </header>

        <main class="l-main">
            <section class="home bd-grid" id="home">
                <div class="home__data">
                    <h1 class="home_title">Hi,<br>I'am <span class="home_title-color">sai ram</span><br> student </h1>

                    <a href="#" class="button">Contact</a>
                </div>

                <div class="home__social">
                    <a href="https://www.linkedin.com/in/sai-ram-3b9978253?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
                    <a href="https://github.com/vootukurisairam123" class="home__social-icon"><i class='bx bxl-github' ></i></a>
                </div>

                <div class="home__img">
                    <svg class="home__blob" viewBox="0 0 479 467" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                        
                    </svg>
                </div>
            </section>

            <section class="about section " id="about">
                <h2 class="section-title">About</h2>

                <div class="about__container bd-grid">
                    <div class="about__img">
                        <img src="https://tse4.mm.bing.net/th?id=OIP.cnDjxaNqBErUC9SpN8yaIQHaLH&pid=Api&P=0&h=220" alt="">
                         <p class="about__img">welcome to my blog....</p>
                    </div>
                    
                    <div>
                        <h2 class="about__subtitle">I'am sairam</h2>
                        <p class="about__text">im from malla reddy college of engineering and technology,currently im pursuing my Btech 3 year.</p>           
                    </div>                                   
                </div>
            </section>

            <section class="skills section" id="skills">
                <h2 class="section-title">Skills</h2>

                <div class="skills__container bd-grid">          
                    <div>
                        <h2 class="skills__subtitle">Profesional Skills</h2>
                        <p class="skills__text">HTML,
                                                CSS,
                                                PYTHON</p>
                                                  <h2 class="skills__subtitle">personal skills</h2>
              
                       <p class="skills__text">good listener,good observer,adaptability</p>
                    
                    

            <section class="contact section" id="contact">
                <h2 class="section-title">Contact</h2>

                <div class="contact__container bd-grid">
                    <form action="" class="contact__form">
                        <input type="text" placeholder="input name" class="contact__input">
                        <input type="mail" placeholder="input Email" class="contact__input">
                        <input type="text" placeholder="issue" textarea name="" id="" cols="0" rows="10" class="contact__input"></textarea>
                        <input type="button" value="contact" class="contact__button button">
                    </form>
                </div>
            </section>
        </main>

        <footer class="footer">
            <p class="footer__title">SAIRAM social media accounts</p>
            <div class="footer__social">
                <a href="#" class="footer__icon"><i class='bx bxl-facebook' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-instagram' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-twitter' ></i></a>
            </div>
            <p class="footer__copy">this is my blog(sairam)</p>
        </footer>

    </body>
</html>
