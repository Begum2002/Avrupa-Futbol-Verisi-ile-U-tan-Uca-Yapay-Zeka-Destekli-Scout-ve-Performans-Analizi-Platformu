# Avrupa-Futbol-Verisi-ile-U-tan-Uca-Yapay-Zeka-Destekli-Scout-ve-Performans-Analizi-Platformu
Kaggle üzerinden geniş kapsamlı European Soccer Database kullanılarak, kulüplerin transfer stratejilerini optimize eden, veriye dayalı bir scouting,karar destek sistemi geliştirilmiştir. Proje, ETL, makine öğrenimi ile gelecek tahminine gibi veri bilimi süreçlerini icerir.Tools:BigQuery (SQL), Python (Pandas, Scikit-learn, Plotly), Looker Studio.

Temel Sorumluluklar ve Kazanımlar:

Veri Yönetimi (BigQuery & SQL): +25.000 maç ve oyuncu verisi BigQuery üzerinde birleştirildi (JOIN), eksik veriler temizlendi ve analize hazır hale getirildi.

Başarı Faktörlerinin Belirlenmesi (Random Forest): Oyuncu reytinglerini etkileyen en kritik faktörler analiz edildi. Hızın aksine, "Pas" ve "Oyun Görüşü"nün elit seviyede daha belirleyici olduğu istatistiksel olarak kanıtlandı.

Oyuncu Segmentasyonu (K-Means Clustering): Oyuncular geleneksel mevkiler yerine; yetenek profillerine göre "Gizli Cevherler (Wonderkids)", "Elit Yıldızlar" ve "Görev Adamları" olarak yapay zeka ile kümelendi.

Gelecek Tahmini (Predictive Modeling): Regresyon modelleri kullanılarak oyuncuların yaşa bağlı gelişim eğrileri analiz edildi ve gelecek 2 yıl içindeki potansiyel reytingleri tahminlendi.

Benzerlik Analizi (Recommendation System): Yıldız oyuncuların (örn: Messi) istatistiksel "Dijital İkizleri" bulunarak, bütçe dostu alternatif transfer hedefleri belirlendi.

Görselleştirme (Looker Studio): Scout ekiplerinin ligleri ve oyuncuları dinamik olarak filtreleyebileceği, yaş/potansiyel analizi yapan interaktif dashboardlar tasarlandı.

<img width="1524" height="916" alt="image" src="https://github.com/user-attachments/assets/78fe1ac2-78df-409a-8bd2-e9dff24eddd8" />

<img width="1506" height="997" alt="image" src="https://github.com/user-attachments/assets/46f73391-0cb1-402f-a95d-6ec792e69781" /> 

<img width="1452" height="971" alt="image" src="https://github.com/user-attachments/assets/1c37e0b3-6d80-4490-afac-c2c2aaca4ec3" /> 

<img width="1848" height="949" alt="image" src="https://github.com/user-attachments/assets/d0fab0c8-4fe1-4de6-a585-4d5be79eed89" />

<img width="1718" height="878" alt="image" src="https://github.com/user-attachments/assets/a06bfbc1-a7bb-4535-874d-85e63003a662" />

<img width="1845" height="941" alt="image" src="https://github.com/user-attachments/assets/13718e97-a517-4787-8826-b85db9caf96a" />

looker studio link:https://lookerstudio.google.com/reporting/af507232-04d0-4b91-a35e-10291edd7641
colab link:https://colab.research.google.com/drive/1PVDvIYV6fxVg8YYG6dhj84yX3iBstXeX?usp=sharing



