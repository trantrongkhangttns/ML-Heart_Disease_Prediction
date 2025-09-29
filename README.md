# Heart Disease Prediction

Dự án Machine Learning dự đoán **nguy cơ đau tim** dựa trên các thông số sức khoẻ trong dataset kaggle heart disease.

## Mục tiêu
- Áp dụng các thuật toán Machine Learning để phân loại bệnh nhân có nguy cơ bệnh tim hay không.
- Thực hành quy trình **Data Analysis → Feature Engineering → Model Training → Evaluation**.
- So sánh hiệu quả của các mô hình khác nhau.

## 📊 Dataset
- Nguồn: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
- Bao gồm các thông số:
age
sex
chest pain type (4 values)
resting blood pressure
serum cholestoral in mg/dl
fasting blood sugar > 120 mg/dl
resting electrocardiographic results (values 0,1,2)
maximum heart rate achieved
exercise induced angina
oldpeak = ST depression induced by exercise relative to rest
the slope of the peak exercise ST segment
number of major vessels (0-3) colored by flourosopy
thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
- Nhãn mục tiêu: `target` (yes hoặc no).

## ⚙️ Công nghệ sử dụng
- Python (NumPy, Pandas, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, Random Forest, v.v.)

## 🚀 Cách chạy dự án
1. Clone repo:
   ```bash
   git clone https://github.com/trantrongkhangttns/ML-Heart_Disease_Prediction.git
   cd ML-Heart_Disease_Prediction
