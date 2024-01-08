# Manufacturing Dashboard

## Giới thiệu
Chạy thuật toán LSTM để dự báo RUL trên 4 tập dataset khác nhau 
Các tập dataset bao gồm các dữ liệu cảm biến thu thập được từ các machine với 21 cảm biến và 3 cấu hình hoạt động

## Cài đặt 

1. Yêu cầu môi trường 
- Python 3.x
- Jupyter notebbook

2. Cài đặt thư viện 
- [Numpy] - `pip install numpy`
- [Pandas] - `pip install pandas`
- [Matplotlib] - `pip install matplotlib`
- [Keras] - `pip install keras`
- [sklearn] - `pip install sklearn`
- [h5py] - `pip3 install h5py`

3. Kết quả
Sau đây là kết quả sau khi chạy thử nghiệm trên 4 tập dataset

|    |      LSTM            | 
| ------------- |:-------------| 
| FD001       | RMSE: 16.14 |
| FD002      | RMSE: 24.49     | 
|  FD003    | RMSE: 16.18    | 
| FD004      | RMSE: 28.17  | 
