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
                  <span class="pulse-dot mr-2 inline-block h-2 w-2 rounded-full bg-[#ff4a17]" />
                  EVENT DETAILS
                </div>
                <span class="block text-4xl sm:text-6xl md:text-7xl font-black">MYMONTY</span>
                <span class="block text-4xl sm:text-6xl md:text-7xl font-black">NETWORKING CIRCLE</span>
                <p class="mt-3 text-xl max-w-xl text-pretty text-neutral-800">
                  Join a curated circle of leaders and innovators for meaningful conversations and lasting connections.
                </p>
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
                  <span class="pulse-dot mr-2 inline-block h-2 w-2 rounded-full bg-[#ff4a17]" />
                  EVENT DETAILS
                </div>
                <span class="block text-5xl sm:text-6xl md:text-7xl font-black">MYMONTY</span>
                <span class="block text-5xl sm:text-6xl md:text-7xl font-black">NETWORKING CIRCLE</span>
                <p class="mt-3 text-xl max-w-xl text-pretty text-neutral-800">
                  Join a curated circle of leaders and innovators for meaningful conversations and lasting connections.
                </p>
              </h1>

              <div class="hidden sm:flex pb-2 md:pb-3 pr-0 md:pr-2 items-center gap-2 md:gap-3 text-neutral-950">
                <span class="text-2xl md:text-3xl font-black">→</span>
                <span class="text-2xl md:text-3xl font-black">→</span>
                <span class="text-2xl md:text-3xl font-black">→</span>
              </div>
            </div>
          </div>

          <!-- Mid strip (left) -->
          <div class="col-span-1 md:col-span-6 border-b border-neutral-300 md:border-r px-6 py-6">
            <p class="text-neutral-800 text-sm">
              The MyMonty Networking Circle is specifically designed for the financial sector in Lebanon. It’s a time to communicate and explore how ideas, relationships, and partnership can grow. Through carefully curated discussions and relaxed networking moments, C-level executives will explore ideas, share experiences, and build relationships that extend beyond the evening. Seats are limited for this gathering, so secure your place today!
            </p>
          </div>

          <div class="col-span-1 md:flex lg:flex-col md:justify-center md:col-span-2 border-b md:border-r border-neutral-300 max-xl:px-3 xl:px-6 py-6">
            <div class="flex items-center justify-between gap-4">
              <a class="flex items-center gap-1" href="https://shorturl.at/Kx0iq" target="_blank">
                <span class="inline-flex items-center justify-center -mt-px">
                  <svg width="22" height="22" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                    <path d="M12 22s7-4.5 7-11a7 7 0 1 0-14 0c0 6.5 7 11 7 11Z" fill="#ff4a17" />
                    <circle cx="12" cy="11" r="2.2" fill="white" />
                  </svg>
                </span>
                <div class="flex items-center gap-2">
                  <p class="text-sm font-black uppercase tracking-tight text-neutral-950 whitespace-nowrap underline underline-offset-3">MONTY CLUB</p>
                  <span class="text-xl font-black -mt-1">→</span>
                </div>
                
                
              </a>
            </div>
          </div>

          <!-- Pixel hero (RIGHT on desktop, STACKED on mobile) -->
          <div class="col-span-1 md:col-span-4 md:row-span-3 border-b border-neutral-300 px-0 py-0 min-h-[400px]">
            <div class="w-full relative h-full">
                <img src="/monty-club-2.webp" class="w-full h-full object-cover absolute top-0 left-0"/>
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
                  
                </div>
              </div>
            </div>
          </div>

          <!-- Bottom copy -->
          <div class="col-span-1 md:col-span-8 md:border-r border-neutral-300 px-6 py-6 flex max-md:flex-col gap-5 md:items-center justify-between">

            <p class="text-[10px] md:text-[9px] leading-4 font-black uppercase tracking-[0.04em] text-neutral-950">
              Seats are limited for this gathering, secure your place today.
            </p>
            <div>
              <img class="w-[150px]" src="/monty-finance-logo.webp" />
            </div>
          </div>
        </div>

        <!-- ✅ REMOVE your md:hidden mobile block completely -->
      </section>
    </div>

    <!-- MODAL -->
    <Teleport to="body">
      <div v-if="isOpen" class="fixed inset-0 z-[60] flex items-center justify-center p-4 overflow-hidden">
        <!-- Backdrop (outside click closes) -->
        <div class="absolute inset-0 bg-black/50" @click.self="closeModal"></div>

        <!-- Panel -->
        <div
          ref="panelRef"
          class="relative w-[min(92vw,48rem)] overflow-hidden rounded-2xl border border-neutral-200 bg-white shadow-2xl
                flex flex-col max-h-[92dvh] sm:max-h-[88vh] modal-panel"
          :class="flipPhase !== 'idle' ? 'is-flipping' : ''"
          :style="panelMinHeight ? { minHeight: panelMinHeight } : null"
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
          <form
            v-show="view === 'form'"
            class="px-6 py-6 overflow-y-auto modal-body"
            @submit.prevent="submitReservation"
          >
            
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
              <div class="flex flex-col sm:items-center sm:justify-between gap-3 border-t border-neutral-200 pt-5">
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
            </div>
          </form>
          <div v-show="view === 'success'" class="px-6 py-10 overflow-y-auto modal-body">
            <div class="mx-auto max-w-xl text-center">
              <div class="mx-auto flex h-14 w-14 items-center justify-center rounded-2xl bg-[#ff4a17]/10 text-[#ff4a17]">
                <svg width="28" height="28" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                  <path d="M20 6L9 17l-5-5" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round" />
                </svg>
              </div>

              <h3 class="mt-5 text-2xl font-black tracking-tight text-neutral-950">
                Registration Confirmed ✅
              </h3>

              <p class="mt-3 text-sm leading-6 text-neutral-700">
                We look forward to welcoming you for an exclusive evening with the
                <span class="font-semibold text-neutral-950">MyMonty Networking Circle</span>.
              </p>

              <p class="mt-4 text-sm leading-6 text-neutral-700">
                Your ticket is now ready and can be downloaded in PDF format below.
              </p>

              <div class="mt-5 rounded-2xl border border-neutral-200 bg-neutral-50 p-5 text-left">
                <p class="text-xs font-black uppercase tracking-[0.14em] text-neutral-500">
                  Need help?
                </p>

                <p class="mt-2 text-sm leading-6 text-neutral-700">
                  Should you have any questions or require further assistance, please feel free to contact
                  <span class="font-semibold text-neutral-950">Lina Osman</span> at
                  <a href="tel:+96171958090" class="font-semibold text-[#ff4a17] underline underline-offset-4 hover:brightness-95">
                    +961 71 958090
                  </a>
                  for local calls or at
                 <a
                  href="https://wa.me/447771242999"
                  target="_blank"
                  rel="noopener"
                  class="font-semibold text-[#ff4a17] underline underline-offset-4 hover:brightness-95"
                >
                  +44 7771242999
                </a>
                   for WhatsApp calls and messages.
                </p>
              </div>

              <p class="mt-5 text-sm font-semibold text-neutral-800">
                We look forward to hosting you.
              </p>

              <div class="mt-7 flex flex-col sm:flex-row items-center justify-center gap-3">
                <button
                  type="button"
                  @click="downloadTicketsPdf"
                  class="h-12 w-full sm:w-auto rounded-xl bg-[#ff4a17] px-6 text-white text-sm font-semibold shadow-sm
                        hover:brightness-95 active:brightness-90"
                >
                  Download Tickets PDF
                </button>

                <button
                  type="button"
                  @click="closeModal"
                  class="h-12 w-full sm:w-auto rounded-xl border border-neutral-200 bg-white px-6 text-sm font-semibold text-neutral-900
                        hover:bg-neutral-50"
                >
                  Close
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </Teleport>
  </main>
</template>

<script setup>

useSeoMeta({
  title: 'MyMonty Networking Circle',
  ogTitle: 'MyMonty Networking Circle',
  description: 'We are delighted to invite you to an exclusive evening of connection with the MyMonty Team. This invitation is only for the financial sector and is targeting C-level. It’s a casual gathering—just socializing and connection. If we missed any C-level , feel free to invite them or let us know so we can invite them directly. The event is next Thursday, June 12th, from 5 PM till 8 PM, held at the Monty Club. If you need any information, please contact Myrna Beaini at +961 71 778774 or myrna.beaini@montyholding.com',
  ogDescription: 'We are delighted to invite you to an exclusive evening of connection with the MyMonty Team. This invitation is only for the financial sector and is targeting C-level. It’s a casual gathering—just socializing and connection. If we missed any C-level , feel free to invite them or let us know so we can invite them directly. The event is next Thursday, June 12th, from 5 PM till 8 PM, held at the Monty Club. If you need any information, please contact Myrna Beaini at +961 71 778774 or myrna.beaini@montyholding.com',
  ogImage: 'https://mmnc.mymonty.com.lb/monty-club-preview.webp',
  twitterCard: 'summary_large_image',
})
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
const view = ref('form')        // 'form' | 'success'
const isFlipping = ref(false)   // triggers animation

const flipPhase = ref('idle')          // 'idle' | 'out' | 'in'
const panelRef = ref(null)
const panelMinHeight = ref('')

// Tickets (start with 1)
const tickets = ref([{ fullName: '', phone: '', email: '' }])
const errors = ref([{}])

function openModal() {
  view.value = 'form'
  isFlipping.value = false
  submitError.value = ''
  submitSuccess.value = false
  isOpen.value = true
  flipPhase.value = 'idle'
  panelMinHeight.value = ''
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

    isFlipping.value = true

    // Freeze height to avoid layout jump during animation
    panelMinHeight.value = panelRef.value ? `${panelRef.value.offsetHeight}px` : ''

    flipPhase.value = 'out'

    // Swap content exactly at mid-flip (when panel is edge-on)
    setTimeout(() => {
      view.value = 'success'
      flipPhase.value = 'in'
    }, 240) // half of animation duration

    // End flip + unfreeze height
    setTimeout(() => {
      flipPhase.value = 'idle'
      panelMinHeight.value = ''
    }, 480)

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

@keyframes dotPulse {
  0% {
    box-shadow: 0 0 0 0 rgba(255, 74, 23, 0.7);
    transform: scale(1);
  }
  50% {
    box-shadow: 0 0 0 6px rgba(255, 74, 23, 0);
    transform: scale(1.15);
  }
  100% {
    box-shadow: 0 0 0 0 rgba(255, 74, 23, 0);
    transform: scale(1);
  }
}

.pulse-dot {
  animation: dotPulse 1.8s ease-in-out infinite;
}
.modal-panel{
  transform-style: preserve-3d;
  backface-visibility: hidden;
  will-change: transform, opacity;
  max-width: 100%;
  overflow: hidden;
}

/* Prevent perspective from affecting layout */
.is-flipping{
  transform-origin: center center;
}

@keyframes flipOutInSmooth {
  0%   { transform: perspective(1000px) rotateY(0deg); opacity: 1; }
  50%  { transform: perspective(1000px) rotateY(88deg); opacity: .25; }
  50.01% { transform: perspective(1000px) rotateY(-88deg); opacity: .25; }
  100% { transform: perspective(1000px) rotateY(0deg); opacity: 1; }
}

.is-flipping{
  animation: flipOutInSmooth 480ms cubic-bezier(.2,.8,.2,1);
}
</style>