# adventcodendar — şu an ne doğru?

Ürün tanımı: PROJECT.md. Geçmiş: REPORTS.md. Gerekçeli yapılmayacaklar: YAPILMAYACAKLAR.md.

## Faz
Araştırma + ağaç prototipi (`agac/index.html`, tek dosya). Çam ağacı kalıyor: farklı boyda tuğlalar
ortak duvarlarla lego gibi geniş ağaç, 30 kutu (Damla 30.10: "AoC'yi çalmıyoruz, ilham alıyoruz").
Süsler 30 Eki'dekiler, fazlası yok: kavisli girland, kenarlarda sarkan ışık dizileri, dal ucu ampulleri,
karakter yıldız, omuzlarda kar, ızgarada düşen kar, karlı zemin. Köy/ay/bulut eklemek reddedildi (1.11).
Terminal çerçevesi karakteristik, kalır: `guest@adventcodendar:~$ tree` yazılır, ağaç satır satır basılır,
altta tmux çubuğu (mod, gerçek sayım, saat).
Yazı ve renk dewguard / portfolyo bahçesi gibi (1.11): siyah #0b0b0c, başlık tek sans ve küçük harf
(geniş ekranda solda, dar ekranda üstte), yazı beyaz/gri, renk çizimde (bahçe paleti), monospace
komut satırı/çizim/çubukta. Parlama durduk yere yok: yalnız üstüne gelinen kutunun kenarında ve açılan
kutuda (bahçedeki hover gibi); ampuller parlamadan yanıp söner. Pause düğmesi var.
Kutu içi yalnız parıltı + numara: hediye/case içeriği yok (hediye tasarımı ağaç çekiminden sonra).

## Kesin sınırlar (Damla'nın sözü)
- Ağaç bölümü çekilmeden hediye tasarımı/teslimi yok. Aşama atlayıp "hazır elim değmişken"
  üyelik, hediye, puanlama bitirmek yok.
- Ladybug yepyeni; hiçbir kodu yok. Bilgisayardaki aynı adlı eski dosyalar bu projeye bağlanmaz.
- Teknolojiye göre ana kategori yok (web/RAG/Python/C++ aynı ihtiyacı çözebilir).
  "Her şeyi gönder, AI puanlasın" kestirmesi yok.
- Katkı satırı tek satır: `damumya · 29.10.2026 · sewing engine`.
- Aylık topluluk özeti / "ayın izi" reddedildi; başka isimle geri gelmez.
- Tier = kazanılan başarı seviyesi; ücretli paket diye yorumlanmaz.
- Çalışan mekanik, token listesi, tutarlılık veya test sonucu görsel kaliteye cevap değildir.
- Sıradan uygulama hataları (çift XP, yetki, veri kaybı, erken açılma) araştırmanın merkezi değil.

## Karar verildi (3 Kas, Damla)
- Ad kalıyor: "adventcodendar gayet unique". AoC benzerlik notu YAPILMAYACAKLAR.md §0'da duruyor.
- Hosting Vercel. Ağaç slopware video 2'de localhost'tan Vercel'e çıkar.
- Build in public = slopware YouTube serisi. Proje seri boyunca adım adım kurulur:
  video 0 fikir + ağaç, video 2 ağaç localhost → Vercel, video 3 kutu açılması
  (sunucu saati karar verir, açılan kutu önce localStorage sonra veritabanı). Plan
  ~/damla_projects_2026/writings_rework/taslaklar/0311-slopware-videolar.txt.
- Slop parodi sayfası önce slopware bölüm 1'de yaşar, sonra ilk case olur (ağaç çekilmeden case yok).

## Karar verilmemiş (uygulama, Damla'ya sormadan seçme)
Yayın ritmi, ilk case kapsamı, teslim biçimi, Ladybug'ın ilk sorumluluğu,
streak/katkı kuralı, XP formülü, ücretli özellikler, framework/db (video 3'ten önce sorulacak).

## Repo
- github.com/nosey-dewdrop/adventcodendar (public), github.com/nosey-dewdrop/ladybug (public, README).
- Araştırma kanıtı: research/<tarih>/. Doğrulanan commit hemen push.
