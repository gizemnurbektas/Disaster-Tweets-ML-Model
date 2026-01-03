# Disaster-Tweets-ML-Model
Tweet Classification using NLP & Machine Learning

Bu proje, Twitter verileri üzerinde metin sınıflandırma (text classification) problemi çözmek amacıyla geliştirilmiştir. Tweet’ler çeşitli Doğal Dil İşleme (NLP) teknikleri ile işlenmiş ve farklı Makine Öğrenmesi algoritmaları kullanılarak sınıflandırılmıştır.

📌 Proje Amacı

Tweet metinlerinden anlamlı özellikler çıkarmak

Metinleri belirli sınıflara ayırmak

NLP ve klasik makine öğrenmesi algoritmalarının performansını karşılaştırmak

Bu çalışma, özellikle sosyal medya analizi, duygu analizi ve metin tabanlı tahmin sistemleri için temel bir örnek sunmaktadır.

📂 Veri Seti

Tweet metinlerinden oluşan bir veri seti

Veri seti genel olarak şu sütunları içerir:

Veri Seti Sütunları

text : Tweet içeriği

label / target : Tweet sınıfı (problem türüne göre değişebilir)

🧹 Veri Ön İşleme (Preprocessing)

Projede uygulanan temel NLP adımları:

Küçük harfe çevirme

Noktalama işaretlerinin kaldırılması

Stopwords temizleme

Tokenization

Metinlerin sayısal forma dönüştürülmesi

🧠 Kullanılan Yöntemler

Bag of Words (CountVectorizer)

TF-IDF Vectorization

Makine Öğrenmesi Algoritmaları:

Logistic Regression

Naive Bayes

Decision Tree

Random Forest

⚙️ Kullanılan Teknolojiler

Python

Jupyter Notebook

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

📊 Model Değerlendirme

Modeller aşağıdaki metrikler ile değerlendirilmiştir:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

Ayrıca farklı modellerin sonuçları karşılaştırılarak en başarılı yaklaşım analiz edilmiştir.

▶️ Projeyi Çalıştırma

Repository’yi klonlayın:

git clone https://github.com/kullanici_adi/tweet-classification-nlp.git


Gerekli kütüphaneleri yükleyin:

pip install -r requirements.txt


Jupyter Notebook’u çalıştırın:

jupyter notebook tweets.ipynb

🚀 Geliştirme Önerileri

Word2Vec / GloVe kullanımı

LSTM veya Transformer tabanlı modeller

Gerçek zamanlı Twitter API entegrasyonu

Daha büyük veri setleri ile eğitim

👩‍💻 Hazırlayan

Gizem Bektaş
NLP & Machine Learning Projesi
