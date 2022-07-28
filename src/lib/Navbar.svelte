<script>
   let src="./images/logo.png";
</script>

<div class='Navbar'>
  <header class="text-white bg-[#232323]">
      <div class="container px-40 mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
         <a href='/'>
         <img {src} class="w-20" alt="logo"/>
       </a>
       <nav class="md:ml-auto flex flex-wrap items-center text-base justify-center">
          <a href='/' class="mr-5 hover:text-[#00FFA6]">Home</a>
          <a sveltekit:prefetch href='/Ourwork' class="mr-5 hover:text-[#00FFA6]">Our Work</a>
         <a href='/' class="mr-5 hover:text-[#00FFA6]">Contact Us</a>
        </nav>
      </div>
   </header>
</div>

