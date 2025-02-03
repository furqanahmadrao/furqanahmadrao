<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Furqan's GitHub</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #181818;
            color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        h1, h2 {
            color: #58a6ff;
        }
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
        }
        .bio {
            margin-bottom: 20px;
        }
        .bio p {
            font-size: 18px;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .skill {
            background-color: #2f2f2f;
            padding: 10px;
            border-radius: 5px;
            font-size: 16px;
        }
        .projects {
            margin-top: 40px;
        }
        .progress-bar-container {
            width: 100%;
            background-color: #444;
            border-radius: 5px;
            margin-top: 20px;
        }
        .progress-bar {
            height: 25px;
            background-color: #58a6ff;
            border-radius: 5px;
        }
        .progress-text {
            font-size: 16px;
            margin-top: 10px;
            color: #ccc;
        }

        /* Image Hover Effect */
        .image-container {
            position: relative;
            display: inline-block;
            cursor: pointer;
        }
        .image-container img {
            border-radius: 10px;
            transition: transform 0.3s ease-in-out;
        }
        .image-container:hover img {
            transform: scale(1.1);
        }
        .image-container::after {
            content: "Click to View!";
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 18px;
            color: white;
            font-weight: bold;
            display: none;
        }
        .image-container:hover::after {
            display: block;
        }

        /* Card Design for Projects */
        .project-card {
            background-color: #2f2f2f;
            padding: 20px;
            border-radius: 8px;
            margin-top: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }
        .project-card:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hi, I'm Furqan 👋</h1>
        <div class="bio">
            <p>I'm passionate about tech, cloud, and AI! Currently, I'm learning **C++** and exploring **Azure**. I'm working on improving my skills in **Cloud Engineering**, **AI**, and **Machine Learning**. Welcome to my GitHub profile!</p>
        </div>

        <h2>🌱 Currently Learning</h2>
        <p>I’m diving deep into the world of **Azure** and **Cloud Computing**. Here’s my learning progress so far:</p>
        
        <div class="progress-bar-container">
            <div class="progress-bar" style="width: 70%"></div>
        </div>
        <p class="progress-text">Azure Cloud: 70% completed</p>

        <h2>💼 Skills</h2>
        <div class="skills">
            <div class="skill">C++</div>
            <div class="skill">Azure</div>
            <div class="skill">AI & ML</div>
            <div class="skill">Python</div>
            <div class="skill">Data Science</div>
        </div>

        <h2>📂 My Projects</h2>
        <div class="projects">
            <p>Here are some of the projects I’ve been working on:</p>

            <!-- Project 1 Card -->
            <div class="project-card">
                <h3><a href="https://github.com/your-username/project1" target="_blank">Project 1 - Cloud Automation</a></h3>
                <p>This project is about automating cloud resource provisioning using Azure. The code automates VM creation and storage account management.</p>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200" alt="Cloud Automation Project">
                </div>
            </div>

            <!-- Project 2 Card -->
            <div class="project-card">
                <h3><a href="https://github.com/your-username/project2" target="_blank">Project 2 - C++ Machine Learning</a></h3>
                <p>This project implements basic machine learning algorithms using C++. It demonstrates linear regression and classification tasks.</p>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200" alt="C++ ML Project">
                </div>
            </div>

            <!-- Project 3 Card -->
            <div class="project-card">
                <h3><a href="https://github.com/your-username/project3" target="_blank">Project 3 - Data Science Research</a></h3>
                <p>This research project involves analyzing large datasets for trends and insights using Python and machine learning techniques.</p>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200" alt="Data Science Project">
                </div>
            </div>
        </div>

        <h2>📫 How to Reach Me</h2>
        <p>Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/your-profile). I’d love to collaborate on projects!</p>
    </div>
</body>
</html>
