
<template>

  <section class="page2-3 flex flex-col overflow-hidden bg-[rgb(227,231,233)]">
    <!-- This section handles the donation amount input and associated buttons. -->

    <div class="mx-auto mt-[18px] mb-[39px] flex w-full max-w-[430.3999938964844px] gap-x-4 tn:gap-x-2">
      <img class="mb-[839px] w-[38px] object-cover tn:mx-0 tn:mt-0 tn:mb-[50px]" src="/assets/e1089d533756577fe053d25380af2bd1.svg" alt="alt text" />
      <!-- Displays the related image for the donation section. -->

      <div class="relative mt-[41.5px] flex w-[344px] min-w-0 flex-col">
        <div class="relative flex flex-col">
          <h2 class="font-Piazzolla ml-[13.08%] flex w-[229px] max-w-[85%] items-center justify-center text-center text-[24px] font-semibold leading-[0.91] text-black tn:my-0 tn:mx-auto">
            <!-- Title indicating the donation amount. -->
             捐款金額
          </h2>
          <button class="font-Aboreto mt-[88.5px] mr-1.5 flex items-center justify-center rounded-lg bg-white pt-[57.5px] pr-2 pb-[57.5px] pl-2 text-center text-[16px] font-normal leading-[1.37] text-white">
            <!-- Button for standard fee donation. -->
             feefefe
          </button>
          <button class="font-Aboreto mt-[22px] mr-1.5 flex items-center justify-center rounded-lg bg-white pt-[57.5px] pr-2 pb-[57.5px] pl-2 text-center text-[16px] font-normal leading-[1.37] text-white">
            <!-- Button for custom fee donation. -->
             feefefe
          </button>
          <button class="font-Aboreto mt-[22px] mr-1.5 flex items-center justify-center rounded-lg bg-[rgb(180,226,234)] pt-[57.5px] pr-2 pb-[57.5px] pl-2 text-center text-[16px] font-normal leading-[1.37] text-[rgb(180,226,234)]">
            <!-- Button for additional fee donation. -->
             feefefe
          </button>
          <button class="mt-[22px] mr-1.5 flex items-center justify-center rounded-lg pt-[19px] pr-9 pb-[19px] pl-9">
            <!-- Button for custom amount input. -->

            <span class="font-Roboto text-center text-[32px] font-semibold leading-[0.68] text-black">
              <span class="font-semibold">$ ___ 自訂金額     </span>
              <span class="font-semibold text-white"> </span>
              <span class="text-[1.125em] font-semibold text-white">.</span>
            </span>
          </button>
          <button class="font-Abel mt-[136px] ml-auto flex w-[175px] max-w-full items-center justify-center rounded-lg bg-[rgb(90,180,197)] pt-[13px] pr-2 pb-[13px] pl-2 text-center text-[24px] font-normal leading-[0.91] text-white">
            <!-- Button to proceed with the donation process. -->
             繼續
          </button>
        </div>
        <div class="absolute left-[-17px] top-[165.5px] flex w-[189px] flex-col gap-y-[137px] tn:gap-y-[50px]">
          <h1 class="font-Roboto flex items-center justify-center text-center text-[32px] font-semibold leading-[0.68] text-black">
            <!-- Donation amount option of $200. -->
             $ 200
          </h1>
          <h1 class="font-Roboto flex items-center justify-center text-center text-[32px] font-semibold leading-[0.68] text-black">
            <!-- Donation amount option of $800. -->
             $ 800
          </h1>
          <h1 class="font-Roboto flex items-center justify-center text-center text-[32px] font-semibold leading-[0.68] text-black">
            <!-- Donation amount option of $1200. -->
             $ 1200
          </h1>
        </div>
      </div>
    </div>
  </section>

</template>

<style scoped lang="scss">
  @import 'Page2_3.scss';
</style>

