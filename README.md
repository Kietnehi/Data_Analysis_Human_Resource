# Dự Án Dự Đoán Nhân Viên Rời Công Ty

Dự án này sử dụng các thuật toán học máy để dự đoán khả năng một nhân viên sẽ rời công ty hoặc ở lại dựa trên các đặc điểm và dữ liệu liên quan đến nhân viên. Dự án sử dụng các phương pháp **Machine Learning**, **Fine-tuning** mô hình và có phần **Phân tích sâu vào dữ liệu** để đưa ra kết quả chính xác.

## Mục Tiêu Dự Án

Mục tiêu của dự án là:
- Xây dựng một mô hình học máy để dự đoán khả năng một nhân viên sẽ rời công ty.
- Phân tích các yếu tố có ảnh hưởng đến quyết định rời đi của nhân viên.
- Tối ưu hóa mô hình bằng cách sử dụng phương pháp **Fine-tuning** để cải thiện độ chính xác.

## Kết quả sau khi training
Kết quả accuracy cao nhất là 0.986 bằng sử dụng mô hình XGBoost
![image](https://github.com/user-attachments/assets/d2d660bf-75c0-4e85-a34f-ce114e49ae41)

Một số hình ảnh sau khi đã training 
![image](https://github.com/user-attachments/assets/726aed72-bbef-45b6-8939-51bc99f11dc7)
![image](https://github.com/user-attachments/assets/b35c50e0-0030-4b3f-b6e8-b46c0f77b12c)
![image](https://github.com/user-attachments/assets/82ea57ed-70c9-4e23-9d0c-6aaa5c015ab6)
![image](https://github.com/user-attachments/assets/8eb3e544-56bb-484a-9e6a-61cb1c69ef52)

## Yêu Cầu

Để chạy dự án này, bạn cần cài đặt các thư viện sau:

- **matplotlib**: Thư viện vẽ đồ thị.
- **pandas**: Thư viện xử lý và phân tích dữ liệu.
- **bokeh**: Thư viện trực quan hóa dữ liệu tương tác.
- **seaborn**: Thư viện vẽ đồ thị thống kê.
- **scikit-learn**: Thư viện học máy cơ bản.
1. Clone dự án về máy tính của bạn:
   ```bash
   git clone https://github.com/your-username/project-name.git
   cd project-name
2.Cài đặt các thư viện cần thiết từ file requirements.txt:
  ```bash
  pip install -r requirements.txt
