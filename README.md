# Mô hình Dự đoán Môn học và Điểm số của Sinh viên sử dụng LSTM
## Giới thiệu
Dự án này nhằm phát triển mô hình LSTM (Long Short-Term Memory) để dự đoán môn học sinh viên có khả năng học trong kỳ tiếp theo và điểm số mà họ có thể đạt được trong môn học đó.
## Thông tin:
- data: Chứa dữ liệu đầu vào, bao gồm thông tin về các môn học, điểm số, và lịch sử học tập của sinh viên sử dụng để huấn luyện mô hình của chúng ta. Trong file `data.xlsx` có chứa 4 sheet và ta sẽ đọc sheet `Dulieu0205` để sử dụng vì nó chứa thông tin quan trọng để huấn luyện mô hình.
- notebooks: chứa các bước phân tích, xử lý dữ liệu và huấn luyện mô hình LSTM.
## Cài đặt các thư viện cần thiết:
```bash
pip install tensorflow pandas numpy scikit-learn
```
Tải dữ liệu: file `data.xlsx`
Chạy mô hình: Sử dụng notebook để chạy mô hình từ bước xử lý dữ liệu đến huấn luyện và dự đoán.
## Kết quả và Đánh giá
- `accuracy = 91,33%` - một độ chính xác cao với mô hình LSTM
- `loss = 34.8390` khá thấp