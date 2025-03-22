 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
   
    <script src="https://kit.fontawesome.com/9e463a2bb4.js" crossorigin="anonymous"></script>
</head>
<body>
<div id="header">
    <div class="container">
        <nav>
            <img src="logo-6.png">
            <ul id="sidemenu">
                <li><a href="#header">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
                <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
            </ul> 
            <i class="fa-solid fa-bars"onclick="openmenu()"></i>
               
        </nav>
        <div><br>
           
        </div>
        <div class="header-text">
           
            <h2 style="text-align: center;"><span> RIFANA PA</span><br></h2>
          
           
            <p style="text-align: center;">Front-end Developer | UI/UX Designer</p>
        </div>
    </div>
</div>
<div>
    <!-- ----------about---------- -->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="aboutme.png">
                </div>
                <div class="about-col-2">
                    <h1 style="font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;" class="sub-title">ABOUT ME</h1><br>
                    <p >Hello! I'm Rifana PA, a passionate front-end developer and UI/UX designer dedicated to crafting exceptional digital experiences. With more than 5 years of experience in the industry, I've developed a strong foundation in HTML, CSS, JavaScript, and React. My design philosophy is centered around user-centered design, simplicity, and innovative problem-solving. When I'm not coding or designing, you can find me dealing with paintings. Let's connect and create something amazing together!</p>
                   <br>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('SKILLS')">SKILLS</p><br>
                        <p class="tab-links" onclick="opentab('EXPERIENCE')">EXPERIENCE</p><br>
                        <p class="tab-links" onclick="opentab('EDUCATION')">EDUCATION</p><br>

                    </div>
                    <div class="tab-contents active-tab" id="SKILLS">
                        <ul>
                            <li>
                                <span>UI/UX</span><br>Designing Web/App interfaces
                            </li><br>
                            <li>
                                <span>Web Development</span><br>Web App Development
                            </li><br>
                            <li>
                                <span>App Development</span><br>Building Android/iOS Apps
                            </li><br>
                            <li>
                                <span>Front-end developer</span><br>Building Front-end of Web/Applications
                            </li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="EXPERIENCE">
                        <ul>
                            <li>
                                <span>2025 - Current</span><br>UI/UX Design Trainer and Front-end Developer at ET Institute
                            </li><br>
                            <li>
                                <span>2023 - 2025</span><br>Team lead at Startup LLC.
                            </li><br>
                            <li>
                                <span>2021 - 2023</span><br>UI/UX Design Executive at Coin Digital Ltd.
                            </li><br>
                            <li>
                                <span>2020 - 2021</span><br>Internship at Varcons Technology Private Ltd.
                            </li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="EDUCATION">
                        <ul>
                            <li>
                                <span>2020</span><br>UI/UX Design Training at EET Institute Bangalore.
                            </li><br>
                            <li>
                                <span>2019</span><br>Front-end Training at EET Institute Bangalore.
                            </li><br>
                            <li>
                                <span>2018</span><br>BE from HMSIT Tumkur.
                            </li><br>
                           
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- ------services----- -->
 <div id="services">
    <div class="container">
        <h1 class="sub-title">MY SERVICES</h1><br>
        <div class="services-list">
            <div>
                <i class="fa-sharp fa-solid fa-code"></i><br>
               
                <h2>Web Design</h2><br>
                <p>
                 Custom Website Design: Creating a unique and tailored website design that reflects the client's brand and vision.<br>
                 Responsive Web Design: Designing websites that are optimized for various devices, including desktops, laptops, tablets, and smartphones.<br>
                 Website Redesign: Updating and refreshing an existing website's design to improve its appearance, usability, and performance.<br>
                 Landing Page Design: Creating dedicated landing pages that are optimized for conversions, such as sales, sign-ups, or downloads.<br>
                    
                </p><br>
                <a href="#">Learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-crop-simple"></i><br>
                <h2>UI/UX Design</h2><br>
                <p>
 User Research: Conducting research to understand the target audience's needs, behaviors, and motivations.<br>
 Wireframing: Creating low-fidelity sketches of the website's layout and functionality.<br>
  Visual Design: Creating the visual design of the application, including the color scheme, typography, and imagery.<br>
 Icon Design: Designing custom icons that are used throughout the application.<br>
Button Design: Designing custom buttons that are used throughout the application.<br>
Layout Design: Designing the layout of the application, including the positioning of elements and the use of whitespace.<br>
 
                </p><br>
                <a href="#">Learn more</a>
            </div>
            <div>
                <i class="fab fa-app-store"></i><br>
                <h2>App Design</h2><br>
                <p>
                     iOS App Design: Designing intuitive and user-friendly interfaces for iOS apps.<br>
                     Android App Design: Designing intuitive and user-friendly interfaces for Android apps.<br>
                     Cross-Platform App Design: Designing apps that work seamlessly across multiple platforms, including iOS, Android, and Windows.<br>
                     Mobile App Prototyping: Creating interactive prototypes to test and refine the app's design and functionality.<br>
                </p><br>
                <a href="#">Learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-server"></i><br>
                <h2>Front-end Development</h2><br>
                <p>
                     HTML/CSS Development: Writing clean, semantic HTML and CSS code to bring the design to life.<br>
                     JavaScript Development: Adding interactivity to the website using JavaScript libraries and frameworks.<br>
                     Responsive Development: Ensuring the website is optimized for various devices and screen sizes.<br>
                     Accessibility Development: Ensuring the website meets accessibility standards and is usable by everyone.<br>
                </p><br>
                <a href="#">Learn more</a>
            </div>

        </div>
    </div>
 </div>
 <!-- -------portfolio---- -->
  <div id="portfolio">
    <div class="container">
        
        <h1 class="sub-title">MY WORK</h1><br>  
        <div class="work-list">
            <div class="work">
                <img src="work-1.png">
                <div class="layer">
                    <h3>Social Media Application</h3>
                    <p>The app connects you to the talented people around the world.
                        Download it from play store.
                    </p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="work-2.png">
                <div class="layer">
                    <h3>Website Design</h3>
                    <p>This website is used to generate text with the help of AI.
                        Login to this website using google chrome.
                    </p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="work-3.png">
                <div class="layer">
                    <h3>Music Application</h3>
                    <p>This application contains music from world wide.
                        Download it from play store.
                    </p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="work-5.png">
                <div class="layer">
                    <h3>Stock Market Application</h3>
                    <p>The application is used to invest in stock market.
                        Download it from play store.
                    </p>
                    <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            

            </div>
            
        </div>
        <a href="#" class="btn">See more</a>

    </div>
  </div>
  <!-- -----contact------ -->
   <div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-solid fa-paper-plane"></i>
                    rifanapa2001@gmail.com
                </p>
                <p><i class="fa-solid fa-phone"></i>8073927783</p>
                <div class="social-icons">
                    <a href="https://facebook.com/"><i class="fa-brands fa-facebook"></i></a>
                    <a href=""><i class="fa-brands fa-x-twitter"></i></a>
                    <a href=""><i class="fa-brands fa-instagram"></i></a>
                    <a href=""><i class="fa-brands fa-linkedin"></i></a>
                </div>
                <a href="my-cv.pdf" download class="btn btn2">Download CV</a>
            </div>
           
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="email" name="Email" placeholder="Your Email " required>
                    <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
       
    </div>
    <div class="copyright">
        <p>Copyright @ Riff.Built with ..<i class="fa-solid fa-palette"></i> passion and creativity.</p>
    </div>
   </div>
 <script>

var tablinks = document.getElementsByClassName("tab-links");
var tabcontents = document.getElementsByClassName("tab-contents");
function opentab(tabname){
    for(tablink of tablinks){
        tablink.classList.remove("active-link");
    }
    for(tabcontent of tabcontents){
        tabcontent.classList.remove("active-tab");
    }
    event.currentTarget.classList.add("active-link");
    document.getElementById(tabname).classList.add("active-tab");
}
 </script>   

 <script>
    var sidemenu = document.getElementById("sidemenu");
    function openmenu(){
        sidemenu.style.right = "0";
    }
    function closemenu(){
        sidemenu.style.right = "-200px";
    }
 </script>
 <script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbzh57BdXBOy7PwdeqGD8EJKfTU8wov5RKDVc3Tsz7I91npdZtS90Fzsg6DY5w-UeYA/exec'
    const form = document.forms['submit-to-google-sheet']
    const msg = document.getElementById("msg")
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
            msg.innerHTML = "Message sent successfully"
            setTimeout(function(){
                msg.innerHTML = ""
            },5000)
            form.reset()
        })
    
        .catch(error => console.error('Error!', error.message))
    })
  </script>
</body>
</html>



*{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;

}
html{
    scroll-behavior: smooth;
}
body{
    background: #080808 ;

color: #fff;
}
#header{
    width: 100;
    height: 100vh;
    background-image: url(background.png);
    background-size: cover;
    background-position: right;
}
.container{
    padding: 10px 10%;

}

nav{
    display: flex;
    align-items: right;
    justify-content: space-between;
    flex-wrap: wrap;
}

.logo-6{
    width: 60px;
    


}

nav ul li{
    display: inline-block;
    list-style: none;
    margin:10px 10px;
}
nav ul li a{
    color: #fff;
    text-decoration: none;
    font-size: 18px;
    position: relative;
  
}
nav ul li a::after{
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 10px;
    bottom: -6px;
    transition: 0.5s;
}
nav ul li a:hover::after{
    width: 50%;
}
.header-text{
   margin-top: 1px;
    font-size: 17px;
   font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}



.header-text h2{
    font-size: 50px;
   margin-top: 1px;
    font-weight: 300;
  font-family: Georgia, 'Times New Roman', Times, serif;
    
    
}
.header-text h2 span{
    color:hsla(0, 58%, 44%, 0.887);
    font-family: Georgia, 'Times New Roman', Times, serif;
}
/* ---------about------- */

#about{
    padding: 80px 0;
    color: #ababab;
}
.row{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;

}
.about-col-1{
    flex-basis: 60%;

}
.about-col-1 img{
    width: 100%;
    border-radius: 15px;
    
}
.about-col-2{
    flex-basis: 35%;
}
.sub-title{
    font-size: 60px;
    font-weight: 600;
    color: #fff;
}
.tab-titles{
    display: flex;
    margin: 20px 0 40px;
}
.tab-links{
    margin-right: 50px;
    font-size: 18px;
    font-weight: 500;
    cursor: pointer;
    position: relative;
}
.tab-links::after{
    content: '';
    width: 0;
    height: 3px;
    background: #ff004f;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;
}
.tab-links.active-link::after{
    width: 50%;
}
.tab-contents ul li{
    list-style: none;
    margin: 10px 0;

}
.tab-contents ul li span{
    color: #b54769;
    font-size: 14px;
}
.tab-contents{
    display: none;
}
.tab-contents.active-tab{
    display: block;
}
/* -----------services------ */
#services{
    padding: 30px 0;

}
.services-list{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.services-list div{
    background: #262626;
    padding: 40px;
    font-size: 13px;
    font-weight: 300;
    border-radius: 10px;
    position: relative;
    transition: background 0.5s, transform 0.5s;
}
.services-list div i{
    font-size: 50px;
    margin-bottom: 30px;
}
.services-list div h2{
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;

}
.services-list div a{
    text-decoration: none;
    color: #fff;
    font-size: 12px;
    margin-top: 20px;
    display: inline-block;
}
.services-list div:hover{
    background: #ff004f;
    transform: translateY(-10px);
}
/* ----portfolio--- */
#portfolio{
    padding: 50px 0;

}
.work-list{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.work{
    border-radius: 10px;
    position: relative;
    overflow: hidden;
}
.work img{
    width: 100%;
    border-radius: 10px;
    display: block;
    transition: transform 0.5s;
}
.layer{
    width: 100%;
    height: 0%;
    background: linear-gradient(rgba(0,0,0,0.6), #ff004f);
    border-radius: 10px;
    position: absolute;
    left: 0;
    bottom: 0;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 40px;
    text-align: center;
    font-size: 14px;
    transition: height 0.5s;

}
.layer h3{
    font-weight: 500;
    margin-bottom: 20px;

}
.layer a{
    margin-top: 20px;
    color: #ff004f;
    text-decoration: none;
    font-size: 18px;
    line-height: 60px;
    background: #fff;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    text-align: center;
}
.work:hover img{
    transform: scale(1.1);
}
.work:hover .layer{
    height: 100%;
}
.btn{
    display: block;
    margin: 50px auto;
    width: fit-content;
    border: 1px solid #ff004f;
    padding: 14px 50px;
    border-radius: 6px;
    text-decoration: none;
    color: #fff;
    transition: background 0.5s;
}
.btn:hover{
    background: #ff004f;

}
/* --------contact------ */
.contact-left{
    flex-basis: 35%;
}
    .contact-right{
        flex-basis: 60%;

}
.contact-left p{
    margin-top: 30px;
}
.contact-left p i{
    color: #ff004f;
    margin-right: 15px;
    font-size: 25px;
}
.social-icons{
    margin-top: 30px;

}
.social-icons a{
    text-decoration: none;
    font-size: 30px;
    margin-right: 15px;
    color: #ababab;
    display: inline-block;
    transition: transform 0.5s;
}
.social-icons a:hover{
    color: #ff004f;
    transform: translateY(-5px);
}
.btn.btn2{
    display: inline-flex;
    background: #ff004f;
}
.contact-right form{
    width: 100%;

}
form input, form textarea{
    width: 100%;
    border: 0;
    outline: none;
    background: #262626;
    padding: 15px;
    margin: 15px 0;
    color: #fff;
    font-size: 18px;
    border-radius: 6px;

}
form .btn2{
    padding: 14px 60px;
    font-size: 18px;
    margin-top: 20px;
    cursor: pointer;

}
.copyright{
    width: 100%;
    text-align: center;
    padding: 25px 0;
    background: #262626;
    font-weight: 300;
    margin-top: 20px;

}
.copyright i{
    color: gold;

}
/* -------css for small screen---- */

nav .fa-solid{
    display: none;
}
@media only screen and (max-width: 600px){
    #header{
        background-image: url(background-mobile.png);
        background-position: center;
       
    }
    .header-text{
        margin-top: 50%;
        font-size: 16p;
    }
    .header-text h2{
        font-size: 30px;
    }
    nav .fa-solid{
        display: block;
        
        font-size: 25px;
    }
    nav ul{
        background: #ff004f;
        position: fixed;
        top: 0;
        right: -200px;
        width: 200px;
        height: 100vh;
        padding-top: 50px;
        z-index: 2;
        transition: right 0.5s;
    }
    nav ul li{
        display: block;
        margin: 25px;

    }
    nav ul .fa-solid{
        position: absolute;
        top: 25px;
        left: 25px;
        cursor: pointer;
    }
    .sub-title{
        font-size: 40px;

    }
    .about-col-1, .about-col-2{
        flex-basis: 100%;
    }
    .about-col-1{
        margin-bottom: 30px;

    }
    .about-col-2{
        font-size: 14px;

    }
    .tab-links{
        font-size: 16px;
        margin-right: 20px;
    }
    .contact-left, .contact-right{
        flex-basis: 100%;
    }
    .copyright{
        font-size: 14px;
    }

    }
#msg{
    color: #61b752;
    margin-top: -40px;
    display: block;
}
