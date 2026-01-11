# Hướng dẫn tạo markdown chuyên nghiệp
## Dùng thẻ <details> để làm "Collapsible Section" (Thu gọn nội dung)
`Ví dụ`
<details>
<summary><b>🔍 Xem hướng dẫn bật Virtualization trong BIOS</b></summary>

1. Khởi động lại máy, nhấn liên tục phím F2 hoặc Del.
2. Tìm mục **Advanced** hoặc **CPU Configuration**.
3. Chỉnh **Intel Virtualization Technology** sang **Enabled**.
4. Nhấn F10 để lưu và thoát.
</details>
👉 ```html
<details>
<summary><b>🔍 Xem hướng dẫn bật Virtualization trong BIOS</b></summary>

1. Khởi động lại máy, nhấn liên tục phím F2 hoặc Del.
2. Tìm mục **Advanced** hoặc **CPU Configuration**.
3. Chỉnh **Intel Virtualization Technology** sang **Enabled**.
4. Nhấn F10 để lưu và thoát.
</details>
```

## Cú pháp để tạo đường link
basic: ```bash [Google](https://www.google.com) ```
Thêm tiêu đề (tooltip khi hover): ```bash [Google](https://www.google.com "Công cụ tìm kiếm") ```
Liên kết tham chiếu (Reference-style links): 
```bash
[Google][google-link]
[google-link]: https://www.google.com "Công cụ tìm kiếm"
```
👉 [Google][google-link]
[google-link]: https://www.google.com "Công cụ tìm kiếm"
Liên kết nội bộ (Anchor link đến heading): ```bash [Đến phần Giới thiệu](#giới-thiệu) ```
👉 [Đến phần Hướng dẫn tạo markdown chuyên nghiệp](#hướng-dẫn-tạo-markdown-chuyên-nghiệp)
Liên kết kèm hình ảnh: ```bash [![Alt text](https://via.placeholder.com/150)](https://example.com) ```
👉 [![Alt text](https://gratisography.com/wp-content/uploads/2024/11/gratisography-augmented-reality-800x525.jpg)](https://gratisography.com/wp-content/uploads/2024/11/gratisography-augmented-reality-800x525.jpg)
Liên kết email: ```bash <mailto:example@gmail.com> ``` 
👉 <mailto:example@gmail.com>

## Tạo Badge "xịn xò" cho Profile (Shields.io)
[Link logo](https://shields.io/ "link dẫn đến trang tạo badge")
Ví dụ: ```bash ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ```
* **Style:** ![Style](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)
* **Color (named):** ![Color (named)](https://img.shields.io/badge/coverage-95%25-orange)
* **Logo:** ![Logo](https://img.shields.io/badge/github-repo-blue?logo=github)

## Checklist tương tác
```bash Cú pháp: - [x] cho mục đã xong và - [ ] cho mục chưa xong. ```
* - [x] 🧩 Bước 1: Kiểm tra máy (Xong)
* - [ ] 📦 Bước 2: Tải Docker Desktop
* - [ ] ⚙️ Bước 3: Cấu hình môi trường

## Kẻ bảng (Table) chuyên nghiệp
**kẻ bảng**
| Feature | Windows | Linux | MacOS |
| :--- | :---: | :---: | :---: |
| Docker Support | ✅ | ✅ | ✅ |
| Performance | Khá | **Tốt nhất** | Tốt |
Cú pháp: ```bash Dấu : giúp căn lề (Trái :---, Phải ---:, Giữa :---:) ```

## Sử dụng "Keyboard Key" HTML Tag
Ví dụ: ```bash Nhấn <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> để mở Command Palette. ```

## Quote "đặc biệt" (Alerts) trên GitHub
> [!NOTE]
> Thông tin quan trọng cần lưu ý ở đây.

> [!TIP]
> Một mẹo nhỏ để làm việc nhanh hơn.

> [!WARNING]
> Cẩn thận! Hành động này có thể gây mất dữ liệu.

## Tạo thanh tiến độ (Progress Bar) bằng HTML
<progress value="75" max="100"></progress> 75%
cú pháp: ```html <progress value="75" max="100"></progress> 75% ```