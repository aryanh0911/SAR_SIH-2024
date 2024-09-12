<script>
    // import dragDropFile from 'Images/Tool-Images/drag-drop-file.png'
</script>


<section class="py-4">
    <div class="px-6 mx-auto">
        <div class="container mx-auto max-w-[1440px] rounded-lg p-4">
            <div class="single-image p-4">
                <div class="flex justify-between items-center">
                    <p class="text-white text-2xl">Single-Image Selection</p>
                    <button class="rounded-md px-6 py-2 bg-[#E4FF00]">Done</button>
                </div>
                <div class="aspect-[1/.7] bg-[#0E1325] mt-2 rounded-xl flex-grow flex justify-center items-center">
                    <div class="flex flex-col justify-center items-center gap-5">
                        <input type="file" accept="image/*" class="image-upload-input">
                        <img src='Images/Tool-Images/drag-drop-file.png' alt="" class="w-40">
                    </div>    
                </div>
            </div>

            <div class="multi-image p-4">
                <div class="flex justify-between items-center">
                    <p class="text-white text-2xl">Multi-Image Selection</p>
                    <button class="rounded-md px-6 py-2 bg-[#E4FF00]">Done</button>
                </div>

                <div class="sub-grid">
                    <div class=" bg-[#0E1325] mt-2 rounded-xl flex justify-center items-center">
                        <div class="flex flex-col justify-center items-center gap-5">
                            <input type="file" accept="image/*" class="image-upload-input">
                            <img src='Images/Tool-Images/drag-drop-file.png' alt="" class="w-40">
                        </div>
                    </div>
                    <div class="text-input bg-[#0E1325] rounded-xl flex justify-center items-center px-6 py-4">
                        <input type="text" placeholder="Insert Data-set Link" class="w-full rounded-lg h-full p-4 input-bg">
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>


<style>
    .container {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 1rem;
        background: linear-gradient(180.05deg, #101630 0.04%, #1A2141 220.73%);

        @media (max-width: 750px) {
            grid-template-columns: 1fr;
        }
    }

    .single-image,
    .multi-image {
        display: flex;
        flex-direction: column;
    }
    
    .sub-grid {
        display: grid;
        grid-template-rows: 4fr 1fr;
        gap: 1rem;
        flex-grow: 1;
    }
    
    .sub-grid > div {
        min-height: 0; /* allows the grid items to shrink below their content size */
    }

    .input-bg {
        background: linear-gradient(to left, #31364D, #252A3D);
        border: none;
        color: white;
    }

    .input-bg::placeholder {
        color: rgb(221, 220, 220);
    }
</style>