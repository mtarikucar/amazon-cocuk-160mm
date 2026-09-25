# Amazon Çocuk — yüzü düzeltilmiş 160 mm reçine baskı seti

Kaide dahil yükseklik **160,00 mm**. Bu sürüm önceki parçalı setin tamamını içerir. **153 parça / figür; 200 figür için 30600 parça.** Her STL bir figürde bir kez kullanılır.

## Yüzde yapılan değişiklik

**P015 Yüz:** Kaşlar, kirpikler ve dudak yüzle bütünleşiktir. Ayrı montaj parçaları değildir. Sol kaşın saç parçasında kalmış ucu da yüze alınmıştır. Eski, konumu kaymış göz/kaş/kirpik ekleri kaldırılmıştır.

**P161 Sağ Göz ve P162 Sol Göz:** Her göz tek fiziksel parçadır. Göz beyazı, kahverengi iris, siyah göz bebeği ve beyaz ışık noktası aynı parçanın üzerine boyanır. Gözlerin görünen yüzeyi ve sınırları özgün Meshy yüzünden alınmıştır; önceki bağımsız yuvarlak göz katmanları kullanılmaz. Sağ/sol adları karakterin sağı/soludur.

Gözler, kendilerine ait asimetrik dış hat ve arka D kesitli pimle yönlenir. Önden takılıp çıkarılır. Nominal göz gövde derinliği ön–arka yönünde 2,20 mm, arka pim çapı 1,80 mm ve pim uzunluğu 1,80 mm'dir. Dış hat yuvasında yaklaşık 0,10 mm yan payı; pimde 0,25 mm çap farkı; arka yüzeyde 0,25 mm pay bulunur. Mesh temizliği sırasında yerel boşluklar bir miktar genişletilmiştir.

Boyama için gözleri yüz dışında tutun. Yuva ve pimleri boyadan koruyun. Kuru montajı son kürden sonra deneyin. Tekrar çıkarmak istediğiniz gözleri yapıştırmayın; bu geçme elastik çıtçıt veya kilit mekanizması değildir. Nihai sergileme montajında isterseniz az miktarda yapıştırıcıyla sabitleyebilirsiniz.

## Dosyalar

- `Amazon_Cocuk_160mm_Parcali.blend`: Düzenlenebilir model. `MONTAJ_160mm` birleşik modeli, `PARCALAR_PATLATILMIS` ayrılmış parçaları, `YUZ_VE_IKI_GOZ` yüz alt grubunu gösterir. Sahne nesneleri bağımsızdır; ayrılmış görünüm montaj konumlarını değiştirmez.
- `Amazon_Cocuk_160mm_Montaj.3mf`: Milimetre birimli, ayrı nesnelerden oluşan birleşik montaj referansı. Yüz ve göz boyasının ayrıntılı referansı Blender dosyası ve PNG görüntülerdedir; 3MF temel parça renklerini taşır.
- `STL/`: Güncel parçalar boya gruplarına göre klasörlenmiştir. Gözlerin çok renkli boyanacak tek parça STL'leri kırık beyaz klasöründedir. Her STL XY merkezine ve Z=0'a alınmıştır. Slicer'da birimi **mm** seçin; otomatik ölçekleme uygulamayın.
- `Yuz_Yakin_Plan.png`, `Yuz_Geometri.png`, `Yuz_ve_Iki_Goz_Parcalari.png`: Renkli boyama referansı, renksiz yüz geometrisi ve ayrılmış yüz alt grubu.
- `Montaj_Onizleme.png`, `Parcalar_Patlatilmis.png`: Tam modele ait Blender görüntüleri.
- `Parca_Listesi.md`, `Parca_Listesi_ve_Olculer.json`: Parça kodları, miktarlar, ölçüler ve STL'den montaj konumuna dönüş koordinatları.
- `Gecme_Testi/`: 2, 4 ve 6 mm pimler ile farklı boşlukları karşılaştıran test kuponu.

STL dosyaları renk ve doku taşımaz. Görüntülerdeki yanak pembeliği, çil, göz parıltısı ve diğer boya efektleri baskıdan sonra boyanır. P kodlarında boşluklar bulunması normaldir; iptal edilen eski yüz ayrıntılarının kodları başka parçalar için kullanılmamıştır. Eski ZIP'teki parçalarla karıştırmadan bu klasörü kullanın.

## Diğer parçalar ve montaj

Kaide, üzerindeki taş, botlar, pantolon, iç gövde, ön/arka zırh, tunik, kollar, eller, şal, yüz, kulak, saç ve örgü bölümleri, saç bağı, bere ve bere bandı ayrıdır. Kalkanın ön/arka paneli, dış çerçevesi, arma tabanı, atlı kabartması ve renk bölgeleri de ayrıdır. Bere, kıyafet ve kaide üzerindeki renk motifleri ile broş ve toka ayrı kalır.

Önce bere, kıyafet ve kalkanın küçük renk parçalarını hazırlayın. Kaide–taş–bot–pantolon grubunu; ardından gövde, zırh, tunik, kollar, eller ve şalı kuru olarak birleştirin. Yüz–saç–bere grubunu ve boyalı iki gözü tamamlayın. Kalkanı son aşamada takın. Ana geçmelerde 0,25 mm nominal çap farkı ve 0,30 mm yuva dip payı kullanılmıştır. İnce motifler dış hatlarına uygun gömme yuvalara oturur.

| Pim bulunan parça | Yuva bulunan parça | Nominal çap | Pim uzunluğu |
|---|---|---:|---:|
| P025 Kalkan On Panel | P026 Kalkan Dis Cerceve | 5.00 mm | 3.50 mm |
| P023 Bere Bandi | P016 Sac | 5.00 mm | 3.50 mm |
| P015 Yuz | P016 Sac | 5.00 mm | 3.50 mm |
| P012 Sag El | P010 Sag Kol | 5.00 mm | 3.50 mm |
| P022 Bere | P023 Bere Bandi | 5.00 mm | 3.50 mm |
| P002 Kaide Ustu Tas | P001 Kaide | 5.00 mm | 3.50 mm |
| P014 Sal | P008 Zirh Arka | 5.00 mm | 3.50 mm |
| P005 Pantolon | P009 Tunik Etek | 5.00 mm | 3.50 mm |
| P004 Sol Bot | P005 Pantolon | 5.00 mm | 3.50 mm |
| P003 Sag Bot | P001 Kaide | 5.00 mm | 3.50 mm |
| P003 Sag Bot | P005 Pantolon | 5.00 mm | 3.50 mm |
| P014 Sal | P007 Zirh On | 5.00 mm | 3.50 mm |
| P009 Tunik Etek | P007 Zirh On | 5.00 mm | 3.50 mm |
| P025 Kalkan On Panel | P024 Kalkan Arka Panel | 5.00 mm | 3.50 mm |
| P027 Arma Taban | P025 Kalkan On Panel | 4.00 mm | 3.00 mm |
| P014 Sal | P015 Yuz | 4.00 mm | 3.00 mm |
| P013 Sol El | P011 Sol Kol | 4.00 mm | 3.00 mm |
| P006 Govde | P008 Zirh Arka | 3.00 mm | 2.70 mm |
| P020 Sac Bagi | P016 Sac | 3.00 mm | 2.70 mm |
| P018 Sac Ic 2 | P016 Sac | 3.00 mm | 2.70 mm |
| P014 Sal | P010 Sag Kol | 3.00 mm | 2.70 mm |
| P014 Sal | P011 Sol Kol | 3.00 mm | 2.70 mm |
| P014 Sal | P026 Kalkan Dis Cerceve | 3.00 mm | 2.70 mm |
| P020 Sac Bagi | P019 Orgu Ucu | 2.20 mm | 2.20 mm |
| P017 Sac Ic 1 | P015 Yuz | 1.60 mm | 1.70 mm |
| P021 Sol Kulak | P016 Sac | 1.60 mm | 1.70 mm |
| P161 Sag Goz | P015 Yuz | 1.80 mm | 1.80 mm |
| P162 Sol Goz | P015 Yuz | 1.80 mm | 1.80 mm |

## İlk numune ve 200 adet üretim

Bu dosyalar ilk numune baskı ve montaj denemesi içindir. Fiziksel baskı veya son kür sonrası geçme testi yapılmadı. Önce kendi reçine, yazıcı ve kür ayarlarınızla kuponu; ardından yüz ve iki gözü; sonra bir tam figürü basıp montajı doğrulayın. 200 adede bundan sonra geçin.

Yazıcı modeli, tabla ölçüsü, reçine ve pozlama profili belirtilmediği için destekler, tabla dizilimi ve pozlama ayarları eklenmedi. STL'nin Z=0 olması önerilen baskı yönü anlamına gelmez. Görünür yüzeyleri ve pim/yuvaları destek izlerinden koruyun. Model dolu katılardır; üretim için boşaltma ve drenaj tasarımı yapılmamıştır.

Toplam geometrik katı hacmi yaklaşık **213.7 mL / figür**, 200 figür için **42.7 litre**. Destek, tabla ve süreç kayıpları bu hesaba dahil değildir.

Geometri denetimleri kapalı yüzey, pozitif hacim, tek bağlı katı, STL bütünlüğü, montaj ölçüsü ve gözün örneklenen çıkarma konumlarını kapsar. Bunlar fiziksel baskı denemesi yerine geçmez. Tek ön fotoğraftan Meshy ile oluşturulan arka yüzler yorumlanmıştır. Boyalı önizleme nihai baskı fotoğrafı değildir.
