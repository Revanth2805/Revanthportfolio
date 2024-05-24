<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Revanth Sri Nagulamalyala</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            background-color: #333;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            text-align: center;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            display: inline-block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav ul li a:hover {
            background-color: #111;
        }
        section {
            padding: 2em;
        }
        #about, #education, #experience, #projects, #skills, #certifications, #contact {
            border-bottom: 1px solid #ddd;
        }
        .education, .experience, .project {
            margin: 1em 0;
            padding: 1em;
            border: 1px solid #ddd;
        }
        .education h3, .experience h3, .project h3 {
            margin: 0 0 0.5em 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Revanth Sri Nagulamalyala</h1>
        <p>Software Engineer | Data Scientist | Salesforce Developer</p>
        <p>Binghamton, New York, 13905 | <a href="mailto:nrevanth@binghamton.edu" style="color: white;">nrevanth@binghamton.edu</a> | +1 (607)-821-5927</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#certifications">Certifications</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a dedicated and passionate web developer, software engineer, and data scientist with a solid background in 
            artificial intelligence and machine learning. Currently pursuing my Master's in Computer Science with a focus on 
            Artificial Intelligence at Binghamton University, I have a strong foundation in various programming languages and 
            frameworks. With hands-on experience in both academic projects and professional roles, I excel in building efficient 
            and scalable solutions.
        </p>
    </section>
    <section id="education">
        <h2>Education</h2>
        <div class="education">
            <h3>Binghamton University - State University of New York</h3>
            <p>Masters in Computer Science in Artificial Intelligence (Aug 2023 - Dec 2024)</p>
            <p>Grade: Pursuing</p>
            <p>Courses: Machine Learning, Database Systems, Natural Language Processing, Data Mining, Neural Networks, Large Language Models, Design Analysis and Algorithms.</p>
        </div>
        <div class="education">
            <h3>Gokaraju Ranga Raju Institute of Engineering and Technology</h3>
            <p>Bachelor of Technology in Electronics Communication and Engineering (Aug 2016 - Sep 2020)</p>
            <p>Grade: 3.4/4.0</p>
            <p>Courses: Data Structures and Algorithms, Linear Algebra and Single Variable Calculus, Transform Calculus and Fourier Series, Numerical Methods, Probability and Stochastic Process, Python Programming.</p>
        </div>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Programming Languages: Python, R, C/C++, MATLAB, Java, HTML, CSS, JavaScript, SQL</li>
            <li>Software and Tools: Visual Studio, Tableau, SQL Server, JIRA, Google Colab, Google Analytics, AWS SageMaker, AWS EC2</li>
            <li>Cloud Platforms: AWS, Salesforce, GCP, Azure</li>
            <li>Frameworks: PyTorch, Scikit Learn, TensorFlow, SpaCy, Numpy, Pandas</li>
            <li>Machine Learning: Classification, Regression, Time Series Analysis, Natural Language Processing, Neural Networks, Reinforcement Learning, Large Language Models</li>
        </ul>
    </section>
    <section id="experience">
        <h2>Experience</h2>
        <div class="experience">
            <h3>Salesforce Developer at WIPRO</h3>
            <p>(Nov 2020 – Dec 2022)</p>
            <ul>
                <li>Developed routing for cases to specific agents from different origins and sent surveys to consumers, improving customer query resolve efficiency by 25%.</li>
                <li>Created a chatbot for Advisor and customer connection, achieving 75% efficiency.</li>
                <li>Developed REST API to fetch data from external sources and create records in Salesforce, preventing data loss.</li>
                <li>Implemented CI/CD pipeline and developed multilingual surveys and omni-channel routing codes using Salesforce Flow Automations.</li>
            </ul>
        </div>
        <div class="experience">
            <h3>Data Scientist Intern at Tech-trunk Solutions</h3>
            <p>(May 2019 – Aug 2019)</p>
            <ul>
                <li>Managed and analyzed extensive datasets, successfully handling up to 200,000 records.</li>
                <li>Deployed machine learning models on AWS, improving system effectiveness with a 70% accuracy rate.</li>
                <li>Created a Flask interface to showcase visualized data and daily KPIs.</li>
            </ul>
        </div>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Parkinson’s Disease Severity Prediction</h3>
            <p>(Aug 2022)</p>
            <p>Developed an Android app using an RNN for real-time prediction of Parkinson’s Disease severity, processing 16 voice parameters from patient recordings. Achieved a 73% accuracy rate and utilized a vector database with SQL for efficient data management.</p>
        </div>
        <div class="project">
            <h3>Image Quality Testing</h3>
            <p>(May 2020)</p>
            <p>Developed a Random Forest classifier model with a Laplacian filter to evaluate image sharpness and assign a blurriness score. Launched a Streamlit application for analyzing technical aspects of images such as blur, brightness, and contrast, providing users with scores from 0 to 1.</p>
        </div>
    </section>
    <section id="certifications">
        <h2>Certifications</h2>
        <ul>
            <li>IBM Machine Learning Developer (Coursera)</li>
            <li>AWS Machine Learning Certified</li>
            <li>Statistics for Data Science (Stanford, EdX)</li>
            <li>SQL Certified (EdX)</li>
            <li>Generative AI for LLM, Sequence Models, Natural Language Processing on Vector Database</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:nrevanth@binghamton.edu">nrevanth@binghamton.edu</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/revanth-nagulamalyala-210483129/">Revanth Nagulamalyala</a></p>
    </section>
    <footer>
        <p>&copy; 2024 Revanth Sri Nagulamalyala. All rights reserved.</p>
    </footer>
</body>
</html>
