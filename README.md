# dichvu.asco.vn — Trang dịch vụ ASCO

Kho mã tĩnh cho các trang giới thiệu dịch vụ của **Hãng Kiểm toán và Định giá ASCO**.
Toàn bộ là HTML tĩnh, không cần máy chủ, không cần cơ sở dữ liệu.

## Nội dung

| Đường dẫn | Trang |
|---|---|
| `/` | Trang tổng — ba dịch vụ |
| `/kiem-toan-quyet-toan-nha-o-xa-hoi/` | Kiểm toán quyết toán dự án **Nhà ở xã hội** |
| `/kiem-toan-quyet-toan-du-an-cap-xa/` | Kiểm toán quyết toán dự án **cấp xã, phường** |
| `/kiem-toan-quy-tin-dung-nhan-dan/` | Kiểm toán BCTC **Quỹ tín dụng nhân dân** |

Kèm theo: `robots.txt`, `sitemap.xml`, 4 ảnh chia sẻ mạng xã hội (`og-*.png`).

## Tên miền

`CNAME` đã đặt sẵn **dichvu.asco.vn**. Sau khi bật GitHub Pages, cần trỏ bản ghi DNS
tại nơi quản lý tên miền asco.vn:

```
Loại: CNAME    Tên: dichvu    Giá trị: <tên-tài-khoản-github>.github.io
```

## Cập nhật nội dung

Mỗi trang là **một file HTML duy nhất**, đã nhúng sẵn CSS, JavaScript và logo
(dạng base64) — không phụ thuộc file ngoài. Sửa file rồi commit là xong.

File `.nojekyll` để GitHub Pages phục vụ nguyên trạng, không xử lý qua Jekyll.

## Còn phải làm trước khi chạy quảng cáo

- [ ] Điền mã Formspree vào form liên hệ (hiện chưa nối cổng nhận biểu mẫu)
- [ ] Điền mã đo lường Google Analytics 4
- [ ] Bổ sung họ tên và số chứng chỉ hành nghề của phụ trách Quỹ tín dụng nhân dân
- [ ] Đối chiếu bảng phí Ki/Kt với bản ký Điều 20 Nghị định 193/2026/NĐ-CP
