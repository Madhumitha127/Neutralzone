<template>
  <v-main id="app">
      <div class="firstpage">
        <v-img alt="land1" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbTgJAHK6YC0we4cCKGNV7HTpicIfqXH1kjPeZ76VH7pIqORBOI3qJqJ9P_aXrzNm-bNk&usqp=CAU.jpg m-0 p-0">
               <v-spacer></v-spacer>
                 <v-card-text class="font-weight-medium mt-12 text-center text-subtitle-1">
                      <h1 class="text-white text-right  max-height=800  padding-top: 30px padding-right:80px " >DATA STORING <br/>
                        PLATFORM
                       </h1>
                             <p class="text-md-right text-white padding-top-30px">A data platform is an integrated set<br/>
                                of technologies that collectively meets an organization's <br/>
                                end-to-end data needs.
                              </p>  
                 </v-card-text>  
         <v-img alt="land4" src="https://cdni.iconscout.com/illustration/premium/thumb/data-sharing-2600556-2179741.png" max-height="500"
             max-width="600" data-aos="slide-down"
             data-aos-ease = 'ease'
             data-aos-duration="1500"
               data-aos-delay='500'></v-img> 
   </v-img>
 
  </div>
      <div class="secondpage">
      <v-img alt="land2" src="https://wallpapercrafter.com/desktop/87115-lines-simple-background-abstract-hd-4k-dark-black-dribbble-oled.jpg">
  

      </v-img>
  </div>
      <v-img alt="land3" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbTgJAHK6YC0we4cCKGNV7HTpicIfqXH1kjPeZ76VH7pIqORBOI3qJqJ9P_aXrzNm-bNk&usqp=CAU.jpg">

      </v-img>
  </v-main>
</template>


<style scoped>
#firstpage{
  
  margin:0;
padding:0;

justify-content: space-evenly;
  font-size:48px;
  color:white;
  padding-top: 30px;
  padding-right: 80px;
}



#land2{
  background-image:url('https://wallpapercrafter.com/desktop/87115-lines-simple-background-abstract-hd-4k-dark-black-dribbble-oled.jpg');
  background-size:default;
  width:100vh;height:100vh;top:0;bottom:0;left:0;right:0;position:absolute;
}
#land3{
  background-image:url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbTgJAHK6YC0we4cCKGNV7HTpicIfqXH1kjPeZ76VH7pIqORBOI3qJqJ9P_aXrzNm-bNk&usqp=CAU.jpg');
  background-size:default;
  width:100vh;height:100vh;top:0;bottom:0;left:0;right:0;position:absolute;
}
#land4{
  background-image:url('https://cdni.iconscout.com/illustration/premium/thumb/data-sharing-2600556-2179741.png');
  background-size:contain;
  width:600;right:0;height:500;position:relative;
}

</style>
<script>
export default{
  name :"homepage",
 
 
}
</script>
