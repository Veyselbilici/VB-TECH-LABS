# PeriyoDoz — Gizlilik Politikası

**Son güncelleme:** 10 Eylül 2026
**Yürürlük tarihi:** 10 Eylül 2026

> ⚠️ **YAYINLAMADAN ÖNCE DOLDURULMASI GEREKENLER** (bu blok yayından kaldırılmalı)
> - `[VERİ SORUMLUSU]` → gerçek ad/soyad veya şirket unvanı
> - `[ADRES]` → tebligat adresi (KVKK aydınlatma yükümlülüğü için zorunlu)
> - `[FIRESTORE BÖLGESİ]` → Firebase Console → Firestore → konum (ör. `eur3`)
> - Uygulama App Store/Play'de yayınlandıktan sonra mağaza bağlantılarını ekle

---

## 1. Bu politika kimin ve neyin hakkında

PeriyoDoz ("Uygulama"), ilaç hatırlatma ve aile sağlık takibi amacıyla geliştirilmiş bir mobil uygulamadır. Bu politika, Uygulama'yı kullandığınızda hangi verilerin işlendiğini, neden işlendiğini, kimlerle paylaşıldığını ve haklarınızı açıklar.

**Veri sorumlusu:** `[VERİ SORUMLUSU]`
**İletişim:** destek@periyodoz.com
**Adres:** `[ADRES]`

Bu politika 6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) ve Avrupa Birliği Genel Veri Koruma Tüzüğü (GDPR) kapsamında hazırlanmıştır.

---

## 2. Önemli uyarı: Uygulama tıbbi cihaz değildir

PeriyoDoz **tıbbi tavsiye, teşhis veya tedavi sağlamaz**. İlaç etkileşim kontrolü dahil tüm özellikler, sınırlı sayıda bilinen etkileşim kategorisine dayanan otomatik bir hatırlatma/bilgilendirme aracıdır ve eksiksiz değildir. Uygulamada bir uyarı çıkmaması, hiçbir risk olmadığı anlamına gelmez.

**İlaçlarınızla ilgili her kararı doktorunuza veya eczacınıza danışarak alın.**

---

## 3. İşlenen veriler

### 3.1 Hesap ve kimlik verileri

| Veri | Nasıl toplanır | Neden |
|---|---|---|
| E-posta adresi | Kayıt sırasında siz girersiniz | Hesap oluşturma, giriş, şifre sıfırlama |
| Şifre | Kayıt sırasında siz girersiniz | Kimlik doğrulama. Şifreniz **bize hiçbir zaman ulaşmaz**; Google Firebase Authentication tarafından şifrelenmiş biçimde saklanır ve tarafımızdan görülemez |
| Ad | İsteğe bağlı, siz girersiniz | Uygulama içi kişiselleştirme, bakıcı bildirimlerinde kimin adına gönderildiğini belirtme |
| Yaş, cinsiyet | İsteğe bağlı, siz girersiniz | Özelliklerin uyarlanması (ör. döngü takibi yalnızca ilgili kullanıcılara gösterilir) |
| Telefon numarası | İsteğe bağlı, siz girersiniz | Yalnızca cihazınızda ve hesabınızda saklanır; SMS gönderimi için kullanılmaz |
| Profil fotoğrafı | İsteğe bağlı, siz yüklersiniz | Uygulama içi profil görseli |

**Anonim kullanım:** Uygulamayı hesap açmadan da kullanabilirsiniz. Bu durumda cihazınıza kimliksiz (anonim) bir kimlik atanır ve verileriniz bu kimlikle ilişkilendirilir. E-posta ile kayıt olduğunuzda mevcut verileriniz korunarak bu kimlik hesabınıza yükseltilir.

### 3.2 Sağlık verileri (özel nitelikli kişisel veri)

Aşağıdaki veriler **yalnızca siz girdiğiniz takdirde** işlenir. Uygulama bu verileri cihaz sensörlerinden veya üçüncü taraflardan otomatik olarak toplamaz.

- **İlaç bilgileri:** ilaç adı, dozaj, kullanım saatleri, hatırlatma günleri, stok miktarı, etken madde, kullanım amacı, reçete notları, ilaç kutusu fotoğrafı
- **Kullanım kayıtları:** ilacı aldığınız/atladığınız zamanlar, düzenlilik istatistikleri
- **Ölçümler:** tansiyon, kilo, kan şekeri değerleri ve ölçüm tarihleri
- **Sağlık günlüğü:** ağrı, yan etki, ruh hali, uyku, enerji, stres gibi serbest metin notları
- **Döngü takibi:** âdet günleri, ruh hali, semptomlar, lekelenme, gebelik testi sonucu ve stres/uyku/egzersiz/beslenme faktörleri
- **Su tüketimi ve uyku hedefleri**

Bu veriler KVKK m.6 anlamında **özel nitelikli kişisel veri** sayılır ve yalnızca **açık rızanıza** dayanarak işlenir. Uygulamayı kullanmayı bırakarak veya hesabınızı silerek bu rızayı her zaman geri çekebilirsiniz.

### 3.3 Aile üyelerine ait veriler

Uygulama, aile üyeleri (çocuk, ebeveyn, eş) için alt profiller oluşturmanıza izin verir. Bu profillere girdiğiniz veriler **başka bir kişiye aittir**.

Bir aile üyesi için profil oluşturarak, o kişinin verilerini girmeye yetkili olduğunuzu (veli/vasi olduğunuzu ya da kişinin rızasını aldığınızı) beyan etmiş olursunuz. Bu verilerin doğruluğu ve hukuka uygunluğu sizin sorumluluğunuzdadır.

### 3.4 Bakıcı bağlantısı

Bir aile üyesini "bakıcı" olarak bağladığınızda:
- Size özel, tek kullanımlık bir davet kodu üretilir
- Kodu kullanan kişi, **sizin belirlediğiniz kapsamda** verilerinizi görüntüleyebilir ("yalnızca ilaçlar" veya "tam paylaşım")
- Bir dozu atladığınızda bakıcınıza bildirim gönderilir

Bu paylaşımı istediğiniz zaman durdurabilirsiniz. Bakıcı erişimi teknik olarak sunucu tarafında doğrulanır; hiçbir kullanıcı davet kodu olmadan başkasının verisine erişemez.

### 3.5 Otomatik toplanan teknik veriler

- **Cihaz ve uygulama bilgileri:** işletim sistemi sürümü, uygulama sürümü, cihaz modeli, dil
- **Kullanım analitiği:** hangi ekranların görüntülendiği, giriş/kayıt/abonelik olayları (içerik değil, yalnızca olay adı)
- **Çökme raporları:** uygulama çöktüğünde hata yığını ve çökme öncesi ekran geçişleri
- **Bildirim jetonu (push token):** bakıcı bildirimlerini iletebilmek için
- **Reklam kimliği:** yalnızca ücretsiz sürümde, reklam gösterimi ve sahtecilik önleme amacıyla

Analitik ve çökme raporları **sağlık verilerinizin içeriğini içermez** — ilaç adlarınız, ölçümleriniz veya günlük notlarınız bu raporlara dahil edilmez.

### 3.6 Cihaz izinleri

| İzin | Ne için | Reddedilirse |
|---|---|---|
| **Kamera** | İlaç kutusu fotoğrafı çekmek, barkod okumak | Fotoğrafı galeriden seçebilir veya ilacı elle ekleyebilirsiniz |
| **Fotoğraflar** | Galeriden ilaç/profil fotoğrafı seçmek | Uygulama çalışmaya devam eder |
| **Bildirimler** | İlaç hatırlatmaları ve bakıcı uyarıları | Hatırlatma alamazsınız — bu, uygulamanın temel işlevidir |
| **İzleme (yalnızca iOS)** | Kişiselleştirilmiş reklam | Reklamlar kişiselleştirilmemiş olarak gösterilir |

Tüm izinler isteğe bağlıdır ve cihaz ayarlarınızdan istediğiniz zaman geri alınabilir.

---

## 4. Verilerin işlenme amaçları ve hukuki dayanağı

| Amaç | Hukuki dayanak (KVKK / GDPR) |
|---|---|
| Hesap oluşturma ve kimlik doğrulama | Sözleşmenin ifası |
| İlaç hatırlatmalarının kurulması ve gönderilmesi | Açık rıza (sağlık verisi) |
| Sağlık verilerinin saklanması ve cihazlar arası senkronizasyonu | Açık rıza |
| Bakıcılarla paylaşım | Açık rıza |
| Abonelik satın alma ve doğrulama | Sözleşmenin ifası |
| Reklam gösterimi (ücretsiz sürüm) | Meşru menfaat / açık rıza (kişiselleştirilmiş reklam için) |
| Hata ayıklama, çökme analizi, güvenlik | Meşru menfaat |
| Yasal yükümlülüklerin yerine getirilmesi | Hukuki yükümlülük |

---

## 5. Verilerin paylaşıldığı üçüncü taraflar

Verilerinizi **satmıyoruz** ve pazarlama amacıyla üçüncü taraflarla paylaşmıyoruz. Uygulamanın çalışabilmesi için aşağıdaki hizmet sağlayıcılar kullanılmaktadır:

| Sağlayıcı | Ne aktarılıyor | Amaç |
|---|---|---|
| **Google Firebase** (Authentication, Firestore, Storage, Cloud Functions, Remote Config) | Hesap bilgileri, sağlık verileri, fotoğraflar | Verilerin saklanması ve cihazlar arası senkronizasyonu |
| **Google Firebase Analytics** | Ekran görüntülemeleri, olay adları, cihaz bilgisi | Kullanım istatistikleri |
| **Google Firebase Crashlytics** | Hata yığını, cihaz bilgisi, kullanıcı kimliği | Çökme tespiti ve giderilmesi |
| **Google Cloud Vision** | **İlaç kutusu fotoğrafı** (yalnızca siz tarama yaptığınızda) | Kutu üzerindeki yazının okunması (OCR). Fotoğraf bu işlem için Google'a gönderilir |
| **Google AdMob** | Reklam kimliği, yaklaşık konum (ülke düzeyi), cihaz bilgisi | Reklam gösterimi (**yalnızca ücretsiz sürümde**) |
| **RevenueCat** | Anonim kullanıcı kimliği, satın alma makbuzu | Abonelik durumunun doğrulanması |
| **Apple App Store / Google Play** | Satın alma bilgileri | Ödemenin alınması. **Ödeme kartı bilgileriniz bize hiçbir zaman ulaşmaz** |
| **Expo Push Service** | Bildirim jetonu, bildirim metni | Bakıcı bildirimlerinin iletilmesi |

Her sağlayıcı yalnızca kendi işlevi için gerekli veriyi alır. Sağlık verilerinizin tamamı yalnızca Firebase'de saklanır; diğer sağlayıcılara aktarılmaz.

### Yurt dışına aktarım

Firebase ve diğer hizmetler Google LLC tarafından işletilmektedir ve verileriniz yurt dışındaki sunucularda saklanabilir. Veritabanı bölgemiz `[FIRESTORE BÖLGESİ]`, sunucu fonksiyonlarımız ise Avrupa (`europe-west1`) bölgesinde çalışmaktadır. Bu aktarım, KVKK m.9 kapsamında açık rızanıza dayanmaktadır.

---

## 6. Reklamlar

Ücretsiz sürümde Google AdMob üzerinden reklam gösterilir.

- **Premium aboneliğe geçtiğinizde reklamlar tamamen kaldırılır.**
- Avrupa Birliği ve Birleşik Krallık'taki kullanıcılara, reklam kişiselleştirmesi için Google'ın onay formu (UMP) gösterilir.
- iOS'ta, uygulama açıldığında izleme izni sorulur. İzin vermezseniz reklamlar kişiselleştirilmez.
- Reklam tercihlerinizi cihaz ayarlarından (Android: Ayarlar → Google → Reklamlar / iOS: Ayarlar → Gizlilik → İzleme) istediğiniz zaman değiştirebilirsiniz.
- **Sağlık verileriniz reklam hedeflemesi için asla kullanılmaz ve reklam ağlarıyla paylaşılmaz.**

---

## 7. Saklama süresi

- Verileriniz, hesabınız açık kaldığı sürece saklanır.
- Hesabınızı sildiğinizde tüm sağlık verileriniz (ilaçlar, ölçümler, günlük kayıtları, aile profilleri ve hesap bilgileriniz) **kalıcı olarak silinir**.
- Çökme raporları ve toplu (kimliksizleştirilmiş) analitik veriler, hizmet sağlayıcının saklama politikası uyarınca en fazla 14 ay saklanır.
- Yasal olarak saklanması zorunlu kayıtlar (ör. fatura kayıtları) ilgili mevzuatın öngördüğü süre boyunca saklanır.

---

## 8. Haklarınız

KVKK m.11 ve GDPR uyarınca şu haklara sahipsiniz:

- Kişisel verilerinizin işlenip işlenmediğini **öğrenme**
- İşlenmişse buna ilişkin **bilgi talep etme**
- İşlenme amacını ve amacına uygun kullanılıp kullanılmadığını **öğrenme**
- Yurt içinde/yurt dışında aktarıldığı üçüncü kişileri **bilme**
- Eksik veya yanlış işlenmişse **düzeltilmesini isteme**
- **Silinmesini veya yok edilmesini isteme**
- Verilerinizin **taşınabilir bir kopyasını alma**
- Açık rızanızı **geri çekme**
- Otomatik sistemlerle analiz edilmesi sonucu aleyhinize bir sonuç doğmasına **itiraz etme**
- Zarara uğramanız hâlinde **tazminat talep etme**

### Bu hakları nasıl kullanırsınız

| Hak | Uygulama içinden |
|---|---|
| Verilerinizi düzeltme | Hesap ve profil ekranlarından doğrudan düzenleyebilirsiniz |
| Verilerinizin kopyasını alma | Ayarlar → PDF Sağlık Raporu |
| **Hesabınızı ve tüm verilerinizi silme** | **Hesap → Hesabımı Sil** (işlem geri alınamaz) |
| Bakıcı paylaşımını durdurma | Bakıcı ekranından bağlantıyı kaldırın |
| Bildirimleri kapatma | Ayarlar → Bildirimler |

Diğer talepleriniz için **destek@periyodoz.com** adresine yazabilirsiniz. Başvurularınız en geç **30 gün** içinde yanıtlanır.

Ayrıca Türkiye'de Kişisel Verileri Koruma Kurumu'na (kvkk.gov.tr), AB'de ise bulunduğunuz ülkenin veri koruma otoritesine şikâyette bulunma hakkınız vardır.

---

## 9. Veri güvenliği

- Tüm veri aktarımı **TLS/HTTPS** ile şifrelenir.
- Veriler sunucuda şifrelenmiş olarak saklanır.
- Sunucu tarafındaki güvenlik kuralları, **her kullanıcının yalnızca kendi verisine erişebilmesini** teknik olarak zorunlu kılar. Bir kullanıcının başka bir kullanıcının verisini okuması veya yazması mümkün değildir.
- Bakıcı erişimi, istemci tarafından değil sunucu tarafından doğrulanır.
- Şifreniz Google Firebase Authentication tarafından yönetilir ve tarafımızdan hiçbir şekilde görülemez.
- Cihazınızda oturumu kapattığınızda, o hesaba ait tüm veriler cihazdan silinir.

Hiçbir sistem %100 güvenli değildir. Verilerinizi etkileyen bir güvenlik ihlali yaşanması hâlinde, mevzuatın öngördüğü süreler içinde sizi ve ilgili otoriteyi bilgilendireceğiz.

---

## 10. Çocukların gizliliği

Uygulama **13 yaşın altındaki çocuklara yönelik değildir** ve doğrudan çocuklardan veri toplamaz.

Ebeveynler, çocukları için alt profil oluşturabilir. Bu durumda çocuğa ait sağlık verileri, **veli/vasi sıfatıyla ve onun sorumluluğunda** girilir. Bir çocuğun verisinin rızanız dışında girildiğini düşünüyorsanız destek@periyodoz.com adresinden bize bildirin; ilgili veriyi derhal sileriz.

---

## 11. Abonelikler

Premium abonelikler App Store veya Google Play üzerinden satın alınır ve otomatik olarak yenilenir.

- Ödeme, satın alma onaylandığında mağaza hesabınızdan tahsil edilir.
- Dönem bitiminden en az 24 saat önce iptal etmezseniz abonelik aynı ücretle yenilenir.
- Aboneliğinizi mağaza hesabınızın ayarlarından yönetebilir veya iptal edebilirsiniz.
- **Ödeme bilgileriniz (kart numarası vb.) bize hiçbir zaman ulaşmaz** — ödemeyi tamamen Apple/Google işler. Biz yalnızca aboneliğin aktif olup olmadığı bilgisini alırız.

---

## 12. Bu politikadaki değişiklikler

Bu politikayı zaman zaman güncelleyebiliriz. Önemli bir değişiklik olduğunda uygulama içinde bildirim yapılır ve yukarıdaki "Son güncelleme" tarihi değiştirilir. Değişiklikten sonra uygulamayı kullanmaya devam etmeniz, güncel politikayı kabul ettiğiniz anlamına gelir.

---

## 13. İletişim

Gizlilikle ilgili her türlü soru, talep ve şikâyet için:

**E-posta:** destek@periyodoz.com
**Veri sorumlusu:** `[VERİ SORUMLUSU]`
**Adres:** `[ADRES]`
