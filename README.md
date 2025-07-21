<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> My Protfolio</title>
    <link rel="stylesheet"href="style2.css">
</head>
<body>
     
    <div class="main">
        <div class="navbar">
            
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">SKILLS</a></li>
                <li><a href="#">MY WORK</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>

        </div>

        <div class="info">
            <h3>Hi, I'm <span>Kiran</span>.</h3>
            <h1><span>B</span>TECH <span>S</span>TUDENT</h1>
            <h3> BTech student of Millennium institute of science and technology college BHOPAL,MP.</h3>
                <a href="#">Hire Me <Meta:refresh></Meta:refresh></a>
        </div>
         

        <div class="image">
             <img src="image/IMG_20250702_110506.jpg" alt="My Image" class="image-class">

            
           
        </div>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
        <div class="social-icons">
    <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook-f"></i></a>
    <a href="https://twitter.com" target="_blank"><i class="fab fa-twitter"></i></a>
    <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
</div>

    </div>
    
</body>*{
    margin: 0;
    padding: 0;
}

.main{
    width: 100%;
    background-color: darkgray;
    padding: 20px;
    min-height: 100vh; /* full screen height */
}
.navbar ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 30px;
}

.navbar li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    font-size: 18px;
    margin-top: -3%;
}

ul li a:hover{
    color:red
}
.info{
    margin-left:7%;
    margin-top: 10%;
}

.info h1{
    font-size: 55px;
    color:rgb(243, 15, 167);
}
.info h3{
    font-size:18px;
    letter-spacing: 1px;
    line-height: 24px;
}

.info span{
    color:#e70e0e
}

.info a{
    text-decoration: none;
    color:#fff;
    background:blue;
    margin: 26px 0;
    padding: 10px 18px;
    border-radius: 10px;
    display: inline-block;
}
 .info a:hover{
    background: rgb(59,174,209);
 }

 .image-class {
    width: 400px;         /* Adjust size as needed */
    height: 400px;        /* Keep it square */
    border-radius: 100%;   /* Makes it circular */
    object-fit: cover;    /* Makes sure it fills the circle */
    border: 3px solid white;  /* Optional: border around the image */
    
}

.image-class {
    position: absolute;         
    height: 400px;        
    right: -5%;   
    transform: translate(-55%);    
    bottom: 20%; 
    transition: left 2s ease; 
    
}

.image:hover .class{
    left:55%;
    
}

.social-icons {
    position: fixed;
    bottom: 300px;
    left: 100px;
    display: flex;
    flex-direction: row;
    gap: 15px;
    z-index: 999;
    
}

.social-icons a {
    text-decoration: none;
    color: white; /* Change color as needed */
    font-size: 24px;
    margin: 0 15px;
    transition: color 0.3s;
}

.social-icons a:hover {
    color: #0077ff; /* Blue hover effect */
}
</html>
