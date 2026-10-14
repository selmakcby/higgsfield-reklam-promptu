# İskender reklamı

Ek: iskender tabağının fotoğrafı. Zirve anı: masada tereyağı dökülmesi.

Kullanım: ChatGPT'de yeni sohbet aç, Higgsfield eklentisini seç, fotoğrafı ekle ve aşağıdaki promptun tamamını yapıştır. Sağ üstteki kopyala düğmesiyle tek seferde alabilirsin.

````text
Bu sohbette Higgsfield eklentisini kullan. Aşağıdaki işi baştan sona tek seferde, bana soru sormadan yap. Her adımın sonunda tek satır durum yaz, sonra bir sonraki adıma geç. Kredi onayı gerektiğinde: tüm adımlar için önceden onaylıyorum, üret. Bir adım hata verirse hatayı tek cümleyle yaz, bir kez yeniden dene, yine olmazsa kalan adımlara geç. Ses gerekiyorsa Higgsfield'ın hazır (preset) kadın seslerinden birini seç. Hiçbir üretimde gerçek marka logosu kullanma. Ekteki fotoğraf benim çektiğim İskender tabağıdır; reklamın ürünü budur.

AMAÇ: Rotterdam'daki kurgusal "Bursa Sofrası" kebapçısı için, Hollanda'da yaşayan Türklere hitap eden 15 saniyelik dikey Instagram reel reklamı. Zirve anı: masada tereyağı dökülmesi. Çıktı: İngilizce konuşmalı, İngilizce altyazılı, 9:16, 720p bitmiş video + SRT dosyası.

ADIM 1 — KARAKTER
Önce kendi görsel üretiminle şu karakteri çiz, sonra bu görseli Higgsfield'a yükle ve bu sohbette @Image1 olarak kullan. Kendi ürettiğin görseli Higgsfield'a aktaramıyorsan aynı prompt'u Higgsfield'da gpt_image_2_5 modeliyle üret ve onu @Image1 yap:
"Draw a full-body, straight-on, eye-level photo of one person: a lively Turkish woman in her late 20s, long dark wavy hair past her shoulders, light natural makeup, warm medium skin, oversized cream knit sweater with the sleeves pushed up, straight dark blue jeans, white leather sneakers, small silver hoop earrings, a thin silver ring on her right hand, standing relaxed with her weight on one leg, mid-laugh with teeth showing, looking straight at the camera. Seamless matte light-grey studio background with the floor blending into the wall, soft even high-key light, gentle grounded shadow, photorealistic, natural skin texture, razor-sharp from head to shoes, the entire outfit and both feet visible. No text, no logo, no props. Portrait 3:4."

ADIM 2 — ÜRÜN REFERANSI
Ekteki İskender fotoğrafını Higgsfield'a yükle ve @Image2 olarak kullan.

ADIM 3 — REEL KAYNAK VİDEOSU
Higgsfield'da Seedance 2.5 ile üret: duration 15, aspect_ratio 9:16, resolution 720p, generate_audio true, mode omni_reference, medias = [@Image1 karakter, @Image2 İskender]. Konuşma İNGİLİZCE. Prompt'u aynen gönder, kısaltma:

"Style & Mood: UGC iPhone aesthetic, a busy Turkish kebab house at lunch: light oak tables, cream walls, warm overhead spots, a glass-fronted doner grill glowing in the background, MIXED: starts SELFIE handheld, hard-cuts to STATIC locked-off, hard-cuts back to SELFIE handheld, POV alternates per cut, social media vertical format.
Dish detail (the exact plate from @Image2, keep it identical in every cut): a hammered oval copper plate; thin strips of doner meat laid over cubes of pide bread, everything drowned in a glossy tomato-butter sauce; two grilled tomato halves and one long grilled green pepper on top; a thick white scoop of strained yogurt on the left rim; a fork resting on the right rim. Around it on the oak table: a copper ayran cup with thick white foam overflowing the rim, a small white dish of red onion rings dusted with sumac and parsley, a white dish of shredded red cabbage and carrot salad, a plate of folded lavash bread with a grilled pepper, a pickle on a saucer.
Narrative Summary: a creator (the woman from @Image1, same face, long dark wavy hair and oversized cream knit sweater throughout) shows her followers in the Netherlands that a real Bursa-style Iskender exists in Rotterdam, with the butter-pour ritual as the peak moment, and tells them to come tonight, performed by a natural, engaged creator, genuine reactions, lively but human, never staged screaming energy.
Cut 1 (0.0-1.9s, SELFIE): candid handheld iPhone zoom-in toward her face, a tiny overshoot-and-correct, she is already mid-turn toward the lens with one palm raised like stopping traffic, the glowing doner grill blurred behind her, first word lands as the zoom settles. Hard cut to.
Cut 2 (1.9-3.8s, STATIC): locked-off frame at table height, a waiter's hands in a white sleeve set the heavy copper plate down with a soft metallic thud, sauce still bubbling at the edges, the foam on the ayran cup trembles. Hard cut to.
Cut 3 (3.8-5.6s, SELFIE): close handheld, she leans in over the plate, points with her index finger at the pide under the meat, then at the tomato sauce, talking fast, one eyebrow raised. Hard cut to.
Cut 4 (5.6-7.5s, STATIC-CLOSE): locked macro on the copper plate, from the top of the frame a small copper pan tilts and pours sizzling browned butter in a thin stream over the meat, the butter hisses and foams as it hits the sauce, tiny spatters jump, one deliberate slow camera push-in, otherwise static. Hard cut to.
Cut 5 (7.5-9.4s, SELFIE): handheld, her mouth open in a silent wow, she fans the sizzle smoke toward her face with one hand and breathes it in, eyes close, then she looks straight into the lens and nods once, slowly. Hard cut to.
Cut 6 (9.4-11.2s, STATIC): locked wide frame across the table, the full spread in the foreground, she tears a piece of lavash, drags it through the butter and sauce, lifts it with a strip of doner and a bit of yogurt, sauce dripping back onto the copper. Hard cut to.
Cut 7 (11.2-13.1s, STATIC-CLOSE): locked macro on the copper ayran cup, she lifts it and the thick foam leaves a white line on her upper lip, next to it the sumac onions sharp in focus. Then she walks toward the camera and reaches past the lens, the frame lifts, shakes for a beat and becomes handheld again.
Cut 8 (13.1-15.0s, SELFIE): her face close and slightly wide-angled, she wipes the foam line with the back of her hand and laughs, holds the copper cup up beside her cheek, one closed-mouth grin, then the last line to the lens.
Audio: She speaks to camera in English, iPhone microphone audio with natural room tone, the clatter of a busy kebab house, the metallic thud of the copper plate in Cut 2, a loud butter sizzle and hiss in Cut 4, a soft slurp of ayran in Cut 7. [*sharp inhale*] "Looking for a real Iskender in the Netherlands? Copper plate, pide underneath, doner on top. And now... the butter. Hear that sizzle? Foamy ayran on the side. Bursa Sofrasi, Delfshaven. Come tonight."
Performance: the butter pour in Cut 4 is the peak, the line "And now..." pauses right before it and "the butter" lands on the sizzle; at least one unguarded beat, the foam moustache in Cut 7 and her laugh in Cut 8 are genuine; movements land between phrases, never on a key word.
Facial features clear and undistorted, consistent clothing and hairstyle throughout, the same woman in every selfie cut. Shot on iPhone, natural lighting, social media aesthetic, handheld micro-shake during selfie cuts, locked-off frozen frame during static-camera cuts, an opening candid handheld iPhone zoom-in then steady. No on-screen text, no subtitles, no captions, no watermarks, no real brand logos anywhere, no legible text on any object, no cinematic grade, no film grain, no bokeh, no lens flare, no fisheye, no slow motion, no beauty filter, no third arm, no extra hands, no duplicated limbs, no deformed hands, no morphing food, no people other than the creator and a waiter's hands."

Video tamamlanana kadar bekle (5-8 dakika sürebilir). Tamamlanınca job id'sini yaz.

ADIM 4 — İNGİLİZCE ALTYAZI
ADIM 3 videosuna video-montage akışıyla altyazı yak. Konuşulan dil İngilizce. Altyazı metni kelimesi kelimesine şu (araç konuşmayı yazıya döküp bu metinle hizalasın): "Looking for a real Iskender in the Netherlands? Copper plate, pide underneath, doner on top. And now... the butter. Hear that sizzle? Foamy ayran on the side. Bursa Sofrasi, Delfshaven. Come tonight." Satır başına en fazla 3 kelime, alt-orta yerleşim, yüzü ve bakır tabağı kapatmasın, kompakt beyaz yazı, siyah dış çizgi, arka plan kutusu yok, animasyon yok. UYARI: Bu adım daha önce denenmedi. Montaj akışı çalışmazsa altyazısız videoyu teslim et ve SRT dosyasını yine de üret (aynı metin, 15 saniyeye konuşma sırasına göre dağıtılmış 3 kelimelik satırlar); "ALTYAZI YAKILAMADI" diye açıkça yaz.

ADIM 5 — TESLİM
Sırayla ver: (1) karakter görseli, (2) kaynak video linki ve job id, (3) altyazılı final video linki, (4) SRT dosyası, (5) toplam harcanan kredi. Hiçbir adımı atlama; atlamak zorunda kaldıysan hangisi ve neden, tek cümle.
````
