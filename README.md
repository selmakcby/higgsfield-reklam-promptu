# Tek Promptla Reklam Videosu (ChatGPT + Higgsfield)

Bir yemek fotoğrafını ve tek bir promptu ChatGPT'ye ver; yaklaşık 10 dakika sonra 15 saniyelik, 8 kesimli, dikey bir reklam videosu çıkıyor. Bu depo, YouTube videomda kullandığım promptların tamamını ve hangi Higgsfield yeteneklerini açtığımı içerir.

Higgsfield'ı buradan dene: https://higgsfield.ai/s/higgsfield-ads-studio-yt-selma-builds-IaYxSW

## Promptlar

| Prompt | Ek | Ne üretir |
|---|---|---|
| [Sarma](promptlar/sarma.md) | sarma tabağının fotoğrafı | 15 sn reel, limon sıkma ve yoğurt detaylı |
| [İskender](promptlar/iskender.md) | iskender tabağının fotoğrafı | 15 sn reel, zirve anı: tereyağı dökülmesi |
| [Menü + 4 varyasyon](promptlar/menu-varyasyon.md) | karakter görseli + iskender fotoğrafı | kaynak reel + Ad Multiplier ile 4 farklı tabak |

Promptlardaki lokantalar kurgusaldır. Kendi işletmen ya da müşterin için lokanta adını, şehri, yemeği ve konuşma metnini değiştir.

## Nasıl kullanılır

1. ChatGPT'de yeni bir sohbet aç ve Higgsfield eklentisini seç.
2. Eklenti ayarlarında [kullandığım yetenekleri](yetenekler.md) açık tut.
3. Yemek fotoğrafını ekle. Fotoğrafta sadece yemek olsun: arkada insan, tabela ya da menü yazısı görünmesin.
4. Promptun tamamını yapıştır ve gönder. Gerisine dokunmana gerek yok.

## Promptun anatomisi

- **Kurallar en başta:** "bana soru sorma", "krediyi önceden onaylıyorum", "hata olursa bir kez dene". Yazmazsan ChatGPT her adımda soru sorar.
- **Karakter, bütün vücut:** sadece üst gövdeyi tarif edersen alt tarafı model uydurur. Karakteri önce görsel olarak üretip `@Image1` diye kaydediyorum. İdeali dört görünüm: yüzün önü, yüzün arkası, bütün vücudun önü ve arkası.
- **Ürün referansı:** fotoğraf `@Image2`. "Her planda birebir aynı tabak" demezsen 8 kesimin her birinde tabak değişir.
- **15 saniyede 8 sert kesim:** her 2 saniyede bir sahne değişir. Selfie ve sabit kamera dönüşümlü gider. Tek planlık video güzel olur ama reklam olmaz.
- **İzleyiciyi bağlayan anlar:** limon sıkma, sosa batırma, ayran, tereyağı dökme.
- **Konuşma ve ses efektleri:** konuşma metni her kesime göre yazılır; tabağın konma sesi, limonun sıkılma sesi gibi efektler adıyla belirtilir.
- **Yasaklılar:** ekranda yazı yok, logo yok, filtre yok, fazladan el yok. Gerçek bir reklamda yazıyı ve logoyu kurguda sen ekle.

## Bilmen gerekenler

- Videolar mükemmel değil. Üzerinde biraz revize gerekebilir.
- Türkçe konuşturmada model kelimeleri yutabiliyor, İngilizce daha iyi. Higgsfield'ın dublaj aracı da var ama ek kredi harcar.
- Kredi maliyeti her üretimden önce ekranda görünür. Rakamlar modele, süreye ve çözünürlüğe göre değişir.

## Lisans

Tüm hakları saklıdır. Promptları kendi reklam videolarını üretmek için kullanabilir, ürettiğin videoları kendi işinde ya da müşterin için kullanabilirsin. Promptların kendisini kopyalayıp yayınlamak ya da satmak için izin gerekir. Ayrıntı: [LICENSE](LICENSE).
