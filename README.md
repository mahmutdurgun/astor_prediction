ASTOR Hisse Senedi Fiyat Tahminlemesi
Bu proje, ASTOR firmasına ait hisse senedi fiyatlarını LSTM (Long Short-Term Memory) modeli kullanarak tahminlemeyi amaçlamaktadır.

Projenin Amacı
Finansal zaman serileri, genellikle gürültülü, non-stationary ve volatilite kümeleme gibi özelliklere sahiptir. Bu tür zaman serileri üzerinde tahmin yapmak zor olabilir. Bu projede, LSTM'nin bu tür zorlukları aşma yeteneğini değerlendiriyoruz.

Kullanılan Veri Seti
ASTOR firmasına ait hisse senedi fiyatlarına dair bir veri seti kullanılmıştır. Bu veri seti şu özelliklere sahiptir:

time: Zaman damgası
open: Açılış fiyatı
high: En yüksek fiyat
low: En düşük fiyat
close: Kapanış fiyatı
... (diğer özellikler)
Kullanılan Yöntem
Projede, kapanış fiyatını tahminlemek için LSTM (Long Short-Term Memory) modeli kullanılmıştır. LSTM, tekrarlayan sinir ağlarının (RNN) bir türüdür ve zaman serisi tahminlemesi, doğal dil işleme gibi sekans verisiyle çalışırken iyi performans gösterir.

Sonuçlar
Model, veri setinin son 50 gününü test seti olarak kullanarak eğitilmiştir. Ayrıca, model sonraki 100 gün için de tahminlerde bulunmuştur. Elde edilen tahminler, gerçek değerlerle karşılaştırılmış ve bir grafik üzerinde gösterilmiştir.

Nasıl Çalıştırılır
Veri setini yükleyin.
LSTM_model.py dosyasını çalıştırın.
Elde edilen grafikleri inceleyin.



yatırım tavsiyesi diildir. eğitim amaçlı kullanılmıştır.
