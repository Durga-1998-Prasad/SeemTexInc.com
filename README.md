# SeemTexInc.com
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SeamTex Inc.</title>
    <style>
        body {
            background-image: url('https://saintpetersuniversity1-my.sharepoint.com/:i:/g/personal/tdurgaprasad_saintpeters_edu/EaXvQokTeg1GuZyihQiXvaEB6YzzxQMD-4gWrkfn2xHAxQ?e=rq248D.jpg'); /* Replace 'your-background-image-file.jpg' with your actual image file name */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif; /* Add your preferred font-family here */
        }

        /* Add your additional CSS styles here */
            /* Your existing styles */
        #products-gallery {
            margin-top: 20px;
            text-align: center;
        }

        .product-gallery-container {
            display: flex;
            overflow: hidden; /* Ensure images do not overflow */
            transition: transform 3s ease-in-out; /* Transition effect */
        }

        .product-item {
            width: 200px; /* Adjust the width as needed */
            margin: 10px;
            text-align: center;
        }

        .product-item img {
            width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .product-item p {
            margin-top: 10px;
        }
    </style>
    <!-- Add your stylesheets, fonts, and other dependencies here -->
</head>

<body>
    <!-- Header Section -->
    <header>
        <!-- Navigation Menu can be added here -->
        <!-- Logo and other header elements can be added here -->
        <img src="seamtex_logo.jpg" alt="SeamTex Inc. Logo">
    </header>

    <!-- Home Page Content -->
    <section id="home">
        <div>
            <h1>SeamTex Inc.</h1>
            <p>Your Seamless Garment Manufacturer</p>
            <!-- Add a nice image or video of the factory here -->
        </div>

        <!-- Mission Section -->
        <div>
            <h2>Our Mission:</h2>
            <p>SeamTex Inc is committed to revolutionizing the seamless undergarment industry by offering a direct manufacturing
                solution that bridges China to your USA warehouse.</p>
        </div>

        <!-- About Us Section -->
        <div>
            <h2>About Us:</h2>
            <p>Welcome to SeamTex Inc – Your Premier Destination for Quality Seamless Undergarments</p>
            <p>At SeamTex Inc., we're more than just a seamless undergarment manufacturer; we're your dedicated partner in
                revolutionizing comfort and style. With a commitment to quality, innovation, and direct-to-warehouse
                efficiency, we stand as a beacon of reliability in the ever-evolving fashion landscape.</p>
        </div>

        <!-- Expert Management Section -->
        <div>
            <h2>Expert Management:</h2>
            <p>Our seasoned management team combines for over 70 years of collective experience, specializing in the
                manufacturing, development, and creation of high-quality seamless garments.</p>
        </div>

        <!-- Proximity Section -->
        <div>
            <h2>Proximity, Not Just Geographically:</h2>
            <p>Our newly established sales office in the heart of New York City ensures seamless communication, understanding
                your unique needs, and providing instant solutions. Say goodbye to the hassles of flying to China – we're
                right here to cater to your requirements.</p>
        </div>

        <!-- What Sets Us Apart Section -->
        <div>
            <h2>What Sets Us Apart:</h2>
            <ul>
                <li>
                    <h3>Cost-Efficiency Redefined:</h3>
                    <p>By choosing SeamTex Inc., you're choosing a cost-effective solution. Our direct ownership of the
                        manufacturing process allows us to offer competitive pricing without compromising on the integrity
                        of our products.</p>
                    <!-- Add image here -->
                    <!-- Products Gallery Section -->
                </li>
                <li>
                    <h3>Quality without Compromise:</h3>
                    <p>We take pride in delivering seamless undergarments that prioritize both comfort and durability. Our
                        rigorous quality control measures ensure that every piece meets the highest standards, promising a
                        luxurious feel and a perfect fit.</p>
                    <!-- Add image here -->

                </li>
                <li>
                    <h3>Direct Manufacturing Advantage:</h3>
                    <p>SeamTex Inc. cuts out the middleman, ensuring a direct link from our state-of-the-art facilities in
                        China to your USA warehouse. This not only guarantees superior quality but also streamlines the
                        entire process for your convenience.</p>
                    <!-- Add image here -->
                </li>
            </ul>
        </div>

        <!-- Products Gallery Section -->
    <section id="products-gallery">
        <h2>Products Gallery</h2>
        <div class="product-gallery-container">
            <!-- Product 1 -->
            <div class="product-item">
                <img src="images/product1.jpg" alt="Product 1">
                <p>Product 1 Description</p>
            </div>
            <!-- Product 2 -->
            <div class="product-item">
                <img src="images/product2.jpg" alt="Product 2">
                <p>Product 2 Description</p>
            </div>
            <!-- Product 3 -->
            <div class="product-item">
                <img src="images/product3.jpg" alt="Product 3">
                <p>Product 3 Description</p>
            </div>
            <!-- Add similar blocks for products 4 to 13 -->
            <!-- Product 4 -->
            <div class="product-item">
                <img src="images/product4.jpg" alt="Product 4">
                <p>Product 4 Description</p>
            </div>
            <!-- Product 5 -->
            <div class="product-item">
                <img src="images/product5.jpg" alt="Product 5">
                <p>Product 5 Description</p>
            </div>
            <!-- Product 6 -->
            <div class="product-item">
                <img src="images/product6.jpg" alt="Product 6">
                <p>Product 6 Description</p>
            </div>
            <!-- Product 7 -->
            <div class="product-item">
                <img src="images/product7.jpg" alt="Product 7">
                <p>Product 7 Description</p>
            </div>
            <!-- Product 8 -->
            <div class="product-item">
                <img src="images/product8.jpg" alt="Product 8">
                <p>Product 8 Description</p>
            </div>
            <!-- Product 9 -->
            <div class="product-item">
                <img src="images/product9.jpg" alt="Product 9">
                <p>Product 9 Description</p>
            </div>
            <!-- Product 10 -->
            <div class="product-item">
                <img src="images/product10.jpg" alt="Product 10">
                <p>Product 10 Description</p>
            </div>
       </div>
    </section>

    <script>
        // JavaScript for the slideshow
        const container = document.querySelector('.product-gallery-container');
        let productIndex = 0;

        function slideProducts() {
            productIndex++;
            container.style.transform = `translateX(${-productIndex * 220}px)`; // Adjust width + margin
        }

        setInterval(slideProducts, 5000); // Slide every 5 seconds
    </script>
        <div>
            <h2>Our Range of Seamless Garments</h2>
            <p>SeamTex Inc offers a wide range of seamless garments with customization options for bras, underwear,
                shapewear, activewear, and more.</p>
            <!-- Show products with arrows as requested -->
            <!-- Use a similar style as the provided example -->
        </div>
    </section>

    <!-- Our Process Page Section -->
    <section id="process">
        <h2>Our Process</h2>
        <p>Seeking a manufacturing partner committed to your brand's success? It's simple with SeamTex Inc’s one-stop OEM
            solution.</p>

        <!-- Design and Conceptualization Section -->
        <div>
            <h3>Design and Conceptualization:</h3>
            <p>Our journey begins with visionary designers conceptualizing design, considering factors such as style,
                functionality, and material choice. Detailed sketches and digital models set the foundation for our
                creations.</p>
        </div>

        <!-- Pattern Making Section -->
        <div>
            <h3>Pattern Making:</h3>
            <p>Expert pattern makers translate design concepts into precise templates, using advanced CAD software for
                accuracy. These patterns guide the seamless knitting process to follow.</p>
        </div>

        <!-- Material Selection Section -->
        <div>
            <h3>Material Selection:</h3>
            <p>We meticulously select premium fabrics, focusing on stretch, breathability, and durability to meet the high
                standards of comfort and performance that define our brand.</p>
        </div>

        <!-- Knitting/Weaving Section -->
        <div>
            <h3>Knitting/Weaving:</h3>
            <p>Harnessing state-of-the-art seamless knitting machines, we produce tubular fabrics that form the core of our
                garments. This seamless approach ensures unparalleled comfort and a flawless fit.</p>
        </div>

        <!-- Cutting/Assembly Section -->
        <div>
            <h3>Cutting/Assembly:</h3>
            <p>Automated cutting machines precisely cut fabric according to the perfected patterns, ensuring consistency
                and accuracy in every piece. Join the cut pieces using advanced sewing techniques or seamless bonding
                methods, ensuring a smooth and comfortable finish. Add features like elastic bands, straps, or closures as
                required.</p>
        </div>

        <!-- Quality Control Section -->
        <div>
            <h3>Quality Control:</h3>
            <p>Rigorous quality control measures are embedded throughout the process. From fabric inspection to final
                garment checks, we guarantee excellence in every detail.</p>
        </div>

        <!-- Dyeing/Finishing Finesse Section -->
        <div>
            <h3>Dyeing/Finishing Finesse:</h3>
            <p>For garments requiring color, we apply meticulous dyeing or printing techniques. Excess fabric and threads
                are trimmed, and care labels and brand tags are attached for a polished appearance.</p>
        </div>

        <!-- Packaging/Distribution Section -->
        <div>
            <h3>Packaging/Distribution:</h3>
            <p>Finished garments are carefully placed into suitable packaging, ensuring they remain in pristine condition
                during transportation. Ship the finalized products to distribution centers, retailers, or directly to
                customers. This streamlined process ensures precision, comfort, and quality in every seamless garment we
                create at SeamTex Inc.</p>
        </div>
    </section>

    <!-- Our Products Section -->
    <section id="products">
        <h2>Our Products</h2>
        <!-- Dropdown with different categories -->
        <select>
            <option value="seamless_bras">Seamless Bras</option>
            <option value="seamless_underwear">Seamless Underwear</option>
            <option value="seamless_workout_wear">Seamless Workout Wear</option>
            <option value="seamless_shapewear">Seamless Shapewear</option>
            <option value="seamless_clothing">Seamless Clothing</option>
        </select>
    </section>

    <!-- Contact Us Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <!-- Add a contact form here -->
        <p>Contact Information:</p>
        <p>Sheena Mirchandani<br> sheenamirchandani@yahoo.com<br> (973)-908-4962</p>
        <p>Business Partner:</p>
        <p>Peter Mirchandani<br> peter@mediavisioncorp.com<br> (973)-420-4242</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <!-- Add footer content and links here -->
    </footer>

    <!-- Add your scripts and other dependencies here -->
</body>

</html>
