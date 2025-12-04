<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI"
        crossorigin="anonymous"></script>
    <style>
        .navbar-renk {
            background-color: #1672b4;
            color: white;
        }

        .dropdown-item {
            color: black;
        }

        .nav-link {
            color: white;
        }

        .navbar-brand {
            color: white;
        }

        .d-block {
            height: 400px;
            width: 100%;
        }
        .banner {
            color: black;
        }
    </style>
</head>
<!--
    (li>a[class="dropdown-item" href="#"]>{Ürün$})*10
-->

<body>
    <div class="container">
        <!-- bg-body-tertiary renk kendisi atar silinirse biz atarız -->
        <nav class="navbar navbar-expand-lg navbar-renk">
            <div class="container-fluid">
                <a class="navbar-brand" href="#"><img width="100px" height="100px" src="images/resim.jpg" alt=""
                        srcset=""></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link" aria-current="page" href="#">Ana Sayfa</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Hakkımızda</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                                aria-expanded="false">
                                Ürünler
                            </a>
                            <ul class="dropdown-menu">
                                <li><a href="#" class="dropdown-item">Ürün1</a></li>
                                <li><a href="#" class="dropdown-item">Ürün2</a></li>
                                <li><a href="#" class="dropdown-item">Ürün3</a></li>
                                <li><a href="#" class="dropdown-item">Ürün4</a></li>
                                <li><a href="#" class="dropdown-item">Ürün5</a></li>
                                <li><a href="#" class="dropdown-item">Ürün6</a></li>
                                <li><a href="#" class="dropdown-item">Ürün7</a></li>
                                <li><a href="#" class="dropdown-item">Ürün8</a></li>
                                <li><a href="#" class="dropdown-item">Ürün9</a></li>
                                <li><a href="#" class="dropdown-item">Ürün10</a></li>
                                <li>
                                    <hr class="dropdown-divider">
                                </li>
                                <li><a class="dropdown-item" href="#">Hepsini gör</a></li>
                            </ul>
                        </li>
                        <!-- 
                      <li class="nav-item">
                        <a class="nav-link disabled" aria-disabled="true">Disabled</a>
                      </li>
                        -->
                    </ul>
                    <!--
                        
    
                        <form class="d-flex" role="search">
                      <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search"/>
                      <button class="btn btn-outline-success" type="submit">Search</button>
                    </form>
                    -->
                    Sipariş Telefon:05448781421
                    <!--
                        hesap makinesinde gözüküyor diyelimki ben 4c gibi yapcam ama sayıyı 52 yapcam bunun icin napmalıyım
                    -->
                </div>
            </div>
        </nav>

        <!-- slayt -->
        <div class="row">
            <div class="col-md-12">
                <div id="carouselExampleCaptions" class="carousel slide">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0"
                            class="active" aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                            aria-label="Slide 2"></button>
                        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
                            aria-label="Slide 3"></button>
                    </div>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="images/Resim.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>First slide label</h5>
                                <p>Some representative placeholder content for the first slide.</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="images/Resim2.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>Second slide label</h5>
                                <p>Some representative placeholder content for the second slide.</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="images/Resim3.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                                <h5>Third slide label</h5>
                                <p>Some representative placeholder content for the third slide.</p>
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
            </div>
        </div>
        <div class="row">
            <div class="col-md-3">
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
            <div class="col-md-9">
                <div class="row row-cols-1 row-cols-md-4 g-4">
                    <div class="card">
                        <img src="images/kek1.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This content is a little bit longer.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek2.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This card has supporting text below as a natural lead-in to additional
                                content.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek3.webp" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek4.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>

                    <div class="card">
                        <img src="images/kek5.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek6.webp" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek7.webp" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek8.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek9.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek10.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek11.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek12.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek13.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek14.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek15.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <div class="card">
                        <img src="images/kek16.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This card has even longer content than the first to show that equal
                                height action.</p>
                            <a href="#" class="btn btn-danger p-2">satın al</a>
                        </div>
                    </div>
                    <nav aria-label="Page navigation example">
                        <ul class="pagination">
                          <li class="page-item"><a class="page-link" href="#">Previous</a></li>
                          <li class="page-item"><a class="page-link" href="#">1</a></li>
                          <li class="page-item"><a class="page-link" href="#">2</a></li>
                          <li class="page-item"><a class="page-link" href="#">3</a></li>
                          <li class="page-item"><a class="page-link" href="#">Next</a></li>
                        </ul>
                      </nav> 
                </div>
            </div>
        </div>
        <div class="row banner kirmizi">
            <div class="col-md-3 p-2 mt-5">
                <ul>
                    <li>Ana Sayfa</li>
                    <li>Hakkımızda</li>
                    <li>Ürünler</li>
                    <li>İletişim</li>
                </ul>
            </div>
            <div class="col-md-3 p-2 mt-5">
                <ul>
                    <li>Ana Sayfa</li>
                    <li>Hakkımızda</li>
                    <li>Ürünler</li>
                    <li>İletişim</li>
                </ul>
            </div>
        </div>
    </div>

</body>

</html>
