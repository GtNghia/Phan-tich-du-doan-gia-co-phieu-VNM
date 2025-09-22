

Giới thiệu

Chương trình này được xây dựng để dự đoán giá cổ phiếu của Vinamilk (mã VNM) bằng cách sử dụng mô hình học máy mạng nơ-ron hồi quy dài-ngắn hạn (LSTM). Mô hình LSTM được đào tạo trên dữ liệu giá cổ phiếu lịch sử từ năm 2013 đến năm 2025 để tìm ra mối quan hệ phụ thuộc theo thời gian, từ đó đưa ra dự báo cho các ngày trong tương lai.

Các công cụ được sử dụng

Chương trình sử dụng các thư viện Python sau để thực hiện các bước từ tiền xử lý dữ liệu đến xây dựng và đánh giá mô hình:

pandas: Dùng để đọc và xử lý dữ liệu từ file CSV.

numpy: Hỗ trợ các phép toán xử lý dữ liệu số.

matplotlib.pyplot: Được sử dụng để vẽ biểu đồ.

sklearn.preprocessing.MinMaxScaler: Dùng để chuẩn hóa dữ liệu, đưa dữ liệu về cùng một khoảng giá trị.

keras và tensorflow.keras: Các thư viện cốt lõi để xây dựng mô hình mạng nơ-ron, bao gồm các lớp như Sequential (đầu vào), LSTM (học phụ thuộc), Dropout (tránh học tủ) và Dense (đầu ra).

sklearn.metrics: Dùng để đánh giá độ chính xác của mô hình thông qua các chỉ số như r2_score, mean_absolute_error và mean_absolute_percentage_error.
