# Rues Community

Topluluk içerikleri (`icerikler/`) ve RC RSI uyumsuzluk aracı
(`index.html`, `js/`, `lib/`, `api/`). Testler: `npm test`.
Metinler Türkçe, sade dille yazılır.

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

## Kadro (`.claude/agents/`)
| Ajan | Model | İş |
|---|---|---|
| yukleyici | haiku | Mekanik toplu işler |
| arastirmaci | sonnet | Kaynaklı araştırma, kod yazmaz |
| gelistirici | sonnet | Tarif edilmiş kod ve test |
| denetci | sonnet / opus | Bağımsız kontrol, ONAY / DUZELT |
| tasarimci | opus | Görsel yargı |
| video-ureticisi | opus | Video ve ses |
| arsivci | haiku | Yazı arşivi, Aşama A: özgün metni değiştirmeden kaydeder |
| edebi-okur | opus | Aşama B: edebî değerlendirme (04-notlar.md) |
| duzeltmen | sonnet | Aşama C: imla ve noktalama (02-duzeltilmis.md) |
| deneme-editoru | opus | Aşama D: yalnızca istenirse deneme sürümü (03-deneme.md) |
| yazi-denetcisi | sonnet | Yazı işini denetler; ses kaybı ve özgün metin kontrolü |

## Kişisel yazılar bu repoya girmez
Bu repo herkese açık. Kişisel yazılar ve yazarlık arşivi
ayrı, gizli bir repoda tutulur. Yazı ajanları buradan
oraya kopyalanabilir; metinler buraya kopyalanmaz.
