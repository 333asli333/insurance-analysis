# insurance-analysis
Regresyondan Ormana: Model Seçiminde Stratejik Yaklaşımlar
Bu projede, bireylerin demografik ve yaşam tarzı bilgilerine göre sağlık harcamalarını (charges) tahmin etmeyi amaçlayan farklı regresyon modelleri karşılaştırılmıştır. Modelleme sürecinde klasik istatistiksel yöntemler ile makine öğrenmesi teknikleri bir araya getirilmiş, yorumlanabilirlik ve tahmin gücü arasında stratejik bir denge arayışı vurgulanmıştır.

🔍 Kullanılan Veri Seti
Veri seti Kaggle üzerinden temin edilmiştir:
🔗 Insurance Dataset (Simple Linear Regression) - Kaggle

Veri seti aşağıdaki değişkenleri içermektedir:

age: Kişinin yaşı

sex: Cinsiyet

bmi: Vücut kitle indeksi

children: Çocuk sayısı

smoker: Sigara içme durumu

region: Yaşanılan bölge

charges: Yıllık sağlık harcaması

⚙️ Kullanılan Yöntemler
Bu projede aşağıdaki modelleme teknikleri kullanılmıştır:

✅ Lineer Regresyon (lm)

🛡️ Robust Regresyon (rlm)

✴️ Etkileşimli Modelleme (bmi * smoker)

🔁 Logaritmik Dönüşüm

🌲 Random Forest

🧬 Lasso Regresyon

📏 Ridge Regresyon

📈 Model Değerlendirme ve Analizler
Model performansı aşağıdaki kriterlerle değerlendirilmiştir:

Varsayım kontrolleri (residual vs fitted, Q-Q, leverage analizi)

Multikolinearite (VIF değerleri)

Aykırı gözlem ve etkili nokta tespiti (Cook’s Distance)

Test ve eğitim seti R² farkı

Model karşılaştırmaları (RMSE, MAE, görsel karşılaştırmalar)

🖥️ Quarto ile Çalıştırma
Projeyi Quarto ile render etmek için:
RStudio üzerinde .qmd dosyasını açarak "Render" butonuna tıklayabilirsiniz.


🧠 Neler Öğrendim?
Klasik modellerde varsayım ihlallerini nasıl tespit ederim?

Etkileşim terimleri modeli nasıl geliştirir?

Robust regresyon ne zaman tercih edilir?

Yüksek tahmin gücü için Random Forest ve düzenlileştirilmiş modellerin rolü nedir?

Yorumlanabilirlik ve performans arasında denge kurmak neden önemlidir?

📬 Geri Bildirim ve Katkı
Bu projeyi öğrenme amacıyla geliştirdim. Geliştirme fikirleri, katkılar veya önerileriniz varsa LinkedIn üzerinden bana ulaşabilir ya da doğrudan PR gönderebilirsiniz.


