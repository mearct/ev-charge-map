<template>
  <q-page id="registrationPage">

    <q-toolbar class="bg-teal-9 text-white">
        <q-toolbar-title> Register </q-toolbar-title>
    </q-toolbar>

    <q-scroll-area class="form-style">
      <div class="text-h6 text-center q-mt-md">
        <q-img src="favicon.ico" height="60px" width="60px" />
        <div>Ev Charge Map</div>
      </div>

      <div class="q-pa-md q-gutter-md">
        <div class="text-center"> Register and get extra features! </div>

        <q-input outlined stack-label label="First Name">
          <template v-slot:append >
            <q-icon name="close" />
          </template>
        </q-input>

        <q-input outlined stack-label label="Last Name">
          <template v-slot:append >
            <q-icon name="close" />
          </template>
        </q-input>

        <q-input outlined stack-label label="Email">
          <template v-slot:append >
            <q-icon name="close" />
          </template>
        </q-input>

        <q-input outlined stack-label label="Password">
          <template v-slot:append >
            <q-icon name="close" />
          </template>
        </q-input>

        <q-input outlined stack-label label="Confirm Password">
          <template v-slot:append >
            <q-icon name="close" />
          </template>
        </q-input>

        <div>
          <q-btn color="black" size="lg"  class="full-width" label="Register" />
        </div>
      </div>
    </q-scroll-area>
  </q-page>
</template>

<script setup> </script>

<style lang="scss">
  #registrationPage {
    .form-style {
      margin: 0 auto;
      height: 800px;
      max-width: 500px;
    }
  }
</style>
