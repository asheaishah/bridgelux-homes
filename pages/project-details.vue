<template>
  <div>
    <div>
      <div class="py-8 select-none bg-gradient-to-b from-violet-500 to-green-200 pb-20 h-10">
          <div class="text-xl font-semibold text-center text-white sm:text-4xl">
          Project Details
        </div>
      </div>
<!--
      <div class="max-w-6xl px-4 mx-auto prose text-justify">
        <h1> About Developer </h1>
          <p>
            Teknik Perancang Realty Sdn Bhd Teknik Perancang Realty Sdn Bhd was incorporated on 1980 in Malaysia. Teknik Perancang Realty Sdn Bhd business includes property development
          </p>
      </div>
-->
      <section class="py-12">
        <div class="max-w-6xl px-4 mx-auto">
          <div class="p-6 bg-white rounded-lg shadow-lg">
            <div class="grid grid-cols-1 gap-6 sm:grid-cols-2">
              <div>
                <label class="block text-gray-500 font-bold">Project Name</label>
                <p>Bridgelux Homes</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">Developer</label>
                <p>Teknik Perancang Realty Sdn. Bhd</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">Location</label>
                <p>Lot 9680, Kota Samarahan</p>
              </div>
              
              <div>
                <label class="block text-gray-500 font-bold">District</label>
                <p>Kota Samarahan</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">Maximum Gross Floor Area</label>
                <p>1990 ft / unit</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">Tenure</label>
                <p>Perpetuity 3.37 h.a</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">Land Size</label>
                <p>6.12 points ~ 16.25 points</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">No of car park lots</label>
                <p>2 per unit</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">Project by</label>
                <p>Idaman Prima Sdn Bhd ( 496661-M )</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">Total No. of Units</label>
                <p>62 units</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">Land use</label>
                <p>Residentials</p>
              </div>
              <div>
                <label class="block text-gray-500 font-bold">Expected Date of Legal Completion</label>
                <p>24 months from S &amp; P date</p>
              </div>
            </div>
          </div>
          <div class="py-4 italic text-center text-gray-500">
            (Project details for Bridgelux Homes may be subjected to change without prior notice)
          </div>
          <section class="py-6">
            <NuxtLink
              to="/location-map"
              class="
                inline-flex
                items-center
                justify-center
                w-full
                px-3
                py-3
                text-white
                transition
                rounded
                sm:px-0
                hover:bg-blue-600
                bg-blue-300
              "
            >
              Continue To Location Map
              <svg
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
                class="w-5 h-5"
              >
                <path
                  d="M13 6l6 6-6 6M5 6l6 6-6 6"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                ></path></svg
            ></NuxtLink>
          </section>
        </div>
      </section>
      
      <BookAppointment />
    
    </div>
  </div>
</template>
<script>
export default {}
</script>
