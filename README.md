# innobytes
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>King Sukh Guest House</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-900">
    <!-- Header Section -->
    <header class="bg-blue-900 text-white py-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold">King Sukh Guest House</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#about" class="hover:underline">About</a></li>
                    <li><a href="#rooms" class="hover:underline">Rooms</a></li>
                    <li><a href="#contact" class="hover:underline">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-cover bg-center h-screen text-center text-white flex items-center justify-center" style="background-image: url('https://via.placeholder.com/1920x1080');">
        <div class="bg-black bg-opacity-50 p-8 rounded">
            <h2 class="text-4xl font-bold mb-4">Welcome to King Sukh Guest House</h2>
            <p class="mb-6">Experience comfort and luxury at affordable prices.</p>
            <a href="#rooms" class="bg-blue-500 text-white py-2 px-4 rounded hover:bg-blue-700">Explore Rooms</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-gray-50">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-8">About Us</h2>
            <p class="max-w-2xl mx-auto">King Sukh Guest House offers premium accommodations with world-class amenities, ensuring your stay is both comfortable and memorable.</p>
        </div>
    </section>

    <!-- Rooms Section -->
    <section id="rooms" class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-8">Our Rooms</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white shadow rounded-lg overflow-hidden">
                    <img src="https://via.placeholder.com/300x200" alt="Room 1" class="w-full">
                    <div class="p-4">
                        <h3 class="text-xl font-bold">Deluxe Room</h3>
                        <p class="text-gray-600">A spacious room with all modern amenities.</p>
                    </div>
                </div>
                <div class="bg-white shadow rounded-lg overflow-hidden">
                    <img src="https://via.placeholder.com/300x200" alt="Room 2" class="w-full">
                    <div class="p-4">
                        <h3 class="text-xl font-bold">Executive Room</h3>
                        <p class="text-gray-600">Perfect for business travelers with added facilities.</p>
                    </div>
                </div>
                <div class="bg-white shadow rounded-lg overflow-hidden">
                    <img src="https://via.placeholder.com/300x200" alt="Room 3" class="w-full">
                    <div class="p-4">
                        <h3 class="text-xl font-bold">Family Suite</h3>
                        <p class="text-gray-600">Spacious and ideal for families.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-50">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl font-bold mb-8">Contact Us</h2>
            <form class="max-w-lg mx-auto">
                <input type="text" placeholder="Name" class="w-full mb-4 p-2 border rounded">
                <input type="email" placeholder="Email" class="w-full mb-4 p-2 border rounded">
                <textarea placeholder="Message" class="w-full mb-4 p-2 border rounded"></textarea>
                <button class="bg-blue-500 text-white py-2 px-4 rounded hover:bg-blue-700">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-blue-900 text-white py-4">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 King Sukh Guest House. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
