<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="home.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body style="background-color: rgb(5, 5, 9);">
    <!-- navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <img src="./ZEE5_logo.svg" alt="" height="50px" width="50px">
            <a class="navbar-brand" href="#" style="margin-left: 50px;">Home</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active"style="margin-left: 20px;" aria-current="page" href="#">TV Shows</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active"style="margin-left: 20px;" href="#">Movies</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link active" href="#"style="margin-left: 20px;">Premium</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link active" href="#"style="margin-left: 20px;">Web series</a>
                    </li>
                    <i class="fa-solid fa-grip-vertical fa-rotate-90" style="color: #ebeef4;" ></i>
    <input type="text" id="input" placeholder="Search for movies,shows,etc">
    <i class="fa-solid fa-magnifying-glass" style="color: white;"></i>         
</ul>
<button type="submit" id="btn1">Login</button>
<button type="submit" id="btn2">BUY PLAN</button>
                <!-- <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                </form> -->
            </div>
        </div>
    </nav>

    <!-- carousel -->

    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
                aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
                aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://akamaividz2.zee5.com/image/upload/w_1188,h_475,c_scale,f_webp,q_auto:eco/resources/0-6-4z5359283/cover/1920x770ffe3d1ab5413488b9a00c7f8bd068751.jpg"
                    class="d-block w-75" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <!-- <h5>First slide label</h5>
          <p>Some representative placeholder content for the first slide.</p> -->
                    <h4 style="color: rgb(245, 240, 240);font-weight: bolder;position: relative;right: 55%;">SeethaRama
                    </h4>

                    <button id="btn">Watch</button>
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://akamaividz2.zee5.com/image/upload/w_1188,h_475,c_scale,f_webp,q_auto:eco/resources/0-6-4z5399186/cover/1920x770c5af6b1638ba40588c10ba2dc34fb5004e65aaded94243f8a2795bbddafaed56.jpg"
                    class="d-block w-75" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <!-- <h5>Second slide label</h5>
          <p>Some representative placeholder content for the second slide.</p> -->
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://akamaividz2.zee5.com/image/upload/w_1188,h_475,c_scale,f_webp,q_auto:eco/resources/0-0-1z5359029/cover/1920x770e80779dbdde042fd8f451ea5a69cec08.jpg"
                    class="d-block w-75" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <!-- <h5>Third slide label</h5>
          <p>Some representative placeholder content for the third slide.</p> -->
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>

    <h3>treanding near you </h3>

    <div id="poster">
        <img src="https://akamaividz2.zee5.com/image/upload/w_231,h_347,c_scale,f_webp,q_auto:eco/resources/0-101-10z5391597/portrait/kadharbasha200h1920w720953c0fbe41e842f4940fd8ba0158f34c.jpg"
            alt="">
        <img src="https://akamaividz2.zee5.com/image/upload/w_231,h_347,c_scale,f_webp,q_auto:eco/resources/0-6-4z5399186/portrait/1920x770c5af6b1638ba40588c10ba2dc34fb5004e65aaded94243f8a2795bbddafaed56.jpg"
            alt="">
        <img src="https://akamaividz2.zee5.com/image/upload/w_231,h_347,c_scale,f_webp,q_auto:eco/resources/0-0-1z5379692/portrait/1920x7703d34f25a3b8a4f7291e750b118e494270d06216ac413418d82e506d09671a1fc.jpg"
            alt="">
        <img src="https://akamaividz2.zee5.com/image/upload/w_231,h_347,c_scale,f_webp,q_auto:eco/resources/0-101-10z5395323/portrait/1920x770da0a1149e53a4fc4866398e2c7dc00db.jpg"
            alt="">
        <img src="https://akamaividz2.zee5.com/image/upload/w_231,h_347,c_scale,f_webp,q_auto:eco/resources/0-0-1z5334341/portrait/1920x7702020ffa4b64f4222b16e4d5ebc0c3a36.jpg"
            alt="">
        <img src="https://akamaividz2.zee5.com/image/upload/w_231,h_347,c_scale,f_webp,q_auto:eco/resources/0-101-10z5387550/portrait/1920x770ab2558d0e9e24dd19cb3382829f51067.jpg"
            alt="">
        <!-- <img src="https://akamaividz2.zee5.com/image/upload/w_231,h_347,c_scale,f_webp,q_auto:eco/resources/0-0-1z5133458/portrait/1920x770ee070807403048a7a76f9fab0a1ca2ffeed49224d0aa47148205083f6f067665.jpg" alt="">   -->
    </div>





    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"
        integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js"
        integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF"
        crossorigin="anonymous"></script>
</body>

</html>
