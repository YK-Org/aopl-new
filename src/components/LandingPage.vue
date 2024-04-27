<template>
	<div class="h-full w-full bg-white">
		<!-- top navigation -->
		<div class="top-0 left-0 right-0 z-50 bg-orange-50">
			<div class="max-w-7xl mx-auto p-4">
				<div class="flex justify-between items-center">
					<div class="text-lg sm:text-2xl text-orange-600 font-bold">AOPL</div>
					<div class="hidden md:flex space-x-8 items-center">
						<a
							href="#home"
							class="text-gray-900 hover:text-orange-600 hover:underline transition"
							>Home</a
						>
						<a
							href="#about"
							class="text-gray-900 hover:text-orange-600 hover:underline transition"
							>About</a
						>
					</div>
					<div class="md:hidden">
						<button id="menu-toggle" class="text-gray-800 hover:text-white">
							<svg
								xmlns="http://www.w3.org/2000/svg"
								class="h-6 w-6"
								fill="none"
								viewBox="0 0 24 24"
								stroke="currentColor"
							>
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									stroke-width="2"
									d="M4 6h16M4 12h16M4 18h16"
								/>
							</svg>
						</button>
					</div>
				</div>
				<div id="mobile-menu" class="hidden md:hidden mt-4">
					<ul class="flex flex-col space-y-4">
						<a
							href="#home"
							class="text-gray-900 hover:text-orange-600 hover:underline transition"
							>Home</a
						>
						<a
							href="#about"
							class="text-gray-900 hover:text-orange-600 hover:underline transition"
							>About</a
						>
					</ul>
				</div>
			</div>
		</div>
		<!-- end of top navigation -->

		<!-- hero section -->
		<div class="h-screen w-full relative flex justify-center min-h-svh">
			<div class="relative w-full text-center bg-cover bg-center">
				<img
					class="w-full h-full inset-0 object-cover"
					src="https://images.pexels.com/photos/1033729/pexels-photo-1033729.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
					alt="Background image"
				/>

				<div
					class="absolute inset-0 h-full bg-gradient-to-t from-green-900 from-30% to-green-900/40 to-70% opacity-90"
				></div>
			</div>

			<div
				class="absolute max-w-7xl w-full flex justify-center items-center min-h-screen gap-8 mx-auto px-8 -mt-12"
			>
				<div class="flex h-full w-full flex-col gap-4 items-center">
					<h1
						class="text-center font-black text-orange-100 text-5xl sm:text-8xl drop-shadow-2xl break-all"
					>
						Authentic Ghanaian <br class="hidden sm:block" />
						<span class="text-orange-300">Palm Oil</span> Conveniently Packaged
						in Tins & Gallons
					</h1>
					<h2
						class="text-center text-lg sm:text-2xl font-light text-white drop-shadow-2xl"
					>
						Experience the Richness and Purity of Our Homegrown Palm Oil, Direct
						from Ghana
					</h2>

					<button
						class="rounded-full bg-orange-500 p-4 px-6 text-2xl w-fit font-semibold text-white transition-all delay-50 ease-in-out hover:bg-orange-600"
					>
						Order Now
					</button>
				</div>

				<!-- <div class="w-1/3">
					<img
						class="h-96 w-96 rounded-2xl object-fill sm:object-cover"
						src="@/assets/images/tin.webp"
						alt=""
						srcset=""
					/>
				</div> -->
			</div>
		</div>

		<!-- end hero section -->

		<!-- second section -->
		<div
			class="relative flex min-h-screen w-full flex-col gap-8 px-8 py-16 sm:py-32"
		>
			<div
				class="mx-auto w-full max-w-7xl flex flex-col sm:flex-row items-center justify-between gap-16 rounded-[2rem] sm:rounded-[3rem] bg-amber-50 p-8 sm:p-16 transition-all delay-50 ease-in-out border-4 border-transparent hover:border-amber-100"
			>
				<div class="flex w-full items-center justify-center">
					<img
						class="h-full w-full rounded-2xl object-cover"
						src="@/assets/images/tin.webp"
						alt=""
						srcset=""
					/>
				</div>

				<div class="flex flex-col items-start justify-center gap-4 w-full">
					<h2 class="text-left font-bold text-gray-800 text-4xl sm:text-5xl">
						Easy to Carry, Stays Fresh Longer
					</h2>
					<p class="text-left text-xl font-normal text-gray-600 leading-8">
						Experience the convenience of mobility and the assurance of extended
						freshness with our tinned palm oil.
					</p>
					<button
						class="rounded-full bg-orange-500 p-4 font-semibold text-white transition-all delay-50 ease-in-out hover:bg-orange-600"
					>
						Order Now
					</button>
				</div>
			</div>

			<div
				class="mx-auto w-full max-w-7xl flex flex-col sm:flex-row items-center justify-between gap-16 rounded-[2rem] sm:rounded-[3rem] bg-orange-50 p-8 sm:p-16 transition-all delay-50 ease-in-out border-4 border-transparent hover:border-orange-100"
			>
				<div class="flex flex-col items-start justify-center gap-4 w-full">
					<h2 class="text-left font-bold text-gray-800 text-4xl sm:text-5xl">
						Convenient Gallon-Sized Palm Oil
					</h2>
					<p class="text-left text-xl font-normal text-gray-600 leading-8">
						Enjoy the convenience of our gallon-sized tinned palm oil, offering
						easy storage and extended freshness for all your cooking needs.
					</p>
					<button
						class="rounded-full bg-orange-500 p-4 font-semibold text-white transition-all delay-50 ease-in-out hover:bg-orange-600"
					>
						Order Now
					</button>
				</div>

				<div class="flex w-full items-center justify-center">
					<img
						class="h-full w-full rounded-2xl object-cover"
						src="@/assets/images/gallon.webp"
						alt=""
						srcset=""
					/>
				</div>
			</div>
		</div>

		<!-- end second section -->

		<!-- what others think section -->
		<div
			class="relative flex h-min w-full flex-col gap-16 p-8 sm:p-16 max-w-7xl mx-auto"
		>
			<h2
				class="text-center font-bold text-gray-800 text-4xl sm:text-6xl max-w-2xl mx-auto"
			>
				What Others Think About <span class="text-orange-500">PALMIGO</span>
			</h2>

			<div class="grid grid-cols-1 sm:grid-cols-2 gap-8">
				<div class="flex flex-col sm:flex-row border-2 border-gray-200 hover:border-orange-500 group transition-all delay-50 ease-in-out rounded-3xl bg-white">
					<img
						class="h-full w-full sm:w-1/3 object-cover rounded-t-3xl sm:rounded-tr-none sm:rounded-l-3xl"
						src="https://images.pexels.com/photos/11696003/pexels-photo-11696003.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2"
						alt=""
						srcset=""
					/>

					<div class="w-full sm:w-2/3 flex flex-col gap-2 p-8">
						<p class="text-left text-lg font-normal text-gray-800">
							I've been using this palm oil for my cooking for a few months now,
							and I'm truly impressed by the quality. It's rich, pure, and
							brings a distinct flavor to my dishes that reminds me of home.
							Plus, the tins and gallons make storage and usage so convenient
						</p>
						<p class="text-left text-md font-normal text-gray-500 group-hover:text-orange-500 transition-all delay-50 ease-in-out">
							- Ama, Accra
						</p>
					</div>
				</div>

				<div class="flex flex-col sm:flex-row border-2 border-gray-200 hover:border-orange-500 group transition-all delay-50 ease-in-out rounded-3xl bg-white">
					<img
						class="h-full w-full sm:w-1/3 object-cover rounded-t-3xl sm:rounded-tr-none sm:rounded-l-3xl"
						src="https://images.pexels.com/photos/4989135/pexels-photo-4989135.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2"
						alt=""
						srcset=""
					/>

					<div class="w-full sm:w-2/3 flex flex-col gap-2 p-8">
						<p class="text-left text-lg font-normal text-gray-800">
							This palm oil has transformed my cooking! Its authentic Ghanaian
							flavor enhances every dish, and the tin packaging is not only
							convenient but also ensures the oil stays fresh longer. I’m so
							glad I found this product!" -
						</p>
						<p class="text-left text-md font-normal text-gray-500 group-hover:text-orange-500 transition-all delay-50 ease-in-out">
							- Kojo, Kumasi
						</p>
					</div>
				</div>

				<div class="flex flex-col sm:flex-row border-2 border-gray-200 hover:border-orange-500 group transition-all delay-50 ease-in-out rounded-3xl bg-white">
					<img
						class="h-full w-full sm:w-1/3 object-cover rounded-t-3xl sm:rounded-tr-none sm:rounded-l-3xl"
						src="https://images.pexels.com/photos/17882855/pexels-photo-17882855/free-photo-of-black-woman-in-turban-sitting-on-chair-in-garden.jpeg?auto=compress&cs=tinysrgb&w=800"
						alt=""
						srcset=""
					/>

					<div class="w-full sm:w-2/3 flex flex-col gap-2 p-8">
						<p class="text-left text-lg font-normal text-gray-800">
							I switched to this brand of palm oil on a friend’s recommendation
							and haven’t looked back since. The oil is consistently fresh and
							authentic, just like what I grew up with in Ghana. The convenient
							gallon packaging is a bonus, making it easy to stock up.
						</p>
						<p class="text-left text-md font-normal text-gray-500 group-hover:text-orange-500 transition-all delay-50 ease-in-out">
							Yaa, London.
						</p>
					</div>
				</div>

				<div class="flex flex-col sm:flex-row border-2 border-gray-200 hover:border-orange-500 group transition-all delay-50 ease-in-out rounded-3xl bg-white">
					<img
						class="h-full w-full sm:w-1/3 object-cover rounded-t-3xl sm:rounded-tr-none sm:rounded-l-3xl"
						src="https://images.pexels.com/photos/6126975/pexels-photo-6126975.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2"
						alt=""
						srcset=""
					/>

					<div class="w-full sm:w-2/3 flex flex-col gap-2 p-8">
						<p class="text-left text-lg font-normal text-gray-800">
							As a professional chef, I prioritize quality ingredients, and this
							Ghanaian palm oil has exceeded my expectations. The flavor is
							unbeatable, and the packaging is perfectly designed for heavy
							kitchen use. It's my go-to oil now!
						</p>
						<p class="text-left text-md font-normal text-gray-500 group-hover:text-orange-500 transition-all delay-50 ease-in-out">
							- Chef David - Canada
						</p>
					</div>
				</div>
			</div>
		</div>

		<!-- more on product section -->
		<div
			class="relative flex flex-col sm:flex-row min-h-screen w-full max-w-7xl mx-auto gap-8 p-8 sm:p-16"
		>
			<div
				class="mx-auto flex w-full flex-col items-center gap-16 rounded-[2rem] sm:rounded-[3rem] bg-amber-50 p-8 sm:p-16 border-2 border-transparent hover:border-amber-100"
			>
				<div class="flex items-center justify-center w-2/3">
					<img
						class="h-full w-full rounded-2xl object-cover"
						src="@/assets/images/tin.webp"
						alt=""
						srcset=""
					/>
				</div>

				<div class="flex flex-col items-start justify-center gap-8 w-full">
					<div class="w-full flex flex-col gap-4">
						<h3 class="text-left font-bold text-gray-800 text-2xl sm:text-4xl">
							Easy to Carry, Stays Fresh Longer
						</h3>
						<p
							class="text-left text-lg sm:text-xl font-normal text-gray-600 leading-8"
						>
							Perfect for smaller households or occasional use, each tin ensures
							that the rich flavors and aromas are perfectly preserved from our
							farm to your kitchen.
						</p>

						<ul
							class="list-disc space-y-2 list-outside text-left text-lg sm:text-xl font-normal text-gray-600 leading-8"
						>
							<li class="ml-4">
								Purely Organic: Harvested from sustainably grown oil palms.
							</li>
							<li class="ml-4">
								Rich in Vitamins: High in vitamin E and beta-carotene for a
								healthier diet.
							</li>
							<li class="ml-4">
								No Additives: Free from artificial colors or preservatives.
							</li>
							<li class="ml-4">
								Long Shelf Life: Sealed to maintain freshness and quality.
							</li>
						</ul>
					</div>
					<button
						class="rounded-full bg-orange-500 p-4 font-semibold text-white transition-all delay-50 ease-in-out hover:bg-orange-600"
					>
						Order Now
					</button>
				</div>
			</div>
			<div
				class="mx-auto flex w-full flex-col items-center gap-16 rounded-[2rem] sm:rounded-[3rem] bg-orange-50 p-8 sm:p-16 border-2 border-transparent hover:border-orange-100"
			>
				<div class="flex items-center justify-center w-full">
					<img
						class="h-full w-full rounded-2xl object-cover"
						src="@/assets/images/gallon.webp"
						alt=""
						srcset=""
					/>
				</div>

				<div class="flex flex-col items-start justify-center gap-8 w-full">
					<div class="w-full flex flex-col gap-4">
						<h3 class="text-left font-bold text-gray-800 text-2xl sm:text-4xl">
							Bulk Convenience with Great Quality
						</h3>
						<p
							class="text-left text-lg sm:text-xl font-normal text-gray-600 leading-8"
						>
							For large families and culinary enthusiasts. This bulk packaging
							ensures that you always have enough of our premium, richly
							flavored palm oil on hand.
						</p>

						<ul
							class="list-disc space-y-2 list-outside text-left text-lg sm:text-xl font-normal text-gray-600 leading-8"
						>
							<li class="ml-4">
								Economical Packaging: Ideal for heavy usage at a better price
								point.
							</li>
							<li class="ml-4">
								Consistent Flavor: Delivers the same rich, authentic taste in
								every dish.
							</li>
							<li class="ml-4">
								Versatile Use: Perfect for frying, cooking, and traditional
								recipes.
							</li>
							<li class="ml-4">
								Easy Storage
							</li>
						</ul>
					</div>
					<button
						class="rounded-full bg-orange-500 p-4 font-semibold text-white transition-all delay-50 ease-in-out hover:bg-orange-600"
					>
						Order Now
					</button>
				</div>
			</div>
		</div>

		<!-- end more on product section -->

		<!-- about section -->
		<div
			class="w-full flex flex-col sm:flex-row items-center max-w-7xl min-h-screen mx-auto p-8 gap-16"
		>
			<div class="w-full sm:w-2/3 flex flex-col gap-10 items-start">
				<div class="w-full flex flex-col gap-4">
					<h3 class="text-left font-bold text-gray-800 text-4xl sm:text-5xl">
						Asare Odometa Plantations Limited (AOPL)
					</h3>
					<p class="text-left text-xl font-normal text-gray-600 leading-8">
						Was set up to produce high quality agricultural products in a
						sustainable manner while upholding the highest safety, health and
						environmental practices and building on the vast experience of its
						Managing Director in oil palm cultivation and plantation management.
					</p>
				</div>
				<div class="flex flex-wrap w-full items-start gap-8">
					<img
						class="w-auto h-12 object-cover grayscale hover:grayscale-0 transition ease-in-out duration-300 hover:delay-50"
						src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Kempinski_Logo_2015.svg/1200px-Kempinski_Logo_2015.svg.png"
						alt=""
						srcset=""
					/>
					<img
						class="w-auto h-12 object-cover grayscale hover:grayscale-0 transition ease-in-out duration-300 hover:delay-50"
						src="https://www.airportviewhotels.com/images/logo2.png"
						alt=""
						srcset=""
					/>
					<img
						class="w-auto h-12 object-cover grayscale hover:grayscale-0 transition ease-in-out duration-300 hover:delay-50"
						src="https://www.papaspizzaghana.com/wp-content/uploads/2015/09/papas_logo@2x.png"
						alt=""
						srcset=""
					/>
					<img
						class="w-auto h-12 object-cover grayscale hover:grayscale-0 transition ease-in-out duration-300 hover:delay-50"
						src="data:image/png;base64,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"
						alt=""
						srcset=""
					/>
				</div>

				<button
					class="rounded-full bg-orange-500 py-4 px-6 font-semibold text-white transition-all delay-50 ease-in-out hover:bg-orange-600"
				>
					Partner With Us
				</button>
			</div>
			<div class="w-full sm:w-1/3 flex flex-col items-center">
				<img
					class="h-auto w-auto rounded-2xl object-fill sm:object-cover"
					src="@/assets/images/tin.webp"
					alt=""
					srcset=""
				/>
			</div>
		</div>
		<!-- End about section -->

		<footer class="p-4 py-24 w-full bg-orange-600">
			<div
				class="flex flex-col sm:flex-row justify-between sm:items-start max-w-7xl mx-auto space-y-8 sm:space-y-0 px-4 sm:px-8"
			>
				<div class="flex flex-col w-1/3 space-y-2">
					<h1 class="text-4xl font-bold text-white">AOPL</h1>
					<p class="text-gray-200">Description</p>
				</div>
				<div
					class="w-2/3 flex flex-col sm:flex-row justify-between space-x-0 sm:space-x-12 space-y-12 sm:space-y-0 text-gray-900"
				>
					<div class="flex flex-col items-start w-full space-y-4">
						<a href="#" class="font-bold text-white">Links</a>
						<a
							href="#home"
							class="w-full text-white hover:text-white/50 hover:underline transition ease-in-out duration-300 hover:delay-50"
							>Home</a
						>
						<a
							href="#about"
							class="w-full text-white hover:text-white/50 hover:underline transition ease-in-out duration-300 hover:delay-50"
							>About</a
						>
					</div>

					<div class="flex flex-col items-start w-full space-y-4">
						<a href="#" class="font-bold text-white">Socials</a>
						<a
							href="#"
							class="w-full text-white hover:text-white/50 hover:underline transition ease-in-out duration-300 hover:delay-50"
							>X (Formerly Twitter)</a
						>
						<a
							href="#"
							class="w-full text-white hover:text-white/50 hover:underline transition ease-in-out duration-300 hover:delay-50"
							>Instagram</a
						>
						<a
							href="#"
							class="w-full text-white hover:text-white/50 hover:underline transition ease-in-out duration-300 hover:delay-50"
							>Facebook</a
						>
					</div>
				</div>
			</div>
		</footer>
	</div>
</template>
