<script lang="ts">
  import CardTopTen from "../components/elements/CardTopTen.svelte";
  let count: number = 0;
</script>

<main
  class="bg-heroFit bg-cover w-full h-full flex items-center justify-center flex-col gap-3 text-4xl">
  <p class="text-white">SE TU MEJOR</p>
  <section class="container mx-auto mt-5 text-center">
    <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
        
        <div class="bg-sky-800 row-span-5">
          
          <CardTopTen/>
          
        </div>

        <div class="bg-sky-800">
          <spam class="text-2xl">The best Gym reviews</spam>
          <div class="flex justify-center m-3">
            <div class="block p-6 rounded-lg shadow-lg bg-slate-200 max-w-sm">
              <h5 class="text-gray-900 text-xl leading-tight font-medium mb-2">Gimnasio Fitup</h5>
              <p class="text-gray-700 text-base mb-4">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>

        <div class="bg-sky-800">
          <spam class="text-2xl">Latest Gym Comments</spam>
          <div class="flex justify-center m-3">
            <div class="block p-6 rounded-lg shadow-lg bg-slate-200 max-w-sm">
              <h5 class="text-gray-900 text-xl leading-tight font-medium mb-2">Gimnasio Fitup</h5>
              <p class="text-gray-700 text-base mb-4">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
          </div>
        </div>
    </div>
    
  </section>


</main>
