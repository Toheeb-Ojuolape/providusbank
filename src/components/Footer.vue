<template>
  <v-main>
    <v-card tile height="400px" style="text-align:start" color="#fdb913" flat>
      <!--Laptop-->
      <v-container class="hidden-md-and-down pa-6">
        <v-row>
          <v-col style="margin-top:40px">

            <p
              style="margin:0px;padding:0px"
              class="mt-9 font-weight-medium white--text"
            >
             Ready to get started? Sign in
            </p>
            <v-row no-gutters>
              <v-col>
                <v-text-field
                  outlined
                  single-line
                  style="border-radius:10px 0px 0px 10px;background:white;height:55px"
                  label="Enter your email address"
                />
              </v-col>
              <v-col>
                <v-btn
                  color="black"
                  style="border-radius:0px 10px 10px 0px"
                  x-large
                  height="55px"
                  class="white--text"
                  >Subscribe</v-btn
                >
              </v-col>
            </v-row>
          </v-col>

          <v-col style="margin-right:-400px;margin-top:30px">
            <p class="font-weight-medium" style="font-size:21px;color:#F5BA43">
              View More
            </p>
            <div>
              <a
               href="https://swiftend.stoplight.io/docs/public-api/YXBpOjIwNDYxMzc4-swiftend-api"
                style="text-decoration:none;color:white"
                to="/terms-of-service"
                >Documentation</a
              >
            </div>
            <div>
              <a
                href="#features"
                style="text-decoration:none;color:white"
                to="/terms-of-service"
                >Features</a
              >
            </div>
            <div>
              <router-link
                style="text-decoration:none;color:white"
                to="/terms-of-service"
                >Customer service</router-link
              >
            </div>
            <div>
              <router-link
                style="text-decoration:none;color:white"
                to="/terms-of-service"
                >How to trade</router-link
              >
            </div>
            <div style="margin-top:30px">
              <v-btn x-small class="mr-2" depressed fab
                ><v-icon color="black">mdi-instagram</v-icon></v-btn
              >
              <v-btn x-small class="mr-2" depressed fab
                ><v-icon color="black">mdi-facebook</v-icon></v-btn
              >
              <v-btn color="white" x-small class="mr-2" depressed fab
                ><v-icon color="black">mdi-twitter</v-icon></v-btn
              >
              <v-btn color="white" x-small depressed fab
                ><v-icon color="black">mdi-linkedin</v-icon></v-btn
              >
            </div>
          </v-col>
        </v-row>
      </v-container>

      <!--Phone-->
      <v-container class="pa-4 hidden-lg-and-up">
        <v-row>
          <v-col style="margin-top:40px">
            <p
              style="margin:0px;padding:0px"
              class="mt-9 font-weight-medium white--text"
            >
              Get latest deals and discounts
            </p>
            <v-row no-gutters>
              <v-col>
                <v-text-field
                  outlined
                  single-line
                  style="border-radius:10px 0px 0px 10px;background:white;height:55px"
                  label="Enter your email address"
                />
              </v-col>
              <v-col>
                <v-btn
                  color="black"
                  style="border-radius:0px 10px 10px 0px"
                  x-large
                  height="55px"
                  class="white--text"
                  >Subscribe</v-btn
                >
              </v-col>
            </v-row>
          </v-col>
          </v-row>
          <v-row>
          <v-col style="margin-right:-400px;margin-top:30px">
            <p class="font-weight-medium" style="font-size:21px;color:#F5BA43">
              View More
            </p>
            <div>
              <router-link
                style="text-decoration:none;color:white"
                to="/terms-of-service"
                >FAQs</router-link
              >
            </div>
            <div>
              <router-link
                style="text-decoration:none;color:white"
                to="/terms-of-service"
                >Terms and Policy</router-link
              >
            </div>
            <div>
              <router-link
                style="text-decoration:none;color:white"
                to="/terms-of-service"
                >Customer service</router-link
              >
            </div>
            <div>
              <router-link
                style="text-decoration:none;color:white"
                to="/terms-of-service"
                >How to trade</router-link
              >
            </div>
            <div style="margin-top:30px">
              <v-btn x-small class="mr-2" href="https://www.instagram.com/duffle.ng/" depressed fab
                ><v-icon color="black">mdi-instagram</v-icon></v-btn
              >
              <v-btn x-small class="mr-2" depressed fab
                ><v-icon color="black">mdi-facebook</v-icon></v-btn
              >
              <v-btn color="white" x-small class="mr-2" depressed fab
                ><v-icon color="black">mdi-twitter</v-icon></v-btn
              >
              <v-btn color="white" x-small depressed fab
                ><v-icon color="black">mdi-linkedin</v-icon></v-btn
              >
            </div>
          </v-col>
        </v-row>
      </v-container>
    </v-card>
  </v-main>
</template>
