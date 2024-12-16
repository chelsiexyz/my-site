<script>
    import "../app.css";
    import Header from "$lib/Header.svelte";
  </script>
  
  <Header></Header>
  

  <main class="bg-gradient-to-b from-gray-900 via-gray-800 to-black backdrop-blur-sm backdrop-brightness-70 min-h-screen">
    <div class="relative z-10">
      <slot />
    </div>
  </main>