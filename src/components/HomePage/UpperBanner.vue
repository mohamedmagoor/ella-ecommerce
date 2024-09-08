<template>
  <div class="banner">
    <div class="parentt">
      <v-container>
        <v-row>
          <v-col cols="6">
            <div class="cont">
              <h3><span>Huge Saving</span> on UHD Televisions</h3>
              <p class="hint py-3">Sale up to 70% off on selected items*</p>
              <v-btn
                variant="outlined"
                style="border-radius: 30px; text-transform: none"
                class="py-3 px-10"
                density="combact"
              >
                Shop Now
              </v-btn>
            </div>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </div>
</template>
<style lang="scss">
.banner {
  .parentt {
    background-image: url("../../assets/images/banner-bg.jpg");
    background-position: center;
    background-size: cover;
    height: 390px;
    .cont {
      color: white;
      padding: 40px 0 0 100px;
      h3 {
        font-weight: 900;
        font-size: 45px;
        span {
          color: rgb(45, 251, 223);
        }
      }
      .hint {
        margin: 20px 0 40px;
      }
    }
  }
}
</style>
