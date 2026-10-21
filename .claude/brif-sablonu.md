# Brif şablonu

Ajanlar birbirini ve şefle yapılan sohbeti görmez; bildikleri tek şey brif.
Sınır çiz, yol çizme: neye dokunacağını ve ne zaman bitmiş sayılacağını söyle,
nasıl yapacağını ajana bırak.

```
GÖREV: Ne yapılacak ve neden.
SENİN DOSYALARIN: Ajanın değiştirebileceği dosyalar.
DOKUNMA: Başka ajanın çalıştığı ya da riskli dosyalar.
ÖNCE OKU: CLAUDE.md ve işle ilgili belgeler.
BİTTİ TANIMI:
 - ölçülebilir madde ("npm test geçiyor", "uydurma rakam yok",
   "390 px ekranda taşma yok")
RAPOR: {"dosyalar": [], "ozet": "", "testler": "",
 "acikSorunlar": [], "oneriler": []}
```

Denetçinin cevabı her zaman aynı biçimdedir:

```
{"karar": "ONAY | DUZELT",
 "engeller": [],        // düzelmeden iş bitmiş sayılmaz
 "cilalar": [],         // küçük, engel olmayan öneriler
 "gercekHatalari": []}  // uydurma veri, yanlış hesap, boş test
```
