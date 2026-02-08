<!DOCTYPE html>
<html lang="en">
<head>
  <!-- =====================
       Project: Zionist 7th Day Church of God Kenya
       Single-page responsive website
       ===================== -->
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Zionist 7th Day Church of God Kenya</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            heading: ['Playfair Display', 'serif'],
            body: ['Roboto', 'sans-serif'],
          },
          colors: {
            faithgreen: '#1f7a63',
            faithgold: '#c9a227',
          }
        }
      }
    }
  </script>

  <style>
    html { scroll-behavior: smooth; }
  </style>
</head>
<body class="font-body text-gray-800">

<!-- ===================== HERO SECTION ===================== -->
<section id="home" class="relative bg-gradient-to-br from-faithgreen via-green-700 to-gray-900 text-white">
  <div class="absolute inset-0 opacity-20">
    <!-- Placeholder background image -->
    <img src="https://images.unsplash.com/photo-1547970810-dc1eac37d174" alt="Kenyan landscape" class="w-full h-full object-cover" />
  </div>
  <div class="relative max-w-6xl mx-auto px-6 py-32 text-center">
    <h1 class="font-heading text-4xl md:text-6xl mb-4">Welcome to Zionist 7th Day Church of God Kenya</h1>
    <p class="text-xl md:text-2xl text-faithgold mb-6">Keeping the Sabbath Holy, Walking in Faith</p>
    <p class="max-w-3xl mx-auto mb-8">
      A church with roots in the wilderness with Moses, reborn through Christ, observing the seventh-day Sabbath and biblical feasts as revealed in Scripture.
    </p>
    <div class="flex flex-col md:flex-row gap-4 justify-center">
      <a href="#services" class="bg-faithgold text-black px-8 py-3 rounded-full font-semibold hover:bg-yellow-400">Join Our Services</a>
      <a href="#contact" class="border border-white px-8 py-3 rounded-full hover:bg-white hover:text-black">Contact Us</a>
    </div>
  </div>
</section>

<!-- ===================== ABOUT US ===================== -->
<section id="about" class="py-20 bg-white">
  <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
    <img src="https://via.placeholder.com/600x400" alt="Church congregation" class="rounded-lg shadow-lg" />
    <div>
      <h2 class="font-heading text-3xl mb-4 text-faithgreen">About Us</h2>
      <p class="mb-6">
        Zionist 7th Day Church of God Kenya is a Sabbath-keeping Christian church committed to biblical truth from Genesis to Revelation. We observe the seventh-day Sabbath, biblical feasts such as Pesach, and uphold salvation through Christ. Rooted in Kenya, we are united in faith, worship, and community service.
      </p>
      <div class="grid grid-cols-2 gap-4">
        <div class="p-4 bg-gray-100 rounded">
          <p class="font-bold">Established</p>
          <p>Faith-rooted ministry</p>
        </div>
        <div class="p-4 bg-gray-100 rounded">
          <p class="font-bold">Leadership</p>
          <p>General Overseer</p>
        </div>
        <div class="p-4 bg-gray-100 rounded">
          <p class="font-bold">Core Values</p>
          <p>Faith, Community</p>
        </div>
        <div class="p-4 bg-gray-100 rounded">
          <p class="font-bold">Foundation</p>
          <p>Scripture-based worship</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ===================== OUR BELIEFS ===================== -->
<section id="beliefs" class="py-20 bg-gray-50">
  <div class="max-w-6xl mx-auto px-6">
    <h2 class="font-heading text-3xl text-center mb-12 text-faithgreen">Our Beliefs</h2>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-white p-6 rounded-lg shadow">
        <i class="fa-solid fa-calendar-day text-faithgold text-3xl mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">Sabbath Keeping</h3>
        <ul class="list-disc ml-5 text-sm">
          <li>Seventh-day Sabbath (Saturday)</li>
          <li>Commanded in Scripture</li>
        </ul>
      </div>
      <div class="bg-white p-6 rounded-lg shadow">
        <i class="fa-solid fa-book-bible text-faithgold text-3xl mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">Biblical Feasts</h3>
        <ul class="list-disc ml-5 text-sm">
          <li>Pesach and holy convocations</li>
          <li>Christ-centered meaning</li>
        </ul>
      </div>
      <div class="bg-white p-6 rounded-lg shadow">
        <i class="fa-solid fa-cross text-faithgold text-3xl mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">Salvation Through Christ</h3>
        <ul class="list-disc ml-5 text-sm">
          <li>Jesus Christ our Savior</li>
          <li>Grace and obedience</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- ===================== SERVICES & EVENTS ===================== -->
<section id="services" class="py-20 bg-white">
  <div class="max-w-6xl mx-auto px-6">
    <h2 class="font-heading text-3xl text-center mb-12 text-faithgreen">Services & Events</h2>
    <div class="mb-12 text-center">
      <p class="text-lg font-semibold">Sabbath Worship</p>
      <p>Saturday | 9:00 AM – 1:00 PM</p>
      <p>Nakuru, Kenya</p>
    </div>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="p-6 bg-gray-100 rounded">
        <h4 class="font-bold">General Conference</h4>
        <p class="text-sm">Upcoming national gathering</p>
        <a href="#" class="text-faithgreen text-sm">Learn More</a>
      </div>
      <div class="p-6 bg-gray-100 rounded">
        <h4 class="font-bold">Church Opening – Mutrakwa</h4>
        <p class="text-sm">New fellowship launch</p>
        <a href="#" class="text-faithgreen text-sm">Learn More</a>
      </div>
      <div class="p-6 bg-gray-100 rounded">
        <h4 class="font-bold">Youth Sabbath</h4>
        <p class="text-sm">Youth-led worship</p>
        <a href="#" class="text-faithgreen text-sm">Learn More</a>
      </div>
    </div>
  </div>
</section>

<!-- ===================== SERMONS & RESOURCES ===================== -->
<section id="sermons" class="py-20 bg-gray-50">
  <div class="max-w-6xl mx-auto px-6">
    <h2 class="font-heading text-3xl text-center mb-12 text-faithgreen">Sermons & Resources</h2>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-white p-4 rounded shadow">
        <iframe class="w-full h-48 mb-4" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Sermon video"></iframe>
        <h4 class="font-semibold">History of Church of God 7th Day Kenya</h4>
        <a href="#" class="text-faithgreen">Watch Now</a>
      </div>
      <div class="bg-white p-4 rounded shadow">
        <h4 class="font-semibold">Bible Study Notes</h4>
        <p class="text-sm">Downloadable PDF teachings</p>
        <a href="#" class="text-faithgreen">Download</a>
      </div>
      <div class="bg-white p-4 rounded shadow">
        <h4 class="font-semibold">Feast Day Teachings</h4>
        <p class="text-sm">Understanding biblical feasts</p>
        <a href="#" class="text-faithgreen">View Resource</a>
      </div>
    </div>
  </div>
</section>

<!-- ===================== COMMUNITY & OUTREACH ===================== -->
<section id="community" class="py-20 bg-white">
  <div class="max-w-6xl mx-auto px-6">
    <h2 class="font-heading text-3xl text-center mb-12 text-faithgreen">Community & Outreach</h2>
    <div class="grid md:grid-cols-3 gap-6 mb-12">
      <blockquote class="p-6 bg-gray-100 rounded">“I found truth and fellowship in the Sabbath.”</blockquote>
      <blockquote class="p-6 bg-gray-100 rounded">“This church strengthened my faith journey.”</blockquote>
      <blockquote class="p-6 bg-gray-100 rounded">“A welcoming spiritual family.”</blockquote>
    </div>
    <p class="text-center max-w-3xl mx-auto">
      We actively serve our communities in Kenya through outreach, prayer, and support initiatives that reflect Christ’s love.
    </p>
  </div>
</section>

<!-- ===================== CONTACT & CONNECT ===================== -->
<section id="contact" class="py-20 bg-gray-900 text-white">
  <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12">
    <div>
      <h2 class="font-heading text-3xl mb-4">Contact & Connect</h2>
      <p>Nakuru, Kenya</p>
      <p>Phone: +254 XXX XXX XXX</p>
      <p>Email: info@zionist7thdaychurch.org</p>
      <div class="flex gap-4 mt-4">
        <a href="#" aria-label="Facebook"><i class="fab fa-facebook text-2xl"></i></a>
        <a href="#" aria-label="YouTube"><i class="fab fa-youtube text-2xl"></i></a>
      </div>
      <a href="#" class="inline-block mt-6 bg-faithgold text-black px-6 py-3 rounded">Support Our Ministry</a>
    </div>
    <form class="bg-white text-black p-6 rounded">
      <input type="text" placeholder="Your Name" class="w-full mb-4 p-2 border rounded" />
      <input type="email" placeholder="Your Email" class="w-full mb-4 p-2 border rounded" />
      <textarea placeholder="Your Message" class="w-full mb-4 p-2 border rounded"></textarea>
      <button class="bg-faithgreen text-white px-6 py-2 rounded">Send Message</button>
    </form>
  </div>
</section>

<!-- ===================== FOOTER ===================== -->
<footer class="bg-black text-center text-white py-4 text-sm">
  © 2026 Zionist 7th Day Church of God Kenya. All rights reserved.
</footer>

</body>
</html>
