<template>
    <br><br><br>
    <img src="/img/okl.png" class="img-fluid" alt="..." style="margin-left: 200px;">
    <br><br><br>
    <div class="accordion accordion-flush" id="accordionFlushExample" style="margin-bottom: 200px;">
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                    data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                    KOMİSYONLAR
                </button>
            </h2>
            <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                <ul class="list-group">
                    <li class="list-group-item disabled" aria-disabled="true">Eğitim Komisyonu</li>
                    <li class="list-group-item">Öğrenciler için Sosyal Yardım Komisyonu</li>
                    <li class="list-group-item">Staj Komisyonu</li>
                    <li class="list-group-item">Öğrenci Etkinlikleri Komisyonu</li>
                    <li class="list-group-item">Kurumlar ve Sanayi İle İşbirliği Komisyonu</li>
                </ul>
                <br>
                
            </div>
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                    data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                    OKUL FOTOĞRAFLARI
                </button>
            </h2>
            <div id="flush-collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                <div id="carouselExampleIndicators" class="carousel slide" style="width: 1500px; ">
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
                            <img src="/img/foto.jpg" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="/img/foto1.jpg" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="/img/foto2.jpg" class="d-block w-100" alt="...">
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
        </div>
        <div class="accordion-item">
            <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                    data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                    YÖNETİCİ KADROMUZ
                </button>
            </h2>
            <div id="flush-collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                <div class="card" style="width: 18rem; float: left; margin-left: 100px; margin-right: 50px; ">
                    <img src="/img/müdür.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Dr. Öğr. üyesi Nedim ÇETİNKAYA</h5>
                        <h6>Meslek Yüksekokulu Müdürü</h6>
                    </div>
                </div>
                <div class="card" style="width: 18rem; float: left; margin-left: 50px;">
                    <img src="/img/turkler.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Öğr. Gör. Levent TüRKLER</h5>
                        <h6>Meslek Yüksekokulu Müdür Yardımcısı</h6>
                    </div>
                </div>
                <div class="card" style="width: 18rem; float: left; margin-left: 50px;">
                    <img src="/img/müdüry.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Öğr. Gör. Dr. Mehmet ÇETİN</h5>
                        <h6>Meslek Yüksekokulu Müdür Yardımcısı</h6>
                    </div>
                </div>
                <div class="card" style="width: 18rem; float: left; margin-left: 50px;">
                    <img src="/img/yaramis.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Seher YARAMIŞ</h5>
                        <h6>Yüksekokul Sekreter V.</h6>
                    </div>
                </div>


            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: "MyComponent",
    props: {
        
        title: String
    }
}
</script>