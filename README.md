<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Freelance Haiti — Plateforme #1 des freelances en Haïti</title>
  <meta name="description" content="Freelance Haiti connecte talents et entreprises : designers, développeurs, marketeurs, rédacteurs. Trouvez votre prochain prestataire ou mission aujourd'hui." />
  <link rel="canonical" href="https://freelancehaiti.example" />
  <meta property="og:title" content="Freelance Haiti" />
  <meta property="og:description" content="Connexion Talents & Entreprises. Boostez vos missions, visez l’international." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://freelancehaiti.example" />
  <meta property="og:image" content="/og-image.jpg" />
  <meta name="theme-color" content="#0ea5e9" />

  <!-- Tailwind CSS CDN (production build) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: { sans: ["Inter", "ui-sans-serif", "system-ui"] },
          colors: {
            brand: {
              50: '#eff6ff',
              100: '#dbeafe',
              200: '#bfdbfe',
              300: '#93c5fd',
              400: '#60a5fa',
              500: '#3b82f6', // Bleu principal
              600: '#2563eb',
              700: '#1d4ed8',
              800: '#1e40af',
              900: '#1e3a8a',
              metal: '#1f4e79' // Bleu métallique
            }
          },
          boxShadow: {
            glow: '0 10px 30px rgba(31, 78, 121, 0.25)'
          }
        }
      }
    };
  </script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

  <style>
    /* Subtile grain background */
    body { font-feature-settings: "ss01" on, "ss02" on; }
    .noise {
      background-image: radial-gradient(rgba(255,255,255,.05) 1px, transparent 1px);
      background-size: 4px 4px;
    }
  </style>
</head>
<body class="font-sans antialiased text-slate-800 bg-slate-50">
  <!-- Top Announcement Bar -->
  <div class="w-full bg-brand-800 text-white text-sm py-2"><div class="max-w-7xl mx-auto px-4 text-center">🚀 Plateforme #1 des freelances en Haïti — Ouvrez votre mission aujourd’hui.</div></div>

  <!-- Navigation -->
  <header class="sticky top-0 z-50 bg-white/90 backdrop-blur border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4">
      <div class="flex items-center justify-between h-16">
        <a href="#" class="flex items-center gap-2">
          <!-- Replace with your logo -->
          <img src="/logo-freelance-haiti.png" alt="Freelance Haiti" class="h-9 w-auto" onerror="this.style.display='none'" />
          <span class="font-bold text-xl tracking-tight text-brand-700">Freelance Haiti</span>
        </a>
        <nav class="hidden md:flex items-center gap-8">
          <a class="hover:text-brand-700" href="#services">Services</a>
          <a class="hover:text-brand-700" href="#fonctionnement">Fonctionnement</a>
          <a class="hover:text-brand-700" href="#tarifs">Tarifs</a>
          <a class="hover:text-brand-700" href="#contact">Contact</a>
        </nav>
        <div class="flex items-center gap-2">
          <!-- TODO: Remplacez le numéro WhatsApp ci-dessous -->
          <a href="https://wa.me/50900000000?text=Bonjou%20Freelance%20Haiti%2C%20mwen%20bezwen%20info%20sou..." class="hidden sm:inline-flex items-center gap-2 rounded-2xl bg-brand-600 hover:bg-brand-700 text-white px-4 py-2 shadow-glow transition">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 24 24" fill="currentColor"><path d="M.057 24l1.687-6.163a11.867 11.867 0 01-1.62-6.003C.122 5.281 5.403 0 12.06 0c3.183 0 6.167 1.24 8.413 3.488a11.82 11.82 0 013.495 8.414c-.003 6.657-5.284 11.939-11.941 11.939a11.9 11.9 0 01-6.003-1.62L.057 24zm6.597-3.807c1.72.995 3.276 1.591 5.392 1.593 5.448.003 9.886-4.431 9.889-9.88.002-5.462-4.415-9.89-9.881-9.892-5.45-.002-9.887 4.43-9.889 9.878a9.82 9.82 0 001.746 5.555l-.999 3.648 3.742-.902zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.03-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.521.149-.174.198-.298.298-.497.099-.198.05-.372-.025-.521-.074-.149-.669-1.611-.916-2.206-.242-.579-.487-.5-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.262.489 1.694.626.712.227 1.36.195 1.873.118.571-.085 1.758-.718 2.006-1.412.248-.694.248-1.289.173-1.413z"/></svg>
            WhatsApp
          </a>
          <button id="menuBtn" class="md:hidden inline-flex items-center justify-center p-2 rounded-lg border border-slate-300" aria-label="Ouvrir le menu">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/></svg>
          </button>
        </div>
      </div>
    </div>
    <!-- Mobile menu -->
    <div id="mobileMenu" class="md:hidden hidden border-t border-slate-200">
      <nav class="px-4 py-3 space-y-2 bg-white">
        <a class="block py-2" href="#services">Services</a>
        <a class="block py-2" href="#fonctionnement">Fonctionnement</a>
        <a class="block py-2" href="#tarifs">Tarifs</a>
        <a class="block py-2" href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="relative overflow-hidden">
    <div class="absolute inset-0 bg-gradient-to-br from-brand-900 via-brand-700 to-brand-500 opacity-95"></div>
    <div class="absolute inset-0 noise opacity-[.12]"></div>
    <div class="relative max-w-7xl mx-auto px-4 py-24 lg:py-32 text-white">
      <div class="grid lg:grid-cols-2 gap-10 items-center">
        <div>
          <h1 class="text-4xl md:text-5xl font-extrabold leading-tight">Connexion <span class="text-brand-200">Talents</span> & Entreprises en Haïti</h1>
          <p class="mt-4 text-lg md:text-xl text-brand-100/90">Trouvez des freelances qualifiés (dev, design, marketing, rédaction) ou décrochez votre prochaine mission. Simple. Rapide. Pro.</p>
          <div class="mt-8 flex flex-wrap gap-3">
            <a href="#contact" class="inline-flex items-center justify-center rounded-2xl bg-white text-brand-800 font-semibold px-6 py-3 shadow-glow">Publier une mission</a>
            <a href="#services" class="inline-flex items-center justify-center rounded-2xl ring-2 ring-white/70 text-white font-semibold px-6 py-3 hover:bg-white/10">Voir les services</a>
          </div>
          <div class="mt-6 text-sm text-brand-100/80">\ud83d\udce8 contact@freelancehaiti.ht · \ud83d\udcf1 +509 XX XX XX XX</div>
        </div>
        <div class="relative">
          <div class="rounded-3xl bg-white/10 backdrop-blur p-4 md:p-6 shadow-xl ring-1 ring-white/20">
            <div class="rounded-2xl bg-white p-5 md:p-6">
              <div class="flex items-center gap-2 mb-4">
                <span class="h-3 w-3 rounded-full bg-red-400"></span>
                <span class="h-3 w-3 rounded-full bg-amber-400"></span>
                <span class="h-3 w-3 rounded-full bg-emerald-400"></span>
              </div>
              <h3 class="text-xl font-bold mb-3 text-slate-800">Publiez un besoin · Recevez 3 devis</h3>
              <form action="#contact" class="grid gap-3">
                <input type="text" placeholder="Je cherche un designer pour un logo" class="w-full rounded-xl border border-slate-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand-500" required>
                <input type="email" placeholder="Votre email" class="w-full rounded-xl border border-slate-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand-500" required>
                <button class="rounded-xl bg-brand-600 hover:bg-brand-700 text-white px-4 py-3 font-semibold">Recevoir des devis</button>
              </form>
              <p class="mt-3 text-xs text-slate-500">Gratuit · Réponse sous 24h ouvrées</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Badges / Trust -->
  <section class="py-10 bg-white">
    <div class="max-w-7xl mx-auto px-4">
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4 text-center text-sm text-slate-600">
        <div class="p-3 rounded-xl border">\u23f1\ufe0f  Réponse rapide</div>
        <div class="p-3 rounded-xl border">\ud83d\udcbb +50 compétences</div>
        <div class="p-3 rounded-xl border">\ud83c\udfe0 100% remote</div>
        <div class="p-3 rounded-xl border">\ud83d\udcb0 Paiement sécurisé</div>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-20 bg-slate-50">
    <div class="max-w-7xl mx-auto px-4">
      <div class="md:flex items-end justify-between mb-10">
        <h2 class="text-3xl md:text-4xl font-extrabold text-slate-900">Compétences & Services</h2>
        <p class="text-slate-600 mt-3 md:mt-0">Design · Développement · Marketing · Rédaction · Audio/Video · Support</p>
      </div>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Service card template -->
        <article class="p-6 bg-white rounded-2xl border hover:shadow-lg transition">
          <h3 class="text-lg font-bold mb-2">Développement Web & App</h3>
          <p class="text-slate-600">Sites vitrines, e‑commerce, apps mobiles (Flutter), intégrations Supabase, automations.</p>
        </article>
        <article class="p-6 bg-white rounded-2xl border hover:shadow-lg transition">
          <h3 class="text-lg font-bold mb-2">Design & Branding</h3>
          <p class="text-slate-600">Logos, identités visuelles, UI/UX, bannières réseaux sociaux, créas pubs.</p>
        </article>
        <article class="p-6 bg-white rounded-2xl border hover:shadow-lg transition">
          <h3 class="text-lg font-bold mb-2">Marketing Digital</h3>
          <p class="text-slate-600">Community management, campagnes Meta/Google, SEO local, emailing.</p>
        </article>
        <article class="p-6 bg-white rounded-2xl border hover:shadow-lg transition">
          <h3 class="text-lg font-bold mb-2">Rédaction & Traduction</h3>
          <p class="text-slate-600">Textes humanisés FR/HT/EN, scripts vidéo, fiches produits, blog.</p>
        </article>
        <article class="p-6 bg-white rounded-2xl border hover:shadow-lg transition">
          <h3 class="text-lg font-bold mb-2">Photo / Vidéo</h3>
          <p class="text-slate-600">Montage, sous-titrage, miniatures YouTube, shooting produits.</p>
        </article>
        <article class="p-6 bg-white rounded-2xl border hover:shadow-lg transition">
          <h3 class="text-lg font-bold mb-2">Support & Assistance</h3>
          <p class="text-slate-600">Support client, modération, saisie de données, assistants virtuels.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- How it works -->
  <section id="fonctionnement" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-3xl md:text-4xl font-extrabold text-slate-900 mb-10">Comment ça marche ?</h2>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="p-6 rounded-2xl border">
          <div class="text-3xl">1</div>
          <h3 class="font-bold mt-3 mb-2">Publiez votre besoin</h3>
          <p class="text-slate-600">Décrivez votre projet, budget et délai. C’est gratuit et sans engagement.</p>
        </div>
        <div class="p-6 rounded-2xl border">
          <div class="text-3xl">2</div>
          <h3 class="font-bold mt-3 mb-2">Recevez des devis</h3>
          <p class="text-slate-600">Nous vous proposons 2‑3 freelances qualifiés adaptés à votre besoin.</p>
        </div>
        <div class="p-6 rounded-2xl border">
          <div class="text-3xl">3</div>
          <h3 class="font-bold mt-3 mb-2">Travaillez en sécurité</h3>
          <p class="text-slate-600">Paiement sécurisé, contrat simple, suivi jusqu’à la livraison.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing -->
  <section id="tarifs" class="py-20 bg-slate-50">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-3xl md:text-4xl font-extrabold text-slate-900 mb-10">Tarifs simples</h2>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-white rounded-2xl border p-6">
          <h3 class="text-xl font-bold">Starter</h3>
          <p class="mt-2 text-slate-600">Pour petites missions ponctuelles</p>
          <div class="mt-4 text-3xl font-extrabold">$0</div>
          <ul class="mt-4 space-y-2 text-slate-600">
            <li>✔️ Publication gratuite</li>
            <li>✔️ 2 devis en 24‑48h</li>
            <li>✔️ Contrat standard</li>
          </ul>
        </div>
        <div class="bg-white rounded-2xl border p-6 ring-2 ring-brand-500">
          <h3 class="text-xl font-bold">Pro</h3>
          <p class="mt-2 text-slate-600">Pour besoins récurrents</p>
          <div class="mt-4 text-3xl font-extrabold">$49<span class="text-base font-semibold">/mois</span></div>
          <ul class="mt-4 space-y-2 text-slate-600">
            <li>✔️ Priorité de matching</li>
            <li>✔️ Support WhatsApp dédié</li>
            <li>✔️ Facturation consolidée</li>
          </ul>
        </div>
        <div class="bg-white rounded-2xl border p-6">
          <h3 class="text-xl font-bold">Entreprise</h3>
          <p class="mt-2 text-slate-600">Pour équipes & agences</p>
          <div class="mt-4 text-3xl font-extrabold">Sur devis</div>
          <ul class="mt-4 space-y-2 text-slate-600">
            <li>✔️ Recrutement multi‑profils</li>
            <li>✔️ SLA & gestion de projet</li>
            <li>✔️ Paiements locaux (MonCash)</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="py-16 bg-gradient-to-r from-brand-900 via-brand-700 to-brand-600 text-white">
    <div class="max-w-7xl mx-auto px-4 text-center">
      <h2 class="text-3xl md:text-4xl font-extrabold">Prêt à lancer votre mission ?</h2>
      <p class="mt-3 text-brand-100">Décrivez votre besoin en 2 minutes. On s’occupe du reste.</p>
      <a href="#contact" class="mt-6 inline-flex items-center justify-center rounded-2xl bg-white text-brand-800 font-semibold px-6 py-3 shadow-glow">Démarrer</a>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4">
      <div class="grid lg:grid-cols-2 gap-10 items-start">
        <div>
          <h2 class="text-3xl md:text-4xl font-extrabold text-slate-900">Contact & Réseaux</h2>
          <p class="mt-3 text-slate-600">Parlez‑nous de votre projet : FR · HT · EN.</p>
          <div class="mt-6 space-y-3">
            <a href="mailto:contact@freelancehaiti.ht" class="block">✉️ contact@freelancehaiti.ht</a>
            <a href="tel:+50900000000" class="block">📞 +509 XX XX XX XX</a>
            <!-- Replace social links below -->
            <div class="flex items-center gap-3 pt-2">
              <a aria-label="WhatsApp" href="https://wa.me/50900000000?text=Bonjou%20Freelance%20Haiti" class="p-2 rounded-xl border hover:bg-slate-50">WhatsApp</a>
              <a aria-label="Instagram" href="https://instagram.com/freelancehaiti" class="p-2 rounded-xl border hover:bg-slate-50">Instagram</a>
              <a aria-label="Facebook" href="https://facebook.com/freelancehaiti" class="p-2 rounded-xl border hover:bg-slate-50">Facebook</a>
              <a aria-label="Pinterest" href="https://pinterest.com/freelancehaiti" class="p-2 rounded-xl border hover:bg-slate-50">Pinterest</a>
              <a aria-label="Email" href="mailto:contact@freelancehaiti.ht" class="p-2 rounded-xl border hover:bg-slate-50">Email</a>
            </div>
          </div>
        </div>
        <div>
          <form class="bg-slate-50 rounded-2xl p-6 border grid gap-4" name="contact" method="POST" data-netlify="true">
            <input type="hidden" name="form-name" value="contact">
            <div>
              <label class="block text-sm font-medium mb-1" for="name">Nom</label>
              <input id="name" name="name" type="text" class="w-full rounded-xl border border-slate-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand-500" required>
            </div>
            <div>
              <label class="block text-sm font-medium mb-1" for="email">Email</label>
              <input id="email" name="email" type="email" class="w-full rounded-xl border border-slate-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand-500" required>
            </div>
            <div>
              <label class="block text-sm font-medium mb-1" for="type">Type de besoin</label>
              <select id="type" name="type" class="w-full rounded-xl border border-slate-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand-500">
                <option>Développement</option>
                <option>Design</option>
                <option>Marketing</option>
                <option>Rédaction</option>
                <option>Photo/Vidéo</option>
                <option>Autre</option>
              </select>
            </div>
            <div>
              <label class="block text-sm font-medium mb-1" for="message">Message</label>
              <textarea id="message" name="message" rows="4" class="w-full rounded-xl border border-slate-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand-500" placeholder="Décrivez brièvement votre projet"></textarea>
            </div>
            <button class="rounded-xl bg-brand-600 hover:bg-brand-700 text-white px-4 py-3 font-semibold">Envoyer</button>
            <p class="text-xs text-slate-500">En envoyant ce formulaire, vous acceptez nos conditions et politique de confidentialité.</p>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-10 bg-slate-900 text-slate-300">
    <div class="max-w-7xl mx-auto px-4 grid md:grid-cols-3 gap-8">
      <div>
        <div class="font-bold text-white text-lg">Freelance Haiti</div>
        <p class="mt-2 text-slate-400">Boostez vos missions, visez l’international.</p>
      </div>
      <div>
        <div class="font-semibold text-white">Liens</div>
        <ul class="mt-2 space-y-1 text-slate-400">
          <li><a href="#services" class="hover:text-white">Services</a></li>
          <li><a href="#fonctionnement" class="hover:text-white">Fonctionnement</a></li>
          <li><a href="#tarifs" class="hover:text-white">Tarifs</a></li>
          <li><a href="#contact" class="hover:text-white">Contact</a></li>
        </ul>
      </div>
      <div>
        <div class="font-semibold text-white">Newsletter</div>
        <form class="mt-2 flex gap-2">
          <input type="email" placeholder="Votre email" class="flex-1 rounded-xl border border-slate-600 bg-slate-800 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand-500" />
          <button class="rounded-xl bg-brand-600 hover:bg-brand-700 text-white px-4 py-3 font-semibold">S’abonner</button>
        </form>
      </div>
    </div>
    <div class="mt-8 text-center text-xs text-slate-500">© <span id="year"></span> Freelance Haiti — Tous droits réservés.</div>
  </footer>

  <script>
    // Mobile menu toggle
    const btn = document.getElementById('menuBtn');
    const menu = document.getElementById('mobileMenu');
    btn?.addEventListener('click', () => menu.classList.toggle('hidden'));

    // Current year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>

  <!-- Structured Data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "Freelance Haiti",
    "url": "https://freelancehaiti.example",
    "logo": "https://freelancehaiti.example/logo-freelance-haiti.png",
    "sameAs": [
      "https://instagram.com/freelancehaiti",
      "https://facebook.com/freelancehaiti",
      "https://pinterest.com/freelancehaiti"
    ],
    "contactPoint": {
      "@type": "ContactPoint",
      "contactType": "customer support",
      "telephone": "+50900000000",
      "email": "contact@freelancehaiti.ht"
    }
  }
  </script>
</body>
</html>
