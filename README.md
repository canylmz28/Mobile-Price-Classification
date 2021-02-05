# Mobile Price Classification

# Problem Tanımı
* Bir kişi kendi mobil şirketini kurdu. Apple, Samsung gibi büyük şirketler ile mücadele etmek istiyor. Şirketlerin oluşturduğu cep telefonlarının fiyatını nasıl tahmin edeceğini bilmiyor. Bu sorunu çözebilmek için çeşitli şirketlerinin cep telefonlarının satış verilerini topluyor.
* Şirket sahibi, cep telefon özellikleri ile satış fiyatı arasındaki ilişkiyi öğrenmek istiyor. Bu problemde gerçek fiyatı tahmin etmek yerine fiyatın ne kadar yüksek olduğunu gösteren bir fiyat aralığı vermemiz isteniyor. 

# Veri Seti Tanımı
* battery_power : Bir pilin mAh cinsinden ölçülen bir seferde depolayabileceği toplam enerji
* blue : Bluetooth olup olmadığı
* clock_speed : Mikroişlemci hızı
* dual_sim : Çift sim desteği olup olmadığı
* fc : Ön kamera mega pixelleri
* four_g : 4G olup olmadığı
* imt_memory : Gigabytes cinsinden dahili bellek
* m_dep : Cm cinsinden mobil derinlik
* mobile_wt : Cep telefon ağırlığı
* n_cores : İşlemci çekirdek sayısı
* pc : Birincil kamera mega pixel
* px_height : Pixel çözünürlük yüksekliği
* px_weight : Pixel çözünürlük genişliği
* ram : RAM
* sc_h : Cm cinsinden mobil ekran yüksekliği
* sc_w : Cm cinsinden mobil ekran genişliği
* talk_time : Tek bir pil şarjının dayanacağı en uzun süre
* three_g : 3G olup olmadığı
* touch_screen : Dokunmatik ekran olup olmadığı
* wifi : Kablosuz bağlantı olup olmadığı
* price_range : Hedef değişkenimiz: 0(düşük fiyatlı), 1(orta fiyatlı), 2(yüksek fiyatlı), 3(çok yüksek fiyatlı)

# Proje Adımları
* 1) Import Library
* 2) Import Dataset
* 3) Missing Value
* 4) EDA
* 5) Outlier Detection
* 6) Feature Engineering
* 7) Ml Models ( Logistic Regression, KNN, Decision Tree, SVM, Random Forest)
