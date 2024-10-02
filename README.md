# GAIH_MLPROJECT
## Projenin Amacı:
Bu proje, şarapların üretildiği ülke, üzüm vb. özelliklerine göre puanını tahmin etmek için bir veri seti kullanır.Veri setinde şarapların üretildiği ülke, bölge, üzüm ve kullanan kişinin yorumunu, adını, twitter adresini, puanını içerir. Şarap puanını etkileyen faktörleri inceler.

## Veri Seti
Kullanılan veri seti, 50000 satır ve 14 sütundan oluşur.
Öznitelikler:
* country
* description
* designation
* points
* price
* province
* region_1
* region_2
* taster_name
* taster_twitter_handle
* title
* variety
* winery

## Proje Sonucu:
Yapılan Çapraz doğrulama sonucunda diğer modellere kıyasla en yüksek doğruluk oranına sahip model Karar Ağacı Modelidir. Ancak yine de %23 civarında bir doğruluk oranı, bu modelin veriler üzerinde düşük performans gösterdiğini işaret eder. Bu, ya veri setinde modelin öğrenmesini zorlaştıran bir karmaşıklık olduğunu ya da özellik mühendisliğinde ve model parametrelerinde iyileştirmeler yapılması gerektiğini gösteriyor.
Eğer amacınız veri setindeki doğal kümelemeleri veya grupları keşfetmek ise, K-ortalama kümeleme uygundur.

## Kaggle adresi:
https://www.kaggle.com/code/ervaalk/gaih-mlproject
