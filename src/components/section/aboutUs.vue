<template>
    <div class="aboutUs">
       <div class="container">
           <div class="row">
               <div class="col-md-6 text-center citycarosel">
                   <div class="city-img"><img src="../../assets/img/city.jpg" alt="" class="city"></div>
                   <div class="mycarousel">
                            <div id="testimonial-slider" class="owl-carousel">
                                <div class="testimonial">
                                    <p class="description">
                                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus molestie, justo nec convallis sollicitudin, sapien lorem dictum lacus, non consequat odio ipsum nec est. Sed mattis egestas elementum. Nulla facilis
                                    </p>
                                    <!-- <ul> 
                                        <ul>
                                            <li>icon</li>
                                            <li>client name</li>
                                        </ul>
                                        <ul class="review">

                                        </ul>
                                    </ul>                             -->
                                </div>
            
                                <div class="testimonial">
                                    <p class="description">
                                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus molestie, justo nec convallis sollicitudin, sapien lorem dictum lacus, non consequat odio ipsum nec est. Sed mattis egestas elementum. Nulla facilis
                                    </p>
                                    <h3 class="title">KATRINA</h3>
                                    <span class="post">Web Designer</span>
                                </div>
            
                                <div class="testimonial">
                                    <p class="description">
                                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus molestie, justo nec convallis sollicitudin, sapien lorem dictum lacus, non consequat odio ipsum nec est. Sed mattis egestas elementum. Nulla facilis
                                    </p>
                                    <h3 class="title">JEREMY CLEN</h3>
                                    <span class="post">Web Developer</span>
                                </div>
                </div>
            </div>
                   </div>
               </div>
               <div class="col-md-6">

               </div>
           </div>
       </div>
</template>
<script>
export default {
 
}
</script>
<style lang="css">
 .aboutUs{
     padding-top: 100px;
 }
 #testimonial-slider{
    padding: 50px 20px 35px 20px;
    background: #fff;
    text-align: center;
     
}
.testimonial .description{
    font-size: 14px;
    color: #fff;
    line-height: 26px;
    text-indent: 30px;
    position: relative;
    border-left: 1px solid #fff;
}
.testimonial .description:before{
    content: "\f10d";
    font-family: "Font Awesome 5 Free";
    font-weight: 900;
    position: absolute;
    top: 0;
    left: -15px;
}
.testimonial .title{
    font-size: 22px;
    font-weight: bold;
    color: #646262;
    text-transform: capitalize;
    margin: 0;
    letter-spacing: 1px;
}
.testimonial .post{
    display: block;
    font-size: 15px;
    color: #363636;
}
.owl-buttons{
    width: 100%;
    height: 40px;
    position: absolute;
    bottom: 40%;
    left: 0;
}
.owl-prev,
.owl-next{
    position: absolute;
    left: 0;
    transition: all 0.4s ease-in-out 0s;
}
.owl-next{
    left: auto;
    right: 0;
}
.owl-buttons .owl-prev:before,
.owl-buttons .owl-next:before{
    content: "\f104";
    font-family: "Font Awesome 5 Free";
    font-weight: 900;
    font-size: 60px;
    font-weight: 900;
    color: #cacaca;
    line-height: 20px;
    opacity: 0.8;
}
.owl-buttons .owl-next:before{
    content: "\f105";
}
.owl-buttons .owl-prev:hover:before,
.owl-buttons .owl-next:hover:before{
    opacity: 1;
}
.owl-theme .owl-controls .owl-buttons div{
    background: transparent;
}
.owl-theme .owl-controls{
    margin-top: 40px;
}
/* .owl-theme .owl-controls .owl-page span{
    width: 80px;
    height: 80px;
    border-radius: 50%;
    border: 4px solid dodgerblue;
    background: url("") no-repeat;
    background-size: cover;
    transition: all 0.3s ease-in-out 0s;
}
.owl-theme .owl-controls .owl-page:nth-child(2) span{
    background: url("") no-repeat;
    background-size: cover;
}
.owl-theme .owl-controls .owl-page:nth-child(3) span{
    background: url("") no-repeat;
    background-size: cover;
} */
/* .owl-theme .owl-controls.clickable .owl-page:hover span{
    opacity: 0.5;
}
.owl-theme .owl-controls .owl-page.active span,
.owl-theme .owl-controls .owl-page.active:hover span{
    border-color: dodgerblue;
    opacity: 1;
}
@media only screen and (max-width: 479px){
    .owl-buttons{ bottom: 30%; }
} */
.citycarousel{
    position: relative;
}
.mycarousel{
    position: absolute;
    bottom: -100px;
    right: -107px;
    width: 500px;
    height: 300px;
}
.mycarousel #testimonial-slider {
    padding: 50px 20px 35px 20px;
    background: #333456;
    text-align: center;
    color: #fff;
}

</style>