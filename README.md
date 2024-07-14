# Türkiye Çalışan Maaş Tahmin Modeli

Bu proje, çalışan maaşlarını tahmin etmek için bir yapay zeka modelini kullanır. Model, şehir ve departman bilgilerini alarak tahmin edilen maaşları hesaplar ve enflasyon oranını dikkate alır. Bu proje, maaş tahmini yapmak isteyen kişiler için kullanışlı bir araç sağlar.

## İçerik

- **Model Dosyaları**: `maas_modeli.h5`, `scaler.pkl`, `le_sehir.pkl`, `le_departman.pkl`
- **Kod**: `maas_tahmin.py` - Maaş tahmini ve enflasyon hesaplamalarını yapar
- **Veri Seti**: `veri_seti.csv` - (Varsa) Maaş tahmini için kullanılan veri seti

## Kullanım

1. **Gerekli Kütüphaneler**:
   Proje, aşağıdaki Python kütüphanelerine ihtiyaç duyar:
   - TensorFlow
   - scikit-learn
   - pandas
   - numpy
   - matplotlib
   - seaborn

   Kütüphaneleri yüklemek için aşağıdaki komutu çalıştırabilirsiniz:
   ```bash
   pip install tensorflow scikit-learn pandas numpy matplotlib seaborn

## Veri Seti
Veri seti calisan_data.csv dosyasını içerir ve şehir, departman, maaş gibi bilgileri barındırır. Bu dosya, modelin eğitiminde ve tahminlerde kullanılabilir.

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.

## İletişim
Proje ile ilgili sorularınız veya katkılarınız varsa, issue açabilir veya proje sahibi ile iletişime geçebilirsiniz.
