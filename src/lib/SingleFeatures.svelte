
<script>
    export let animationSrc="./gif/2D.gif";;
    export let explainerSrc="./gif/ANZExplainer.gif";
    export let socialMediaadsSrc="./gif/ProductVideo.gif";
    export let interactiveCourseSrc="./gif/Interactivecourse.gif";
    
</script>
<section class="text-[#232323] body-font bg-[#232323] pb-20 ">
    <!--Heading text-->
    <div class="text-gray-600 body-font">
        <div class="container px-20 pt-24 mx-auto">
          <div class="text-center mb-20">
            <h1 class="sm:text-3xl text-2xl font-medium title-font text-slate-50 mb-4">We Expertise In</h1>
            <div class="flex mt-6 justify-center">
              <div class="w-60 h-1 rounded-full bg-[#00FFA6] inline-flex"></div>
            </div>
          </div>
        </div>
    </div>
    <!--End of Heading text-->
    <!--2D Animation Section-->
    <div class="container mx-auto flex px-40 py-5 md:flex-row flex-col items-center">
      <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
        <img src={animationSrc} class="object-cover object-center rounded" alt="hero"/>
      </div>
      <div class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center">
        <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-[#00FFA6] body-font"> 2D Animation</h1>
        <p class="mb-8 leading-relaxed text-slate-50 body-font">Ved-Media provides all the Digital Solutions to your company.</p>
        <div class="flex justify-center">
            <a sveltekit:prefetch href='/Ourwork'><button class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg">Watch More</button> </a>
          </div>
      </div>
    </div>
    <!--Explainer Video Section-->
    <div class="container mx-auto flex px-40 py-5 md:flex-row flex-col items-center">
      <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
        <img src={explainerSrc} class="object-cover object-center rounded" alt="hero"/>
      </div>
      <div class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center">
        <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-[#00FFA6] body-font"> Explainer Videos</h1>
        <p class="mb-8 leading-relaxed text-slate-50 body-font">Ved-Media provides all the Digital Solutions to your company.</p>
        <div class="flex justify-center">
            <a sveltekit:prefetch href='/Ourwork'><button class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg">Watch More</button> </a>
          </div>
      </div>
    </div>
    <!--End of Explainer Video Section-->
    <!--Social Media Ads Section-->
    <div class="container mx-auto flex px-40 py-5 md:flex-row flex-col items-center">
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
          <img src={socialMediaadsSrc} class="object-cover object-center rounded" alt="hero"/>
        </div>
        <div class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center">
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-[#00FFA6] body-font">Social Media Ads</h1>
          <p class="mb-8 leading-relaxed text-slate-50 body-font">Ved-Media provides all the Digital Solutions to your company.</p>
          <div class="flex justify-center">
              <a sveltekit:prefetch href='/Ourwork'><button class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg">Watch More</button> </a>
            </div>
        </div>
    </div>
    <!--End of Social Media Ads Section-->
    <!--Interactive e-Learning Section-->
    <div class="container mx-auto flex px-40 py-5 md:flex-row flex-col items-center">
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
          <img src={interactiveCourseSrc} class="object-cover object-center rounded" alt="hero"/>
        </div>
        <div class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center">
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-[#00FFA6] body-font">Interactive e-Learning Course</h1>
          <p class="mb-8 leading-relaxed text-slate-50 body-font">Ved-Media provides all the Digital Solutions to your company.</p>
          <div class="flex justify-center">
              <a sveltekit:prefetch href='/Ourwork'><button class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg">Watch More</button> </a>
            </div>
        </div>
    </div>
    <!--End of Interactive e-Learning Section-->
  </section>