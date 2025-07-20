<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Autobiography</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: radial-gradient(circle, #b5d9f7, #a1cbe5);
            margin: 0;
            padding: 0;
            color: #333333;
        }
        header {
            background-color: #9fd0f2;
            color: white;
            text-align: center;
            padding: 20px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #6eb1e0;
            box-shadow: 0px 4px 8px rgba(110, 177, 224, 0.3);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            font-weight: bold;
            transition: 0.3s ease;
        }
        nav a:hover {
            background: #aee3ff;
            border-radius: 5px;
            color: #1f4e78;
        }
        section {
            display: none;
            padding: 40px;
            margin: 20px;
            background: #d9effb;
            border-radius: 10px;
            font-size: 18px;
            box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
        }
        section.active {
            display: block;
        }
        #profile img {
            width: 250px;
            border-radius: 10%;
            margin: 0 auto;
            display: block;
            border: 4px solid #a3cce9;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2); 
        }
        h2 {
            color: #1c4d7b;
            font-size: 30px;
        }
        h1 {
            color: #2c3e50;
            text-align: center; 
            font-size: 40px; 
        }
        h3 {
            color: #2c3e50;
            font-size: 30px;
        }
        h4 {
            color: #2c3e50;
            font-size: 50px;
            text-align: center;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #cce9fb;
            color: #4a90a4;
            margin-top: 20px;
        }
        a {
            color: #3388bb;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>My Autobiography</h1>
</header>

<nav>
    <a href="#" onclick="showSection('profile')">Profile</a>
    <a href="#" onclick="showSection('about')">About Me</a>
    <a href="#" onclick="showSection('Education')">Educational Background</a>
    <a href="#" onclick="showSection('contact')">Contact</a>
</nav>

<main>
    <section id="profile" class="active">
        <h4>My Profile</h4>
        <div style="display: flex; align-items: center; justify-content: center; flex-direction: column;">
            <img src="1.jpg" alt="Your Profile Picture">
            <p>Hello! I am <strong>Winnie Rose P. Montebon</strong></p>
        </div>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am <strong>Winnie Rose P. Montebon</strong>, 19 years of age, currently living at Marigondon, Lapu-Lapu City. I'm an extroverted person who loves traveling with family and friends. I enjoy being around people who share the same sense of humor and those who respect my feelings. So far, 2024 has been the best year of my life, as I’ve had the opportunity to travel to many places and meet genuinely kind people along the way.</p>
        <p>Through these experiences, I also learned how to earn money by working part-time at a restaurant. Additionally, I’ve started a sideline where I help students with their schoolwork, supporting those who need assistance.</p>
        <p>My motto in life: <strong>"Keep dreaming, and never give up"</strong>. I believe in staying resilient and persevering, no matter the challenges life presents.</p> 

        <h2>Skills</h2>
        <p>I have skills in <strong>Active listening</strong>, <strong>Solving Math Problems</strong>,
            <strong>Good Communication</strong>, <strong>Leadership</strong>, and <strong>Flexibility</strong>.</p>

        <h2>Hobbies</h2>
        <p>In my free time, I <strong>play games like Valorant and Mobile Legends</strong>, <strong>watch K-drama series</strong>, <strong>love dancing</strong>, and <strong>read novels</strong>.</p>

        <h2>Favorite Food</h2>
        <ol>
            <li>Lugaw (Rice Porridge)</li>
            <li>Mango</li>
            <li>Bubble Tea</li>
            <li>Mango Float</li>
            <li>Salad</li>
            <li>Seafoods</li>
            <li>Gummies</li>
            <li>Cake</li>
            <li>Fried Chicken</li>
            <li>Fries</li>
            <li>Sisig</li>
        </ol>
    </section>

    <section id="Education">
        <h1>Educational Background</h1> 
        <h2>Elementary</h2>
        <p>I graduated at <strong>Marigondon Elementary School</strong>, year 2017.</p>
        <h2>High School</h2>
        <p>I completed my junior high school at <strong>Marigondon National High School</strong>, year 2020.</p>
        <p>I graduated from <strong>Asian Learning Center</strong> as a STEM student, year 2023.</p>
        <h2>College</h2>
        <p>Currently studying at <strong>Lapu-Lapu City College</strong> as a BindTech-CompTech student.</p>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>☎ Number: 09284313980</p>
        <p>📧 Email: <a href="mailto:winniemontebon18@gmail">winnie</a></p>
        <p>📘 Facebook: <a href="https://www.facebook.com/m.winnieee" target="_blank">Winnie</a></p>
        <p>📷 Instagram: <a href="https://www.instagram.com/m.winniee/?next=%2F" target="_blank">@m.winnie</a></p>
    </section>
</main>

<script>
    function showSection(id) {
        document.querySelectorAll('section').forEach(section => {
            section.classList.remove('active');
        });
        document.getElementById(id).classList.add('active');
    }
</script>

</body>
</html>
