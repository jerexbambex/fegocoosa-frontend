<template>
  <div class="home">
    <!-- Hero Start -->
        <section class="main-slider">
            <ul class="slides">
                <li class="bg-slider bg-animation-left d-flex align-items-center" style="background-image:url('images/eoy2.jpg')">
                    <div class="container">
                        <div class="row align-items-center">
                            <div class="col-lg-7 col-md-7">
                                <div class="title-heading position-relative mt-4" style="z-index: 1;">
                                    <h1 class="heading display-4 mb-3 font-boing font-normal">Welcome to <br> FEGOCOOSA</h1>
                                    <p class="para-desc">Welcome to the official website of the Federal Government College, Ogbomoso Old Students Association. This is aimed at fostering lifelong relationship between our alma mater and her old students and be able to build for a greater tomorrow.</p>
                                    <div class="mt-4 pt-2">
                                        <a href="#" class="btn btn-pills btn-brand mouse-down px-4 shadow-3">
                                        	Connect now &nbsp;

                                        	<span class="border-radius-pill badge badge-pill badge-sm badge-light rounded-circle py-2 ml-3 -mr-12"><i data-feather="log-in" class="fea icon-sm"> </i></span>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </li>
            </ul>
        </section><!--end section-->
        <!-- Hero End -->


		<section class="section pt-0">
            <div class="container mt-100 mt-60">
                <div class="row align-items-center">
                    <div class="col-lg-5 col-md-6 mt-4 pt-2">
                        <img src="images/president2.jpg" alt="">
                    </div><!--end col-->

                    <div class="col-lg-7 col-md-6 mt-4 pt-2">
                        <div class="section-title ml-lg-5">
                            <h4 class="title mb-4 font-boing">President's Address</h4>
                            <h6 class="display-4 -mt-12">Akinyemi Omoyeni</h6>
                            <h6 class="font-sm -mt-12 mb-3"><span class="badge badge-pill badge-success"> 1992 Set </span></h6>
							<p class="mb-4">Smallest directly families surprise honoured am an. Speaking replying mistress him numerous she returned feelings may day. Evening way luckily son exposed get general greatly. Zealously prevailed be arranging do. Set arranging too dejection september happiness.</p>

							<p class="mb-4">John draw real poor on call my from. May she mrs furnished discourse extremely. Ask doubt noisy shade guest did built her him. Ignorant repeated hastened it do. Consider bachelor he yourself expenses no. Her itself active giving for expect vulgar months.</p>

							<p class="mb-4">It real sent your at. Amounted all shy set why followed declared. Repeated of endeavor mr position kindness offering ignorant so up. Simplicity are melancholy preference considered saw companions. Disposal on outweigh do speedily in on.</p>

                            <!-- <ul class="list-unstyled feature-list text-muted">
                                <li><i data-feather="check-circle" class="fea icon-sm text-success mr-2"></i>Digital Marketing Solutions for Tomorrow</li>
                                <li><i data-feather="check-circle" class="fea icon-sm text-success mr-2"></i>Our Talented & Experienced Marketing Agency</li>
                                <li><i data-feather="check-circle" class="fea icon-sm text-success mr-2"></i>Create your own skin to match your brand</li>
                            </ul> -->
                            <div class="mt-4">
                                <!-- <a href="javascript:void(0)" class="btn btn-primary">Read More <i data-feather="arrow-right" class="fea icon-sm"></i></a> -->
                                <a href="#" class="text-muted readmore">Read More <i data-feather="arrow-right" class="fea icon-sm"> </i></a>
                            </div>
                        </div>
                    </div><!--end col-->
                </div><!--end row-->
            </div><!--end container-->
		</section>

        <!-- Testi n Download cta start -->
        <section class="section pt-0">
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <div class="rounded bg-brand p-lg-5 p-4">
		                    <div class="row align-items-end">
		                        <div class="col-md-8">
		                            <div class="section-title text-md-left text-center">
		                                <h4 class="title mb-3 text-white title-dark">Start connecting with your set members today</h4>
		                                <p class="text-white-50 mb-0">A place to reminisce and go down memory lane together. A place to talk about the future and respond to the emerging needs of our dear school.</p>
		                            </div>
		                        </div><!--end col-->

		                        <div class="col-md-4 mt-4 mt-sm-0">
		                            <div class="text-md-right text-center">
		                                <a href="javascript:void(0)" class="btn btn-light">Get Started</a>
		                            </div>
		                        </div><!--end col-->
		                    </div><!--end row-->
		                </div>
                    </div><!--end col-->
                </div><!--end row-->

                <!--end row-->
            </div><!--end container-->
        </section><!--end section-->
        <!-- Testi n Download cta End -->

        <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Footer from '@/components/partials/Footer.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld, Footer
  }
}
</script>
