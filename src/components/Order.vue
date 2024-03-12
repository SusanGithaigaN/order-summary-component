<template>
  <div class="rounded-lg w-96 overflow-hidden shadow-2xl bg-white justify-items-center">
    <div>
      <a href="#">
        <img
          class="object-cover"
          src="../../images//illustration-hero.svg"
          alt="card 1"
        />
      </a>
    </div>

    <div class="px-6 py-4 text-center">
      <h1 class="font-bold py-2">Order Summary</h1>
      <p class="des-blue font-semibold">
        You can now listen to millions of songs, audiobooks, and podcasts on any device
        anywhere you like!
      </p>


      <div class="pale-blue flex flex-col sm:flex-row py-6 px-2 my-2 rounded-xl">
        <div class="left w-full">
          <div class="flex items-center">
            <img
              class="rounded-full inline-block mr-2"
              src="../../images/icon-music.svg"
              alt="Avatar"
            />

            <p class="flex-flex-row">
              <span class="annual font-bold text-sm">Annual Plan</span>
              <br />
              <span class="des-blue font-semibold text-sm">$59.99/year</span>
            </p>
          </div>
        </div>

        <div class="right w-full flex justify-end">
          <div class="flex items-center">
            <h5 class="text-sm">
              <span class="soft-blue font-semibold underline px-4">Change</span>
            </h5>
          </div>
        </div>
      </div>
    </div>
    <div class="payments text-center py-2">
      <button class="checkout text-white font-bold py-2 px-14 rounded-xl shadow-xl">
        Proceed to Payment
      </button>
      <p class="des-blue font-bold py-3">Cancel Order</p>
    </div>
  </div>

  <div class="attribution py-2">
    Challenge by
    <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
      >Frontend Mentor</a
    >. Coded by <a href="http://github.com/SusanGithaigaN">Susan Githaiga</a>.
  </div>
</template>

<script>
export default {
  name: "order-summary-component",
};
</script>
<style scoped>
.attribution {
  font-size: 11px;
  text-align: center;
}
.attribution a {
  color: hsl(228, 45%, 44%);
}
.checkout {
  background-color: hsl(245, 75%, 52%);
}
.des-blue {
  color: hsl(224, 23%, 55%);
}
.pale-blue{
    background-color: hsl(225, 100%, 98%);
}
p {
  font-size: 16px;
}
h1 {
  font-size: 20px;
}
h1,
span,
.annual {
  color: hsl(223, 47%, 23%);
}
.soft-blue {
  color: hsl(245, 75%, 52%);
}
</style>
