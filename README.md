# roblox-portfolio

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Roblox Studio Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white font-sans">
  <!-- Header -->
  <header class="bg-blue-600 py-6 text-center">
    <h1 class="text-4xl font-bold">My Roblox Studio Portfolio</h1>
    <p class="mt-2 text-lg">Showcasing my scripting and game development skills</p>
  </header>

  <!-- About Section -->
  <section class="max-w-4xl mx-auto py-10 px-4">
    <h2 class="text-3xl font-semibold mb-4">About Me</h2>
    <p class="text-lg">
      I'm a passionate Roblox Studio developer specializing in Lua scripting, visual effects, and game systems. I create engaging gameplay mechanics and immersive experiences for Roblox games. Check out my projects below!
    </p>
  </section>

  <!-- Projects Section -->
  <section class="max-w-4xl mx-auto py-10 px-4">
    <h2 class="text-3xl font-semibold mb-6">My Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <!-- Project 1: Admin Abuse Event -->
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <h3 class="text-2xl font-bold mb-2">Admin Abuse Event</h3>
        <p class="mb-4">A dynamic event system with Shock VFX that moves from start to end, triggers explosions, and includes screen shake for immersion. Built with Lua in Roblox Studio.</p>
        <p class="text-gray-400">[Add screenshot or video here]</p>
        <button class="mt-4 bg-blue-500 hover:bg-blue-600 text-white py-2 px-4 rounded" onclick="alert('Details: Lua scripts for VFX, RemoteEvents for screen shake, and particle emitters.')">View Details</button>
      </div>
      <!-- Project 2: Inventory System -->
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <h3 class="text-2xl font-bold mb-2">Inventory System</h3>
        <p class="mb-4">A simple inventory system for Roblox, allowing players to collect and manage items with a UI display. Built with Lua and Roblox GUI.</p>
        <p class="text-gray-400">[Add screenshot or video here]</p>
        <button class="mt-4 bg-blue-500 hover:bg-blue-600 text-white py-2 px-4 rounded" onclick="alert('Details: Server-client communication, GUI updates, and item management in Lua.')">View Details</button>
      </div>
      <!-- Project 3: Leaderboard System -->
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <h3 class="text-2xl font-bold mb-2">Leaderboard System</h3>
        <p class="mb-4">A leaderboard system tracking player scores, updating in real-time across the server. Built with Lua and DataStore for persistence.</p>
        <p class="text-gray-400">[Add screenshot or video here]</p>
        <button class="mt-4 bg-blue-500 hover:bg-blue-600 text-white py-2 px-4 rounded" onclick="alert('Details: Uses DataStore for saving scores and leaderstats for display.')">View Details</button>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="max-w-4xl mx-auto py-10 px-4 text-center">
    <h2 class="text-3xl font-semibold mb-4">Contact Me</h2>
    <p class="text-lg mb-4">Interested in hiring me for a Roblox Studio commission? Reach out!</p>
    <p class="text-lg">[Roblox User : Pyleon65  or Discord .pyleon]</p>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 py-4 text-center">
    <p>&copy; 2025 My Roblox Studio Portfolio. All rights reserved.</p>
  </footer>
</body>
</html>
