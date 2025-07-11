<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Musically Dashboard</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gradient-to-br from-purple-700 to-indigo-900 text-white min-h-screen flex">

  <!-- Sidebar -->
  <aside class="w-64 bg-[#121212] text-white p-6 space-y-6">
    <h1 class="text-2xl font-bold mb-4 flex items-center gap-2">🎵 Musically</h1>
    <nav class="space-y-3">
      <a href="#" class="flex items-center gap-2 text-pink-400 font-semibold">🏠 Home</a>
      <a href="#" class="flex items-center gap-2">🔍 Search</a>
      <a href="#" class="flex items-center gap-2">📚 Your Library</a>
      <a href="#" class="flex items-center gap-2">❤️ Liked Songs</a>
      <a href="#" class="flex items-center gap-2">🔥 Trending</a>
    </nav>
    <div class="mt-6">
      <h2 class="text-sm uppercase text-gray-400 mb-2">Your Playlists</h2>
      <ul class="space-y-1 text-sm">
        <li>🎧 My Favorites</li>
        <li>🌊 Chill Vibes</li>
        <li>💪 Workout Beats</li>
        <li>🚗 Road Trip Mix</li>
        <li>📚 Study Focus</li>
      </ul>
    </div>
  </aside>

  <!-- Main content -->
  <main class="flex-1 p-8">
    <div class="flex justify-between items-center">
      <h2 class="text-3xl font-semibold">Welcome back!</h2>
      <div class="bg-gray-800 px-4 py-2 rounded-full">🎧 Music Lover</div>
    </div>

    <div class="mt-6 grid grid-cols-2 md:grid-cols-4 gap-4">
      <div class="bg-gradient-to-tr from-pink-400 to-red-500 p-4 rounded-lg">❤️ Liked Songs</div>
      <div class="bg-gradient-to-tr from-cyan-400 to-blue-500 p-4 rounded-lg">🌊 Chill Vibes</div>
      <div class="bg-gradient-to-tr from-orange-400 to-yellow-500 p-4 rounded-lg">💪 Workout Beats</div>
      <div class="bg-gradient-to-tr from-purple-400 to-pink-500 p-4 rounded-lg">🚗 Road Trip Mix</div>
    </div>

    <h3 class="text-2xl mt-10 mb-4">Trending Now</h3>
    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-4">
      <div class="bg-gradient-to-br from-green-300 to-purple-400 p-4 rounded-lg text-center">
        ✨ <br /> Blinding Lights<br /><span class="text-sm text-gray-200">The Weeknd</span>
      </div>
      <div class="bg-gradient-to-br from-pink-300 to-orange-400 p-4 rounded-lg text-center">
        🍉 <br /> Watermelon Sugar<br /><span class="text-sm text-gray-200">Harry Styles</span>
      </div>
      <div class="bg-gradient-to-br from-blue-300 to-indigo-500 p-4 rounded-lg text-center">
        🚀 <br /> Levitating<br /><span class="text-sm text-gray-200">Dua Lipa</span>
      </div>
      <div class="bg-gradient-to-br from-violet-300 to-pink-500 p-4 rounded-lg text-center">
        💜 <br /> Good 4 U<br /><span class="text-sm text-gray-200">Olivia Rodrigo</span>
      </div>
      <div class="bg-gradient-to-br from-yellow-300 to-orange-500 p-4 rounded-lg text-center">
        🌟 <br /> Stay<br /><span class="text-sm text-gray-200">The Kid LAROI</span>
      </div>
    </div>
  </main>

  <!-- Music Player -->
  <footer class="fixed bottom-0 w-full bg-black text-white p-4 flex items-center justify-between">
    <div class="flex items-center gap-4">
      <span class="text-sm">🎵 Choose a song</span>
    </div>
    <div class="flex items-center gap-4">
      <button>⏮️</button>
      <button class="text-2xl">⏯️</button>
      <button>⏭️</button>
    </div>
    <div class="w-1/3 bg-gray-600 h-1 rounded-full overflow-hidden">
      <div class="bg-green-400 h-1 w-1/4"></div>
    </div>
  </footer>
</body>
</html>
