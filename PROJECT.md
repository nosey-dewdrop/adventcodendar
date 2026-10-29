# adventcodendar — ne inşa ediyoruz?

Kaynak: Damla'nın 30.10.2026 session'ına yapıştırdığı devir notu (29 Eki sohbetinin özeti), aynen.
Bu belge ürün tanımıdır; yavaş değişir. Durum için CLAUDE.md, geçmiş için REPORTS.md,
gerekçeli yapılmayacaklar için YAPILMAYACAKLAR.md.

---

## 1. Adventcodendar fikri nereden geliyor?

Senin ilk anlatımın, ideathon, hackathon ve case marathon dünyasındaki problemleri bir araya getirmekti. İnsanların sadece okuyup geçtiği bir fikir arşivi değil; bir problem seçtiği, çözüm geliştirdiği, gönderdiği ve karşılığında ilerleme kazandığı bir platform.

"Yeni nesil LeetCode gibi" dedin ama kapsamın algoritma sorularıyla sınırlı değil. Statik bir proje de olabilir, sistem mühendisliği gerektiren bir problem de. Ortak nokta, bir ihtiyaca gerçekten çözüm üretmek.

İlk anlattığın döngü şöyleydi:

- Kullanıcı bir case bulur veya takvimden açar.
- İster her gün uğraşır, ister kendi temposunda tamamlar.
- Çözümünü gönderir.
- Motor çözümü kontrol eder; çalışması ve değerlendirmesi üzerinden puan kazanır.
- XP'si, seviyesi ve görünür tier'ı ilerler.
- Zamanla gerçek bir çözüm geçmişi oluşur.

İleride işverenlerin bu geçmişe bakarak insanları keşfetmesini düşündün. Bu, uzun vadeli bir olasılık; henüz ilk sürümün işe alım ürünü olması kararlaştırılmadı.

## 2. Problem arşivi ile takvim birlikte var olacak

Fikirde birbiriyle ilişkili iki kullanım var:

- Düzenli olarak yeni içerik açılan advent calendar deneyimi.
- İnsanların geçmişte yayımlanmış case'leri ve proje fikirlerini araştırıp seçebildiği, kaydedebildiği arşiv.

Dolayısıyla ürün yalnızca "bugünün sorusunu çöz, yarın gel" biçiminde düşünülmeyecek. İnsanlar kendilerine uygun bir problem bulup onun üzerinde çalışabilecek.

Just Dance örneğini verdin: her ay yeni bir içerik grubu gelmesi, ayın kendine ait bir seçkisi olması. "Her ay 30 yeni konu" bunun örneğiydi.

Ancak şu seçenekler henüz birbirinden ayrılıp kararlaştırılmadı:

- Her gün yeni case mi açılır?
- Haftalık mı, on günlük mü açılır?
- Ay başında 30 konu mu gelir?
- Açılmış içerikler herkes için aynı mı ilerler?
- Takvimdeki açılma ile kullanıcının çözüm temposu nasıl ilişkilendirilir?

Bunlar konuşulmuş seçenekler. Sonraki ajan bunları aynı anda verilmiş kesin gereksinimler gibi uygulamamalı.

## 3. Teknoloji serbestliği, fikrin temel sınırlarından biri

Özellikle şunu söyledin: RAG, C++, Python, iOS, web diye ayırmak istemiyorsun.

Çünkü aynı ihtiyacı:

- biri veritabanlı bir web uygulamasıyla,
- biri RAG sistemiyle,
- biri Python programıyla,
- biri C++ ile

çözebilir.

Bu, yalnızca filtre isimlerini değiştirmek değil. Problem yazımını ve değerlendirme sistemini de etkiliyor. Kullanıcıya farkında olmadan tek bir çözüm mimarisi dayatırsak fikrin doğasını değiştirmiş oluruz.

Bununla birlikte teknoloji serbestliğinin teknik olarak nasıl sağlanacağı henüz çözülmedi. "Her şeyi gönder, AI puanlasın" diye kestirip atılmayacak. Araştırmanın en önemli konusu bu.

## 4. Case'ler nereden gelecek?

Üç kaynak düşünüyorsun:

- Gerçek etkinliklerden ve kurumlardan alınan problemler.
- Günlük ihtiyaçlardan ilhamla bizim hazırladığımız problemler.
- Üyelerin önerdiği problemler.

Akbank'ı örnek verdin: bir problemde "Akbank, 2025" gibi kökeni görülebilir, kaynak linkine tıklanabilir ve kullanıcıdan o probleme çözüm üretmesi istenebilir.

Ama kapsam Türkiye, bankalar veya birkaç tanınmış kurumla sınırlı değil. Dünyanın farklı yerlerindeki hackathon ve benzeri etkinlikler araştırılacak.

Önceden yapılmış projeleri ve fikirleri de incelemek istiyorsun. Burada "ilham alınan proje", "kaynağından derlenen case" ve "bizim yeniden yazdığımız problem" arasındaki ilişkiyi araştırmada netleştirmemiz gerekiyor. Kaynak linki koymayı, her içeriği aynen yayımlama hakkı varmış gibi değerlendirmeyeceğiz.

Üye önerilerinde AI'nın değerlendirmeye yardımcı olması fikrini söyledin. Fakat AI'nın neye göre kabul edeceği, testleri kimin hazırlayacağı ve yayına alma süreci henüz belirlenmedi.

## 5. Katkıcı görünürlüğü kısa olacak

Kaynak, öneren kişi ve problemin ortaya çıkışı hakkında uzun açıklamalar önermiştim. Sen bunun gereksiz uzamasına itiraz ettin.

Verdiğin örnek:

damumya · 29.10.2026 · sewing engine

İstediğin şey katkının görünmesi, fakat küçük bir kredi satırının hikâye paneline dönüşmemesi. Zor veya ilginç bir problem olsa bile anlatımı kısa tutmak istiyorsun.

Topluluğun katkı verebilmesini ve projenin açık kaynak olarak ilerleyebilmesini önemsiyorsun. Bunun teknik katkı modeli, içerik lisansı ve moderasyon süreci henüz belirlenmedi.

## 6. Üyelik, maillist, XP ve tier birbirine karıştırılmayacak

İlk anlatımında:

- Üyelik, kullanıcının ilerlemesini ve görünür tier'ını taşıyor.
- Case tamamlamak XP ve seviye kazandırıyor.
- Sıralamalar için kullanıcı kimliği gerekiyor.
- Maillist, yeni içerikleri ve güncellemeleri duyurmak için var.

Buradaki tier'ın başlangıç anlamı kazanılan başarı seviyesi. Bunu kendiliğinden ücretli abonelik paketleri olarak yorumlamayacağız.

Bu ürünün ilk defa gerçek kullanıcı ve gelir kazanmasını beklediğini özellikle söyledin. Bu nedenle üyelikten performansa kadar bütün sistemleri ciddi tasarlamamızı istiyorsun. Ancak fiyatlandırma, ücretli özellikler veya abonelik modeli henüz kararlaştırılmadı.

## 7. Sevdiğin ve devam etmemizi istediğin deneyim fikirleri

Aşağıdaki fikirleri açıkça olumlu karşıladın:

- Ağacın seni hatırlaması. Bunun ayrı bir reels konusu bile olabileceğini söyledin.
- Hediye üzerinde ipucu bulunması. Açmadan önce merak uyandıran küçük bir işaret.
- Kaldığın yerden devam etme.
- Çözüm geçmişi.
- GitHub benzeri katkı görünümü ve "never break the chain" hissi.
- Streak. İnsanların geri gelmesini sağlayabilecek bir alışkanlık mekanizması.

Burada önemli bir düzeltmen vardı: Ben streak psikolojisini anlatmaya devam ettiğimde, sen asıl görsel itirazını kaçırdığımı söyledin. "Streak her uygulamaya yapılır" demenin anlamı, bu mekanizmayı reddetmen değildi. Bir özellik eklemenin kötü tasarımı çözmediğini anlatıyordun.

GitHub'a benzeyen birkaç yeşil kare yapmak da yeterli değil. Daha önce "GitHub gibi" istediğinde çıkan tasarımın çok kötü olduğunu özellikle anlattın.

Günlük katkının ne sayılacağı ve case başarısıyla ilişkisi ise henüz kesinleştirilmedi. Benim bu konudaki araştırma yorumlarım, onaylanmış ürün kuralı sayılmayacak.

## 8. Fazla bulduğun veya sonraya bıraktığın fikirler

"Ayın geride kalan izi" adıyla ay sonunda açılan case'leri, çözümleri ve katkıcıları özetleyen bir kayıt önermiştim. Bunu fazla ve gereksiz buldun. Başka isimle ilk sürüme geri sokmayacağız.

Çözümden sonra farklı yaklaşımları keşfetme fikrine daha açıktın. Buradan:

- projelerin gezilebildiği,
- insanların farklı çözümleri inceleyebildiği,
- belki kullanıcıyı tanıyan öneriler sunan,
- ileride iOS uygulaması da olabilecek

bir yön düşündün. "Projelerin Instagram'ı gibi" ifadesini kullandın.

Bu, sonraki aşama olasılığı. İlk sürümün kişiselleştirme algoritması veya sosyal akış gerektirdiği anlamına gelmiyor.

## 9. Görsel beklentinin merkezi: "dünya gibi hissettirmek"

Sohbet boyunca en çok yanlış anlaşılan yer burasıydı.

Senin "dünya" dediğin şey yalnızca:

- ağaç,
- hediyeler,
- maskot,
- animasyon,
- hikâye,
- oyunlaştırma

değil.

Bunu açıkça düzelttin: Bir sitenin fontu, yazı büyüklükleri ve bütün görsel ilişkileri de o dünya hissini oluşturuyor.

GitHub profil sayfasını çok güçlü bir örnek olarak verdin. Advent of Code'un hem görünüşünü hem de ince düşünülmüş mühendisliğini seviyorsun.

Stitchu örneğinde ise üyelik mekaniklerinin zaten bulunduğunu söyledin: silme, kaydetme, şifremi unuttum gibi akışlar mevcut. Buna rağmen tasarımı çok kötü buluyorsun. GYMGYME için de benzer bir itirazın var.

Buradan sonraki sessiona taşınması gereken ders:

Eksiksiz çalışan sayfalar, aynı renkleri kullanan bileşenler veya bir tasarım rehberi, tek başına senin aradığın görsel kaliteyi sağlamıyor.

Benim "GitHub boş durumları ve hataları da tasarlıyor" açıklamam doğru bir araştırma bulgusu olsa da senin itirazını karşılamadı. Konuyu yine mekaniklere çekmiş oldum.

## 10. Somut görsel tercihlerin ve henüz verilmemiş kararlar

Söylediklerin:

- Rabadon'daki ağacı mutlaka istiyorsun.
- Advent of Code'un ağacı ve atmosferi incelensin istiyorsun.
- Ağacın altında küçük hediyeler olabilir.
- Font "çok tatlı" ve karakterli olmalı.
- Yazılar büyük olmalı.
- Monospace yönünü seviyor gibisin.
- Kalınlık konusunda henüz kesin kararın yok.
- Ekranın sağında ve solunda gereksiz geniş boşluklar istemiyorsun.
- Site statik bir proje vitrini gibi hissettirmemeli.

"Statik hissetmesin" sözünü otomatik olarak çok animasyon, ağır JavaScript veya sürekli hareket talebi olarak yorumlamayacağız. Buradaki şikâyetin ürünün cansız, jenerik ve yüzeysel görünmesi.

Henüz seçilmiş bir font, palet, ekran düzeni veya onaylanmış tasarım sistemi yok. Kartlar, gradient veya büyük başlıklar için de senden gelmiş evrensel yasaklar yok. Araştırma sonucunu "sen bunu kesin istiyorsun" diye sunmayacağız.

## 11. Build in public, geliştirme sırasını gerçekten etkiliyor

Bu senin ilk build in public projen olacak. Ürünün yalnızca bitmiş hâlini değil, nasıl oluştuğunu adım adım anlatmak istiyorsun.

İlk anlattığın olası içerik akışı:

1. Fikrini ve projeyi anlatırsın.
2. Ağacı gösterirsin; neden ağaç olduğunu anlatırsın.
3. Hediyeleri ve açılma mekanizmasını gösterirsin.
4. Maillist ve üyeliği eklersin; güncellemeleri ve sıralamaları anlatırsın.
5. Case'leri açarsın.
6. Çözüm gönderme akışını gösterirsin.
7. Ladybug ile sistem kontrolünü anlatırsın.

Üyelerin katkı verebilmesi, ağacın kullanıcıyı hatırlaması ve hediyelerdeki ipuçları da ayrı içeriklere dönüşebilir.

Bu liste henüz son yayın takvimi değil. Ama verdiğin sınır çok açık:

İkinci aşamayı çekmeden hediye paketlerini yapıp önüne koymamı istemiyorsun.

Dolayısıyla bir ajan "hazır elim değmişken üyeliği, hediyeleri ve puanlamayı da bitirdim" diyerek ilerlemeyecek. Aşamaların görsel ve teknik bağımlılıklarıyla, senin anlatacağın sıra birlikte kararlaştırılacak.

## 12. Mühendislik beklentin: rutin kontrol listesinden daha derin

Başından beri "sadece güzel görünen bir şey" istemediğini söyledin. Görünüş kadar altyapının da ciddi olmasını istiyorsun.

Ama benim teknik örneklerim şunlara kayınca itiraz ettin:

- çift XP,
- başkasının teslimine erişim,
- test sırasında veri kaybı,
- erken açılan case.

Bunları araştırmanın merkezine koymamı istemiyorsun. Kodlama ajanının zaten dikkat etmesi gereken temel kontroller üzerinden sana teknik derinlik sunuyormuş gibi davranmamı eleştirdin.

"Claude Code gerizekâlı değil" derken istediğin şey, sıradan uygulama hatalarının listesi değil; ürünü yanlış temele oturtabilecek mimari ve değerlendirme kararlarının araştırılmasıydı.

Sonraki araştırmada bu düzeye inmemiz gerekiyor:

- AoC tam olarak neyi doğruluyor?
- LeetCode, çözümün hangi sınırlar içinde çalışmasını bekliyor?
- Bu modellerin gerçek proje değerlendirmesinde yetmediği yerler neler?
- Aynı problemi farklı teknolojilerle çözen iki proje nasıl değerlendirilebilir?
- Testi geçen bir çözümle ihtiyacı gerçekten karşılayan çözüm arasındaki boşluk nedir?
- Değerlendiricinin kendisinin yanlış olduğunu nasıl fark ederiz?
- Puan hangi kanıta dayanır ve farklı çözümler arasında ne kadar karşılaştırılabilir?

Bunlar henüz cevaplanmış kararlar değil; araştırmanın asıl soruları.

## 13. Ladybug hakkında yaptığın kesin düzeltme

Ladybug için eski bir altyapı varmış gibi kod aramaya başladım. Sen bunu düzelttin:

"Ladybug için hiçbir şey yok şu anda, Ladybug yeni bir şey."

Bu nedenle:

- Ladybug'ın hazır bir motoru olduğunu varsaymayacağız.
- Bilgisayarda bulunan aynı adlı eski dosyaları bu projeye bağlamayacağız.
- Eski planlardan özellik veya mimari taşımayacağız.
- Ladybug'ın görevini, Adventcodendar'ın değerlendirme ihtiyaçlarından çıkaracağız.

CLI olarak altyapıda yer alması senin ilk önerindi. Bunun kesin kapsamı henüz yok.

Araştırmada çalıştırma, test etme, değerlendirme ve raporlama sorumluluklarının birbirinden nasıl ayrılacağını ele alacağız. Ladybug'ın hangilerini üstleneceği, hangi yetenekleri ilk aşamada taşıyacağı daha sonra kararlaştırılacak.

## 14. SEO, GEO, performans ve ölçek beklentin

"İyi SEO yap" dendiğinde beş HTML sayfasına etiket eklenmesini eleştirdin. Senin istediğin, çok büyük sayıda içerikle yaşayabilecek bir sistem.

Örneklerin özellikle şunlardı:

- Çok sayıda sayfa oluşturabilmek.
- Bu sayfaların iyi yüklenmesi.
- Güvenlik.
- Navbarın kaymaması.
- Bütün sistemin gerçek kullanıma dayanması.

Verdiğin çok büyük sayfa sayısı bir kapasite hedefinden çok, ölçek düşüncesinin baştan kurulması gerektiğini vurguluyordu. Bunu rastgele milyonlarca sayfa üretme talebi olarak okumayacağız.

Araştırma yalnızca meta etiketlerine değil; içerik modeli, kalıcı bağlantılar, arşiv ve filtre sayfaları, indekslenme, sunum ve performans ilişkisine bakmalı. Henüz framework, hosting, veritabanı veya dağıtım mimarisi seçmedik.

## 15. İstediğin araştırma çıktısı ne?

Benzer platformlardan yeni fikirler çıkarabiliriz. İnsan psikolojisi ve ürün psikolojisi üzerinden özgün önerilere de açıksın.

Fakat bunların ürünün doğasını değiştirmesini istemiyorsun.

Son talebin özellikle şuydu: Yapacaklarımızı saymadan önce, sohbeti ve referansları inceleyerek teknik ve görsel açıdan derin bir yapılmayacaklar listesi hazırlamak.

Bu liste:

- senin açıkça reddettiklerini,
- belirli bir aşamaya kadar ertelenenleri,
- araştırmayla ortaya çıkan mimari tuzakları,
- henüz doğrulanmamış tasarım yorumlarını

birbirine karıştırmamalı.

"Jenerik tasarım yapma", "güvenli olsun", "hızlı çalışsın" gibi cümlelerle yetinmemeli. Hangi kararın neden kötü sonuç doğurduğunu, bizim ürünümüzde hangi örnekte ortaya çıkacağını açıklamalı.

## 16. Sonraki adımların sırası (devir notundan)

1. Eksik teknik araştırmayı derinleştir: AoC, LeetCode ve açık kaynak değerlendirme sistemlerinin gerçek çalışma sözleşmeleri; belgelenen bilgi ile çıkarım ayrı.
2. Görsel araştırmayı Damla'nın eleştirisi üzerinden tamamla. Özellik listesi veya tasarım token'ları estetik kaliteye cevap değildir.
3. Gerekçeli yapılmayacaklar listesi.
4. Açık kararlar birlikte: yayın ritmi, ilk case kapsamı, teslim biçimi, Ladybug'ın ilk sorumluluğu, görsel yön.
5. Build in public aşamaları ve bağımlılıkları.
6. Sonra ilk aşamanın geliştirmesi.

İlk ekranı üretmiş olmak, araştırmanın tamamlandığı veya görsel yönün onaylandığı anlamına gelmez.
