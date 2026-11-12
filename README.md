# SoftITo | Veri Analitiği – 2

İstanbul Ticaret Odası (İTO) bünyesindeki **SoftITo Yazılım-Bilişim Akademisi Veri Analitiği – 2** programı kapsamında hazırladığım ödevler ve bitirme projesi.

Sağlık, eğitim, perakende ve sosyal medya verileri üzerinde veri temizleme, keşifsel veri analizi, istatistiksel testler, görselleştirme ve makine öğrenmesi ile metin sınıflandırma çalışmaları yaptım.

<p align="left">
  <a href="https://github.com/KULLANICI_ADIN" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/LINKEDIN_KULLANICI_ADIN" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://medium.com/@sumeyraeraslan04" target="_blank">
    <img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/>
  </a>
</p>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4051B5?style=flat)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 🎓 Bitirme Projesi: Makine Öğrenmesi Yöntemleriyle Siber Zorbalık Tespiti ve Psikolojik Etki Analizi

Siber zorbalık iki açıdan incelendi: mağduriyetin öğrencilerin ruh sağlığıyla ilişkisi ve sosyal medyadaki zorbalık içeriklerinin makine öğrenmesiyle tespit edilip edilemeyeceği.

| Çalışma | Veri | Yöntem | Öne çıkan sonuç |
|---|---|---|---|
| [Psikolojik etki analizi](bitirme%20projesi/anket_analizi.ipynb) | 561 üniversite öğrencisi anketi (DASS-21, siber mağduriyet ölçeği) | Veri kalitesi kontrolü, Spearman korelasyonu, ki-kare testi, lojistik regresyon | Orta ve üzeri depresyon %30,1, anksiyete %44,0; mağduriyet ile belirtiler arasında zayıf ama anlamlı pozitif ilişki |
| [Zorbalık türü sınıflandırma](bitirme%20projesi/metin_siniflandirma.ipynb) | ~47.700 İngilizce tweet (6 sınıf), ~5.800 Bangla yorum (5 sınıf) | TF-IDF + lojistik regresyon, çelişkili etiket temizliği | İngilizce makro F1 = 0,869; Bangla makro F1 = 0,529 |
| [Türkçe zorbalık tespiti](bitirme%20projesi/turkce_zorbal%C4%B1k_tespiti.ipynb) | 5.000 Türkçe tweet + 25 sayısal özellik | TF-IDF + lojistik regresyon, popülerlik kontrol deneyi | Yalnızca beğeni + retweet ile F1 = 0,813, metin modeline (0,869) çok yakın: veri setinde hesap popülerliği yanlılığı var |

📄 Detaylı rapor: [Siber Zorbalık Tespiti ve Etki Analizi (PDF)](bitirme%20raporu/Siber_Zorbal%C4%B1k_Tespiti_Etki_Analizi.pdf)

---

## 📂 Ödevler

| # | Ödev | Veri | Yapılanlar | Araçlar |
|---|---|---|---|---|
| 1 | [Kronik Hastalık İzlem Analizi](1.%20%C3%B6dev/113_izlem_veriseti_analiz.ipynb) | ~101.000 kayıtlık hastalık izlem verisi | Türkiye ve İstanbul karşılaştırması, yaş ve cinsiyete göre dağılım, sigara/alkol kullanımının hastalıklarla ilişkisi | Pandas |
| 2 | [Pandas 01](2.%20%C3%B6dev/13_Pandas_01.ipynb) | Bestsellers, Mount Everest ölümleri, film başlıkları (TSV) | Veri okuma, eksik değer analizi, indeks ve ayırıcı ayarları, sütun adlandırma | Pandas |
| 3 | [Pandas 02](3.%20%C3%B6dev/13_Pandas_02.ipynb) | Amazon bestsellers | Series işlemleri, tekil değerler, sıklık analizi, pasta/çubuk grafik ve histogram | Pandas, Matplotlib |
| 4 | [İstanbul Satış ve Hava Durumu Raporu](4.%20%C3%B6dev/113_analiz.pbix) | İstanbul AVM satış verisi + hava durumu | Takvim tablosu, TL/USD ciro, kategori ve AVM bazlı analiz, sıcaklık ve yağışın ciroya etkisi | Power BI, DAX |
| 5 | [Öğrenci Başarı Değerlendirmesi](5.%20%C3%B6dev/13.ipynb) | Sınav notu ve değerlendirme puanları | Normalizasyon, en başarılı öğrenci ve gruplar, günlük başarı trendi, korelasyon (r ≈ 0,89) | Pandas, Matplotlib |

---

## ⚙️ Kurulum ve Kullanım

```bash
git clone https://github.com/KULLANICI_ADIN/REPO_ADI.git
cd REPO_ADI
pip install pandas numpy matplotlib scipy scikit-learn statsmodels pyreadstat openpyxl jupyter
jupyter notebook
```

Power BI raporunu (`.pbix`) açmak için Power BI Desktop gerekir.

---

> Bu depo kişisel proje portföyümdür; İTO veya SoftITo'nun resmî deposu değildir.
