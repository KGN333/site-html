<!-- Header -->
<header class="bg-blue-600 p-8 text-center relative overflow-hidden" role="banner">
  <!-- Decorative blobs: marked aria-hidden -->
  <div class="absolute top-0 left-0 w-24 h-24 bg-blue-500 rounded-full mix-blend-multiply filter blur-xl opacity-70 animate-blob" aria-hidden="true"></div>
  <div class="absolute top-0 right-0 w-24 h-24 bg-teal-400 rounded-full mix-blend-multiply filter blur-xl opacity-70 animate-blob animation-delay-2000" aria-hidden="true"></div>

  <div class="relative z-10">
    <!-- Decorative icon: aria-hidden -->
    <div class="mx-auto bg-white/20 w-16 h-16 rounded-full flex items-center justify-center mb-4 backdrop-blur-sm border border-white/30" aria-hidden="true">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" focusable="false" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"/>
      </svg>
    </div>

    <h1 id="card-title" class="text-3xl font-bold text-white tracking-wide uppercase">Fernanda</h1>
    <p class="text-xl font-light text-blue-100 tracking-widest uppercase">Diárias</p>
  </div>
</header>

<!-- Main content -->
<main id="main-content" class="p-6 bg-pattern" role="main" aria-labelledby="services-title">
  <p id="services-title" class="text-center text-gray-500 text-sm mb-6 uppercase tracking-wider font-semibold">Tabela de Serviços</p>

  <!-- Semantic list of services -->
  <ul class="space-y-4" aria-label="Lista de serviços e preços">
    <!-- Item 1 -->
    <li class="flex items-center justify-between p-4 bg-white rounded-xl border-l-4 border-blue-400 shadow-sm hover:shadow-md transition-shadow" >
      <div class="flex items-center gap-3">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-400" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true" focusable="false">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
        </svg>
        <span class="font-semibold text-gray-700">3 Horas</span>
      </div>
      <span class="text-xl font-bold price">R$ 60,00</span>
    </li>

    <!-- Item 2 -->
    <li class="flex items-center justify-between p-4 bg-white rounded-xl border-l-4 border-blue-500 shadow-sm hover:shadow-md transition-shadow" >
      <div class="flex items-center gap-3">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-500" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true" focusable="false">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
        </svg>
        <span class="font-semibold text-gray-700">6 Horas</span>
      </div>
      <span class="text-xl font-bold price">R$ 100,00</span>
    </li>

    <!-- Item 3 - destaque -->
    <li class="flex items-center justify-between p-4 bg-white rounded-xl border-l-4 border-blue-600 shadow-sm hover:shadow-md transition-shadow transform scale-105 ring-2 ring-blue-100" aria-current="true">
      <div class="flex items-center gap-3">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true" focusable="false">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
        </svg>
        <span class="font-semibold text-gray-800">8 Horas</span>
        <span class="bg-green-100 text-green-700 text-xs px-2 py-1 rounded-full font-bold">Mais pedido</span>
      </div>
      <span class="text-xl font-bold price-strong">R$ 130,00</span>
    </li>
  </ul>
</main>

<!-- Footer / Contact area -->
<footer class="bg-gray-50 p-6 border-t border-gray-100" role="contentinfo">
  <div class="flex flex-col sm:flex-row items-center gap-3">
    <!-- WhatsApp CTA: accessible name and safe external linking -->
    <a
      id="whatsapp-link"
      class="bg-green-500 hover:bg-green-600 transition-colors text-white py-3 px-4 rounded-xl flex items-center justify-center gap-3 shadow-lg shadow-green-200 group focus-ring"
      href="https://wa.me/5545998232577"
      target="_blank"
      rel="noopener noreferrer"
      title="Abrir chat do WhatsApp com Fernanda Diárias"
      aria-label="Abrir chat do WhatsApp com Fernanda Diárias (45) 99823-2577"
    >
      <!-- WhatsApp SVG marked decorative (aria-hidden) -->
      <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" focusable="false">
        <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.008-.57-.008-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413Z"/>
      </svg>

      <span class="text-xl font-bold tracking-wide group-hover:tracking-wider transition-all">(45) 99823-2577</span>
    </a>

    <!-- Copy number button (accessible) -->
    <button
      id="copy-number"
      class="py-3 px-4 rounded-xl bg-white border border-gray-200 text-gray-700 hover:bg-gray-50 focus-ring"
      type="button"
      aria-label="Copiar número para área de transferência"
    >
      Copiar número
    </button>

    <!-- Optional QR (visual) - aria-hidden -->
    <div class="sr-only sm:not-sr-only no-print" aria-hidden="true">
      <!-- Small inline QR using Google Chart API (visual only) -->
      <img alt="" src="https://chart.googleapis.com/chart?chs=120x120&cht=qr&chl=https%3A%2F%2Fwa.me%2F5545998232577&choe=UTF-8" width="56" height="56" class="rounded-md border border-gray-100" />
    </div>
  </div>

  <p class="text-center text-xs text-gray-400 mt-3">Clique no botão para agendar pelo WhatsApp</p>

  <!-- Live region for copy feedback (screen reader + visual) -->
  <div id="copy-status" class="sr-only" role="status" aria-live="polite"></div>
</footer>
