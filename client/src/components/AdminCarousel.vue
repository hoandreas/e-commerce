<template>
    <div id="carouselExampleIndicators" class="carousel slide my-4" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner" role="listbox">
            <div class="carousel-item active">
                <img class="d-block img-fluid carousel-img" src="../assets/Admin-Page.png" alt="First slide" >
            </div>
            <div class="carousel-item">
                <img class="d-block img-fluid carousel-img" src="../assets/Admin-Page-3.png" alt="Second slide">
            </div>
            <div class="carousel-item">
                <img class="d-block img-fluid carousel-img" src="../assets/Admin-Page-2.png" alt="Third slide">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
</template>

<script>
export default {
  name: 'Carousel'

}
</script>

<style scoped>
.carousel-img {
    object-fit: contain;
    height: 350px;
    width: 900px;
}
</style>
