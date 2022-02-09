<template>
    <div class="header">
        <div class="site-mobile-menu site-navbar-target togel">
            <div class="site-mobile-menu-header">
                <div class="site-mobile-menu-close mt-3">
                    <span class="icon-close2 js-menu-toggle"></span>
                </div>
            </div>
            <div class="site-mobile-menu-body text-left"></div>
        </div>
        <header
        class="site-navbar js-sticky-header site-navbar-target"
        role="banner">
            <div class="container">
                <div class="row align-items-center position-relative">
                    <div class="site-logo">
                        <a href="/"><img src="../assets/km-logo.png" alt=""></a>
                    </div>
                    <div class="col-12 navbar">
                        <nav class="site-navigation ml-auto" role="navigation">
                            <ul
                                class="site-menu main-menu js-clone-nav ml-auto d-none d-lg-block">
                                <li>
                                <router-link to="/" class="nav-link link-active">Beranda</router-link>
                                <router-link to="/CaraKerja">Cara Kerja</router-link>
                                <router-link to="/About" class="nav-link">Tentang</router-link>
                                <router-link to="/Promo" class="nav-link">Promo</router-link>
                                <router-link to="/Event" class="nav-link">Event</router-link>
                                <router-link to="/FAQ" class="nav-link">FAQ</router-link>
                                <router-link to="/Kontak" class="nav-link">Kontak</router-link>
                                </li>
                            </ul>
                        </nav>
                    </div>
                    <div class="toggle-button d-inline-block d-lg-none">
                        <a href="#" class="site-menu-toggle py-5 js-menu-toggle text-black"
                        ><span class="icon-menu h3"></span
                        ></a>
                    </div>
                </div>
            </div>
        </header>
        <router-view />
    </div>
</template>

<script>
export default {};
</script>

<style>
    .togel {
        color: white;
        background-color: #CC3300;
    }
@media (max-width: 576px) {
    
}
@media (max-width: 1279px) {
    
}
@media (min-width: 1280px) {
    
}
</style>
