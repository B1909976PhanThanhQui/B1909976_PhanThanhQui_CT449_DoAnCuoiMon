<template>
    <div class="container-fluid" style="    width: 1000px;
        height: 635px;
        margin-top: 17px;
        border: 2px solid #ccc;
        padding: 8px;
        border-radius: 14px">
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="https://theme.hstatic.net/1000219449/1000505399/14/slideshow_2.jpg?v=952" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="https://theme.hstatic.net/1000219449/1000505399/14/slideshow_3.jpg?v=952" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="https://theme.hstatic.net/1000219449/1000505399/14/slideshow_5.jpg?v=952" class="d-block w-100" alt="...">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>
</template>