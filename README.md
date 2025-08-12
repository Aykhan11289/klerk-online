<!DOCTYPE html><html lang="az">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
Klerk.Online - Ofis Xidmətləri
  <link rel="icon" href="logo.png" type="image/png" sizes="96x96">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  
</head>
<body class="font-inter bg-gray-50 text-gray-800">
  <header class="bg-white shadow-md p-4 sticky top-0 z-50">
	  <div class="container mx-auto flex justify-between items-center">
      <div class="flex items-center space-x-2">
	      <img src="logo.png" alt="Hawk Logo" width="100" height="auto"/>
        <h1 class="text-2xl font-bold text-blue-700">Klerk.Online</h1>
      </div>
      <div class="flex items-center space-x-4">
        <nav class="space-x-4 hidden md:block">
          <a href="#services" class="hover:text-blue-700">Xidmətlər</a>
          <a href="#about" class="hover:text-blue-700">Haqqımızda</a>
          <a href="#contact" class="hover:text-blue-700">Əlaqə</a>
        </nav>
        <div>
	  <select class="border border-gray-300 rounded-lg px-2 py-1 text-sm" onchange="changeLanguage(this.value)">
            <option value="index.html" selected>AZ</option>
            <option value="index-ru.html">RU</option>
            <option value="index-en.html">EN</option>
          </select>
        </div>
      </div>
    </div>
  </header>  <section class="text-center py-16 bg-blue-700 text-white">
    <h2 class="text-4xl font-extrabold mb-4">Ofis Əməliyyatlarını Sadələşdirin</h2>
    <p class="text-lg">Biznesinizə uyğun ofis xidmətləri</p>
  </section>  <section id="services" class="py-16 container mx-auto px-4">
    <h3 class="text-3xl font-bold mb-10 text-center">Xidmətlərimiz</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-white shadow p-6 rounded-2xl">
        <h4 class="text-xl font-semibold mb-2">Ofis Menecerləri</h4>
        <p>Gündəlik idarəetmə üçün peşəkar və təcrübəli menecerlər.</p>
      </div>
      <div class="bg-white shadow p-6 rounded-2xl">
        <h4 class="text-xl font-semibold mb-2">Sənədləşmə</h4>
        <p>Kopyalama, skan, çap, sənədlərin idarəsi və qorunması.</p>
      </div>
      <div class="bg-white shadow p-6 rounded-2xl">
        <h4 class="text-xl font-semibold mb-2">Mühasiblər</h4>
        <p>Maliyyə hesabatları və vergi üçün peşəkar mühasibat xidmətləri.</p>
      </div>
      <div class="bg-white shadow p-6 rounded-2xl">
        <h4 class="text-xl font-semibold mb-2">Ofis Kirayəsi</h4>
        <p>Ən yaxşı yerlərdə müasir şəraitli ofislər.</p>
      </div>
      <div class="bg-white shadow p-6 rounded-2xl">
        <h4 class="text-xl font-semibold mb-2">Hüquqşünaslar</h4>
        <p>Müqavilələr, hüquqi məsləhət və uyğunluq üçün hüquq xidmətləri.</p>
      </div>
      <div class="bg-white shadow p-6 rounded-2xl">
        <h4 class="text-xl font-semibold mb-2">Brokerlər</h4>
        <p>Əmlak, maliyyə və investisiya sahəsində peşəkar vasitəçilər.</p>
      </div>
    </div>
  </section>  <section id="about" class="py-16 bg-gray-100">
    <div class="container mx-auto px-4 text-center">
      <h3 class="text-3xl font-bold mb-6">Niyə Biz?</h3>
      <p class="max-w-2xl mx-auto text-lg">Biz ofis əməliyyatlarını asan və miqyaslana bilən etmək üçün peşəkarları bir araya gətiririk. Vaxtınıza və resurslarınıza qənaət edin – qalanını biz həll edək.</p>
    </div>
  </section>  <section id="contact" class="py-16 container mx-auto px-4">
    <h3 class="text-3xl font-bold mb-6 text-center">Bizimlə Əlaqə</h3>
   <!-- <form class="max-w-xl mx-auto space-y-4">
      <input type="text" placeholder="Adınız" class="w-full p-3 border rounded-xl" required />
      <input type="email" placeholder="Email" class="w-full p-3 border rounded-xl" required />
      <textarea placeholder="Mesajınız" class="w-full p-3 border rounded-xl" rows="5" required></textarea>
      <button type="submit" class="bg-blue-700 text-white px-6 py-3 rounded-xl hover:bg-blue-800">Göndər</button>
    </form>-->
	
	<form action="https://formsubmit.co/info@klerk.online" method="POST" class="max-w-xl mx-auto space-y-4">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_next" value="https://klerk.online/thanks.html">
  
  <input type="text" name="name" placeholder="Your Name" class="w-full p-3 border rounded-xl" required />
  <input type="email" name="email" placeholder="Email" class="w-full p-3 border rounded-xl" required />
  <textarea name="message" placeholder="Message" class="w-full p-3 border rounded-xl" rows="5" required></textarea>
  
  <button type="submit" class="bg-blue-700 text-white px-6 py-3 rounded-xl hover:bg-blue-800">Göndər</button>
</form>

  </section>  <footer class="bg-white shadow-md p-4 text-center text-sm text-gray-500">
    &copy; 2025 Union Inc MMC. Bütün hüquqlar qorunur.
  </footer> <script>
   function changeLanguage(page) {
     window.location.href = page;
    }
  </script>
  </body>
</html> 
