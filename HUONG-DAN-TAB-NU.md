# Hướng dẫn sửa tab "Phương · Nu" (Nupakachi)

Link tab: https://dolinhanh-bridal.github.io/kich-ban-tra/#phuong-nu

## Sửa ở đâu
- Repo GitHub: `dolinhanh-bridal/kich-ban-tra` · file `index.html`
- Kịch bản tab Nu nằm trong mảng **`BAI_NU`** (tìm dòng `const BAI_NU = [`).
- **Chỉ sửa trong `BAI_NU`.** Không đụng `BAI` (tab Trà) và `BAI_EN` (tab Phương · DLA).

## Mỗi bài là 1 dòng như sau
```js
{"id":"nu-01","so":"N01","ten":"Tên bài","mau":"https://link-clip-mau (không bắt buộc)","vay":"Cảnh cần quay, ngăn bằng dấu ·","rows":[["Câu đọc 1",""],["Câu đọc 2",""]]},
```
- `id`: không trùng · `so`: mã hiện trên bảng (N01, N02…) · `ten`: tên bài
- `rows`: mỗi câu Phương đọc là một cặp `["câu", ""]`, câu đầu là câu mở (hook)
- `vay`: cột 2 "cần quay" · `mau`: link clip mẫu, hiện nút "Xem clip mẫu"

## Sau khi sửa
- Kiểm cú pháp: mở trang thấy tab Nu hiện bài là được.
- Commit + push lên nhánh `main` → trang tự cập nhật sau khoảng 1–10 phút.
- Up source: nút trên bảng mở thư mục Drive "SOURCE PHƯƠNG - NUPAKACHI (tiếng Anh)".
