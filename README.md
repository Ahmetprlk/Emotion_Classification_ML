Duygu Sınıflandırma
Bu proje, metin verilerinden duyguları sınıflandırmayı amaçlamaktadır ve hem geleneksel makine öğrenimi hem de derin öğrenme modelleri kullanılarak gerçekleştirilmiştir. Veri seti, sevinç, öfke, üzüntü gibi duygularla etiketlenmiş cümlelerden oluşmaktadır. Proje, Lojistik Regresyon, Naive Bayes, Destek Vektör Makineleri (SVM) ve Rastgele Ormanlar gibi çeşitli makine öğrenimi tekniklerini araştırmaktadır. Ayrıca, metin sınıflandırması için LSTM (Uzun Kısa Süreli Bellek) ağı kullanan bir derin öğrenme modeli de içermektedir.

Veri Ön İşleme: Metin temizleme işlemleri kök bulma, tokenizasyon ve durak kelimelerin kaldırılmasını içermektedir. Özellik çıkarımı için hem TF-IDF Vektörleştirme hem de Tek-Sıcaklık Kodlama teknikleri uygulanmıştır.
Makine Öğrenimi Modelleri: Lojistik Regresyon, Naive Bayes, SVM ve Rastgele Ormanlar gibi sınıflandırıcılar veri seti üzerinde değerlendirilmiş, modellerin karşılaştırılması için doğruluk ve sınıflandırma raporları üretilmiştir.
Derin Öğrenme Modeli: TensorFlow/Keras kullanılarak Embedding, LSTM ve Dense katmanlarına sahip ardışık bir model inşa edilmiştir.
