<script>
  import "../app.css";
</script>

<div class="h-screen p-10 grilla">
  <div
    class="w-full h-full bg-gray-200 rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 border border-gray-500 hover:border-gray-100 transition container1"
  >
    <div
      class="bg-gray-800 text-white rounded-tl-md rounded-tr-md flex justify-between p-1"
    >
      <div class="flex items-center gap-1">
        <div
          class="rounded-full bg-blue-400 w-3 h-3 hover:bg-blue-100 transition"
        />
        <p>About Me!</p>
      </div>
      <div class="flex gap-1 items-center">
        <div
          class="rounded-full bg-yellow-400 w-3 h-3 hover:bg-yellow-100 transition"
        />
        <div
          class="rounded-full bg-green-400 w-3 h-3 hover:bg-green-100 transition"
        />
        <div
          class="rounded-full bg-red-400 w-3 h-3 hover:bg-red-100 transition"
        />
      </div>
    </div>
    <div />
  </div>
  <div
    class="w-full h-full bg-gray-200 rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 border border-gray-500 hover:border-gray-100 transition container2"
  >
    <div
      class="bg-gray-800 text-white rounded-tl-md rounded-tr-md flex justify-between p-1"
    >
      <div class="flex items-center gap-1">
        <div
          class="rounded-full bg-pink-400 w-3 h-3 hover:bg-pink-100 transition"
        />
        <p>Tech Stack</p>
      </div>
      <div class="flex gap-1 items-center">
        <div
          class="rounded-full bg-yellow-400 w-3 h-3 hover:bg-yellow-100 transition"
        />
        <div
          class="rounded-full bg-green-400 w-3 h-3 hover:bg-green-100 transition"
        />
        <div
          class="rounded-full bg-red-400 w-3 h-3 hover:bg-red-100 transition"
        />
      </div>
    </div>
    <div />
  </div>
  <div
    class="w-full h-full bg-gray-200 rounded-md bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 border border-gray-500 hover:border-gray-100 transition container3"
  >
    <div
      class="bg-gray-800 text-white rounded-tl-md rounded-tr-md flex justify-between p-1"
    >
      <div class="flex items-center gap-1">
        <div
          class="rounded-full bg-green-400 w-3 h-3 hover:bg-green-100 transition"
        />
        <p>Projects</p>
      </div>
      <div class="flex gap-1 items-center">
        <div
          class="rounded-full bg-yellow-400 w-3 h-3 hover:bg-yellow-100 transition"
        />
        <div
          class="rounded-full bg-green-400 w-3 h-3 hover:bg-green-100 transition"
        />
        <div
          class="rounded-full bg-red-400 w-3 h-3 hover:bg-red-100 transition"
        />
      </div>
    </div>
    <div />
  </div>
</div>

<style>
  .grilla {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-column-gap: 10px;
    grid-row-gap: 10px;
  }

  .container1 {
    grid-area: 1 / 1 / 2 / 2;
  }
  .container2 {
    grid-area: 2 / 1 / 3 / 2;
  }
  .container3 {
    grid-area: 1 / 2 / 3 / 3;
  }
</style>
