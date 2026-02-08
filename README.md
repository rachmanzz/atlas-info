<!-- Toggle Bahasa -->
<div style="margin-bottom: 1em;">
  <button onclick="setLang('id')" id="btn-id">🇮🇩 Indonesia</button> |
  <button onclick="setLang('en')" id="btn-en">🇺🇸 English</button>
</div>

<!-- Konten Bahasa Indonesia -->
<div id="content-id">
  ## 🇮🇩 Tentang Project Ini

  **Atlas adalah codename untuk project AI yang masih dalam tahap pre-release.**  
  Project ini membantu founder, UMKM, dan startup membuat **roadmap bisnis 90 hari yang siap dieksekusi**.

  Fitur saat ini:

  * Roadmap bisnis 90 hari terstruktur  
  * Sprint mingguan untuk 30 hari pertama  
  * KPI dengan target angka  
  * Target biaya, revenue, dan profit  
  * Analisis & insight kompetitor masuk ke roadmap

  Contoh hasil Atlas:  
  * Pencarian kompetitor: [https://rachmanzz.github.io/atlas-info/examples/id/competitor](https://rachmanzz.github.io/atlas-info/examples/id/competitor)  
  * Roadmap bisnis: [https://rachmanzz.github.io/atlas-info/examples/id/roadmap](https://rachmanzz.github.io/atlas-info/examples/id/roadmap)  
</div>

<!-- Konten Bahasa Inggris -->
<div id="content-en" style="display:none;">
  ## 🇺🇸 About This Project

  **Atlas is a codename for an AI project currently in pre-release.**  
  The project helps founders and small businesses generate a **90-day business roadmap ready to execute**.

  Current capabilities:

  * Structured 90-day roadmap  
  * Weekly sprint for the first 30 days  
  * KPI with numeric targets  
  * Cost, revenue, and profit targets  
  * Competitor insights are incorporated into the roadmap

  Atlas sample outputs:  
  * Competitor Search: [https://rachmanzz.github.io/atlas-info/examples/en/competitor](https://rachmanzz.github.io/atlas-info/examples/en/competitor)  
  * Complete Business Roadmap: [https://rachmanzz.github.io/atlas-info/examples/en/roadmap](https://rachmanzz.github.io/atlas-info/examples/en/roadmap)  
</div>

<script>
function setLang(lang) {
  document.getElementById('content-id').style.display = (lang === 'id') ? 'block' : 'none';
  document.getElementById('content-en').style.display = (lang === 'en') ? 'block' : 'none';
}
</script>
