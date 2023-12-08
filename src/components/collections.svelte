<div class="row p-5">
	<div class="col-md-12 col-lg-12 col-sm-12 mb-4">
		<div class="d-flex justify-content-center">
			<h5>New Products</h5>
		</div>
	</div>
	<div class="col-md-12 col-lg-12 col-sm-12 mb-4">
		<div class="d-flex justify-content-center">
			<h3>Shop The New Collection</h3>
		</div>
	</div>
</div>
<div class="container">
	<div class="box">
		<div class="imgBx">
			<!-- svelte-ignore a11y-missing-attribute -->
			<img
				src="https://images.unsplash.com/photo-1579748138140-ce9ef2c32db1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80"
			/>
		</div>
		<div class="content d-flex">
			<div
				class="d-flex justify-content-between border cart"
				style="background-color: black;width:100%;cursor:pointer"
			>
				<div class="d-flex justify-content-center pt-3 ps-3">
					<h6>Add To Cart</h6>
				</div>
				<div class="d-flex justify-content-center pe-2">
					<i class="bi bi-cart fs-4 p-1"></i>
				</div>
			</div>
		</div>
        <div class="text-below-image">
			<p>Accessories, New Collection, Women Cream Tote Bag $35.00</p>
		</div>
	</div>

	<div class="box">
		<div class="imgBx">
			<!-- svelte-ignore a11y-missing-attribute -->
			<img
				src="https://images.unsplash.com/photo-1579748138140-ce9ef2c32db1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80"
			/>
		</div>
		<div class="content d-flex">
			<div
				class="d-flex justify-content-between border cart"
				style="background-color: black;width:100%;cursor:pointer"
			>
				<div class="d-flex justify-content-center pt-3 ps-3">
					<h6>Add To Cart</h6>
				</div>
				<div class="d-flex justify-content-center pe-2">
					<i class="bi bi-cart fs-4 p-1"></i>
				</div>
			</div>
		</div>
        <div class="text-below-image">
			<p>Accessories, New Collection, Women Cream Tote Bag $35.00</p>
		</div>
	</div>
	<div class="box">
		<div class="imgBx">
			<!-- svelte-ignore a11y-missing-attribute -->
			<img
				src="https://images.unsplash.com/photo-1579748138140-ce9ef2c32db1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80"
			/>
		</div>
		<div class="content d-flex">
			<div
				class="d-flex justify-content-between border cart"
				style="background-color: black;width:100%;cursor:pointer"
			>
				<div class="d-flex justify-content-center pt-3 ps-3">
					<h6>Add To Cart</h6>
				</div>
				<div class="d-flex justify-content-center pe-2">
					<i class="bi bi-cart fs-4 p-1"></i>
				</div>
			</div>
		</div>
        <div class="text-below-image">
			<p>Accessories, New Collection, Women Cream Tote Bag $35.00</p>
		</div>
	</div>
	<div class="box">
		<div class="imgBx">
			<!-- svelte-ignore a11y-missing-attribute -->
			<img
				src="https://images.unsplash.com/photo-1579748138140-ce9ef2c32db1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80"
			/>
		</div>

		<div class="content d-flex">
			<div
				class="d-flex justify-content-between border cart"
				style="background-color: black;width:100%;cursor:pointer"
			>
				<div class="d-flex justify-content-center pt-3 ps-3">
					<h6>Add To Cart</h6>
				</div>
				<div class="d-flex justify-content-center pe-2">
					<i class="bi bi-cart fs-4 p-1"></i>
				</div>
			</div>
		</div>
		<div class="text-below-image">
			<p>Accessories, New Collection, Women Cream Tote Bag $35.00</p>
		</div>
	</div>
</div>

<style>
	* {
		margin: 0;
		padding: 0;
	}

	.box {
		cursor: pointer;
	}
	.container .box .text-below-image {
		position: absolute;
		bottom: 0;
		left: 0;
		width: 100%;
		height: 100%;
		text-align: center;
		padding: 10px;
		background: rgba(0, 0, 0, 0.4);
		color: #fff;
		font-size: 14px;
		opacity: 0;
		transition: opacity 0.5s;
	}

	.container .box:hover .text-below-image {
		opacity: 1;
	}
	.container {
		position: relative;
		width: 1160px;
		display: flex;
		justify-content: center;
		flex-wrap: wrap;
		transform-style: preserve-3d;
		perspective: 500px;
		margin: auto;
	}
	.container .box {
		position: relative;
		width: 275px;
		height: 275px;
		background: #000;
		transition: 0.5s;
		transform-style: preserve-3d;
		overflow: hidden;
		margin-right: 15px;
	}

	.container .box:hover {
		transform: rotateY(0deg) scale(1.1);
		z-index: 1;
		box-shadow: 0 25px 40px rgba(0, 0, 0, 0.5);
	}
	.container .box .imgBx {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
	}
	.container .box .imgBx:before {
		content: '';
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		background: linear-gradient(180deg, rgb(225, 215, 215), #b7b7b7);
		z-index: 1;
		opacity: 0;
		transition: 0.5s;
		mix-blend-mode: multiply;
	}
	.container .box:hover .imgBx:before {
		opacity: 1;
	}
	.container .box .imgBx img {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		object-fit: cover;
	}
	.container .box .content {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		z-index: 1;
		display: flex;
		align-items: flex-end;
		box-sizing: border-box;
	}

	.container .box .content div {
		color: #fff;
		transition: 0.5s;
		font-size: 14px;
		transform: translateY(200px);
		transition-delay: 0s;
	}
	.container .box:hover .content div {
		transform: translateY(0px);
	}
</style>
