# Partima-s-Portfolio
#This is my personal portfolio i will update it Further
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Partima - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@1,200;1,500&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(0, 0, 33);
            color: aliceblue;
            font-family: 'Poppins', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 18, 62);
        }

        nav ul {
            display: flex;
            justify-self: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            color: rgb(155, 155, 236);
            font-size: 1.02rem;
        }

        main hr {
            border: 0;
            background: #9c97f1;
            height: 1.2px;
            margin: 60px 84px;
        }

        .left {
            font-size: 1.5rem;
        }

        .firstsection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 100px 0;


        }

        .firstsection>div {
            width: 38%;

        }

        .leftsection {
            font-size: 3rem;
        }

        .leftsection .btn {
            padding: 12px;
            background: rgb(26 26 53);
            color: white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;
        }

        .leftsection .buttons {
            padding: 50px 0;
        }

        .rightsection img {
            width: 80%;
        }

        .purple {
            color: rgb(186, 133, 235);

        }

        .text-gray {
            color: gray;
        }

        #element {
            color: rgb(186, 133, 235);
        }

        .secondsection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }

        .secondsection h1 {
            font-size: 1.9rem;
        }

        .secondsection .box {
            background: white;
            width: 77vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondsection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 12vw;

        }

        .image-top {
            width: 40px;
            position: relative;
            top: -50px;
            left: -9px;
        }

        .vertical-title {
            position: relative;
            top: 48px;
            width: 150px;
            font-size: 16px;

        }

        .vertical-desc {
            position: relative;
            top: 60px;
            color: gray;
            width: 150px;
            font-size: 11px;
        }

        footer {
            background-color: rgb(7, 2, 21);
        }

        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }

        footer.ul {
            list-style: none;
        }

        .footer>div {
            width: 223px;
        }

        footer .footer-rights {
            text-align: center;
            color: gray;
            padding: 12px 0;
        }

        @media screen and (max-width: 1200px) {
            .box{
                flex-direction: column;
            }
            .vertical-title , .vertical-desc{
                left: 40px;
            }
            .secondsection .box{
                width: 50vw;
            }
            nav{
                flex-direction: column;
            }
            
            .secondsection .vertical{
                height: unset;
            }
            .firstsection {
                flex-direction: column-reverse;
            }
            .leftsection{
                width: 100% !important;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
            }
            .rightsection{
                width: 700px !important;
                display: flex;
                justify-content: center;
            }
            .rightsection img{
                width: 45vw;
                margin-bottom: 73px;
            }
            .image-top{
                top: 100px;
            }
            .secondsection{
                max-width: 80vw;
                margin: auto;
                height: 141vh;
            }
            body{
                min-width: fit-content;
            }
            
        }
    </style>

</head>

<body>
    <header>
        <nav>
            <div class="left">Partima's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Project</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section class="firstsection">
            <div class="leftsection">
                <div>Hi,My name is <span class="purple">Partima Jain.</span></div>
                <div>I am Passionate</div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn">Download Resume</button>
                    <button class="btn">Visit Github</button>
                </div>
            </div>
            <div class="rightsection">
                <img src="/Users/partimajain/Downloads/pari.jpeg" alt="Pari image" width="150" height="500">
            </div>

        </section>
        <hr>
        <section class="secondsection">
            <span class="text-gray"> What I have Studied so far </span>
            <h1>Education</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="/Users/partimajain/Desktop/dav.png" alt="">
                    <div class="vertical-title">
                        10th From DAV School,Tohana(2019)
                    </div>
                    <div class="vertical-desc">
                        I scored 70% in my 10th-grade exams!.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="/Users/partimajain/Desktop/rigveda.png" alt="">
                    <div class="vertical-title">
                        12th From Rigveda International School,Tohana(2021)
                    </div>
                    <div class="vertical-desc">
                        I scored 76% in my 12th-grade exams!..
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="/Users/partimajain/Desktop/cgc.png" alt="">
                    <div class="vertical-title">
                        Btech(AiMl) From CGC,Jhanjheri(2021-2025)
                    </div>
                    <div class="vertical-desc">
                        I aced the previous semester with an 86% (4th Sem).
                    </div>
                </div>

            </div>
        </section>
    </main>
    <footer>
        <div class="footer">
            <div class="footer-first">
                Partima's Portfolio
            </div>
            <div class="footer-second">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Project</li>
                    <li>contact</li>
                </ul>
            </div>
            <div class="footer-third"></div>
            <div class="footer-fourth"></div>
        </div>
        <div class="footer-rights">
            Copyright &#169;partimasportfolio.com | All rights reserved
        </div>
    </footer>

    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Software Developer.', 'Full Stack Developer.'],
            typeSpeed: 50,
        });
    </script>
</body>

</html>
