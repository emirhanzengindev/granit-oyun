# Granit: Kaçış Destanı

Tarayıcıda çalışan, 3D, hikâyeli bir hayatta kalma ve nişancı oyunu (Three.js). Oyun beş kısımdan oluşuyor; her kısımda 30 bölüm ve 6 boss var. Toplam 150 bölüm ve 30 boss.

Yüzbaşı Arda "Granit" Demir, iptal edilen bir süper asker programının hayatta kalan tek deneğidir. Önce gizli bir hapishaneden kaçar. Sonra canlı bir müzeye numune olarak kaçırılır, kanından bir asker ordusu dökülür, eski bir Osmanlı saatiyle zamanda geri gider Taş Devri'ne düşer ve sonunda serumun kaynağını bulmak için Karadeniz'in dibindeki batık bir kente iner.

## Kısımlar

| Kısım | Ad | Konu |
|---|---|---|
| I | Kara Sektör'den Kaçış | Yeraltı hapishanesi, Dr. Varga ve mutantları |
| II | Cam Çölü | Mühürcülerin canlı müzesi, camdan gezegen Serap, camdan yaratık Uğultu |
| III | Dönüş | Döküm Ustası, Granit'in kanından dökülen Kalıp ordusu, kor kılıcı |
| IV | Yarının Gölgesi | Galata'nın altındaki Muvakkithane'nin saatiyle 2049–2026 arası zaman savaşı, Uyumcu robotlar |
| V | Taş Devri | Dinozorlar, mağara kabileleri, parçalanmış zaman makinesi |
| VI | Derinlerin Şehri | Karadeniz'in dibinde batık bir Anadolu kenti, oksijen, akıntılar ve serumun kaynağı Derin Ana |

Kısım II'den itibaren her kısım bir önceki kısmın özetiyle başlar. Her 5 bölümün başında hikâyeyi konuşma balonlu bir çizgi roman sayfası anlatır.

## Oynanış

- **Otomatik ateş:** Silah en yakın düşmana kendiliğinden ateş eder. Sen hareket eder, kaçar ve yer seçersin.
- **Seviye atlama:** 16 yetenek arasından üç kart sunulur. Kartlar dört kategoriye ayrılır: saldırı, savunma, hareket ve teknoloji. Seyrek çıkan destansı kartlar iki kademe birden verir. Her seviyede bir kez kartları yeniden çekebilirsin.
- **Silahlar:** Her boss sonrası 7 silah arasından seçim yapılır ve silah bir kademe güçlenir. Silahların adı ve görünüşü her kısımda değişir.
- **Bosslar:** Canları, karşılaştığın anda karakterinin gücüne göre ayarlanır.
- **Kısma özgü mekanikler:** Her kısmın kendine ait tehlikeleri vardır. Örneğin Uğultu, akort totemleri, hurda presi, keskin nişancı, zaman yırtıkları, uyum, sürü koşusu, meteor yağmuru ve ince buz.
- **Altın ve market:** Düşmanlar ve bosslar altın düşürür, her bölüm sonunda ödül verilir. Oyuna 5 temel eklentiyle başlanır; diğer 11 eklenti ve fazladan yuvalar marketten altınla alınır. Seviye atlayınca yalnızca takılı eklentiler kart olarak çıkar.
- **Özgün saldırılar:** Her düşman tipinin kendine özgü bir saldırısı, her bossun ekranda adı görünen iki imza saldırısı vardır.
- **Serum Kanı:** Öldürdükçe ve hasar aldıkça dolar; Boşluk tuşuyla her kısma özgü bir güç açığa çıkar. Granit'in kanından yapılmış düşmanlara iki kat etkilidir.
- **Görsel stil:** Çizgi roman havası: üç tonlu gölgelendirme, mürekkep konturları, baskı noktası dokusu, ekrana patlayan ses yazıları ve her kısmın kendi imza rengi.
- **Müzik:** Tarayıcıda anlık üretilir; her kısmın Türk makamlarına dayalı kendi ritmi vardır, boss gelince değişir.
- **Yan karakterler:** Her boss savaşından önce üç yan karakterden birini seçersin: Şifacı Ece (iyileştirir), Saya (serum barını doldurur) ya da Gardiyan Hasan (%60 daha fazla hasar). Granit ve yan karakterlerin modelleri Tripo'da üretilip oyun için sadeleştirildi.
- **Konuşmalar:** Bölüm başlarında, boss savaşlarında ve yan karakterlerle çizgi roman balonlarıyla konuşmalar geçer.
- **Silah ustalığı:** Boss sonrası aynı silahı seçersen ustalığı artar (en fazla 5 kademe); ilerleme ve stat değişimi ekranda gösterilir.
- **Mobil yan ekran:** Telefonda yan ekran için düzenlenmiş arayüz, tam ekran ve yatay kilit. Android'de Chrome'dan **Ana ekrana ekle** ile uygulama gibi tam ekran açılır.
- **Mini harita:** Düşmanları, bossu, engelleri, tehlikeleri ve toplanabilir nesneleri gösterir.
- **Kayıt:** İlerleme her kısım için ayrı ayrı tarayıcıda kaydedilir (localStorage).

## Kontroller

| Eylem | Klavye | Dokunmatik |
|---|---|---|
| Hareket | WASD / ok tuşları | Ekranda sürükle |
| Ateş | Otomatik | Otomatik |
| Güçlendirme seçimi | 1, 2, 3 | Karta dokun |
| Serum Kanı | Boşluk | SERUM düğmesi |
| Duraklat | Esc / P | II düğmesi |

## Çalıştırma

Kurulum gerekmez. `index.html` dosyasını bir tarayıcıda aç. Three.js r128 CDN'den yüklendiği için internet bağlantısı gerekir.

GitHub Pages ile yayınlamak için deponun **Settings → Pages** bölümünde kaynak olarak **`main` / root** seç.
