# **Prediksi Pelanggan Churn di Perusahaan Telekomunikasi Menggunakan Machine Learning** <br>

## **Deskripsi**
Proyek ini bertujuan untuk memprediksi pelanggan yang mungkin berhenti berlangganan (churn) dari layanan perusahaan telekomunikasi 
menggunakan teknik machine learning. Dengan menggunakan dataset historis pelanggan beserta berbagai fitur terkait, 
proyek ini mengembangkan model machine learning yang dapat memprediksi pelanggan churn. 
Prediksi ini membantu perusahaan untuk mengidentifikasi pelanggan potensial yang berisiko churn sehingga mereka dapat mengambil 
tindakan pencegahan yang sesuai untuk mempertahankan pelanggan tersebut.

## **Fitur-fitur**
- Data Pelanggan: Prediksi ini menggunakan dataset pelanggan yang mencakup informasi seperti durasi langganan, jenis layanan, biaya bulanan, penggunaan layanan tambahan, dll. Dataset dapat dilihat 
[di sini](https://github.com/yanacunanda/customerchurnpredictionintelecommunicationcompany/blob/main/data_telco_customer_churn.csv) <br>
- Pemodelan Machine Learning: Berbagai algoritma machine learning seperti Decision Tree, Random Forest, Logistic Regression, Xgboost, K-Neighbors, Adaboost, Voting Classifier, dan Stacking Classifier
digunakan untuk membangun model prediksi churn.
- Evaluasi Model: Proses evaluasi model melibatkan metrik seperti presisi, recall, dan F2-score untuk mengukur kinerja model.

## **Pemahaman tentang dataset yang digunakan**
Dataset yang digunakan terdiri dari 11 kolom yang memuat informasi yang terkait dengan perilaku pelanggan.

|Nama Kolom| Deskripsi|
|-----------|------|
|Dependents|Pelanggan memiliki tanggungan atau tidak|
|tenure|Jumlah bulan berlangganan|
|OnlineSecurity|Pelanggan berlangganan online security atau tidak <br>(yes, no, no internet service)|
|OnlineBackup|Pelanggan berlangganan online backup atau tidak <br>(yes, no, no internet service)|
|InternetService|Pelanggan berlangganan internet service atau tidak<br> (yes, no)|
|DeviceProtection|Pelanggan berlangganan device protection atau tidak <br>(yes, no, no internet service)|
|TechSupport|Pelanggan berlangganan tech support atau tidak<br>(yes, no, no internet service)|
|Contract|Tipe kontrak yang digunakan berdasarkan durasi<br>(month-to-month, two year, dan one year)|
|PaperlessBilling|Bentuk tagihan yang digunakan dalam bentuk paperless atau tidak <br>(yes, no)|
|MonthlyCharges|Jumlah tagihan setiap bulan|
|Churn|Pelanggan berpindah ke pesaing atau tidak <br>(yes, no)|

## **Final model**
Model terbaik yang digunakan dalam prediksi ini dapat dilihat [di sini](https://github.com/yanacunanda/customerchurnpredictionintelecommunicationcompany/blob/main/TelcoCustumerChurn_ADBmodel.sav)
