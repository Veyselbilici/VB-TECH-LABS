# TadFit – Web Sayfaları (vb-tech-labs.vercel.app)

Bu dosya, mağaza kayıtları için gereken herkese açık sayfaların metnidir. Her bölüm sitede ayrı bir sayfa olur. Mevcut site düzenine uygun dosya adları:

| Sayfa | Dosya | Adres (yayından sonra) | Nerede kullanılır |
|---|---|---|---|
| Tanıtım / indirme | `tadfit.html` | https://vb-tech-labs.vercel.app/tadfit.html | Mağaza "web sitesi" alanı |
| Gizlilik politikası | `privacy-tadfit.html` | https://vb-tech-labs.vercel.app/privacy-tadfit.html | Play + App Store gizlilik URL'si, uygulama içi |
| Kullanım koşulları (EULA) | `tadfit-terms.html` | https://vb-tech-labs.vercel.app/tadfit-terms.html | App Store abonelik açıklaması, paywall |
| Destek ve SSS | `tadfit-support.html` | https://vb-tech-labs.vercel.app/tadfit-support.html | App Store "Support URL" |
| Hesap ve veri silme | `tadfit-hesap-silme.html` | https://vb-tech-labs.vercel.app/tadfit-hesap-silme.html | Play Console "Veri silme" URL'si |

**Yayından önce doldurulacak yer tutucular** (köşeli parantez içinde):

| Yer tutucu | Açıklama |
|---|---|
| ~~`[VERİ SORUMLUSU]`~~ | Dolduruldu: Veysel Bilici |
| `[ADRES]` | KVKK için tebligat adresi (il/ilçe yeterli olabilir; hukukçuya sor) |
| ~~`Google (Gemini)`~~ | Dolduruldu: Google (Gemini) |
| ~~`[BARINDIRMA BÖLGESİ]`~~ | Dolduruldu: Avrupa Birliği – Frankfurt |

> Bu metinler uygulamanın bugünkü davranışına göre hazırlanmış taslaktır. Yayından önce bir KVKK/hukuk uzmanına okutman önerilir (docs/TADFIT_PROJE.md Bölüm 19). Uygulamaya yeni veri, SDK veya özellik eklendiğinde bu sayfalar da güncellenir.

---

## 1. `tadfit.html` – Tanıtım

### TadFit: Kalori ve Diyet Planı

**Tadından vazgeçmeden formda kal.**

TadFit; boyuna, kilona, hedefine ve alerjilerine göre kişisel beslenme planı hazırlayan ve günlük takibini kolaylaştıran bir beslenme ve kilo yönetimi uygulamasıdır.

- Günlük kalori ve makro hedefi (bilimsel formülle)
- Besin arama ve barkodla öğün kaydı
- Su ve kilo takibi, ilerleme grafikleri
- Alerjine uygun tarifler, kilerdeki malzemelerle tarif bulma, adım adım pişirme
- Seri, rozet ve haftalık meydan okumalar
- Premium AI: kişisel 7 günlük AI beslenme planı ve alışveriş listesi

[Google Play'den indir](https://play.google.com/store/apps/details?id=com.tadfit.app) · App Store (yakında)

[Gizlilik Politikası](privacy-tadfit.html) · [Kullanım Koşulları](tadfit-terms.html) · [Destek](tadfit-support.html) · [Hesap Silme](tadfit-hesap-silme.html)

*TadFit tıbbi bir cihaz değildir ve tıbbi tavsiyenin yerini tutmaz.*

---

## 2. `privacy-tadfit.html` – Gizlilik Politikası ve KVKK Aydınlatma Metni

**Son güncelleme:** 28 Ekim 2026

Bu metin, TadFit mobil uygulamasını ("Uygulama") kullanırken kişisel verilerinin nasıl işlendiğini 6698 sayılı Kişisel Verilerin Korunması Kanunu ("KVKK") kapsamında açıklar.

### 2.1 Veri sorumlusu
Veysel Bilici (bireysel geliştirici, VB Tech Labs), [ADRES]
İletişim: bilicisoftwaree@gmail.com

### 2.2 Hangi verileri işliyoruz?

| Veri | Örnek | Zorunlu mu |
|---|---|---|
| Kimlik ve iletişim | Ad soyad, e-posta, telefon (isteğe bağlı) | Ad ve e-posta zorunlu |
| Profil | Doğum tarihi, cinsiyet, dil tercihi | Evet |
| **Sağlık ve beslenme verisi (özel nitelikli)** | Boy, kilo, hedef kilo, aktivite düzeyi, beslenme tipi, alerjiler, "doktor takibi gerektiren bir durumun var mı" sorusunun evet/hayır cevabı, öğün/su/kilo kayıtları, aktivite kayıtları (tür, süre, yoğunluk, tahmini yakılan kalori), vücut ölçüleri | Uygulamanın çalışması için evet |
| İlerleme ve profil fotoğrafları (kendi yüklediğin, isteğe bağlı) | Kendi yüklediğin fotoğraflar | İsteğe bağlı |
| Uygulama içeriği | Favori tarifler, kiler listesi, alışveriş listesi, beslenme planları, geri bildirim mesajların | Kullanıma bağlı |
| Abonelik | Abonelik durumu, ürün, bitiş tarihi (kart bilgisi değil) | Abonelikte |
| Kullanım ve teknik veri | Uygulama içi etkileşimler (sağlık değeri içermez), çökme kayıtları | Evet |

Hastalık, ilaç veya tanı bilgisi **sorulmaz ve saklanmaz**. Konum verisi toplanmaz; yüklenen fotoğraflardaki konum bilgisi (EXIF) yüklemeden önce cihazında silinir.

### 2.3 Hangi amaçlarla ve hangi hukuki sebeple?

| Amaç | Hukuki sebep (KVKK m.5, m.6) |
|---|---|
| Hesap oluşturma, giriş, iki adımlı doğrulama | Sözleşmenin kurulması ve ifası |
| Kalori/makro hedefi hesaplama, kayıt tutma, ilerleme ve raporlar | **Sağlık verisi için açık rızan** |
| Kişisel AI beslenme planı (Premium AI) | **Açık rızan** |
| Abonelik yönetimi | Sözleşmenin ifası |
| Güvenlik, kötüye kullanımın önlenmesi, denetim kaydı | Meşru menfaat, hukuki yükümlülük |
| Uygulamanın geliştirilmesi (anonim kullanım analitiği, çökme raporları) | Meşru menfaat |
| AI özelliklerinin geliştirilmesi (anonimleştirilmiş kayıtlarla) | Yalnızca isteğe bağlı açık rızanla |
| Kampanya ve yenilik iletileri | Yalnızca isteğe bağlı ticari ileti onayınla |

Sağlık verisine verdiğin açık rızayı geri almak istersen hesabını silebilirsin (Bölüm 2.8). İsteğe bağlı rızaları uygulamada **Profil > Gizlilik ve verilerim** ekranından istediğin zaman açıp kapatabilirsin.

### 2.4 Yapay zekâ kullanımı
- Kalori ve makro değerleri yapay zekâdan alınmaz; besin veritabanından ve formülle hesaplanır.
- AI beslenme planı hazırlanırken AI hizmet sağlayıcısına (Google (Gemini)) **adın, e-postan ve telefonun gönderilmez**. Gönderilenler: anonim bir kimlik, yaş, cinsiyet, boy, kilo, hedef, beslenme tipi, alerjiler ve uygun besin listesi.
- Doktor takibi gerektiren bir durum bildiren veya vücut kitle indeksi güvenli aralığın dışında olan kullanıcılara AI plan hazırlanmaz.

### 2.5 Verileri kimlerle paylaşıyoruz? (Hizmet sağlayıcılar)

Verilerin satılmaz ve reklam amacıyla kullanılmaz. Uygulamada reklam yoktur. Veriler yalnızca hizmeti sunmak için aşağıdaki sağlayıcılarla, gerektiği kadar paylaşılır:

| Sağlayıcı | Amaç | Paylaşılan veri |
|---|---|---|
| Supabase (veritabanı, kimlik doğrulama, dosya depolama) | Barındırma | Hesap ve uygulama verileri (Avrupa Birliği – Frankfurt) |
| Google (Gemini) | AI beslenme planı | Bölüm 2.4'teki anonim veriler |
| RevenueCat, Apple App Store, Google Play | Abonelik | Kullanıcı kimliği, abonelik durumu |
| PostHog | Kullanım analitiği | Kullanıcı kimliği, uygulama içi etkileşimler (sağlık değeri yok) |
| Sentry | Çökme ve hata raporları | Teknik hata bilgisi (kişisel ve sağlık verisi ayıklanır) |
| Open Food Facts | Barkodla ürün bulma | Yalnızca barkod numarası (kişisel veri yok) |

Hukuken zorunlu olduğunda yetkili kamu kurumlarıyla paylaşılabilir.

### 2.6 Yurt dışına aktarım
Hizmet sağlayıcıların sunucuları yurt dışında bulunabilir. Bu aktarım KVKK m.9 kapsamında, açık rızan ve/veya standart sözleşme gibi Kanun'un öngördüğü güvencelerle yapılır.

### 2.7 Saklama süresi ve güvenlik
- Verilerin hesabın açık olduğu sürece saklanır.
- Hesabını sildiğinde tüm hesap verilerin, kayıtların ve fotoğrafların **kalıcı olarak silinir**. Yedeklerden en geç 30 gün içinde çıkar.
- Denetim kayıtlarında yalnızca anonim kullanıcı kimliği ve işlem türü kalır.
- Tüm bağlantılar şifrelidir (TLS). Her kullanıcı yalnızca kendi verisine erişebilir (satır düzeyinde güvenlik). Fotoğraflar özel alanda tutulur ve yalnızca sana, kısa süreli bağlantılarla gösterilir.
- Hatırlatma bildirimleri cihazında zamanlanır; bildirim metinlerinde kilo, kalori gibi kişisel değerler yer almaz.

### 2.8 Hakların (KVKK m.11)
Verilerinin işlenip işlenmediğini öğrenme, bilgi talep etme, amacını öğrenme, aktarıldığı kişileri bilme, düzeltme, silme, itiraz etme ve zararın giderilmesini isteme hakların vardır.
- **Verilerimi indir:** Uygulamada Profil > Gizlilik ve verilerim > Verilerimi indir (JSON dosyası).
- **Düzeltme:** Profil > Profil bilgileri ve Sağlık bilgileri.
- **Silme:** Profil > Hesabı sil, ya da [hesap silme sayfası](tadfit-hesap-silme.html).
- Diğer talepler için kayıtlı e-posta adresinden **bilicisoftwaree@gmail.com** adresine yaz. Talepler en geç 30 gün içinde yanıtlanır.
- Kişisel Verileri Koruma Kurulu'na şikâyet hakkın saklıdır.

### 2.9 Yaş sınırı
TadFit 18 yaş ve üzeri içindir. 18 yaşından küçüklerin kaydı kabul edilmez.

### 2.10 Değişiklikler
Bu politika değişirse güncel hali bu sayfada yayımlanır. Önemli değişikliklerde uygulama içinde bilgilendirilirsin.

---

### Privacy Policy (English summary)

**Last updated:** 28 October 2026 · Controller: Veysel Bilici (VB Tech Labs, individual developer) · Contact: bilicisoftwaree@gmail.com

**Data we collect**
- Account details: name, email, optional phone.
- Profile: date of birth, sex.
- Health and nutrition data (special category): height, weight, goal, activity, diet type, allergies, one yes/no follow-up question, meal, water and weight logs, activity logs (type, duration, intensity, estimated calories burned), body measurements.
- Optional progress photos and an optional profile photo; location metadata is removed on your device before upload.
- Subscription status.
- Usage analytics without any health values, and crash reports.

We do not ask for diseases, medications or diagnoses.

**Why we use it**
- To run the service under our contract with you.
- Health data is processed only with your explicit consent.
- Optional consents cover AI improvement and marketing; you can change them anytime in Profile > Privacy & my data.

**AI**
- Calories and macros come from a food database and formulas, never from AI.
- For AI meal plans, Google (Gemini) receives an anonymous ID and the nutrition-related data needed — never your name, email or phone.

**Service providers**
- Supabase: hosting.
- Google (Gemini): AI meal plans.
- RevenueCat, Apple and Google: subscriptions.
- PostHog: analytics.
- Sentry: crash reports.
- Open Food Facts: barcode lookups, sent the barcode number only.

We do not sell data and there are no ads.

**Retention and deletion**
- Your data is kept while your account exists.
- Deleting your account permanently erases it; backups clear within 30 days.
- Download your data or delete your account in the app, or see the [account deletion page](tadfit-hesap-silme.html).

**Your rights in the EU/EEA/UK (GDPR)**
- Legal bases: performance of our contract with you (Art. 6(1)(b)), your explicit consent for health data (Art. 9(2)(a)) and for the optional AI improvement and marketing uses (Art. 6(1)(a)), and legal obligations (Art. 6(1)(c)).
- You have the right to access, rectify, erase, restrict and object to processing of your data, to data portability, and to withdraw consent at any time without affecting earlier processing.
- Use the in-app tools (Profile > Privacy & my data: download, correct, delete) or write to bilicisoftwaree@gmail.com. We reply within one month.
- You can lodge a complaint with your local data protection authority.
- Data is hosted in the European Union (Frankfurt). If a provider processes data outside the EU/EEA, the transfer relies on safeguards such as the EU Standard Contractual Clauses.
- Controller: Veysel Bilici, VB Tech Labs.

**Age:** 18+ only.

---

## 3. `tadfit-terms.html` – Kullanım Koşulları (EULA)

**Son güncelleme:** 26 Ekim 2026

TadFit'i indirerek veya kullanarak bu koşulları kabul etmiş olursun.

1. **Hizmet.** TadFit, beslenme ve kilo yönetimi için kalori/makro hesabı, kayıt, tarif ve kişisel plan sunan bir yazılımdır.
2. **Tıbbi uyarı.** TadFit tıbbi bir cihaz değildir. Herhangi bir hastalığı teşhis, tedavi veya önleme amacı taşımaz ve sağlık profesyonelinin tavsiyesinin yerini tutmaz. Hamileysen, emziriyorsan, yeme bozukluğu geçmişin veya doktor takibi gerektiren bir durumun varsa beslenme değişikliğinden önce doktoruna danış. Uygulama bu durumdaki kullanıcılara AI beslenme planı hazırlamaz.
3. **Uygunluk.** TadFit'i kullanmak için 18 yaşını doldurmuş olmalısın. Hesap bilgilerinin doğru ve güncel olmasından, şifrenin gizliliğinden sen sorumlusun.
4. **AI içerikleri.** AI tarafından hazırlanan plan ve öneriler bilgilendirme amaçlıdır. Güvenlik kurallarıyla sınırlandırılmıştır (güvenli alt kalori sınırı, haftalık kilo kaybı hızı sınırı, alerjen içeren besinlerin çıkarılması) ancak hatasız olduğu garanti edilmez. Kendi sağlık durumunu göz önünde bulundurarak değerlendir.
5. **Premium AI aboneliği.**
   - Aylık veya yıllık, **otomatik yenilenen** bir aboneliktir. Fiyat satın alma ekranında mağazanın yerel fiyatıyla gösterilir.
   - Ödeme, satın alma onayında Apple Kimliği / Google Play hesabından alınır.
   - Dönem bitmeden en az 24 saat önce iptal edilmezse abonelik aynı süre ve fiyatla yenilenir.
   - Ücretsiz deneme sunuluyorsa, deneme bitmeden iptal edilmediğinde ücretli abonelik başlar.
   - Aboneliğini App Store veya Google Play hesap ayarlarından yönetebilir ve iptal edebilirsin. Hesabını silmek aboneliği iptal etmez.
   - İadeler Apple ve Google'ın iade politikalarına tabidir.
6. **Kabul edilemez kullanım.** Uygulamayı tersine mühendislik, otomatik erişim, başkası adına hesap açma veya hizmeti aksatacak şekilde kullanmak yasaktır.
7. **Fikri mülkiyet.** Uygulama, tasarımı ve içerikleri VB Tech Labs'a aittir. Sana kişisel ve ticari olmayan kullanım için devredilemez bir lisans verilir.
8. **Apple'a özgü hükümler.** Bu lisans yalnızca seninle VB Tech Labs arasındadır; Apple bu uygulamanın bakımından ve desteğinden sorumlu değildir. Apple'ın Standart Son Kullanıcı Lisans Sözleşmesi (EULA) de geçerlidir: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
9. **Sorumluluğun sınırlandırılması.** Yürürlükteki hukukun izin verdiği ölçüde, uygulamanın kullanımından doğan dolaylı zararlardan sorumluluk kabul edilmez.
10. **Fesih.** Hesabını istediğin zaman silebilirsin. Koşulların ihlali hâlinde hesap askıya alınabilir.
11. **Değişiklikler ve hukuk.** Koşullar güncellenebilir; güncel hali bu sayfadadır. Türkiye Cumhuriyeti hukuku uygulanır.
12. **İletişim.** bilicisoftwaree@gmail.com

---

## 4. `tadfit-support.html` – Destek ve SSS

**İletişim:** bilicisoftwaree@gmail.com — mesajında uygulama sürümünü ve cihaz modelini yaz. Uygulama içinden de **Profil > Yardım ve erişilebilirlik > Geri bildirim** ile yazabilirsin. Lütfen şifre veya sağlık bilgisi gönderme.

**Sık sorulanlar**

- **Kalori değerleri nereden geliyor?** Besin veritabanından ve formülle hesaplanır. AI kalori uydurmaz; yalnızca seçim ve öneri yapar.
- **AI planı neden göremiyorum?** AI plan Premium AI paketindedir. Ayrıca güvenlik için bazı durumlarda (ör. doktor takibi gereken bir durum) AI plan hazırlanmaz; öğün, su ve kilo kaydını kullanmaya devam edebilirsin.
- **Alerjilerim nasıl korunuyor?** Seçtiğin alerjenleri içeren besin ve tarifler plana, tarif listesine ve önerilere girmez.
- **Verilerimi kim görebilir?** Yalnızca sen. Fotoğrafların özel alanda tutulur.
- **Aboneliği nasıl iptal ederim?** App Store veya Google Play abonelik ayarlarından. Uygulamada Profil > Abonelik ekranındaki "Mağazada yönet" bağlantısını kullanabilirsin.
- **Satın alımımı başka telefonda nasıl açarım?** Aynı hesapla giriş yap, Profil > Abonelik > "Satın alımları geri yükle".
- **Bildirim gelmiyor.** Telefon ayarlarından TadFit bildirim iznini aç; uygulamada Profil > Bildirimler'den hatırlatmaları kontrol et. 22:30–08:00 arası sessiz saatlerde bildirim gönderilmez.
- **Hesabımı nasıl silerim?** Bkz. [Hesap ve veri silme](tadfit-hesap-silme.html).

**Support (English):** Email bilicisoftwaree@gmail.com with your app version and device model, or use Profile > Help & accessibility > Feedback in the app. Never send passwords or health details.

---

## 5. `tadfit-hesap-silme.html` – Hesap ve Veri Silme

**Uygulama:** TadFit: Kalori ve Diyet Planı (VB Tech Labs) · Paket adı: com.tadfit.app

### Uygulama içinden (önerilen, anında)
1. TadFit'i aç, **Bugün** ekranında sağ üstteki profil simgesine dokun.
2. En alttaki **Hesabı sil**'i seç.
3. Şifreni gir ve **Hesabımı kalıcı olarak sil** ile onayla.

Hesabın ve tüm verilerin hemen, kalıcı olarak silinir.

### Uygulamaya erişemiyorsan (e-posta ile)
TadFit'e kayıtlı e-posta adresinden **bilicisoftwaree@gmail.com** adresine **"Hesap silme talebi – TadFit"** konulu bir e-posta gönder. Kimliğini doğrulamak için yalnızca kayıtlı adresinden gelen talepler işleme alınır. Talebin en geç **30 gün** içinde yerine getirilir ve sana e-postayla bildirilir.

### Neler silinir?
- Profil ve hesap bilgileri (ad, e-posta, telefon, doğum tarihi, cinsiyet)
- Sağlık bilgileri, hedefler ve alerjiler
- Öğün, su ve kilo kayıtları, vücut ölçüleri ve **ilerleme fotoğrafları**
- Beslenme planları, alışveriş listesi, favoriler, kiler, rozetler, bildirim tercihleri, geri bildirim mesajları

### Neler kalır?
- Denetim kayıtlarında yalnızca anonim kullanıcı kimliği ve işlem türü (kişisel veya sağlık verisi içermez), güvenlik ve yasal yükümlülükler için.
- Sistem yedeklerinde veriler en geç 30 gün içinde kendiliğinden silinir.
- Mağaza satın alma kayıtları Apple / Google tarafından kendi politikalarına göre tutulur.

**Önemli:** Hesabını silmek aboneliğini iptal etmez. Ücretlendirilmemek için önce App Store veya Google Play'den aboneliğini iptal et.

**Silmeden önce:** Profil > Gizlilik ve verilerim > **Verilerimi indir** ile verilerinin bir kopyasını alabilirsin.

---

### Account & data deletion (English)
- **In the app (immediate):** Open TadFit, tap your profile icon on the Today screen, choose **Delete account**, enter your password and confirm. Everything is deleted permanently and immediately.
- **Without app access:** Email bilicisoftwaree@gmail.com from your registered address with the subject "Account deletion request – TadFit". We complete it within 30 days.
- **What is deleted:** your profile, health details, meal, water and weight logs, measurements, progress photos, plans and all other app data.
- **What remains:** anonymous audit records only (no personal or health data). Backups clear within 30 days.
- **Subscriptions:** deleting your account does not cancel your subscription; cancel it in the App Store or Google Play first.
