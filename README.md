<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <style>
        body {background-color: rgb(50, 2, 2);color: #fff;line-height: 1.6;padding: 0;display: 
            flex;flex-direction: column;align-items: center;justify-content: center;}

        h1 {
            color: aqua;
            font-size: 3rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-top: 20px;
        }

        

        .section {
            width: 100%;
            max-width: 1200px;
            margin: 20px;
            padding: 30px;
            background-color: white;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
            transition: all 0.3s ease;
        }

        .section:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
        }

        .section h2 {
            font-size: 2rem;
            color: #333;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
        }

        .section p,
        .section ul {
            font-size: 1.1rem;
            color: #555;
            line-height: 1.8;
        }

        ul {
            list-style-type: none;
            padding-left: 0;
        }

        ul li {
            padding: 12px;
            margin: 8px 0;
            background-color: #f0f8ff;
            border-left: 5px solid #56b4e9;
            border-radius: 8px;
            transition: all 0.3s ease;
        }

        ul li:hover {
            background-color: #e3f2fd;
            transform: translateX(5px);
            cursor: pointer;
        }

        .contact ul {
            list-style-type: none;
        }

        .contact li {
            font-size: 1.1rem;
            margin-bottom: 15px;
            color: #333;
        }
        .contact li a {
            text-decoration: none;
            color: #56b4e9;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .contact li a:hover {
            color: #ff6f61;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: #fff;
            width: 100%;
            margin-top: 40px;
            border-radius: 10px;
        }

        footer p {
            font-size: 1.1rem;
        }

        footer a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
            font-size: 1.2rem;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<!--27-Dec-2024 AIDS(A) Created by Ravikumar Parkhe-->
<body>
    
        <h1>Welcome To My Portfolio</h1>
    
    <div class="section">
        <h2>About Me</h2>
        <p>Hello I'm <b>Ravikumar Gajanan Parkhe</b>, a First-year Artificial Intelligence and Data Science Engineering student at Zeal College of Engineering and Research.</p>
    </div>
    <div class="section">
        <h2>My Skills</h2>
        <ul>
            <li>Programming: Python, C , HTML</li>
            <li>Problem Solving</li>
            <li>Mathematics</li>
            <li>Public Speaking and Teamwork</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>My Education</h2>
        <ul>
            <li>I have passed my 10th form Baliram Patil Highschool,Aurangabad</li>
            <li>I have passed my 12th from Govt. College of Arts and Science,Aurangabad</li>
            <li>I am currently studying at Zeal College of Engineering and Research.</li>
        </ul>
    </div>
    <div class="section">
        <h2>My Hobbies</h2>
        <ul>
            <li>I love watching and playing sports, especially Shooting, Cricket.</li>
            <li>I enjoy listening music, which helps me relax and de-stress.</li>
        </ul>
    </div>
    <div class="section contact">
        <h2>Contact</h2>
        <ul>
            <li>Phone no: ******5616</li>
            <li>Email: <a href="mailto:abc@gmail.com">Zeal@gmail.com</a></li>
        </ul>
    </div>
    <footer>
        <p>Created by Ravikumar Gajanan Parkhe - AIDS Engineering Student</p>
    </footer>
</body>
</html>
