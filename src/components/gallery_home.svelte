<!-- Modal gallery -->
<section class="p-5">
	<!-- Section: Images -->
	<section class="">
		<div class="row">
			<div class="col-lg-3 col-md-12 mb-4 mb-lg-0 image">
				<div class="bg-image hover-overlay ripple shadow-1-strong" data-ripple-color="light">
					<!-- svelte-ignore a11y-missing-attribute -->
					<img src="https://mdbcdn.b-cdn.net/img/screens/yt/screen-video-1.webp" class="w-100" />
					<a href="#!" data-mdb-toggle="modal" data-mdb-target="#exampleModal1">
						<div class="mask" style="background-color: rgba(251, 251, 251, 0.2);"></div>
					</a>
					<div class="overlay">
						<div class="text">Hello World</div>
					</div>
				</div>
			</div>

			<div class="col-lg-3 mb-4 mb-lg-0 image">
				<div class="bg-image hover-overlay ripple shadow-1-strong" data-ripple-color="light">
					<!-- svelte-ignore a11y-missing-attribute -->
					<img src="https://mdbcdn.b-cdn.net/img/screens/yt/screen-video-2.webp" class="w-100" />
					<a href="#!" data-mdb-toggle="modal" data-mdb-target="#exampleModal2">
						<div class="mask" style="background-color: rgba(251, 251, 251, 0.2);"></div>
					</a>
					<div class="overlay">
						<div class="text">Hello World</div>
					</div>
				</div>
			</div>

			<div class="col-lg-3 mb-4 mb-lg-0 image">
				<div class="bg-image hover-overlay ripple shadow-1-strong" data-ripple-color="light">
					<!-- svelte-ignore a11y-missing-attribute -->
					<img src="https://mdbcdn.b-cdn.net/img/screens/yt/screen-video-3.webp" class="w-100" />
					<a href="#!" data-mdb-toggle="modal" data-mdb-target="#exampleModal3">
						<div class="mask" style="background-color: rgba(251, 251, 251, 0.2);"></div>
					</a>
					<div class="overlay">
						<div class="text">Hello World</div>
					</div>
				</div>
			</div>

			<div class="col-lg-3 mb-4 mb-lg-0 image">
				<div class="bg-image hover-overlay ripple shadow-1-strong" data-ripple-color="light">
					<!-- svelte-ignore a11y-missing-attribute -->
					<img src="https://mdbcdn.b-cdn.net/img/screens/yt/screen-video-3.webp" class="w-100" />
					<a href="#!" data-mdb-toggle="modal" data-mdb-target="#exampleModal3">
						<div class="mask" style="background-color: rgba(251, 251, 251, 0.2);"></div>
					</a>
					<div class="overlay">
						<div class="text">Hello World</div>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- Section: Images -->


</section>

<!-- Modal gallery -->

<style>
	.overlay {
		position: absolute;
		top: 0;
		bottom: 0;
		left: 0;
		right: 0;
		height: 100%;
		width: 100%;
		opacity: 0;
		transition: 0.5s ease;
		background-color: #008cba;
	}

	.image:hover .overlay {
		opacity: 0.8;
	}
	.text {
		color: white;
		font-size: 20px;
		position: absolute;
		top: 50%;
		left: 50%;
		-webkit-transform: translate(-50%, -50%);
		-ms-transform: translate(-50%, -50%);
		transform: translate(-50%, -50%);
		text-align: center;
	}
	.image{
		cursor: pointer;
	}
</style>
