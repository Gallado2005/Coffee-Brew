<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coffee Brew</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
    * {

box-sizing: border-box;
}

body {
font-family: Arial, sans-serif;
margin: 0;
padding: 0;
background-color: black;
}

.container {
background-color: rgba(255, 255, 255, 0.9);
padding: 10px;
}

header {
width: 100%;
}

nav {
display: flex;
align-items: center;
justify-content: space-between;
background-color: #4b3621;
}

.logo {
height: 50px;
margin-right: 20px;
border-radius: 8px;
padding: 3px 3px 3px 3px;
}

.nav-links {
display: flex; 
flex-grow: 1; 
justify-content: flex-end;
}

.link {
color: white; 
text-decoration: none;
margin: 0 15px; 
}

.link:hover {
text-decoration: underline; 
}

.home-image, .about-image {
border-radius: 15px; 
width: 100%;
height: auto; 
}

.home-text {
position: absolute; /* Positioning the text absolutely */
top: 50%; /* Center vertically */
left: 50%; /* Center horizontally */
transform: translate(-50%, -50%); /* Adjust for centering */
text-align: center; /* Center text */
background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background */
padding: 20px; /* Padding around the text */
border-radius: 10px; /* Rounded corners */
color: white; /* Text color */
}

h2 {
text-align: center; 
}

footer {
text-align: center;
padding: 10px;
background-color: black; 
color: white;
}

p, h2 {
color: white;
}

@media (max-width: 768px) {
nav {
    flex-direction: column; 
    align-items: flex-start;
}

.link {
    margin: 10px 0;
}
}

</style>
<body>
    <header>
        <nav>
            <img src="logo1.jpg" alt="Logo" class="logo" />
            <a class="link" href="#home">Home</a>
            <a class="link" href="#about">About Us</a>
            <a class="link" href="#contact">Contact Us</a>
        </nav>
    </header>

    <main>
        <section id="home">
            <div class="home-image" style="position: relative; text-align: center; color: white;">
                <img src="bg.jpg" alt="Welcome to Our Shop" style="width: 97%; height: 700px; padding-top: 10px; border-radius: 8px;" />
                <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);">
                    <h2>Welcome to Our Shop</h2>
                    <p>Discover our wide range of products and services.</p>
                    <button style="border-radius: 8px; background-color: seagreen; width: 200px; height: 50px; border: none; color: white;">Explore Our Services</button>
                </div>
            </div>
        </section>
        
        <section id="about">
            <h2>About Us</h2>
            <div class="about-content" style="display: flex; align-items: center; color: white;">
                <img src="about.jpg" alt="About Us" class="about-image" style="width: 30%; height: auto; margin-right: 20px; padding-left: 15px;" />
                <div style="flex: 1;">
                    <p style="text-align: justify; font-size: 17px;">We pride ourselves on our commitment to quality and sustainability. We work closely with farmers who practice ethical and environmentally friendly methods, ensuring that our coffee not only tastes good but also supports the communities that grow it. Our beans are carefully selected and roasted to perfection, bringing out the unique characteristics of each origin.</p>
                </div>
            </div>
        </section>
        
        <section id="contact">
            <<h2 style="color: #4b3c2a;">Contact Us</h2>
            <div style="margin-top: 20px; padding: 10px; background-color: #000000; border: none black;">
                <p style="color: #333;">We’d love to hear from you! Whether you have questions, feedback, or just want to chat about coffee, feel free to reach out.</p>
                <ul style="list-style-type: none; padding: 0;">
                    <li style="color: #333; font-size: 20px;"><strong>Email:</strong> <a href="mailto:your-email@example.com">JamesGallado28@gmail.com</a></li>
                    <li style="color: #333; font-size: 20px;"><strong>Phone:</strong> 63+ 60-858-2630</li>
                    <li style="color: #333; font-size: 20px;"><strong>Address:</strong> 123 Coffee Street, Cebu City, 6000</li>
        </section>
    </main>
    
    <footer style="text-align: center; margin-top: 20px; padding: 10px; background-color: black;">
        <p>&copy; 2023 My Shop. All rights reserved.</p>
        <div>
            <a href="https://www.facebook.com/yourprofile">
                <img src="fb.jpg" alt="Facebook" style="width: 20px; height: 20px; margin: 0 5px;">
            </a>
            <a href="https://www.instagram.com/yourprofile">
                <img src="insta.jpg" alt="Instagram" style="width: 20px; height: 20px; margin: 0 5px;">
            </a>
            <a href="https://www.twitter.com/yourprofile">
                <img src="twitter.jpg" alt="Twitter" style="width: 20px; height: 20px; margin: 0 5px;">
            </a>
        </div>
    </footer>

</body>
</html>
