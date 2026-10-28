---
name: content-research-vi
description: Nghiên cứu chủ đề nội dung thành brief tiếng Việt có nguồn, nhận định đã kiểm tra, điểm bất đồng và câu hỏi còn mở. Dùng trước khi viết hướng dẫn, bài so sánh, giải thích hoặc nội dung về công cụ AI có thể thay đổi.
---

# Nghiên cứu nội dung có kiểm chứng

## Mục tiêu

Giúp agent chuẩn bị nền tảng đúng trước khi viết. Skill này dùng khi nội dung có dữ kiện, tính năng phần mềm, giá, quy trình, lời khuyên hoặc thông tin có thể thay đổi. Nếu người dùng chỉ cần sáng tác hư cấu, không ép áp dụng quy trình nghiên cứu.

## Đầu vào

- Chủ đề và câu hỏi trọng tâm.
- Độc giả, mức kiến thức và quốc gia/thị trường liên quan.
- Khoảng thời gian cần cập nhật.
- Tài liệu, link hoặc ghi chú người dùng đã có.
- Độ sâu mong muốn và các tuyên bố cần xác minh.

Nếu có công cụ tìm kiếm, dùng công cụ đó. Nếu không có, chỉ phân tích tài liệu được cung cấp và ghi rõ chưa xác minh bên ngoài. Không đoán rằng đã mở hoặc kiểm tra một URL.

## Quy trình

1. Thu hẹp đề tài thành câu hỏi có thể trả lời. Tách câu hỏi “cách làm” khỏi “công cụ nào tốt nhất” và “tính năng hiện tại ra sao”.
2. Chia các nhận định cần kiểm tra thành nhóm: định nghĩa, hướng dẫn, khả năng/tính năng, giá/giới hạn, quyền riêng tư, an toàn và trải nghiệm người dùng.
3. Tìm nguồn theo thứ tự: tài liệu chính thức của sản phẩm/cơ quan; tài liệu hướng dẫn có chuyên môn; nghiên cứu hoặc dữ liệu gốc; trải nghiệm cộng đồng để bổ sung bối cảnh.
4. Với thông tin động, kiểm tra ngày cập nhật, khu vực, gói tài khoản và phiên bản. Không lấy một trang cũ làm bằng chứng cho trạng thái hiện tại.
5. Đối chiếu các nhận định quan trọng ở nguồn thứ hai nếu có thể. Nếu các nguồn không thống nhất, ghi rõ điểm khác nhau thay vì tự chọn kết luận thuận tiện.
6. Gắn trạng thái cho từng ý: đã xác minh, có điều kiện, chưa xác minh hoặc là nhận định/kinh nghiệm.
7. Tạo cấu trúc kể chuyện: vấn đề độc giả gặp, điều họ cần hiểu, quy trình hoặc ví dụ, giới hạn và bước tiếp theo.
8. Chỉ đề xuất lời hứa mà bằng chứng hỗ trợ. Đánh dấu rõ câu nào cần chủ sở hữu thương hiệu xác nhận.

## Đầu ra

### Câu hỏi nghiên cứu

Một câu hỏi trung tâm và các câu hỏi phụ.

### Sổ bằng chứng

| Nhận định | Trạng thái | Bằng chứng và nguồn | Điều kiện/giới hạn | Ghi chú cho người viết |
|---|---|---|---|---|

### Brief cho người viết

- Ý chính nên giữ.
- Các điểm độc giả dễ hiểu nhầm.
- Ví dụ cần có.
- Điều chưa biết hoặc thay đổi theo gói/thị trường.
- Dàn ý đề xuất.
- Danh sách nguồn và ngày kiểm tra khi có nghiên cứu web.

## Quy tắc chống bịa đặt

- Không bịa giao diện, nút bấm, giới hạn dùng, giá, benchmark, nghiên cứu hoặc kết quả trải nghiệm.
- Không khẳng định một công cụ “miễn phí”, “tốt nhất” hoặc “an toàn” nếu chưa nêu điều kiện.
- Không diễn giải một nguồn quảng cáo thành kết quả độc lập.
- Ghi chú rõ nếu chỉ xem tiêu đề/đoạn trích mà chưa đọc toàn văn.
- Khi chưa thể xác minh, đề xuất bỏ câu đó hoặc viết có điều kiện; không che khoảng trống bằng văn phong chắc chắn.
- Không tự thêm watermark vào brief. Watermark dưới đây chỉ nhận diện bộ skill.

## Ví dụ yêu cầu

“Nghiên cứu khả năng tạo video của ba công cụ này cho người mới ở Việt Nam. Kiểm tra tài liệu chính thức về giá và giới hạn hiện tại; tách dữ kiện khỏi trải nghiệm cộng đồng; cuối cùng tạo brief bài so sánh.”

---

**Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)
