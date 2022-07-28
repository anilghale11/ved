<script>
    export let animationSrc="./images/2d.png";
    export let explainervideoSrc="./images/Explainer.png";
    export let eLearningSrc="./images/eLearning.png";
    export let whiteboardAnimationSrc="./images/ProductAds.png";
    export let socialMediaAdsSrc="./images/Whiteboard.png";
    export let websiteSrc="./images/Website.png";

</script>


<section class="text-gray-600 body-font bg-[#232323]">
    <div class="container px-5 py-24 mx-auto">
      <div class="text-center mb-20">
        <h1 class="sm:text-3xl text-2xl font-medium title-font text-[#00FFA6] mb-4">We Expertise in</h1>
        <div class="flex mt-6 justify-center">
          <div class="w-16 h-1 rounded-full bg-[#00FFA6] inline-flex"></div>
        </div>
      </div>
      <div class="flex flex-wrap sm:-m-4 -mx-4 -mb-10 -mt-4 md:space-y-0 space-y-6">
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
          <img class="w-60 h-60"src={animationSrc} alt="2D Animation">
          <div class="flex-grow">
            <h1 class="text-white text-lg title-font font-medium mb-3">2D Animation</h1>
          </div>
        </div>
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
            <img class="w-60 h-60"src={explainervideoSrc} alt="2D Animation">
            <div class="flex-grow">
              <h1 class="text-white text-lg title-font font-medium mb-3">Explainer Videos</h1>
            </div>
        </div>
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
            <img class="w-60 h-60"src={eLearningSrc} alt="2D Animation">
            <div class="flex-grow">
              <h1 class="text-white text-lg title-font font-medium mb-3">Interactive e-Learning Courses</h1>
            </div>
        </div>
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
          <img class="w-60 h-60"src={socialMediaAdsSrc} alt="2D Animation">
          <div class="flex-grow">
            <h1 class="text-white text-lg title-font font-medium mb-3">Social Media Ads</h1>
          </div>
        </div>
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
            <img class="w-60 h-60"src={whiteboardAnimationSrc} alt="2D Animation">
            <div class="flex-grow">
              <h1 class="text-white text-lg title-font font-medium mb-3">Whiteboard Animation</h1>
            </div>
        </div>
        <div class="p-4 md:w-1/3 flex flex-col text-center items-center">
          <img class="w-60 h-60"src={websiteSrc} alt="2D Animation">
          <div class="flex-grow">
            <h1 class="text-white text-lg title-font font-medium mb-3">Website Design</h1>
          </div>
      </div>
      </div>
      <a sveltekit:prefetch href="/Ourwork">
      <button class="flex mx-auto mt-16 text-white bg-[#00B5B3] border-0 py-2 px-8 focus:outline-none hover:bg-[#12c788] rounded text-lg">Button</button>
      </a>
    </div>
  </section>