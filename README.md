<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Website</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">

  
    <nav class="bg-white shadow-md">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between items-center py-4">
                <a href="#" class="text-xl font-bold text-gray-800">ShopEase</a>
                <ul class="flex space-x-6">
                    <li><a href="#" class="text-gray-700 hover:text-blue-500">Home</a></li>
                    <li><a href="#" class="text-gray-700 hover:text-blue-500">Shop</a></li>
                    <li><a href="#" class="text-gray-700 hover:text-blue-500">Contact</a></li>
                    <li><a href="#" class="text-gray-700 hover:text-blue-500">Cart 🛒</a></li>
                </ul>
            </div>
        </div>
    </nav>

   
    <header class="bg-blue-500 text-white text-center py-16">
        <h1 class="text-4xl font-bold">Discover the Best Deals!</h1>
        <p class="mt-2">Shop top-quality products at unbeatable prices.</p>
        <a href="#" class="mt-4 inline-block bg-white text-blue-500 font-bold py-2 px-6 rounded-full shadow-md">Shop Now</a>
    </header>

    
    <section class="max-w-6xl mx-auto px-4 py-10">
        <h2 class="text-2xl font-bold text-gray-800 mb-6">Featured Products</h2>
        
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
            
            <div class="bg-white p-4 rounded-lg shadow-md">
                <img src="e1.jpg" alt="Product 1" class="w-full h-40 object-cover rounded">
                <h3 class="text-lg font-semibold mt-2">Product 1</h3>
                <p class="text-gray-600">$49.99</p>
                <button class="mt-2 bg-blue-500 text-white py-1 px-3 rounded hover:bg-blue-600">Add to Cart</button>
            </div>

           
            <div class="bg-white p-4 rounded-lg shadow-md">
                <img src="e2.jpg" alt="Product 2" class="w-full h-40 object-cover rounded">
                <h3 class="text-lg font-semibold mt-2">Product 2</h3>
                <p class="text-gray-600">$39.99</p>
                <button class="mt-2 bg-blue-500 text-white py-1 px-3 rounded hover:bg-blue-600">Add to Cart</button>
            </div>

           
            <div class="bg-white p-4 rounded-lg shadow-md">
                <img src="e3.jpg" alt="Product 3" class="w-full h-40 object-cover rounded">
                <h3 class="text-lg font-semibold mt-2">Product 3</h3>
                <p class="text-gray-600">$29.99</p>
                <button class="mt-2 bg-blue-500 text-white py-1 px-3 rounded hover:bg-blue-600">Add to Cart</button>
            </div>

            
            <div class="bg-white p-4 rounded-lg shadow-md">
                <img src="e4.jpg" alt="Product 4" class="w-full h-40 object-cover rounded">
                <h3 class="text-lg font-semibold mt-2">Product 4</h3>
                <p class="text-gray-600">$59.99</p>
                <button class="mt-2 bg-blue-500 text-white py-1 px-3 rounded hover:bg-blue-600">Add to Cart</button>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-white text-center py-4 mt-10">
        <p>&copy; 2025 ShopEase. All Rights Reserved.</p>
    </footer>

</body>
</html>
