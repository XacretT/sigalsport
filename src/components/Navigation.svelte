<script>
	export let segment;
</script>

<style>
	[aria-current] {
		color: black;
	}

	[aria-current]::after {
		position: absolute;
		content: '';
		width: calc(35% - 1em);
		height: 2px;
		background-color: gold;
		display: block;
		bottom: 20px;
	}
</style>

<div class="tm-header-mobile uk-hidden@m">
    <div class="uk-navbar-container">
        <nav uk-navbar="" class="uk-navbar">
            <div class="uk-navbar-left">
				<a class="uk-navbar-toggle" href="#tm-mobile" uk-toggle="">
                    <div uk-navbar-toggle-icon="" class="uk-icon uk-navbar-toggle-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" data-svg="navbar-toggle-icon"><rect y="9" width="20" height="2"></rect><rect y="3" width="20" height="2"></rect><rect y="15" width="20" height="2"></rect></svg></div>
                </a>
            </div>
            
            <div class="uk-navbar-center">
                <a class="uk-navbar-item uk-logo" href=".">
                    <img alt="Fjord" style="height:65px" src="logo-inverted.svg">
				</a>
            </div>
            
            
        </nav>
    </div>

    

	<div id="tm-mobile" uk-offcanvas="" mode="slide" overlay="" class="uk-offcanvas">
		<div class="uk-offcanvas-bar">
			<button class="uk-offcanvas-close uk-icon uk-close" type="button" uk-close=""><svg width="14" height="14" viewBox="0 0 14 14" xmlns="http://www.w3.org/2000/svg" data-svg="close-icon"><line fill="none" stroke="#000" stroke-width="1.1" x1="1" y1="1" x2="13" y2="13"></line><line fill="none" stroke="#000" stroke-width="1.1" x1="13" y1="1" x2="1" y2="13"></line></svg></button>    
			<div class="uk-child-width-1-1 uk-grid uk-grid-stack" uk-grid="">    
				<div>
					<div class="uk-panel">
						<ul class="uk-nav uk-nav-default">
							
							<li class="uk-active"><a href="." class=" menu-item menu-item-type-post_type menu-item-object-page menu-item-home current-menu-item page_item page-item-19 current_page_item">Home</a></li>
							<li class="uk-parent"><a href="services" class=" menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children">Services</a>
							<ul class="uk-nav-sub">

								<li><a href="services/tuning" class=" menu-item menu-item-type-post_type menu-item-object-page">Tuning</a></li></ul></li>
							<li><a href="projects" class=" menu-item menu-item-type-post_type menu-item-object-page">Projects</a></li>
							<li><a href="team" class=" menu-item menu-item-type-post_type menu-item-object-page">Team</a></li>
							<li><a href="blog" class=" menu-item menu-item-type-taxonomy menu-item-object-category">Blog</a></li>
							<li class="uk-parent"><a href="shop" class=" menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children">Shop</a>
							<ul class="uk-nav-sub">

								<li><a href="shop/cart" class=" menu-item menu-item-type-post_type menu-item-object-page">Cart</a></li>
								<li><a href="shop/account" class=" menu-item menu-item-type-post_type menu-item-object-page">My account</a></li></ul></li>
						</ul>
					</div>
				</div>
			</div>
				
		</div>
	</div>

</div>