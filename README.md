# Day 18 — AI Notes: Three prototypes, one next change

## 1. Thông tin cá nhân và nhóm

| Mục | Nội dung |
|---|---|
| MHV | 2A202602898 |
| Họ tên | Lê Thị Hoài Thương |
| Tên nhóm | Thương |
| Thành viên 1 / 2 / 3 | Thương|
| Case | Case B — AI Notes: Personal Learning Notes |
| Option chịu trách nhiệm chính | Thương |

## 2. Hypothesis Problem

> Khi vừa hoàn thành một lesson có nhiều highlights, điểm “Chưa hiểu”, câu hỏi và ghi chú rời rạc, learner gặp khó khăn trong việc biến các dấu vết đó thành một bản ghi chú có cấu trúc để xem lại sau vì phải tự đọc lại lesson, chọn lọc và tổ chức thông tin, dẫn đến tốn effort, bỏ qua việc tạo note hoặc không quay lại review.

Hypothesis kế thừa **Pain A** trong `notes day 17.md`. Đây chưa phải validation: việc learner muốn AI viết thay, tin nội dung AI hoặc thực sự review lại note vẫn cần kiểm tra.

## 3. Three Solution Options

| Option | Cơ chế | Prototype |
|---|---|---|
| A — Gom theo dấu vết | AI chỉ nhóm/sắp thứ tự dấu vết; learner tự viết tóm tắt. | [Mở Option A](prototypes/index.html#A) |
| B — AI hỏi, bạn quyết | AI đề xuất từng cụm; learner dùng, sửa hoặc bỏ qua. | [Mở Option B](prototypes/index.html#B) |
| C — Bản nháp hoàn chỉnh | AI soạn bản nháp; learner duyệt, sửa/xóa từng khối trước khi lưu. | [Mở Option C](prototypes/index.html#C) |

Xem comparison contract, decision table và fixture chung tại [three-option-design-sheet.md](three-option-design-sheet.md). Hướng dẫn mở/test/reset ở [prototype-link.md](prototype-link.md).

## 4. Đóng góp của tôi trong nhóm

Thương build phần shared context/content, Human–AI decisions, việc build, facilitation, observation
## 5. Prototype Feedback

- Feedback Note phiên bản thân facilitate: [prototype-feedback-note.md](prototype-feedback-note.md).
- Tổng hợp ba phiên: [group-feedback-synthesis.md](group-feedback-synthesis.md).
- Trạng thái hiện tại: prototype đã sẵn sàng để test; 

## 6. AI Support Log

Xem [ai-support-log.md](ai-support-log.md). Cần rà soát và xác nhận lại nội dung log theo đúng cách sử dụng AI thực tế trước khi nộp.

## Cấu trúc repository

```text
README.md
three-option-design-sheet.md
prototype-link.md
prototype-feedback-note.md
group-feedback-synthesis.md
ai-support-log.md
prototypes/index.html
```