# Booking-Travel
fronted.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Travel Support</title>
    <link rel="stylesheet" href="style.css"/>
    <style>
       /* General Styles */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #333;
    line-height: 1.4;
    margin: 0;
    padding: 40px 0;
    background-color: #fff;
}

.container {
    max-width: 1100px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    gap: 50px;
    padding: 0 100px;
}

/* Header Styling */
.header-content {
    text-align: center;
    margin-bottom: 70px;
}

.subtitle {
    font-size: 15px;
    letter-spacing: 2px;
    color: #666;
    text-transform: uppercase;
}

.header-content h1 {
    font-size: 42px;
    margin: 20px 0;
    font-weight: 900;
}

/* List Items Styling */
.text-items {
    flex: 1;
}

.item {
    margin-bottom: 35px;
}

.number {
    display: inline-block;
    padding: 10px 15px;
    border-radius: 100px;
    color: white;
    font-weight: bold;
    font-size: 10px;
    margin-bottom: 10px;
}

.blue { background-color: #4A63E7; }
.orange { background-color: #F18F71; }
.light-orange { background-color: #F8D1A3; }

.item h3 {
    font-size: 20px;
    margin: 5px 0;
}

.item p {
    color: #777;
    font-size: 15px;
}

.right{
    position:relative;
    width:40%;
    height:400px;
}

.img{
    position:absolute;
    width:100px;
    height:180px;
    object-fit:cover;
    border-radius:80px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
}

.img1{
     top: absoluate;
    right:230px;
}

.img2{
    bottom: 160px;
    right: 160px;
}

.img3{
    margin-right:80px;
    right:0px;
}
    </style> 
     
</head>
<body>
     <section class="travel-support">
        <header class="header-content">
            <p class="subtitle">TRAVEL SUPPORT</p>
            <h1>Plan your travel with confidence</h1>
            <p class="description">Find help with your bookings and travel plans, and see what to expect along your journey.</p>
        </header>

        <div class="container">
            <div class="text-items">
                <div class="item">
                    <span class="number blue">01</span>
                    <h3>Travel Requirements for Dubai</h3>
                    <p>Stay informed and prepared for your trip to Dubai
                         with essential travel requirements,
                         ensuring a smooth and hassle-free experience in this vibrant and captivating city.</p>
                </div>

                <div class="item">
                    <span class="number orange">02</span>
                    <h3>Multi-risk travel insurance</h3>
                    <p>Comprehensive protection for your peace of mind,range of potential travel risks and unexpected situations.</p>
                </div>

                <div class="item">
                    <span class="number light-orange">03</span>
                    <h3>Travel Requirements by destinations</h3>
                    <p>Stay informed and plan your trip with ease, requirements specific to your desired destinations.</p>
                </div>
            </div>
        <!--Right images-->
    <div class="plan_image">
        <img src="https://wallpaperaccess.com/full/3920054.jpg" 
        class="img img1">
         <img src="https://atravelerstrail.com/wp-content/uploads/2022/09/flight-essentials-768x1024.jpg" 
         class="img img2">
         <img src="https://resize.indiatvnews.com/en/resize/newbucket/715_-/2021/11/purvanchal-expressway-7-1636651319.jpeg" 
         class="img img3">
    </div>
    </div>
    </section>
</body>
</html>
