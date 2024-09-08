<template>
  <div class="top-offers bg-grey-lighten-4 py-9">
    <v-container fluid class="pt-9">
      <v-row>
        <v-col cols="4">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent pr-2" v-bind="props" style="overflow: hidden">
              <img
                :style="`width: 100%;cursor:pointer;transition:0.5s all ease-in-out;scale:${
                  isHovering ? 1.05 : 1
                }`"
                src="../../assets/images/playstations.webp"
                alt=""
              />
            </div>
          </v-hover>
        </v-col>
        <v-col cols="4">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent pr-2" v-bind="props" style="overflow: hidden">
              <img
                :style="`width: 100%;cursor:pointer;transition:0.5s all ease-in-out;scale:${
                  isHovering ? 1.05 : 1
                }`"
                src="../../assets/images/headset.webp"
                alt=""
              />
            </div>
          </v-hover>
        </v-col>
        <v-col cols="4">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent pr-2" v-bind="props" style="overflow: hidden">
              <img
                :style="`width: 100%;cursor:pointer;transition:0.5s all ease-in-out;scale:${
                  isHovering ? 1.05 : 1
                }`"
                src="../../assets/images/chairs.webp"
                alt=""
              />
            </div>
          </v-hover>
        </v-col>
        <v-col cols="6" class="mt-3">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent pr-2" v-bind="props" style="overflow: hidden">
              <img
                :style="`width: 100%;cursor:pointer;transition:0.5s all ease-in-out;scale:${
                  isHovering ? 1.05 : 1
                }`"
                src="../../assets/images/iphones.webp"
                alt=""
              />
            </div>
          </v-hover>
        </v-col>
        <v-col cols="6" class="mt-3">
          <v-hover v-slot="{ isHovering, props }">
            <div class="parent pl-2" v-bind="props" style="overflow: hidden">
              <img
                :style="`width: 100%;cursor:pointer;transition:0.5s all ease-in-out;scale:${
                  isHovering ? 1.05 : 1
                }`"
                src="../../assets/images/laptops.webp"
                alt=""
              />
            </div>
          </v-hover>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<style scoped>
.parent {
  border-radius: 7px;
}
</style>
