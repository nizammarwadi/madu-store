<template>
    <div class="whyus" id="excellence">
        <h3 class="title-whyus">Mengapa Anda Memilih Madu Kami?</h3>
        <p class="content-whyus">Madu Store dimana sebuah toko yang menyediakan madu - madu pilihan dan berbagai macam jenis madu juga disediakan disini.</p>
        <div class="whyus-one">
            <div class="whyus-content-one">
                <h3 class="whyus-one-title">Mutu Terjamin 100%</h3>
                <p class="whyus-one-content">Kualitas dari madu kami jangan anda ragukan lagi, dikarenakan kemurnian dan kesempurnaan rasa dan khasiatnya. Sehingga dapat membuat anda merasakan kemurnian dan keaslian madu dari kami tanpa harus ragu.</p>
            </div>
             <img src="~/assets/image/registration.png" alt="" class="whyus-one-img">
        </div>
        <div class="whyus-one">
             <img src="~/assets/image/registration.png" alt="" class="whyus-one-img">
            <div class="whyus-content-one">
                <h3 class="whyus-one-title">Harga Terjangkau dan Terpercaya</h3>
                <p class="whyus-one-content">Kualitas dari madu kami jangan anda ragukan lagi, dikarenakan kemurnian dan kesempurnaan rasa dan khasiatnya. Sehingga dapat membuat anda merasakan kemurnian dan keaslian madu dari kami tanpa harus ragu.</p>
            </div>
        </div>
        <div class="whyus-one">
            <div class="whyus-content-one">
                <h3 class="whyus-one-title">Mutu Terjamin 100%</h3>
                <p class="whyus-one-content">Kualitas dari madu kami jangan anda ragukan lagi, dikarenakan kemurnian dan kesempurnaan rasa dan khasiatnya. Sehingga dapat membuat anda merasakan kemurnian dan keaslian madu dari kami tanpa harus ragu.</p>
            </div>
             <img src="~/assets/image/registration.png" alt="" class="whyus-one-img">
        </div>  
        
    </div>
</template>

<script>
export default {

}
</script>

<style>
body {
    background-color: white;
}
.whyus {
    padding-top: 80px;
}
.title-whyus {
    text-align: center;
    font-size: 40px;
    font-weight: bold;
}
.title-whyus::after  {
    content: "";
    display: block;
    width: 150px;
    height: 2px;
    margin: 24px auto;
    background: #86d0c1;
}
.content-whyus {
    text-align: center;
    font-size: 22px;
    margin: 0px auto;
}
.whyus-one {
    padding-top: 50px;
    padding-left: 80px;
    width: 100%;
    text-align: justify;
    display: flex;
    justify-content: space-around;
}
.whyus-one-title {
    margin-top: 40px;
    font-size: 32px;
    font-weight: bold;
}
.whyus-content-one {
    width: 500px;
    text-align: justify;
    font-size: 17px;
    font-weight: 400;
}
.whyus-one-img {
    max-width: 400px;
}
@media(max-width: 678px){
    .whyus {
        margin: 50px 0px 0px 0px;
        padding: 0px 0px;
    }
    .whyus-one {
        display: block;
        width: 90%;
        padding: 0px 10px;
        margin: 0px auto;
    }
    .whyus-content-one{
        width: 100%;
        margin: 0px 0px;
        padding: 0px;
    }
    .whyus-one-img {
        width: 100% !important;
    }
}
</style>