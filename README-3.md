# remil-abjad-tool

> **Remil & Abjad Calculation Tool** — A browser-based utility for scholars and students of traditional Islamic sciences.

---

## 🇹🇷 Türkçe

### Nedir?

**remil-abjad-tool**, alimlerin, hocaların ve ulemanın kağıt üzerinde elle yaptıkları ebced ve remil hesaplamalarını otomatikleştiren, tamamen tarayıcı tabanlı bir yardımcı araçtır.

### Ne Yapar?

- **Ebced Hesabı** — Arapça veya Latin metin girişinden harf bazlı ebced değeri üretir
- **Remil Dönüşümü** — Sayıyı sürekli 2'ye bölerek Remil sembol zincirine çevirir
- **Element Analizi** — Her harfi ebced değerine göre periyodik tablodaki en yakın elementle eşleştirir
- **Şifreleme I** — Baş-son harf kaydırma algoritması
- **Şifreleme II** — Toplam tabanlı karakter dönüşüm algoritması

### Dil Desteği

🇹🇷 Türkçe · 🇬🇧 English · 🇸🇦 عربي · 🇮🇩 Indonesia

### Önemli Uyarı

> ⚠️ **Bu araç yalnızca hesaplama ve tefekkür içindir.**
> Fal aracı **değildir**. Gayb bilgisine erişim aracı **değildir**.
> Sonuçlar bağlayıcı değildir.

### Kullanım

Tek dosya — indirip tarayıcıda aç, internet bağlantısı gerekmez (font yüklemesi hariç).

```bash
git clone https://github.com/SeyyidKadir/remil-abjad-tool.git
cd remil-abjad-tool
# index.html dosyasını tarayıcınızda açın
```

---

## 🇬🇧 English

### What is it?

**remil-abjad-tool** is a fully browser-based utility that automates the abjad (gematria) and remil (geomancy) calculations that Islamic scholars traditionally perform by hand on paper.

### Features

- **Abjad Calculator** — Computes letter-by-letter abjad values from Arabic or Latin text
- **Remil Conversion** — Repeatedly divides by 2 to generate a Remil symbol chain
- **Element Analysis** — Maps each letter to its nearest periodic element by abjad value
- **Cipher I** — First-last letter shift algorithm
- **Cipher II** — Character sum-based transformation algorithm

### Language Support

🇹🇷 Turkish · 🇬🇧 English · 🇸🇦 Arabic · 🇮🇩 Indonesian

### Important Disclaimer

> ⚠️ **This tool is for calculation and contemplation only.**
> It is **not** a divination tool. It does **not** provide access to hidden knowledge (ghayb).
> Results are not binding.

### Usage

Single file — download and open in any browser. No server required (except for Google Fonts).

```bash
git clone https://github.com/SeyyidKadir/remil-abjad-tool.git
cd remil-abjad-tool
# Open index.html in your browser
```

---

## 🇸🇦 عربي

### ما هي هذه الأداة؟

**remil-abjad-tool** هي أداة تعمل في المتصفح تُؤتمت حسابات الأبجد والرمل التي يجريها العلماء والفقهاء تقليديًا على الورق.

### المميزات

- **حساب الأبجد** — يحسب قيمة الأبجد لكل حرف من النص العربي أو اللاتيني
- **تحويل الرمل** — يقسم الرقم على 2 بشكل متكرر لإنتاج سلسلة رموز الرمل
- **تحليل العناصر** — يربط كل حرف بأقرب عنصر في الجدول الدوري وفق قيمته الأبجدية
- **التشفير I** — خوارزمية إزاحة الحرف الأول والأخير
- **التشفير II** — خوارزمية التحويل بناءً على مجموع الأحرف

### دعم اللغات

🇹🇷 تركي · 🇬🇧 إنجليزي · 🇸🇦 عربي · 🇮🇩 إندونيسي

### تنبيه مهم

> ⚠️ **هذه الأداة مخصصة للحساب والتفكر فقط.**
> **ليست** أداة تنجيم أو تكهن. **لا** توفر وصولاً إلى علم الغيب.
> النتائج غير ملزمة.

### الاستخدام

ملف واحد — نزّله وافتحه في أي متصفح. لا يحتاج إلى خادم.

---

## 🇮🇩 Indonesia

### Apa ini?

**remil-abjad-tool** adalah utilitas berbasis browser yang mengotomatiskan perhitungan abjad dan remil yang biasanya dilakukan para ulama secara manual di atas kertas.

### Fitur

- **Kalkulator Abjad** — Menghitung nilai abjad per huruf dari teks Arab atau Latin
- **Konversi Remil** — Membagi angka berulang kali dengan 2 untuk menghasilkan rantai simbol Remil
- **Analisis Elemen** — Memetakan setiap huruf ke elemen periodik terdekat berdasarkan nilai abjad
- **Sandi I** — Algoritma pergeseran huruf pertama-terakhir
- **Sandi II** — Algoritma transformasi berbasis jumlah karakter

### Dukungan Bahasa

🇹🇷 Turki · 🇬🇧 Inggris · 🇸🇦 Arab · 🇮🇩 Indonesia

### Perhatian Penting

> ⚠️ **Alat ini hanya untuk perhitungan dan tadabbur.**
> **Bukan** alat ramal atau tenung. **Tidak** memberikan akses ke ilmu ghaib.
> Hasil tidak bersifat mengikat.

### Penggunaan

Satu file — unduh dan buka di browser mana pun. Tidak memerlukan server.

---

## Technical Notes

- Pure HTML + CSS + JavaScript — zero dependencies, zero build step
- All computation is client-side
- Supports Arabic (RTL) and Latin (LTR) scripts with automatic direction switching
- Responsive design for mobile and desktop

## License

MIT

---

*Built for scholars. Grounded in tradition. Bounded by humility.*
