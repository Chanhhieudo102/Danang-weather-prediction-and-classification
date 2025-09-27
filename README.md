# Danang-weather-prediction-and-classification
Bài toán của nhóm nhằm xây dựng mô hình dự đoán nhiệt độ thực tế cảm nhận dựa trên các thông số thời tiết ở khu vực thành phố Đà Nẵng .  
Dữ liệu được thu thập bằng API từ trang web weatherapi.com với hơn 8000 mẫu dữ liệu mô tả đặc điểm thời tiết theo mỗi giờ năm 2024.
# 🌦️ Danang Weather Prediction and Classification
- Dữ liệu được thu thập từ [WeatherAPI](https://www.weatherapi.com/).  
- Dataset gồm hơn **8000 mẫu dữ liệu** theo từng giờ trong năm 2024.  
- Các đặc trưng gồm: nhiệt độ, độ ẩm, áp suất, tốc độ gió, lượng mưa...  

---
## 📂 Cấu trúc thư mục
📂 Danang-weather-prediction-and-classification
┣ 📂 data/ # Dữ liệu thô và dữ liệu tiền xử lý

┃ ┣ raw_data_train.csv

┃ ┗ raw_data_test.csv

┣ 📂 notebooks/ # Notebook theo từng bước xử lý

┃ ┣ Crawl.ipynb # Crawl dữ liệu từ Open-Meteo API

┃ ┣ FeatureEngineer.ipynb # Làm sạch, xử lý dữ liệu, trích xuất đặc trưng

┃ ┣ ClassificationModel.ipynb# Mô hình phân loại thời tiết

┃ ┗ RegressionModel.ipynb # Mô hình hồi quy nhiệt độ

┣ README.md # Tài liệu mô tả dự án

