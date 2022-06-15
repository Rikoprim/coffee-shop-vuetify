<template>
  <v-row justify="center">
    <v-col cols="12" md="2">
      <v-item v-slot="{ active, toggle }">
        <v-card
          :color="active ? '#F6EFEF' : 'white'"
          :class="active ? 'borderme' : 'borderout'"
          class="f-flex align-center rounded-lg mx-2"
          dark
          height="140"
          @click="toggle"
        >
          <v-row>
            <v-col cols="12" sm="12">
              <v-list-item three-line class="text-center">
                <v-list-item-content>
                  <div align="center" justify="center">
                    <v-img
                      src="c1.png"
                      max-width="110"
                      max-height="110"
                      contain
                    >
                    </v-img>
                  </div>
                  <v-list-item-subtitle
                    :class="active ? 'brown--text' : 'black--text'"
                    class="caaption mt-4"
                  >
                    All
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>
        </v-card>
      </v-item>
    </v-col>

    <v-col cols="12" md="2">
      <v-item v-slot="{ active, toggle }">
        <v-card
          :color="active ? '#F6EFEF' : 'white'"
          :class="active ? 'borderme' : 'borderout'"
          class="f-flex align-center rounded-lg mx-2"
          dark
          height="140"
          @click="toggle"
        >
          <v-row>
            <v-col cols="12" sm="12">
              <v-list-item three-line class="text-center">
                <v-list-item-content>
                  <div align="center" justify="center">
                    <v-img src="c2.png" max-width="90" max-height="90" contain>
                    </v-img>
                  </div>
                  <v-list-item-subtitle
                    :class="active ? 'brown--text' : 'black--text'"
                    class="caaption mt-4"
                  >
                    Coffee
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>
        </v-card>
      </v-item>
    </v-col>

    <v-col cols="12" md="2">
      <v-item v-slot="{ active, toggle }">
        <v-card
          :color="active ? '#F6EFEF' : 'white'"
          :class="active ? 'borderme' : 'borderout'"
          class="f-flex align-center rounded-lg mx-2"
          dark
          height="140"
          @click="toggle"
        >
          <v-row>
            <v-col cols="12" sm="12">
              <v-list-item three-line class="text-center">
                <v-list-item-content>
                  <div align="center" justify="center">
                    <v-img src="c3.png" max-width="80" max-height="80" contain>
                    </v-img>
                  </div>
                  <v-list-item-subtitle
                    :class="active ? 'brown--text' : 'black--text'"
                    class="caaption mt-4"
                  >
                    Juice
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>
        </v-card>
      </v-item>
    </v-col>

    <v-col cols="12" md="2">
      <v-item v-slot="{ active, toggle }">
        <v-card
          :color="active ? '#F6EFEF' : 'white'"
          :class="active ? 'borderme' : 'borderout'"
          class="f-flex align-center rounded-lg mx-2"
          dark
          height="140"
          @click="toggle"
        >
          <v-row>
            <v-col cols="12" sm="12">
              <v-list-item three-line class="text-center">
                <v-list-item-content>
                  <div align="center" justify="center">
                    <v-img src="c4.png" max-width="80" max-height="80" contain>
                    </v-img>
                  </div>
                  <v-list-item-subtitle
                    :class="active ? 'brown--text' : 'black--text'"
                    class="caaption mt-4"
                  >
                    Milk Based
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>
        </v-card>
      </v-item>
    </v-col>

    <v-col cols="12" md="2">
      <v-item v-slot="{ active, toggle }">
        <v-card
          :color="active ? '#F6EFEF' : 'white'"
          :class="active ? 'borderme' : 'borderout'"
          class="f-flex align-center rounded-lg mx-2"
          dark
          height="140"
          @click="toggle"
        >
          <v-row>
            <v-col cols="12" sm="12">
              <v-list-item three-line class="text-center">
                <v-list-item-content>
                  <div align="center" justify="center">
                    <v-img
                      src="c5.png"
                      max-width="110"
                      max-height="110"
                      contain
                    >
                    </v-img>
                  </div>
                  <v-list-item-subtitle
                    :class="active ? 'brown--text' : 'black--text'"
                    class="caaption mt-4"
                  >
                    Snack
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>
        </v-card>
      </v-item>
    </v-col>

    <v-col cols="12" md="2">
      <v-item v-slot="{ active, toggle }">
        <v-card
          :color="active ? '#F6EFEF' : 'white'"
          :class="active ? 'borderme' : 'borderout'"
          class="f-flex align-center rounded-lg mx-2"
          dark
          height="140"
          @click="toggle"
        >
          <v-row>
            <v-col cols="12" sm="12">
              <v-list-item three-line class="text-center">
                <v-list-item-content>
                  <div align="center" justify="center">
                    <v-img
                      src="c6.png"
                      max-width="110"
                      max-height="110"
                      contain
                    >
                    </v-img>
                  </div>
                  <v-list-item-subtitle
                    :class="active ? 'brown--text' : 'black--text'"
                    class="caaption mt-4"
                  >
                    Dessert
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>
        </v-card>
      </v-item>
    </v-col>
  </v-row>
</template>

<script>
export default {};
</script>

<style scoped>
.v-card.borderme {
  border: 2px solid #704232 !important;
}
.v-card.borderout {
  border: 1px solid #bcaaa4 !important;
}
</style>
