<template>
    <section id="header">
      <div class="w-screen h-full flex pb-20">
        <div class="w-6/12">
          <p class="font-semibold text-6xl tracking-tight ml-24 pt-24 mr-20 text-white">The History of Scooby Doo</p>
          <p class="text-2xl tracking-tight ml-24 mr-20 text-white">This is a space to learn all you always wished to know about the history of Scooby Doo</p>
          <p class="mt-6">
            <a href="#" class="text-sm px-4 ml-24 py-3 leading-none border rounded text-white border-white hover:border-transparent hover:text-purple-500 hover:bg-white font-black">DO</a>
            <a href="#" class="text-sm px-4 ml-5 py-3 leading-none border rounded text-white border-white hover:border-transparent hover:text-purple-500 hover:bg-white font-black">NOTHING</a>
          </p>
        </div>
        <div class="">
          <span class="z-10 float-right w-10/12 relative mt-24"><img alt="Mystery Machine" src="@/assets/img/mystery-machine.png"></span>
          <span class="z-0 float-right w-6/12 mt-12 -ml-5 absolute"><img alt="Blob" src="@/assets/img/tealblob.png"></span>
        </div>
      </div>
    </section>
</template>

<script>
    export default {
        name: 'Header'
    }
</script>