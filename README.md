**Machine Learning with Flight Fare Prediction Dataset Classification and Regression Model**
----------------------------------
![image](https://github.com/user-attachments/assets/c82f69bc-2481-4085-a18f-192d22ab8e33)



**Veri Seti:**
Bu veri seti, 1993'ten 2024'e kadar Amerika Birleşik Devletleri içindeki havayolu uçuş rotaları, tarifeler ve yolcu hacimlerine dair ayrıntılı bilgileri sunmaktadır. Veri seti, havaalanları arasındaki mesafeler, yolcu sayıları ve farklı havayolu taşıyıcıları tarafından sunulan tarifeleri içeren ölçümleri kapsamaktadır. Üç on yıl boyunca hava seyahati, fiyatlandırma ve taşıyıcı rekabetindeki trendleri analiz etmek için kapsamlı bir kaynak sağlar.

Veri seti şu özellikleri içermektedir:



1. **tbl**: 
   - Tabloya ait tanımlayıcı numara veya etiket.

2. **Year**: 
   - Verinin toplandığı veya kaydedildiği yıl (1993-2024).

3. **quarter**: 
   - Yılın çeyreği (1-4). Her yıl 4 çeyreğe ayrılır.

4. **citymarketid_1**: 
   - Kalkış şehri için pazar kimlik numarası.

5. **citymarketid_2**: 
   - Varış şehri için pazar kimlik numarası.

6. **city1**: 
   - Kalkış şehri adı.

7. **city2**: 
   - Varış şehri adı.

8. **airportid_1**: 
   - Kalkış havaalanı için benzersiz havaalanı kimliği.

9. **airportid_2**: 
   - Varış havaalanı için benzersiz havaalanı kimliği.

10. **airport_1**: 
    - Kalkış havaalanının IATA (Uluslararası Hava Taşımacılığı Birliği) kodu.

11. **airport_2**: 
    - Varış havaalanının IATA kodu.

12. **nsmiles**: 
    - Kalkış ve varış havaalanları arasındaki mesafe (mil cinsinden).

13. **passengers**: 
    - Uçuşta seyahat eden toplam yolcu sayısı.

14. **fare**: 
    - Uçuşun ortalama bilet fiyatı.

15. **carrier_lg**: 
    - En yüksek yolcu sayısına sahip havayolu şirketinin kodu.

16. **large_ms**: 
    - En büyük havayolunun pazardaki payı (yüzde olarak).

17. **fare_lg**: 
    - En büyük havayolunun ortalama bilet fiyatı.

18. **carrier_low**: 
    - En düşük bilet fiyatına sahip havayolu şirketinin kodu.

19. **lf_ms**: 
    - En düşük tarifeye sahip havayolunun pazar payı (yüzde olarak).

20. **fare_low**: 
    - En düşük bilet fiyatı.

21. **Geocoded_City1**: 
    - Kalkış şehri için coğrafi koordinatlar.

22. **Geocoded_City2**: 
    - Varış şehri için coğrafi koordinatlar.

23. **tbl1apk**: 
    - Uçuş rotası için benzersiz tanımlayıcı.
   

------------------------------------------------

**Model Seçimi**

Gözetimli ve gözetimsiz öğrenme algoritma skorlarına göre en iyi skora sahip olan model olan "linear regression" modeli ile hiperparametre optimizasyonuna devam ettik.

--------------------
**Proje Çıktıları**


Accuracy: 0.9489668040548067

Precision: 0.9423198653718485

Recall: 0.9443902891890638

F1 Score: 0.9433539412673878

----------------------------------
Model: Linear Regression

Test R-Squared Score: 0.93698


test_r2                                      0.94106

test_neg_mean_absolute_error                10.44058

test_neg_mean_squared_error                373.77968

test_neg_mean_absolute_percentage_error      0.04757

dtype: object

--------------------------------

