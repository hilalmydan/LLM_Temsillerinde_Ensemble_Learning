# LLMlerin Temsilleri Üzerinde Ensemble
<p align="center">
<img src="https://github.com/hilalmydan/LLMModels/blob/main/image/LLM%20Models.png" alt="rule-based" width="450" height="400"/>
<p>
  
## Proje Özeti

Bu çalışmada, Dil Modeli (LLM) temsillerinin geliştirilmesi amacıyla ensemble yöntemleri olan Bagging, AdaBoost, Random Forest, Rotation Forest ve SVM gibi algoritmaların karşılaştırmalı analizi yapılmaktadır. Ayrıca, bu yöntemlerin hiperparametre optimizasyonu süreci detaylı bir şekilde incelenmektedir. Türkçe metin veri kümesi üzerinde gerçekleştirilen deneylerde, farklı ensemble yöntemlerinin performansları karşılaştırılarak en etkili yöntem belirlenmeye çalışılmaktadır.

Çalışma aynı zamanda büyük ve küçük BERT modellerinin kullanımının LLM temsilleri üzerindeki etkilerini ele almaktadır. Bu bağlamda, büyük BERT modellerinin performansıyla küçük BERT modellerinin performansı arasındaki farklılıklar ve avantajlar detaylı bir şekilde incelenmektedir. Türkçe metin veri kümesi üzerinde yapılan deneylerle, her iki BERT modelinin de LLM temsillerini geliştirmedeki katkıları ve sınırlamaları ortaya konmaktadır.

Sonuç olarak, bu çalışma LLM temsillerini optimize etmek amacıyla ensemble yöntemlerinin seçimi, hiperparametre optimizasyonu ve farklı BERT modellerinin kullanımı konularında kapsamlı bir analiz sunarak, dil işleme alanındaki araştırmacılara değerli bir kaynak sağlamaktadır. 

## Veri Setleri
* Data klasörü altında bulunann veri setleri LLM modelleri ile çalışılabilecek uygunluktaki "yorumsepeti" ve "E-Ticaret" adlarında Türkçe veri setleridir. Bu projede yorumsepeti ve E-Ticaret veri setlerinin yanında Huggging face'teki interpress_news_category_tr_lite veri setinden de 3 farklı veri seti türetilerek toplamda 5 adet veri seti üzerinde işlemler yapılmıştır.
* Hugging faceten alınan veri setinden oluşturulan ilk veri seti Türkçe haber verilerini içeren ve sınıfları magazin ve teknoloji olan iki sınıflı bir veri seti olarak tasarlanmıştır. İkinci oluşturulan veri setinin sınıfları eğitim ve spordur. 3. oluşturulan veri setinin sınıfları ise kültürsanat ve ekonomidir.
  
