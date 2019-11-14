<template>
  <section
    id="welcome"
    class="hide-overflow"
  >
    <v-layout>
      <v-flex
        hidden-sm-and-down
        md6
      >
        <v-img
          src="https://i0.wp.com/kucing.co.id/wp-content/uploads/2018/12/Kucing-Betina-PUTIH.jpg?fit=788%2C403&ssl=1"
          height="100vh"
        />
      </v-flex>

      <v-flex
        xs12
        md6
        align-content-space-between
        layout
        :pa-5="$vuetify.breakpoint.smAndDown"
        wrap
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateY(25%)"
        />

        <v-layout
          align-center
          justify-center
        >
          <v-flex
            xs10
            md6
          >
            <base-heading><h1>Welcome!</h1></base-heading>
            <br>
            <base-text>
            <p style="text-align:justify">
              
            </p>
            </base-text>
            <base-btn class="mt-4">
                <v-btn rounded color="primary" dark router to="/user">Get In</v-btn>
            </base-btn>
          </v-flex>
        </v-layout>

        <base-bubble-2
          style="transform: rotate(180deg) translate(-200px, -15%)"
        />
      </v-flex>
    </v-layout>
  </section>
</template>