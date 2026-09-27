# Phát Hiện Hành Vi Bạo Lực Qua Video Giám Sát

Dự án nghiên cứu và xây dựng mô hình Học sâu (Deep Learning) kết hợp xử lý chuỗi thời gian (BiLSTM) nhằm tự động nhận diện và phát hiện các hành vi bạo lực từ video quay bởi camera giám sát.

## Cấu trúc dự án
- `Đồ Án Phát Hiện Bạo Lực (1).ipynb`: Mã nguồn Jupyter Notebook thực hiện tiền xử lý dữ liệu, trích xuất đặc trưng pose/keypoints, huấn luyện và đánh giá mô hình.
- `clips/`: Thư mục chứa các file đoạn clip phụ trợ.

## Bộ dữ liệu (Dataset), Mô hình (.keras) & Video Kết quả
## Tài nguyên dự án (Google Drive)
- **Bộ dữ liệu gốc (`Dataset/`):** [Bấm vào đây để tải Dataset]([DÁN_LINK_DATASET_VÀO_ĐÂY](https://drive.google.com/drive/folders/1zp___kyLCa5bEJ4h0yHKrGVYOpGBogrd?usp=drive_link)
- **Dữ liệu điểm Pose (`Pose_Keypoints/`):** [Bấm vào đây để tải Pose Keypoints]([DÁN_LINK_POSE_KEYPOINTS_VÀO_ĐÂY](https://drive.google.com/drive/folders/1xUmEIHcG7z7X7CkbnFFgNz27a3HqnYKW?usp=drive_link)
- **Thư mục Video kiểm thử (`video_test/`):** [Bấm vào đây để tải Video Test]([DÁN_LINK_VIDEO_TEST_VÀO_ĐÂY](https://drive.google.com/drive/folders/1RIqPpKHtLaXYKrNBzZOm6UoxaO4cPYW2?usp=sharing)
- **Thư mục Video kết quả (`video_KetQua/`):** [Bấm vào đây để xem Video Kết Quả]([DÁN_LINK_VIDEO_KETQUA_VÀO_ĐÂY](https://drive.google.com/drive/folders/1PQkepazy9Y7juD2OgGSy5uFQ_wYmhdU3?usp=sharing)
- **Mô hình Pose (`bilstm_pose_best.keras`):** [Bấm vào đây để tải Model Pose Best]([DÁN_LINK_BILSTM_POSE_BEST_VÀO_ĐÂY](https://drive.google.com/file/d/1vHZAYmax5R2cYw8R2zGvzdYnYAZwT8jC/view?usp=sharing)
- **Mô hình chính (`bilstm_best_model.keras`):** [Bấm vào đây để tải Model Best]([DÁN_LINK_BILSTM_BEST_MODEL_VÀO_ĐÂY](https://drive.google.com/file/d/1ZGIM9eYLLvt7pCBBh6iYEWMOPXT4Nq2t/view?usp=sharing)
## Công nghệ sử dụng
- **Ngôn ngữ:** Python
- **Thư viện:** TensorFlow / Keras, OpenCV, NumPy, Pandas, Matplotlib
