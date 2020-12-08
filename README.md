# AI_project
Chương trình nhận diện tiền Việt Nam
# 1. Yêu cầu cài đặt đối với chương trình:
  Cài đặt Python, Cuda và CuDNN.
  ```
  Python 3.8.2 (https://www.python.org/downloads/release/python-382/)
  ```
  ```bash
  Cuda 10.1 (https://developer.nvidia.com/cuda-10.1-download-archive-base)
  ```
  ```bash
  CuDNN 7.6.5 (https://developer.nvidia.com/rdp/cudnn-archive)
  ```
  Sau đó mở terminal cài đặt tensorflow-gpu
  ```bash
  py -m pip install tensorflow-gpu
  ```
 # 2. Cài đặt thư viện cần thiết
  Mở terminal, cd vào thư mục VietnameseMoney_Classify, gõ lệnh
  ```bash
  py -m pip install -r setup.txt
  ```
  # Lưu ý
  Có thể sử dụng các phiên bản khác, tuy nhiên để môi trường chạy và thư viện tương thích với nhau, nên cài đặt các phiên bản được nêu trên để tránh lỗi xảy ra trong quá trình chạy
