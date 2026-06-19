# Karbon Ayak İzi Hesaplama ve Bilinçlenme📈
Proje Amacı:
Bu proje, insanların kendi bir günde elde ettiği karbon ayak izini öğrenmelerini ve hangi eşyaların iklim değişikliklerini kötü yönde etkilediğini öğrenmelerini hedefliyor.

## 🤷‍♀️ Nasıl Çalışır?
### Veri Seti Oluşturma:

* bir grafik oluşturulur

* kullanıcının girdiği bilgiler değerlendirilir

* eğer kullanıcının değerleri çok fazla ise onu google teachable machine'ne yönlendirir
   
* kullanıcının hangi durumların bu olayı kötü etkilediği hakkında bilinçlendirir

### Model Eğitimi:

* Google Teachable Machine kullanılarak bilgisayarlı görü modeli eğitilir.

* Model, görselleri iki kategoriye ayırmak üzere eğitilir.

* Eğitimde kullanılan algoritma, görüntü sınıflandırması yapmak için makine öğrenmesi tekniklerini içerir.

### Modelin Kullanımı:

* Kullanıcının iklim hakkında bilgilerini alır,

* kullanıcının karbon ayak izini hazırlar

* kullanıcıyı bilinçlendirmek için onu karşılaştırmaya yönlendirir.

### 🔨 Kullanılan Araçlar ve Teknolojiler 💻:
* Google Teachable Machine: Görüntü sınıflandırma modeli eğitimi için kullanıcı dostu bir araç.

* Google Colab: Modeli test etmek ve sonuçları görmek için Python kodu yazma ortamı.

* Python: Görüntü işleme ve model entegrasyonu.

* TensorFlow / Keras: (Google Teachable Machine tarafından kullanılan kütüphaneler.)

* NumPy, PIL (Python Imaging Library): Görsel verilerin işlenmesi.
