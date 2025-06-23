<!-- Banner -->
<p align="center">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin" style="border: none;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology">
  </a>
</p>

<h1 align="center"><b>NHẬP MÔN THỊ GIÁC MÁY TÍNH</b></h>

## THÀNH VIÊN NHÓM
| STT    | MSSV          | Họ và Tên              |Chức Vụ    | Github                                                  | Email                   |
| ------ |:-------------:| ----------------------:|----------:|--------------------------------------------------------:|-------------------------:
| 1      | 23520514      | Đoàn Thái Hoàng        |Nhóm trưởng|[thaihoang104569](https://github.com/thaihoang104569)    |23520514@gm.uit.edu.vn   |
| 2      | 23520070      | Phạm Ngô Quốc Anh      |Thành viên |[anteeeeeeee](https://github.com/anteeeeeeee)            |23520070@gm.uit.edu.vn   |

## GIỚI THIỆU MÔN HỌC
* **Tên môn học:** Nhập môn thị giác máy tính
* **Mã môn học:** CS231
* **Mã lớp:** CS231.P22
* **Năm học:** HK2 (2024 - 2025)
  
## ĐỒ ÁN CUỐI KÌ - Phân loại lỗi bề mặt ốc vít

### 1. Giới thiệu đồ án
Đồ án **CS231: Nhập môn Thị giác máy tính** phát triển hệ thống tự động phân loại lỗi bề mặt ốc vít.
#### Mục tiêu
- Tự động phân loại ốc vít theo các lớp lỗi bề mặt ốc vít dựa trên ảnh chụp.
- Thay thế kiểm tra thủ công, nâng cao hiệu quả kiểm soát chất lượng trong sản xuất.

#### Phương pháp
- **HOG + SVM**: Sử dụng trích xuất đặc trưng HOG kết hợp với mô hình SVM.
- **EfficientNet-B0**: Áp dụng mô hình học sâu với chiến lược fine-tuning.

#### Dữ liệu
- Tập dữ liệu gồm ảnh ốc vít, chia thành các tập huấn luyện, kiểm tra và đánh giá, chi tiết trong báo cáo.

#### Ứng dụng
- Tích hợp vào dây chuyền sản xuất để phát hiện sản phẩm lỗi tự động theo thời gian thực.

#### Nội dung kho lưu trữ
- Tăng cường dữ liệu: [data-augmentation.ipynb](https://github.com/thaihoang104569/CS231.P22/blob/main/Final%20Project/Code/data-augmentation.ipynb).
- Triển khai mô hình HOG + SVM: [hog-svm.ipynb](https://github.com/thaihoang104569/CS231.P22/blob/main/Final%20Project/Code/hog-svm.ipynb).
- Triển khai mô hình EfficientNet-B0: [efficientnetb0.ipynb](https://github.com/thaihoang104569/CS231.P22/blob/main/Final%20Project/Code/efficientnetb0.ipynb).
- Báo cáo chi tiết của đồ án: [Report.pdf](https://github.com/thaihoang104569/CS231.P22/blob/main/Final%20Project/Report.pdf).

### 2. Yêu cầu cài đặt
- Python 3.7+
- Thư viện: `tensorflow`, `scikit-learn`, `scikit-image`, `numpy`, `opencv-python`, `matplotlib`, `seaborn`, `tqdm`, `joblib`

### 3. Hướng dẫn chạy
1. Chuẩn bị dữ liệu với cấu trúc phù hợp, được viết chi tiết trong báo cáo.
2. Cài đặt python
3. Chạy huấn luyện SVM: `hog-svm.ipynb`
4. Chạy huấn luyện EfficientNetB0: `efficientnetb0.ipynb`
