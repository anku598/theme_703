<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang='scss'>
$primary-color: #ff4900;
.active-tab-703 {
  background: $primary-color !important;
  color: #fff !important;
  border: none !important;
  transition: all 0.3s ease-in-out !important ;
}

.tab_703 {
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
  padding: 1.2rem 1rem !important;
  border: none !important;
  outline: none !important;

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

.nav-tab-703 {
  border-bottom: 0px solid #000 !important;
  border-top: 2px solid $primary-color;
  @media (max-width: 767.98px) {
    overflow-x: scroll;
    flex-wrap: nowrap;
    border-top: 0px solid $primary-color;
  }
}
</style>
