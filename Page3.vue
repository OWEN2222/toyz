
<template>

  <section class="page3 flex flex-col overflow-hidden bg-[rgb(227,231,233)]">
    <!-- Section for processing payment information. -->

    <div class="mt-[25px] mr-[11px] mb-[37px] flex max-w-[419.3999938964844px] flex-col gap-y-2.5 tn:mt-[25px] tn:mr-2 tn:mb-[37px] tn:ml-0">
      <img class="w-6 object-cover" src="/assets/e4f347b54a7686e96e72eecf3ac06efa.svg" alt="alt text" />
      <div class="flex flex-col items-center gap-y-[83px] tn:gap-y-[50px]">
        <div class="flex w-full flex-col">
          <div class="flex flex-col">
            <h2 class="font-Piazzolla mx-auto flex items-center justify-center text-center text-[24px] font-semibold leading-[0.91] text-black">付款</h2>
            <h2 class="font-Abel mt-[45.5px] flex w-[126px] max-w-[85%] items-center justify-center text-center text-[26px] font-normal leading-[0.84] text-black">捐贈金額</h2>
            <h2 class="font-Abel mt-[45px] ml-3 flex w-[219px] max-w-[85%] items-center text-[26px] font-normal leading-[0.84] text-black tn:mt-[45px] tn:mr-0 tn:mb-0 tn:ml-2">
              持卡人姓名
              <br />
              Holder of Credit Card
            </h2>
            <p class="mt-[9px] ml-3 min-h-[48px] w-[219px] max-w-[85%] bg-[rgb(217,217,217)] tn:mt-[9px] tn:mr-0 tn:mb-0 tn:ml-2"></p>
            <h2 class="font-Abel mt-[17px] ml-3 flex w-[227px] max-w-[85%] items-center text-[26px] font-normal leading-[0.84] text-black tn:mt-[17px] tn:mr-0 tn:mb-0 tn:ml-2">
              信用卡號
              <br />
              Credit Card Number
            </h2>
            <div class="mt-[9px] ml-3 flex flex-col items-center gap-y-1.5 tn:mt-[9px] tn:mr-0 tn:mb-0 tn:ml-2">
              <!-- Section for CVV information. -->

              <div class="relative flex w-full flex-col">
                <div class="relative flex flex-col">
                  <div class="flex items-center">
                    <color class="block h-12 min-h-[48px] w-[78px] bg-[rgb(217,217,217)]"></color>
                    <h1 class="font-Abel flex items-center justify-center text-center text-[45px] font-normal leading-[0.48] text-black">-</h1>
                    <color class="block h-12 min-h-[48px] w-[78px] bg-[rgb(217,217,217)]"></color>
                    <h1 class="font-Abel flex items-center justify-center text-center text-[45px] font-normal leading-[0.48] text-black">-</h1>
                    <color class="block h-12 min-h-[48px] w-[78px] bg-[rgb(217,217,217)]"></color>
                    <h1 class="font-Abel flex items-center justify-center text-center text-[45px] font-normal leading-[0.48] text-black">-</h1>
                    <color class="block h-12 min-h-[48px] w-[78px] bg-[rgb(217,217,217)]"></color>
                  </div>
                  <h2 class="font-Abel mt-7 flex items-center text-[26px] font-normal leading-[0.84] text-black">背面末三碼  CVV2/CVC2/CAV2</h2>
                  <div class="mt-[17px] flex w-[110px] max-w-[85%] flex-col items-center gap-y-[19px]">
                    <!-- Section for credit card expiry date. -->

                    <color class="block min-h-[48px] w-[93.64%] bg-[rgb(217,217,217)]"></color>
                    <h2 class="font-Abel flex w-full items-center text-[26px] font-normal leading-[0.84] text-black">
                      有效年月
                      <br />
                      Valid Thru
                    </h2>
                  </div>
                </div>
                <color class="absolute left-0 bottom-[-54px] block h-12 w-[78px] bg-[rgb(217,217,217)]"></color>
              </div>
              <div class="flex w-[271.2375183105469px] max-w-[85%]">
                <h3 class="font-Abel mt-4 mb-2.5 flex items-center justify-center text-center text-[20px] font-normal leading-[1.1] text-black">月</h3>
                <div class="flex w-[119px] min-w-0 items-center gap-x-2.5 tn:gap-x-2">
                  <color class="block h-12 min-h-[48px] w-[77px] bg-[rgb(217,217,217)]"></color>
                  <h3 class="font-Abel flex items-center justify-center text-center text-[20px] font-normal leading-[1.1] text-black">日</h3>
                </div>
              </div>
            </div>
          </div>
          <h2 class="font-Abel mt-[19px] ml-3 flex w-[158px] max-w-[85%] items-center text-[26px] font-normal leading-[0.84] text-black tn:mt-[19px] tn:mr-0 tn:mb-0 tn:ml-2">
            手機號碼
            <br />
            Phone Number
          </h2>
          <p class="mt-1.5 ml-3 min-h-[48px] w-[227px] max-w-[85%] bg-[rgb(217,217,217)] tn:mt-1.5 tn:mr-0 tn:mb-0 tn:ml-2"></p>
        </div>
        <button class="font-Roboto mx-auto flex w-[343px] max-w-full items-center justify-center rounded-lg bg-[rgb(90,180,197)] pt-3.5 pr-2 pb-3.5 pl-2 text-center text-[24px] font-normal leading-[0.91] text-white">
          <!-- TODO -->
           送出  Confirm
        </button>
      </div>
    </div>
  </section>

</template>

<style scoped lang="scss">
  @import 'Page3.scss';
</style>

