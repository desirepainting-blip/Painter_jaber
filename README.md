```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Painter Jaber | Desire Painting - Chhatrapati Sambhajinagar</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            royal: {
              DEFAULT: '#1e3a8a',
              dark: '#172554',
              light: '#2563eb'
            },
            slateDark: '#0f172a',
            amberAccent: '#f59e0b'
          }
        }
      }
    }
  </script>
  <style>
    /* Custom subtle animations and scrollbar styling */
    body {
      font-family: 'Inter', sans-serif;
    }
    .hero-pattern {
      background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 60%, #172554 100%);
    }
    .card-hover {
      transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
    }
    .card-hover:hover {
      transform: translateY(-5px);
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-900 antialiased selection:bg-amber-500 selection:text-white">

  <!-- Sticky Top Navigation Bar -->
  <nav class="sticky top-0 z-40 bg-slateDark/95 backdrop-blur-md border-b border-slate-800 text-white">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-3 flex items-center justify-between">
      <a href="#" class="flex items-center gap-2.5 group">
        <div class="w-10 h-10 rounded-xl bg-amberAccent flex items-center justify-center text-slateDark font-extrabold text-xl shadow-md group-hover:scale-105 transition">
          PJ
        </div>
        <div>
          <span class="font-bold text-lg tracking-tight block leading-none">Painter Jaber</span>
          <span class="text-xs text-amber-400 font-medium">Desire Painting • Sambhajinagar</span>
        </div>
      </a>

      <!-- Desktop Navigation Links -->
      <div class="hidden md:flex items-center gap-6 text-sm font-medium text-slate-200">
        <a href="#services" class="hover:text-amber-400 transition">Specializations</a>
        <a href="#gallery" class="hover:text-amber-400 transition">Work Gallery</a>
        <a href="#rates" class="hover:text-amber-400 transition">Rate Card</a>
        <a href="#calculator" class="hover:text-amber-400 transition">Cost Calculator</a>
        <a href="#reviews" class="hover:text-amber-400 transition">Reviews</a>
        <a href="#contact" class="hover:text-amber-400 transition">Contact</a>
      </div>

      <!-- Quick Call Button -->
      <div class="flex items-center gap-2">
        <a href="tel:9028886620" class="inline-flex items-center gap-1.5 bg-emerald-600 hover:bg-emerald-500 text-white text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-xl shadow transition">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
          </svg>
          <span>9028886620</span>
        </a>
      </div>
    </div>
  </nav>

  <!-- 1. Hero Header Section -->
  <header class="hero-pattern text-white relative overflow-hidden">
    <!-- Decorative background glow -->
    <div class="absolute -top-24 -right-24 w-96 h-96 bg-amber-500/15 rounded-full blur-3xl pointer-events-none"></div>
    <div class="absolute -bottom-24 -left-24 w-96 h-96 bg-blue-500/20 rounded-full blur-3xl pointer-events-none"></div>

    <div class="max-w-5xl mx-auto px-4 sm:px-6 py-16 sm:py-24 text-center relative z-10">
      <div class="inline-flex items-center gap-2 bg-white/10 border border-white/15 px-4 py-1.5 rounded-full text-xs sm:text-sm font-medium text-amber-300 mb-6">
        <span>📍 Chhatrapati Sambhajinagar (Aurangabad)</span>
        <span>•</span>
        <span>Trusted Painting Contractor</span>
      </div>

      <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight mb-4">
        Painter Jaber
      </h1>

      <p class="text-base sm:text-xl text-slate-200 max-w-3xl mx-auto font-medium leading-relaxed mb-8">
        Interior &amp; Exterior Paints • All Types Furniture &amp; Polishing Work • Spray Painting &amp; Waterproofing
      </p>

      <!-- CTA Buttons -->
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
        <a href="tel:9028886620" class="w-full sm:w-auto inline-flex items-center justify-center gap-2.5 bg-emerald-500 hover:bg-emerald-600 text-white font-bold px-7 py-4 rounded-xl shadow-lg shadow-emerald-950/30 transition transform hover:-translate-y-0.5 text-base">
          <span>📞 Call Now: 9028886620</span>
        </a>
        <a href="https://wa.me/919028886620?text=Hello%20Painter%20Jaber,%20mujhe%20painting%20work%20ke%20liye%20estimate%20chahiye." target="_blank" rel="noopener noreferrer" class="w-full sm:w-auto inline-flex items-center justify-center gap-2.5 bg-amberAccent hover:bg-amber-600 text-slateDark font-extrabold px-7 py-4 rounded-xl shadow-lg shadow-amber-950/30 transition transform hover:-translate-y-0.5 text-base">
          <span>💬 WhatsApp for Estimate</span>
        </a>
      </div>

      <!-- Quick Highlights Bar -->
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-6 max-w-3xl mx-auto mt-12 pt-8 border-t border-white/10 text-center">
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">100%</p>
          <p class="text-xs sm:text-sm text-slate-300">Genuine Material</p>
        </div>
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">4.9 ★</p>
          <p class="text-xs sm:text-sm text-slate-300">Customer Rating</p>
        </div>
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">On-Time</p>
          <p class="text-xs sm:text-sm text-slate-300">Project Delivery</p>
        </div>
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">Free</p>
          <p class="text-xs sm:text-sm text-slate-300">Site Visit &amp; Quote</p>
        </div>
      </div>
    </div>
  </header>

  <main class="max-w-6xl mx-auto px-4 sm:px-6 py-12 sm:py-16 space-y-20">

    <!-- 2. Our Specializations Section (4 Cards) -->
    <section id="services" class="scroll-mt-20">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-royal bg-blue-100 px-3 py-1 rounded-full">What We Do</span>
        <h2 class="text-2xl sm:text-3xl font-extrabold text-slateDark mt-2">Our Specializations</h2>
        <div class="w-16 h-1 bg-amberAccent mx-auto mt-3 rounded-full"></div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-royal card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-blue-50 text-royal flex items-center justify-center text-2xl mb-4">
              🎨
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Interior &amp; Exterior Painting</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Royale Plastic, Water Luster, Oil Paint, Plastic Emulsion, ACE, Apex, Ultima with smooth full-putty work.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-royal">
            ✓ Smooth Putty &amp; Primer Finish
          </div>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-amberAccent card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center text-2xl mb-4">
              ✨
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Wood Polishing &amp; PU Finish</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Melamyne and PU polish Matt &amp; Glossy finishes for main doors, furniture, wooden panels.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-amber-700">
            ✓ Mirror Gloss &amp; Premium Matt
          </div>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-royal card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-blue-50 text-royal flex items-center justify-center text-2xl mb-4">
              🛡️
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Waterproofing &amp; Damp Proof</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Wall protection, crack filling, terrace &amp; ceiling dampness treatment.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-royal">
            ✓ Long-Lasting Leakage Protection
          </div>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-amberAccent card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center text-2xl mb-4">
              ⚡
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Spray Painting &amp; Textures</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Duco, spray painting for metal gates, furniture, designer accent walls, commercial stores, and hotels.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-amber-700">
            ✓ Factory-Grade Spray Finish
          </div>
        </div>
      </div>
    </section>

    <!-- 3. Our Work Gallery Section (Grid of 6 items) -->
    <section id="gallery" class="scroll-mt-20">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-royal bg-blue-100 px-3 py-1 rounded-full">Portfolio</span>
        <h2 class="text-2xl sm:text-3xl font-extrabold text-slateDark mt-2">Our Work Gallery</h2>
        <div class="w-16 h-1 bg-amberAccent mx-auto mt-3 rounded-full"></div>
        <p class="text-sm text-slate-600 mt-3">Click on any photo to view a larger preview of our finishing quality.</p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Gallery Item 1 -->
        <div onclick="openGalleryModal('Luxury Interior Royal Finish', 'Full Putty & Smooth Plastic Emulsion', 'https://images.unsplash.com/photo-1589939705384-5185137a7f0f?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1589939705384-5185137a7f0f?auto=format&fit=crop&w=600&q=80"
                 alt="Luxury Interior Royal Finish"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Luxury+Interior+Finish';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Interior</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Luxury Interior Royal Finish</h3>
            <p class="text-xs text-slate-500 mt-1">Full Putty &amp; Smooth Plastic Emulsion</p>
          </div>
        </div>

        <!-- Gallery Item 2 -->
        <div onclick="openGalleryModal('Modern Living Room Makeover', 'Premium Color Consultation & Finish', 'https://images.unsplash.com/photo-1562259949-e8e7689d7828?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1562259949-e8e7689d7828?auto=format&fit=crop&w=600&q=80"
                 alt="Modern Living Room Makeover"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Living+Room+Makeover';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Makeover</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Modern Living Room Makeover</h3>
            <p class="text-xs text-slate-500 mt-1">Premium Color Consultation &amp; Finish</p>
          </div>
        </div>

        <!-- Gallery Item 3 -->
        <div onclick="openGalleryModal('PU & Melamyne Wood Polish', 'High-Gloss & Matt Finish for Doors', 'https://images.unsplash.com/photo-1615529182904-14819c35db37?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1615529182904-14819c35db37?auto=format&fit=crop&w=600&q=80"
                 alt="PU & Melamyne Wood Polish"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/f59e0b/0f172a?text=PU+Wood+Polish';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-amberAccent text-slateDark font-semibold text-xs px-2.5 py-1 rounded-lg">Wood Polish</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">PU &amp; Melamyne Wood Polish</h3>
            <p class="text-xs text-slate-500 mt-1">High-Gloss &amp; Matt Finish for Doors</p>
          </div>
        </div>

        <!-- Gallery Item 4 -->
        <div onclick="openGalleryModal('Exterior Weatherproof Painting', 'Apex, Ultima & Damp Proof Coating', 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=600&q=80"
                 alt="Exterior Weatherproof Painting"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Exterior+Painting';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Exterior</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Exterior Weatherproof Painting</h3>
            <p class="text-xs text-slate-500 mt-1">Apex, Ultima &amp; Damp Proof Coating</p>
          </div>
        </div>

        <!-- Gallery Item 5 -->
        <div onclick="openGalleryModal('Designer Feature Walls', 'Water Luster & Custom Wall Finishes', 'https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=600&q=80"
                 alt="Designer Feature Walls"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/f59e0b/0f172a?text=Designer+Feature+Wall';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-amberAccent text-slateDark font-semibold text-xs px-2.5 py-1 rounded-lg">Textures</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Designer Feature Walls</h3>
            <p class="text-xs text-slate-500 mt-1">Water Luster &amp; Custom Wall Finishes</p>
          </div>
        </div>

        <!-- Gallery Item 6 -->
        <div onclick="openGalleryModal('Detailed Surface Preparation', 'Crack Filling, Putty & Primer Work', 'https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&w=600&q=80"
                 alt="Detailed Surface Preparation"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Putty+and+Primer+Work';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Prep Work</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Detailed Surface Preparation</h3>
            <p class="text-xs text-slate-500 mt-1">Crack Filling, Putty &amp; Primer Work</p>
          </div>
        </div>
      </div>
    </section>

    <!-- 4. Standard Rate Card Table & Interactive Quick Estimate Calculator -->
    <section id="rates" class="scroll-mt-20">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-royal bg-blue-100 px-3 py-1 rounded-full">Transparent Pricing</span>
        <h2 class="text-2xl sm:text-3xl font-extrabold text-slateDark mt-2">Standard Rate Card (Per Brass)</h2>
        <div class="w-16 h-1 bg-amberAccent mx-auto mt-3 rounded-full"></div>
        <p class="text-sm text-slate-600 mt-3">Click any row below to load that service directly into our Quick Estimate Calculator.</p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
        <!-- Rate Card Table (7 columns on large screens) -->
        <div class="lg:col-span-7 bg-white rounded-2xl shadow-md overflow-hidden border border-slate-200">
          <div class="bg-royal text-white px-6 py-4 flex items-center justify-between">
            <h3 class="font-bold text-base sm:text-lg">Official Quotation Rate Chart</h3>
            <span class="text-xs bg-white/15 px-2.5 py-1 rounded-full">1 Brass = 100 Sq. Ft.</span>
          </div>
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse">
              <thead>
                <tr class="bg-slate-100 text-slate-700 text-xs sm:text-sm uppercase font-bold border-b border-slate-200">
                  <th class="py-3.5 px-4 sm:px-6">Service / Item</th>
                  <th class="py-3.5 px-3 sm:px-4 text-right">L```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Painter Jaber | Desire Painting - Chhatrapati Sambhajinagar</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            royal: {
              DEFAULT: '#1e3a8a',
              dark: '#172554',
              light: '#2563eb'
            },
            slateDark: '#0f172a',
            amberAccent: '#f59e0b'
          }
        }
      }
    }
  </script>
  <style>
    /* Custom subtle animations and scrollbar styling */
    body {
      font-family: 'Inter', sans-serif;
    }
    .hero-pattern {
      background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 60%, #172554 100%);
    }
    .card-hover {
      transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
    }
    .card-hover:hover {
      transform: translateY(-5px);
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-900 antialiased selection:bg-amber-500 selection:text-white">

  <!-- Sticky Top Navigation Bar -->
  <nav class="sticky top-0 z-40 bg-slateDark/95 backdrop-blur-md border-b border-slate-800 text-white">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-3 flex items-center justify-between">
      <a href="#" class="flex items-center gap-2.5 group">
        <div class="w-10 h-10 rounded-xl bg-amberAccent flex items-center justify-center text-slateDark font-extrabold text-xl shadow-md group-hover:scale-105 transition">
          PJ
        </div>
        <div>
          <span class="font-bold text-lg tracking-tight block leading-none">Painter Jaber</span>
          <span class="text-xs text-amber-400 font-medium">Desire Painting • Sambhajinagar</span>
        </div>
      </a>

      <!-- Desktop Navigation Links -->
      <div class="hidden md:flex items-center gap-6 text-sm font-medium text-slate-200">
        <a href="#services" class="hover:text-amber-400 transition">Specializations</a>
        <a href="#gallery" class="hover:text-amber-400 transition">Work Gallery</a>
        <a href="#rates" class="hover:text-amber-400 transition">Rate Card</a>
        <a href="#calculator" class="hover:text-amber-400 transition">Cost Calculator</a>
        <a href="#reviews" class="hover:text-amber-400 transition">Reviews</a>
        <a href="#contact" class="hover:text-amber-400 transition">Contact</a>
      </div>

      <!-- Quick Call Button -->
      <div class="flex items-center gap-2">
        <a href="tel:9028886620" class="inline-flex items-center gap-1.5 bg-emerald-600 hover:bg-emerald-500 text-white text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-xl shadow transition">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
          </svg>
          <span>9028886620</span>
        </a>
      </div>
    </div>
  </nav>

  <!-- 1. Hero Header Section -->
  <header class="hero-pattern text-white relative overflow-hidden">
    <!-- Decorative background glow -->
    <div class="absolute -top-24 -right-24 w-96 h-96 bg-amber-500/15 rounded-full blur-3xl pointer-events-none"></div>
    <div class="absolute -bottom-24 -left-24 w-96 h-96 bg-blue-500/20 rounded-full blur-3xl pointer-events-none"></div>

    <div class="max-w-5xl mx-auto px-4 sm:px-6 py-16 sm:py-24 text-center relative z-10">
      <div class="inline-flex items-center gap-2 bg-white/10 border border-white/15 px-4 py-1.5 rounded-full text-xs sm:text-sm font-medium text-amber-300 mb-6">
        <span>📍 Chhatrapati Sambhajinagar (Aurangabad)</span>
        <span>•</span>
        <span>Trusted Painting Contractor</span>
      </div>

      <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight mb-4">
        Painter Jaber
      </h1>

      <p class="text-base sm:text-xl text-slate-200 max-w-3xl mx-auto font-medium leading-relaxed mb-8">
        Interior &amp; Exterior Paints • All Types Furniture &amp; Polishing Work • Spray Painting &amp; Waterproofing
      </p>

      <!-- CTA Buttons -->
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
        <a href="tel:9028886620" class="w-full sm:w-auto inline-flex items-center justify-center gap-2.5 bg-emerald-500 hover:bg-emerald-600 text-white font-bold px-7 py-4 rounded-xl shadow-lg shadow-emerald-950/30 transition transform hover:-translate-y-0.5 text-base">
          <span>📞 Call Now: 9028886620</span>
        </a>
        <a href="https://wa.me/919028886620?text=Hello%20Painter%20Jaber,%20mujhe%20painting%20work%20ke%20liye%20estimate%20chahiye." target="_blank" rel="noopener noreferrer" class="w-full sm:w-auto inline-flex items-center justify-center gap-2.5 bg-amberAccent hover:bg-amber-600 text-slateDark font-extrabold px-7 py-4 rounded-xl shadow-lg shadow-amber-950/30 transition transform hover:-translate-y-0.5 text-base">
          <span>💬 WhatsApp for Estimate</span>
        </a>
      </div>

      <!-- Quick Highlights Bar -->
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-6 max-w-3xl mx-auto mt-12 pt-8 border-t border-white/10 text-center">
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">100%</p>
          <p class="text-xs sm:text-sm text-slate-300">Genuine Material</p>
        </div>
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">4.9 ★</p>
          <p class="text-xs sm:text-sm text-slate-300">Customer Rating</p>
        </div>
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">On-Time</p>
          <p class="text-xs sm:text-sm text-slate-300">Project Delivery</p>
        </div>
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">Free</p>
          <p class="text-xs sm:text-sm text-slate-300">Site Visit &amp; Quote</p>
        </div>
      </div>
    </div>
  </header>

  <main class="max-w-6xl mx-auto px-4 sm:px-6 py-12 sm:py-16 space-y-20">

    <!-- 2. Our Specializations Section (4 Cards) -->
    <section id="services" class="scroll-mt-20">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-royal bg-blue-100 px-3 py-1 rounded-full">What We Do</span>
        <h2 class="text-2xl sm:text-3xl font-extrabold text-slateDark mt-2">Our Specializations</h2>
        <div class="w-16 h-1 bg-amberAccent mx-auto mt-3 rounded-full"></div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-royal card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-blue-50 text-royal flex items-center justify-center text-2xl mb-4">
              🎨
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Interior &amp; Exterior Painting</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Royale Plastic, Water Luster, Oil Paint, Plastic Emulsion, ACE, Apex, Ultima with smooth full-putty work.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-royal">
            ✓ Smooth Putty &amp; Primer Finish
          </div>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-amberAccent card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center text-2xl mb-4">
              ✨
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Wood Polishing &amp; PU Finish</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Melamyne and PU polish Matt &amp; Glossy finishes for main doors, furniture, wooden panels.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-amber-700">
            ✓ Mirror Gloss &amp; Premium Matt
          </div>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-royal card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-blue-50 text-royal flex items-center justify-center text-2xl mb-4">
              🛡️
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Waterproofing &amp; Damp Proof</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Wall protection, crack filling, terrace &amp; ceiling dampness treatment.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-royal">
            ✓ Long-Lasting Leakage Protection
          </div>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-amberAccent card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center text-2xl mb-4">
              ⚡
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Spray Painting &amp; Textures</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Duco, spray painting for metal gates, furniture, designer accent walls, commercial stores, and hotels.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-amber-700">
            ✓ Factory-Grade Spray Finish
          </div>
        </div>
      </div>
    </section>

    <!-- 3. Our Work Gallery Section (Grid of 6 items) -->
    <section id="gallery" class="scroll-mt-20">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-royal bg-blue-100 px-3 py-1 rounded-full">Portfolio</span>
        <h2 class="text-2xl sm:text-3xl font-extrabold text-slateDark mt-2">Our Work Gallery</h2>
        <div class="w-16 h-1 bg-amberAccent mx-auto mt-3 rounded-full"></div>
        <p class="text-sm text-slate-600 mt-3">Click on any photo to view a larger preview of our finishing quality.</p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Gallery Item 1 -->
        <div onclick="openGalleryModal('Luxury Interior Royal Finish', 'Full Putty & Smooth Plastic Emulsion', 'https://images.unsplash.com/photo-1589939705384-5185137a7f0f?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1589939705384-5185137a7f0f?auto=format&fit=crop&w=600&q=80"
                 alt="Luxury Interior Royal Finish"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Luxury+Interior+Finish';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Interior</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Luxury Interior Royal Finish</h3>
            <p class="text-xs text-slate-500 mt-1">Full Putty &amp; Smooth Plastic Emulsion</p>
          </div>
        </div>

        <!-- Gallery Item 2 -->
        <div onclick="openGalleryModal('Modern Living Room Makeover', 'Premium Color Consultation & Finish', 'https://images.unsplash.com/photo-1562259949-e8e7689d7828?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1562259949-e8e7689d7828?auto=format&fit=crop&w=600&q=80"
                 alt="Modern Living Room Makeover"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Living+Room+Makeover';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Makeover</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Modern Living Room Makeover</h3>
            <p class="text-xs text-slate-500 mt-1">Premium Color Consultation &amp; Finish</p>
          </div>
        </div>

        <!-- Gallery Item 3 -->
        <div onclick="openGalleryModal('PU & Melamyne Wood Polish', 'High-Gloss & Matt Finish for Doors', 'https://images.unsplash.com/photo-1615529182904-14819c35db37?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1615529182904-14819c35db37?auto=format&fit=crop&w=600&q=80"
                 alt="PU & Melamyne Wood Polish"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/f59e0b/0f172a?text=PU+Wood+Polish';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-amberAccent text-slateDark font-semibold text-xs px-2.5 py-1 rounded-lg">Wood Polish</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">PU &amp; Melamyne Wood Polish</h3>
            <p class="text-xs text-slate-500 mt-1">High-Gloss &amp; Matt Finish for Doors</p>
          </div>
        </div>

        <!-- Gallery Item 4 -->
        <div onclick="openGalleryModal('Exterior Weatherproof Painting', 'Apex, Ultima & Damp Proof Coating', 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=600&q=80"
                 alt="Exterior Weatherproof Painting"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Exterior+Painting';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Exterior</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Exterior Weatherproof Painting</h3>
            <p class="text-xs text-slate-500 mt-1">Apex, Ultima &amp; Damp Proof Coating</p>
          </div>
        </div>

        <!-- Gallery Item 5 -->
        <div onclick="openGalleryModal('Designer Feature Walls', 'Water Luster & Custom Wall Finishes', 'https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=600&q=80"
                 alt="Designer Feature Walls"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/f59e0b/0f172a?text=Designer+Feature+Wall';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-amberAccent text-slateDark font-semibold text-xs px-2.5 py-1 rounded-lg">Textures</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Designer Feature Walls</h3>
            <p class="text-xs text-slate-500 mt-1">Water Luster &amp; Custom Wall Finishes</p>
          </div>
        </div>

        <!-- Gallery Item 6 -->
        <div onclick="openGalleryModal('Detailed Surface Preparation', 'Crack Filling, Putty & Primer Work', 'https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&w=600&q=80"
                 alt="Detailed Surface Preparation"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Putty+and+Primer+Work';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Prep Work</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Detailed Surface Preparation</h3>
            <p class="text-xs text-slate-500 mt-1">Crack Filling, Putty &amp; Primer Work</p>
          </div>
        </div>
      </div>
    </section>

    <!-- 4. Standard Rate Card Table & Interactive Quick Estimate Calculator -->
    <section id="rates" class="scroll-mt-20">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-royal bg-blue-100 px-3 py-1 rounded-full">Transparent Pricing</span>
        <h2 class="text-2xl sm:text-3xl font-extrabold text-slateDark mt-2">Standard Rate Card (Per Brass)</h2>
        <div class="w-16 h-1 bg-amberAccent mx-auto mt-3 rounded-full"></div>
        <p class="text-sm text-slate-600 mt-3">Click any row below to load that service directly into our Quick Estimate Calculator.</p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
        <!-- Rate Card Table (7 columns on large screens) -->
        <div class="lg:col-span-7 bg-white rounded-2xl shadow-md overflow-hidden border border-slate-200">
          <div class="bg-royal text-white px-6 py-4 flex items-center justify-between">
            <h3 class="font-bold text-base sm:text-lg">Official Quotation Rate Chart</h3>
            <span class="text-xs bg-white/15 px-2.5 py-1 rounded-full">1 Brass = 100 Sq. Ft.</span>
          </div>
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse">
              <thead>
                <tr class="bg-slate-100 text-slate-700 text-xs sm:text-sm uppercase font-bold border-b border-slate-200">
                  <th class="py-3.5 px-4 sm:px-6">Service / Item</th>
                  <th class="py-3.5 px-3 sm:px-4 text-right">L```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Painter Jaber | Desire Painting - Chhatrapati Sambhajinagar</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            royal: {
              DEFAULT: '#1e3a8a',
              dark: '#172554',
              light: '#2563eb'
            },
            slateDark: '#0f172a',
            amberAccent: '#f59e0b'
          }
        }
      }
    }
  </script>
  <style>
    /* Custom subtle animations and scrollbar styling */
    body {
      font-family: 'Inter', sans-serif;
    }
    .hero-pattern {
      background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 60%, #172554 100%);
    }
    .card-hover {
      transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
    }
    .card-hover:hover {
      transform: translateY(-5px);
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-900 antialiased selection:bg-amber-500 selection:text-white">

  <!-- Sticky Top Navigation Bar -->
  <nav class="sticky top-0 z-40 bg-slateDark/95 backdrop-blur-md border-b border-slate-800 text-white">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-3 flex items-center justify-between">
      <a href="#" class="flex items-center gap-2.5 group">
        <div class="w-10 h-10 rounded-xl bg-amberAccent flex items-center justify-center text-slateDark font-extrabold text-xl shadow-md group-hover:scale-105 transition">
          PJ
        </div>
        <div>
          <span class="font-bold text-lg tracking-tight block leading-none">Painter Jaber</span>
          <span class="text-xs text-amber-400 font-medium">Desire Painting • Sambhajinagar</span>
        </div>
      </a>

      <!-- Desktop Navigation Links -->
      <div class="hidden md:flex items-center gap-6 text-sm font-medium text-slate-200">
        <a href="#services" class="hover:text-amber-400 transition">Specializations</a>
        <a href="#gallery" class="hover:text-amber-400 transition">Work Gallery</a>
        <a href="#rates" class="hover:text-amber-400 transition">Rate Card</a>
        <a href="#calculator" class="hover:text-amber-400 transition">Cost Calculator</a>
        <a href="#reviews" class="hover:text-amber-400 transition">Reviews</a>
        <a href="#contact" class="hover:text-amber-400 transition">Contact</a>
      </div>

      <!-- Quick Call Button -->
      <div class="flex items-center gap-2">
        <a href="tel:9028886620" class="inline-flex items-center gap-1.5 bg-emerald-600 hover:bg-emerald-500 text-white text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-xl shadow transition">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
          </svg>
          <span>9028886620</span>
        </a>
      </div>
    </div>
  </nav>

  <!-- 1. Hero Header Section -->
  <header class="hero-pattern text-white relative overflow-hidden">
    <!-- Decorative background glow -->
    <div class="absolute -top-24 -right-24 w-96 h-96 bg-amber-500/15 rounded-full blur-3xl pointer-events-none"></div>
    <div class="absolute -bottom-24 -left-24 w-96 h-96 bg-blue-500/20 rounded-full blur-3xl pointer-events-none"></div>

    <div class="max-w-5xl mx-auto px-4 sm:px-6 py-16 sm:py-24 text-center relative z-10">
      <div class="inline-flex items-center gap-2 bg-white/10 border border-white/15 px-4 py-1.5 rounded-full text-xs sm:text-sm font-medium text-amber-300 mb-6">
        <span>📍 Chhatrapati Sambhajinagar (Aurangabad)</span>
        <span>•</span>
        <span>Trusted Painting Contractor</span>
      </div>

      <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight mb-4">
        Painter Jaber
      </h1>

      <p class="text-base sm:text-xl text-slate-200 max-w-3xl mx-auto font-medium leading-relaxed mb-8">
        Interior &amp; Exterior Paints • All Types Furniture &amp; Polishing Work • Spray Painting &amp; Waterproofing
      </p>

      <!-- CTA Buttons -->
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
        <a href="tel:9028886620" class="w-full sm:w-auto inline-flex items-center justify-center gap-2.5 bg-emerald-500 hover:bg-emerald-600 text-white font-bold px-7 py-4 rounded-xl shadow-lg shadow-emerald-950/30 transition transform hover:-translate-y-0.5 text-base">
          <span>📞 Call Now: 9028886620</span>
        </a>
        <a href="https://wa.me/919028886620?text=Hello%20Painter%20Jaber,%20mujhe%20painting%20work%20ke%20liye%20estimate%20chahiye." target="_blank" rel="noopener noreferrer" class="w-full sm:w-auto inline-flex items-center justify-center gap-2.5 bg-amberAccent hover:bg-amber-600 text-slateDark font-extrabold px-7 py-4 rounded-xl shadow-lg shadow-amber-950/30 transition transform hover:-translate-y-0.5 text-base">
          <span>💬 WhatsApp for Estimate</span>
        </a>
      </div>

      <!-- Quick Highlights Bar -->
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-6 max-w-3xl mx-auto mt-12 pt-8 border-t border-white/10 text-center">
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">100%</p>
          <p class="text-xs sm:text-sm text-slate-300">Genuine Material</p>
        </div>
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">4.9 ★</p>
          <p class="text-xs sm:text-sm text-slate-300">Customer Rating</p>
        </div>
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">On-Time</p>
          <p class="text-xs sm:text-sm text-slate-300">Project Delivery</p>
        </div>
        <div>
          <p class="text-2xl sm:text-3xl font-extrabold text-amber-400">Free</p>
          <p class="text-xs sm:text-sm text-slate-300">Site Visit &amp; Quote</p>
        </div>
      </div>
    </div>
  </header>

  <main class="max-w-6xl mx-auto px-4 sm:px-6 py-12 sm:py-16 space-y-20">

    <!-- 2. Our Specializations Section (4 Cards) -->
    <section id="services" class="scroll-mt-20">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-royal bg-blue-100 px-3 py-1 rounded-full">What We Do</span>
        <h2 class="text-2xl sm:text-3xl font-extrabold text-slateDark mt-2">Our Specializations</h2>
        <div class="w-16 h-1 bg-amberAccent mx-auto mt-3 rounded-full"></div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-royal card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-blue-50 text-royal flex items-center justify-center text-2xl mb-4">
              🎨
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Interior &amp; Exterior Painting</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Royale Plastic, Water Luster, Oil Paint, Plastic Emulsion, ACE, Apex, Ultima with smooth full-putty work.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-royal">
            ✓ Smooth Putty &amp; Primer Finish
          </div>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-amberAccent card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center text-2xl mb-4">
              ✨
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Wood Polishing &amp; PU Finish</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Melamyne and PU polish Matt &amp; Glossy finishes for main doors, furniture, wooden panels.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-amber-700">
            ✓ Mirror Gloss &amp; Premium Matt
          </div>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-royal card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-blue-50 text-royal flex items-center justify-center text-2xl mb-4">
              🛡️
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Waterproofing &amp; Damp Proof</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Wall protection, crack filling, terrace &amp; ceiling dampness treatment.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-royal">
            ✓ Long-Lasting Leakage Protection
          </div>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-2xl p-6 shadow-md border-t-4 border-amberAccent card-hover flex flex-col justify-between">
          <div>
            <div class="w-12 h-12 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center text-2xl mb-4">
              ⚡
            </div>
            <h3 class="text-lg font-bold text-slateDark mb-2">Spray Painting &amp; Textures</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
              Duco, spray painting for metal gates, furniture, designer accent walls, commercial stores, and hotels.
            </p>
          </div>
          <div class="mt-4 pt-3 border-t border-slate-100 text-xs font-semibold text-amber-700">
            ✓ Factory-Grade Spray Finish
          </div>
        </div>
      </div>
    </section>

    <!-- 3. Our Work Gallery Section (Grid of 6 items) -->
    <section id="gallery" class="scroll-mt-20">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-royal bg-blue-100 px-3 py-1 rounded-full">Portfolio</span>
        <h2 class="text-2xl sm:text-3xl font-extrabold text-slateDark mt-2">Our Work Gallery</h2>
        <div class="w-16 h-1 bg-amberAccent mx-auto mt-3 rounded-full"></div>
        <p class="text-sm text-slate-600 mt-3">Click on any photo to view a larger preview of our finishing quality.</p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Gallery Item 1 -->
        <div onclick="openGalleryModal('Luxury Interior Royal Finish', 'Full Putty & Smooth Plastic Emulsion', 'https://images.unsplash.com/photo-1589939705384-5185137a7f0f?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1589939705384-5185137a7f0f?auto=format&fit=crop&w=600&q=80"
                 alt="Luxury Interior Royal Finish"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Luxury+Interior+Finish';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Interior</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Luxury Interior Royal Finish</h3>
            <p class="text-xs text-slate-500 mt-1">Full Putty &amp; Smooth Plastic Emulsion</p>
          </div>
        </div>

        <!-- Gallery Item 2 -->
        <div onclick="openGalleryModal('Modern Living Room Makeover', 'Premium Color Consultation & Finish', 'https://images.unsplash.com/photo-1562259949-e8e7689d7828?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1562259949-e8e7689d7828?auto=format&fit=crop&w=600&q=80"
                 alt="Modern Living Room Makeover"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Living+Room+Makeover';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Makeover</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Modern Living Room Makeover</h3>
            <p class="text-xs text-slate-500 mt-1">Premium Color Consultation &amp; Finish</p>
          </div>
        </div>

        <!-- Gallery Item 3 -->
        <div onclick="openGalleryModal('PU & Melamyne Wood Polish', 'High-Gloss & Matt Finish for Doors', 'https://images.unsplash.com/photo-1615529182904-14819c35db37?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1615529182904-14819c35db37?auto=format&fit=crop&w=600&q=80"
                 alt="PU & Melamyne Wood Polish"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/f59e0b/0f172a?text=PU+Wood+Polish';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-amberAccent text-slateDark font-semibold text-xs px-2.5 py-1 rounded-lg">Wood Polish</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">PU &amp; Melamyne Wood Polish</h3>
            <p class="text-xs text-slate-500 mt-1">High-Gloss &amp; Matt Finish for Doors</p>
          </div>
        </div>

        <!-- Gallery Item 4 -->
        <div onclick="openGalleryModal('Exterior Weatherproof Painting', 'Apex, Ultima & Damp Proof Coating', 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=600&q=80"
                 alt="Exterior Weatherproof Painting"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Exterior+Painting';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Exterior</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Exterior Weatherproof Painting</h3>
            <p class="text-xs text-slate-500 mt-1">Apex, Ultima &amp; Damp Proof Coating</p>
          </div>
        </div>

        <!-- Gallery Item 5 -->
        <div onclick="openGalleryModal('Designer Feature Walls', 'Water Luster & Custom Wall Finishes', 'https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=600&q=80"
                 alt="Designer Feature Walls"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/f59e0b/0f172a?text=Designer+Feature+Wall';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-amberAccent text-slateDark font-semibold text-xs px-2.5 py-1 rounded-lg">Textures</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Designer Feature Walls</h3>
            <p class="text-xs text-slate-500 mt-1">Water Luster &amp; Custom Wall Finishes</p>
          </div>
        </div>

        <!-- Gallery Item 6 -->
        <div onclick="openGalleryModal('Detailed Surface Preparation', 'Crack Filling, Putty & Primer Work', 'https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&w=900&q=80')" class="bg-white rounded-2xl overflow-hidden shadow-md card-hover cursor-pointer group">
          <div class="relative h-56 overflow-hidden bg-slate-200">
            <img src="https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&w=600&q=80"
                 alt="Detailed Surface Preparation"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Putty+and+Primer+Work';"
                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
            <span class="absolute top-3 right-3 bg-slateDark/75 text-white text-xs px-2.5 py-1 rounded-lg backdrop-blur-sm">Prep Work</span>
          </div>
          <div class="p-4 text-center">
            <h3 class="font-bold text-slateDark text-base">Detailed Surface Preparation</h3>
            <p class="text-xs text-slate-500 mt-1">Crack Filling, Putty &amp; Primer Work</p>
          </div>
        </div>
      </div>
    </section>

    <!-- 4. Standard Rate Card Table & Interactive Quick Estimate Calculator -->
    <section id="rates" class="scroll-mt-20">
      <div class="text-center max-w-2xl mx-auto mb-10">
        <span class="text-xs font-bold uppercase tracking-widest text-royal bg-blue-100 px-3 py-1 rounded-full">Transparent Pricing</span>
        <h2 class="text-2xl sm:text-3xl font-extrabold text-slateDark mt-2">Standard Rate Card (Per Brass)</h2>
        <div class="w-16 h-1 bg-amberAccent mx-auto mt-3 rounded-full"></div>
        <p class="text-sm text-slate-600 mt-3">Click any row below to load that service directly into our Quick Estimate Calculator.</p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
        <!-- Rate Card Table (7 columns on large screens) -->
        <div class="lg:col-span-7 bg-white rounded-2xl shadow-md overflow-hidden border border-slate-200">
          <div class="bg-royal text-white px-6 py-4 flex items-center justify-between">
            <h3 class="font-bold text-base sm:text-lg">Official Quotation Rate Chart</h3>
            <span class="text-xs bg-white/15 px-2.5 py-1 rounded-full">1 Brass = 100 Sq. Ft.</span>
          </div>
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse">
              <thead>
                <tr class="bg-slate-100 text-slate-700 text-xs sm:text-sm uppercase font-bold border-b border-slate-200">
                  <th class="py-3.5 px-4 sm:px-6">Service / Item</th>
                  <th class="py-3.5 px-3 sm:px-4 text-right">L
