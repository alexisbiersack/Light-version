# This is my light version of my personal website hope you like it!


### Here's the code of html nut fully semantic
```html
<!-- html -->
<!DOCTYPE html>
<html lang="en">

<head>
    <!-- meta-tags -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <meta name="Keywords" content="Front end developer,Front end UI Developer,Metal head, Coding is life">
    <meta name="Description" content="2018 Personal website by Mark Alexis Posadas.">
    <!-- /meta-tags -->
    <!-- stylesheet -->
    <link rel="stylesheet" href="css/style.css">
    <!-- google-font -->
    <link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
    <!-- /google-font -->
    <!-- font-awesome -->
    <link rel="stylesheet" href="fonts/css/font-awesome.css">
    <!-- /font-awesome -->
    <!-- /stylesheet -->
    <title>Portfolio || 2018</title>
</head>exit

<body>
    <main>
        <!-- header -->
        <header id="top-header">
            <!-- parent -->
            <nav class="navigation-bar">
                <!-- items -->
                <a href="#" class="logo">Home</a>
                <a href="#projects">Projects</a>
                <a href="#about-me">About</a>
                <a href="#contact">Contact</a>
                <!-- /items -->
            </nav>
            <!-- /parent -->
        </header>
        <!-- /header -->

        <!-- container -->
        <section id="container">
            <div class="row">
                <div class="background-title">
                    <h1 class="name">Mark Alexis Posadas</h1>
                    <h2 class="description">Aspiring Front End Developer</h2>
                </div>
            </div>
        </section>
        <!-- /container -->

        <!-- projects -->
        <section id="projects">
            <div class="col-projects">
                <div class="items">
                    <h3 class="project-name">Practice 1</h3>
                    <p><a href="https://github.com/alexisbiersack/Portfolio" target="_blank" class="view-project">View</a></p>
                </div>

                <div class="items">
                    <h3 class="project-name">Practice 2</h3>
                    <p><a href="https://codepen.io/alexisposadas/pen/QBGaoP" target="_blank" class="view-project">View</a></p>
                </div>

                <div class="items">
                    <h3 class="project-name">Practice 3</h3>
                    <p><a href="https://alexisposadas.imgur.com/all/" target="_blank" class="view-project">View</a></p>
                </div>

                <div class="items">
                    <h3 class="project-name">Practic 4</h3>
                    <p><a href="#" class="view-project">View</a></p>
                </div>

                <div class="items">
                    <h3 class="project-name">Practice 5</h3>
                    <p><a href="#" class="view-project">View</a></p>
                </div>

                <div class="items">
                    <h3 class="project-name"><a href="#" class="all-projects">View all here</a></h3>
                </div>
            </div>
        </section>
        <!-- /projects -->

        <!-- about-me -->
        <section id="about-me">
            <div class="container-about">
                <div class="about-inner">
                    <p>Hello there! My name is Mark Alexis Posadas Aspiring Front End Developer or UI Developer Based in the Philippines.
                        I've been developing Static website for over 3 years now.
                        I love html and css a lot also javascript but not really good because I am a newbie programmer in javascript.I used sass also for personal projects and bootstrap,bulma css for big projects.</p>
                </div>
            </div>
        </section>
        <!-- /about-me -->

        <!-- contact -->
        <section id="contact">
            <div class="contact-wrapper">
                <div class="contact-inner">
                    <a href="https://twitter.com/posadasalexis6" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                    <a href="https://github.com/alexisbiersack" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
                    <a href="https://codepen.io/alexisposadas/" target="_blank"><i class="fa fa-codepen" aria-hidden="true"></i></a>
                    <!-- <a href="#"><i class="fa fa-envelope-o fa-1x" aria-hidden="true"></i></a> -->
                    <!-- <a href="#"><i class="fa fa-envelope fa-stack-1x fa-fw" alt="Email: markalexisposadas@gmail.com"></i></a> -->
                </div>
            </div>
        </section>

        <!-- footer -->
        <footer id="footer">
            <div class="footer-wrapper">
                <div class="footer-inner">
                    <p class="me">&copy; Mark Alexis Posadas 2018</p>
                </div>
            </div>
        </footer>
        <!-- /footer -->
    </main>
</body>

</html>
<!-- /html -->
```

### Here's the Css file

```Css
/*variables*/
/* reset */
* {
    padding: 0;
    margin: 0;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

/* /reset */
html body {
    font-family: 'Open Sans', sans-serif;
    scroll-behavior: smooth;
}

main {
    width: 100%;
}

h1, h2, h3, h4, h5, h6 {
    -webkit-font-smoothing: antialiased;
    text-rendering: optimizelegibility;
}

#top-header {
    background: #fff;
    border-bottom: 1px solid #dadada;
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
}

#top-header .navigation-bar {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -ms-flex-direction: row;
    flex-direction: row;
    height: 3rem;
}

#top-header .navigation-bar .logo {
    font-weight: 700;
    color: #32ADAD;
}

#top-header .navigation-bar .logo:hover {
    color: #32ADAD;
}

#top-header .navigation-bar a {
    position: relative;
    -webkit-box-flex: 1;
    -ms-flex: 1;
    flex: 1;
    color: #66757f;
    text-decoration: none;
    text-align: center;
    font-weight: 700;
}

#top-header .navigation-bar a:hover {
    color: #32ADAD;
}

#container {-0
    width: 100%;
    background: #f0f0f0;
    border-bottom: 1px solid #dadada;
}

#container .row {
    width: 100%;
    height: 390px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-flow: column;
    flex-flow: column;
}

#container .background-title {
    background: #fff;
    padding: 2rem;
}

#container .description {
    text-align: center;
    color: #66757f;
}

#container .name {
    text-align: center;
    font-size: 2rem;
    font-weight: 700;
    letter-spacing: 4px;
    background: url(../img/bg.jpg);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
}

#container .description {
    font-weight: 300;
    font-size: 1rem;
    letter-spacing: 2px;
}

#projects {
    width: 100%;
    padding: 6rem 0;
    background: #f0f0f0;
}

#projects .col-projects {
    max-width: 90%;
    margin: auto;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
}

#projects .items {
    background: #fafafa;
    -webkit-box-shadow: 1px 15px 45px -10px rgba(0, 0, 0, 0.2);
    box-shadow: 1px 15px 45px -10px rgba(0, 0, 0, 0.2);
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    border-radius: .2rem;
    height: 300px;
    width: 300px;
    margin: .5rem;
}

#projects .project-name {
    color: #32ADAD;
    font-size: 1.2rem;
    letter-spacing: 1px;
}

#projects .all-projects {
    text-decoration: underline;
    color: #66757f;
}

#projects .all-projects:hover {
    color: #32ADAD;
    -webkit-transition: 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    -o-transition: 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    transition: 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}

#projects .view-project {
    font-size: 1rem;
    text-decoration: underline;
    color: #66757f;
    letter-spacing: 1px;
}

#projects .view-project:hover {
    color: #32ADAD;
    -webkit-transition: 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    -o-transition: 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    transition: 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}

#about-me {
    width: 100%;
    background: #f0f0f0;
    border-top: 1px solid #dadada;
}

#about-me .container-about {
    width: 70%;
    max-width: 100%;
    margin: 0 auto;
}

#about-me .about-inner {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    height: 100vh;
}

#about-me p {
    font-size: 1.1rem;
    color: #66757f;
    letter-spacing: 1px;
    line-height: 1.6;
}

#contact {
    width: 100%;
    background: #f0f0f0;
    border-top: 1px solid #dadada;
}

#contact .contact-wrapper {
    max-width: 90%;
    margin: 0 auto;
}

#contact .contact-inner {
    height: 100vh;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
}

#contact .contact-inner i {
    margin: 2rem 0;
    font-size: 2.8rem;
    text-decoration: none;
    color: #66757f;
}

#contact .contact-inner i:hover {
    color: #32ADAD;
}

#contact .contact-inner a {
    -webkit-box-flex: 1;
    -ms-flex: 1;
    flex: 1;
    text-align: center;
}

#footer {
    width: 100%;
    background: #fff;
    border-top: 1px solid #dadada;
}

#footer .footer-wrapper {
    max-width: 90%;
    margin: 0 auto;
    height: 200px;
}

#footer .footer-inner {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    height: 200px;
}

#footer .me {
    color: #66757f;
    font-size: 1rem;
    letter-spacing: 2px;
}

@media (max-width: 800px) {
    #container .background-title {
        padding: 2rem;
        width: 100%;
    }

    #container .name {
        font-size: 2rem;
    }

    #container .description {
        font-size: .9rem;
    }

    #contact .contact-inner {
        -webkit-box-orient: vertical;
        -webkit-box-direction: normal;
        -ms-flex-direction: column;
        flex-direction: column;
    }

    #contact .contact-inner a {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: center;
        -ms-flex-align: center;
        align-items: center;
        text-decoration: none;
    }
}
```
