<template>
  <div class="section">
    <h2 class="title text-center">Why choosing Kidzona ?</h2>
    <div class="container">
      <div class="row">
        <div class="col-md-10 ml-auto col-xl-6 mr-auto">
          <p class="category" style="text-align:center;">Less time</p>
          <!-- Tabs with Background on Card -->
          <div class="card">
          <div style="text-align: center;">
          <img class="n-logo" src="img/time.png" alt="" height="90" width="90"/>
          </div>
                <p class="card-body text-center">
                  The school bus sells to many children on the way to school, 
                  and the journey time is very long. 
                  with Kidzona your kids will save thier time going to school and be more active
                </p>
          </div>
          <!-- End Tabs on plain Card -->
        </div>
        <div class="col-md-10 ml-auto col-xl-6 mr-auto">
          <p class="category" style="text-align:center;">Safe</p>
          <!-- Tabs with Background on Card -->
          <div class="card">
          <div style="text-align: center;">
          <img class="n-logo" src="img/safe.png" alt="" height="100" width="100"/>
          </div>
                <p class="card-body text-center">
                  You will be interviewed by the captain before subscribing, 
                  and you will receive a copy of his papers, card, licenses, analysis, and check out your kids trip.
                </p>
          </div>
          <!-- End Tabs on plain Card -->
        </div>
        <div class="col-md-10 ml-auto col-xl-6 mr-auto">
          <p class="category" style="text-align:center;">comfort</p>
          <!-- Tabs with Background on Card -->
          <div class="card">
          <div style="text-align: center;">
          <img class="n-logo" src="img/Comfrot.png" alt="" height="90" width="90"/>
          </div>
                <p class="card-body text-center">
                  Your child will ride Kidzona bus with air conditioning and comfortable and guarantee the child's comfort and you are not to be worry or wakr up early
                </p>
          </div>
          <!-- End Tabs on plain Card -->
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Card, Tabs, TabPane } from '@/components';

export default {
  components: {
    Card,
    Tabs,
    TabPane
  }
};
</script>
<style>
.tab-content.tab-content-padding {
  padding: 20px;
}
</style>
