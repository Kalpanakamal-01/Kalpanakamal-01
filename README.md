<html>

<head>

    <title>Portfolio</title>

    <style>

        body {

            font-family: Arial, sans-serif;

            margin: 0;

            padding: 0;

            background-color: #84a6e9;

        }



        header {

            background-color: #941919;

            color: #fff;

            text-align: center;

            padding: 2rem 0;

            position: relative; /* Add this */

        }



        .header-content h1 {

            font-size: 2.5rem;

        }



        /* Add styles for the round profile picture */

        .profile-picture {

            width: 50px; /* Adjust the size as needed */

            height: 50px;

            border-radius: 75%; /* Create a circular shape */

            object-fit: cover; /* To ensure the image fills the circular area */

            position: absolute; /* Add this */

            top: 75px; /* Adjust top position as needed */

            left: 75px; /* Adjust left position as needed */

        }



        nav {

            background-color: #333;

            color: #fff;

            text-align: center;

        }



        nav ul {

            list-style-type: none;

            padding: 0;

        }



        nav ul li {

            display: inline;

            margin: 0 20px;

        }



        nav ul li a {

            text-decoration: none;

            color: #fff;

        }



        .section-content {

            background-color: #fff;

            padding: 2rem;

            margin: 1rem;

            border-radius: 20px;

            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

            text-align: justify;

        }



        .download-button {

            background-color: #333;

            color: #fff;

            padding: 0.5rem 1rem;

            text-decoration: none;

            border-radius: 20px;

            display: inline-block;

            margin-top: 10px;

            align-self: center;

        }



        .download-button:hover {

            background-color: #555;

        }



        footer {

            text-align: center;

            padding: 1rem 0;

            background-color: #333;

            color: #fff;

        }



        ul {

            list-style-type: disc;

            padding-left: 20px;

        }

    </style>

</head>

<body>

    <header>

        <div class="header-content">

            <!-- Add your profile picture here -->

            <img src="Passport.jpg" alt="Your Profile Picture" class="profile-picture">

            <h1>Kalpana K</h1>

            <p>Bsc Computer Science</p>

        </div>

    </header>



    <nav>

        <ul>

            <li><a href="#about">About</a></li>

            <li><a href="#education">Education</a></li>

            <li><a href="#skills">Skills</a></li>

            <li><a href="#projects">Projects</a></li>

            <li><a href="#resume">Resume</a></li>

           

        </ul>

    </nav>



    <section id="about">

        <div class="section-content">

            <h2>About Me</h2>

            <p>I'm a student of <b>Bsc Computer Science</b> am a second-year BSc Computer Science student with a strong passion for technology, programming, and problem-solving. I have experience in coding with languages Python, Java, C++ and enjoy exploring areas such as software development, data structures, and algorithms. I am eager to apply my knowledge through projects, internships, and collaborative learning experiences. I am continuously improving my skills to build innovative solutions and grow as a tech professional.</p>



        </div>

    </section>



    <section id="education">

        <div class="section-content">

            <h2>Education</h2>

            <p>University of Madras</p>

            

            

        </div>

    </section>



    <section id="skills">

        <div class="section-content">

            <h2>Skills</h2>

            <ul></ul>

                <li>Data structures</li>

                <li>Python</li>

                <li>Css</li>

                <li>Html</li>

                <li>java</li>

                <li>c++</li>

            </ul>

        </div>

    </section>



    <section id="projects">

        <div class="section-content">

            <h2>Projects</h2>

            <ul>

                <li><a href="#">Login form</a></li>

                <li><a href="#">Registeration form</a></li>

                <li><a href="#">Survey form</a></li>

                <li><a href="#">Student grade form</a></a></li> 

                <!-- Add more project links here -->

            </ul>

        </div>

    </section>



    <section id="resume">

    

        <div class="section-content">

            <center>

            <h2>Resume</h2>

            <a href="Resume.pdf" target="_blank" class="download-button">Download CV</a>

        </center>

        </div>

        

    </section>



    <footer>

        <p>&copy; 2025 Kalpana K</p>

    </footer>



    <script>

        // Smooth scrolling to section when clicking on navigation links

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {

            anchor.addEventListener('click', function(e) {

                e.preventDefault();



                const targetId = this.getAttribute('href').substring(1);

                const targetElement = document.getElementById(targetId);



                if (targetElement) {

                    window.scrollTo({

                        top: targetElement.offsetTop,

                        behavior: 'smooth'

                    });

                }

            });

        });

    </script>

</body>

</html>
