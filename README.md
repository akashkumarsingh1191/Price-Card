# Price-Card
I am making my first HTML &amp; CSS project i.e. "Price Card" in which the price card will change their size according to the Window size and I am using the "CSS-Gradient" in which the color will change after the reaching the button. 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Price Card</title>
    <link rel="StyleSheet" href="style.css">
</head>
<body>
    <section class="container">
        <div class="card">
            <div class="detail">
                <p class="package">Basic</p>
                <p class="price"><sup class="dollar">$</sup>19.99</p>
                <hr>
                <p>100 GB</p>
                <hr>
                <p>2 Users</p>
                <hr>
                <p>Send To More People</p>
                <hr>
                <button class="card-btn btn-one">Subscribe</button>
            </div>
        </div>

        <div class="card middle">
            <div class="detail">
                <p class="package">Adept</p>
                <p class="price"><sup class="dollar">$</sup>99.99</p>
                <hr>
                <p>1000 GB</p>
                <hr>
                <p>50 Users</p>
                <hr>
                <p>Send To More People</p>
                <hr>
                <button class="card-btn btn-two">Subscribe</button>
            </div>
        </div>

        <div class="card">
            <div class="detail">
                <p class="package">Intermediate</p>
                <p class="price"><sup class="dollar">$</sup>29.99</p>
                <hr>
                <p>500 GB</p>
                <hr>
                <p>4 Users</p>
                <hr>
                <p>Send To More People</p>
                <hr>
                <button class="card-btn btn-one">Subscribe</button>
            </div>
        </div>
    </section>
</body>
</html>
