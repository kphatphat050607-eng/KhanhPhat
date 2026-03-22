# 📚 DSALab — C++ Cấu Trúc Dữ Liệu & Giải Thuật — 15 Tuần

> **Ngôn ngữ:** C++17 | **Đối tượng:** Sinh viên năm 1–2 | **Mục tiêu:** Thực hành qua dự án thực tế

---

## 📋 Lộ Trình 15 Tuần

| Tuần | Chủ đề | Dự án Mini |
|------|--------|------------|
| 1  | [Tổng Quan C++ & Big-O](./Chuong1_TongQuan) | 📊 Big-O Benchmark Tool |
| 2  | [Mảng & Con Trỏ](./exercises/week02) | 🗂️ Student Score Manager |
| 3  | [Tìm Kiếm](./Chuong2_TimKiem_SapXep) | 🔍 Smart Search Engine |
| 4  | [Sắp Xếp Cơ Bản](./Chuong2_TimKiem_SapXep) | 🎬 Sorting Visualizer (Console) |
| 5  | [Sắp Xếp Nâng Cao](./exercises/week05) | ⚡ Sort Race — So Sánh Tốc Độ |
| 6  | [Danh Sách Liên Kết Đơn](./Chuong3_DanhSachLienKet) | 🌐 Lịch Sử Trình Duyệt |
| 7  | [Danh Sách Liên Kết Đôi & Vòng](./exercises/week07) | 🎵 Music Playlist Player |
| 8  | [Stack & Ứng Dụng](./Chuong3_DanhSachLienKet) | 🧮 Máy Tính Biểu Thức (Postfix) |
| 9  | [Queue & Ứng Dụng](./Chuong3_DanhSachLienKet) | 🏥 Hệ Thống Hàng Chờ Bệnh Viện |
| 10 | [Cây Nhị Phân](./Chuong4_CauTrucCay) | 🌳 BST Visualizer (Console) |
| 11 | [Binary Search Tree](./Chuong4_CauTrucCay) | 📖 Từ Điển Anh–Việt BST |
| 12 | [Đệ Quy & Backtracking](./exercises/week12) | ♛ N-Queens Solver |
| 13 | [Graph Cơ Bản](./exercises/week13) | 🗺️ Tìm Đường Ngắn Nhất (BFS) |
| 14 | [Dynamic Programming](./exercises/week14) | 🎒 Bài Toán Cái Túi (Knapsack) |
| 15 | [Dự Án Tổng Kết](./BaiTapUngDung) | 🎭 Theater Management System |

---

## 🚀 Bắt Đầu Nhanh

```bash
git clone https://github.com/CocAgent/DSALab.git
cd DSALab
mkdir -p bin
make        # Biên dịch tất cả
make clean  # Dọn dẹp
```

---

## 📁 Cấu Trúc Dự Án

```
DSALab/
├── include/
│   └── utils.h                      # Hàm tiện ích dùng chung
├── Chuong1_TongQuan/                 # Tuần 1: Big-O, kiểu dữ liệu
├── Chuong2_TimKiem_SapXep/           # Tuần 3–5: Tìm kiếm & Sắp xếp
├── Chuong3_DanhSachLienKet/          # Tuần 6–9: DSLK, Stack, Queue
├── Chuong4_CauTrucCay/               # Tuần 10–11: Binary Tree, BST
├── exercises/week01–15/              # Bài tập từng tuần
├── BaiTapUngDung/                    # 5 Dự án mini tổng hợp
├── BaiTapTongHop/                    # Bài tập tổng hợp lý thuyết
├── Makefile
└── README.md
```

---

## 🎯 5 Dự Án Mini Tổng Hợp (BaiTapUngDung)

| # | Dự án | Cấu trúc sử dụng | Độ khó |
|---|-------|-----------------|--------|
| 1 | 📋 Quản Lý Sinh Viên | Mảng + Sort + Search | ⭐⭐ |
| 2 | 🌐 Lịch Sử Trình Duyệt | Stack (Back/Forward) | ⭐⭐ |
| 3 | 🧮 Máy Tính Biểu Thức | Stack (Postfix Evaluator) | ⭐⭐⭐ |
| 4 | 🏥 Hàng Chờ Bệnh Viện | Queue + Priority Queue | ⭐⭐⭐ |
| 5 | 🎭 Rạp Chiếu Phim | BST + Queue + Stack | ⭐⭐⭐ |

---

## 🌐 Tài Liệu Tham Khảo

| Nguồn | Link |
|-------|------|
| Algorithm Visualizer | [algorithm-visualizer.org](https://algorithm-visualizer.org) |
| Algorithms Repo | [github.com/algorithm-visualizer/algorithms](https://github.com/algorithm-visualizer/algorithms) |
| Projects with C++ | [github.com/DanielSantDev/Projects-with-Cpp](https://github.com/DanielSantDev/Projects-with-Cpp) |
| DSALab (repo gốc) | [github.com/CocAgent/DSALab](https://github.com/CocAgent/DSALab) |

---

## 📌 Hướng Dẫn Fork & Nộp Bài

**Bước 1 — Fork repo:**
Vào [github.com/CocAgent/DSALab](https://github.com/CocAgent/DSALab) → nhấn **Fork**

**Bước 2 — Clone về máy:**
```bash
git clone https://github.com/<tên-của-bạn>/DSALab.git
cd DSALab
```

**Bước 3 — Làm bài, commit, push:**
```bash
git add .
git commit -m "[MSSV] - Ho Ten - Bai tap tuan X"
git push origin main
```

**Bước 4 — Tạo Pull Request** với tiêu đề:
```
[22010456] - Nguyen Van A - Bai tap tuan 1
```

---

> **"Cấu trúc dữ liệu tốt không phải là cấu trúc phức tạp nhất, mà là cấu trúc phù hợp nhất với bài toán."**
