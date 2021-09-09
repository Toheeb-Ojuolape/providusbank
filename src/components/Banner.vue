<template>
  <v-main>
    <!--Laptop-->
    <v-container class="hidden-md-and-down">
      <v-sheet style="margin:9px 3px 19px 0px;z-index:21">
        <v-row>
          <v-col>
            <v-img
              width="100px"
              height="39px"
              src="../assets/providus-bank-login-logo.png"
              style="z-index:21"
            />
          </v-col>

          <v-col>
            <div style="z-index:21" class="hidden-md-and-down">
              <router-link
                to="/"
                color="black"
                class="menuLink"
                active-class="active"
                >Home</router-link
              >
              <a href="#features" class="menuLink">Features</a>
              <a href="https://swiftend.stoplight.io/docs/public-api/YXBpOjIwNDYxMzc4-swiftend-api" class="menuLink"
                >Documentation</a
              >
              <v-btn
                outlined
                class="hoverEffect"
                width="100px"
                height="40px"
                rounded
                color="#fdb913"
                style="margin-left:30px"
                href="http://swiftend-providusbank.herokuapp.com/"
                >Sign in</v-btn
              >
            </div>
            <v-btn
              class="hidden-lg-and-up"
              style="float:right"
              color="#F5BA43"
              text
              @click.stop="drawer = !drawer"
              ><v-icon>mdi-menu</v-icon></v-btn
            >
          </v-col>
        </v-row>
      </v-sheet>
    </v-container>

    <!--Phone-->
    <v-container class="hidden-lg-and-up">
      <v-sheet style="margin:9px 3px 19px 0px;z-index:21">
        <v-row>
          <v-col>
            <v-img
              width="100px"
              height="39px"
              src="../assets/providus-bank-login-logo.png"
            />
          </v-col>

          <v-col>
            <v-btn
              rounded
              outlined
              color="#fdb913"
              class="hoverEffect"
              style="float:right"
            >
              Sign in
            </v-btn>
            <v-btn
              class="hidden-lg-and-up"
              style="float:right"
              color="#F5BA43"
              text
              @click.stop="drawer = !drawer"
              ><v-icon>mdi-menu</v-icon></v-btn
            >
          </v-col>
        </v-row>
      </v-sheet>
    </v-container>

    <!--Laptop-->
    <v-card class="hidden-md-and-down createAccount" height="700px" flat tile>
      <v-row>
        <v-col style="width:60%">
          <div style="margin:30px 70px 50px 70px">
            <h1
              class="hidden-md-and-down"
              style="text-align:start;z-index:10;color:#374b54;margin-top:150px;margin-bottom:10px;font-size:48px"
            >
              Banking As a Service
            </h1>
            <p style="width:50%;text-align:start;z-index:10;color:#374b54;font-size:22px">
              Our vision is to collaboratively provide the underlying banking
              services infrastructure to fintechs and innovators in order to
              deliver best in class user experiences and target the next
              generation bank customers.
            </p>
            <v-btn
              height="59px"
              width="270px"
              x-large 
              color="#fdb913"
              class="black--text mt-2 font-weight-bold"
              href="http://swiftend-providusbank.herokuapp.com/"
              style="float:left;border-radius:15px"
              >Start Here <v-icon>mdi-chevron-right</v-icon></v-btn
            >
          </div>
        </v-col>
      </v-row>
    </v-card>

    <!--Phone-->
    <v-card
      class="pt-8 hidden-lg-and-up createAccount"
      width="100%"
      height="700px"
      flat
      tile
    >
      <div style="padding:80px 40px 50px 40px">
        <h1
          class="text-center font-weight-bold"
          style="color:#374b54;margin-bottom:30px;font-size:35px"
        >
          Banking As A Service
        </h1>
        <p class="text-center" style="margin:auto;color:#374b54;font-size:16px">
         Our vision is to collaboratively provide the underlying banking
              services infrastructure to fintechs and innovators in order to
              deliver best in class user experiences and target the next
              generation bank customers.
        </p>
      </div>

      <p style="margin:0px 0px 30px 0px;padding:0px" class="text-center">
        <v-btn
          height="59px"
          width="270px"
          color="#fdb913"
          x-large
         href="http://swiftend-providusbank.herokuapp.com/"
          style="border-radius:15px"
          class="hidden-lg-and-up text-center"
          >Start Here <v-icon>mdi-chevron-right</v-icon></v-btn
        >
      </p>
    </v-card>


    <v-card color="#374b54" class="pa-12 text-center" flat tile>
    <div style="padding:30px 0px 30px 0px">
    <h1 style="color:white;font-size:43px" class="font-weight-bold"> All the APIs You need</h1>
    <p style="margin-top:8px;color:white">Are you a fintech, developer or even an incumbent trying to do something new and novel? <br>We want to collaborate with you, not compete.</p>
    </div>
    
    </v-card>

    <v-navigation-drawer
      v-if="drawer == true"
      v-model="drawer"
      absolute
      right
      temporary
    >
      <v-list nav dense>
        <v-list-item-group
          v-model="group"
          active-class="deep-orange--text text--accent-4"
        >
          <v-list-item to="/" active-class="active">
            <v-list-item-title>
              <a class="active">
                Home
              </a>
            </v-list-item-title>
          </v-list-item>

          <v-list-item href="#features">
            <v-list-item-title>Features</v-list-item-title>
          </v-list-item>

          <v-list-item href="https://swiftend.stoplight.io/docs/public-api/YXBpOjIwNDYxMzc4-swiftend-api">
            <v-list-item-title>Documentation</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
    <!-- <v-img style="top:-10;left:0;position:fixed" src="../../assets/Group.svg"/> -->
  </v-main>
</template>

<script>
export default {
  name: "Banner",
  data() {
    return {
      drawer: false,
    };
  },
};
</script>

<style>
.menuLink {
  text-decoration: none;
  color: black !important;
  margin-left: 59px;
}

.menuLink:hover {
  border-bottom: solid 2px #fdb913;
  color: #fdb913 !important;
}

.active {
  border-bottom: solid 2px #fdb913;
  color: #fdb913 !important;
}

.createAccount {
  background-image: url("../assets/globe.png");
  background-position: center;
  background-size: cover;
}

.hoverEffect:hover {
  background: #fdb913 !important;
  border: #fdb913;
  color: black !important;
}

.v-btn {
  text-transform: none !important;
}
</style>
