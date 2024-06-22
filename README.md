# Portfolio
First Portfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanchit Singh Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: black;
            color: white;
            font-family: "Poppins", sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(6, 6, 54);
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 25px;

        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            color: rgb(103, 12, 12);
            font-size: 1.5rem;
        }


        .left {
            font-size: 1.25rem;
        }

        .firstsection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 130px 0;

        }

        .leftsection {
            /* background-color: red; */
            /* width:34px; */
            font-size: 3rem;
            margin: 70px o;

        }


        .rightsection {
            /* background-color: red; */

        }

        .firstsection>div {
            width: 30%;

        }

        .rightsection img {
            width: 80%;
            margin: 50px 0;

        }

        .purple {

            color: rgb(11, 11, 101)1;
        }


        #element {
            color: blueviolet;
        }

        .secondSection {
            max-width: 80uv;
            margin: auto;
            height: 80vh;
        }

        main hr {
            border: 0;
            background: #0c0772;
            height: 12px;
            /* margin: 40px 84px; */
        }

        .secondSection h1 {
            font-size: 2rem;

        }

        .grey {
            text-decoration-color: gray;
        }

        .box {
            background: rgb(20, 0, 150);
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
            padding: 4px;

        }

        .vertical {
            height: 100px;
            width: 5px;
            background-color: rgb(178, 163, 179);
            margin: 0 120px;
        }

        .image-top {
            width: 50px;
            position: relative;
            top: -62px;
            left: -9px;
        }

        .vertical-title {
            position: relative;
            top: 75px;
            width: 150px;
            font-size: 14px;


        }

        .vertical-desc {
            position: relative;
            top: 90px;
            color: grey;
            width: 150px;
            font-size: 12px;

        }

        .footer {
            display: absolute;
            padding: 40px 60px;
            justify-content: space-evenly;

        }

        footer {
            background-color: rgb(12, 41, 55);
            /* height: 220px; */

        }

        footer ul {
            list-style: none;
        }

        .footer>div {
            width: 20px;
        }

        footer .footer-rights {
            text-align: center;
            color: rgb(70, 60, 216);
            /* padding: 10px 10px; */

        }

        .btns {
            background-color: #1a148b;
            color: rgb(191, 189, 192);
            border: 3px solid white;
            border-radius: 4px;
            font-size: 20px;

        }

        .leftsection .buttons {
            padding: 10px;
            /* cursor:hover; */
        }

        .leftsection .buttons .btns:hover {
            color: #8b1414;
            /* cursor:hover; */
            font-size: 25px;
            cursor: pointer;
        }

        .one {
            height: 340px;
            width: 500px;
            padding: 5px 5px;
        }
    </style>
</head>

<body>

    <header>
        <nav>
            <div class="left">Sanchit's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li> <a href="/">Service</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section class="firstsection">
            <div class="leftsection">Hi ,My name is <span class="purple">Atomicx</span>
                <div>I am a passionate</div>
                <div>Web Developer</div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btns">Resume</button>
                    <button class="btns">View Github</button>
                </div>
            </div>
            <div class="rightsection">
                <img class="one" src="developer2.png" alt="You better know!">
            </div>
        </section>
        <hr>

        <section class="secondSection">
            <span class="grey">What I have learn so far!</span>
            <h1>Work Experience</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="html2.png" alt="You better know">
                    <div class="vertical-title">
                        HTML Developer
                    </div>

                    <div class="vertical-desc">
                        Hyper Text Markup Language
                        HTML stands for Hyper Text Markup Language. HTML is the standard markup language for creating
                        Web pages. HTML describes the structure of a Web page. HTML consists of a series of elements.
                        HTML elements tell the browser how to display the content.
                    </div>


                </div>
                <div class="vertical">
                    <img class="image-top" src="css.png" alt="You better know">
                    <div class="vertical-title">
                        CSS Developer
                    </div>

                    <div class="vertical-desc">
                        CSS is a design language that makes a website look more appealing than just plain or uninspiring
                        pieces of text. Whereas HTML largely determines textual content, CSS determines visual
                        structure, layout, and aesthetics.
                    </div>

                </div>
                <div class="vertical">
                    <img class="image-top" src="javascript.png" alt="You better know">

                    <div class="vertical-title">
                        JavaScript Developer
                    </div>

                    <div class="vertical-desc">
                        JavaScript is a programming language used to create dynamic content for websites. It achieves
                        this by adding new HTML elements while modifying existing ones. Many coders enhance web
                        development skills using JavaScript to create user-friendly and interactive websites.
                    </div>
                    <!-- <div class="vertical">
                        <img class="image-top" src="pv2.jpeg" alt="You better know">
                        <div class="vertical-title">
                            Python Developer
                        </div>
                        <div class="vertical-desc">
                            Python is often used as a support language for software developers, for build control and
                            management, testing, and in many other ways. SCons for build control. Buildbot and Apache
                            Gump for automated continuous compilation and testing. Roundup or Trac for bug tracking and
                            project management.
                        </div>
                    </div> -->
        </section>

    </main>

    <footer>
        <div class="footer">
            <div class="first">
                <h2>Live Young,Live free</h2>
            </div>
            <div class="second">

                <ul>
                    <li>Contact Us</li>
                    <li>Help</li>
                </ul>
            </div>
            <!-- <div class="footer-third"></div>
            <div class="footer-fourth"></div> -->
        </div>
        <div class="footer-rights">
            Copyright&#169; www.sanchitportfolio.com | @All rights reserved
        </div>
    </footer>


    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

    <script>
        var typed = new Typed('#element', {
            strings: ['<i>Web Developer</i> ', '&amp; Graphic Designer.', 'MotherFucker Starboy','Jai Shree Ram'],
            typeSpeed: 50,
        });
    </script>

</body>


</html>
