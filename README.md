# 📊 insurance-analysis  
## Regresyondan Ormana: Model Seçiminde Stratejik Yaklaşımlar

Bu projede, bireylerin demografik ve yaşam tarzı bilgilerine göre sağlık harcamalarını (charges) tahmin etmeyi amaçlayan farklı regresyon modelleri karşılaştırılmıştır. Modelleme sürecinde klasik istatistiksel yöntemler ile makine öğrenmesi teknikleri bir araya getirilmiş, yorumlanabilirlik ve tahmin gücü arasında stratejik bir denge arayışı vurgulanmıştır.

---

## 🔍 Kullanılan Veri Seti

Veri seti Kaggle üzerinden temin edilmiştir:  
🔗 [Insurance Dataset (Simple Linear Regression) - Kaggle](https://www.kaggle.com/datasets/taseermehboob9/insurance-dataset-simple-linear-regression)

### 📌 Değişkenler

- `age`: Kişinin yaşı  
- `sex`: Cinsiyet  
- `bmi`: Vücut kitle indeksi  
- `children`: Çocuk sayısı  
- `smoker`: Sigara içme durumu  
- `region`: Yaşanılan bölge  
- `charges`: Yıllık sağlık harcaması

---

## ⚙️ Kullanılan Yöntemler

Bu projede aşağıdaki modelleme teknikleri kullanılmıştır:

- ✅ **Lineer Regresyon** (`lm`)  
- 🛡️ **Robust Regresyon** (`rlm`)  
- ✴️ **Etkileşimli Modelleme** (`bmi * smoker`)  
- 🔁 **Logaritmik Dönüşüm**  
- 🌲 **Random Forest**  
- 🧬 **Lasso Regresyon**  
- 📏 **Ridge Regresyon**

---

## 📈 Model Değerlendirme ve Analizler

Model performansı aşağıdaki kriterlerle değerlendirilmiştir:

- Varsayım kontrolleri (Residual vs Fitted, Q-Q, Scale-Location, Leverage)  
- Multikolinearite (VIF değerleri)  
- Aykırı gözlem ve etkili nokta tespiti (Cook’s Distance)  
- Eğitim ve test seti R² farkı  
- Model karşılaştırmaları (RMSE, MAE, görsel analizler)

---

## 🖥️ Quarto ile Çalıştırma

Projeyi Quarto ile çalıştırmak için:  
RStudio üzerinde `.qmd` dosyasını açarak **"Render"** butonuna tıklayabilirsiniz.  
Alternatif olarak terminal üzerinden:

```bash
quarto render sigorta_quarto.qmd --output-dir docs --output-file index.html

