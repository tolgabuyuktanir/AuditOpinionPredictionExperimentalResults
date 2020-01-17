# AuditOpinionPredictionExperimentalResults
Independent Audit Opinion Prediction Experimental Results- Bağımsız Denetim Görüşü Tahmini Deneysel Sonuçları

## Verilerin Toplanması
1. Kamu aydınlatma platformundan bütün bağımsız denetim raporları toplanmıştır. Raporlar toplandıktan sonra, bu raporlardan sırasıyla, *bildirim numarası, şirket ismi, şirket kodu, bildirim tarihi, bildirim tipi kodu, bildirim yılı, bildirim dönemi, bağımsız denetim şirketinin ismi, önceki denetim dönemindeki bağımsız denetim şirketinin şimdiki ile aynı olup olmadığı, denetim türü, görüş türü, önceki görüş bildirme tarihi, önceki görüş bildirme dönemi, önceki dönemin bağımsız denetim şirketi, önceki dönemin denetim türü ve önceki dönemin görüş türü* bilgileri vardır.  [Örnek bildirim](https://www.kap.org.tr/tr/Bildirim/266639)
2. Şirketlere ait mali tablolar toplanmıştır. Mali tablolar toplandıktan sonra finansal oranlar hesaplanacaktır. [Örnek mali tablo (bilanço)](https://www.kap.org.tr/tr/Bildirim/266639)
3. KAP'tan halka açık şirket bilgileri toplanmıştır. [Şirket bilgileri](https://www.kap.org.tr/tr/bist-sirketler)
4. Şirketler, bir bağımsız denetçi tarafından denetlendikten sonra, denetim raporunun KAP'a bildirilmesi için son bildirim tarihi mevcuttur. Denetçi isterse bu süreye ek süre talep edebilir. Bu öznitelik literatürde kullanıldığından, son bildirim tarihleri de toplanmıştır. [Son bildirim tarihleri](https://www.kap.org.tr/file/Finansal-Rapor-Ilan-Tarihleri/Finansal-Rapor-Ilan-Tarihleri)
5. Bağımsız denetim şirketleri, denetledikleri şirket sayısına göre A-F arasındaki harflerden biri ile sınıflandırılmıştır. 
## Finansal Oranların Hesaplanması

### Likidide Oranları	 
1.	    Cari Oran = DÖNEN VARLIKLAR / KISA VADELİ YÜKÜMLÜLÜKLER
2.	    Asit-Test Oranı = (DÖNEN VARLIKLAR - STOKLAR - DİĞER DÖNEN VARLIKLAR) / KISA VADELİ YÜKÜMLÜLÜKLER
3.	    Nakit Oranı = (HAZIR DEĞERLER + MENKUL KIYMETLER) / KISA VADELİ YÜKÜMLÜLÜKLER
### Kaldıraç Oranları	 
1.      finansal_kaldirac=[(UZUN VADELİ YÜKÜMLÜLÜKLER+KISA VADELİ YÜKÜMLÜLÜKLER)/TOPLAM AKTİFLER]*100
2.	    Gecen yilin aynı donemine göre artis
3.      borclanma_katsayisi=[(UZUN VADELİ YÜKÜMLÜLÜKLER+KISA VADELİ YÜKÜMLÜLÜKLER)/ÖZ SERMAYE (AZINLIK PAYI DAHİL)]*100
4.	    Gecen yilin aynı donemine göre artis
5.	    ozsermaye_carpani=TOPLAM AKTİFLER/ÖZ SERMAYE (AZINLIK PAYI DAHİL)
6.	    kisa_vadeli_borclar_aktifler_orani= KISA VADELİ YÜKÜMLÜLÜKLER/TOPLAM AKTİFLER
7.	    Gecen yilin aynı donemine göre artis
8.	    borc_yapisi_orani=[KISA VADELİ YÜKÜMLÜLÜKLER/(UZUN VADELİ YÜKÜMLÜLÜKLER+KISA VADELİ YÜKÜMLÜLÜKLER)]*100
9.	    Gecen yilin aynı donemine göre artis
10.	    uzun_vadeli_borclar_aktifler_orani=(UZUN VADELİ YÜKÜMLÜLÜKLER/TOPLAM AKTİFLER)*100
11.	    Gecen yilin ayni donemine göre artis
12.	    uzun_vadeli_borclar_devamli_sermaye_orani= UZUN VADELİ YÜKÜMLÜLÜKLER/(UZUN VADELİ YÜKÜMLÜLÜKLER+ÖZ SERMAYE (AZINLIK PAYI DAHİL))*100
13.	    sermaye_ozsermaye_orani=(SERMAYE/ÖZ SERMAYE (AZINLIK PAYI DAHİL))*100
### Mali Yapı Oranları	 
1.	    maddi_duran_varliklar_ozsermaye_orani= MADDİ DURAN VARLIKLAR*100/ÖZ SERMAYE (AZINLIK PAYI DAHİL)
2.	    Gecen yilin aynı donemine göre artis
3.	    duran_varliklar_ozsermaye_orani=DURAN VARLIKLAR*100/ÖZ SERMAYE (AZINLIK PAYI DAHİL)
4.	    Gecen yilin aynı donemine göre artis
5.	    finansal_duran_varliklar_duran_varliklar_orani=FİNANSAL DURAN VARLIKLAR*100/DURAN VARLIKLAR
6.	    Gecen yilin aynı donemine göre artis
### Faaliyet Oranları	 
1.	    alacak_devir_hizi = SATIŞ GELİRLERİ/(UZUN VADELİ TİCARİ ALACAKLAR+KISA VADELİ TİCARİ ALACAKLAR)
2.	    Gecen yilin aynı donemine göre artis
3.	    stok_devir_hizi = SATIŞLARIN MALİYETİ (-)/STOKLAR
4.	    Gecen yilin aynı donemine göre artis
5.	    ticari_borclar_devir_hizi=SATIŞLARIN MALİYETİ (-)/TİCARİ BORÇLAR
6.	    Gecen yilin aynı donemine göre artis
### Karlılık Oranları	 
1.	    brut_kar_marji= BRÜT ESAS FAALİYET KARI/ZARARI *100/ SATIŞ GELİRLERİ
2.	    Gecen yilin aynı donemine göre artis
3.	    net_kar_marji = NET DÖNEM KARI*100/SATIŞ GELİRLERİ
4.	    Gecen yilin aynı donemine göre artis
5.	    esas_faaliyet_karliligi= NET ESAS FAALİYET KARI/ZARARI*100/SATIŞ GELİRLERİ
6.	    faaliyet_karliligi= FAALİYET KARI VEYA ZARARI*100 /SATIŞ GELİRLERİ
7.	    oz_sermaye_kar_marji= NET DÖNEM KARI/ZARARI/ ÖZ SERMAYE (AZINLIK PAYI DAHİL)
8.	    aktif_kar_marji = NET DÖNEM KARI/ZARARI/ TOPLAM AKTİFLER
### Büyüme Oranları	 
1.	    net_kar_buyume_orani = NET DÖNEM KARI/ZARARI(t)/NET DÖNEM KARI/ZARARI(t-1)
2.	    net_satislar_buyume_orani = SATIŞ GELİRLERİ(t)/SATIŞ GELİRLERİ(t-1)
3.	    net_isletme_sermayesi_buyume_orani = (Dönen Varlıklar - K.V. Borçlar)(t) / (Dönen Varlıklar - K.V. Borçlar)(t-1)
4.	    aktifler_buyume_orani = TOPLAM AKTİFLER(t)/TOPLAM AKTİFLER(t-1)
5.	    ozsermaye_buyume_orani = ÖZ SERMAYE (Azınlık Payı Dahil)(t)/ÖZ SERMAYE (Azınlık Payı Dahil)(t-1)
6.	    ana_ortak_ozsermaye_orani= ÖZ SERMAYE (ANA ORTAKLIĞA AİT)*100/ ÖZ SERMAYE (Azınlık Payı Dahil)

## Veri Kümesi
Veri kümesinde bulunan alanlar ve veri kümesine ait bir satır aşağıda gösterilmiştir.
```
bildirim_numarasi  -> ***
sirket_adi  -> *** 
sirket_kodu  -> *** 
bildirim_tarihi  -> 26,02,2013 
bildirim_kodu  -> FR 
bildirim_yili  -> 2012
bildirim_donemi  -> Ara,12 
donemin_denetci_sirketi  -> ***
denetci_sirketi_degisti_mi  -> FALSE 
gorus_tipi  -> Sürekli 
gorus_turu  -> Olumlu 
o_bildirim_tarihi  -> 28,07,2012 
o_bildirim_donemi  -> Haz,12 
o_donemin_denetci_sirketi  -> ***
o_gorus_tipi  -> Sınırlı 
o_gorus_turu  -> Olumlu 
denetim_sirketi_sinifi  -> B 
o_denetim_sirketi_sinifi  -> B 
son_bildirim_tarihi  -> 26,02,2013 
gec_bildirim_suresi  -> 0
o_son_bildirim_tarihi  -> 28,07,2012 
o_gec_bildirim_suresi  -> 0
cari_oran  -> 0,81927396
asit_test_orani  -> 1,31685215
nakit_orani  -> 0,00389725
finansal_kaldirac  -> 55,86034655
o_finansal_kaldirac  -> 0,38991258
borclanma_katsayisi  -> 126,55365910
o_borclanma_katsayisi  -> 0,88336122
ozsermaye_carpani  -> 2,26553659
kisa_vadeli_borclar_aktifler_orani  -> 43,20658195
o_kisa_vadeli_borclar_aktifler_orani  -> 1,43103063
borc_yapisi_orani  -> 77,34750071
o_borc_yapisi_orani  -> 0,74905290
uzun_vadeli_yukumlulukler_aktifler_orani  -> 12,65376460
o_uzun_vadeli_yukumlulukler_aktifler_orani  -> -0,43552514
uzun_vadeli_borclar_devamli_sermaye_orani  -> 22,28033642
sermaye_ozsermaye_orani  -> 19,54676189
maddi_duran_varliklar_ozsermaye_orani  -> 145,94758610
o_maddi_duran_varliklar_ozsermaye_orani  -> 0,17470021
duran_varliklar_ozsermaye_orani  -> 146,35813300
o_duran_varliklar_ozsermaye_orani  -> 0,13272365
finansal_duran_varliklar_duran_varliklar_orani  -> 0,00000000
o_finansal_duran_varliklar_duran_varliklar_orani  -> 0,00000000
alacak_devir_hizi  -> 7,81921884
o_alacak_devir_hizi  -> -0,44197979
stok_devir_hizi  -> 3,08112693
o_stok_devir_hizi  -> -0,47013380
ticari_borclar_devir_hizi  -> 11,76688832
o_ticari_borclar_devir_hizi  -> -0,65804862
brut_kar_marji  -> 13,06548800
o_brut_kar_marji  -> -0,27252951
net_kar_marji  -> 0,00000000
o_net_kar_marji  -> 0,00000000
esas_faaliyet_karliligi  -> -7,08084488
faaliyet_karliligi  -> -3,53714212
oz_sermaye_kar_marji  -> -5,59209480
aktif_kar_marji  -> -2,46833126
net_kar_buyume_orani  -> 0,72671229
net_satislar_buyume_orani  -> 1,04450808
net_isletme_sermayesi_buyume_orani  -> -1,96607570
aktifler_buyume_orani  -> 1,24555520
ozsermaye_buyume_orani  -> 0,91921445
ana_ortak_ozsermaye_orani  -> 1,00000000
ek_sure -> FALSE
```


## Sınıflandırma Sonuçları

Yukarıda paylaşılan veri kümesinin her bir satırı 65 sütundan oluşmaktadır, ancak *bildirim_numarası, sirket_adi,bildirim_tarihi,bildirim_kodu,bildirim_yili,bildirim_donemi,gorus_tipi,o_bildirim_tarihi,o_bildirim_donemi,o_gorus_tipi,son_bildirim_tarihi,o_son_bildirim_tarihi* sütunları görüş tahmini için anlam ifade etmediğinden, veriden atılmıştır. Geriye kalan değerler ile sınıflandırma yapılmıştır. Sınıflandırıcıar, default parametreler ile çalıştırıldığında aşağıdaki sonuçlar elde edilmiştir.

|                                 | Accuracy | Recall | Precision | F1\-Score |
|---------------------------------|----------|--------|-----------|-----------|
| Logistic Regression             | 0,834    | 0,834  | 0,782     | 0,805     |
| Naïve Bayes                     | 0,04     | 0,04   | 0,815     | 0,042     |
| Stochastic Gradient Descent     | 0,281    | 0,281  | 0,744     | 0,384     |
| K\-Nearest Neigbours            | 0,817    | 0,817  | 0,875     | 0,839     |
| Decision Tree                   | 0,907    | 0,907  | 0,907     | 0,907     |
| Random Forest                   | 0,947    | 0,947  | 0,946     | 0,946     |
| AdaBoost                        | 0,936    | 0,936  | 0,934     | 0,935     |
| AdaBoosted Decision Tree        | 0,905    | 0,905  | 0,914     | 0,908     |
| Neural Net                      | 0,762    | 0,762  | 0,854     | 0,796     |
| Quadratic Discriminant Analysis | 0,165    | 0,165  | 0,812     | 0,189     |
| XGBoost                         | 0,95     | 0,95   | 0,947     | 0,947     |

### Filter Method

Filtreleme metodu ile ilgileşim değerleri yüksek olan değerler bir eşik deperine göre çıkarılarak sınıflandırma yapılmıştır. o_gorus_turu, o2_gorus_turu ve gorus_turu_degisimi çıkarıldığında elde edilen sonuçlar aşağıda paylaşılmıştır.

|                          | Accuracy | Recall | Precision | F1\-Score |
|--------------------------|----------|--------|-----------|-----------|
| Random Forest            | 0,915    | 0,915  | 0,915     | 0,915     |
| AdaBoost                 | 0,735    | 0,735  | 0,851     | 0,778     |
| AdaBoosted Decision Tree | 0,790    | 0,790  | 0,855     | 0,816     |
| XGBoost                  | 0,916    | 0,916  | 0,914     | 0,915     |

### Özyinelemeli Öznitelik Eleme (Recursive Feature Elimination)
Bu algoritma çalıştırılarak 18 öznitelik kalana kadar eleme yapılmış, geriye öznitelikler kullanılarak sınıflandırma yapılmıştır. Sınıflandırma skorları aşağıdaki gibidir:

| Parametreleri ile Model                    | Accuracy | Recall | Precision | F1\-Score |
|--------------------------------------------|----------|--------|-----------|-----------|
| RandomForestClassifier\(random\_state=42\) | 0,950    | 0,950  | 0,948     | 0,949     |
| XGBClassifier\(random\_state=42\)          | 0,947    | 0,947  | 0,945     | 0,945     |

### RFE ve Filter Method'un Birlikte Kullanımı
İki öznitelik seçimi yöntemi birlikte kullanıldığında elde edilen skorlar şöyledir:

| Parametreleri ile Model                    | Accuracy | Recall | Precision | F1\-Score |
|--------------------------------------------|----------|--------|-----------|-----------|
| RandomForestClassifier\(random\_state=42\) | 0,916    | 0,916  | 0,913     | 0,914     |
| XGBClassifier\(random\_state=42\)          | 0,926    | 0,926  | 0,921     | 0,921     |

Elde edilen sonuçlar gösteriyor ki, filtreleme yöntemi ile elenen öznitelikler, sonuç için hatrı sayılır katkı sağlamaktadır. Diğer özniteliklerin elenmesi karmaşıklığı azaltmıştır ancak skora katkı sağlamamıştır.


## Hiper Parametre Seçimi
Hiper parametre seçimi, varsayılan parametrelerde en iyi sonucu veren XGBoost algoritması için yapılmıştır.
### Varsayılan XGBoost Hiper parametreleri
```
{'base_score': 0.5,
 'booster': 'gbtree',
 'colsample_bylevel': 1,
 'colsample_bynode': 1,
 'colsample_bytree': 1,
 'gamma': 0,
 'learning_rate': 0.1,
 'max_delta_step': 0,
 'max_depth': 3,
 'min_child_weight': 1,
 'missing': None,
 'n_estimators': 100,
 'n_jobs': 1,
 'nthread': None,
 'objective': 'binary:logistic',
 'random_state': 42,
 'reg_alpha': 0,
 'reg_lambda': 1,
 'scale_pos_weight': 1,
 'seed': None,
 'silent': None,
 'subsample': 1,
 'verbosity': 1}

```
### Hiper Parametre Ayarlaması Yapıldıktan Sonra Elde Edilen Parametreler
```
 'booster': 'gbtree',
 'colsample_bylevel': 0.8,
 'colsample_bynode': 1,
 'colsample_bytree': 0.6,
 'gamma': 0.0,
 'learning_rate': 0.01,
 'max_delta_step': 0,
 'max_depth': 40,
 'min_child_weight': 1,
 'missing': None,
 'n_estimators': 500,
 'n_jobs': 1,
 'nthread': None,
 'objective': 'binary:logistic',
 'random_state': 0,
 'reg_alpha': 0.05,
 'reg_lambda': 0.005,
 'scale_pos_weight': 1,
 'seed': None,
 'silent': None,
 'subsample': 0.9,
 'verbosity': 1}

```
XGBoost algoritması için hiper parametre ayarı yapıldığında en iyi parametreler yukarıdaki gibi olmaktadır. Bulunan parametrelere göre XGBoost algoritması çalıştırıldığında, doğruluk değeri 0.948, duyarlılık 0.948, kesinlik 0.946 ve F1-Skor 0.946 olmaktadır. Elde edilen bu değerler, varsayılan parametreler ile alınan değerler ile neredeyse aynıdır.
