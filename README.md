<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-COMPATIBLE" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel ="stylesheet" href="style.css">
</head>
<body>
<div id="header">
    <div class="container">
        <nav>
            <div class="header-text">
            <h1>Hi, I'm <span>Emanoel Manibog Agbayani</span><br></h1>
            </div>
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Skills</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
                </ul>
            <i class="fa-solid fa-bars" onclick="openmenu()"></i>
        </nav>
    </div>
</div>
<!-----------about--------->
<div id="about">
    <div class="container">
        <div class = "row">
            <div class="about-col-1">
                <img src="images/user.jpg">
            </div>
            <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <p>My name is Emanoel Agbayani and I am currently a third  year Undergraduate at University of California San 
                    Diego. I am majoring in Cognitive Science: Machine  Learning and Neural Computation. I am Filipino 
                    American that was born in the Coachella Valley. I am an aspiring Data Analyst and Machine Learning
                    Engineer. Some hobbies of mine are guitar, videogames, and eating delicious food. Furthermore, I 
                    aspire to use my technical prowess in the Medical Field.</p>
                <div class="tab-titles">
                    <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                    <p class="tab-links" onclick="opentab('experience')">Leadership Experience</p>
                    <p class="tab-links" onclick="opentab('education')">Education</p>
                </div>
                <div class="tab-contents active-tab" id="skills">
                    <ul>
                        <li><span>Data Science</span>
                            <br>Programs: Python; SQL; R; Tensorflow
                            <br>Python Libraries: Numpy; Pandas; Seaborn PyTorch</li>
                        <li><span>Machine Learning</span>
                            <br>Python Libraries: Scikit Learn</li>
                        <li><span>Web Development</span>
                            <br>HTML
                            <br>CSS</li>
                    </ul>
                </div>
                <div class="tab-contents" id="experience">
                    <ul>
                        <li><span>September 2022-Current</span><br>Coach at UCSD Esports</li>
                        <li><span>2020 - 2022</span><br>Captain at Cathedral City Highschool</li>
                        <li><span>2020 - 2021</span><br>Junior Class Representative</li>
                    </ul>
                </div>
                <div class="tab-contents" id="education">
                    <ul>
                        <li><span>2026</span><br>Cognitive Science: Machine Learning and Neural Computation</li>
                        <li><span>2022</span>Cathedral City Highschool Diploma<br></li>
                        <li><span></span><br></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<!-----------services--------->

<div id="services">
    <div class="container">
        <h1 class="sub-title">My Skills</h1>
        <div class="services-list">
            <div>
                <i class="fa-solid fa-code"></i>
                <h2>Data Science</h2>
                <p>Data Science is an interdisciplinary field that requires a few skills. A few of these steps include: Data Collection;
                    Data analysis; Machine learning; and Data Visualization. With Data Science, you are able to ciphon information even
                    from the biggest of datasets while also contributing to society. </p>
                <a href="#">Learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-crop"></i>
                <h2>Machine Learning </h2>
                <p>Machine Learning is a subfield of Data Science. Furthermore, it can also relate to Artificial Intelligence. There
                    are a variety of Machine Learning Algorithms to help you make your model better. A few skills necessary are: 
                    Feature Engineering; Deep Learning; and Machine Learning Algorithms. </p>
                <a href="#">Learn more</a>
            </div>
            <div>
                <i class="fa-brands fa-app-store"></i>
                <h2>Web App Development</h2>
                <p>Web Application Development is the process of running web servers and making it acessible through a browser. 
                    A few skills required for Web App Development are: HTML; CSS; JavaScript; API development; database management;
                    and more!
                </p>
                <a href="#">Learn more</a>
            </div>
        </div>
    </div>
</div>

<!-----------portfolio--------->

<div id="portfolio">
    <div class="container">
        <h1 class="sub-title">My Work</h1>
        <div class="work-list">
            <div class="work">
                <img src="images/work-1.png">
                <div class="layer">
                    <h3>Hairloss Predictor</h3>
                    <p>Using a variety of Machine Learning Algorithms, I was able to find an Algorithm
                        with the highest average accuracy as well as taking into considering other metrics
                        to obtain the best model.</p>
                    <a href="https://github.com/Bloshing/PredictiveHairlossAnalysis"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-2.png">
                <div class="layer">
                    <h3>AI Trading Bot with Sentiment Analysis</h3>
                    <p>Using Sentiment Analysis, able to make a AI Trading Bot that shifts its trades
                        based on news and certain profit paramters.
                    </p>
                    <a href="https://github.com/Bloshing/AI-Trading-Bot"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-3.png">
                <div class="layer">
                    <h3>Robot Bird Flocking</h3>
                    <p>Using a Camera, able to mimic Bird Flocking with a series of Robots by making it
                        track the Robot infront of it. If Robot was not the Leader, they would be attempting
                        to track the Robot infront of it without deviating from the guideline for the Leader Bot.
                    </p>
                    <a href="https://makecode.microbit.org/_Vzr5m187k8f0"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
        </div>
        <a href="#" class="btn">See More</a>
    </div>
</div>

<!-----------contact--------->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-solid fa-paper-plane"></i>emanoelagbayani3@gmail.com</p>
                <p><i class="fa-solid fa-square-phone"></i></i>7607740566</p>
                <div class="social-icons">
                    <a href="https://www.linkedin.com/in/emanoel-agbayani-71772b345/"><i class="fa-brands fa-linkedin-in"></i></a>
                    <a href="https://github.com/Bloshing"><i class="fa-brands fa-github"></i></a>
                    <a href="https://www.instagram.com/idek.eman/"><i class="fa-brands fa-instagram"></i></a>
                </div>
                <a href="images/EmanoelAgbayani_Resume_2025.pdf" download class="btn btn2">Download Resume</a>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright @  Emanoel. Made with<i class="fa-solid fa-heart"></i>Emanoel Agbayani</p>
    </div>
</div>




</body>
</html>
