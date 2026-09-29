# Lịch sử chuẩn bị công khai

## 2026-09-29

- Kiểm kê các tệp nguồn: hai bản vẽ `.lay6`, một ảnh PNG, một ảnh JPG và một PDF.
- Thay đường dẫn Desktop tuyệt đối nhúng trong hai tệp `.lay6` bằng tên tệp tương đối để không công khai tên tài khoản và đường dẫn máy tính; giữ nguyên kích thước và dữ liệu nhị phân ngoài vùng đường dẫn.
- Thêm README tiếng Việt và tiếng Anh mô tả nội dung, trạng thái chưa kiểm chứng và cách đóng góp.
- Ghi rõ đây là dự án chia sẻ, tác giả không chịu trách nhiệm về hậu quả sử dụng, và các tệp `.lay6` dùng Sprint Layout 6.0.
- Sao chép thêm `Firmware STM32F103C8T6 .bin` và `schh.exe` theo yêu cầu. Không chạy ứng dụng; xác nhận bản sao khớp SHA-256 với tệp nguồn trong Downloads. `schh.exe` không có chữ ký số.
- SHA-256: `Firmware STM32F103C8T6 .bin` `0ce4d8d0e7fe519bcbad5c3d25771b86f1ed301c58bb1d8bdf26260e93c8978e`; `schh.exe` `df44ca80af89a8c07438efc9e386d478692b4f9dbfd110f022f05114e6422c9b`.
- Tạo kho GitHub công khai `https://github.com/mtri-eng/votol-fd-layout`. Lần đẩy đầu bị từ chối vì Git chọn tài khoản `scnks-ship-it`; sau khi xác thực đúng tài khoản `mtri-eng` và gắn danh tính này vào URL kho, toàn bộ dự án đã được đẩy thành công.
- SHA-256 trước chỉnh sửa (các bản vẽ đã lưu ở dạng gốc): `PCB driver U3216.lay6` `dfddb5f49167d72bb4e7857de43e192beecf43d4d79d3a15f51b9f66208e0396`; `pcb fet 30 8pin.lay6` `4c1992a2b2cc356d321f1b8cb29ce0f58197a74b8b4a5ffc0ff0b94dd9355e4a`; `main fet.jpg` `9ae333aba1728112f958697a9d7cb7663159e20c573153aa01d9214d31036cb1`; `pcb driver .png` `02cea3918304295951013b897f519da06f97905d21071d2ed0cf7c330bdef18f`; `CHAN CHUC NANG NEWW.pdf` `a783e75d6a2955f18bdb1ef4f58703f753939f8a9788721cc103daae7c80b85c`.
- SHA-256 sau chỉnh sửa: `PCB driver U3216.lay6` `748b3d95768913eb10c0233f95c6b02bf5fac116ddfac4e6215c3e315ebd3dd2`; `pcb fet 30 8pin.lay6` `13faadc091af48975f151f4840ab248b52e0fc880d944004df9fd7a4fc80c096`.
- Giấy phép chưa được chọn; cần thống nhất trước khi người khác sử dụng hoặc phân phối thiết kế.
