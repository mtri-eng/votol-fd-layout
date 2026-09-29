# Votol FD – layout mạch và vỏ hộp ND

Đây là dự án chia sẻ bộ bản vẽ cá nhân cho layout mạch Votol và vỏ hộp ND để mọi người tham khảo. Tác giả không còn sử dụng thiết kế này. Toàn bộ tệp được tải xuống miễn phí; ai lựa chọn sử dụng thì tự chịu mọi rủi ro.

## Tệp trong dự án

- `PCB driver U3216.lay6` — bản vẽ PCB driver.
- `pcb fet 30 8pin.lay6` — bản vẽ PCB FET.
- `pcb driver .png` — ảnh xem trước PCB driver.
- `main fet.jpg` — ảnh tham chiếu của bản vẽ PCB FET.
- `CHAN CHUC NANG NEWW.pdf` — tài liệu chức năng đi kèm.
- `Firmware STM32F103C8T6 .bin` — tệp chương trình cho STM32F103C8T6.

Các tệp `.lay6` được tạo bằng **Sprint Layout 6.0**. Dùng Sprint Layout 6.0 để mở và chỉnh sửa; ảnh PNG là ảnh xem trước, không thay thế dữ liệu thiết kế.

## Thông tin linh kiện tham khảo

Theo ghi chú do tác giả cung cấp; chưa được kiểm chứng độc lập:

- IC nguồn 14 V: U3018.
- Cuộn cảm nguồn: 330 µH.
- Vi điều khiển: STM32F103C8T6.
- Thạch anh: 8 MHz.
- IC driver MOSFET: U3216 hoặc IR21867.
- Hai IC op-amp: TP102 hoặc SD06.
- IC bảo vệ quá dòng 5 chân: LMV331.
- Tệp firmware `.bin` dùng với ứng dụng Votol qua cổng nối tiếp ở tốc độ 9600 baud.

## Trạng thái

Đây là dự án chia sẻ chỉ để tham khảo và được cung cấp nguyên trạng. Ai lựa chọn sử dụng thì tự chịu mọi rủi ro. Tác giả không chịu trách nhiệm về bất kỳ thiệt hại, lỗi chế tạo hoặc hậu quả nào phát sinh từ việc sử dụng thiết kế. Thiết kế chưa được xác nhận để chế tạo hoặc vận hành. Người sử dụng tự kiểm tra sơ đồ, kích thước, linh kiện, kết nối, cách điện, tản nhiệt và an toàn trước khi đặt mạch hoặc cấp nguồn.

## Đóng góp

Bạn có thể mở issue hoặc gửi pull request để góp ý và hoàn thiện tài liệu/bản vẽ. Kho này hiện chưa kèm giấy phép sử dụng; việc xem công khai không tự cấp quyền sử dụng, sửa đổi hoặc phân phối. Hãy kiểm tra mục License của GitHub trước khi sử dụng.

---

# Votol FD – PCB and ND enclosure layout

This is a shared project containing personal Votol PCB and ND enclosure layout files for reference. The author no longer uses the design. All files are free to download; anyone choosing to use them assumes all risks.

The `.lay6` files were created with **Sprint Layout 6.0**. Use Sprint Layout 6.0 to open and edit them. The PNG is only a preview. `Firmware STM32F103C8T6 .bin` is the program file for that MCU. This project is shared for reference, as-is, and has not been validated for fabrication or operation. Anyone choosing to use these files assumes all risks. The author accepts no responsibility for loss, manufacturing defects, or other consequences resulting from their use. Review the electrical design, dimensions, components, insulation, thermal behavior, and safety before manufacturing or powering it.

## Reference component notes

As provided by the author; not independently verified:

- 14 V power-supply IC: U3018.
- Power inductor: 330 µH.
- Microcontroller: STM32F103C8T6.
- Crystal: 8 MHz.
- MOSFET driver IC: U3216 or IR21867.
- Two op-amp ICs: TP102 or SD06.
- 5-pin overcurrent-protection IC: LMV331.
- The `.bin` firmware is used with the Votol application over a serial connection at 9600 baud.

The repository currently has no license. Public visibility alone does not grant permission to use, modify, or redistribute these files. Check the repository's License section before using them.
