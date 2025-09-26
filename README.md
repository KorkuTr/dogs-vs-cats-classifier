 Köpekler mi, Kediler mi? - Nihai Karar Mekanizması

 Proje Özeti:
Yapay Zekânın İlk Adımları
İnsanlar için iki fotoğraf arasındaki farkı söylemek saniyeler sürer: Biri havlar, diğeri miyavlar. Peki ya bilgisayarlar? Yapay Zekâ dünyasının en ikonik ve temel zorluklarından biri olan bu projede, bir bilgisayara Görüntü Sınıflandırmanın (Image Classification) temellerini öğrettik.

Bu proje, Convolutional Neural Networks (CNN - Evrişimli Sinir Ağları) mimarisinin gücünü kullanarak, verilen bir görüntüdeki dostumuzun bir Köpek mi yoksa bir Kedi mi olduğunu yüksek doğrulukla tahmin eden bir sınıflandırıcı modeldir. Bir Deep Learning macerasına atılmak için mükemmel bir başlangıç noktası!

Temel Özellikler
Evrişimli Sinir Ağı (CNN) Mimarisi: Görüntüden en kritik özellikleri otomatik olarak öğrenen özel bir derin öğrenme modeli.

Ön İşleme Boru Hattı: 
Görüntülerin modele beslenmeden önce yeniden boyutlandırılması, normalize edilmesi ve veri artırımı (Data Augmentation) teknikleriyle zenginleştirilmesi.

Eğitim İzleme:
Modelin doğruluk (accuracy) ve kayıp (loss) metriklerinin eğitim süresince izlenmesi.

Tahmin Arayüzü (Opsiyonel): 
Yeni bir görüntüyü yükleyerek modelin anında tahminini alabilme yeteneği.

 ------------------------------------------------------------------------------------------------------------------------------------------------------------------ 
 
Kullanılan Teknolojiler
Bu projenin kalbinde, güçlü ve popüler veri bilimi araçları yatmaktadır:

Teknoloji	Amaç
Python 3.x	Ana programlama dili.
TensorFlow / Keras	Derin öğrenme modeli oluşturma ve eğitme framework'ü.
NumPy	Veri manipülasyonu ve matris işlemleri.
Matplotlib / Seaborn	Sonuçların ve eğitim grafiklerinin görselleştirilmesi.
Jupyter Notebooks	Veri keşfi, ön işleme ve model denemeleri.

E-Tablolar'a aktar
⚙️ Kurulum ve Çalıştırma
Projeyi yerel makinenizde çalışır duruma getirmek için şu basit adımları izleyin:

1. Depoyu Klonlayın
Bash

git clone https://github.com/KULLANICI_ADINIZ/dogs-vs-cats-classifier.git

cd dogs-vs-cats-classifier

2. Sanal Ortam Oluşturun (Önerilir)
Bash

python -m venv venv
source venv/bin/activate  # Linux/macOS
# venv\Scripts\activate  # Windows

3. Bağımlılıkları Kurun
   
Gerekli tüm kütüphaneler requirements.txt dosyasında listelenmiştir.

Bash

pip install -r requirements.txt

4. Projeyi Çalıştırın
   
Model eğitimi ve analizi için Jupyter Notebook'u başlatın:

Bash

jupyter notebook
Açılan tarayıcı arayüzünde, ana analiz dosyanız olan unsupervised.ipynb (veya benzeri bir isim) dosyasını bularak içindeki hücreleri sırasıyla çalıştırın.
------------------------------------------------------------------------------------------------------------------------------------------------------------------
📈 Sonuçlar
Eğitimden sonra modelimizin performans metrikleri (doğruluk, kayıp grafikleri) ilgili Notebook içinde detaylıca gösterilmiştir.

Modelimiz, artık bir fotoğrafı gördüğünde ne bir "miyavlama" ne de bir "havlama" duymadan, görsel ipuçlarına dayanarak %X doğrulukla nihai kararını verebilir!

Projenizle ilgili harika yorumlar ve pull request'ler bekliyorum. Mutlu kodlamalar!
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Linkler
Çalışmanıza ait tüm Kaggle linklerini mutlaka burada görmeliyiz.

(https://www.kaggle.com/code/korkut61/notebook63a29221fd) 

