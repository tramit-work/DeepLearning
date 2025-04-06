<div align="center">

# Project - Deep Learning

</div>

## *Đề tài: Sử dụng mô hình CNN để phân loại ảnh chất thải trong xây dựng mô hình Deep Learning*
## 1. Công nghệ sử dụng
- **Frameworks**: 
  - `Keras`
  - `Matplotlib`
  - `Numpy`
  - `OpenCV`
  - `OS`
  - `Scikit-learn`
  - `Shutil`
  - `Tensorflow`

## 2. Mô hình CNN
<div style="text-align: justify;">

<strong>CNN là một trong những mô hình mạnh mẽ nhất trong Deep Learning nhờ khả năng nhận diện, phân loại và học các mẫu không gian trong hình ảnh.

</div>

**VD:**
<p align="center">
  <img src="https://aicandy.vn/wp-content/uploads/2024/09/aicandy_CNN_arch.jpg" alt="" style="width: 70%; height: auto;">
<p align="right">
  <em>Convolutional Neural Networks (CNN) trong Deep Learning - AIcandy</em>
  
## 3.  Dữ liệu sử dụng
<div style="text-align: justify;">
Dữ liệu cho bài toán phân loại ảnh chất thải được thu thập từ Kaggle, có tên "Waste Classification Data".
</div>

**Bộ dữ liệu được chia thành ba phần:**
  
- **Train set dùng để huấn luyện mô hình.**

- **Validation set dùng để điều chỉnh các siêu tham số và theo dõi quá trình học.**

- **Test set dùng để đánh giá hiệu suất cuối cùng của mô hình trên dữ liệu chưa từng thấy.**

**Input:** Tập dữ liệu bao gồm nhiều hình ảnh của “organic” và “recyclable”.</br>
**Output:** Phân loại chính xác từng hình ảnh, xác định xem ảnh thuộc về “organic” hay “recyclable”.


