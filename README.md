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
