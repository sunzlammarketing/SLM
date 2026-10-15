# Bảng cảnh bản có logo và voice — 50 giây

Voice: file người dùng cung cấp, tăng tốc 1.15× bằng atempo, giữ cao độ. Không cắt hay thêm câu vào giọng đọc. Các mốc nguồn do người dùng nghe và cung cấp theo giây nguyên; không có đồng bộ từng từ bằng ASR. Mốc hình được tính bằng `round(giây_nguồn / 1.15 × 60)`; làm tròn tới khung hình gần nhất. Hình xuất hiện theo từng ý, không phải phụ đề đầy đủ.

| Thời gian video | Mốc voice gốc | Hình ảnh | Lời đọc / ý tương ứng |
|---|---|---|---|
| 00:00–00:05.217 | 0–6 s | Hook, chai mỹ phẩm vector, thẻ xem lại nội dung | Viết content mỹ phẩm… bị từ chối, bài bị gỡ… |
| 00:05.217–00:12.167 | 6–14 s | Rà trước khi đăng; ba thẻ; 3K hiện tại khoảng 9.57 s | Dùng ngay công thức này… Mình gọi nó… |
| 00:12.167–00:21.733 | 14–25 s | Kiểm từ; nhóm từ xuất hiện và được gạch; mỹ phẩm ≠ thuốc | K thứ nhất… trị, chữa… Mỹ phẩm không phải thuốc… |
| 00:21.733–00:32.167 | 25–37 s | Ví dụ trước–sau; cảm nhận thật; ghi chú về căn cứ | K thứ hai… sáng dậy sờ lên má… Khách tin cảm giác… |
| 00:32.167–00:40.000 | 37–46 s | Tài liệu được đánh dấu từng bước; câu nhắc kiểm tra | K thứ ba… Không chắc… |
| 00:40.000–00:44.350 | 46–51 s | Checklist ba K | Viết xong, đọc lại… |
| 00:44.350–00:50.000 | Từ 51 s | Outro theo thông điệp ảnh 2; lưu, tim, follow | Lưu video này… Voice kết thúc khoảng 47.14 s; còn nhạc tới hết. |

## Các mốc chi tiết

| Câu bắt đầu | Nguồn (giây) | Video (giây, trước làm tròn frame) |
|---|---:|---:|
| nhưng bị từ chối | 2 | 1.739 |
| Dùng ngay công thức này | 6 | 5.217 |
| Mình gọi nó | 11 | 9.565 |
| K thứ nhất | 14 | 12.174 |
| trị, chữa | 17 | 14.783 |
| mỹ phẩm không phải thuốc | 21 | 18.261 |
| K thứ hai | 25 | 21.739 |
| Sáng dậy, sờ lên má | 31 | 26.957 |
| Khách tin cảm giác | 33 | 28.696 |
| K thứ ba | 37 | 32.174 |
| Không chắc | 43 | 37.391 |
| Viết xong | 46 | 40.000 |
| Lưu video | 51 | 44.348 |

## Nội dung và nhận diện còn cần lưu ý

- Bản voice vẫn giữ nội dung gốc. Các câu bảo đảm không vi phạm, khái quát về cảm nhận và căn cứ công bố đã được lưu ý trong loi-doc.txt. Chữ trên hình bổ sung “không bảo đảm được duyệt”, “cảm nhận không phải vé miễn trừ”, “tài liệu chứng minh / quy định hiện hành”; chưa sửa giọng đọc các câu này.
- Chưa xác minh pháp lý cho sản phẩm cụ thể; không bổ sung số liệu, trích nghiên cứu hoặc điều luật.
- Đã nhận logo PNG gốc trong ZIP và sử dụng trực tiếp tại đầu các cảnh và outro. Giữ nguyên ảnh, nền, hình dạng, màu và tỷ lệ. Outro thể hiện thông điệp từ ảnh tham khảo bằng chữ chỉnh sửa được. Đã bỏ nhãn chờ logo.
- Nhạc và tín hiệu âm thanh tự tổng hợp bằng scripts/make_audio.py. Mix tự giảm nhạc theo voice bằng sidechain compression trong scripts/mix_audio.py.
