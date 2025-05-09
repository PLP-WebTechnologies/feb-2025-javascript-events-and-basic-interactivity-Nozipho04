<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Starbucks</title>

    <style>
.container {
    background-color:#1E3932  ;
    max-width: 700px;
    padding: 20px;
    border-radius: 10px;
    margin: 20px auto;
}
body {
    background-color:#EAC784 ;
}
img {
    max-width: 700px;
}
h1 {
    color: white;
    font-size: 50px;
    text-align: center;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
h2 { color: white;

}
p {
    color: white;
    font-size:20px ;
    line-height: 1.5;
}
button {
    display: block;
    margin: 0 auto;
    border-radius: 8px;
    font-size: 24px;
    padding: 10px 15px;
    background-color: white;
    color: #1E3932;
    border: 3px #EAC784;
}
button:hover{
    cursor: pointer;
    color: black;
    background-color: #EAC784;
}
footer{
    text-align: center;
    margin-top: 13px;
    color: #1E3932;
    font-size: 18px;
}

    </style>
</head>
<body>
    <div class="container">
    <h1>Starbucks <br> Introducing the new Honey Pistachio Cold Brew</h1>
    <img src="https://people.com/thmb/3SkJcEKvJJXuQ20qksyus7_he4k=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():focal(719x0:721x2)/stabucks-122122-1-1ab7b91f72014f24b804375b228f748d.jpg">
    
    <p>Introducing to you the Honey Pistachio Cold Brew. This refreshing drink blends
    Starbucks' signature cold brew with a rich pistachio-flavored syrup, lightly sweetened with a touch of honey for a
    perfectly balanced taste. Topped with a velvety cold foam infused with hints of toasted pistachio and a drizzle of
    golden honey, this drink offers a smooth, nutty, and slightly sweet experience in every sip. Whether you're a fan of
    cold brew or looking for a new seasonal favorite, the Honey Pistachio Cold Brew is a must-try for coffee lovers looking
    for something indulgent yet refreshing. </p>

    <p> You should try the Honey Pistachio Cold Brew because it offers a unique and delicious flavor combination that’s
    both refreshing and indulgent. The smooth, slow-steeped cold brew provides a rich coffee experience, while the pistachio
    syrup and honey add a nutty sweetness that isn't overpowering. The velvety cold foam on top enhances the texture, making
    each sip creamy and satisfying. Plus, it's a great option for those who enjoy cold coffee but want something a little
    different from the usual vanilla or caramel flavors. Whether you're a longtime Starbucks fan or just looking to switch
    up your coffee routine, this drink is a perfect blend of bold, nutty, and sweet flavors that make it worth trying!</p>

    <div class="images">
        <img src="https://tb-static.uber.com/prod/image-proc/processed_images/5f6113bb47ea957b142cf2e456c678d9/5143f1e218c67c20fe5a4cd33d90b07b.jpeg" style="display: inline-block; max-width: 200px; margin-top: 10px;">
        <img src="https://globalassets.starbucks.com/digitalassets/products/bev/SBX20211029_SaltedCaramelCreamColdBrew.jpg?impolicy=1by1_wide_topcrop_630" style="display: inline-block; max-width: 200px; margin-top: 15px;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSC2sA1jOXHOGt_uHCig93tmTNlCviE9qnmd7kb6qg08gZAxHw3RyTNLGDFACGTVmxC-34&usqp=CAU"style="display:inline-block; max-width:200px; margin-top:15px;">
        <img src="https://www.starbucks.co.za/sites/starbucks-za/files/styles/c03_image_text_1133x476/public/2021-01/StarbucksDelivers-C02_Hero.jpg.webp?itok=GjUfQw_U">
   
        <p>Your Starbucks® run just got even easier
        Find out if delivery is available near you! Start your order to get your Starbucks® favourites delivered to you via
        UberEats or MrD. </p>
        <button>Order now</button>
    </div>
    </div>

    <script>
        function button(){
            let name=prompt("What is your name?");
            let email=prompt("What is your email address?");
            alert("Thank you "+ name + "! We have sent you the full menu of our cold brew by email,check it out!");
        
        }
        let orderNow=document.querySelector("button");
        orderNow.addEventListener("click",button)
    </script>
    <footer>CODED BY NOZIPHO NDLOVU</footer>
</body>
</html>



