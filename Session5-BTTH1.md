# [Bài thực hành 1] Lập kế hoạch tài chính cá nhân bằng Chain-of-Thought
## 1.Bảng số liệu( ví dụ tham khảo)
|mục|giá trị|
|---|---|
|thu nhập hàng tháng|20.000.000|
|Thuế/BHXH|1.500.000|
|Chi phí cố định|6.000.000 (nhà, điện nước, internet)|
|Nợ A (thẻ tín dụng)|trả tối thiểu 1.500.000|
|Nợ B (vay bạn)|trả 1.000.000, đúng hạn ngày 25|
|Tiết kiệm|≥ 20% thu nhập, có quỹ dự phòng|

## 2.Promting
```promting
# VAI TRÒ
Bạn là chuyên gia tư vấn tài chính cá nhân, làm việc cẩn thận, luôn kiểm tra lại phép tính.

# DỮ LIỆU ĐẦU VÀO
-Thu nhập tháng: 20.000.000
-Thuế/BHXH: 1.500.000
-Chi phí cố định: 6.000.000 (nhà, điện nước, internet)
-Nợ A (thẻ tín dụng): trả tối thiểu 1.500.000
-Nợ B (vay bạn): trả 1.000.000, đúng hạn ngày 25
-Tiết kiệm: ≥ 20% thu nhập, có quỹ dự phòng
# CHỈ THỊ
Hãy suy nghĩ từng bước một và tính toán chi tiết trước khi đưa ra quyết định.

# QUY TRÌNH SUY LUẬN BẮT BUỘC
Bước 1: Tính thu nhập khả dụng = Thu nhập − Thuế − Chi phí cố định.
Bước 2: Phân bổ khoản trả nợ tối thiểu cho từng khoản, tính tổng và số tiền còn lại.
Bước 3: Trích quỹ tiết kiệm theo tỷ lệ cam kết (≥ 20%), ưu tiên quỹ dự phòng.
Bước 4: Chia phần còn lại cho chi tiêu linh hoạt theo quy tắc 50/30/20 cải tiến
        (Nhu cầu / Mong muốn / Tiết kiệm – trả nợ).

# QUY TẮC KIỂM SOÁT
- Ghi rõ công thức và số liệu trung gian ở mỗi bước.
- Sau mỗi bước, tự kiểm tra lại phép tính trước khi sang bước tiếp.
- Nếu tiền không đủ cho nợ + tiết kiệm tối thiểu, nêu rõ thiếu bao nhiêu và đề xuất cách xử lý, không tự bịa số.
- Tổng các hạng mục cuối phải bằng đúng thu nhập; ghi dòng kiểm tra tổng.

# ĐỊNH DẠNG ĐẦU RA (đúng 2 phần)
## Phần 1: Nhật ký suy luận (Reasoning Steps)
Bước 1 → 4, mỗi bước gồm: công thức, phép tính, kết quả trung gian.
## Phần 2: Bảng phân bổ ngân sách cuối cùng
Markdown Table, cột: | Hạng mục | Số tiền | Tỷ lệ % | Ghi chú |
```