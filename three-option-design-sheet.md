# Three-option design sheet — AI Notes

## 1. Evidence snapshot

`notes day 17.md` ghi nhận problem/Pain A: sau lesson, learner phải tự đọc lại, chọn lọc và tổ chức highlights, questions, “Chưa hiểu” và ghi chú rời rạc; effort cao có thể khiến họ bỏ qua việc tạo note. 

| Practice Note | Dữ kiện thực tế | Diễn giải |
note nhiều thiếu ngũ cảnh | thi thoảng note | không nhất thiết dùng AI chỉ cần dùng cấu trúc thông tin phù hợp ví dụ bảng biểu

learner có muốn AI tạo note thay vì tự viết; learner có tin/tự kiểm tra nội dung AI; và họ có quay lại review note sau đó hay không.

## 2. Comparison contract

| Thành phần | Quyết định chung |
|---|---|
| Target user | Learner vừa hoàn thành lesson online và đã highlight/ghi chú trong 7 ngày gần đây |
| Situation | Vừa kết thúc lesson, còn nhớ nội dung nhưng chưa có ghi chú tổng hợp |
| Task | Tạo một ghi chú muốn giữ lại để review sau mà không đọc lại cả bài |
| Desired outcome | Lưu được ghi chú đủ tin cậy và dễ review |
| Fixture | Bài 5 — Overfitting và Regularization; 7 dấu vết cố định bên dưới |

### Fixture dùng chung

| # | Loại | Nội dung | Vị trí |
|---|---|---|---|
| 1 | Highlight | “Mô hình học thuộc dữ liệu train thay vì học quy luật chung” | Mục 1, 02:10 |
| 2 | Highlight | “Loss train giảm nhưng loss validation tăng” | Mục 2, 04:12 |
| 3 | Chưa hiểu | “L1 làm nhiều trọng số về đúng 0” | Mục 3, 07:30 |
| 4 | Highlight | “λ quá lớn dẫn đến underfitting” | Mục 4, 10:05 |
| 5 | Chưa hiểu | “Cross-validation để chọn λ” | Mục 4, 10:40 |
| 6 | Câu hỏi | “Khi nào dùng L1, khi nào dùng L2?” | Mục 3 |
| 7 | Ghi chú cá nhân | “Nhớ thử với bài tập tuần sau” | Mục 4 |

## 3. Three meaningful options

| | A — Gom theo dấu vết | B — AI hỏi, bạn quyết | C — Bản nháp hoàn chỉnh |
|---|---|---|---|
| Mechanism | AI nhóm, không viết nội dung mới | AI đề xuất từng cụm và hỏi | AI tạo toàn bộ, learner duyệt theo khối |
| Learner làm | Chọn/loại nhóm, tự tóm tắt | Dùng, sửa, bỏ qua; phân loại điểm chưa hiểu | Chấp nhận, sửa hoặc xóa từng khối |
| AI làm | Nhóm, sắp thứ tự, trỏ về nguồn | Đề xuất và hỏi khi không chắc | Tóm tắt, giải thích có căn cứ, gắn uncertainty |
| Trigger | Learner chủ động bấm tạo | Learner bắt đầu phiên hỏi-đáp | Bản nháp có sẵn khi kết thúc bài |
| Trade-off | Kiểm soát cao, vẫn tốn effort | Cân bằng nhưng nhiều bước | Ít effort nhưng rủi ro tin/duyệt quá nhanh |

**Distance check:** A phân phối việc viết cho learner; B chia quyết định theo từng cụm; C dồn việc tạo cho AI rồi yêu cầu review. Đây là khác biệt về cơ chế và quyền quyết định, không phải khác biệt giao diện.

## 4. Human–AI decision table

| Nguyên tắc | A | B | C |
|---|---|---|---|
| Expectation | AI chỉ sắp xếp dấu vết, không thêm nội dung. | Hiển thị cụm, nguồn và việc AI chỉ đề xuất. | AI tạo nháp, có thể sai/bỏ sót, chưa lưu tự động. |
| Role & agency | Learner viết/chọn/xóa; AI không tự quyết nội dung. | Learner quyết Dùng/Sửa/Bỏ qua từng cụm. | Learner duyệt từng khối và quyết lưu/bỏ. |
| Evidence & uncertainty | Mỗi dấu vết có vị trí bài gốc. | Mỗi đề xuất ghi “Dựa trên” các dấu vết. | Khối có nhãn nguồn; cross-validation có cảnh báo “AI chưa chắc”. |
| Control & recovery | Sửa text, xóa nhóm, quay lại context. | Sửa, bỏ qua, quay lại, dừng và lưu phần đã chọn. | Sửa/xóa khối, tạo lại phần chưa chắc, bỏ nháp và tự viết. |
| AI act / ask / don't act | **Don't act:** không tự viết/tóm tắt. | **Ask:** hỏi cách xử lý điểm chưa hiểu. | **Act then review:** tạo nháp nhưng learner quyết lưu. |

## 5. Test protocol

- **Relevant-context question:** “Gần đây bạn có từng học một bài online rồi ghi chú, highlight hoặc lưu lại gì đó để xem sau không?”
- **Outcome task:** “Bạn vừa học xong bài này. Hãy dùng từng phương án để có một bản ghi chú mà bạn muốn giữ lại để xem sau.”
- **Quan sát:** first action; hesitation; evidence được đọc/bỏ qua; correction/recovery; lựa chọn và trade-off.
- **Neutral probes:** “Bạn đang nghĩ gì?”; “Bạn mong điều gì xảy ra tiếp theo?”; “Bạn vừa dựa vào thông tin nào để quyết định?”
- Không giải thích giao diện, không hỏi “Bạn có thích không?”, không lấp im lặng. Đổi thứ tự A/B/C giữa ba tester.

## 6. Annotation cho facilitator (không đọc cho tester)

| Option | Kỳ vọng quan sát | Không giải thích |
|---|---|---|
| A | Tester tự viết ít nhất một tóm tắt, xóa/giữ một nhóm. | Vì sao AI không viết hộ. |
| B | Tester dùng/sửa/bỏ qua; xử lý câu hỏi “chưa hiểu”. | Ý nghĩa dòng “Dựa trên”. |
| C | Tester duyệt khối và xử lý cảnh báo uncertainty. | Ý nghĩa của cảnh báo “AI chưa chắc”. |