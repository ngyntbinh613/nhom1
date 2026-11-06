# nhom1

# BÀI THỰC HÀNH: QUẢN LÝ MÃ NGUỒN VÀ CỘNG TÁC TRÊN GITHUB
> **Mã học phần:** MD07 - Lập trình mã nguồn mở  
> **Nhóm thực hiện:** Nhóm 01  

---

## 1. Giới thiệu dự án
Dự án được tạo nhằm thực hành quy trình làm việc nhóm chuyên nghiệp với Git/GitHub theo mô hình **Git Feature Branch Workflow**.
- Quản lý phiên bản mã nguồn phân tán.
- Phân nhánh tính năng (`feature/info-*`), mở Pull Request và Review mã nguồn.
- Mô phỏng và giải quyết xung đột mã nguồn (**Merge Conflict**).

---

## 2. Danh sách thành viên & Phân công nhiệm vụ

| STT | MSSV | Họ và tên | Vai trò | Trách nhiệm chính |
| :---: | :---: | :--- | :---: | :--- |
| 1 | 24010001 | Duy Anh | **Leader** / Maintainer | Khởi tạo repo, quản lý nhánh `main`, duyệt & merge PR |
| 2 | 24012345 | Nguyễn Thanh Bình | **Developer** | Tạo nhánh cá nhân, đẩy thông tin thành viên, mô phỏng conflict |


---

## 3. Cấu trúc thư mục dự án

```text
nhom1/
├── README.md               # Tài liệu tổng quan dự án
├── .gitignore              # Cấu hình bỏ qua các tệp không cần thiết
└── members/                # Thư mục chứa thông tin từng cá nhân
    ├── 24010001-duy-anh.md
    ├── 24012345-nguyen-thanh-binh.md
    └── ...
