<template>
  <v-main>
    <v-card tile height="480px" style="text-align:start" color="#374b54" flat>
      <!--Laptop-->
      <v-container class="hidden-md-and-down pa-6">
        <v-row>
          <v-col style="margin-top:40px">

            <p
              style="font-size:20px;margin:0px;padding:0px"
              class="mt-9 mb-3 font-weight-medium white--text"
            >
             Ready to get started? Sign in
            </p>
                <v-btn
                  color="#ff9d00"
                  rounded
                  width="300px"
                  x-large
                  height="55px"
                  class="white--text"
                  href="http://swiftend-providusbank.herokuapp.com/"
                  >Get Started</v-btn
                >
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
              <a
                style="text-decoration:none;color:white"
                href="https://providusbank.com/about"
                >About Providus Bank</a
              >
            </div>
            <div>
              <a
                style="text-decoration:none;color:white"
                href="https://account.providusbank.com/"
                >Open An Account</a
              >
            </div>
            <div style="margin-top:30px">
              <v-btn x-small class="mr-2" color="#ff9d00" href="https://www.instagram.com/providusbankig" depressed fab
                ><v-icon color="#374b54">mdi-instagram</v-icon></v-btn
              >
              <v-btn x-small class="mr-2" color="#ff9d00" href="https://web.facebook.com/ProvidusBank" depressed fab
                ><v-icon color="#374b54">mdi-facebook</v-icon></v-btn
              >
              <v-btn color="#ff9d00" href="https://twitter.com/providusbank" x-small class="mr-2" depressed fab
                ><v-icon color="#374b54">mdi-twitter</v-icon></v-btn
              >
              <v-btn color="#ff9d00" href="https://www.linkedin.com/company/providusbank/" x-small depressed fab
                ><v-icon color="#374b54">mdi-linkedin</v-icon></v-btn
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
              style="font-size:20px;margin:0px;padding:0px"
              class="mt-9 mb-3 font-weight-medium white--text"
            >
             Ready to get started? Sign in
            </p>
                <v-btn
                  color="#ff9d00"
                  rounded
                  width="300px"
                  x-large
                  height="55px"
                  class="white--text"
                  href="http://swiftend-providusbank.herokuapp.com/"
                  >Get Started</v-btn
                >
          </v-col>
          </v-row>
          <v-row>
          <v-col style="margin-right:-400px;margin-top:30px">
            <p class="font-weight-medium" style="font-size:21px;color:#F5BA43">
              View More
            </p>
            <div>
              <a
                style="text-decoration:none;color:white"
                href="https://swiftend.stoplight.io/docs/public-api/YXBpOjIwNDYxMzc4-swiftend-api"
                >Documentation</a
              >
            </div>
            <div>
              <a
                style="text-decoration:none;color:white"
                href="#features"
                >Features</a
              >
            </div>
            <div>
              <a
                style="text-decoration:none;color:white"
                href="https://providusbank.com/about"
                >About Providus Bank</a
              >
            </div>
            <div>
              <a
                style="text-decoration:none;color:white"
                href="https://account.providusbank.com/"
                >Open An Account</a
              >
            </div>
            <div style="margin-top:30px">
              <v-btn x-small class="mr-2" href="https://www.instagram.com/providusbankig" depressed fab
                ><v-icon color="#ff9d00">mdi-instagram</v-icon></v-btn
              >
              <v-btn x-small class="mr-2" href="https://web.facebook.com/ProvidusBank" depressed fab
                ><v-icon color="#ff9d00">mdi-facebook</v-icon></v-btn
              >
              <v-btn color="white" x-small class="mr-2" href="https://twitter.com/providusbank" depressed fab
                ><v-icon color="#ff9d00">mdi-twitter</v-icon></v-btn
              >
              <v-btn color="white" href="https://www.linkedin.com/company/providusbank/" x-small depressed fab
                ><v-icon color="#ff9d00">mdi-linkedin</v-icon></v-btn
              >
            </div>
          </v-col>
        </v-row>
      </v-container>
    </v-card>
  </v-main>
</template>
