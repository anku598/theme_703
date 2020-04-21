<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang='scss'>
@import url('https://fonts.googleapis.com/css?family=Open+Sans|Roboto|Rubik:400,700&display=swap');

$primary_color: #ed0000;
$font-rubik: 'Rubik', sans-serif;
$font-roboto: 'Roboto', sans-serif;
$font-open-sans: 'Open Sans', sans-serif;

.tab_30 {
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
  padding: 1.2rem 1rem !important;
  border: none !important;
  outline: none !important;
  color: #c7c7c7 !important;
  font-size: 1.6rem;
  transition: all 0.3s ease-in-out !important ;

  .tab_icon {
    margin-right: 12px;
    margin-bottom: 0;
    text-transform: uppercase;
    width: 20px;
    height: 20px;
    border: 3px solid $primary_color;
    display: block;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 10px;
    font-family: $font-rubik;
    font-weight: 700;
    color: #000;
    transition: all 0.3s ease-in-out !important ;
  }

  @media (max-width: 767.98px) {
    padding: 0.5rem 0.8rem !important;
    margin-right: 15px !important;
  }

  &:hover {
    border: none !important;
  }
  img {
    margin-right: 20px;

    @media (max-width: 767.98px) {
      margin-right: 13px;
      width: 16px;
    }
  }
}

.active-tab-30 {
  color: #000 !important;
  border: none !important;
  font-family: $font-rubik;
  font-weight: 700;
  transition: all 0.3s ease-in-out !important ;

  .tab_icon {
    background: $primary_color;
    color: #fff;
  }
}

.nav-tab-30 {
  border-bottom: 0px solid #000 !important;

  @media (max-width: 767.98px) {
    overflow-x: scroll;
    flex-wrap: nowrap;
  }
}

.skill_tab_30 {
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
  padding: 1.2rem 1rem !important;
  border: none !important;
  outline: none !important;
  color: rgba(0, 0, 0, 0.5) !important;
  font-size: 1.2rem;
  transition: all 0.3s ease-in-out !important ;

  @media (max-width: 991.98px) {
    padding: 0.5rem 0.8rem !important;
    margin-right: 15px !important;
    font-size: 0.8rem;
  }

  @media (max-width: 767.98px) {
    min-width: 181px !important;
  }

  &:hover {
    border: none !important;
  }
  img {
    margin-right: 20px;

    @media (max-width: 767.98px) {
      margin-right: 13px;
      width: 16px;
    }
  }
}

.active-skill-tab-30 {
  color: $primary_color !important;
  font-family: $font-rubik;
  font-weight: 700;
  transition: all 0.3s ease-in-out !important ;
  background-color: transparent !important;
  position: relative;

  &:before {
    position: absolute;
    bottom: 0;
    width: 130px;
    height: 4px;
    background: $primary_color;
    content: '';
    left: 50%;
    transform: translateX(-50%);

    @media (max-width: 576.98px) {
      width: 75px;
    }
  }
}

.skill-tab-30 {
  border-bottom: 1px solid rgba(0, 0, 0, 0.1) !important;

  @media (max-width: 991.98px) {
    overflow-x: scroll;
    flex-wrap: nowrap;
  }
}
</style>
