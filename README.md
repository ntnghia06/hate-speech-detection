# hate speech detection

Huấn luyện mô hình lần lượt các mô hình Multinomial Naive Bayes, Bernoulli Naive Bayes và Logistic Regression để dự đoán thái độ của một bình luận trong bộ ngữ liệu đã cho:

1. Tiền xử lý ngữ liệu:
- Các thao tác tiền xử lý và lý do sử dụng từng thao tác.
- Số lượng feature được chọn.
- 100 feature xuất hiện nhiều nhất và 100 feature xuất hiện ít nhất.
- Số lượng mẫu theo mỗi lớp.
- Số lượng feature nhiều nhất, ít nhất, và trung bình có trong mỗi mẫu theo từng lớp.
2. Huấn luyện mô hình:
- Cài đặt thủ công để huấn luyện 1 mô hình
- Sử dụng thư viện Scikit-learn huấn luyện 1 mô hình tương ứng để so sánh.
3. Đánh giá kết quả dự đoán:
- Ma trận nhầm lẫn (confusion matrix) theo từng mô hình.
- Các độ đo P, R, F1 cho từng lớp theo từng mô hình.
4. So sánh kết quả mô hình tự cài đặt với mô hình mặc định từ thư viện Scikit-learn.
