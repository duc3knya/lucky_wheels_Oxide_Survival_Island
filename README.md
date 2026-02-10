# 🎡 Rust Big Wheel – Visual & Logic Tester

Một vòng quay mô phỏng **Rust Big Wheel** dùng cho:
- Test **thứ tự ô**
- Test **lệch trái / phải trong 1 ô**
- Test **logic kết quả theo tam giác**
- Debug & nghiên cứu plugin / game logic

👉 Hoạt động **100% trên trình duyệt**, không cần server.

---

## ✨ Tính năng chính

- 🎯 Vòng quay **24 ô**, đúng thứ tự quy ước
- 🔺 **Tam giác chúi xuống** – kết quả đọc theo đúng vị trí tam giác
- 🎨 Màu sắc theo quy ước:
  - `1` → Vàng  
  - `3` → Xanh lá  
  - `5` → Xanh nước biển  
  - `10` → Đỏ  
  - `20` → Hồng
- 🔢 Chọn **ô mục tiêu (1–24)**
- ↔️ Điều chỉnh **lệch trái / phải trong phạm vi 1 ô**
- 🌀 Quay có animation + easing
- 📘 Có **hướng dẫn sử dụng** tích hợp trong UI

---

## 🔢 Quy ước thứ tự ô

```
1  : 20
2  : 1
3  : 5
4  : 1
5  : 3
6  : 1
7  : 5
8  : 1
9  : 10
10 : 1
11 : 3
12 : 1
13 : 5
14 : 1
15 : 3
16 : 1
17 : 10
18 : 1
19 : 3
20 : 1
21 : 5
22 : 1
23 : 3
24 : 1
```

- **Ô số 1** là ô mà **tam giác đang chỉ**
- Đếm ô theo **chiều kim đồng hồ**

---

## 🕹️ Cách sử dụng

### 1️⃣ Chạy vòng quay
- Mở file `index.html` bằng trình duyệt
- Bấm **SPIN** để quay
- Kết quả hiển thị:  
  `KẾT QUẢ: Ô X → GIÁ TRỊ`

---

### 2️⃣ Chỉnh ô mục tiêu
- Nhập số **ô mục tiêu (1–24)**
- Bấm **ALIGN**
- Tam giác sẽ chỉ đúng ô đó

---

### 3️⃣ Chỉnh lệch trái / phải
- Dùng thanh **Lệch trái / phải**
- Giá trị:
  - Âm (−) → lệch sang **trái**
  - Dương (+) → lệch sang **phải**
- Dùng để test sát vạch giữa 2 ô

---

### 4️⃣ Hướng dẫn trong app
- Bấm nút **HƯỚNG DẪN** ở góc trên bên phải
- Có giải thích trực quan cho người mới

---

## 🛠️ Kỹ thuật

- HTML5 Canvas
- JavaScript thuần (không thư viện)
- Hệ góc đã **offset về 12 giờ**

---

## 🎯 Mục đích sử dụng

- Test / debug **plugin Rust Big Wheel**
- Nghiên cứu **logic snap – lệch – kết quả**
- Demo / training / kiểm thử

Thanks mấy ní zì đã quan tâm :D
