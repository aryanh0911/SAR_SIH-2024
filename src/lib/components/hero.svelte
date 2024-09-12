<script>

</script>


<section class="py-10">
	<div class="px-6 w-fit mx-auto">
        <div class="container mx-auto">
            <div class="image-container rounded-xl overflow-hidden relative">
                <img src="/Images/Hero-images/earth.png" alt="" class="object-cover h-full w-full" />
                <div class="hero-text absolute z-10 bottom-8 p-4 px-6">
                    <div class="title text-3xl pb-2 text-[#e5e5e5]">SAR IMAGE DETECTION</div>
                    <div class="description text-[#c4c3c3] max-w-[60%]">
                            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempora perspiciatis dolores iusto expedita vitae laboriosam neque officia! Deserunt tenetur repellendus reiciendis error! Molestias, hic quod necessitatibus expedita illum aliquam a!
                    </div>
                        <button class="rounded-md px-4 py-2 bg-[#E4FF00] mt-4">Learn More</button>
                </div>
            </div>
            <div class="implementations text-[#bdbaba] rounded-xl bg-[#0F121F] p-4">
                <p class="text-2xl text-[#e5e5e5]">Recent Implementation</p>
        
                    <ul class="list">
                        <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</li>
                        <li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
                        <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</li>
                        <li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
                    </ul>
            </div>
        </div>
    </div>
</section>


<style>
	section {
		background-color: #0b0c15;
	}

	.container {
		display: grid;
		grid-template-columns: 2fr .7fr;
		gap: 2rem;
		max-width: 1440px;

        @media (max-width: 1000px) {
            grid-template-columns: 1fr;
        }
	}

	.title {
		font-family: Alata, sans-serif;
		font-weight: 400;
	}
	.description {
		font-family: Alata, sans-serif;
	}

	.image-container::after {
		content: '';
		position: absolute;
		inset: 0;
		z-index: 0;
        background: linear-gradient(90deg, #0F121F 12.75%, rgba(15, 18, 31, 0.81) 24.64%, rgba(30, 43, 60, 0) 108.08%);

	}

    button{
        font-family: Alata, sans-serif;
    }

    .list li{
        padding-block: 1rem;
        border-bottom: 1px solid rgba(255, 255, 255, 0.146);
    }

    .implementations p {
        font-family: Alata;
    }
</style>
