<template>
  <v-app>
    <v-content class="ct-back2">
      
    <!-- Header large screen -->
    <div id="ct-hiddenclass">
        <div class="header d-flex justify-space-between pa-10 white">
          <!-- header item 1 -->
          <div class="d-flex">
            <v-avatar height="100" width="100" class="hidden-sm-and-down">
              <img src="../assets/profileimg.png" alt="avatar" class="ct-primary pa-1">
            </v-avatar>

            <v-avatar height="80" width="80" class="hidden-md-and-up">
              <img src="../assets/profileimg.png" alt="avatar" class="ct-primary pa-1">
            </v-avatar>

            <div class="ml-10 ml-md-8 ml-sm-4">
              <div class="display-1 font-weight-bold ct-primary--text mb-2 hidden-md-and-down">Wilkerson Doe</div>
              <div class="headline font-weight-bold ct-primary--text mb-2 hidden-lg-and-up">Wilkerson Doe</div>
              <div class="body-2 ct-primary--text mb-6">Web Developer & UX Designer</div>
              <v-btn 
                large          
                class="text-capitalize header-btn">
                Hire me
              </v-btn>
            </div>
          </div>

        <!-- Header 2 item -->
          <div class="hidden-md-and-down">
          <v-card class="pa-4 d-flex align-center justify-space-between mr-12 ct-header-card py-10" id="square-it" min-width="400">
            <v-avatar height="50" width="50">
              <img src="../assets/dollar.png" alt="dollar">
            </v-avatar>
            <div class="text-center">
              <div class="caption">Hourly Rate</div>
              <div class="ct-primary--text title">$50 USD</div>
            </div>
            <v-avatar height="50" width="50">
              <img src="../assets/loadpre.png" alt="load">
            </v-avatar>
            <div class="text-center">
              <div class="caption">Weekly Availability</div>
              <div class="ct-primary--text title">15 Hours</div>
            </div>
          </v-card>
          </div>

          <!-- header 2 md screen -->
          <div class="hidden-lg-and-up">
          <v-card class="pa-2 d-flex align-center justify-space-around py-4" id="square-it" min-width="300">
            <v-avatar height="30" width="30">
              <img src="../assets/dollar.png" alt="dollar">
            </v-avatar>
            <div class="text-center">
              <div class="caption">Hourly Rate</div>
              <div class="ct-primary--text body-2 font-weight-bold">$50 USD</div>
            </div>
            <v-avatar height="30" width="30">
              <img src="../assets/loadpre.png" alt="load">
            </v-avatar>
            <div class="text-center">
              <div class="caption">Weekly Availability</div>
              <div class="ct-primary--text body-2 font-weight-bold">15 Hours</div>
            </div>
          </v-card>
          </div>
        
        <!-- Header 3 item -->
          <div class="text-right">
            <div class="ct-line"></div>
            
            <div class="d-flex mb-4">
              <v-avatar size="20" class="mr-2" style="margin-top: 4px" tile>
                <img src="../assets/icons/linkedin.png" alt="linkedin">
              </v-avatar>
                
              <v-avatar size="20" class="mr-2" tile style="margin-top: 4px">
                <img src="../assets/icons/dribble.png" alt="dribble" class="ct-icon">
              </v-avatar>

              <div class="px-1 ct-primary">
              <v-avatar size="18" tile>
                <img src="../assets/icons/twitter.png" alt="twitter" class="ct-icon">
              </v-avatar>
              </div>

              <v-avatar height="20" width="12" style="margin-top: 4px" tile>
                <img src="../assets/icons/facebook.png" alt="facebook" class="ct-icon facebook">
              </v-avatar>
            </div>

            <div class="flex justify-end mt-6">
              <img src="../assets/call.png" alt="call" class="add-img" >
              <img src="../assets/video.png" alt="video" class="add-img ml-2" >
            </div>
          </div>
        </div>
      </div>
      <!-- Header large screen end -->

      <!-- Header small screen-->
      <div class="smallscreenhead white">
        <div class="text-center py-5">
          <div class="d-flex justify-space-between">

            <v-avatar height="15" width="15" tile>
              <img src="../assets/menu.png" alt="avatar">
            </v-avatar>

            <div class="body-2 font-weight-bold mb-4">MY RESUME</div>

            <v-avatar height="15" width="15" tile>
              <img src="../assets/close.png" alt="avatar">
            </v-avatar>

          </div>
          

          <v-avatar height="110" width="110" class="mb-4">
            <img src="../assets/profileimg.png" alt="avatar" class="ct-primary pa-1">
          </v-avatar>

          <div class="headline font-weight-bold ct-primary--text mb-4">Wilkerson Doe</div>
          <div class="body-2 ct-primary--text mb-4">Web Developer & UX Designer</div>
          
           <div class="d-flex justify-center mb-4">
              <v-avatar size="20" class="mr-2" style="margin-top: 2px" tile>
                <img src="../assets/icons/linkedin.png" alt="linkedin">
              </v-avatar>
                
              <v-avatar size="20" class="mr-2" style="margin-top: 4px" tile>
                <img src="../assets/icons/dribble.png" alt="dribble" class="ct-icon">
              </v-avatar>

              <div class="px-1 ct-primary">
              <v-avatar size="16" tile>
                <img src="../assets/icons/twitter.png" alt="twitter" class="ct-icon">
              </v-avatar>
              </div>

              <v-avatar height="20" width="14" style="margin-top: 4px" tile>
                <img src="../assets/icons/facebook.png" alt="facebook" class="ct-icon facebook">
              </v-avatar>
            </div>

          <div class="d-flex justify-center">
             <div class="d-flex justify-space-between" style="width: 20rem">
                 <div class="d-flex align-center">
                   <div class="body-2 font-weight-regular ct-primary--text mr-5">Hourly</div>
                   <div class="body-1 font-weight-bold ct-primary--text">$50 USD</div>
                 </div>

                 <div class="d-flex align-center">
                   <div class="body-2 font-weight-regular ct-primary--text mr-5">Weekly</div>
                   <div class="body-1 font-weight-bold ct-primary--text">15 Hours</div>
                 </div>
             </div>
          </div>
        </div>
      </div>

      <!-- Header small screen-->

      <div class="ct-light">
         <v-tabs
            fixed-tabs
            center-active
            hide-slider
            show-arrows
          >
            <v-tab v-for="tab in tabs" @click="activeTab=tab.id"
              :key="tab.id" 
              :class="[
                activeTab == tab.id ? 'ct-active-tab' : '',
                activeTab < tab.id ? 'ct-tab-line' : ''
              ]"
              class="ct-tab text-capitalize px-12 ">
              {{ tab.title }}
            </v-tab>
          </v-tabs>
      </div>

      <!-- mobile tab view end -->
    <div class="scroll-content">
      <div class="container-2">
        <v-container>
           
           <!-- Porfolio -->

          <div v-if="activeTab==1" class="sb-nav-12">
            <div class="mt-5 font-weight-thin">
                <v-tabs centered color="#444444" background-color="#F8F8F8">
                  <v-tab class="text-capitalize">All</v-tab>
                  <v-tab class="text-capitalize">Mobile UI</v-tab>
                  <v-tab class="text-capitalize">Web UI</v-tab>
                  <v-tab class="text-capitalize">Logo</v-tab>
                  <v-tab class="text-capitalize">Illustrator</v-tab>
                </v-tabs>
            </div>

            <div class="text-center mt-10">
              <v-row>
                <v-col
                  v-for="n in 6"
                  :key="n"
                  cols="12"
                  sm="6"
                  md="6"
                  lg="4"
                >
                  <div class="ct-img-box" style="max-width: 23.1rem">
                    <v-img :src="getImgUrl(n)" 
                      max-height="300" max-width="370" 
                      min-height="270" min-width="270" 
                      aspect-ratio="1" class="ct-image">
                    </v-img>
                    <div class="text-center ct-buttom-tab py-2">
                      Lorem Ipsum Dolor
                    </div>
                  </div>
                </v-col>
              </v-row>
  
              <v-btn 
                large        
                class="text-capitalize header-btn mt-5">
                  View All
              </v-btn>
            </div>
          </div>

          <!-- Exp -->

          <div v-if="activeTab==2" class="mt-8">
            <v-row justify-center>
              <v-col cols="12" lg="6" md="6" sm="12" class="pa-lg-12 pa-md-8 pa-sm-4">
                 <v-timeline dense>
                    <v-timeline-item v-for="n in exp" :key="n.id"
                      fill-dot icon="mdi-check" color="#444444" class="pt-5 pb-5 ct-timeline-item" 
                    >
                    
                    <div class="hidden-sm-and-down">

                      <div>
                        <div>Joined as Web Developer</div>
                        <div class="body-2">Candy ice cream cake. Halvah gummi bears Cupcake</div>
                        <div class="caption">25 mins ago</div>
                      </div>

                    </div>

                    <div class="hidden-md-and-up">

                      <div v-if="cexp!=n.id" @click="cexp=n.id">
                        <div>Joined as Web Developer</div>
                        <div class="body-2">Candy ice cream cake. Halvah gummi bears Cupcake</div>
                        <div class="caption">25 mins ago</div>
                      </div>

                      <div class="pa-8 white" @click="cexp=n.id" v-if="cexp==n.id">
                          <div class="d-flex justify-space-between">
                            <div>
                              <div class="ct-primary--text ct-font2 mb-4">Joined as UI Designer</div>
                              <div class="px-8 ct-primary" style="height: 3px"></div>
                            </div>

                            <div>
                              <v-avatar height="60" width="60">
                                <img src="../assets/rlogo.png" alt="avatar">
                              </v-avatar>
                            </div>
                          </div>
                          
                          <p class="mt-5  body-2">
                            Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed
                         </p>

                         <div class="d-flex align-center mt-3">                   
                           <img src="../assets/Places.png" alt="avatar" style="width: 1.2rem">
                           <div class="body-2 ml-3">Baridhara, Dhaka, Bangladesh</div>
                        </div>
                        <div class="body-1 ct-primary--text font-weight-regular mt-4">2015 to 2017</div>

                      </div>

                    </div>
                    </v-timeline-item>
                  </v-timeline>
              </v-col>
              <v-col cols="12" md="6" sm="6" class="hidden-sm-and-down">
                 <div class="pa-xl-12 pa-lg-12 pa-md-10 pa-sm-8 pa-8 white ct-letter">
                    <v-avatar height="100" width="100">
                      <img src="../assets/rlogo.png" alt="avatar">
                    </v-avatar>

                    <div class="ct-primary--text ct-font mt-2">UI Designer</div>
                    <div class="ct-primary my-4" style="width: 7rem; height: 0.2rem;"></div>
                    <p class="mt-5  ct-para">
                      Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.
                    </p>

                    <div class="d-flex align-center mt-12">                   
                      <img src="../assets/Places.png" alt="avatar" style="width: 1.2rem">
                      <div class="body-2 ml-3">Baridhara, Dhaka, Bangladesh</div>
                    </div>
                    <div class="headline ct-primary--text font-weight-regular mt-8">2015 to 2017</div>
                 </div>
              </v-col>
            </v-row>
          </div>

          <!-- content 3 skills -->
          <div v-if="activeTab == 3" class="py-8 hidden-md-and-down">
            <div class="d-flex justify-center">
                <v-avatar v-for="skill in skills" :key="skill.id" min-width="150"
                  :class="[skill.id < skill.id - 1 ? '' : 'mr-12']"
                  height="150" width="150" class="white p-item">
                  <v-progress-circular
                    :size="120"
                    :width="15"
                    :value="skill.value"
                    color="#444444"
                  >
                    <div class="text-center">
                      <div class="p-child-val">{{ skill.value }}%</div>
                      <div class="progress-child">{{ skill.title }}</div>
                    </div>
                  </v-progress-circular>
                </v-avatar>
            </div>

            <!-- pointed box -->
            <div class="pointed-box pa-12 mt-12">
              <v-row class="px-10">
                <v-col
                  v-for="skill in subSkills" :key="skill.id"
                  cols="12" md="6" sm="6"
                >
                  <div>
                    <div class="sub-skill mb-3">{{ skill.title }}</div>
                    <div class="d-flex mb-3">
                      <div 
                        class="pa-2 mr-3" style="borderRadius: 2rem"
                        :class="[skill.value <= n ? 'grey lighten-2' : 'ct-primary']"
                        v-for="n in 10" :key="n">
                      </div>
                    </div>

                    <div class="caption">2 Years ago</div>
                  </div>
                </v-col>
              </v-row>
            </div>
          </div>

          <!-- content 3 skills small screen -->
          <div v-if="activeTab == 3" class="py-8 hidden-lg-and-up">
            <div class="d-flex justify-space-between">
                <v-avatar v-for="skill in skills" :key="skill.id" 
                  :class="[
                    skill.id < skill.id - 1 ? '' : '',
                    skill.id > 3 ? 'hidden-sm-and-down' : ''
                  ]"
                  height="105" width="105" class="white p-item">
                  <v-progress-circular
                    :size="90"
                    :width="10"
                    :value="skill.value"
                    color="#444444"
                  >
                    <div class="text-center">
                      <div class="p-child-val2">{{ skill.value }}%</div>
                      <div class="progress-child">{{ skill.title }}</div>
                    </div>
                  </v-progress-circular>
                </v-avatar>
            </div>

            <!-- pointed box small-->
            <div class="pointed-box2 py-8 mt-12">
              <v-row class="px-10">
                <v-col
                  v-for="skill in subSkills" :key="skill.id"
                  cols="12" md="6" sm="6"
                >
                  <div>
                    <div class="sub-skill mb-3">{{ skill.title }}</div>
                    <div class="d-flex mb-3">
                      <div 
                        class="mr-3" style="borderRadius: 2rem; padding: 8px"
                        :class="[skill.value <= n ? 'grey lighten-2' : 'ct-primary']"
                        v-for="n in 10" :key="n">
                      </div>
                    </div>

                    <div class="caption">2 Years ago</div>
                  </div>
                </v-col>
              </v-row>
            </div>
          </div>
          
          
          <!-- content 4 Education -->
          <div v-if="activeTab==4" class="mt-8">
            <v-row>
              <v-col cols="12" md="6" sm="12" class="pa-lg-12 pa-md-8 pa-sm-4">
                 <v-timeline dense>
                    <v-timeline-item v-for="n in edu" :key="n.id"
                      fill-dot icon="mdi-check" color="#444444" class="pt-5 pb-5 ct-timeline-item" 
                    >
                      <div class="hidden-sm-and-down">
                        <div>Completed A Level</div>
                        <div class="body-2">Candy ice cream cake. Halvah gummi bears Cupcake</div>
                        <div class="caption">25 mins ago</div>
                      </div>

                      <div class="hidden-md-and-up">

                      <div v-if="cedu!=n.id" @click="cedu=n.id">
                        <div>Completed Bsc</div>
                        <div class="body-2">Candy ice cream cake. Halvah gummi bears Cupcake</div>
                        <div class="caption">25 mins ago</div>
                      </div>

                      <div class="pa-2 white" @click="cedu=n.id" v-if="cedu==n.id">
                         <div class="pa-lg-12 pa-10">

                            <div class="d-flex justify-space-between">
                              <div>
                                <div class="ct-primary--text title font-weight-bold">Completed BSc</div>
                                <div class="ct-primary--text title font-weight-bold mt-2">Computer Science & Engineering</div>

                                <div class="d-flex align-center mt-2">                   
                                  <img src="../assets/Places.png" alt="avatar" style="width: 1.2rem">
                                  <div class="body-2 ml-3">Paderborn University, Paderborn, Germany</div>
                                </div>
                              </div>

                              <v-avatar height="70" width="50" tile>
                                <img src="../assets/medal.png" alt="avatar">
                              </v-avatar>
                            </div>

                            <div class="ct-primary my-6" style="width: 7rem; height: 0.2rem;"></div>
                            <p class="mt-5 mr-lg-10 body-2">
                              Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. 
                            </p>
                            
                            <div class="ct-primary--text body-2 font-weight-bold mt-8">CGPA 1.00 on German Grade</div>
                            <div class="body-1 ct-primary--text font-weight-regular mt-4">2015 to 2017</div>
                        </div>
                      </div>
                    </div>
                    </v-timeline-item>
                  </v-timeline>
              </v-col>

              <v-col cols="12" md="6" sm="12" class="hidden-sm-and-down">
                 <div class="pa-lg-12 pa-10 ct-letter-2">
                    <v-avatar height="100" width="75" tile>
                      <img src="../assets/medal.png" alt="avatar">
                    </v-avatar>

                    <div class="ct-primary--text headline font-weight-bold mt-5">BSc</div>
                    <div class="ct-primary--text title font-weight-bold mt-2">Computer Science & Engineering</div>

                    <div class="d-flex align-center mt-2">                   
                      <img src="../assets/Places.png" alt="avatar" style="width: 1.2rem">
                      <div class="body-2 ml-3">Paderborn University, Paderborn, Germany</div>
                    </div>

                    <div class="ct-primary my-6" style="width: 7rem; height: 0.2rem;"></div>
                    <p class="mt-5 mr-lg-10 ct-para">
                      Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.Lorem ipsum dolor sit amet,Stet clita kasd lorem ipsum dolor sit amet. sed diam  eirmod tempor dolore.
                    </p>
                     
                    <div class="ct-primary--text title font-weight-bold mt-8">CGPA 1.00 on German Grade</div>
                    <div class="title ct-primary--text font-weight-regular mt-4">2015 to 2017</div>
                 </div>
              </v-col>
            </v-row>
          </div>

          <!-- about section -->
          <div v-if="activeTab == 5">
              <v-row>
                <v-col cols="12" md="6" sm="6" class="pa-12 hidden-md-and-down">
                  <div class="d-flex justify-center">
                  <div class="pa-4 ">
              
                      <v-avatar height="250" width="250" class="ml-12">
                        <img src="../assets/profileimg.png" alt="avatar" class="ct-primary pa-2">
                      </v-avatar>

                      <div class="d-flex ml-12 mt-6">
                        <v-avatar height="100" width="100" class="ml-10 mr-5">
                          <img src="../assets/blankimg.png" alt="avatar" class="ct-primary pa-1">
                        </v-avatar>

                        <v-avatar height="70" width="70">
                          <img src="../assets/blankimg.png" alt="avatar" class="ct-primary pa-1">
                        </v-avatar>
                      </div>
                    </div>
                  </div>
                </v-col>

                <v-col cols="12" lg="6" md="12" sm="12" class="hidden-md-and-down">
                  <div class="pa-lg-12 pa-lg-12 pa-md-10 pa-sm-6 pa-4">
                    <div class="ct-primary--text title font-weight-bold mt-2">Objective</div>
                    <div class="body-2 font-weight-regular my-4">
                      I'm Creative Director and UI/UX Designer from New York, working in web development and print media. I enjoy turning complex problems into simple, beautiful and intuitive designs.
                    </div>

                    <div class="body-2 font-weight-regular">
                      My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add a personal touch to your product and make sure that it is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way.
                    </div>
                  </div>

                  <div class="px-12 hidden-sm-and-down">
                    <div class="ct-primary--text title font-weight-bold mt-2">Personal Details</div>
                    <div class="mt-4">
                      <div class="d-flex align-center mb-3">
                        <v-icon color="#444444">mdi-account</v-icon>
                        <div class="ml-3">Wilkerson Doe</div>
                      </div>

                      <div class="d-flex align-center mb-3">
                        <img src="../assets/Places.png" alt="avatar" style="width: 1.2rem" >
                        <div class="ml-4">Dhaka, Bangladesh</div>
                      </div>

                      <div class="d-flex align-center mb-2">
                        <v-icon color="#444444">@</v-icon>
                        <div class="ml-3">example@123.com</div>
                      </div>

                      <div class="d-flex justify-space-between align-center mb-3">
                          <div class="d-flex">
                            <v-icon color="#444444">mdi-phone</v-icon>
                            <div class="ml-3">+1234567890</div>
                          </div>

                          <v-btn 
                            large class="text-capitalize header-btn-dark">
                            View Resume
                          </v-btn>            
                      </div>
                    </div>
                  </div>    
                </v-col>
            </v-row>
             
            <div class="hidden-lg-and-up tab-screen-ve121">
              <div class="pa-lg-12 pa-lg-12 pa-md-10 pa-sm-6 pa-4">
                    <div class="ct-primary--text title font-weight-bold mt-2">Objective</div>
                    <div class="body-2 font-weight-regular my-4">
                      I'm Creative Director and UI/UX Designer from New York, working in web development and print media. I enjoy turning complex problems into simple, beautiful and intuitive designs.
                    </div>

                    <div class="body-2 font-weight-regular">
                      My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add a personal touch to your product and make sure that it is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way.
                    </div>
                  </div>
 
            <v-row>
              <v-col cols="12" md="6" sm="6">
                <div class="pa-4 text-center">
                    <v-avatar height="250" width="250">
                      <img src="../assets/profileimg.png" alt="avatar" class="ct-primary pa-2">
                    </v-avatar>

                    <div class="d-flex ml-12 mt-6">
                      <v-avatar height="100" width="100" class="ml-10 mr-5">
                        <img src="../assets/blankimg.png" alt="avatar" class="ct-primary pa-1">
                      </v-avatar>

                      <v-avatar height="70" width="70">
                        <img src="../assets/blankimg.png" alt="avatar" class="ct-primary pa-1">
                      </v-avatar>
                    </div>
                </div>
              </v-col>
              <v-col cols="12" md="6" sm="6" class="d-flex align-center">
                  <div class="px-12">
                    <div class="ct-primary--text title font-weight-bold mt-2">Personal Details</div>
                    <div class="mt-4">
                      <div class="d-flex align-center mb-4">
                        <v-icon color="#444444">mdi-account</v-icon>
                        <div class="ml-3">Wilkerson Doe</div>
                      </div>

                      <div class="d-flex align-center mb-4">
                        <img src="../assets/Places.png" alt="avatar" style="width: 1.2rem" >
                        <div class="ml-4">Dhaka, Bangladesh</div>
                      </div>

                      <div class="d-flex align-center mb-4">
                        <v-icon color="#444444">@</v-icon>
                        <div class="ml-3">example@123.com</div>
                      </div>

                      <div class="d-flex mb-12">
                        <v-icon color="#444444">mdi-phone</v-icon>
                        <div class="ml-3">+1234567890</div>
                      </div>

                      <v-btn 
                        large class="text-capitalize header-btn-dark">
                        View Resume
                      </v-btn>    
                    </div>
                  </div>    
              </v-col>
            </v-row>
            </div>
          </div>

          
        </v-container>
        </div>


        <v-container class="last-element mb-8 pa-8 ct-back2" v-if="activeTab==5">
          <div class="ct-primary--text title font-weight-bold mt-2">Objective</div>
                    <div class="body-2 font-weight-regular my-4">
                      I'm Creative Director and UI/UX Designer from New York, working in web development and print media. I enjoy turning complex problems into simple, beautiful and intuitive designs.
                    </div>

                    <div class="body-2 font-weight-regular">
                      My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add a personal touch to your product and make sure that it is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way.
                    </div>
        </v-container>

        <div class="wrapper last-element ct-back2" v-if="activeTab==5">
          

          <div class="text-center d-flex align-center ct-back2">
            <v-avatar height="100" width="100" class="ml-sm-10 ml-4 hidden-xs-and-down">
              <img src="../assets/profileimg.png" alt="avatar" class="ct-primary pa-1">
            </v-avatar>
          </div>

          <div class="pa-6 pr-4 ct-mob-about ct-primary">
             <div>
                  <div class="white--text body-1 font-weight-bold mb-5">Personal Details</div>                   
                    <div class="d-flex align-center mb-3">
                      <img src="../assets/bicon/profile.png" alt="avatar" class="info-pic">
                      <div class="ml-4 white--text info-text">Wilkerson Doe</div>
                    </div>

                    <div class="d-flex align-center mb-3">
                      <img src="../assets/bicon/add.png" alt="avatar" class="info-pic">
                      <div class="ml-4 white--text info-text">Dhaka, Bangladesh</div>
                  </div>

                  <div class="d-flex align-center mb-3">
                    <img src="../assets/bicon/email.png" alt="avatar" class="info-pic">
                    <div class="ml-4 white--text info-text">example@123.com</div>
                  </div>

                  <div class="d-flex justify-space-between">
                    <div class="d-flex align-center">
                      <img src="../assets/bicon/call.png" alt="avatar" class="info-pic">
                      <div class="ml-4 white--text info-text" >+123458115</div>
                    </div>                   
                    <button class="ct-button">View Resume</button>
                  </div>
                </div>
          </div>
        </div>


        <v-container class="last-element">
          <div class="d-flex justify-space-between align-center mb-4">
            <div class="d-flex align-center">
              <img src="../assets/call.png" alt="call" class="add-img2" >
              <img src="../assets/video.png" alt="video" class="add-img2 ml-2" >
            </div>

              <v-btn           
                class="text-capitalize header-btn">
                Hire me
              </v-btn>
          </div>
        </v-container>
      </div>
    </v-content>
  </v-app>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      activeTab: 1,
      cexp: 1,
      cedu: 1,
      tabs: [
        { id: 1, title: "Portfolio" },
        { id: 2, title: "Experience" },
        { id: 3, title: "Skills" },
        { id: 4, title: "Education" },
        { id: 5, title: "About" }
      ],
      skills: [
        { id: 1, title: 'FRONTEND', value: 50 },
        { id: 2, title: 'DESIGN', value: 75 },
        { id: 3, title: 'WEB DEV', value: 20 },
        { id: 4, title: 'APP DEV', value: 50 },
        { id: 5, title: 'ANALYTICAL', value: 50 }
      ], 
      skills2: [
        { id: 1, title: 'FRONTEND', value: 50 },
        { id: 2, title: 'DESIGN', value: 75 },
        { id: 3, title: 'WEB DEV', value: 20 }
      ],
      subSkills: [
        { id: 1, title: 'HTML', value: 7 },
        { id: 2, title: 'CSS', value: 8 },
        { id: 3, title: 'JQUERY', value: 5 },
        { id: 3, title: 'BOOTSTRAP', value: 10 }
      ],
      exp: [
        {id: 1 }, {id: 2 }, {id: 3 }, {id: 4 }, {id: 5 }, {id: 6 }, {id: 7 }
      ],
      edu: [
        {id: 1 }, {id: 2 }, {id: 3 }, {id: 4 }, {id: 5 }, {id: 6 }, {id: 7 }
      ]
    }),

    methods: {
        getImgUrl(id) {
           let image = require.context('../assets/portfolio', false, /\.png$/)
           return image('./' + id + ".png")
        }
    }
  }
</script>

<style>
/* Global style */
.ct-primary { background-color: #444444 }
.ct-primary--text { color: #444444 };
.ct-light { background-color: #F8F8F8 }
.ct-back2 { background-color: #F8F8F8 !important;}

#square-it {
  border-radius: 0;
    box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
}

#square-it22 {
  border-radius: 0;
}

/* Global style end */


/* Header styles */

.header-btn {
  border-radius: 0;
  border: solid 2px #444444;
  background-color: white !important;
}

.header-btn-dark {
  border-radius: 0;
  color: white !important; 
  font-size: 1rem;
  font-weight: 300;
  background-color: #444444 !important;
}

.ct-header-card {
  transform: translateX(-3.5rem);
}

.ct-line {
  height: 2px;
  width: 7.4rem;
  background-color: #444444;
}

.ct-icon .facebook {
  height: 1rem;
  width: 2rem;
}

.add-img {
  height: 4rem;
  width: auto;
}

.add-img2 {
  height: 3rem;
  width: auto;
}

/* small header style */
.make-center {
  margin: 0 auto;
}

/* Header styles end */

/* tab style start */
.ct-tab {
  font-size: 1rem !important;
  font-weight: 400 !important;
  transition: 0.2s;
}

.ct-active-tab {
  background-color: #444444;
  color: white !important;
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
}

.ct-tab-line {
  border-bottom: solid #d1d1d1 2px;
}

/* small tab settings */


/* contents style */

.container-2 {
  background-color: #F8F8F8;
}

/* content style 1  */
.ct-img-box {
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
  margin: 0 auto;
}

.ct-buttom-tab {
  border-bottom: solid 2px #444444;
  background-color: white;
}

.ct-col-item {
  margin: 0 auto;
}
/* content style 2 */

/* left */
.ct-timeline-item {
  transition: 0.2s;
  cursor: pointer;
}

/* right */
.ct-font {
  font-size: 2rem;
  font-weight: 600;
  font-family: 'Times New Roman', Times, serif;
}

.ct-font2 {
  font-size: 1.2rem;
  font-weight: 600;
  font-family: 'Times New Roman', Times, serif;
}

.ct-para {
  line-height: 1.6;
  font-size: 1rem;
  font-weight: 300;
}

.ct-letter {
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
}

.ct-letter-2 {
  background-color: white;
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
  border-bottom: solid 2px #444444;
}

/* content style 3 */
.p-item {
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
}

.p-child-val {
  font-size: 1.6rem;
  font-weight: 600;
  font-family: 'Times New Roman', Times, serif;
  color: #444444;
}

.p-child-val2 {
  font-size: 1rem;
  font-weight: 600;
  font-family: 'Times New Roman', Times, serif;
  color: #444444;
}

.progress-child {
  font-size: 0.7rem;
  color: #444444;
}

.pointed-box {
  max-width: 60rem;
  margin: 0 auto;
  position: relative;
  background-color: white;
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
  border-bottom: solid 4px #444444;
}

.pointed-box::before {
  position: absolute;
  width: 3rem;
  height: 3rem;
  background-color: white;
  transform: rotate(45deg);
  top: -1.5rem;
  left: 2.5rem;
  content: ''
}

/* same style 2 */
.pointed-box2 {
  max-width: 60rem;
  margin: 0 auto;
  position: relative;
  background-color: white;
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
  border-bottom: solid 4px #444444;
}

.pointed-box2::before {
  position: absolute;
  width: 3rem;
  height: 3rem;
  background-color: white;
  transform: rotate(45deg);
  top: -1.5rem;
  left: 1.8rem;
  content: ''
}

.sub-skill {
  font-size: 1rem;
  font-weight: 800;
  font-family: sans-serif;
}

.ct-box-about {
  border-top-left-radius: 8px;
  border-bottom-left-radius: 8px;
}

@media only screen and (max-width: 1000px) {
  .ct-box-about {
    width: 30rem;
  }

  .info-pic {
    width: 0.9rem;
  }

  .info-text {
    font-size: 0.9rem;
  }

  .pic-cont-1 {
    display: inline;
  }

}

@media only screen and (max-width: 600px) {
  .ct-box-about {
    width: 20rem;
  }

  .info-pic {
    width: 0.8rem;
  }

  .pic-cont-1 {
    display: none;
  }

  .info-text {
    font-size: 0.8rem;
  }
}

@media only screen and (max-width: 400px) {
  .ct-box-about {
    width: 13rem;
  }

  .info-pic {
    width: 0.8rem;
  }

  .pic-cont-1 {
    display: none;
  }

  .info-text {
    font-size: 0.8rem;
  }
}


/* responsive style */
#ct-hiddenclass {
  display: block;
}


@media only screen and (max-width: 835px) {

   #ct-hiddenclass {
    display: none !important;
  }
  
}

.smallscreenhead {
  display: none;
}

.res-style-tab {
  display: block;
}


@media only screen and (max-width: 835px) {

  #ct-hiddenclass {
    display: none !important;
  }

  .smallscreenhead {
    display: block;
  }
}

.small-size-tab {
  display: none;
}

@media only screen and (max-width: 910px) {

  .res-style-tab {
    display: none;
  }

  .small-size-tab {
    font-weight: 400;
    color: rgb(117, 116, 116);
    cursor: pointer;
    display: block;
  }
}

.mobile-tab-view {
  overflow: auto;
  white-space: nowrap;
  display: none;
  background-color: white;
}

  .tab-screen-ve121 {
    display: block;
  }

.last-element {
    display: none !important;
  }

@media only screen and (max-width: 835px) {

  .res-style-tab {
    display: none;
  }

  .small-size-tab {
    display: none;
  }

  .mobile-tab-view {
    display: block;
  }

  .tab-screen-ve121 {
    display: none;
  }

  .last-element {
    display: grid !important;
  }

  .ct-tab {
    width: 33.33vw !important;
  }

}

.mobile-tab-view::-webkit-scrollbar {
  display: none;
}

/* Hide scrollbar for IE and Edge */
.mobile-tab-view {
  -ms-overflow-style: none;
}

.item-tab {
  cursor: pointer;
  text-align: center;
  height: 2rem;
  font-size: 1rem;
  width: 33.333333vw;
  border-block-end: solid 1.5px rgba(0,0,0,.15);
  display: inline-block;
}

/* about secton small screen */
.wrapper {
  display: grid;
  grid-template-columns: 35% 65%;
}

.ct-mob-about {
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px;
}

.ct-button {
  background-color: white;
  border: none;
  color: #444444;
  padding: 4px 8px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 10px;
  cursor: pointer;
}


@media only screen and (min-width: 1200px) {

  .scroll-content {
    height: 100%;
    overflow-y: scroll;
    -ms-overflow-style: none;
    padding-bottom: 20rem;
  }

  .ct-back2 {
    height: 100vh !important;
    overflow: hidden;
  }

.scroll-content::-webkit-scrollbar { width: 0 !important }
.scroll-content { overflow: -moz-scrollbars-none; }

.scroll-content::-webkit-scrollbar {
  display: none;
}

}

.v-slide-group.v-item-group > .v-slide-group__next, .v-slide-group.v-item-group > .v-slide-group__prev {
  display: none !important
}

.v-slide-group.v-item-group > .v-slide-group__next, .v-slide-group.v-item-group > .v-slide-group__prev {
   display: none !important
}

@media only screen and (min-width: 961px) {

  .ct-timeline-item:hover {
    background-color: white; 
    box-shadow: 0 .5rem 1rem rgba(0,0,0,.15);
    transform: scale(1.05);
  }

}

</style>