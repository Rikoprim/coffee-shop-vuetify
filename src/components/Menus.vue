<template>
  <v-row>
    <v-col cols="12" sm="6">
      <v-card flat class="rounded-lg mx-5">
        <v-list-item three-line>
          <v-list-item-avatar rounded size="120" color="grey lighten-4">
            <v-img src="2.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title class="text-h5">
              Caramel Frappuccino
            </v-list-item-title>
            <v-list-item-subtitle class="mt-1">
              Caramel sytrup with coffe, milk and whipped cream
            </v-list-item-subtitle>
            <strong class="mt-3">$3.95</strong>
          </v-list-item-content>
        </v-list-item>
        <v-card-actions>
          <v-row>
            <v-col cols="12" sm="6" class="mt-1">
              <strong class="ml-3">Moods</strong><br />
              <v-item-group mandatory class="mt-n1">
                <v-container>
                  <v-row>
                    <v-col cols="12" md="5">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="50"
                          width="50"
                          flat
                          @click="toggle"
                        >
                          <v-icon dark color="orange">fas fa-fire</v-icon>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" md="5">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="50"
                          width="50"
                          flat
                          @click="toggle"
                        >
                          <v-icon dark color="blue">fab fa-modx</v-icon>
                        </v-card>
                      </v-item>
                    </v-col>
                  </v-row>
                </v-container>
              </v-item-group>
            </v-col>

            <v-col cols="12" sm="6" class="mt-1">
              <strong class="ml-2">Size</strong>
              <v-item-group mandatory class="mt-n1">
                <v-container>
                  <v-row>
                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">S</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">M</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">L</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>
                  </v-row>
                </v-container>
              </v-item-group>
            </v-col>
          </v-row>
        </v-card-actions>

        <v-card-actions>
          <v-row>
            <v-col cols="12" sm="6" class="mt-1">
              <strong class="ml-3">Sugar</strong><br />
              <v-item-group mandatory class="mt-n1">
                <v-container>
                  <v-row>
                    <v-col cols="12" md="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="40"
                          width="40"
                          flat
                          @click="toggle"
                        >
                          <v-list-item class="text-center">
                            <v-list-item-content>
                              <strong
                                class="overline"
                                :class="active ? 'brown--text' : 'red--text'"
                              >
                                30%
                              </strong>
                            </v-list-item-content>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" md="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="40"
                          width="40"
                          flat
                          @click="toggle"
                        >
                          <v-list-item class="text-center">
                            <v-list-item-content>
                              <strong
                                class="overline"
                                :class="active ? 'brown--text' : 'red--text'"
                              >
                                50%
                              </strong>
                            </v-list-item-content>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" md="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="40"
                          width="40"
                          flat
                          @click="toggle"
                        >
                          <v-list-item class="text-center">
                            <v-list-item-content>
                              <strong
                                class="overline"
                                :class="active ? 'brown--text' : 'red--text'"
                              >
                                70%
                              </strong>
                            </v-list-item-content>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>
                  </v-row>
                </v-container>
              </v-item-group>
            </v-col>

            <v-col cols="12" sm="6" class="mt-1">
              <strong class="ml-2">Ice</strong>
              <v-item-group mandatory class="mt-n1">
                <v-container>
                  <v-row>
                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">S</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">M</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">L</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>
                  </v-row>
                </v-container>
              </v-item-group>
            </v-col>
          </v-row>
        </v-card-actions>

        <v-card-actions>
          <v-btn color="#704232" dark block class="widthoutupercase mb-2">
            Add Billing
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="12" sm="6">
      <v-card flat class="rounded-lg mx-5">
        <v-list-item three-line>
          <v-list-item-avatar rounded size="120" color="grey lighten-4">
            <v-img src="3.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title class="text-h5">
              Chocolate Frappuccino
            </v-list-item-title>
            <v-list-item-subtitle class="mt-1">
              Sweet chocolate with coffe, milk and whipped cream
            </v-list-item-subtitle>
            <strong class="mt-3">$5.65</strong>
          </v-list-item-content>
        </v-list-item>
        <v-card-actions>
          <v-row>
            <v-col cols="12" sm="6" class="mt-1">
              <strong class="ml-3">Moods</strong><br />
              <v-item-group mandatory class="mt-n1">
                <v-container>
                  <v-row>
                    <v-col cols="12" md="5">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="50"
                          width="50"
                          flat
                          @click="toggle"
                        >
                          <v-icon dark color="orange">fas fa-fire</v-icon>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" md="5">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="50"
                          width="50"
                          flat
                          @click="toggle"
                        >
                          <v-icon dark color="blue">fab fa-modx</v-icon>
                        </v-card>
                      </v-item>
                    </v-col>
                  </v-row>
                </v-container>
              </v-item-group>
            </v-col>

            <v-col cols="12" sm="6" class="mt-1">
              <strong class="ml-2">Size</strong>
              <v-item-group mandatory class="mt-n1">
                <v-container>
                  <v-row>
                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">S</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">M</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">L</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>
                  </v-row>
                </v-container>
              </v-item-group>
            </v-col>
          </v-row>
        </v-card-actions>

        <v-card-actions>
          <v-row>
            <v-col cols="12" sm="6" class="mt-1">
              <strong class="ml-3">Sugar</strong><br />
              <v-item-group mandatory class="mt-n1">
                <v-container>
                  <v-row>
                    <v-col cols="12" md="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="40"
                          width="40"
                          flat
                          @click="toggle"
                        >
                          <v-list-item class="text-center">
                            <v-list-item-content>
                              <strong
                                class="overline"
                                :class="active ? 'brown--text' : 'red--text'"
                              >
                                30%
                              </strong>
                            </v-list-item-content>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" md="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="40"
                          width="40"
                          flat
                          @click="toggle"
                        >
                          <v-list-item class="text-center">
                            <v-list-item-content>
                              <strong
                                class="overline"
                                :class="active ? 'brown--text' : 'red--text'"
                              >
                                50%
                              </strong>
                            </v-list-item-content>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" md="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          dark
                          height="40"
                          width="40"
                          flat
                          @click="toggle"
                        >
                          <v-list-item class="text-center">
                            <v-list-item-content>
                              <strong
                                class="overline"
                                :class="active ? 'brown--text' : 'red--text'"
                              >
                                70%
                              </strong>
                            </v-list-item-content>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>
                  </v-row>
                </v-container>
              </v-item-group>
            </v-col>

            <v-col cols="12" sm="6" class="mt-1">
              <strong class="ml-2">Ice</strong>
              <v-item-group mandatory class="mt-n1">
                <v-container>
                  <v-row>
                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">S</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">M</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>

                    <v-col cols="12" sm="4">
                      <v-item v-slot="{ active, toggle }">
                        <v-card
                          color="#F6EFEF"
                          :class="active ? 'borderme' : ''"
                          class="d-flex align-center rounded-circle justify-center"
                          height="40"
                          width="40"
                          @click="toggle"
                          flat
                        >
                          <v-list-item class="text-center">
                            <strong class="font-weight-black">L</strong>
                          </v-list-item>
                        </v-card>
                      </v-item>
                    </v-col>
                  </v-row>
                </v-container>
              </v-item-group>
            </v-col>
          </v-row>
        </v-card-actions>

        <v-card-actions>
          <v-btn color="#704232" dark block class="widthoutupercase mb-2">
            Add Billing
          </v-btn>
        </v-card-actions>
      </v-card>
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
