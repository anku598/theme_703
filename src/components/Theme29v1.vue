<template>
  <div class="hold_theme_29v1">
    <b-container fluid class="header">
      <b-row></b-row>
    </b-container>

    <div class="navigation">
      <div class="body_icon">
        <img src="@/assets/img/body_icon.svg" alt />
      </div>
      <b-tabs v-model="tabIndex" content-class="mt-3" fill nav-class="nav-tab-29v1">
        <b-tab class="addHere" :title-link-class="[linkClass(0), 'tab_29v1']">
          <template v-slot:title>
            <img src="../assets/img/portfolio_icon.svg" alt />
            <p>Portfolio</p>
          </template>

          <div class="tab-content-wrapper">
            <b-container fluid>
              <b-row>
                <b-col lg="4" xl="4" md="12" sm="12" cols="12" class="portfolio_img">
                  <b-img src="../assets/img/portfolio_one.jpg" fluid-grow alt="Portfolio one"></b-img>
                </b-col>

                <b-col lg="4" xl="4" md="12" sm="12" cols="12" class="portfolio_img">
                  <b-img src="../assets/img/portfolio_one.jpg" fluid-grow alt="Portfolio one"></b-img>
                </b-col>

                <b-col lg="4" xl="4" md="12" sm="12" cols="12" class="portfolio_img">
                  <b-img src="../assets/img/portfolio_one.jpg" fluid-grow alt="Portfolio one"></b-img>
                </b-col>

                <b-col lg="4" xl="4" md="12" sm="12" cols="12" class="portfolio_img">
                  <b-img src="../assets/img/portfolio_one.jpg" fluid-grow alt="Portfolio one"></b-img>
                </b-col>

                <b-col lg="4" xl="4" md="12" sm="12" cols="12" class="portfolio_img">
                  <b-img src="../assets/img/portfolio_one.jpg" fluid-grow alt="Portfolio one"></b-img>
                </b-col>

                <b-col lg="4" xl="4" md="12" sm="12" cols="12" class="portfolio_img">
                  <b-img src="../assets/img/portfolio_one.jpg" fluid-grow alt="Portfolio one"></b-img>
                </b-col>
              </b-row>
            </b-container>
          </div>
        </b-tab>
        <b-tab class="addHere" :title-link-class="[linkClass(1), 'tab_29v1']">
          <template v-slot:title>
            <img src="../assets/img/work_icon.svg" alt />
            <p>Work</p>
          </template>

          <div class="tab-content-wrapper work_wrapper">
            <b-container fluid>
              <b-row>
                <b-col lg="6" xl="6" md="12" sm="12" cols="12">
                  <div class="job_experience">
                    <b-row class="d-flex align-items-center mb-5">
                      <b-col lg="5" xl="5" md="5" sm="5" cols="5">
                        <h2 class="job-title">Google</h2>
                      </b-col>

                      <b-col lg="7" xl="7" md="7" sm="7" cols="7">
                        <p class="job_designation">User Experience Designer</p>
                      </b-col>
                    </b-row>

                    <b-row>
                      <b-col lg="5" xl="5" md="5" sm="5" cols="5">
                        <div class="job-duration">
                          <span class="d-none d-lg-block d-xl-block">duration</span>
                          <p class="date">Dec 19 - Present</p>
                        </div>
                      </b-col>

                      <b-col lg="7" xl="7" md="7" sm="7" cols="7">
                        <p
                          class="exp_details"
                        >I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
                      </b-col>
                    </b-row>
                  </div>
                </b-col>

                <b-col lg="6" xl="6" md="12" sm="12" cols="12">
                  <div class="job_experience">
                    <b-row class="d-flex align-items-center mb-5">
                      <b-col lg="5" xl="5" md="5" sm="5" cols="5">
                        <h2 class="job-title">Google</h2>
                      </b-col>

                      <b-col lg="7" xl="7" md="7" sm="7" cols="7">
                        <p class="job_designation">User Experience Designer</p>
                      </b-col>
                    </b-row>

                    <b-row>
                      <b-col lg="5" xl="5" md="5" sm="5" cols="5">
                        <div class="job-duration">
                          <span class="d-none d-lg-block d-xl-block">duration</span>
                          <p class="date">Dec 19 - Present</p>
                        </div>
                      </b-col>

                      <b-col lg="7" xl="7" md="7" sm="7" cols="7">
                        <p
                          class="exp_details"
                        >I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
                      </b-col>
                    </b-row>
                  </div>
                </b-col>

                <b-col lg="6" xl="6" md="12" sm="12" cols="12">
                  <div class="job_experience">
                    <b-row class="d-flex align-items-center mb-5">
                      <b-col lg="5" xl="5" md="5" sm="5" cols="5">
                        <h2 class="job-title">Google</h2>
                      </b-col>

                      <b-col lg="7" xl="7" md="7" sm="7" cols="7">
                        <p class="job_designation">User Experience Designer</p>
                      </b-col>
                    </b-row>

                    <b-row>
                      <b-col lg="5" xl="5" md="5" sm="5" cols="5">
                        <div class="job-duration">
                          <span class="d-none d-lg-block d-xl-block">duration</span>
                          <p class="date">Dec 19 - Present</p>
                        </div>
                      </b-col>

                      <b-col lg="7" xl="7" md="7" sm="7" cols="7">
                        <p
                          class="exp_details"
                        >I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
                      </b-col>
                    </b-row>
                  </div>
                </b-col>

                <b-col lg="6" xl="6" md="12" sm="12" cols="12">
                  <div class="job_experience">
                    <b-row class="d-flex align-items-center mb-5">
                      <b-col lg="5" xl="5" md="5" sm="5" cols="5">
                        <h2 class="job-title">Google</h2>
                      </b-col>

                      <b-col lg="7" xl="7" md="7" sm="7" cols="7">
                        <p class="job_designation">User Experience Designer</p>
                      </b-col>
                    </b-row>

                    <b-row>
                      <b-col lg="5" xl="5" md="5" sm="5" cols="5">
                        <div class="job-duration">
                          <span class="d-none d-lg-block d-xl-block">duration</span>
                          <p class="date">Dec 19 - Present</p>
                        </div>
                      </b-col>

                      <b-col lg="7" xl="7" md="7" sm="7" cols="7">
                        <p
                          class="exp_details"
                        >I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
                      </b-col>
                    </b-row>
                  </div>
                </b-col>
              </b-row>
            </b-container>
          </div>
        </b-tab>
        <b-tab class="addHere" :title-link-class="[linkClass(2), 'tab_29v1']">
          <template v-slot:title>
            <img src="../assets/img/education_icon.svg" alt />
            <p>Education</p>
          </template>

          <div class="tab-content-wrapper work_wrapper">
            <b-container fluid>
              <b-row>
                <b-col lg="6" xl="6" md="12" sm="12" cols="12" class="mb-5">
                  <div class="job_experience">
                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <span>University</span>
                    </b-col>
                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <h2 class="job-title mt-5 mb-5">California Institute of Technology</h2>
                    </b-col>

                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <div class="job-duration">
                        <p class="u-duration mb-5">M.Sc in HCI, Dec 19 - Present</p>
                      </div>
                    </b-col>

                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <p
                        class="exp_details"
                      >I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
                    </b-col>
                  </div>
                </b-col>

                <b-col lg="6" xl="6" md="12" sm="12" cols="12" class="mb-5">
                  <div class="job_experience">
                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <span>University</span>
                    </b-col>
                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <h2 class="job-title mt-5 mb-5">California Institute of Technology</h2>
                    </b-col>

                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <div class="job-duration">
                        <p class="u-duration mb-5">M.Sc in HCI, Dec 19 - Present</p>
                      </div>
                    </b-col>

                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <p
                        class="exp_details"
                      >I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
                    </b-col>
                  </div>
                </b-col>

                <b-col lg="6" xl="6" md="12" sm="12" cols="12" class="mb-5">
                  <div class="job_experience">
                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <span>University</span>
                    </b-col>
                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <h2 class="job-title mt-5 mb-5">California Institute of Technology</h2>
                    </b-col>

                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <div class="job-duration">
                        <p class="u-duration mb-5">M.Sc in HCI, Dec 19 - Present</p>
                      </div>
                    </b-col>

                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <p
                        class="exp_details"
                      >I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
                    </b-col>
                  </div>
                </b-col>

                <b-col lg="6" xl="6" md="12" sm="12" cols="12" class="mb-5">
                  <div class="job_experience">
                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <span>University</span>
                    </b-col>
                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <h2 class="job-title mt-5 mb-5">California Institute of Technology</h2>
                    </b-col>

                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <div class="job-duration">
                        <p class="u-duration mb-5">M.Sc in HCI, Dec 19 - Present</p>
                      </div>
                    </b-col>

                    <b-col lg="12" xl="12" md="12" sm="12" cols="12">
                      <p
                        class="exp_details"
                      >I'm a paragraph. Click here to add your own text and edit me. It’s easy. Just click “Edit Text” or double click me to add your own content and make changes.</p>
                    </b-col>
                  </div>
                </b-col>
              </b-row>
            </b-container>
          </div>
        </b-tab>
        <b-tab class="addHere" :title-link-class="[linkClass(3), 'tab_29v1']">
          <template v-slot:title>
            <img src="../assets/img/skills_icon.svg" alt />
            <p>Skills</p>
          </template>

          <div class="tab_component_wrapper">
            <b-tabs v-model="skillTabIndex" content-class="mt-3" fill nav-class="skill-tab-29v1">
              <b-tab class="addHere" :title-link-class="[SkilllinkClass(0), 'skill_tab_29v1' ]">
                <template v-slot:title>
                  <p>Programming Language</p>
                </template>

                <div class="skill_component_wrapper">
                  <b-row class="d-flex align-items-center">
                    <b-col
                      lg="12"
                      xl="12"
                      sm="12"
                      md="12"
                      cols="12"
                      v-for="(bar,index) in bars"
                      :key="index"
                      class="mb-4"
                    >
                      <b-row>
                        <b-col lg="3" xl="3" sm="3" md="3" cols="3" class="text-center">
                          <div class="skill_badge">{{bar.label}}</div>
                        </b-col>
                        <b-col lg="6" xl="6" sm="6" md="6" cols="6" align-self="center">
                          <b-progress class="w-100">
                            <b-progress-bar
                              :value="bar.value"
                              :style="{backgroundColor:progressBg}"
                            ></b-progress-bar>
                          </b-progress>
                        </b-col>
                        <b-col
                          class="text-center"
                          lg="3"
                          xl="3"
                          sm="3"
                          md="3"
                          cols="3"
                        >{{bar.value}} %</b-col>
                      </b-row>
                    </b-col>
                  </b-row>
                </div>
              </b-tab>

              <b-tab class="addHere" :title-link-class="[SkilllinkClass(1), 'skill_tab_29' ]">
                <template v-slot:title>
                  <p>Frameworks/Database</p>
                </template>
              </b-tab>

              <b-tab class="addHere" :title-link-class="[SkilllinkClass(2), 'skill_tab_29' ]">
                <template v-slot:title>
                  <p>Design Skills</p>
                </template>
              </b-tab>

              <b-tab class="addHere" :title-link-class="[SkilllinkClass(3), 'skill_tab_29' ]">
                <template v-slot:title>
                  <p>Software</p>
                </template>
              </b-tab>
            </b-tabs>
          </div>
        </b-tab>
      </b-tabs>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Theme703',
  data() {
    return {
      tabIndex: 0,
      skillTabIndex: 0,
      show: false,
      progressBg: '#71BFFF',
      bars: [
        { value: 75, label: 'Html', max: 100 },
        { value: 36, label: 'CSS', max: 100 },
        { value: 25, label: 'bootstrap', max: 100 },
        { value: 80, label: 'javascript', max: 100 }
      ]
    };
  },
  methods: {
    linkClass(idx) {
      if (this.tabIndex === idx) {
        return ['active-tab-703'];
      } else {
        return ['text-light'];
      }
    },
    SkilllinkClass(idx) {
      if (this.skillTabIndex === idx) {
        return ['active-skill-tab-30'];
      } else {
        return ['text-light'];
      }
    }
  }
};
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Lato:400,700|Roboto:400,500,300,700&display=swap');

$primary-color: #3852ce;
$secondary-color: #e5f1ff;
$font-roboto: 'Roboto', sans-serif;
$font-lato: 'Lato', sans-serif;
* {
  box-sizing: border-box;
}
a {
  text-decoration: none;
  &:hover {
    text-decoration: none;
  }
}

h1,
h2,
h3,
h4,
h5,
h6,
p,
span {
  margin: 0;
  padding: 0;
}
.hold_theme_29v1 {
  width: 100%;
  height: 100vh;
  background: #fff;
  color: #fff;
  overflow-x: hidden;
}

.header {
  min-height: 300px;
  width: 100%;
  margin: 0 auto;
  position: relative;
  background: $secondary-color;
}

.navigation {
  position: relative;
  .body_icon {
    position: absolute;
    top: 60px;
    left: 20px;
    width: 10%;
    max-width: 120px;
    min-width: 70px;
    img {
      width: 100%;
    }
  }
}

.tab-content-wrapper {
  width: 90%;
  margin: 0 auto;
  margin-bottom: 2rem;
  margin-top: 6rem;
}

.work_wrapper {
  @media (max-width: 576.98px) {
    width: 100%;
  }
}

.portfolio_img {
  padding-bottom: 30px;
  img {
    box-shadow: 0px 15px 30px rgba(113, 130, 224, 0.19);
  }
}

.job_experience {
  background: $secondary-color;
  color: #000;
  padding: 5rem;
  box-shadow: 6px 6px 30px rgba(0, 0, 0, 0.1);
  border-radius: 30px;

  @media (min-width: 992px) and (max-width: 1170.98px) {
    padding: 5rem 2rem;
  }

  @media (max-width: 767.98px) {
    padding: 3rem 2rem;
  }
}

.job_experience {
  margin: 30px;
  @media (max-width: 991.98px) {
    margin: 30px 0;
  }

  @media (min-width: 992px) and (max-width: 1170.98px) {
    margin: 30px 0;
  }

  .job-title {
    font-family: $font-roboto;
    font-style: normal;
    font-weight: 900;
    font-size: 36px;
    line-height: 42px;
    color: $primary-color;

    @media (max-width: 767.98px) {
      font-size: 24px;
    }
  }

  .job_designation,
  .job-duration,
  .exp_details {
    font-family: $font-roboto;
    font-style: normal;
    font-weight: 400;
    font-size: 17px;
    line-height: 24px;
    text-transform: inherit;

    @media (max-width: 767.98px) {
      font-size: 15px;
    }

    @media (max-width: 576.98px) {
      font-size: 13px;
    }
  }

  .job-duration {
    @media (max-width: 991.98px) {
      margin-bottom: 15px;
    }
    span {
      text-transform: capitalize;
    }
    .date {
      color: $primary-color;
      font-family: $font-roboto;
      font-weight: 900;
    }
  }
}

.exp_details {
  font-weight: 300 !important;
}

.u-duration {
  font-family: $font-lato;
  font-weight: 700;
  color: #4a4b4c;
}

.skill_component_wrapper {
  width: 70%;
  margin: 0 auto;
  color: $primary-color;
  font-family: $font-roboto;
  font-style: normal;
  font-weight: 400;
  font-size: 35px;
  text-transform: capitalize;
  line-height: 56px;
  margin-top: 3rem;

  @media (max-width: 767.98px) {
    width: 90%;
    font-size: 24px;
  }
}

.skill_badge {
  text-align: left;
}
</style>