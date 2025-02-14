<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   Food Sales Website
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
 </head>
 <body class="bg-gray-100 font-roboto">
  <header class="bg-white shadow">
   <div class="container mx-auto p-4 flex justify-between items-center">
    <h1 class="text-3xl font-bold">
     food coffee
    </h1>
    <nav>
     <ul class="flex space-x-4">
      <li>
       <a class="text-gray-700 hover:text-gray-900" href="#">
        Home
       </a>
      </li>
      <li>
       <a class="text-gray-700 hover:text-gray-900" href="#">
        Menu
       </a>
      </li>
      <li>
       <a class="text-gray-700 hover:text-gray-900" href="#">
        About
       </a>
      </li>
      <li>
       <a class="text-gray-700 hover:text-gray-900" href="#">
        Contact
       </a>
      </li>
     </ul>
    </nav>
   </div>
  </header>
  <main>
   <!-- Hero Section -->
   <section class="bg-cover bg-center h-96 relative">
    <img alt="A delicious spread of various dishes on a table" class="w-full h-full object-cover" height="600" src="https://storage.googleapis.com/a1aa/image/KTFw5VIfRlHmWXFoD24yFxbz9gxkerMpow_0t3yboHA.jpg" width="1920"/>
    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center">
     <div class="text-center text-white">
      <h2 class="text-4xl font-bold mb-4">
       Delicious Food Delivered To You
      </h2>
      <p class="text-lg mb-6">
       Experience the best food from the comfort of your home
      </p>
      <a class="bg-green-500 text-white px-4 py-2 rounded" href="#">
       Order Now
      </a>
     </div>
    </div>
   </section>
   <!-- Menu Section -->
   <section class="container mx-auto p-6">
    <h2 class="text-3xl font-bold text-center mb-6">
     Our Menu
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
     <!-- Menu Item 1 -->
     <div class="bg-white p-4 rounded-lg shadow-lg">
      <img alt="A plate of spaghetti with tomato sauce and basil" class="w-full h-48 object-cover rounded-t-lg" height="200" src="https://storage.googleapis.com/a1aa/image/GLgLFpQb7cN6xWHY2IP2BK7ihaOq3lA7lrLrgxYqSzM.jpg" width="300"/>
      <div class="p-4">
       <h3 class="text-xl font-bold mb-2">
        Spaghetti
       </h3>
       <p class="text-gray-700 mb-4">
        Delicious spaghetti with tomato sauce and fresh basil.
       </p>
       <p class="text-green-500 font-bold">
        Rp 30,000
       </p>
      </div>
     </div>
     <!-- Menu Item 2 -->
     <div class="bg-white p-4 rounded-lg shadow-lg">
      <img alt="A bowl of fresh salad with various vegetables" class="w-full h-48 object-cover rounded-t-lg" height="200" src="https://storage.googleapis.com/a1aa/image/TeVI6rPHAWv3ZmQwsK7f7ipGCSU9CZF3w_sV3QojoTg.jpg" width="300"/>
      <div class="p-4">
       <h3 class="text-xl font-bold mb-2">
        Fresh Salad
       </h3>
       <p class="text-gray-700 mb-4">
        A bowl of fresh salad with various vegetables.
       </p>
       <p class="text-green-500 font-bold">
        Rp 20,000
       </p>
      </div>
     </div>
     <!-- Menu Item 3 -->
     <div class="bg-white p-4 rounded-lg shadow-lg">
      <img alt="A juicy burger with cheese, lettuce, and tomato" class="w-full h-48 object-cover rounded-t-lg" height="200" src="https://storage.googleapis.com/a1aa/image/julGZzeajt9xB-Eei6MrywsZqYfjwxqEw4YmtrrC5P8.jpg" width="300"/>
      <div class="p-4">
       <h3 class="text-xl font-bold mb-2">
        Cheeseburger
       </h3>
       <p class="text-gray-700 mb-4">
        A juicy burger with cheese, lettuce, and tomato.
       </p>
       <p class="text-green-500 font-bold">
        Rp 40,000
       </p>
      </div>
     </div>
     <!-- Menu Item 4 -->
     <div class="bg-white p-4 rounded-lg shadow-lg">
      <img alt="A bowl of ramen with noodles, egg, and vegetables" class="w-full h-48 object-cover rounded-t-lg" height="200" src="https://storage.googleapis.com/a1aa/image/PItZYYnZIMXLKlQStKI1IzmjS0TpEox5dTmouNbEZt0.jpg" width="300"/>
      <div class="p-4">
       <h3 class="text-xl font-bold mb-2">
        Ramen
       </h3>
       <p class="text-gray-700 mb-4">
        A bowl of ramen with noodles, egg, and vegetables.
       </p>
       <p class="text-green-500 font-bold">
        Rp 60,000
       </p>
      </div>
     </div>
     <!-- Menu Item 5 -->
     <div class="bg-white p-4 rounded-lg shadow-lg">
      <img alt="A slice of chocolate cake with a cherry on top" class="w-full h-48 object-cover rounded-t-lg" height="200" src="https://storage.googleapis.com/a1aa/image/HwRMGMB00Z8OKfjMl-DoQSDRyqnC5D56zK4T82uTjrA.jpg" width="300"/>
      <div class="p-4">
       <h3 class="text-xl font-bold mb-2">
        Chocolate Cake
       </h3>
       <p class="text-gray-700 mb-4">
        A slice of chocolate cake with a cherry on top.
       </p>
       <p class="text-green-500 font-bold">
        Rp 25,000
       </p>
      </div>
     </div>
     <!-- Menu Item 6 -->
     <div class="bg-white p-4 rounded-lg shadow-lg">
      <img alt="A glass of fresh orange juice with ice cubes" class="w-full h-48 object-cover rounded-t-lg" height="200" src="https://storage.googleapis.com/a1aa/image/ohOt6YKDO46ipm4_uy_mAeJgqDIBn3eM4aVoJC25kOQ.jpg" width="300"/>
      <div class="p-4">
       <h3 class="text-xl font-bold mb-2">
        Orange Juice
       </h3>
       <p class="text-gray-700 mb-4">
        A glass of fresh orange juice with ice cubes.
       </p>
       <p class="text-green-500 font-bold">
        Rp 15,000
       </p>
      </div>
     </div>
    </div>
   </section>
   <!-- About Section -->
   <section class="bg-gray-200 py-12">
    <div class="container mx-auto p-6">
     <h2 class="text-3xl font-bold text-center mb-6">
      About Us
     </h2>
     <div class="flex flex-col md:flex-row items-center">
      <img alt="A team of chefs in a kitchen" class="w-full md:w-1/2 h-64 object-cover rounded-lg mb-6 md:mb-0 md:mr-6" height="300" src="https://storage.googleapis.com/a1aa/image/-qx34KGYnHELk40lvPaqbTY06w84NV61s7ms-gcxp08.jpg" width="400"/>
      <div class="md:w-1/2">
       <p class="text-gray-700 mb-4">
        We are a team of passionate chefs and food enthusiasts dedicated to bringing you the best culinary experiences. Our mission is to provide delicious, high-quality food that you can enjoy from the comfort of your home.
       </p>
       <p class="text-gray-700">
        Whether you're craving a hearty meal or a light snack, we have something for everyone. Thank you for choosing us to satisfy your taste buds!
       </p>
      </div>
     </div>
    </div>
   </section>
   <!-- Contact Section -->
   <section class="container mx-auto p-6">
    <h2 class="text-3xl font-bold text-center mb-6">
     Contact Us
    </h2>
    <div class="flex flex-col md:flex-row items-center">
     <div class="md:w-1/2 mb-6 md:mb-0 md:mr-6">
      <h3 class="text-xl font-bold mb-4">
       Get in Touch
      </h3>
      <p class="text-gray-700 mb-4">
       Have any questions or feedback? We'd love to hear from you! Reach out to us using the form below or through our social media channels.
      </p>
      <ul class="text-gray-700">
       <li class="mb-2">
        <i class="fas fa-phone-alt mr-2">
        </i>
        +62 851-3589-5807
       </li>
       <li class="mb-2">
        <i class="fas fa-envelope mr-2">
        </i>
        info@food coffee.com
       </li>
       <li>
        <i class="fas fa-map-marker-alt mr-2">
        </i>
        Jl. mutiara 12 no f 3 desa Alue awe No. f3, desa Alue awe kec muara dua Lhokseumawe, Indonesia
       </li>
      </ul>
     </div>
     <div class="md:w-1/2">
      <form>
       <div class="mb-4">
        <label class="block text-gray-700" for="name">
         Name: owner putra official
        </label>
        <input class="w-full p-2 border border-gray-300 rounded mt-1" id="name" placeholder="Your name" type="text"/>
       </div>
       <div class="mb-4">
        <label class="block text-gray-700" for="email">
         Email: muhammadzakwansaputra@gmail.com
        </label>
        <input class="w-full p-2 border border-gray-300 rounded mt-1" id="email" placeholder="Your email" type="email"/>
       </div>
       <div class="mb-4">
        <label class="block text-gray-700" for="message">
         Message
        </label>
        <textarea class="w-full p-2 border border-gray-300 rounded mt-1" id="message" placeholder="Your message" rows="4"></textarea>
       </div>
       <button class="w-full bg-green-500 text-white p-2 rounded" type="submit">
        Send Message
       </button>
      </form>
     </div>
    </div>
   </section>
  </main>
  <footer class="bg-gray-800 text-white py-6">
   <div class="container mx-auto text-center">
    <p>
     © 2025 Food coffee. All rights reserved.
    </p>
   </div>
  </footer>
 </body>
</html>
