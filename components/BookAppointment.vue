<template>
  <section class="pb-12">
    <div class="bg-theme-300 pb-96"></div>
    <div class="max-w-6xl px-4 mx-auto -mt-80">
      <div class="overflow-hidden bg-white rounded-md shadow-lg">
        <div class="flex flex-wrap">
          <div class="p-4 prose bg-gray-200 sm:order-2 md:w-1/2">
            <img
              src="~assets/img/book-an-appointment.jpg"
              alt="Book An Appointment"
              class="w-full"
            />
            <br>
            <p>
            Make an appointment now to explore the elegant Single-storey Terrace House of Bridgelux Homes. With direct developer pricing, and an exclusive hardcopy E-Brochure, 
            we guarantee the best price possible for your future residence.
          </p>
          <br>
          <p>Alternatively,</p>
          <br>
          <p>
            Fill out the form provided and receive an instant digital copy of our latest updates, E-Brochure, and pricing information! Take the first step in your journey to discovering your perfect home.
          </p>
          <p>Respecting your privacy is our priority. We adhere strictly to a no spam policy.</p>
          </div>
          <div class="p-4 md:order-1 md:w-1/2">
            <section class="space-y-6">
              <form-book-appoinment />
            </section>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import FormBookAppoinment from './FormBookAppoinment.vue'
export default {
  components: { FormBookAppoinment },
}
</script>

<style scoped>
/* .prose p {
  margin-top: 1.25em;
  margin-bottom: 1.25em;
} */
</style>
