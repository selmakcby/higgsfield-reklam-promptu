# Sarma reklamı

Ek: sarma tabağının fotoğrafı. Tek fotoğraftan 15 saniyelik, 8 kesimli reel.

Kullanım: ChatGPT'de yeni sohbet aç, Higgsfield eklentisini seç, fotoğrafı ekle ve aşağıdaki promptun tamamını yapıştır. Sağ üstteki kopyala düğmesiyle tek seferde alabilirsin.

````text
Bu sohbette Higgsfield eklentisini kullan. Aşağıdaki işi baştan sona tek seferde, bana soru sormadan yap. Her adımın sonunda tek satır durum yaz, sonra bir sonraki adıma geç. Kredi onayı gerektiğinde: tüm adımlar için önceden onaylıyorum, üret. Bir adım hata verirse hatayı tek cümleyle yaz, bir kez yeniden dene, yine olmazsa kalan adımlara geç. Ses gerekiyorsa Higgsfield'ın hazır (preset) kadın seslerinden birini seç. Hiçbir üretimde gerçek marka logosu kullanma. Ekteki fotoğraf benim çektiğim sarma tabağıdır; reklamın ürünü budur.

AMAÇ: Rotterdam'daki kurgusal "Anneanne Sofrası" lokantası için, Hollanda'da yaşayan Türklere hitap eden 15 saniyelik dikey Instagram reel reklamı. Çıktı: İngilizce konuşmalı, İngilizce altyazılı, 9:16, 720p bitmiş video + SRT dosyası.

ADIM 1 — KARAKTER
Önce kendi görsel üretiminle şu karakteri çiz, sonra bu görseli Higgsfield'a yükle ve bu sohbette @Image1 olarak kullan. Kendi ürettiğin görseli Higgsfield'a aktaramıyorsan aynı prompt'u Higgsfield'da gpt_image_2_5 modeliyle üret ve onu @Image1 yap:
"Draw a full-body, straight-on, eye-level photo of one person: a lively Turkish woman in her late 20s, long dark wavy hair past her shoulders, light natural makeup, warm medium skin, oversized cream knit sweater with the sleeves pushed up, straight dark blue jeans, white leather sneakers, small silver hoop earrings, a thin silver ring on her right hand, standing relaxed with her weight on one leg, mid-laugh with teeth showing, looking straight at the camera. Seamless matte light-grey studio background with the floor blending into the wall, soft even high-key light, gentle grounded shadow, photorealistic, natural skin texture, razor-sharp from head to shoes, the entire outfit and both feet visible. No text, no logo, no props. Portrait 3:4."

ADIM 2 — ÜRÜN REFERANSI
Ekteki sarma fotoğrafını Higgsfield'a yükle ve @Image2 olarak kullan.

ADIM 3 — REEL KAYNAK VİDEOSU
Higgsfield'da Seedance 2.5 ile üret: duration 15, aspect_ratio 9:16, resolution 720p, generate_audio true, mode omni_reference, medias = [@Image1 karakter, @Image2 sarma]. Konuşma İNGİLİZCE. Prompt'u aynen gönder, kısaltma:

"Style & Mood: UGC iPhone aesthetic, a small homely Turkish lokanta in Rotterdam in daylight: a cream ceramic plate on a dark speckled stone counter, a folded grey linen cloth, a window with soft grey Dutch daylight, shelves of jars in the background, MIXED: starts SELFIE handheld, hard-cuts to STATIC locked-off, hard-cuts back to SELFIE handheld, POV alternates per cut, social media vertical format.
Dish detail (the exact plate from @Image2, keep it identical in every cut): a cream round plate piled high with slim hand-rolled vine-leaf sarma, each roll pencil-thin and tightly wrapped, dark olive green leaves with a glossy olive-oil sheen and visible leaf veins, a few rolls showing the rice filling at the ends, a small puddle of oil on the plate. Beside it a lemon cut in half and a small bowl of thick yogurt.
Narrative Summary: a creator (the woman from @Image1, same face, long dark wavy hair and oversized cream knit sweater throughout) tells Turks living in the Netherlands that someone in Rotterdam rolls sarma like their grandmother did, proves it by the thinness and the taste, and tells them to come on Sunday and take a pot home, performed by a natural, engaged creator, genuine reactions, warm and a little nostalgic, never staged screaming energy.
Cut 1 (0.0-1.9s, SELFIE): candid handheld iPhone zoom-in toward her face, a tiny overshoot-and-correct, she is already mid-turn toward the lens with a knowing half-smile, the jars and window blurred behind her, first word lands as the zoom settles. Hard cut to.
Cut 2 (1.9-3.8s, STATIC): locked-off frame at counter height, an older woman's hands with a thin gold ring set the full plate of sarma down, then place a lemon half beside it, a few drops of oil run down the pile. Hard cut to.
Cut 3 (3.8-5.6s, SELFIE): close handheld, she picks up one roll between two fingers and holds it right in front of the lens to show how thin it is, turns it slowly, nods. Hard cut to.
Cut 4 (5.6-7.5s, STATIC-CLOSE): locked macro on the plate, a hand squeezes the lemon half over the rolls, juice beads on the glossy leaves, one deliberate slow camera push-in, otherwise static. Hard cut to.
Cut 5 (7.5-9.4s, SELFIE): handheld, she bites a roll in half, chews with eyes closed, one slow exhale through the nose, then eyes open to the lens, a small emotional nod, a quick thumb-wipe at the corner of her mouth. Hard cut to.
Cut 6 (9.4-11.2s, STATIC): locked wide frame across the counter, the plate in the foreground, she dips the other half of the roll into the yogurt bowl and lifts it, yogurt dripping, the grey daylight soft on the window. Hard cut to.
Cut 7 (11.2-13.1s, STATIC-CLOSE): locked macro on the pile of sarma, the bitten roll placed back showing the rice and herb filling inside, leaf veins sharp in focus. Then she walks toward the camera and reaches past the lens, the frame lifts, shakes for a beat and becomes handheld again.
Cut 8 (13.1-15.0s, SELFIE): her face close and slightly wide-angled, she holds the plate up beside her cheek with both hands, one closed-mouth grin, a tiny shrug, then the last line to the lens.
Audio: She speaks to camera in English, iPhone microphone audio with natural room tone, a quiet lokanta, the ceramic plate set down in Cut 2, the lemon squeeze in Cut 4, a soft bite in Cut 5. [*soft exhale*] "Miss your grandmother's sarma in the Netherlands? Every one rolled by hand, thin as a pencil. Olive oil, lemon, yogurt. In Rotterdam, on Sundays. Take a pot home. Anneanne Sofrasi."
Performance: calm, warm register; at least one unguarded beat, in Cut 5 the nod is a little too emotional and she laughs at herself in Cut 8; movements land between phrases, never on a key word; one closed-mouth beat in Cut 8 before the last line.
Facial features clear and undistorted, consistent clothing and hairstyle throughout, the same woman in every selfie cut. Shot on iPhone, natural lighting, social media aesthetic, handheld micro-shake during selfie cuts, locked-off frozen frame during static-camera cuts, an opening candid handheld iPhone zoom-in then steady. No on-screen text, no subtitles, no captions, no watermarks, no real brand logos anywhere, no legible text on any object, no cinematic grade, no film grain, no bokeh, no lens flare, no fisheye, no slow motion, no beauty filter, no third arm, no extra hands, no duplicated limbs, no deformed hands, no morphing food, no people other than the creator and an older woman's hands."

Video tamamlanana kadar bekle (5-8 dakika sürebilir). Tamamlanınca job id'sini yaz.

ADIM 4 — İNGİLİZCE ALTYAZI
ADIM 3 videosuna video-montage akışıyla altyazı yak. Konuşulan dil İngilizce. Altyazı metni kelimesi kelimesine şu (araç konuşmayı yazıya döküp bu metinle hizalasın): "Miss your grandmother's sarma in the Netherlands? Every one rolled by hand, thin as a pencil. Olive oil, lemon, yogurt. In Rotterdam, on Sundays. Take a pot home. Anneanne Sofrasi." Satır başına en fazla 3 kelime, alt-orta yerleşim, yüzü ve tabağı kapatmasın, kompakt beyaz yazı, siyah dış çizgi, arka plan kutusu yok, animasyon yok. UYARI: Bu adım daha önce denenmedi. Montaj akışı çalışmazsa altyazısız videoyu teslim et ve SRT dosyasını yine de üret (aynı metin, 15 saniyeye konuşma sırasına göre dağıtılmış 3 kelimelik satırlar); "ALTYAZI YAKILAMADI" diye açıkça yaz.

ADIM 5 — TESLİM
Sırayla ver: (1) karakter görseli, (2) kaynak video linki ve job id, (3) altyazılı final video linki, (4) SRT dosyası, (5) toplam harcanan kredi. Hiçbir adımı atlama; atlamak zorunda kaldıysan hangisi ve neden, tek cümle.
````
