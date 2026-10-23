# DS201.R11.2-LAB2
**Sinh viên:** Đỗ Yến Nhi
**MSSV:** 24521259

Bài thực hành 2: Mạng neural tích chập (CNN). Notebook `LAB2_24521259.ipynb` gồm:

- **Bài 1:** Xây dựng và huấn luyện LeNet-5 (hai biến thể AvgPool và MaxPool) trên tập MNIST
- **Bài 2:** Xây dựng và huấn luyện GoogLeNet từ đầu trên tập VinaFood21 (21 lớp món ăn Việt Nam)

Mỗi mô hình được đánh giá trên tập test bằng accuracy, precision, recall và F1 (macro).

## Kết quả

| Mô hình | Dữ liệu | Accuracy | macro-F1 |
|---|---|---|---|
| LeNet-5 (AvgPool) | MNIST | 0.9839 | 0.9838 |
| LeNet-5 (MaxPool) | MNIST | 0.9882 | 0.9881 |
| GoogLeNet | VinaFood21 | 0.6625 | 0.6520 |

Nhận xét chi tiết nằm trong notebook, sau mỗi bài.

## Cách chạy

1. Mở `LAB2_24521259.ipynb` trên Google Colab, bật GPU
2. **MNIST:** tải `mnist_train.csv` và `mnist_test.csv`, đặt vào thư mục `Colab Notebooks/MNIST_CSV` trên Google Drive
3. **VinaFood21:** không cần tải trước, notebook tự tải và giải nén vào `/content`.
4. Chạy tuần tự các ô từ trên xuống.
