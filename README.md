# 🍱 Online Food Delivery - Müşteri Davranış Analizi

Bu proje, Bangalore bölgesindeki çevrimiçi yemek siparişi verilerini kullanarak müşteri segmentasyonu, demografik analiz ve geri bildirim trendlerini incelemektedir. Veri odaklı bir **Teknik İş Analisti** bakış açısıyla, ham veriden anlamlı iş içgörüleri üretmek amacıyla hazırlanmıştır.

## 🚀 Projenin Amacı
Platform kullanıcılarının demografik yapılarını (Yaş, Gelir, Eğitim vb.) çözümleyerek, hangi faktörlerin "Pozitif" geri bildirim ve "Sipariş Tekrarı" (Output) üzerinde etkili olduğunu saptamak ve iş stratejilerine veri desteği sağlamaktır.

## 🛠 Kullanılan Teknolojiler
* **Python 3.x**
* **Pandas & NumPy:** Veri manipülasyonu ve temizleme.
* **Matplotlib & Seaborn:** Veri görselleştirme (Countplots, Stacked Bar Charts).
* **Jupyter Notebook:** Geliştirme ortamı.

## 📋 Veri İşleme ve Analiz Süreci
Proje, notebook içerisinde adım adım şu aşamalardan geçmektedir:

1.  **Veri Temizleme:** Gereksiz sütunların (`Unnamed: 12`) kaldırılması ve eksik verilerin kontrolü.
2.  **Feature Engineering:** Analizi derinleştirmek için yaş verilerinin gruplandırılması (`AgeGroup`).
3.  **Keşifsel Veri Analizi (EDA):**
    * **Yaş Grubu Analizi:** En yüksek sipariş yoğunluğunun 19-25 yaş aralığında olduğunun tespiti.
    * **Eğitim & Aile İlişkisi:** Aile büyüklüğüne göre eğitim seviyelerinin sipariş alışkanlıklarına etkisi.
    * **Gelir Dağılımı:** Aylık gelirin geri bildirim (Feedback) üzerindeki etkisi.
    * **Cinsiyet ve Meslek Dağılımı:** Öğrenci ve çalışan profillerinin platform kullanımı.

## 📊 Öne Çıkan Bulgular
* **Hedef Kitle:** Verilere göre en aktif kullanıcı segmenti **21-25 yaş** aralığındaki bekarlar ve öğrencilerden oluşmaktadır.
* **Geri Bildirim:** Pozitif geri bildirimlerin, belirli gelir grupları ve eğitim seviyeleriyle yüksek korelasyona sahip olduğu gözlemlenmiştir.
* **Sipariş Tekrarı:** "Yes" (Sipariş veren) kitlesinde aile büyüklüğü ve eğitim durumu dağılımı kritik bir metriktir.

## 📁 Dosya Yapısı
* `Online_Foods.ipynb`: Tüm analiz, veri temizleme ve görselleştirme kodlarını içeren ana dosya.
* `onlinefoods.csv`: Analizde kullanılan 388 kayıtlık veri seti.

## ⚙️ Kurulum ve Çalıştırma
1. Bu repoyu klonlayın:
   ```bash
   git clone [https://github.com/haticebahar/online_foods.git](https://github.com/haticebahar/online_foods.git)
