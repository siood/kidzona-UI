<template>
  <div>
    <div class="page-header clear-filter" filter-color="blue">
      <parallax
        class="page-header-image"
        style="background-image:url('img/kidzona2.jpg')"
      >
      </parallax>
      <div class="container">
        <div class="content-center brand">
          <img class="n-logo" src="img/kidzonaLogo.png" alt=""/>
          <h1 class="h1-seo" style="font-weight:bold;">Kidzona</h1>
          <h3>School is gonna be fun from now on</h3>
        </div>
      </div>
    </div>
    <tabs-section></tabs-section>
    <signup-form></signup-form>
  </div>
</template>
<script>
import { Parallax } from '@/components';
import TabsSection from './components/Tabs';
import SignupForm from './components/SignupForm';


export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
    Parallax,
    TabsSection,
    SignupForm
  }
};
</script>
<style></style>
