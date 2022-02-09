<template>
    <div>
        <section id="section" class="section py-3">
            <div class="footer atas">
                <div class="container">
                    <div class="row row-atas">
                        <div class="col-xl-4 col-md-6 col-12 kepala">
                            <div class="log_1">
                                <img src="../assets/km-logo-white.png" width="150px" alt="">
                            </div><br>
                            <div class="row mb-2">
                                <div class="col-2">
                                    <div class="icon">
                                        <img src="../assets/location.png" width="17px" alt="">
                                    </div>
                                </div>
                                <div class="col-9 alamat">
                                    <small>
                                        Jl. Raya Tamansari, Kompleks Karangwuni, 
                                        Desa Tamansari, Karangmoncol, Kab. Purbalingga, 
                                        Jawa Tengah 53355
                                    </small>
                                </div>
                            </div>
                            <div class="row mb-2">
                                <div class="col-2">
                                    <div class="icon">
                                        <img src="../assets/whatsapp.png" width="17px" alt="">
                                    </div>
                                </div>
                                <div class="col-9 alamat">
                                    <small>
                                        +62 813 6064 6002
                                    </small>
                                </div>
                            </div>
                            <div class="row mb-2">
                                <div class="col-2">
                                    <div class="icon">
                                        <img src="../assets/massage.png" width="17px" alt="">
                                    </div>
                                </div>
                                <div class="col-9 alamat">
                                    <small>
                                        contact@komerce.id
                                    </small>
                                </div>
                            </div>
                        </div>
                        <div class="col-xl-2 col-md-3 col-6 pt-2 pundak">
                            <h5>Perusahaan</h5><br>
                            <li class="mb-2"><router-link to="/About">Tentang</router-link></li>
                            <li class="mb-2"><router-link to="/CaraKerja">Cara Kerja</router-link></li>
                            <li class="mb-2"><router-link to="/Promo">Promo</router-link></li>
                            <li class="mb-2"><router-link to="/Event">Event</router-link></li>
                            <li class="mb-2"><router-link to="/FAQ">FAQ</router-link></li>
                            <li class="mb-2"><router-link to="/Kontak">Kontak</router-link></li>
                        </div>
                        <div class="col-xl-3 col-md-3 col-6 pt-2 lutut">
                            <h5 class="judul mb-2">Keahlian Talent</h5><br>
                            <li class="mb-2">Customer Service</li>
                            <li class="mb-2">Advertiser</li>
                            <li class="mb-2">Admin Social Media</li>
                            <li class="mb-2">Admin Order</li>
                            <li class="mb-2">Admin Marketplace</li>
                        </div>
                        <div class="col-xl-3 col-md-6 col-12 pt-2 kaki">
                            <h5 class="judul">Partner Kolaborasi</h5><br>
                            <div class="row">
                                <div class="col-3 mb-2"><img src="../assets/image-30.png" width="35px" alt=""></div>
                                <div class="col-3 mb-2"><img src="../assets/image-38.png" width="35px" alt=""></div>
                                <div class="col-3 mb-2"><img src="../assets/image-32.png" width="35px" alt=""></div>
                                <div class="col-3 mb-2"><img src="../assets/image-35.png" width="35px" alt=""></div>
                                <div class="col-3 mb-2"><img src="../assets/image-36.png" width="35px" alt=""></div>
                                <div class="col-3 mb-2"><img src="../assets/image-37.png" width="35px" alt=""></div>
                                <div class="col-3 mb-2"><img src="../assets/image-33.png" width="35px" alt=""></div>
                                <div class="col-3 mb-2"><img src="../assets/logo-1.png" width="35px" alt=""></div>
                            </div>
                            <div class="row">
                                <div class="col-12"><h5 class="">Cari Tau Berita Terbaru</h5></div>
                                <div class="col-2"><img src="../assets/Vector.png" alt=""></div>
                                <div class="col-2"><img src="../assets/Vector(1).png" alt=""></div>
                                <div class="col-2"><img src="../assets/Vector(4).png" alt=""></div>
                                <div class="col-2"><img src="../assets/Vector(2).png" alt=""></div>
                                <div class="col-2"><img src="../assets/Vector(3).png" alt=""></div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="container pt-5">
                    <div class="row dengkul">
                        <div class="col-xl-2 col-md-4 col-6 dengkul-1">
                            <h5>Syarat & Ketentuan</h5>
                        </div>
                        <div class="col-xl-3 col-md-3 col-6 dengkul-2">
                            <h5>Kebijakan Privasi</h5>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer bawah telapak">
                <div class="container-fluid">
                    <div class="row row-bawah">
                        <div class="col-xl-6 bawah-satu pt-2">
                            <p><small>Copyright © 2021 Komerce. All Rights Reserved</small></p>
                        </div>
                        <div class="col-xl-6 bawah-dua pt-2">
                            <p><small>Trademark of PT Kampung Marketerindo Berdaya</small></p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<style>
.footer {
    color: white;
}
.kepala, .telapak {
    padding: 0px;
}
.dengkul {
    text-decoration: underline;
}
.dengkul-1, .dengkul-2 {
    padding: 0%;
}
h5 {
    font-family: Poppins;
}
.judul {
    margin: 0px;
}
.col-6, h5, li, .col-9, .icon, .col-12, .container {
    border: solid 1px;
}
.col-3 {
    padding: 0%;
    text-align: center;
    border: dotted 1px black
}
    .atas {
        padding: 4%;
        padding-bottom: 2%;
        text-align: left;
        background-color: #CC3300;
    }
    .alamat {
        font-family: Public Sans;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;
        line-height: 24px;
        letter-spacing: 0em;
        text-align: left;

        padding: 0%;
    }
    li {
        list-style-type: none;
        font-family: "Public Sans";
    }
    .bawah {
        background-color: #AF1F00;
    }
    .row-bawah, .icon {
    text-align: center;
    }
@media (max-width: 576px) {
    
}
@media (max-width: 1279px) {
    
}
@media (min-width: 1280px) {
    
}
</style>