# Prototype links và hướng dẫn test

## Mở prototype

Mở `prototypes/index.html` bằng trình duyệt hiện đại, hoặc dùng các link tương đối sau khi repository được publish:

- [Option A — Gom theo dấu vết](prototypes/index.html#A)
- [Option B — AI hỏi, bạn quyết](prototypes/index.html#B)
- [Option C — Bản nháp hoàn chỉnh](prototypes/index.html#C)

Không dùng API, tài khoản hay dữ liệu người dùng thật. Toàn bộ phản hồi AI là canned output từ fixture trong Design Sheet.

## Luồng chung

1. Mỗi option luôn mở ở common context: lesson đã hoàn thành và 7 dấu vết của learner.
2. Tester tự chọn **Tạo ghi chú cho bài này**, thao tác critical interaction, sau đó xem trước và quyết định lưu/bỏ.
3. Nút **Bắt đầu lại** xóa trạng thái tạm và trở về common context. Nút **Quay lại** phục hồi bước trước trong option.

## Điều kiện test

- Dùng cùng outcome task cho A/B/C; không hướng dẫn nút cần bấm.
- Mỗi tester dùng toàn bộ A/B/C; xoay vòng thứ tự A→B→C, B→C→A, C→A→B.
- Facilitator không diễn giải interface. Nếu được hỏi cách hoạt động, hỏi lại: “Theo bạn, nó nên hoạt động như thế nào?”
- Ghi dữ liệu thật vào `prototype-feedback-note.md`; không tạo quote hay observation bằng AI.