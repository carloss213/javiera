<script>
	let isDark = false;
	let isHidden = false;

	function toggleVisibility() {
		isHidden = !isHidden;
	}
</script>

<div class="d-flex">
	<div class={isDark ? 'dark' : 'light'} style="width: 100%;">
		<nav class="navbar navbar-expand-lg navbar-light bg-light contenedor">
			<!-- Container wrapper -->
			<div class="container-fluid">
				<!-- Toggle button -->
				<button
					class="navbar-toggler px-0"
					type="button"
					data-mdb-toggle="collapse"
					data-mdb-target="#navbarExampleOnHover"
					aria-controls="navbarExampleOnHover"
					aria-expanded="false"
					aria-label="Toggle navigation"
				>
					<i class="fas fa-bars"></i>
				</button>

				<!-- Collapsible wrapper -->
				<div class="collapse navbar-collapse" id="navbarExampleOnHover">
					<!-- Left links -->
					<ul class="navbar-nav ms-auto ps-lg-0" style="padding-left: 0.15rem">
						<li class="nav-item">
							<a class="nav-link p-4" href="#/">Home</a>
						</li>
						<li class="nav-item dropdown dropdown-hover position-static" data-mdb-toggle="dropdown">
							<a
								class="nav-link p-4"
								href="#/"
								id="navbarDropdown"
								role="button"
								aria-expanded="false"
							>
								Page
							</a>
							<!-- Dropdown menu -->

							<ul class="dropdown-menu" style="left: 85%;">
								<li><a class="dropdown-item" href="#/">Action</a></li>
								<li><a class="dropdown-item" href="#/">Another action</a></li>
								<li><a class="dropdown-item" href="#/">Something else here</a></li>
							</ul>
						</li>
						<li class="nav-item dropdown dropdown-hover position-static" data-mdb-toggle="dropdown">
							<a
								class="nav-link p-4"
								href="#/"
								id="navbarDropdown"
								role="button"
								aria-expanded="false"
							>
								Portfolio
							</a>
							<!-- Dropdown menu -->

							<ul class="dropdown-menu" style="left: 85%;">
								<li><a class="dropdown-item" href="#/">Action</a></li>
								<li><a class="dropdown-item" href="#/">Another action</a></li>
								<li><a class="dropdown-item" href="#/">Something else here</a></li>
							</ul>
						</li>

						<li class="nav-item dropdown dropdown-hover position-static" data-mdb-toggle="dropdown">
							<a
								class="nav-link p-4"
								href="#/"
								id="navbarDropdown"
								role="button"
								aria-expanded="false"
							>
								Login
							</a>
							<!-- Dropdown menu -->

							<ul class="dropdown-menu" style="left: 85%;">
								<li><a class="dropdown-item" href="#/">Action</a></li>
								<li><a class="dropdown-item" href="#/">Another action</a></li>
								<li><a class="dropdown-item" href="#/">Something else here</a></li>
							</ul>
						</li>
						<li class="nav-item dropdown dropdown-hover position-static" data-mdb-toggle="dropdown">
							<a
								class="nav-link p-4"
								href="#/"
								id="navbarDropdown"
								role="button"
								aria-expanded="false"
							>
								Elements
							</a>
							<!-- Dropdown menu -->
							<div
								class="dropdown-menu w-100 mt-0"
								aria-labelledby="navbarDropdown"
								style="border-top-left-radius: 0;
                              border-top-right-radius: 0;
                            "
							>
								<div class="container">
									<div class="row my-4">
										<div class="col-md-6 col-lg-3 mb-3 mb-lg-0">
											<div class="list-group list-group-flush">
												<a href="#/" class="list-group-item list-group-item-action">Lorem ipsum</a>
												<a href="#/" class="list-group-item list-group-item-action">Dolor sit</a>
												<a href="#/" class="list-group-item list-group-item-action"
													>Amet consectetur</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Cras justo odio</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Adipisicing elit</a
												>
											</div>
										</div>
										<div class="col-md-6 col-lg-3 mb-3 mb-lg-0">
											<div class="list-group list-group-flush">
												<a href="#/" class="list-group-item list-group-item-action"
													>Explicabo voluptas</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Perspiciatis quo</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Cras justo odio</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Laudantium maiores</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Provident dolor</a
												>
											</div>
										</div>
										<div class="col-md-6 col-lg-3 mb-3 mb-md-0">
											<div class="list-group list-group-flush">
												<a href="#/" class="list-group-item list-group-item-action">Iste quaerato</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Cras justo odio</a
												>
												<a href="#/" class="list-group-item list-group-item-action">Est iure</a>
												<a href="#/" class="list-group-item list-group-item-action">Praesentium</a>
												<a href="#/" class="list-group-item list-group-item-action">Laboriosam</a>
											</div>
										</div>
										<div class="col-md-6 col-lg-3">
											<div class="list-group list-group-flush">
												<a href="#/" class="list-group-item list-group-item-action"
													>Cras justo odio</a
												>
												<a href="#/" class="list-group-item list-group-item-action">Saepe</a>
												<a href="#/" class="list-group-item list-group-item-action">Vel alias</a>
												<a href="#/" class="list-group-item list-group-item-action"
													>Sunt doloribus</a
												>
												<a href="#/" class="list-group-item list-group-item-action">Cum dolores</a>
											</div>
										</div>
									</div>
								</div>
							</div>
						</li>
						<!-- Navbar dropdown -->
						<li class="nav-item dropdown dropdown-hover position-static" data-mdb-toggle="dropdown">
							<a
								class="nav-link p-4"
								href="#/"
								id="navbarDropdown"
								role="button"
								aria-expanded="false"
							>
								Shop
							</a>
							<!-- Dropdown menu -->
							<div
								class="dropdown-menu w-100 mt-0"
								aria-labelledby="navbarDropdown"
								style="border-top-left-radius: 0;
                              border-top-right-radius: 0;
                            "
							>
								<div class="container">
									<div class="row my-4">
										<div class="col-md-6 col-lg-3 mb-3 mb-lg-0">
											<div class="list-group list-group-flush">
												<a href="#/" class="list-group-item list-group-item-action">Lorem ipsum</a>
												<a href="#/" class="list-group-item list-group-item-action">Dolor sit</a>
												<a href="#/" class="list-group-item list-group-item-action"
													>Amet consectetur</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Cras justo odio</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Adipisicing elit</a
												>
											</div>
										</div>
										<div class="col-md-6 col-lg-3 mb-3 mb-lg-0">
											<div class="list-group list-group-flush">
												<a href="#/" class="list-group-item list-group-item-action"
													>Explicabo voluptas</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Perspiciatis quo</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Cras justo odio</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Laudantium maiores</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Provident dolor</a
												>
											</div>
										</div>
										<div class="col-md-6 col-lg-3 mb-3 mb-md-0">
											<div class="list-group list-group-flush">
												<a href="#/" class="list-group-item list-group-item-action">Iste quaerato</a
												>
												<a href="#/" class="list-group-item list-group-item-action"
													>Cras justo odio</a
												>
												<a href="#/" class="list-group-item list-group-item-action">Est iure</a>
												<a href="#/" class="list-group-item list-group-item-action">Praesentium</a>
												<a href="#/" class="list-group-item list-group-item-action">Laboriosam</a>
											</div>
										</div>
										<div class="col-md-6 col-lg-3">
											<div class="list-group list-group-flush">
												<a href="#/" class="list-group-item list-group-item-action"
													>Cras justo odio</a
												>
												<a href="#/" class="list-group-item list-group-item-action">Saepe</a>
												<a href="#/" class="list-group-item list-group-item-action">Vel alias</a>
												<a href="#/" class="list-group-item list-group-item-action"
													>Sunt doloribus</a
												>
												<a href="#/" class="list-group-item list-group-item-action">Cum dolores</a>
											</div>
										</div>
									</div>
								</div>
							</div>
						</li>
						<li class="p-3">
							<i class="bi bi-search fs-3"></i>
						</li>
						<li class="p-3">
							<i class="bi bi-handbag fs-3"></i>
						</li>
						<!-- svelte-ignore a11y-no-static-element-interactions -->
						<li class="p-3" id="list">
							<!-- svelte-ignore a11y-click-events-have-key-events -->
							<i
								class="bi bi-list fs-3"
								on:click={toggleVisibility}
								on:click={() => (isDark = !isDark)}
							></i>
						</li>
					</ul>
					<!-- Left links -->
				</div>
				<!-- Collapsible wrapper -->
			</div>
			<!-- Container wrapper -->
		</nav>
	</div>
	<div class:cont={isHidden} class:hidden={!isHidden}>



        
    </div>
</div>

<!-- modal -->
<style>
	.cont {
		margin: 0;
		width: 500px;
		height: 500px;

		background: #333;
		transition: all 0.7s;
	}
	.hidden {
		width: 0;
		transition: all 0.7s;
	}
	.dropdown-hover:hover > .dropdown-menu {
		display: inline-block;
	}
	/* Apply smooth transition to the element */

	.navbar-nav .nav-link {
		position: relative;
		transition: color 0.3s ease;
	}

	.navbar-nav .nav-link::before {
		content: '';
		position: absolute;
		bottom: -2px;
		left: 0;
		width: 0;
		height: 2px;
		background-color: red;
		transition: width 0.3s ease;
	}

	.navbar-nav .nav-link:hover {
		color: red;
	}

	.navbar-nav .nav-link:hover::before {
		width: 100%;
	}

	/* CSS Multi-line Comments - Custom CSS for the navigation menu */

	.navbar {
		background: transparent !important; /* Background is set to transparent */
		font-family: 'Roboto', sans-serif;
		font-size: 14px;
		padding: 0;
	}

	.navbar-nav .nav-link {
		padding: 0.5rem 1rem; /* Adding padding to the navigation links */
	}

	/* Custom CSS for Underlined Gradient Link to the navigation menu */

	/* Custom styles for the expanding underline effect */

	.navbar-nav .nav-link {
		position: relative; /* Establishing a positioning context for the pseudo-element */
		/* Making the text bold */
	}

	.navbar-nav .nav-link::before {
		content: ''; /* Creating a pseudo-element for the underline */
		position: absolute; /* Absolutely positioning the underline */
		bottom: 0; /* Positioning the underline at the bottom of the link */
		left: 0; /* Positioning the underline starting from the left */
		width: 100%; /* Making the underline span the full width of the link */
		height: 3px; /* Setting the thickness of the underline */
		background: linear-gradient(
			to right,
			blue,
			red,
			blue
		); /* Applying a gradient background to the underline */
		transform: scaleX(0); /* Initially hiding the underline with no width */
		transform-origin: left; /* Setting the transform origin to the left */
		transition: transform 0.3s ease; /* Adding a transition for smooth animation */
	}

	.navbar-nav .nav-link:hover::before {
		transform: scaleX(1); /* Expanding the underline to full width on hover */
	}
	li {
		font-size: 18px;
	}
	i {
		cursor: pointer;
	}
	.dark {
		transition: transform 0.8s ease; /* Agrega una transición suave */
		transform: translateX(0px);
	}

	.light {
		/* Estilos adicionales aquí */
		transition: transform 0.8s ease;
		transform: translateX(0);
		position: relative;
	}
</style>
