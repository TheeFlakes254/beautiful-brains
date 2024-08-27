<script>
  import "../app.css";
</script>

<style>
  .background-image {
    background-image: url('/bg 2.png'); /* Replace with your image path */
    background-size: cover;
    background-position: center;
    opacity: 0.5; /* Set the opacity of the background image */
  }


</style>

<div class="relative min-h-screen flex items-center justify-center text-center">
  <div class="absolute inset-0 background-image"></div>
  <div class="relative  z-10 text-center">
    <h1 class="text-2xl md:text-4xl font-bold mb-4 text-blue-700">
        Help Us Build a World Where <br><span class="text-red-500">Every Child</span> Can Thrive
    </h1><br/><br/>

    <div class="bg-lime-300 rounded-lg shadow-2xl p-6 inline-block border-2 border-black">
        <p class="text-lg text-blue-400 md:text-xl mb-4">Support the course, by making a donation</p>
        <form class="flex items-center space-x-2 space-y-7">
            <label for="donation" class="text-sm">I want to give</label>
            <input 
            type="number"
            id="donation"
            placeholder="$"
            class="px-4 py-2 rounded-full focus:outline-none"
            />

            <button
            type="submit"
            class="bg-red-500 text-white px-6 py-2 rounded-full hover:bg-red-600 focus:outline-none"
            >Donate</button>
        </form>
    </div>
  </div>
</div>
