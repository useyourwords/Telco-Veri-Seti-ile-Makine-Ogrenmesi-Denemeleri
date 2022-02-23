# AMAÇ
- Lojistik Regresyon, Gaussian Naive Bayes ve KNN algoritmalarının sınıflandırma için kullanımlarını göstermek
- Confusion Matrix oluşturmak
  * Confusion Matrix, bir sınıflandırma problemindeki tahmin sonuçlarının bir özetidir. Doğru ve yanlış sınıflandırma sayıları tabloya yazılır.


     <img width="265" alt="image" src="https://user-images.githubusercontent.com/90156792/155323489-e28192a5-f8b0-4aba-8243-c732c8f9d5be.png">

  * **TP (True Positive):** Pozitif (class 1) tahmin ettin ve bu doğru.
  * **FP (False Positive):** Pozitif (class 1) tahmin ettin ve bu yanlış. Bu durum aynı zamanda 'Type 1 Error' olarak adlandırılır.
  * **TN (True Negative):** Negatif (class 0) tahmin ettin ve bu doğru.
  * **FN (False Negative):** Negatif (class 0) tahmin ettin ve bu yanlış. Bu durum aynı zamanda 'Type 2 Error' olarak adlandırılır.
      > <img width="242" alt="image" src="https://user-images.githubusercontent.com/90156792/155322302-a9f1941a-b145-4019-a64b-97b7ce7895ab.png">

      > <img width="230" alt="image" src="https://user-images.githubusercontent.com/90156792/155322396-5d9b7e75-1a41-4e3b-8036-7cbadcdd153d.png">
   
      > <img width="341" alt="image" src="https://user-images.githubusercontent.com/90156792/155322901-c5cb76f0-f75a-4eff-bf3a-e1dce35a34ef.png">
     
      > <img width="344" alt="image" src="https://user-images.githubusercontent.com/90156792/155322965-c724b6a0-7e8b-4bc4-ab86-dbdf5180462c.png">
- KNN algoritması için uzaklık ve komşu sayısı parametrelerini incelemek

# SONUÇ
|Algoritma Adı | Accuracy |
|--------------|--------|
|Lojistik Regresyon| 0.80 |
|Gaussian NB | 0.75 |
|KNN (k=2, metric=manhattan)| 0.86|
