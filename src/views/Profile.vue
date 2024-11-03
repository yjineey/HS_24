<template>
  <div class="profile-page">
    <section class="section-profile-cover section-shaped my-0">
      <div class="shape shape-style-1 shape-primary shape-skew alpha-4">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
    </section>
    <section class="section section-skew">
      <div class="container">
        <card
          shadow
          class="card-profile mt--200"
          style="margin-top: -435px !important"
          no-body
        >
          <div class="px-4">
            <div class="row justify-content-center">
              <div class="col-lg-3 order-lg-2">
                <div class="card-profile-image">
                  <a href="#">
                    <img
                      src="../../public/img/profilePicture1.jpg"
                      style="transform: translate(-50%, -36%)"
                      class="rounded-circle"
                    />
                  </a>
                </div>
              </div>

              <div
                class="col-lg-4 order-lg-3 text-lg-right align-self-lg-center"
              >
                <div class="card-profile-actions py-4 mt-lg-0">
                  <base-button type="info" size="sm" class="mr-4"
                    >Connect</base-button
                  >
                  <base-button type="default" size="sm" class="float-right"
                    >Message</base-button
                  >
                </div>
              </div>
              <div class="col-lg-4 order-lg-1">
                <div class="card-profile-stats d-flex justify-content-center">
                  <div>
                    <span class="heading">33</span>
                    <span class="description">Friends</span>
                  </div>
                  <div>
                    <span class="heading">10</span>
                    <span class="description">Photos</span>
                  </div>
                  <div>
                    <span class="heading">89</span>
                    <span class="description">Comments</span>
                  </div>
                </div>
              </div>
            </div>
            <div class="text-center mt-5">
              <h3>
                Yang Jin
                <span class="font-weight-light">, 29</span>
              </h3>
              <div class="h6 font-weight-300 mt-4">
                <i class="ni location_pin mr-2"></i> 📱 010-2567-3706
              </div>
              <div class="h6 font-weight-300">
                <i class="ni location_pin mr-2"></i>
                💌 did3706@naver.com
              </div>

              <div class="h5 mt-4">
                <i class="ni business_briefcase-24 mr-2"></i>
                HanSol PNS (IT)
              </div>
              <div class="h6 font-weight-300 mt-4">
                <i class="ni location_pin mr-2"></i>💡 Solution R&D Department
              </div>
              <div class="h6 font-weight-300">
                <i class="ni location_pin mr-2"></i>🐱‍🚀 Front Developer
              </div>
            </div>
            <div class="mt-5 py-5 border-top text-center" style="padding-top: ">
              <div class="row justify-content-center">
                <div class="col-lg-9">
                  <p>
                    Vue.js, Nuxt3, JavaScript, TypeScript를 다루는 4년 차
                    프론트엔드 개발자입니다😊
                  </p>
                  <p>
                    새로운 도전을 즐기며, 성장하기 위해 끊임없이 달려가고
                    있습니다
                  </p>
                </div>
              </div>
            </div>
            <div class="py-5 border-top text-center">
              <Stack />
            </div>
          </div>
        </card>
      </div>
    </section>
  </div>
</template>
<script>
import Stack from './components/Stack2';

export default {
  name: 'profile',
  components: {
    Stack,
  },
};
</script>
<style></style>
