
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surabhi Rana - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
      .gradient-background {
        background: linear-gradient(to right, #667eea, #764ba2); /* Example gradient */
      }
    </style>
</head>
<body class="bg-gray-100 font-sans">

    <nav class="bg-white p-4 shadow-md">
        <div class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-gray-800">Surabhi Rana</a>
            <div>
                <a href="#about" class="mr-4 text-gray-600 hover:text-gray-800">About</a>
                <a href="#projects" class="mr-4 text-gray-600 hover:text-gray-800">Projects</a>
                <a href="#contact" class="text-gray-600 hover:text-gray-800">Contact</a>
            </div>
        </div>
    </nav>

    <section class="gradient-background py-20 text-white text-center">  <div class="container mx-auto">
            <h1 class="text-5xl font-bold mb-4">Hi, I'm Surabhi Rana</h1>
            <p class="text-xl mb-8">A passionate web developer</p>
            <a href="#projects" class="bg-white text-indigo-700 py-3 px-6 rounded-lg font-bold hover:bg-indigo-100">View My Work</a>
        </div>
    </section>

    <section id="about" class="py-12 bg-gray-100">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-6 text-center">About Me</h2>
            <div class="md:flex md:items-center">  
              <div class="md:w-1/2 md:pl-8">
                <p class="text-gray-800 leading-relaxed">
                   As a passionate computer engineering student, I am deeply interested in leveraging technology to solve real-life problems. I believe that the power of innovation in tech opens up new possibilities to tackle the challenges we face today.

My goal is to combine cutting-edge technology with practical solutions that can make a meaningful impact, driving progress in both the digital and physical worlds.
                </p>
              </div>
            </div>
        </div>
    </section>

    <section id="projects" class="py-12 bg-white">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-6 text-center">My Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">  <div class="bg-gray-100 rounded-lg shadow-md p-6">
                      <h3 class="text-xl font-bold mb-2">Science Fiction Book Club Website</h3>
                    <p class="text-gray-800">It is a platform that connects science fiction readers at same platform.</p>
                    <a href="#" class="text-indigo-600 hover:text-indigo-800 mt-2 inline-block">View Project</a>
                </div>

                <div class="bg-gray-100 rounded-lg shadow-md p-6">
                      <h3 class="text-xl font-bold mb-2">VentureLink</h3>
                    <p class="text-gray-800">It is a platform that bridges the gap between entrepreneurs and investors.</p>
                    <a href="#" class="text-indigo-600 hover:text-indigo-800 mt-2 inline-block">View Project</a>
                </div>

                </div>
        </div>
    </section>

    <section id="contact" class="py-12 bg-gray-100">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-6 text-center">Contact Me</h2>
            <div class="max-w-md mx-auto">
                <form>
                    <div class="mb-4">
                        <label for="name" class="block text-gray-700 font-bold mb-2">Name</label>
                        <input type="text" id="name" name="name" class="w-full border border-gray-300 rounded-md py-2 px-3 focus:outline-none focus:ring-2 focus:ring-indigo-200" required>
                    </div>
                    <div class="mb-4">
                        <label for="email" class="block text-gray-700 font-bold mb-2">Email</label>
                        <input type="email" id="email" name="email" class="w-full border border-gray-300 rounded-md py-2 px-3 focus:outline-none focus:ring-2 focus:ring-indigo-200" required>
                    </div>
                    <div class="mb-6">
                        <label for="message" class="block text-gray-700 font-bold mb-2">Message</label>
                        <textarea id="message" name="message" rows="4" class="w-full border border-gray-300 rounded-md py-2 px-3 focus:outline-none focus:ring-2 focus:ring-indigo-200" required></textarea>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="bg-indigo-700 text-white py-3 px-6 rounded-lg font-bold hover:bg-indigo-800">Send Message</button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 py-4 text-center text-white">
        <p>&copy; 2025 Surabhi Rana</p>
    </footer>

</body>
</html>
