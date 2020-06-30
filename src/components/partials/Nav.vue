<template>
	<!-- Navbar STart -->
        <header id="topnav" class="defaultscroll sticky bg-white">
            <div class="container">
                <!-- Logo container-->
                <div>
                    <a class="logo" href="index.html">
                        <!-- <img src="images/logo-dark.png" height="24" alt=""> -->
                        <!-- Fegocoosa -->
                        <img src="images/logo-white.png" width="30%" alt="">
                    </a>
                </div>
                <div class="buy-button">
                    <a href="#" class="btn btn-pills btn-brand px-4">Sign in</a>
                </div><!--end login button-->
                <!-- End Logo container-->
                <div class="menu-extras">
                    <div class="menu-item">
                        <!-- Mobile menu toggle-->
                        <a class="navbar-toggle">
                            <div class="lines">
                                <span></span>
                                <span></span>
                                <span></span>
                            </div>
                        </a>
                        <!-- End mobile menu toggle-->
                    </div>
                </div>

                <div id="navigation">
                    <!-- Navigation Menu-->
                    <ul class="navigation-menu">
                        <li><a href="index.html">Home</a></li>
                        <li><a href="index.html">About Us</a></li>
                        <li><a href="index.html">Events</a></li>
                        <li class="has-submenu">
                            <a href="javascript:void(0)">Docs</a><span class="menu-arrow"></span>
                            <ul class="submenu">
                                <li><a href="documentation.html">Documentation </a></li>
                                <li><a href="changelog.html">Changelog </a></li>
                                <li><a href="components.html">Components</a></li>
                                <li><a href="widget.html">Widget</a></li>
                            </ul>
                        </li>
                    </ul><!--end navigation menu-->
                    <div class="buy-menu-btn d-none">
                        <a href="#" class="btn btn-pills btn-success">Sign in</a>
                    </div><!--end login button-->
                </div><!--end navigation-->

            </div><!--end container-->
        </header><!--end header-->
    <!-- Navbar End -->
</template>


<script>
	export default {
		name: 'Nav',
		data() {
			return {
				isOpen: false,
	      	}
		},
		methods: {
			//
		}
	}
</script>