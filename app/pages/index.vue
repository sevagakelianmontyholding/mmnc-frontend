<!-- pages/index.vue  (NO TypeScript) -->
<template>
  <main class="min-h-screen bg-neutral-100 p-4 sm:p-8">
    <div class="mx-auto w-full max-w-6xl">
      <section class="bg-white border border-neutral-300">
        <!-- RESPONSIVE GRID (works on mobile + desktop) -->
        <div class="grid grid-cols-1 md:grid-cols-12">
          <!-- Top info bar -->
          <div class="col-span-1 md:col-span-4 border-b border-neutral-300 md:border-r border-neutral-300 px-6 py-5">
            <div class="inline-flex items-center rounded-full border border-neutral-300 px-3 py-1 text-[11px] font-semibold tracking-wide">
              <span class="mr-2 inline-block h-2 w-2 rounded-full bg-[#ff4a17]" />
              EVENT DETAILS
            </div>

            <div class="mt-4 space-y-1 text-[11px] font-semibold tracking-[0.02em] text-neutral-900">
              <p class="uppercase">THE MONTY CLUB, GEFINOR CENTER</p>
              <p class="uppercase">(BLOCK E, 6TH FLOOR, HAMRA)</p>
            </div>
          </div>

          <div class="flex flex-col justify-end col-span-1 md:col-span-3 border-b border-neutral-300 md:border-r border-neutral-300 px-6 py-5">
            <div class="text-[11px] font-semibold uppercase tracking-[0.02em] text-neutral-900">
              <p>THURSDAY, 12 FEBRUARY 2026</p>
              <p class="mt-1">5:00 PM – 8:00 PM</p>
            </div>
          </div>

          <div class="flex flex-col justify-end col-span-1 md:col-span-2 border-b border-neutral-300 md:border-r border-neutral-300 px-6 py-5">
            <div class="text-[11px] font-semibold uppercase tracking-[0.02em] text-neutral-900">
              <p>FREE PARKING</p>
              <p class="mt-1">AVAILABLE ON LEVEL -1</p>
            </div>
          </div>

          <!-- Reserve -->
          <div class="flex-col justify-center col-span-1 md:col-span-3 border-b border-neutral-300 px-6 py-5 flex items-start md:justify-end">
            <button
                type="button"
                @click="openModal"
                class="pulse-button h-12 w-full md:max-w-[240px] rounded-xl bg-[#ff4a17] text-white font-semibold text-sm shadow-sm hover:brightness-95 active:brightness-90 transition"
                >
                Reserve Seat
            </button>
          </div>

          <!-- Title block -->
          <div class="col-span-1 md:col-span-12 border-b border-neutral-300 px-6 md:px-8 py-8 md:py-10">
            <div class="flex items-end justify-between gap-6">
              <h1 class="leading-[0.92] tracking-tight text-neutral-950">
                <span class="block text-5xl sm:text-6xl md:text-7xl font-black">MYMONTY</span>
                <span class="block text-5xl sm:text-6xl md:text-7xl font-black">NETWORK CIRCLE</span>
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

          <div class="col-span-1 md:col-span-3 border-b border-neutral-300 md:border-r border-neutral-300 px-6 py-6">
            <div class="flex items-center justify-between gap-4">
              <p class="text-sm font-black uppercase tracking-tight text-neutral-950">THE MONTY CLUB</p>
              <span class="inline-flex items-center justify-center">
                <svg width="22" height="22" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                  <path d="M12 22s7-4.5 7-11a7 7 0 1 0-14 0c0 6.5 7 11 7 11Z" fill="#ff4a17" />
                  <circle cx="12" cy="11" r="2.2" fill="white" />
                </svg>
              </span>
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
                  <span>5:00-8:00</span>
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
                    <div class="underline underline-offset-4 decoration-neutral-950/30">Parking available</div>
                    <div class="underline underline-offset-4 decoration-neutral-950/30">on level -1</div>
                  </div>
                  <span class="text-xl font-black">→</span>
                </div>
              </div>
            </div>
          </div>

          <!-- Bottom copy -->
          <div class="col-span-1 md:col-span-8 md:border-r border-neutral-300 px-6 py-6">
            <p class="text-[10px] md:text-[9px] leading-4 font-semibold uppercase tracking-[0.04em] text-neutral-700">
              Connections & conversations is designed for professionals who value quality engagement. Through carefully curated
              discussions and relaxed networking moments, C-level executives will explore ideas, share experiences, and build
              relationships that extend beyond the evening.
            </p>

            <p class="mt-3 text-[10px] md:text-[9px] leading-4 font-black uppercase tracking-[0.04em] text-neutral-950">
              Seats are limited for this gathering, secure your place today.
            </p>
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
                Thu, 12 Feb 2026 • 5:00–8:00 PM • The Monty Club
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
                        @click="downloadTicketsPdf"
                        class="h-11 rounded-xl border border-neutral-200 bg-white px-5 text-sm font-semibold text-neutral-950
                            hover:bg-neutral-50"
                    >
                        Download Tickets PDF
                    </button>

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
  const subtitle = 'Thu, 12 Feb 2026 • 5:00–8:00 PM • The Monty Club (Gefinor Center, Hamra)'
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