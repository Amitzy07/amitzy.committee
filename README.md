# amitzy.committee

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Amitzy Committee</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
  </style>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          animation: {
            fadeIn: "fadeIn 2s ease-in-out forwards"
          },
          keyframes: {
            fadeIn: {
              '0%': { opacity: 0 },
              '100%': { opacity: 1 }
            }
          }
        }
      }
    }
  </script>
</head>
<body class="bg-black text-white">

  <!-- HEADER -->
  <header class="flex justify-between items-center p-6 bg-black bg-opacity-80">
    <h1 class="text-2xl font-bold">Amitzy Committee</h1>
    <nav class="space-x-4">
      <a href="#story" class="hover:text-purple-400">Amitzy</a>
      <a href="#council" class="hover:text-purple-400">Council</a>
      <a href="#login" class="hover:text-purple-400">Join</a>
    </nav>
  </header>

  <!-- HERO SECTION -->
  <section class="h-screen bg-center bg-cover flex flex-col justify-center items-center text-center px-4 animate-fadeIn"
    style="background-image: url('Fuco.jpg');">
    <div class="bg-black bg-opacity-70 p-8 rounded-xl">
      <h2 class="text-4xl md:text-5xl font-bold mb-4 tracking-wide">Amitzy Committee</h2>
      <p class="text-lg md:text-xl mb-6 max-w-xl text-gray-300">
        "The Amitzy Committee is a secret council of minds chosen to shape the future, where the forgotten become immortal."
      </p>
      <a href="#login" class="bg-purple-700 hover:bg-purple-900 text-white px-6 py-3 rounded-xl text-lg">Join the Committee</a>
    </div>
  </section>

  <!-- MY STORY SECTION -->
  <section id="story" class="py-20 px-8 bg-gradient-to-b from-black to-gray-900 text-center space-y-6">
    <h2 class="text-3xl font-bold">Amitzy'</h2>
    <p class="max-w-3xl mx-auto text-lg leading-relaxed text-gray-300">
      I am Amitzy — a young visionary from India.  
      I don't chase grades; I command galaxies.  
      This isn’t about space — it’s about control.  
      Control over ideas, over systems, over destiny.  
      Amitzy is not a platform. It’s a movement for those who were never meant to be ordinary —  
      a force built by minds that bend reality,  
      by artists of chaos, scientists of soul, and rebels who create their own universe.
    </p>
  </section>

  <!-- COUNCIL SECTION -->
  <section id="council" class="py-20 px-8 bg-black text-center border-t border-gray-700 space-y-6">
    <h2 class="text-3xl font-bold">The Council</h2>
    <p class="max-w-3xl mx-auto text-lg text-gray-400">
      The Amitzy Council is a secret circle of thinkers, builders, and dreamers.  
      People who want to build brain chips, conquer galaxies, redesign money, solve diseases, and reshape human evolution.  
      This is where legends begin.  
    </p>
  </section>

  <!-- LOGIN / JOIN SECTION -->
  <section id="login" class="py-20 px-8 bg-gray-900 text-center border-t border-gray-700">
    <h2 class="text-3xl font-bold mb-6">Apply to Join</h2>
    <form action="https://formspree.io/f/xblodgzg" method="POST" class="max-w-md mx-auto space-y-4">
      <input type="text" name="name" placeholder="Your Name" class="w-full p-3 rounded bg-black text-white border border-gray-700 focus:outline-none" required>
      <input type="email" name="email" placeholder="Your Email" class="w-full p-3 rounded bg-black text-white border border-gray-700 focus:outline-none" required>
      <textarea name="idea" placeholder="What is your idea?" class="w-full p-3 rounded bg-black text-white border border-gray-700 focus:outline-none h-32" required></textarea>
      <button type="submit" class="bg-purple-700 hover:bg-purple-900 px-6 py-3 rounded-xl text-white w-full">Submit</button>
      <input type="hidden" name="_redirect" value="Amitzy.html" />
    </form>
  </section>

  <!-- FOOTER -->
  <footer class="text-center p-6 bg-black text-gray-500">
    &copy; 2025 Amitzy Committee. Built for the unseen.
  </footer>

</body>
</html>
