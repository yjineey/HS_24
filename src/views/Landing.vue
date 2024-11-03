<template>
  <div>
    <div class="position-relative">
      <!-- shape Hero -->
      <section class="section-shaped my-0">
        <div class="shape shape-style-1 shape-default shape-skew">
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="container shape-container d-flex">
          <div class="col px-0">
            <div class="row">
              <div class="col-lg-6">
                <h1 class="display-3 text-white">
                  A beautiful Design System
                  <span>completed with examples</span>
                </h1>
                <p class="lead text-white">
                  The design system comes with four pre-built pages to help you
                  get started faster. You can change the text and images and
                  you're good to go.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- 1st Hero Variation -->
    </div>
    <section class="section section-lg pt-lg-0 mt--200">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-12">
            <div class="row row-grid">
              <div class="col-lg-4">
                <card class="border-0" hover shadow body-classes="py-5">
                  <icon
                    name="ni ni-check-bold"
                    type="primary"
                    rounded
                    class="mb-4"
                  >
                  </icon>
                  <h6 class="text-primary text-uppercase">Download Argon</h6>
                  <p class="description mt-3">
                    Argon is a great free UI package based on Bootstrap 4 that
                    includes the most important components and features.
                  </p>
                  <div>
                    <badge type="primary" rounded>design</badge>
                    <badge type="primary" rounded>system</badge>
                    <badge type="primary" rounded>creative</badge>
                  </div>
                  <base-button tag="a" href="#" type="primary" class="mt-4">
                    Learn more
                  </base-button>
                </card>
              </div>
              <div class="col-lg-4">
                <card class="border-0" hover shadow body-classes="py-5">
                  <icon
                    name="ni ni-istanbul"
                    type="success"
                    rounded
                    class="mb-4"
                  >
                  </icon>
                  <h6 class="text-success text-uppercase">Build Something</h6>
                  <p class="description mt-3">
                    Argon is a great free UI package based on Bootstrap 4 that
                    includes the most important components and features.
                  </p>
                  <div>
                    <badge type="success" rounded>business</badge>
                    <badge type="success" rounded>vision</badge>
                    <badge type="success" rounded>success</badge>
                  </div>
                  <base-button tag="a" href="#" type="success" class="mt-4">
                    Learn more
                  </base-button>
                </card>
              </div>
              <div class="col-lg-4">
                <card class="border-0" hover shadow body-classes="py-5">
                  <icon name="ni ni-planet" type="warning" rounded class="mb-4">
                  </icon>
                  <h6 class="text-warning text-uppercase">Prepare Launch</h6>
                  <p class="description mt-3">
                    Argon is a great free UI package based on Bootstrap 4 that
                    includes the most important components and features.
                  </p>
                  <div>
                    <badge type="warning" rounded>marketing</badge>
                    <badge type="warning" rounded>product</badge>
                    <badge type="warning" rounded>launch</badge>
                  </div>
                  <base-button tag="a" href="#" type="warning" class="mt-4">
                    Learn more
                  </base-button>
                </card>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section bg-secondary">
      <div class="container">
        <div class="row row-grid align-items-center">
          <div class="col-md-6">
            <div class="card bg-default shadow border-0">
              <img v-lazy="'img/profilePicture2.jpg'" class="card-img-top" />
              <blockquote class="card-blockquote">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="svg-bg"
                >
                  <polygon
                    points="0,52 583,95 0,95"
                    class="fill-default"
                  ></polygon>
                  <polygon
                    points="0,42 583,95 683,0 0,95"
                    opacity=".2"
                    class="fill-default"
                  ></polygon>
                </svg>
                <h4 class="display-3 font-weight-bold text-white">YANG JIN</h4>
                <p class="lead text-italic text-white">
                  <icon name="ni ni-favourite-28"></icon>
                  H.P : 010-2567-3706
                </p>
                <p class="lead text-italic text-white">
                  <icon name="ni ni-favourite-28"></icon>
                  E-mail : did3706@naver.com
                </p>
              </blockquote>
            </div>
          </div>
          <div class="col-md-6">
            <div class="pl-md-5">
              <icon
                name="ni ni-favourite-28"
                class="mb-5"
                size="sm"
                type="warning"
                shadow
              ></icon>
              <span class="display-4" style="margin-left: 20px">Introduce</span>

              <p>안녕하세요</p>
              <p>
                Vue.js, Nuxt3, JavaScript, TypeScript를 다루는 4년 차 프론트엔드
                개발자입니다
              </p>
              <p>
                B2B 시스템의 화면을 주로 개발하였으며, 사용자들이 더 즐겁고
                편리하게 사용할 수 있는 화면을 만드는 것에 큰 보람을 느끼고
                있습니다
              </p>
              <p>
                프로젝트를 진행할 때는 사용자 관점에서 문제를 이해하고 해결하기
                위해 노력하며, 늘 새로운 시각으로 더 나은 결과를 고민하고
                있습니다
              </p>
              <p>
                협업 속에서 더 큰 성장을 이룰 수 있다고 믿기에 팀원들과의 소통을
                가장 중요하게 생각하고 있습니다
              </p>
              <p>
                기술의 변화에 발맞추어 새로운 도전을 즐기며, 끊임없이 성장하는
                개발자가 되고 싶습니다
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section section-md section-shaped my-0 overflow-hidden">
      <div class="shape shape-style-1 bg-gradient-warning shape-skew">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div class="container py-0">
        <div class="row row-grid align-items-center">
          <div class="col-md-6 order-lg-2 ml-lg-auto">
            <div class="position-relative pl-md-5">
              <img src="img/ill/ill-2.svg" class="img-center img-fluid" />
            </div>
          </div>
          <div class="col-lg-6 order-lg-1">
            <div class="d-flex px-3">
              <div>
                <icon
                  name="ni ni-spaceship"
                  size="lg"
                  class="bg-gradient-white"
                  color="primary"
                  shadow
                  rounded
                ></icon>
              </div>
              <div class="pl-4">
                <h4 class="display-3 text-white">Experiences</h4>
                <p class="text-white" style="margin-top: 25px !important">
                  안녕하세요😊
                </p>
                <p class="text-white">
                  Vue.js, Nuxt3, JavaScript, TypeScript를 다루는
                </p>
                <p class="text-white">4년차 Web 프론트엔드 개발자입니다</p>
              </div>
            </div>
            <card shadow class="shadow-lg--hover mt-5">
              <div class="d-flex px-3">
                <div>
                  <icon
                    name="ni ni-satisfied"
                    gradient="success"
                    color="white"
                    shadow
                    rounded
                  ></icon>
                </div>
                <div class="pl-4">
                  <h5 class="title text-success">한솔PNS (IT)</h5>
                  <p>기술연구소 솔루션 R&D 파트</p>
                  <h6 class="text-success">2024 - ING</h6>
                </div>
              </div>
            </card>
            <card shadow class="shadow-lg--hover mt-5">
              <div class="d-flex px-3">
                <div>
                  <icon
                    name="ni ni-satisfied"
                    gradient="warning"
                    color="white"
                    shadow
                    rounded
                  ></icon>
                </div>
                <div class="pl-4">
                  <h5 class="title text-success">IN-SOFT</h5>
                  <p>솔루션사업본부 OpenManager</p>
                  <h6 class="text-success">2021 - 2024</h6>
                </div>
              </div>
            </card>
          </div>
        </div>
      </div>
    </section>
    <section class="section section-lg">
      <div class="container">
        <div class="row justify-content-center text-center mb-md">
          <div class="col-lg-8">
            <h2 class="display-3">Exciting Hobby</h2>
            <p class="lead text-muted">What I love to do in my free time</p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/riding1.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">환상자전거일주</h6>
                  <small class="h6 text-muted">Jeju</small>
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/riding2.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">환상자전거일주</h6>
                  <small class="h6 text-muted">Jeju</small>
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/mtClimbing1.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">관악산</h6>
                  <small class="h6 text-muted">Seoul</small>
                </h5>
              </div>
            </div>
          </div>

          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/mtClimbing3.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">관악산</h6>
                  <small class="h6 text-muted">Seoul</small>
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/climbing1.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">클라임투게더</h6>
                  <small class="h6 text-muted">Wonju</small>
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/climbing2.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">클라임투게더</h6>
                  <small class="h6 text-muted">Wonju</small>
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/climbing5.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">서울숲클라이밍</h6>
                  <small class="h6 text-muted">Seoul</small>
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/climbing6.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">서울숲클라이밍</h6>
                  <small class="h6 text-muted">Seoul</small>
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/mtClimbing5.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">지리산 (천왕봉)</h6>

                  <small class="h6 text-muted">HaDong</small>
                </h5>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-3 mb-5">
            <div class="px-4">
              <img
                v-lazy="'img/hobby/mtClimbing6.PNG'"
                class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                style="width: 200px"
              />
              <div class="pt-4 text-center">
                <h5 class="title">
                  <h6 class="d-block mb-1">지리산 (천왕봉)</h6>
                  <small class="h6 text-muted">HaDong</small>
                </h5>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section section-lg pt-0">
      <div class="container">
        <card gradient="warning" no-body shadow-size="lg" class="border-0">
          <div class="p-4"></div>
          <Stack />
        </card>
      </div>
    </section>
  </div>
</template>

<script>
import Stack from './components/Stack';

export default {
  name: 'home',
  components: {
    Stack,
  },
};
</script>
