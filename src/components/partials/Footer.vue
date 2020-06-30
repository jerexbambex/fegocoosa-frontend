<template>
	<div>
        <!-- Footer Start -->
        <footer class="footer bg-light">
            <div class="container">
                <div class="row">
                    <div class="col-lg-4 col-12 mb-0 mb-md-4 pb-0 pb-md-2">
                        <a href="#" class="logo-footer">
                            <img src="images/logo-white.png" height="24" alt="">
                        </a>
                        <p class="mt-4 text-muted">We have gone digital. Start connecting with us on social media platforms.</p>
                        <ul class="list-unstyled mb-0 mt-4">
                            <li class="list-inline-item"><a href="#" class="btn btn-icon btn-pills btn-primary mx-1"><i data-feather="facebook" class="fea icon-sm"></i></a></li>
                            <li class="list-inline-item"><a href="#" class="btn btn-icon btn-pills btn-info mx-1"><i data-feather="instagram" class="fea icon-sm"></i></a></li>
                            <li class="list-inline-item"><a href="#" class="btn btn-icon btn-pills btn-primary mx-1"><i data-feather="twitter" class="fea icon-sm"></i></a></li>
                            <li class="list-inline-item"><a href="#" class="btn btn-icon btn-pills btn-danger mx-1"><i data-feather="youtube" class="fea icon-sm"></i></a></li>
                            <!-- <li class="list-inline-item"><a href="javascript:void(0)" class="rounded mx-1"><i data-feather="instagram" class="fea icon-sm fea-social"></i></a></li>
                            <li class="list-inline-item"><a href="javascript:void(0)" class="rounded mx-1"><i data-feather="twitter" class="fea icon-sm fea-social"></i></a></li>
                            <li class="list-inline-item"><a href="javascript:void(0)" class="rounded mx-1"><i data-feather="linkedin" class="fea icon-sm fea-social"></i></a></li> -->
                        </ul><!--end icon-->
                    </div><!--end col-->

                    <div class="col-lg-2 col-md-4 col-12 mt-4 mt-sm-0 pt-2 pt-sm-0">
                        <h4 class="text-dark footer-head">Fegocoosa</h4>
                        <ul class="list-unstyled footer-list mt-4">
                            <li><a href="#" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> About us</a></li>
                            <li><a href="#" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Team</a></li>
                            <li><a href="#" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Services</a></li>
                            <li><a href="#" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Dues</a></li>
                            <li><a href="#" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Projects</a></li>
                            <li><a href="#" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Careers</a></li>
                            <li><a href="#" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Blog</a></li>
                            <li><a href="#" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Login</a></li>
                        </ul>
                    </div><!--end col-->

                    <div class="col-lg-3 col-md-4 col-12 mt-4 mt-sm-0 pt-2 pt-sm-0">
                        <h4 class="text-dark footer-head">Useful Links</h4>
                        <ul class="list-unstyled footer-list mt-4">
                            <li><a href="page-terms.html" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Constitution</a></li>
                            <li><a href="page-privacy.html" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Events</a></li>
                            <li><a href="documentation.html" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Pay my Dues</a></li>
                            <li><a href="changelog.html" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Board of Trusties</a></li>
                            <li><a href="components.html" class="text-muted"><i class="mdi mdi-chevron-right mr-1"></i> Find my sets</a></li>
                        </ul>
                    </div><!--end col-->

                    <div class="col-lg-3 col-md-4 col-12 mt-4 mt-sm-0 pt-2 pt-sm-0">
                        <h4 class="text-dark footer-head">Newsletter</h4>
                        <p class="mt-4 text-muted">Sign up and receive the latest tips via email.</p>
                        <form>
                            <div class="row">
                                <div class="col-lg-12">
                                    <div class="foot-subscribe foot-white form-group position-relative">
                                        <label class="text-muted">Write your email <span class="text-danger">*</span></label>
                                        <i data-feather="mail" class="fea icon-sm icons"></i>
                                        <input type="email" name="email" id="emailsubscribe" class="form-control bg-light border pl-5 rounded" placeholder="Your email : " required>
                                    </div>
                                </div>
                                <div class="col-lg-12">
                                    <input type="submit" id="submitsubscribe" name="send" class="btn btn-success btn-block" value="Subscribe">
                                </div>
                            </div>
                        </form>
                    </div><!--end col-->
                </div><!--end row-->
            </div><!--end container-->
        </footer><!--end footer-->
        <footer class="footer footer-bar" style="background-color: #243026;">
            <div class="container text-center">
                <div class="row align-items-center">
                    <div class="col-sm-6">
                        <div class="text-sm-left">
                            <p class="mb-0">&copy;
                            	{{ new Date().getFullYear() }} FEGOCOOSA Developed with <i class="mdi mdi-heart text-danger"></i> by <a href="#" target="_blank" class="text-reset">Oluwatosin</a>.</p>
                        </div>
                    </div><!--end col-->

                    <!-- <div class="col-sm-6 mt-4 mt-sm-0 pt-2 pt-sm-0">
                        <ul class="list-unstyled text-sm-right mb-0">
                            <li class="list-inline-item"><a href="javascript:void(0)"><img src="images/payments/american-ex.png" class="avatar avatar-ex-sm" title="American Express" alt=""></a></li>
                            <li class="list-inline-item"><a href="javascript:void(0)"><img src="images/payments/discover.png" class="avatar avatar-ex-sm" title="Discover" alt=""></a></li>
                            <li class="list-inline-item"><a href="javascript:void(0)"><img src="images/payments/master-card.png" class="avatar avatar-ex-sm" title="Master Card" alt=""></a></li>
                            <li class="list-inline-item"><a href="javascript:void(0)"><img src="images/payments/paypal.png" class="avatar avatar-ex-sm" title="Paypal" alt=""></a></li>
                            <li class="list-inline-item"><a href="javascript:void(0)"><img src="images/payments/visa.png" class="avatar avatar-ex-sm" title="Visa" alt=""></a></li>
                        </ul>
                    </div> --><!--end col-->
                </div><!--end row-->
            </div><!--end container-->
        </footer><!--end footer-->
        <!-- Footer End -->
	</div>
</template>

<script>
	export default {
		name: 'Footer',
	}
</script>