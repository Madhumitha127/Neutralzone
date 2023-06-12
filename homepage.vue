<template>
  <v-container fluid full-hight>
   <v-img class="bg" src="https://img.freepik.com/free-photo/abstract-smooth-empty-grey-studio-well-use-as-background-business-report-digital-website-template-backdrop_1258-55967.jpg">
        <v-row>
          <v-col class="col-sm-12 col-md-6 ">
             <v-img  class="image space-otto " src="https://cdn.quantiphi.com/2021/04/8e045d00-enterprise-data-sharing-platform-01.png" max-height="700" max-width="700" left="50%">
       
             </v-img>
          </v-col>
          <v-col class="col-sm-12 col-md-6">
             <h1 class="text-right font-weight-bold" font-weight="800" style="padding-top: 30%; padding-right: 40%;  font-size: 50px;line-height: 60px; color: #2E3D62;"><b> NEUTRAL ZONE</b>

              </h1>
            
              <br>
              <v-row justify='center'>
                <a href="#" class="banner-one__btn" data-v-b5f60db0="">Get Started</a>
              </v-row>
              
           </v-col> 
        </v-row>
   </v-img>
   <a href="/">
   <v-img  class="bg1" src="https://cdn.dribbble.com/users/140720/screenshots/3561570/meso-800x600_1.gif" alt="gif" left="0%" right="0%" max-height="700"  to='/About'>
                 <h1 class=" left-line black--text text-center" style="font-size:50px; line-height: 60px;">
                 <b>About</b>
                      
                 </h1>
              
             </v-img>
            </a>
            
          
              <v-img class="bg2" src="https://img.freepik.com/free-photo/abstract-smooth-empty-grey-studio-well-use-as-background-business-report-digital-website-template-backdrop_1258-55967.jpg" max-height="700">
                
                 
                 <h1 class=" center black--text text-center " style="font-size:50px; line-height: 60px;">
                   Features
                   
                 </h1>
                
                 <v-row>
                  <v-col>
                   <v-img class="image2 space-otto " src=" https://yukttovuejs.vrishanksofttech.com/yuktto-onepage/img/hero-banner.f7dbb7c6.png" alt="image" left="0%" right="0%" max-height="600" max-width="500">
        
                   </v-img>
                  </v-col>
                  <v-col>
                 
                    <i class="eva eva-lock-outline text-36"></i>
                    <h2 class="card-title pt-2 font-weight-medium black--text text-right" style="padding-top:100%;padding-right:20%;">
                      Data Safety
                    </h2>
                    <br/>
                    <p class="black--text text-right" style="padding-top:0%;padding-right:20%"> Data sharing has become top of mind for organizations reassessing their data strategy. The ability to distribute data effectively - both within an ecosystem and to external parties - represents a new and exciting value proposition. </p>
                 
                  </v-col>
                 </v-row>
                   
              </v-img>
                <v-img class="bg " src="https://img.freepik.com/free-photo/abstract-smooth-empty-grey-studio-well-use-as-background-business-report-digital-website-template-backdrop_1258-55967.jpg" max-height="600">
                  <h1 class="text-center black--text" style="font-size:50px; line-height: 60px;">Services us</h1>
                         <v-row>
                          <v-col class="col-sm-12 col-md-6">
                            <v-img src="https://yukttovuejs.vrishanksofttech.com/yuktto-multipage/img/services-img.f8f1590b.jpg" max-height="800" max-width="400">
                            </v-img>
                          </v-col>
                           <v-col >
                            <h2 class="black--text text-right" style="padding-right:20%; padding-top:10%">Somethings about Services.</h2>
                              <p class=" black--text text-right" style="padding-bottom:40%; padding-right:20%">Thanks to the commonwealth of Virginia, no matter where you live in the U.S., your documents can now be notarized online by a trusted notary.Thanks to the commonwealth of Virginia, no matter where you live in the U.S., your documents can now be notarized online by a trusted notary.</p>
                        
                           </v-col>
                         </v-row>
                   
               </v-img>
               <v-img class="bg2" src="https://img.freepik.com/free-photo/abstract-smooth-empty-grey-studio-well-use-as-background-business-report-digital-website-template-backdrop_1258-55967.jpg" max-height="700">
                <h1 class="text-center black--text" style="font-size:50px; line-height: 60px;">Contact us</h1>
                <h2  class="text-center title-txt" style=" font-size: 30px; line-height: 60px; color: #2E3D62">Become a part of Our bussiness community today</h2>
                    <v-row>
                      <v-col class="text-left">
                        <h1 class="  black--text text-left " font-weight="500" style="padding-left:20%;padding-top:45%;">How can we<br/>
                         Help?
                        </h1>
                        <br/>
                        <v-row justify='center'>
                          <a href="#" class="banner-one__btn" data-v-b5f60db0="">Contact Us</a>
                        </v-row>
              
                      </v-col>
                         <v-col>
                          
                              <v-img  max-height="800px" max-width="800px" src="https://intellipaat.com/blog/wp-content/uploads/2015/07/Big-Data.gif" class="ml-auto">
                               
                              </v-img>
                            
                        
                          </v-col>
                    </v-row>
              </v-img> 
             
              
  </v-container>    
</template>

<script >
  export default{
    name:"homepage",
    methods: {
    scrollToSection(sectionId) {
      this.$vuetify.goTo(sectionId);
    }
  }
  }
  
    

</script>








<style scoped>


.font-weight-bold {
  font-weight: 900 !important;
  font-size: "xxx-large";
}





.image {
  position: absolute; }

.space-otto {
  z-index: 2;
  top: 13.3%;
  left: 0%;
  width: 53%;
  animation: space-otto 8s ease-in-out infinite; }
  @media (max-width: 40em) {
    .space-otto {
      top: 8.3%;
      left: 7.5%;
      width: 60%; } }

@keyframes space-otto {
  0% {
    transform: translateY(0); }
  50% {
    transform: translateY(15px); }
  100% {
    transform: translateY(0); } }


.thirdpage image {
  position: absolute; }

.space-otto {
  z-index: 2;
  top: 5.3%;
  left: 0%;
  width: 53%;
  animation: space-otto 4s ease-in-out infinite; }
  @media (max-width: 40em) {
    .space-otto {
      top: 8.3%;
      left: 7.5%;
      width: 60%; } }

@keyframes space-otto {
  0% {
    transform: translateY(0); }
  50% {
    transform: translateY(15px); }
  100% {
    transform: translateY(0); } }
    .h1{
      font-weight:300;
    }


.eva {
  color: #47404f;
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

 .title-txt {
  font-size: 40px;
  font-weight: 600;
 }
.h1 p{
   
  line-height: 1.6;
  font-size: 15px;
  font-weight:500;
}

.h1{
  position: absolute;
  margin: 0;
  font-weight: bold;
  color: #2E3D62;
  font-size: 50px;
  line-height: 60px;
}
.banner-one__btn{
  display: inline-block;
  vertical-align: middle;
  border-radius: 32px;
  text-align: center;
  background-color: #FF8257;
  color: #FFFFFF;
  font-size: 16px;
  font-weight: 600;
  padding: 15px 59.5px;
  -webkit-transition: all .4s ease;
  transition: all .4s ease;
  -webkit-box-shadow: 0px 10px 30px 0px rgba(255, 130, 87, 0.3);
          box-shadow: 0px 10px 30px 0px rgba(255, 130, 87, 0.3);
}
.banner-one__btn:hover {
  background-color: #2e3d62;
  color: #fff;
  -webkit-box-shadow: 0px 10px 30px 0px rgba(46, 61, 98, 0.3);
          box-shadow: 0px 10px 30px 0px rgba(46, 61, 98, 0.3);
}
::selection {
 color:#2e3d62;
 background-color:black;
}
.h2{
  position: absolute;
  margin: 0;
  font-weight: bold;
  color: #2E3D62;
  font-size: 30px;
  line-height: 60px;
}


</style>