
# Elektrikli Araç Bataryası Veri Analizi

Bu repo, elektrikli araçların bataryalarının gerçek sürüş döngüleri sırasında nasıl performans gösterdiğine dair veri analizi için bir Shiny uygulamasını içerir. Uygulama, dış etkenlerin batarya performansı üzerindeki etkisini incelemek için oluşturulmuştur.

## Özellikler

- Veri setinin yapısal özelliklerini gösteren interaktif bir tablo
- Farklı değişkenlerin dağılımlarını incelemek için histogramlar
- Değişkenler arasındaki ilişkileri görselleştiren korelasyon matrisi
- Sıcaklık ve diğer değişkenlerin batarya kaybı üzerindeki etkisini değerlendiren lineer regresyon analizleri

## Veri Seti

Veriler, [IEEE DataPort'tan](https://ieee-dataport.org/open-access/battery-and-heating-data-real-driving-cycles) alınmış ve 72 gerçek sürüş döngüsü içermektedir. Bu döngüler, bir BMW i3'ün (60 Ah) güç aktarma organları ve ısıtma devresi modelinin doğrulanması için kaydedilmiştir.

### İçerik

- Çevresel veriler (sıcaklık, yükseklik vb.)
- Araç verileri (hız, gaz pedalı pozisyonu vb.)
- Batarya verileri (voltaj, akım, sıcaklık, SoC)
- Isıtma devresi verileri (iç mekan sıcaklığı, ısıtma gücü vb.)

## Kurulum

Projeyi yerel makinenizde çalıştırmak için:

1. Bu repo'yu klonlayın veya indirin.
2. R ve gerekli paketler (`shiny`, `ggplot2`, `DT`, `corrplot`, `GGally`) yüklü olduğundan emin olun.
3. Uygulamayı başlatmak için `Shiny_App.R` dosyasını R'de çalıştırın.

## Kullanım

Uygulama içerisindeki menüden istediğiniz analizi seçin ve verileri interaktif olarak keşfedin.

## Sonuç

Analizler, mevcut veri setiyle kesin sonuçlara varılmadığını, ancak daha fazla veri ve derinlemesine araştırmaya ihtiyaç olduğunu göstermiştir. Shiny uygulaması, bu analiz sürecinde veri görselleştirmesi ve modelleme için kullanılmıştır.

## Uygulama Görselleri

~Screenshots kısmında mevcuttur.

## Hazırlayan

- Ekin Emre Atasoy
