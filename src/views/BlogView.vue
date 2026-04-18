<template>
  <div class="container mx-auto p-3 md:p-8">
    <div class="flex flex-col-reverse md:flex-row relative">
      <div class="w-full md:w-2/3">
        <div class="flex flex-col gap-4 md:px-20 fade-zoom-up">
          <div class="bg-[#1e1e1f] border border-[#383838] rounded-xl p-6 md:p-10">
            <h1 class="text-2xl text-amber-200 font-bold mb-6">Send Me a Message</h1>
            
            <form action="https://formspree.io/f/mkokbwrg" method="POST" class="flex flex-col gap-4">
              <div>
                <label class="text-slate-400 text-sm mb-2 block">Your Name</label>
                <input type="text" name="name" required class="w-full bg-[#282828] border border-[#383838] rounded-lg p-3 text-white focus:outline-none focus:border-amber-200 transition">
              </div>
              
              <div>
                <label class="text-slate-400 text-sm mb-2 block">Email Address</label>
                <input type="email" name="_replyto" required class="w-full bg-[#282828] border border-[#383838] rounded-lg p-3 text-white focus:outline-none focus:border-amber-200 transition">
              </div>
              
              <div>
                <label class="text-slate-400 text-sm mb-2 block">Message</label>
                <textarea name="message" rows="5" required class="w-full bg-[#282828] border border-[#383838] rounded-lg p-3 text-white focus:outline-none focus:border-amber-200 transition"></textarea>
              </div>
              
              <button type="submit" class="bg-amber-200 text-[#1e1e1f] font-bold py-3 rounded-lg hover:bg-amber-300 transition duration-300">
                Send Message
              </button>
            </form>
          </div>
        </div>
      </div>

      <div class="w-full md:w-1/3 h-fit p-8 md:sticky md:top-24">
        <div class="flex flex-col text-left">
          <div class="bg-clip-text bg-gradient-to-r from-slate-100 to-amber-300 text-transparent font-bold text-xl">
            Let's Connect!
          </div>
          <div class="h-[1px] mt-7 mb-7 w-20 bg-amber-200"></div>
          
          <div class="flex flex-col gap-6">
            <a href="mailto:muhamaddandierlangga@gmail.com" class="flex items-center gap-4 group">
              <div class="bg-[#1e1e1f] p-3 rounded-lg border border-[#383838] group-hover:border-amber-200 transition">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5 text-amber-200">
                  <path d="M1.5 8.67v8.58a3 3 0 003 3h15a3 3 0 003-3V8.67l-8.928 5.493a3 3 0 01-3.144 0L1.5 8.67z" />
                  <path d="M22.5 6.908V6.75a3 3 0 00-3-3h-15a3 3 0 00-3 3v.158l9.714 5.978a1.5 1.5 0 001.572 0L22.5 6.908z" />
                </svg>
              </div>
              <div>
                <p class="text-slate-400 text-xs">Email</p>
                <p class="text-white text-sm">muhamaddandierlangga@gmail.com</p>
              </div>
            </a>

            <a href="https://github.com/dandierlangga02" target="_blank" class="flex items-center gap-4 group">
              <div class="bg-[#1e1e1f] p-3 rounded-lg border border-[#383838] group-hover:border-amber-200 transition">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5 text-amber-200">
                  <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.008.069-.008 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd" />
                </svg>
              </div>
              <div>
                <p class="text-slate-400 text-xs">Github</p>
                <p class="text-white text-sm">github.com/dandierlangga02</p>
              </div>
            </a>

            <a href="https://www.linkedin.com/in/muhamad-dandi-erlangga-b1aa13383/" target="_blank" class="flex items-center gap-4 group">
              <div class="bg-[#1e1e1f] p-3 rounded-lg border border-[#383838] group-hover:border-amber-200 transition">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5 text-amber-200">
                  <path d="M20.5 2h-17A1.5 1.5 0 002 3.5v17A1.5 1.5 0 003.5 22h17a1.5 1.5 0 001.5-1.5v-17A1.5 1.5 0 0020.5 2zM8 19H5v-9h3zM6.5 8.25A1.75 1.75 0 118.25 6.5a1.75 1.75 0 01-1.75 1.75zM19 19h-3v-4.74c0-1.42-.6-1.93-1.38-1.93A1.74 1.74 0 0013 14.14V19h-3v-9h2.9v1.3a3.11 3.11 0 012.7-1.4c1.55 0 3.36.86 3.36 3.66z" />
                </svg>
              </div>
              <div>
                <p class="text-slate-400 text-xs">Linkedin</p>
                <p class="text-white text-sm">muhamad-dandi-erlangga</p>
              </div>
            </a>
          </div>

          <div class="hidden md:block mt-10">
            <div class="text-white text-md font-semibold">Location</div>
            <div class="mt-3 flex flex-wrap gap-1">
              <span class="py-2 px-3 rounded-2xl bg-[#1e1e1f] text-white text-xs">Jakarta</span>
              <span class="py-2 px-3 rounded-2xl bg-[#1e1e1f] text-white text-xs">Indonesia</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // Tidak perlu axios lagi karena kita menggunakan form handling
}
</script>

<style scoped>
@keyframes fadeZoomUp {
  0% {
    opacity: 0;
    transform: scale(0.5);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}
.fade-zoom-up {
  animation: fadeZoomUp 1s ease-in-out;
}
</style>