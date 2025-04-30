index.<!DOCTYPE html>
<html>
<head>
	<title><title>HARLEXCLICKS - View Ads, Earn Rewards</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Header -->
    <header class="bg-yellow-600 text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">HARLEXCLICKS</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#" class="hover:underline">Home</a></li>
                    <link rel="stylesheet" type="text/css" href="">
                    <li><a href="#" class="hover:underline">Ads</a></li>
                    <link rel="stylesheet" type="text/css" href="">
                    <li><a href="#" class="hover:underline">Profile</a></li>
                    <link rel="stylesheet" type="text/css" href="">
                    <li><a href="#" class="hover:underline">Login</a></li>
                    <link rel="stylesheet" type="text/css" href="www.dreamleaguesoccer.com">
                </ul>
            </nav>
        </div>
    </header>
<!-- Main Content -->
    <main class="container mx-auto py-8">
        <h2 class="text-3xl font-semibold text-center mb-8">Explore Ads</h2>
        <div id="ads-container" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <!-- Ad Cards (Populated by JavaScript) -->
        </div>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white p-4">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 HARLEXCLICKS. All rights reserved By Kaya Marvin.</p>
            <p><a href="#" class="hover:underline">Terms</a> | <a href="#" class="hover:underline">Privacy</a></p>
        </div>
    </footer>

    <script>
        // Sample ad data (replace with real data from a backend)
        const ads = [
            {
                id: 1,
                title: "Summer Sale!",
                description: "Get 50% off on all summer clothing.",
                image: "https://via.placeholder.com/300x200?text=Summer+Sale",
                link: "https://teacher.ac/st-margret-college-makerere-2020-2021-uce-uace-results-location-and-facilities/"
            },
            {
                id: 2,
                title: "Tech Gadgets",
                description: "Explore the latest in tech innovation.",
                image: "https://via.placeholder.com/300x200?text=Tech+Gadgets",
                link: "https://www.jumia.ug/"
            },
            {
                id: 3,
                title: "Travel Deals",
                description: "Book your dream vacation today!",
                image: "https://via.placeholder.com/300x200?text=Travel+Deals",
                link: "https://merchandiseuganda.com/contributor/rayanshoe/"
            }
        id: 4,
        title: "Dream League Soccer"
        description: "explore the world's HARLEXCLICKS"
        image:"https://media.karousell.com/media/photos/products/2019/07/30/laptop_sale_1564464323_327415740_progressive"
        link:"https://www.bestbuy.ca/en-ca/collection/laptops-on-sale/46082"
// Function to render ads
        function renderAds() {
            const adsContainer = document.getElementById('ads-container');
            adsContainer.innerHTML = '';

            ads.forEach(ad => {
                const adCard = `
                    <div class="bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition">
                        <img src="${ad.image}" alt="${ad.title}" class="w-full h-48 object-cover">
                        <div class="p-4">
                            <h3 class="text-xl font-semibold">${ad.title}</h3>
                            <p class="text-gray-600 mt-2">${ad.description}</p>
                            <a href="${ad.link}" class="mt-4 inline-block bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">View Ad</a>
                        </div>
                    </div>
                `;
                adsContainer.innerHTML += adCard;
            });
        }

        // Initialize
        document.addEventListener('DOMContentLoaded', renderAds);
    </script>
</body>
</html></title>
</head>
<body>

</body>
</html>
