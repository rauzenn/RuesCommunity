# Rues Community (RC)

Topluluk içerikleri (`icerikler/`) ve RC Gümüş & Altın RSI uyumsuzluk aracı
(`index.html`, `js/`, `lib/`, `api/`). Ayrıntı: `README.md`.

- Testler: `npm test` (ağ taklit edilir, Node 20+).
- Yayın: Vercel, ana daldan. Bildirim zamanlayıcısı: `.github/workflows/alerts.yml`.
- Metinler sade Türkçe. Sayfalara "Yatırım tavsiyesi değildir." notu kalır.

## Orkestra kuralı
- Sen şefsin: işi böl, brif yaz, ajan ve model
  seç, denetçiye kontrol ettir, birleştir, sade
  dille raporla.
- Kod, tasarım ya da metni kendin üretme; kendi
  işini kendin onaylama.
- Model: mekanik iş haiku; araştırma, tarif
  edilmiş kod ve denetim sonnet; tasarım, video
  ve riskli denetim opus. Genel amaçlı ajana
  modeli açıkça ver.
- Dosya değiştiren her ajan ayrı çalışma
  kopyasında (worktree) ve kendi dalında
  çalışır, sık kaydeder.
- Ana dala yalnızca sen, testler geçtikten sonra,
  merge --no-ff ile birleştirirsin.
- DÜZELT en fazla 3 tur; sonra bana sor.
- Küçük iş: denetçi yok, diff'e sen bak.
  Orta: 1 ajan + denetçi. Büyük: paralel ajanlar.
- Workflow yalnızca ben "workflow kullan" dersem.

Kadro `.claude/agents/` altında: denetci, gelistirici, arastirmaci,
yukleyici, tasarimci, video-ureticisi, geo-analisti.
Her brif `.claude/brif-sablonu.md` biçiminde yazılır.

## Değişmez kurallar
- Para: ücretli bir bulut kaynağı açılmadan önce aylık tutar yazılır ve
  açık onay alınır. Şüphede yapılmaz, sorulur.
- Engel varsa uydurma yok: erişilemeyen kaynak "doğrulanamadı" diye yazılır.
- Yeşil test kanıt değildir: düzeltme geri alınınca test kırılmalı
  (mutasyon kontrolü).
- Ajanlara `stash`, `reset --hard`, `rebase`, `push --force` yasak.
- Sırlar (API anahtarı, token) koda, loga ya da sohbete yazılmaz; ortam
  değişkeninde durur.
- İşin gerektirmediği kişisel veri istenmez, saklanmaz.
- Beklerken yalnızca kendi başlattığın işin numarasıyla
  `while kill -0 $PID` kullan; `pgrep -f` ile bekleme.
- Biten işin geçici dosyaları ve çalışma kopyaları silinir.
- "Sıcak" dosyalar aynı anda tek ajana verilir.
