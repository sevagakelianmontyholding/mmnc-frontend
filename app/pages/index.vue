<!-- pages/index.vue  (NO TypeScript) -->
<template>
  <main class="min-h-screen bg-neutral-100 p-4 sm:p-8">
    <div class="mx-auto w-full max-w-6xl">
      <section class="bg-white border border-neutral-300">
        <!-- RESPONSIVE GRID (works on mobile + desktop) -->
        <div class="grid grid-cols-1 md:grid-cols-12">

          <!-- Top info bar -->
          <div class="col-span-1 flex flex-col justify-center md:col-span-2 border-b border-neutral-300 md:border-r px-6 py-5">
            <div class="w-full">
              <svg width="133" height="27" viewBox="0 0 133 27" fill="none" xmlns="http://www.w3.org/2000/svg"><g clip-path="url(#clip0_642_4255)"><path d="M77.618 3.84546C82.2664 3.84546 86.3581 7.19362 86.3581 12.1203C86.3581 17.047 82.2664 20.4284 77.618 20.4284C72.9697 20.4284 68.8779 17.1135 68.8779 12.1203C68.8779 7.12715 72.9987 3.84546 77.618 3.84546ZM77.618 16.4613C79.9111 16.4613 81.8635 14.6003 81.8635 12.1203C81.8635 9.64035 79.9111 7.81257 77.618 7.81257C75.325 7.81257 73.3726 9.64035 73.3726 12.1203C73.3726 14.6003 75.3582 16.4613 77.618 16.4613Z" fill="#0E1414"></path><path d="M87.5713 3.84546H92.1906V6.3545C93.524 4.49349 95.1981 3.84546 97.1214 3.84546C101.587 3.84546 102.796 7.40963 102.796 11.439V20.0878H98.1766V11.5304C98.1766 9.3288 97.3707 7.65472 95.2313 7.65472C93.092 7.65472 92.1947 9.35787 92.1947 11.5595V20.0836H87.5754V3.84546H87.5713Z" fill="#0E1414"></path><path d="M109.504 3.8828H113.908V7.50928H109.504V15.2566C109.504 15.9378 109.783 16.6523 110.684 16.6523C111.586 16.6523 111.893 15.9088 111.893 15.1652C111.893 14.6999 111.768 14.0477 111.677 13.8027H115.337C115.615 14.3925 115.71 15.1361 115.71 15.6927C115.71 18.0481 114.161 20.4367 110.41 20.4367C107.618 20.4367 104.893 19.4438 104.893 14.8246L104.864 0.2854H109.513V3.88696L109.504 3.8828Z" fill="#0E1414"></path><path d="M4.6193 3.84546H0V20.0878H4.6193V3.84546Z" fill="#0E1414"></path><path d="M18.7555 3.84546C17.2351 3.84546 14.9421 4.18609 13.7332 6.51235C12.9273 4.90059 11.2823 3.84546 8.86469 3.84546C7.78048 3.84546 6.93306 4.17778 6.15625 4.72196V7.88319C6.39718 7.76688 6.76274 7.65887 7.25292 7.65887C9.30086 7.65887 9.91981 9.36203 9.91981 11.5346V20.0919H14.5059V11.5678C14.5059 9.42849 15.1248 7.66302 17.1395 7.66302C19.1543 7.66302 19.8064 9.36618 19.8064 11.5387V20.0961H24.4257V11.4474C24.4257 7.41794 23.2169 3.85377 18.7513 3.85377L18.7555 3.84546Z" fill="#0E1414"></path><path d="M48.1994 3.84546H43.5801V20.0878H48.1994V3.84546Z" fill="#0E1414"></path><path d="M62.3316 3.84546C60.8113 3.84546 58.5182 4.18609 57.3094 6.51235C56.5035 4.90059 54.8585 3.84546 52.4409 3.84546C51.3567 3.84546 50.5092 4.17778 49.7324 4.72196V7.88319C49.9734 7.76688 50.3389 7.65887 50.8291 7.65887C52.877 7.65887 53.496 9.36203 53.496 11.5346V20.0919H58.0821V11.5678C58.0821 9.42849 58.701 7.66302 60.7157 7.66302C62.7304 7.66302 63.3826 9.36618 63.3826 11.5387V20.0961H68.0019V11.4474C68.0019 7.41794 66.7931 3.85377 62.3275 3.85377L62.3316 3.84546Z" fill="#0E1414"></path><path d="M31.712 11.2397L28.4884 3.84546H23.8691L29.3525 16.5485L31.712 11.2397Z" fill="#0E1414"></path><path d="M37.2576 3.84546L26.9639 27.0001H31.5956L41.8893 3.84546H37.2576Z" fill="#0E1414"></path><path d="M122.822 11.2397L119.599 3.84546H114.979L120.467 16.5485L122.822 11.2397Z" fill="#0E1414"></path><path d="M128.368 3.84546L118.078 27.0001H122.71L132.999 3.84546H128.368Z" fill="#0E1414"></path></g><defs><clipPath id="clip0_642_4255"><rect width="133" height="26.7188" fill="white" transform="translate(0 0.28125)"></rect></clipPath></defs></svg>
            </div>
            
          </div>
          
          <!-- Title block -->
          <div class="md:hidden col-span-1 md:col-span-12 border-b border-neutral-300 px-6 md:px-8 py-8 md:py-10">
            <div class="flex items-end justify-between gap-6">
              
              <h1 class="leading-[0.92] tracking-tight text-neutral-950">
                <div class="mb-2 inline-flex items-center rounded-full border border-neutral-300 px-3 py-1 text-[11px] font-semibold tracking-wide">
                  <span class="mr-2 inline-block h-2 w-2 rounded-full bg-[#ff4a17]" />
                  EVENT DETAILS
                </div>
                <span class="block text-4xl sm:text-6xl md:text-7xl font-black">MYMONTY</span>
                <span class="block text-4xl sm:text-6xl md:text-7xl font-black">NETWORKING CIRCLE</span>
              </h1>

              <div class="hidden sm:flex pb-2 md:pb-3 pr-0 md:pr-2 items-center gap-2 md:gap-3 text-neutral-950">
                <span class="text-2xl md:text-3xl font-black">→</span>
                <span class="text-2xl md:text-3xl font-black">→</span>
                <span class="text-2xl md:text-3xl font-black">→</span>
              </div>
            </div>
          </div>
          <!-- Reserve -->
          <div class="md:hidden flex-col justify-center col-span-1 md:col-span-3 border-b border-neutral-300 px-6 py-5 flex items-start md:justify-end">
            <button
                type="button"
                @click="openModal"
                class="pulse-button h-12 w-full md:max-w-[240px] rounded-xl bg-[#ff4a17] text-white font-semibold text-sm shadow-sm hover:brightness-95 active:brightness-90 transition"
                >
                Reserve Seat
            </button>
          </div>
          <!-- Top info bar -->
          <div class="col-span-1 md:col-span-3 border-b  md:border-r border-neutral-300 px-6 py-5">
            

            <div class="mt-4 space-y-1 text-[11px] font-semibold tracking-[0.02em] text-neutral-900">
              <p class="uppercase">MONTY CLUB, GEFINOR CENTER</p>
              <p class="uppercase">(BLOCK E, 6TH FLOOR, HAMRA)</p>
            </div>
          </div>

          <div class="flex flex-col justify-end col-span-1 md:col-span-2 border-b md:border-r border-neutral-300 px-6 py-5">
            <div class="text-[11px] font-semibold uppercase tracking-[0.02em] text-neutral-900">
              <p>THU, 12 FEB 2026</p>
              <p class="mt-1">5:00 PM – 8:00 PM</p>
            </div>
          </div>

          <div class="flex flex-col justify-end col-span-1 md:col-span-2 border-b md:border-r border-neutral-300 px-6 py-5">
            <div class="text-[11px] font-semibold uppercase tracking-[0.02em] text-neutral-900">
              <p>FREE PARKING</p>
              <p class="mt-1">AVAILABLE ON LEVEL -1</p>
            </div>
          </div>

          <!-- Reserve -->
          <div class="max-md:hidden flex-col justify-center col-span-1 md:col-span-3 border-b border-neutral-300 px-6 py-5 flex items-start md:justify-end">
            <button
                type="button"
                @click="openModal"
                class="pulse-button h-12 w-full md:max-w-[240px] rounded-xl bg-[#ff4a17] text-white font-semibold text-sm shadow-sm hover:brightness-95 active:brightness-90 transition"
                >
                Reserve Seat
            </button>
          </div>

          <!-- Title block -->
          <div class="max-md:hidden col-span-1 md:col-span-12 border-b border-neutral-300 px-6 md:px-8 py-8 md:py-10">
            <div class="flex items-end justify-between gap-6">
              
              <h1 class="leading-[0.92] tracking-tight text-neutral-950">
                <div class="mb-2 inline-flex items-center rounded-full border border-neutral-300 px-3 py-1 text-[11px] font-semibold tracking-wide">
                  <span class="mr-2 inline-block h-2 w-2 rounded-full bg-[#ff4a17]" />
                  EVENT DETAILS
                </div>
                <span class="block text-5xl sm:text-6xl md:text-7xl font-black">MYMONTY</span>
                <span class="block text-5xl sm:text-6xl md:text-7xl font-black">NETWORKING CIRCLE</span>
              </h1>

              <div class="hidden sm:flex pb-2 md:pb-3 pr-0 md:pr-2 items-center gap-2 md:gap-3 text-neutral-950">
                <span class="text-2xl md:text-3xl font-black">→</span>
                <span class="text-2xl md:text-3xl font-black">→</span>
                <span class="text-2xl md:text-3xl font-black">→</span>
              </div>
            </div>
          </div>

          <!-- Mid strip (left) -->
          <div class="col-span-1 md:col-span-5 border-b border-neutral-300 md:border-r border-neutral-300 px-6 py-6">
            <p class="max-w-sm text-[12px] leading-5 text-neutral-800">
              Join a curated circle of leaders and innovators for meaningful conversations and lasting connections.
            </p>
          </div>

          <div class="col-span-1 md:flex md:flex-col md:justify-center md:col-span-3 border-b border-neutral-300 md:border-r border-neutral-300 px-6 py-6">
            <div class="flex items-center justify-between gap-4">
              <a class="flex items-center gap-1" href="https://shorturl.at/Kx0iq" target="_blank">
                <span class="inline-flex items-center justify-center">
                  <svg width="22" height="22" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                    <path d="M12 22s7-4.5 7-11a7 7 0 1 0-14 0c0 6.5 7 11 7 11Z" fill="#ff4a17" />
                    <circle cx="12" cy="11" r="2.2" fill="white" />
                  </svg>
                </span>
                <p class="text-sm font-black uppercase tracking-tight text-neutral-950">MONTY CLUB</p>
                
              </a>
            </div>
          </div>

          <!-- Pixel hero (RIGHT on desktop, STACKED on mobile) -->
          <div class="col-span-1 md:col-span-4 md:row-span-3 border-b border-neutral-300 px-0 py-0 min-h-[400px]">
            <div class="w-full relative h-full">
                <img src="/mmnc-bg.webp" class="w-full h-full object-cover absolute top-0 left-0"/>
            </div>
          </div>

          <!-- Date block -->
          <div class="col-span-1 md:col-span-8 border-b border-neutral-300 md:border-r border-neutral-300 px-6 md:px-8 py-8">
            <div class="flex flex-col sm:flex-row sm:items-end sm:justify-between gap-6">
              <div>
                <p class="text-[64px] sm:text-[80px] md:text-[92px] leading-none font-black tracking-tight text-[#ff4a17]">
                  12.02.26
                </p>

                <div class="mt-4 md:mt-6 flex items-center gap-3 text-sm font-black tracking-[0.08em] text-neutral-950">
                  <span>5:00 PM - 8:00 PM</span>
                  <span class="inline-flex items-center gap-1">
                    <span class="h-2 w-2 bg-neutral-950 rotate-45 inline-block" />
                    <span class="h-2 w-2 bg-neutral-950 rotate-45 inline-block" />
                    <span class="h-2 w-2 bg-neutral-950 rotate-45 inline-block" />
                  </span>
                </div>
              </div>

              <div class="sm:text-right">
                <div class="inline-flex items-center gap-3">
                  <div class="text-[10px] font-black uppercase leading-4 tracking-[0.12em] text-neutral-950">
                    <div>Parking available</div>
                    <div>on level -1</div>
                  </div>
                  <span class="text-xl font-black">→</span>
                </div>
              </div>
            </div>
          </div>

          <!-- Bottom copy -->
          <div class="col-span-1 md:col-span-8 md:border-r border-neutral-300 px-6 py-6">
            <p class="text-[10px] md:text-[9px] leading-4 font-semibold uppercase tracking-[0.04em] text-neutral-700">
              MyMonty Networking Circle is designed for professionals who value quality engagement. Through carefully curated
              discussions and relaxed networking moments, C-level executives will explore ideas, share experiences, and build
              relationships that extend beyond the evening.
            </p>

            <p class="mt-3 text-[10px] md:text-[9px] leading-4 font-black uppercase tracking-[0.04em] text-neutral-950">
              Seats are limited for this gathering, secure your place today.
            </p>
            <div class="mt-4">
              <svg data-v-79e92f9e="" width="70" height="" viewBox="0 0 120 51" fill="none" xmlns="http://www.w3.org/2000/svg" class="logo">
              
              <path fill="#000000" class="close-nav" d="M26.6606 19.8275L28.9727 20.056V22.0455H17.5467V20.056L19.8587 19.7872C19.8991 17.0852 19.8856 14.5043 19.9125 12.5417L20.0066 5.65924L14.5087 22.0455H11.5379L5.60983 5.49793L5.74426 12.3401V19.6259L8.55371 20.056V22.0455H0.03125V20.056L3.3784 19.6393V2.32553L0.434521 1.98947V0H10.4491L15.1136 13.3348L19.5092 0H28.8114V1.98947L26.6606 2.20455C26.6068 4.96023 26.6068 7.72936 26.6068 10.4716V11.547C26.6068 14.3296 26.6068 17.0987 26.6606 19.8006V19.8275ZM47.093 13.6978C47.093 18.8328 43.9475 22.5966 38.1672 22.5966C32.387 22.5966 29.2415 18.7387 29.2415 13.6978C29.2415 8.65688 32.965 5.04089 38.1672 5.04089C43.3694 5.04089 47.093 8.56279 47.093 13.6978ZM40.3315 13.7919C40.3315 8.8854 39.6593 6.89593 38.1672 6.89593C36.6751 6.89593 36.003 8.8854 36.003 13.7919C36.003 18.6983 36.6751 20.7281 38.1672 20.7281C39.6593 20.7281 40.3315 18.7387 40.3315 13.7919ZM65.6972 14.9479V10.6867C65.6972 7.00347 63.533 5.04089 60.5891 5.04089C58.6803 5.04089 57.2688 5.59202 55.4541 7.72936L55.2794 5.41727L54.6745 5.04089L47.2005 7.37986V8.76442L49.0287 9.0736C49.0959 10.4313 49.1362 10.9959 49.1362 12.8643V14.9614C49.1362 16.3459 49.1228 18.3488 49.0959 19.9754L47.55 20.3383V22.0589H56.879V20.3383L55.602 20.056C55.5751 18.4026 55.5617 16.3728 55.5617 14.9614V9.57096C56.3682 9.00639 57.1747 8.68377 57.7662 8.68377C58.855 8.68377 59.2852 9.35589 59.2852 11.1572V14.9748C59.2852 16.4131 59.2718 18.3892 59.2449 20.0022L57.8065 20.3517V22.0724H67.1759V20.3517L65.7644 20.056C65.7375 18.4295 65.7241 16.4131 65.7241 14.9748L65.6972 14.9479ZM78.5212 18.7387C77.9432 19.1823 77.4324 19.4108 76.8678 19.4108C75.9268 19.4108 75.2144 18.6983 75.2144 17.1793V8.11919H78.3196V5.57858H75.2144V0.779657H71.1951L69.1519 5.59202L66.8667 5.88776V8.11919H68.7889V13.9397C68.7889 15.2571 68.7486 16.2384 68.7486 17.5557C68.7486 21.1717 70.6709 22.5966 74.018 22.5966C76.7872 22.5966 78.454 21.4809 79.3681 19.5183L78.5212 18.7387ZM96.9642 5.57858H90.6731V7.16478L92.6223 7.55461L89.7725 15.741L86.8555 7.56805L88.845 7.1379V5.57858H78.6019V7.16478L80.0805 7.43363L87.0706 23.4973C86.5866 24.828 85.8876 25.9438 85.1214 26.8175L84.8929 26.4411C83.9788 24.949 82.7287 24.7474 81.8146 24.7474C80.3628 24.7474 79.1127 25.5271 78.8035 27.2208C78.9783 28.7129 80.5913 29.8958 82.4598 29.8958C85.7398 29.8958 87.1243 27.6913 88.5492 24.0484L94.9478 7.50084L96.9776 7.16478V5.57858H96.9642Z"></path>
              
              <path fill="#000000" class="close-nav" d="M17.7574 28.2285L17.9993 33.9818H14.8269L14.1817 30.2314H9.12737C9.0736 32.7048 9.0736 35.232 9.0736 37.7726H12.2326L12.6358 35.3395H14.7597V42.6791H12.6358L12.2057 39.9368H9.0736C9.0736 42.6253 9.0736 45.3138 9.12737 47.9888L12.125 48.2845V50.274H0V48.2845L2.31209 48.056C2.36586 45.3406 2.36586 42.585 2.36586 39.8024V38.727C2.36586 35.9848 2.36586 33.2156 2.31209 30.4734L0 30.2449V28.2554H17.7574V28.2285ZM26.347 43.1764V38.6732L26.4546 33.6323L25.8497 33.256L17.9993 35.5949V36.9795L19.8275 37.2887C19.8947 38.6463 19.935 39.6949 19.935 41.5499V43.1764C19.935 44.5744 19.9216 46.5639 19.8947 48.2039L18.3892 48.5534V50.274H27.8257V48.5534L26.4142 48.2576C26.3874 46.6177 26.3739 44.5879 26.3739 43.1764H26.347ZM46.5778 43.1764V38.9152C46.5778 35.232 44.4136 33.2694 41.4697 33.2694C39.5609 33.2694 38.1494 33.8205 36.3347 35.9579L36.16 33.6458L35.5551 33.2694L28.0811 35.6084V36.9929L29.9093 37.3021C29.9765 38.6598 30.0168 39.2244 30.0168 41.0929V43.1899C30.0168 44.5744 30.0034 46.5773 29.9765 48.2039L28.4306 48.5668V50.2874H37.7596V48.5668L36.4826 48.2845C36.4557 46.6311 36.4423 44.6013 36.4423 43.1899V37.7995C37.2488 37.2349 38.0553 36.9123 38.6468 36.9123C39.7356 36.9123 40.1658 37.5844 40.1658 39.3857V43.2033C40.1658 44.6416 40.1523 46.6177 40.1255 48.2308L38.6871 48.5803V50.3009H48.0565V48.5803L46.645 48.2845C46.6181 46.658 46.6047 44.6416 46.6047 43.2033L46.5778 43.1764ZM65.3299 47.3973L66.3112 47.935C65.5047 49.9917 64.1873 50.8117 61.7811 50.8117C59.6572 50.8117 58.4071 49.9514 57.8425 48.419C56.4983 49.8707 55.4498 50.8117 53.0167 50.8117C50.3417 50.8117 48.621 49.2255 48.621 46.4429C48.621 43.8351 50.0728 42.0742 55.5573 40.6224C56.1084 40.4745 56.8478 40.2863 57.614 40.0847V38.8749C57.614 35.9982 57.1704 35.0841 55.0465 35.0841C54.8852 35.0841 54.7104 35.0841 54.5357 35.0976V36.2267C54.5357 38.969 53.2183 40.0175 51.7665 40.0175C50.4492 40.0175 49.5351 39.4126 49.1991 38.1893C49.1991 35.2858 52.0085 33.256 57.4527 33.256C62.1172 33.256 63.8378 35.1782 63.8378 39.8158V47.5586C63.8378 47.8947 64.0394 48.1367 64.4158 48.1367C64.6847 48.1367 64.9266 48.0022 65.3299 47.3973ZM57.6274 47.2898V41.6709C57.251 41.7919 56.915 41.9263 56.6461 42.0607C55.7052 42.5043 54.4416 43.5797 54.4416 45.4079C54.4416 47.0613 55.2212 47.8813 56.2025 47.8813C56.6058 47.8813 57.036 47.7065 57.6274 47.2898ZM84.7272 43.1764V38.9152C84.7272 35.232 82.563 33.2694 79.6191 33.2694C77.7103 33.2694 76.2989 33.8205 74.4842 35.9579L74.3094 33.6458L73.7045 33.2694L66.2305 35.6084V36.9929L68.0587 37.3021C68.1259 38.6598 68.1662 39.2244 68.1662 41.0929V43.1899C68.1662 44.5744 68.1528 46.5773 68.1259 48.2039L66.58 48.5668V50.2874H75.909V48.5668L74.632 48.2845C74.6051 46.6311 74.5917 44.6013 74.5917 43.1899V37.7995C75.3982 37.2349 76.2048 36.9123 76.7962 36.9123C77.8851 36.9123 78.3152 37.5844 78.3152 39.3857V43.2033C78.3152 44.6416 78.3018 46.6177 78.2749 48.2308L76.8366 48.5803V50.3009H86.2059V48.5803L84.7944 48.2845C84.7676 46.658 84.7541 44.6416 84.7541 43.2033L84.7272 43.1764ZM96.8119 35.0976C96.8119 35.0976 96.906 35.0976 96.9463 35.0976L97.0136 36.509C97.148 39.4798 98.5057 40.367 99.9171 40.367C101.329 40.367 102.041 39.7621 102.485 38.4044C102.31 35.6353 99.8096 33.2694 96.0323 33.2694C90.5881 33.2694 86.3538 36.4821 86.3538 42.101C86.3538 47.7199 90.5075 50.8251 95.1182 50.8251C98.3309 50.8251 100.872 49.6019 102.323 46.8731L101.006 45.5826C100.065 46.4967 99.0434 47.1688 97.5513 47.1688C94.8493 47.1688 93.1153 45.1121 93.1153 41.3483C93.1153 36.6838 95.2392 35.0976 96.7985 35.0976H96.8119ZM119.18 42.464H109.797C110.12 45.7574 111.935 47.1688 113.937 47.1688C115.631 47.1688 116.841 46.4967 117.795 45.5826L119.113 46.8731C117.661 49.6153 115.12 50.8251 111.773 50.8251C106.706 50.8251 102.982 47.5855 102.982 41.9935C102.982 36.4015 107.646 33.2694 112.082 33.2694C116.922 33.2694 119.355 36.5897 119.355 40.6761C119.355 41.3886 119.314 41.8591 119.18 42.464ZM113.4 38.27C113.4 35.931 112.553 35.0976 111.679 35.0976C110.631 35.0976 109.851 36.3477 109.757 40.5417H111.343C112.97 40.5417 113.4 40.004 113.4 38.27Z"></path>
              
              <path class="close-nav" d="M103.013 20.4067C103.013 21.6568 102.193 22.1676 100.364 22.1676C98.7782 22.1676 97.7969 21.6434 97.7969 20.1513H98.7782C98.7782 21.0922 99.5713 21.2132 100.472 21.2132C101.467 21.2132 101.964 20.9981 101.964 20.4605C101.964 19.7211 100.942 19.7077 100.163 19.5598C98.8051 19.291 97.8506 18.9684 97.8506 17.7317C97.8506 16.495 98.6572 15.9707 100.445 15.9707C102.004 15.9707 102.959 16.495 102.959 17.9871H101.977C101.977 17.0595 101.225 16.9386 100.351 16.9386C99.2755 16.9386 98.9126 17.194 98.9126 17.6644C98.9126 18.1618 99.4503 18.3231 100.579 18.4979C102.139 18.7398 103.026 19.1431 103.026 20.3798L103.013 20.4067ZM104.316 20.9847C103.9 20.9847 103.725 21.1863 103.725 21.5762C103.725 21.966 103.9 22.1676 104.316 22.1676C104.733 22.1676 104.908 21.966 104.908 21.5762C104.908 21.1863 104.733 20.9847 104.316 20.9847ZM108.752 16.1051L111.185 22.0467H110.083L109.653 21.025H106.723L106.306 22.0467H105.204L107.637 16.1051H108.739H108.752ZM109.277 20.0841L108.201 17.4494L107.112 20.0841H109.277ZM112.073 20.9847C111.656 20.9847 111.481 21.1863 111.481 21.5762C111.481 21.966 111.656 22.1676 112.073 22.1676C112.489 22.1676 112.664 21.966 112.664 21.5762C112.664 21.1863 112.489 20.9847 112.073 20.9847ZM114.573 16.1051H113.551V22.0467H118.176V21.1191H114.573V16.1186V16.1051ZM119.412 20.9847C118.995 20.9847 118.821 21.1863 118.821 21.5762C118.821 21.966 118.995 22.1676 119.412 22.1676C119.829 22.1676 120.004 21.966 120.004 21.5762C120.004 21.1863 119.829 20.9847 119.412 20.9847Z" fill="#D4A23C"></path>
              
              <path class="close-nav" d="M23.668 25.5275L27.2033 29.1435C27.4453 29.3855 27.4453 29.7887 27.2033 30.0307L25.5768 31.6841C25.3348 31.9395 24.9316 31.9261 24.6896 31.6572L23.668 30.5146C23.4394 30.2592 23.0362 30.2458 22.7942 30.4877L21.5844 31.6841C21.3424 31.9261 20.9392 31.9126 20.7106 31.6572L19.2992 30.1113C19.0707 29.8694 19.0841 29.493 19.2992 29.251L22.8077 25.5275C23.0496 25.2721 23.4395 25.2721 23.6814 25.5275H23.668Z" fill="#D4A23C"></path></svg>
            </div>
          </div>
        </div>

        <!-- ✅ REMOVE your md:hidden mobile block completely -->
      </section>
    </div>

    <!-- MODAL -->
    <Teleport to="body">
      <div v-if="isOpen" class="fixed inset-0 z-[60] flex items-center justify-center p-4">
        <!-- Backdrop (outside click closes) -->
        <div class="absolute inset-0 bg-black/50" @click.self="closeModal"></div>

        <!-- Panel -->
        <div
            class="relative w-full max-w-3xl overflow-hidden rounded-2xl border border-neutral-200 bg-white shadow-2xl
                    flex flex-col max-h-[92dvh] sm:max-h-[88vh]"
            role="dialog"
            aria-modal="true"
        >
          <!-- Header -->
          <div class="flex items-start justify-between gap-4 border-b border-neutral-200 px-6 py-5">
            <div>
              <p class="text-xs font-black uppercase tracking-[0.14em] text-neutral-500">Reservation</p>
              <h2 class="mt-1 text-2xl font-black tracking-tight text-neutral-950">
                Reserve Tickets
              </h2>
              <p class="mt-2 text-sm text-neutral-600">
                Thu, 12 Feb 2026 • 5:00–8:00 PM • Monty Club
              </p>
            </div>

            <button
              type="button"
              class="h-10 w-10 rounded-xl border border-neutral-200 bg-white text-neutral-800 hover:bg-neutral-50"
              @click="closeModal"
              aria-label="Close"
            >
              ✕
            </button>
          </div>

          <!-- Body -->
          <form class="px-6 py-6 overflow-y-auto" style="max-height: calc(92dvh - 84px);" @submit.prevent="submitReservation">
            <div class="grid gap-5">
              <!-- Add/Remove controls -->
              <div class="flex flex-col sm:flex-row sm:items-center sm:justify-between gap-3">
                <div>
                  <p class="text-xs font-black uppercase tracking-[0.14em] text-neutral-500">Tickets</p>
                  <p class="mt-1 text-sm text-neutral-700">
                    Add up to <span class="font-black">3</span> tickets. Fill attendee details for each ticket.
                  </p>
                </div>

                <div class="flex items-center gap-2">
                  <button
                    type="button"
                    @click="removeTicket"
                    :disabled="tickets.length === 1"
                    class="h-10 rounded-xl border border-neutral-200 bg-white px-4 text-sm font-semibold text-neutral-900
                           hover:bg-neutral-50 disabled:opacity-50 disabled:cursor-not-allowed"
                  >
                    − Remove
                  </button>

                  <button
                    type="button"
                    @click="addTicket"
                    :disabled="tickets.length === 3"
                    class="h-10 rounded-xl bg-neutral-950 px-4 text-sm font-semibold text-white
                           hover:brightness-110 active:brightness-95 disabled:opacity-50 disabled:cursor-not-allowed"
                  >
                    + Add Ticket
                  </button>
                </div>
              </div>

              <!-- Ticket repeaters -->
              <div
                v-for="(t, idx) in tickets"
                :key="idx"
                class="rounded-2xl border border-neutral-200 p-5"
              >
                <div class="flex items-center justify-between">
                  <p class="text-sm font-black uppercase tracking-[0.10em] text-neutral-950">
                    Ticket {{ idx + 1 }}
                  </p>
                  <span class="text-xs font-semibold text-neutral-500">
                    Attendee {{ idx + 1 }}
                  </span>
                </div>

                <div class="mt-4 grid grid-cols-12 gap-3">
                  <div class="col-span-12 sm:col-span-5">
                    <label class="block text-xs font-black uppercase tracking-[0.12em] text-neutral-600">
                      Full Name
                    </label>
                    <input
                      v-model.trim="t.fullName"
                      type="text"
                      class="mt-2 h-11 w-full rounded-xl border px-4 text-sm font-semibold outline-none transition
                             focus:ring-2 focus:ring-neutral-900/10"
                      :class="fieldClass(errors[idx] && errors[idx].fullName)"
                      placeholder="John Doe"
                      autocomplete="name"
                    />
                    <p v-if="errors[idx] && errors[idx].fullName" class="mt-2 text-xs font-semibold text-red-600">
                      {{ errors[idx].fullName }}
                    </p>
                  </div>

                  <div class="col-span-12 sm:col-span-3">
                    <label class="block text-xs font-black uppercase tracking-[0.12em] text-neutral-600">
                      Phone Number
                    </label>
                    <input
                      v-model.trim="t.phone"
                      type="tel"
                      class="mt-2 h-11 w-full rounded-xl border px-4 text-sm font-semibold outline-none transition
                             focus:ring-2 focus:ring-neutral-900/10"
                      :class="fieldClass(errors[idx] && errors[idx].phone)"
                      placeholder="+961..."
                      autocomplete="tel"
                    />
                    <p v-if="errors[idx] && errors[idx].phone" class="mt-2 text-xs font-semibold text-red-600">
                      {{ errors[idx].phone }}
                    </p>
                  </div>

                  <div class="col-span-12 sm:col-span-4">
                    <label class="block text-xs font-black uppercase tracking-[0.12em] text-neutral-600">
                      Email Address
                    </label>
                    <input
                      v-model.trim="t.email"
                      type="email"
                      class="mt-2 h-11 w-full rounded-xl border px-4 text-sm font-semibold outline-none transition
                             focus:ring-2 focus:ring-neutral-900/10"
                      :class="fieldClass(errors[idx] && errors[idx].email)"
                      placeholder="name@email.com"
                      autocomplete="email"
                    />
                    <p v-if="errors[idx] && errors[idx].email" class="mt-2 text-xs font-semibold text-red-600">
                      {{ errors[idx].email }}
                    </p>
                  </div>
                </div>
              </div>

              <!-- Submit -->
              <div class="flex flex-col sm:flex-row sm:items-center sm:justify-between gap-3 border-t border-neutral-200 pt-5">

                  <div v-if="submitSuccess" class="mt-2 flex flex-wrap gap-2">
                    <button
                        type="button"
                        @click="downloadTicketsPdf"
                        class="h-11 rounded-xl border border-neutral-200 bg-white px-5 text-sm font-semibold text-neutral-950
                            hover:bg-neutral-50"
                    >
                        Download Tickets PDF
                    </button>
                </div>
                <button
                  type="submit"
                  :disabled="isSubmitting"
                  class="h-12 rounded-xl bg-[#ff4a17] px-6 text-white text-sm font-semibold shadow-sm
                         hover:brightness-95 active:brightness-90 disabled:opacity-60 disabled:cursor-not-allowed w-full"
                >
                  {{ isSubmitting ? 'Submitting...' : 'Submit Reservation' }}
                </button>
              </div>
 
              <p v-if="submitError" class="text-sm font-semibold text-red-600">
                {{ submitError }}
              </p>
              <p v-if="submitSuccess" class="text-sm font-semibold text-emerald-600">
                Reservation submitted successfully ✅
              </p>

              <div v-if="submitSuccess" class="mt-2 flex flex-wrap gap-2">
                    <button
                        type="button"
                        @click="closeModal"
                        class="h-11 rounded-xl bg-neutral-950 px-5 text-sm font-semibold text-white
                            hover:brightness-110 active:brightness-95"
                    >
                        Close
                    </button>
                </div>
                
            </div>
          </form>
        </div>
      </div>
    </Teleport>
  </main>
</template>

<script setup>
/**
 * ✅ Install once:
 *    npm i jspdf
 *
 * ✅ Configure to match your WP + CF7:
 * - CF7_BASE_URL: WordPress base (no trailing slash)
 * - CF7_FORM_ID: your CF7 form id
 * - CF7_FIELD_TICKETS: a textarea/text field name to store ALL ticket data as ONE field (CFDB7 friendly)
 * - CF7_FILE_FIELD: a CF7 file field name (must exist) that accepts pdf
 *
 * CF7 endpoint:
 *   POST {base}/wp-json/contact-form-7/v1/contact-forms/{id}/feedback
 */
import { jsPDF } from 'jspdf'
import { onBeforeUnmount, onMounted, ref } from 'vue'

const CF7_BASE_URL = 'https://backend.montyfinance.com'
const CF7_FORM_ID = 27
const CF7_FIELD_TICKETS = 'tickets_summary' // create: [textarea tickets_summary]
const CF7_FIELD_COUNT = 'ticket_count'       // optional: [text ticket_count]
const CF7_FILE_FIELD = 'ticket_pdf'          // create: [file ticket_pdf limit:10mb filetypes:pdf]

// Modal
const isOpen = ref(false)
const isSubmitting = ref(false)
const submitError = ref('')
const submitSuccess = ref(false)
const pdfBlobForDownload = ref(null)
const pdfFileNameForDownload = ref('')

// Tickets (start with 1)
const tickets = ref([{ fullName: '', phone: '', email: '' }])
const errors = ref([{}])

function openModal() {
  submitError.value = ''
  submitSuccess.value = false
  isOpen.value = true
}

function closeModal() {
  isOpen.value = false
}

// Escape to close
function onKeydown(e) {
  if (!isOpen.value) return
  if (e.key === 'Escape') closeModal()
}

onMounted(() => window.addEventListener('keydown', onKeydown))
onBeforeUnmount(() => window.removeEventListener('keydown', onKeydown))

// Add/Remove (max 3)
function addTicket() {
  if (tickets.value.length >= 3) return
  tickets.value.push({ fullName: '', phone: '', email: '' })
  errors.value.push({})
}

function removeTicket() {
  if (tickets.value.length <= 1) return
  tickets.value.pop()
  errors.value.pop()
}

// UI helper
function fieldClass(err) {
  return err ? 'border-red-500 focus:ring-red-500/20' : 'border-neutral-300 focus:ring-neutral-900/10'
}

// Validation helpers
function isValidEmail(email) {
  // pragmatic email regex (not over-strict)
  return /^[^\s@]+@[^\s@]+\.[^\s@]{2,}$/i.test(String(email || '').trim())
}

function isValidPhone(phone) {
  // allow +, spaces, dashes, parentheses; requires at least 7 digits
  const s = String(phone || '').trim()
  const digits = s.replace(/\D/g, '')
  if (digits.length < 7) return false
  return /^[+()\d\s-]+$/.test(s)
}

function validateAll() {
  const nextErrors = tickets.value.map(() => ({}))
  let ok = true

  tickets.value.forEach((t, i) => {
    if (!t.fullName || t.fullName.trim().length < 2) {
      nextErrors[i].fullName = 'Full Name is required.'
      ok = false
    }
    if (!t.phone || !isValidPhone(t.phone)) {
      nextErrors[i].phone = 'Please enter a valid phone number.'
      ok = false
    }
    if (!t.email || !isValidEmail(t.email)) {
      nextErrors[i].email = 'Please enter a valid email address.'
      ok = false
    }
  })

  errors.value = nextErrors
  return ok
}

// Serialize ticket repeaters to ONE field (CFDB7 friendly)
function buildTicketsSummary() {
  return tickets.value
    .map((t, idx) => {
      const n = String(t.fullName || '').trim()
      const p = String(t.phone || '').trim()
      const e = String(t.email || '').trim()

      return [
        `===== Ticket ${idx + 1} =====`,
        `Full Name: ${n}`,
        `Phone: ${p}`,
        `Email: ${e}`,
        ``,
      ].join('\n')
    })
    .join('\n')
    .trim()
}

/**
 * Build a “nice PDF” with all ticket info.
 * We generate a single PDF containing separate “ticket cards”.
 */
function generateTicketsPdfBlob() {
  const doc = new jsPDF({ unit: 'pt', format: 'a4' })
  const W = doc.internal.pageSize.getWidth()
  const H = doc.internal.pageSize.getHeight()

  const margin = 48
  const accent = { r: 255, g: 74, b: 23 } // #ff4a17

  const title = 'MYMONTY NETWORK CIRCLE'
  const subtitle = 'Thu, 12 Feb 2026 • 5:00–8:00 PM • Monty Club (Gefinor Center, Hamra)'
  const small = 'Parking available on level -1 • Seats are limited'

  // Header
  doc.setFillColor(accent.r, accent.g, accent.b)
  doc.rect(0, 0, W, 72, 'F')

  doc.setTextColor(255, 255, 255)
  doc.setFont('helvetica', 'bold')
  doc.setFontSize(18)
  doc.text(title, margin, 44)

  doc.setTextColor(20, 20, 20)
  doc.setFont('helvetica', 'normal')
  doc.setFontSize(11)
  doc.text(subtitle, margin, 100, { maxWidth: W - margin * 2 })
  doc.setTextColor(90, 90, 90)
  doc.text(small, margin, 118, { maxWidth: W - margin * 2 })

  // Ticket cards layout
  let y = 150
  const cardGap = 14
  const cardH = 140

  tickets.value.forEach((t, idx) => {
    // New page if needed
    if (y + cardH + margin > H) {
      doc.addPage()
      y = margin
    }

    // Card background
    doc.setDrawColor(220, 220, 220)
    doc.setFillColor(250, 250, 250)
    doc.roundedRect(margin, y, W - margin * 2, cardH, 14, 14, 'FD')

    // Accent pill
    doc.setFillColor(accent.r, accent.g, accent.b)
    doc.roundedRect(margin + 16, y + 16, 86, 22, 10, 10, 'F')
    doc.setTextColor(255, 255, 255)
    doc.setFont('helvetica', 'bold')
    doc.setFontSize(10)
    doc.text(`TICKET ${idx + 1}`, margin + 28, y + 31)

    // Ticket info
    doc.setTextColor(15, 15, 15)
    doc.setFont('helvetica', 'bold')
    doc.setFontSize(14)
    doc.text(String(t.fullName || '').trim() || '—', margin + 16, y + 64)

    doc.setFont('helvetica', 'normal')
    doc.setFontSize(11)
    doc.setTextColor(60, 60, 60)
    doc.text(`Phone: ${String(t.phone || '').trim() || '—'}`, margin + 16, y + 88)
    doc.text(`Email: ${String(t.email || '').trim() || '—'}`, margin + 16, y + 108)

    // Footer line
    doc.setDrawColor(235, 235, 235)
    doc.line(margin + 16, y + 120, W - margin - 16, y + 120)

    doc.setFontSize(10)
    doc.setTextColor(90, 90, 90)
    doc.text('Please bring this ticket (digital or printed) to the venue.', margin + 16, y + 136)

    y += cardH + cardGap
  })

  const pdfArrayBuffer = doc.output('arraybuffer')
  return new Blob([pdfArrayBuffer], { type: 'application/pdf' })
}

function downloadTicketsPdf() {
  if (!pdfBlobForDownload.value) return
  const url = URL.createObjectURL(pdfBlobForDownload.value)
  const a = document.createElement('a')
  a.href = url
  a.download = pdfFileNameForDownload.value || 'tickets.pdf'
  document.body.appendChild(a)
  a.click()
  a.remove()
  URL.revokeObjectURL(url)
}
// Submit to CF7 (with PDF upload)
async function submitReservation() {
  submitError.value = ''
  submitSuccess.value = false

  if (!validateAll()) {
    submitError.value = 'Please fix the highlighted fields.'
    return
  }

  isSubmitting.value = true
  try {
    // Build CF7 payload
    const fd = new FormData()

    // ONE field containing all ticket data (CFDB7 friendly)
    const summary = buildTicketsSummary()
    fd.append(CF7_FIELD_TICKETS, summary)
    fd.append(CF7_FIELD_COUNT, String(tickets.value.length))
    fd.append('_wpcf7_unit_tag', 'rte')

    // Attach PDF (and keep it for download)
    const pdfBlob = generateTicketsPdfBlob()
    const filename = `mymonty-tickets-${Date.now()}.pdf`

    pdfBlobForDownload.value = pdfBlob
    pdfFileNameForDownload.value = filename

    fd.append(CF7_FILE_FIELD, new File([pdfBlob], filename, { type: 'application/pdf' }))   

    // (Optional) Also add a top-level email/name if your CF7 requires it:
    // If your form has "your-email" required, you can map Ticket 1 email to it:
    // fd.append('your-name', tickets.value[0].fullName)
    // fd.append('your-email', tickets.value[0].email)
    // fd.append('your-phone', tickets.value[0].phone)
    const attendeeEmails = tickets.value.map(t => String(t.email || '').trim()).join(', ')
    fd.append('attendee_emails', attendeeEmails)
    const url = `${CF7_BASE_URL}/wp-json/contact-form-7/v1/contact-forms/${CF7_FORM_ID}/feedback`
    const res = await fetch(url, { method: 'POST', body: fd })

    const data = await res.json().catch(() => ({}))

    // CF7 typically returns {status: "mail_sent" | "validation_failed" | ...}
    if (!res.ok) {
      throw new Error(data?.message || 'Request failed.')
    }
    if (data?.status && data.status !== 'mail_sent') {
      // CF7 validation_failed may include invalid_fields
      const msg = data?.message || 'Could not submit. Please try again.'
      throw new Error(msg)
    }

    submitSuccess.value = true

    // Reset fields (optional)
    tickets.value = [{ fullName: '', phone: '', email: '' }]
    errors.value = [{}]

    // Close after a short moment (optional), or keep open
    // closeModal()
  } catch (err) {
    submitError.value = err?.message || 'Something went wrong. Please try again.'
  } finally {
    isSubmitting.value = false
  }
}
</script>

<style scoped>
/* Abstract “pixel” panel without an image asset */
.pixel-hero{
  background:
    radial-gradient(60% 60% at 65% 40%, rgba(0,0,0,0.55) 0%, rgba(0,0,0,0) 55%),
    radial-gradient(70% 70% at 30% 75%, rgba(255,255,255,0.18) 0%, rgba(255,255,255,0) 60%),
    linear-gradient(120deg, #ff3b1a 0%, #ff5a1f 35%, #ff2a17 100%);
  position: relative;
  overflow: hidden;
}
.pixel-hero::before{
  content:"";
  position:absolute;
  inset:0;
  background-image:
    linear-gradient(rgba(0,0,0,0.08) 1px, transparent 1px),
    linear-gradient(90deg, rgba(0,0,0,0.08) 1px, transparent 1px);
  background-size: 6px 6px;
  opacity: .8;
  mix-blend-mode: multiply;
}
.pixel-hero::after{
  content:"";
  position:absolute;
  inset:-20%;
  background:
    radial-gradient(closest-side, rgba(0,0,0,0.25), rgba(0,0,0,0) 70%),
    repeating-linear-gradient(
      0deg,
      rgba(0,0,0,0.06) 0px,
      rgba(0,0,0,0.06) 2px,
      rgba(0,0,0,0) 6px,
      rgba(0,0,0,0) 10px
    );
  filter: blur(1px);
  transform: translateX(6%) skewX(-2deg);
  opacity: .9;
  mix-blend-mode: overlay;
}

@keyframes softPulse {
  0% {
    box-shadow: 0 0 0 0 rgba(255, 74, 23, 0.6);
  }
  50% {
    box-shadow: 0 0 0 10px rgba(255, 74, 23, 0);
  }
  100% {
    box-shadow: 0 0 0 0 rgba(255, 74, 23, 0);
  }
}

.pulse-button {
  animation: softPulse 1.5s ease-in-out infinite;
}
</style>