# Project Responsive Web Design using Bootstrap
## Date:19.11.24

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
HTML code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Dribbble</div>
            <ul class="menu">
                <li><a href="#">Explore</a></li>
                <li><a href="#">Sign In</a></li>
                <li><a href="#" class="btn">Sign Up</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Discover the world's best designers and creatives.</h1>
        <p>Showcase your work and connect with professionals worldwide.</p>
        <button>Sign Up</button>
    </section>

    <section class="works">
        <h2>Featured Work</h2>
        <div class="grid">
            <div class="card">
                <img src="image_processing20210430-26016-12xyd9w.jpg" alt="Work 1">
                <p>App Developer</p>
            </div>
            <div class="card">
                <img src="logo-search-grid-2x.png" alt="Work 2">
                <p>Logo Designer</p>
            </div>
            <div class="card">
                <img src="modern-website-design-examples.jpg" alt="Work 3">
                <p>Web Page Designer</p>
            </div>
            <div class="card">
                <img src="download.jpeg" alt="Work 4">
                <p>Graphic Designer</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2024 Dribbble Clone. All Rights Reserved.</p>
        <div class="socials">
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
            <a href="#">Instagram</a>
        </div>
    </footer>
</body>
</html>
```
CSS code:
```body {
    font-family: Arial, sans-serif;
    font-size: 20px;
    margin: 0;
    padding: 0;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #f5f5f5;
}

.menu {
    display: flex;
    list-style: none;
    gap: 20px;
}

.menu li a {
    text-decoration: none;
    color: #333;
}

.menu .btn {
    padding: 5px 10px;
    background-color: #6a11cb;
    color: white;
    border: none;
    border-radius: 5px;
    text-decoration: none;
}

.hero {
    text-align: center;
    padding: 50px;
    background: linear-gradient(to right, #6a11cb, #2575fc);
    color: white;
}

.hero button {
    padding: 10px 20px;
    background-color: white;
    color: #6a11cb;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.hero button:hover {
    background-color: #eaeaea;
}

.works {
    padding: 40px;
    text-align: center;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.card {
    background: #f5f5f5;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.card img {
    max-width: 100%;
    border-radius: 8px;
}

.card p {
    margin-top: 10px;
    font-size: 30px;
    font-style: bold;
    color: #333;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 20px;
}

footer .socials a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

footer .socials a:hover {
    text-decoration: underline;
}
```


## OUTPUT:
![Screenshot 2024-11-19 153558](https://github.com/user-attachments/assets/9f9f25a0-8d51-4ed0-aff8-bbc2b60331e9)
![Screenshot 2024-11-19 153616](https://github.com/user-attachments/assets/17601758-c5b8-4b64-a0be-092d7e84b054)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
