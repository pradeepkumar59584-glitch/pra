<html>
    <head>
        <title>home design</title>
        <link rel="stylesheet" href="S.CSS">
        <style>
            *{
    margin:0;
    padding:0;
    font-family: sans-serif;
}
.banner{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(53, 14, 14, 0.75),rgba(0,0,0,0.75)),url(BACKGROUND.webp);
    background-size: cover;
    background-position: center;
}
.navbar{
    width: 85%;
    margin: auto;
    padding: 35px 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.logo{
    width: 120px;
    cursor: pointer;
    border-radius: 50%;

}
.navbar ul li{
    list-style: none;
    display: inline-block;
    margin: 0 20px;
    position: relative;
}
.navbar ul li a{
    text-decoration: none;
    color: #fff;
    text-transform: uppercase;
}
.navbar ul li::after{
    content:'';
    height: 3px;
    width: 0;
    background: #009688;
    position: absolute;
    left: 0;
    bottom: -10px;
    transition: 0.5s;
}
.navbar ul li:hover::after{
    width: 100%;
}
.content{
    width: 100%;
    position: absolute;
    top:50%;transform: translateY(-50%);
    text-align: center;
    color: #fff;
}
.content h1{
    font-size: 70px;
    margin-top: 80px;
}
button{
    width: 200px;
    padding: 15px 0;
    text-align: center;
    margin:20px 10px;
    border-radius: 25px;
    font-weight: bold;
    border: 2px solid #009688;
    background: transparent;
    color:#fff;
    cursor: pointer;
    position: relative;
    overflow: hidden;
}
span{
    background: #009688;
    height: 100%;
    width: 0;
    border-radius: 25px;
    position: absolute;
    left: 0;
    bottom: 0;
    z-index: -1;
    transition: 0.5s;
}
button:hover span{
    width: 100%;

}
button:hover{
    border:none;
}
/* .card{
    width: 200px;
    height: 230px;
    display: inline-block;
    border-radius: 10px;
    padding: 12px;
    box-sizing: border-box;
    cursor: pointer;
    margin: 10px 15px;
    background-image: url(https://www.99homeplans.com/wp-content/uploads/2018/03/bangalore-home-design-60-two-story-small-house-design-new-plans.jpg);
    background-position: center;
    background-size: cover;
} */
.col{
    flex-basis: 50%;
    font-size: 50px;

}
        </style>
    </head>
    <body>
        <div class="banner">
            <div class="navbar">
                <img src="LOGO.webp" class="logo">
                <ul>
                    <li><a href="ABOUT.HTML">ABOUT US</a></li>
                  </ul>
            </div>
 <div class="content">
                <h1>DGPS APPOINTMENT BOOKINGS</h1>
            <div>
               <a href="https://calendar.google.com/calendar/appointments/schedules/AcZssZ3yh7INDRyZdiLLZwr31Biu7EEM63YOZQyW3vOEO6n5b3EkmSXtqVQU8FXtPZkZ05GLdcb6p2JX"> <button type="button"><span></span>BOOKINGS</button></a>
</div>
        </div>
        </div>
 </body>
</html>
