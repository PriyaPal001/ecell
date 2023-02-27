<script>
  import head from "$lib/head.jpeg";
  import sir from "$lib/principal.jpg";
  import rais from "$lib/rais.jpg";
</script>
<svelte:head>
    <title>E-CELL</title>
</svelte:head>
<!-- <div class="bg-white pb-6 sm:pb-8 lg:pb-12">
    <section class="max-w-screen-2xl px-4 md:px-8 mx-auto">
      <div class="flex flex-wrap justify-between mb-8 md:mb-16">
        <div class="w-full lg:w-1/3 flex flex-col justify-center lg:pt-48 lg:pb-24 mb-6 sm:mb-12 lg:mb-0">
          <h1 class="text-black-800 text-4xl sm:text-5xl md:text-6xl font-bold mb-4 md:mb-8">Enterprenurship-CELL<br />VPPCOE</h1>
  
          <p class="max-w-md text-gray-500 xl:text-lg leading-relaxed">Entrepreneurship Cell, VPPCOE, popularly known as E-Cell, is a non-profit hub run by the enthusiastic students of VPPCOE. Instated in the year 2006, we envision the creation of leaders and visionaries who can disrupt the market space with their ideas.</p>
        </div>
  
        <div class="w-full lg:w-2/3 flex mb-12 md:mb-16">
          <div class="bg-gray-100 rounded-lg shadow-lg overflow-hidden relative z-10 top-12 md:top-16 left-12 md:left-16 -ml-12 lg:ml-0">
            <img src="https://franchiseindia.s3.ap-south-1.amazonaws.com/uploads/content/edu/art/5efdcaaf8eed3.jpeg" loading="lazy" alt="Photo by Kaung Htet" class="w-[400px] h-[420px] hidden  object-cover object-center" />
          </div>
  
          <div class="bg-gray-100 rounded-lg shadow-lg overflow-hidden">
            <img src="https://franchiseindia.s3.ap-south-1.amazonaws.com/uploads/content/edu/art/5efdcaaf8eed3.jpeg" loading="lazy" alt="Photo by Manny Moreno" class="w-full h-full object-cover object-center mask-circle mask" />
          </div>
        </div>
      </div>
  
      
    </section>
  </div> -->


  <section class="flex flex-col lg:flex-row justify-between gap-6 sm:gap-10 md:gap-16 md:px-32 md:mt-10 px-2">
    <!-- content - start -->
    <div class="xl:w-5/12 flex flex-col justify-center sm:text-center lg:text-left lg:py-12 xl:py-24">
      <!-- <p class="text-indigo-500 md:text-lg xl:text-xl font-semibold mb-4 md:mb-6">Very proud to introduce</p> -->

      <h1 class="text-black-800 text-4xl sm:text-5xl md:text-6xl font-bold mb-8 md:mb-12">Enterprenurship-CELL<br />VPPCOE</h1>

      <p class="lg:w-4/5 text-gray-500 xl:text-lg leading-relaxed mb-8 md:mb-12">Entrepreneurship Cell, VPPCOE, popularly known as E-Cell, is a non-profit hub run by the enthusiastic students of VPPCOE. Instated in the year 2006, we envision the creation of leaders and visionaries who can disrupt the market space with their ideas.</p>
    </div>
    <!-- content - end -->

    <!-- image - start -->
    <div class="xl:w-5/12 h-48 md:h-[500px] lg:h-[500px] bg-gray-100 overflow-hidden shadow-lg rounded-lg">
      <img src={head} loading="lazy" alt="Photo by Fakurian Design" class="w-full h-full object-cover object-center md:h-[500px]" />
    </div>
    <!-- image - end -->
  </section>

  <!-- <div>
    <div>
      <img src="" alt="principal">
    </div>
    <div>
      <img src="" alt="rais">
    </div>
    <div>
      <img src="" alt="mam">
    </div>
  </div> -->

  <section class="text-gray-600 body-font mt-10">
    <div class="w-full py-0 mx-auto md:px-20 px-2">
      <div class="flex items-center mx-auto border-b pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
        <div class="sm:w-36 sm:h-32 h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-lg text-indigo-500 flex-shrink-0">
          <img src={sir} class="sm:w-40 mask-circle mask rounded-xl sm:h-32 w-10 h-10" alt="">
          <!-- <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="sm:w-16 sm:h-16 w-10 h-10" viewBox="0 0 24 24">
            <path d="M22 12h-4l-3 9L9 3l-3 9H2"></path>
          </svg> -->
        </div>
        <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0 ">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-2">Dr. Alam.N.Shaikh</h2>
          <p class="leading-relaxed text-base">"Don't follow the crowd let the crowd follow you" Lorem ipsum dolor sit, amet consectetur adipisicing elit. Velit sunt, adipisci porro dolor mollitia ducimus ipsa repudiandae molestiae consequuntur, magni dolorem amet fuga ipsam quae voluptatibus repellat. Aliquam, consequatur! Unde.</p>
          <!-- <a class="mt-3 text-indigo-500 inline-flex items-center">Learn More
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a> -->
        </div>
      </div>
      <div class="flex items-center  mx-auto border-b pb-10 mb-10 border-gray-200 sm:flex-row flex-col">
        <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0 md:ml-56">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-2 ">Dr.Rais Mulla</h2>
          <p class="leading-relaxed text-base">“Every problem is a gift—without problems we would not grow.” Lorem ipsum dolor sit amet, consectetur adipisicing elit. Incidunt, voluptate, debitis quasi ex inventore harum repudiandae fuga quisquam beatae fugit quo. Neque delectus excepturi nulla aut consequuntur at commodi iure!</p>
          <!-- <a class="mt-3 text-indigo-500 inline-flex items-center">Learn More
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a> -->
        </div>
        <div class="sm:w-32 sm:order-none order-first sm:h-32 h-20 w-20 sm:ml-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0">
          <img src={rais} class="mask-circle mask " alt="">
          <!-- <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="sm:w-16 sm:h-16 w-10 h-10" viewBox="0 0 24 24">
            <circle cx="6" cy="6" r="3"></circle>
            <circle cx="6" cy="18" r="3"></circle>
            <path d="M20 4L8.12 15.88M14.47 14.48L20 20M8.12 8.12L12 12"></path>
          </svg> -->
        </div>
      </div>
      <div class="flex items-center  mx-auto sm:flex-row flex-col">
        <div class="sm:w-32 sm:h-32 h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0">
          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="sm:w-16 sm:h-16 w-10 h-10" viewBox="0 0 24 24">
            <path d="M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2"></path>
            <circle cx="12" cy="7" r="4"></circle>
          </svg>
        </div>
        <div class="flex-grow sm:text-left text-center mt-6 sm:mt-0">
          <h2 class="text-gray-900 text-lg title-font font-medium mb-2">Prof.Randeep kaur kahlon</h2>
          <p class="leading-relaxed text-base">There are no secrets to success. It is the result of preparation, hard work and learning from failure. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Enim porro id, reprehenderit iste laboriosam ea omnis, magnam quas vel ab molestiae consequatur consectetur esse voluptatibus! Cumque fugit itaque aut tenetur?</p>
          <!-- <a class="mt-3 text-indigo-500 inline-flex items-center">Learn More
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </a> -->
        </div>
      </div>
      
    </div>
  </section>

  <div class="bg-white py-6 sm:py-8 lg:py-12 mt-32">
    <div class="max-w-screen-xl px-4 md:px-8 mx-auto">
      <!-- text - start -->
      <div class="mb-8 md:mb-12">
        <h2 class="text-gray-800 text-2xl lg:text-3xl font-bold text-center mb-4 md:mb-6">Our Team by the numbers</h2>
  
        <p class="max-w-screen-md text-gray-500 md:text-lg text-center mx-auto">This is a section of some simple filler text, also known as placeholder text. It shares some characteristics of a real written text but is random or otherwise generated.</p>
      </div>
      <!-- text - end -->
  
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4 lg:gap-8">
        <!-- stat - start -->
        <div class="flex flex-col justify-center items-center bg-gray-100 rounded-lg p-4 lg:p-8">
          <div class="text-indigo-500 text-xl sm:text-2xl md:text-3xl font-bold">200</div>
          <div class="text-sm sm:text-base font-semibold">People</div>
        </div>
        <!-- stat - end -->
  
        <!-- stat - start -->
        <div class="flex flex-col justify-center items-center bg-gray-100 rounded-lg p-4 md:p-8">
          <div class="text-indigo-500 text-xl sm:text-2xl md:text-3xl font-bold">500+</div>
          <div class="text-sm sm:text-base font-semibold">People</div>
        </div>
  
        <!-- stat - start -->
        <div class="flex flex-col justify-center items-center bg-gray-100 rounded-lg p-4 md:p-8">
          <div class="text-indigo-500 text-xl sm:text-2xl md:text-3xl font-bold">1000+</div>
          <div class="text-sm sm:text-base font-semibold">Customers</div>
        </div>
        <!-- stat - end -->
  
        <!-- stat - start -->
        <div class="flex flex-col justify-center items-center bg-gray-100 rounded-lg p-4 md:p-8">
          <div class="text-indigo-500 text-xl sm:text-2xl md:text-3xl font-bold">1000</div>
          <div class="text-sm sm:text-base font-semibold">Coffee breaks</div>
        </div>
        <!-- stat - end -->
      </div>
    </div>
  </div>

  