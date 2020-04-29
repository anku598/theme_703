<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang='scss'>
@import url('https://fonts.googleapis.com/css?family=Lato:400,700|Roboto:400,500,300,700&display=swap');

$primary-color: #3852ce;
$secondary-color: #e5f1ff;
$font-roboto: 'Roboto', sans-serif;
$font-lato: 'Lato', sans-serif;
.tab_29v1 {
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
  padding: 1rem 2rem !important;
  border: none !important;
  outline: none !important;
  color: #a5b4ff !important;
  background: #fafafa !important;
  font-size: 1.3rem;
  transition: all 0.3s ease-in-out !important ;
  box-shadow: 0px 10px 30px rgba(52, 96, 191, 0.05);
  border-radius: 30px !important;
  margin-right: 48px !important;
  font-family: $font-roboto;
  font-weight: 400;

  @media (max-width: 768px) {
    margin-right: 17px !important;
    &:first-child {
      // margin-left: 102px !important;
    }
  }

  // @media (max-width: 576.98px) {
  //   &:first-child {
  //     margin-left: 40rem !important;
  //   }
  // }

  p {
    margin-left: 15px !important;
  }
}
.active-tab-29v1 {
  color: $primary-color !important;
  border: none !important;
  transition: all 0.3s ease-in-out !important ;
  background: #fff !important;
  transition: all 0.3s ease-in-out !important;
  .b-tab-icon {
    background: $primary-color !important;
    transition: all 0.3s ease-in-out !important;
  }
}
.nav-tab-29v1 {
  border-bottom: 0px solid #000 !important;

  @media (max-width: 1231px) {
    overflow-x: scroll;
    flex-wrap: nowrap;
  }
}

.nav-tab-29v1 {
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
  border-bottom: 0 !important;
  max-width: 85%;
  margin: 0 auto;
  margin-top: -35px;

  @media (max-width: 768px) {
    max-width: 100% !important;
    justify-content: flex-start !important;
    padding-bottom: 1rem;
    margin: 0 0 !important;
    margin-top: -35px !important;
  }
}

.skill-tab-29v1 {
  max-width: 90%;
  margin: 0 auto;
  margin-top: 7rem;
  border: 0;
  border-bottom: 1px solid rgba(0, 0, 0, 0.2);

  @media (max-width: 991.98px) {
    overflow-x: scroll;
    flex-wrap: nowrap;
  }
}

a {
  &.skill_tab_29v1 {
    color: #c5c5c5 !important;
    outline: none !important;
    padding-bottom: 1.3rem !important;

    &:hover {
      border: none !important;
    }
  }

  &.active-skill-tab-29v1 {
    border: none !important;
    font-family: $font-lato;
    font-weight: 700;
    color: $primary-color !important;
    text-shadow: 0px 4px 30px rgba(81, 235, 247, 0.4) !important;
    position: relative;
    &:before {
      position: absolute;
      bottom: -4px;
      width: 80px;
      left: 50%;
      transform: translateX(-50%);
      height: 4px;
      background: $primary-color;
      box-shadow: 2px 5px 30px rgba(192, 18, 159, 0.37) !important;
      border-radius: 15px !important;
      content: '';
    }
  }
}
</style>
