<template>
  <div class="home">
    <!-- Hero Start -->
        <section class="main-slider">
            <ul class="slides">
                <li class="bg-slider bg-animation-left d-flex align-items-center" style="background-image:url('images/hotel/bg03.jpg')">
                    <div class="container">
                        <div class="row align-items-center">
                            <div class="col-lg-7 col-md-7">
                                <div class="title-heading position-relative mt-4" style="z-index: 1;">
                                    <h1 class="heading mb-3">Welcome Landrick <br> A Stunning Hotel</h1>
                                    <p class="para-desc">Launch your campaign and benefit from our expertise on designing and managing conversion centered bootstrap4 html page.</p>
                                    <div class="mt-4 pt-2">
                                        <a href="#bookroom" class="btn btn-primary mouse-down"><i class="mdi mdi-home-assistant"></i> Book now</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </li>
            </ul>
        </section><!--end section-->
        <!-- Hero End -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
