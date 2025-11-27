# 11-B

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Sayfam</title>

    <link rel="stylesheet" href="css/bootstrap.css">
    <script src="js/bootstrap.bundle.js"></script>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI"
        crossorigin="anonymous"></script>

    <style>
        .banner {
            background-color: blueviolet;
            color: #FFF;
            height: 150px;
            text-align: center;
        }

        .slide {
            background-color: bisque;
            text-align: center;
            height: 500px;
        }

        .slide-left {
            background-color: orange;
        }

        .slide-right {
            background-color: blue;

        }
        .sss {
            background-color: rgba(49, 49, 49, 0.482);
            height: 300px;
            
        }
        #accordionFlushExample {
            border-radius: 10px;
        }
        
        .navmenu {
            background-color: rgb(96, 17, 170);
            /*height:30px;*/
            color: #FFF;
            padding: 0px;

        }

        .content-left {
            background-color: gray;
            height: 500px;
            color: #FFF;
        }

        .content-right {
            background-color: rgb(97, 92, 92);
            height: 500px;
            color: #FFF;
        }

        .footer {
            height: 250px;
            background-color: rgb(76, 27, 122);
            color: #FFF;
        }

        .navbar-renk {
            background-color: rgb(88, 18, 153);
        }

        .navbar-renk2 {
            background-color: rgb(122, 22, 214);
        }

        .mavi {
            background-color: blue
        }

        .yesil {
            background-color: green;
        }

        .kirmizi {
            background-color: red;
        }

        .sari {
            background-color: rgb(207, 207, 0);
        }

        .mor {
            background-color: purple;
        }

        .siyah {
            background-color: black;
        }

        .acikmavi {
            background-color: rgb(26, 151, 192);
        }
    </style>
</head>
<!--
    Yanlarda bosluklu
    div.container.mavi>(div.row>{meraba}) 
    Tam ekran
    div.container-fluid.mavi>(div.row>{meraba})
    div.container-fluid.mavi>(div.row>h1>{Meraba})
    .nav.navbar.navbar-expand-lg.navbar-renk[data-bs-thema="dark"]>div.container>(a.navbar-brand[href=#]>{ABC Yazılım})+(button.navbar-toggler[type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"]>span.navbar-toggler-icon)


    .nav.navbar.navbar-expand-lg.navbar-renk[data-bs-thema="dark"]>div.container>(a.navbar-brand[href=#]>{ABC Yazılım})+(button.navbar-toggler[type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"]>span.navbar-toggler-icon)+(div.collapse.navbar-collapse#navbarSupportedContent>(ul.navbar-nav.me-auto.mb-2.mb-lg-0>(li.nav-item)+(a.nav-link.active[aria-current="page" href="index.html"]>{Ana Sayfa}))+(li.nav-item>a.nav-link[aria-current="page" href="hakkimizda.html"]>{Hakkımızda})+(li.nav-item>a.nav-link[aria-current="page" href="iletisim.html"]>{İletişim})+(form.d-flex[role="search"]>(input.form-control.me-2[type="search" placeholder="Aranacak bilgi..." aria-label="Search"])+(button.btn.btn-secondary[type="submit"]>{Ara})))


-->

<body>

    <div class="nav navbar navbar-expand-lg navbar-renk" data-bs-thema="dark">
        <div class="container">
            <a href="#" class="navbar-brand">ABC Yazılım</a><button class="navbar-toggler" type="button"
                data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"><span
                    class="navbar-toggler-icon"></span></button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item"></li>
                    <a href="index.html" class="nav-link active" aria-current="page">Ana Sayfa</a>
                </ul>
                <li class="nav-item"><a href="hakkimizda.html" class="nav-link" aria-current="page">Hakkımızda</a></li>
                <li class="nav-item"><a href="iletisim.html" class="nav-link" aria-current="page">İletişim</a></li>
                <form action="" class="d-flex" role="search"><input type="search" class="form-control me-2"
                        placeholder="Aranacak bilgi..." aria-label="Search"><button class="btn btn-secondary"
                        type="submit">Ara</button></form>
            </div>
        </div>
    </div>

    <div class="container">
        <div class="row">
            <div class="banner col-md-12">banner burada yer alacak</div>
        </div>
        <div class="row">
            <div class="col-md-9 slide slide-left">
                <div id="carouselExampleIndicators" class="carousel slide">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0"
                            class="active" aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                            aria-label="Slide 2"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                            aria-label="Slide 3"></button>
                    </div>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img height="500" src="images/Resim.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>residen evil</h5>
                                <p>Zombi tarzı korku gerilim dolu anlar</p>
                            </div>

                        </div>
                        <div class="carousel-item">
                            <img height="500" src="images/Resim2.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>Baslık</h5>
                                <p>Acıklama</p>
                            </div>

                        </div>
                        <div class="carousel-item">
                            <img height="500" src="images/Resim3.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>Baslık</h5>
                                <p>acıklama.</p>
                            </div>

                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>
            <div class="col-md-3 slide slide-right">
                <div id="carouselExampleIndicators2" class="carousel slide">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselExampleIndicators2" data-bs-slide-to="0"
                            class="active" aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators2" data-bs-slide-to="1"
                            aria-label="Slide 2"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators2" data-bs-slide-to="2"
                            aria-label="Slide 3"></button>
                    </div>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img height="500" src="images/Resim.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>residen evil</h5>
                                <p>Zombi tarzı korku gerilim dolu anlar</p>
                            </div>

                        </div>
                        <div class="carousel-item">
                            <img height="500" src="images/Resim2.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>Baslık</h5>
                                <p>Acıklama</p>
                            </div>

                        </div>
                        <div class="carousel-item">
                            <img height="500" src="images/Resim3.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>Baslık</h5>
                                <p>doga.</p>
                            </div>

                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators2"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators2"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>

        </div>
        <div class="row">
            
            <div class="cold-md-12 sss">
                <h1>Sıkça sorulan sorular (SSS)</h1>
                <div class="accordion accordion-flush" id="accordionFlushExample">
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                                data-bs-target="#flush-collapseOne" aria-expanded="false"
                                aria-controls="flush-collapseOne">
                                Özel yazılım geliştirme yapıyor musunuz?
                            </button>
                        </h2>
                        <div id="flush-collapseOne" class="accordion-collapse collapse"
                            data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">
                                Windows Masaüstü, web programlama ve mobil uygulamalar geliştirmekteyim.
                                </div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                                data-bs-target="#flush-collapseTwo" aria-expanded="false"
                                aria-controls="flush-collapseTwo">
                                Teknik destek veriyor musunuz?
                            </button>
                        </h2>
                        <div id="flush-collapseTwo" class="accordion-collapse collapse"
                            data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">
                                Geliştirilen yazılımların teknik desteği pazar hariç haftanın 6 günü verilmektedir.
                            </div>
                        </div>
                    </div>
                    <div class="accordion-item">
                        <h2 class="accordion-header">
                            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                                data-bs-target="#flush-collapseThree" aria-expanded="false"
                                aria-controls="flush-collapseThree">
                                Sizinle nasıl iletişim kurabilirim
                            </button>
                        </h2>
                        <div id="flush-collapseThree" class="accordion-collapse collapse"
                            data-bs-parent="#accordionFlushExample">
                            <div class="accordion-body">
                                05448781421 numarısıyla iletişim kurabiliriz.
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-9 content-left">9 birim sol taraf</div>
            <div class="col-md-3 content-right">3 birim sağ taraf</div>
        </div>

        <div class="row">
            <div class="col-md-12 footer">
                <div class="row">
                    <div class="col-md-3 mavi">
                        <ul>
                            <li>Ana Sayfa</li>
                            <li>Hakkımda</li>
                            <li>Projelerim</li>
                            <li>İletişim</li>
                        </ul>
                    </div>
                    <div class="col-md-3 kirmizi">
                        <h5></h5>
                        <ul>
                            <li>Instagram</li>
                            <li>WhatsApp</li>
                            <li>Youtube</li>
                            <li>X (Twitter)</li>
                            <li>FaceBook</li>
                        </ul>
                    </div>
                    <div class="col-md-3 yesil">
                        <h5>En çok okunan makaleler</h5>
                        <ul>
                            <li>
                                Makale 1
                                Makale 2
                                Makale 3
                            </li>
                        </ul>
                    </div>
                    <div class="col-md-3 acikmavi">
                        <h5>Adres</h5>
                        ABC Mah.<br>
                        ABC Cad.<br>
                        Beylikdüzü İSTANBUL
                    </div>
                </div>
            </div>
        </div>

    </div>
    <script>

    </script>
</body>

</html>
