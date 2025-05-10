
# 📽️ README - Giấu tin trong video với nhiều kỹ thuật PVD

Dự án thực hiện giấu tin vào video bằng các kỹ thuật khác nhau như , **PVD_Edge**, và **PVD_EMD**.  
Dưới đây là các nhiệm vụ chính trong dự án:

---
# **PVD-Edge**
## ✅ Nhiệm vụ 1: Chuyển 1 đoạn tin thành bit

- **File**: `messtobit.py`
- **Cách dùng**:
  ```bash
  nano messtobit.py       # Để xem đoạn code và sửa thông điệp
  python3 messtobit.py    # Để chạy file
  ```

---

## ✅ Nhiệm vụ 2: Giấu đoạn tin “lam nguoi yeu anh nhe” bằng PVD_Edge

- **File**: `PVD_Edge_Embed.py`
- **Cách dùng**:
  ```bash
  python3 PVD_Edge_Embed.py
  ```

---

## ✅ Nhiệm vụ 3: Giải tin được giấu bằng PVD_Edge

- **File**: `PVD_Edge_Ex.py`
- **Cách dùng**:
  ```bash
  python3 PVD_Edge_Ex.py
  ```

---

## ✅ Nhiệm vụ 4: Giấu tin bằng PVD_EMD

- **File**: `PVD_EMD_Embed.py`
- **Cách dùng**:
  ```bash
  nano PVD_EMD_Embed.py       # Sửa nội dung cần giấu
  python3 PVD_EMD_Embed.py    # Chạy file giấu tin
  ```

---

## ✅ Nhiệm vụ 5: Giấu tin bằng PVD

- **File**: `PVD.py`
- **Cách dùng**:
  ```bash
  nano PVD.py           # Sửa nội dung cần giấu
  python3 PVD.py        # Chạy file giấu tin
  ```

---

## ✅ Nhiệm vụ 6: Kiểm tra size của video xuất ra

- **File**: `checksize.py`
- **Cách dùng**:
  ```bash
  nano checksize.py     # Sửa file, thay đổi đường dẫn video nếu cần
  ```

---

## ✅ Nhiệm vụ 7: So sánh 2 file trước và sau khi giấu

- **File**: `compare_stats.py`
- **Cách dùng**:
  ```bash

# PVD-EMD
# Hướng Dẫn Sử Dụng Dự Án Giấu Tin Trong Video

## Giới Thiệu
Dự án này bao gồm các bước liên quan đến việc giấu thông tin vào trong video bằng phương pháp PVD (Pixel Value Differencing). Các nhiệm vụ chủ yếu bao gồm chuyển đổi thông điệp thành dạng bit, giấu thông điệp vào video và kiểm tra kết quả sau khi giấu.

## Các Nhiệm Vụ

### Nhiệm Vụ 1: Chuyển Đoạn Tin Thành Bit
Để chuyển đổi một đoạn tin thành dạng bit, mở file `message_to_bit.py` và chỉnh sửa thông điệp cần giấu.

#### Các bước thực hiện:
1. Mở file để chỉnh sửa thông điệp:
    ```bash
    nano message_to_bit.py
    ```
2. Để chạy chương trình chuyển đổi tin thành bit:
    ```bash
    python3 message_to_bit.py
    ```

### Nhiệm Vụ 2: Giấu Đoạn Tin "lam nguoi yeu anh nhe" Bằng PVD_EMD
Giấu thông điệp vào video bằng phương pháp PVD_emd.

#### Các bước thực hiện:
1. Để chạy chương trình giấu tin:
    ```bash
    python3 PVD_EMD_Embed.py
    ```

### Nhiệm Vụ 3: Giải Tin Được Giấu Bằng PVD_Emd
Giải mã thông tin đã được giấu trong video bằng PVD_emd.

#### Các bước thực hiện:
1. Để chạy chương trình giải mã tin:
    ```bash
    python3 PVD_EMD_extract.py
    ```

### Nhiệm Vụ 4: Giấu Tin Bằng PVD
Giấu thông tin vào video bằng phương pháp PVD.

#### Các bước thực hiện:
1. Mở file để chỉnh sửa thông điệp và video đầu vào:
    ```bash
    nano PVD.py
    ```
2. Để chạy chương trình giấu tin:
    ```bash
    python3 PVD.py
    ```

### Nhiệm Vụ 5: Kiểm Tra Kích Thước Của Video Xuất Ra
Kiểm tra kích thước của video sau khi đã giấu thông tin.

#### Các bước thực hiện:
1. Mở file để thay đổi đường dẫn của video:
    ```bash
    nano checksize.py
    ```
2. Để chạy chương trình kiểm tra kích thước:
    ```bash
    python3 checksize.py
    ```

### Nhiệm Vụ 6: So Sánh Hai File Trước Và Sau Khi Giấu
So sánh hai file video trước và sau khi giấu thông tin.

#### Các bước thực hiện:
1. Mở file để chỉnh sửa đường dẫn:
    ```bash
    nano compare_stats.py
    ```
2. Để chạy chương trình so sánh:
    ```bash
    python3 compare_stats.py
    ```


