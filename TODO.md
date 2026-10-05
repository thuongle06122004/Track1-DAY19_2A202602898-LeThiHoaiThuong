# TODO — Day 18: AI Notes (Three prototypes, one next change)

> Trạng thái: Chưa bắt đầu  
> Case kế thừa từ Day 17: **Case B — AI Notes: Personal Learning Notes**  
> Mục tiêu: tạo 3 micro-prototype A/B/C cho cùng một hypothesis problem, test cả ba với 3 tester ngoài nhóm, rồi tổng hợp thành một thay đổi kế tiếp có căn cứ.

## Nguyên tắc bắt buộc

- [ ] Giữ **một** Hypothesis Problem, cùng target user, situation, task, desired outcome và content/data fixture cho A/B/C.
- [ ] Làm 3 **solution mechanisms** khác nhau; không chỉ đổi màu, layout hoặc wording.
- [ ] Mỗi option chỉ gồm 2–3 trạng thái: common context → critical interaction → result/user decision.
- [ ] Mỗi tester tự thao tác cả A/B/C bằng cùng một outcome task; facilitator không giải thích giao diện hoặc dẫn dắt.
- [ ] Ghi hành vi/quote thực tế trước khi diễn giải; không tuyên bố solution đã được validated chỉ từ 3 feedback.
- [ ] Không dùng AI tạo quote, observation hoặc feedback của tester. Khai báo mọi hỗ trợ AI đã dùng.

---

## 0. Chuẩn bị đầu vào và phân công

- [ ] Điền thông tin nhóm: tên nhóm, case, MHV/họ tên của 3 thành viên.
- [ ] Thu thập đủ 3 Practice Notes Day 17 và Solution Parking Lot (tối thiểu 5 hướng).
- [ ] Đặt `notes day 17.md`, 3 Practice Notes và Conversation Guide cạnh nhau để tham chiếu.
- [ ] Thống nhất công cụ prototype (Figma/Framer/HTML-CSS-JS/giấy) và nơi lưu artifact chung.
- [ ] Phân công: mỗi thành viên chịu trách nhiệm chính 1 option, nhưng cả nhóm cùng chốt các quyết định ở chặng 1–3.

## 1. Evidence Snapshot và Hypothesis Problem — 15 phút

### Evidence Day 17 hiện có

- [ ] Xác nhận/cập nhật observation gốc: learner phải tự đọc lại, chọn lọc và tổ chức highlights, questions, notes rời rạc sau lesson.
- [ ] Xác nhận/cập nhật consequence: effort cao khiến learner bỏ qua việc tạo note, mất thời gian tìm lại thông tin hoặc không review.
- [ ] Tách rõ observation/quote thực tế khỏi diễn giải của nhóm.
- [ ] Ghi ít nhất một điều chưa biết (ví dụ: learner có tin/cần AI tự tổng hợp không; dạng control nào đủ để họ lưu note).

### Bản nháp cần nhóm chốt

- [ ] Hoàn thiện Hypothesis Problem theo cấu trúc:  
  **Khi** vừa hoàn thành một lesson có nhiều thông tin quan trọng, **learner** gặp khó khăn trong việc biến highlights, questions và notes rời rạc thành tài liệu có cấu trúc để review, **vì** phải tự đọc lại, chọn lọc và tổ chức thông tin, **dẫn đến** effort cao, mất thời gian hoặc bỏ qua việc tạo/review note.
- [ ] Liệt kê evidence Day 17 hỗ trợ hypothesis này.
- [ ] Liệt kê điều chưa được chứng minh; không coi Practice Notes là validation.
- [ ] Kiểm tra Gate 1: hypothesis có đủ user, situation, job, barrier, consequence và nối với ít nhất 1 observation Day 17.

## 2. Chọn ba Solution Options A/B/C — 20 phút

- [ ] Chốt chung cho A/B/C: target user, situation, task, desired outcome, lesson content và bộ highlights/questions/notes mẫu.
- [ ] Chọn 3 mechanism khác nhau từ Solution Parking Lot; bảo đảm khác nhau ở cách chia việc/quyền quyết định giữa learner và AI.
- [ ] Mô tả cho từng option: mechanism, learner làm gì, AI làm gì, trigger và trade-off chính.
- [ ] Viết distance check: A khác B; B khác C; A khác C — không đề cập màu, layout hay wording.
- [ ] Không cố tình làm một option kém hơn để option khác thắng.
- [ ] Kiểm tra Gate 2: A/B/C giải cùng problem/task nhưng khác mechanism có ý nghĩa.

## 3. Human–AI Design Decision Table — 30 phút

### Hoàn thiện cho từng option A/B/C

- [ ] **Expectation:** trước khi AI hoạt động, learner hiểu AI sẽ làm gì và giới hạn nào.
- [ ] **Role & Agency:** ghi rõ learner làm gì, AI làm gì; quyết định AI Act / Ask / Don't Act và lý do.
- [ ] **Evidence & Uncertainty:** cho biết AI dựa vào highlights/questions/notes nào; biểu hiện khi AI không chắc.
- [ ] **Control & Recovery:** learner có preview, edit, reject, stop, undo hoặc dismiss; có đường quay lại task khi AI sai.
- [ ] Nếu feedback/data có liên quan: ghi dữ liệu nào được dùng, feedback ảnh hưởng phiên hiện tại/lần sau hay không được nhớ, và cách rút quyền.
- [ ] Kiểm tra Gate 3: mọi option đều có agency tương xứng hậu quả khi sai, cùng đường control/recovery rõ ràng.

## 4. Build ba micro-prototype — 80 phút

- [ ] Tạo common context chung: learner vừa hoàn thành lesson và có cùng lesson content, highlights, “chưa hiểu”, questions, personal notes.
- [ ] Chuẩn bị canned AI output/dummy data đủ thật để tester đưa ra quyết định.
- [ ] Dùng chung khoảng 70% context, fixture, components và visual style; chỉ critical interaction khác rõ.
- [ ] Build Option A (người phụ trách: __________).
- [ ] Build Option B (người phụ trách: __________).
- [ ] Build Option C (người phụ trách: __________).
- [ ] Bổ sung evidence/uncertainty cùng control/recovery cho từng option.
- [ ] Thêm annotation ngoài frame, không hiển thị tester: “We expect… / Watch for… / Do not explain…”.
- [ ] Mỗi thành viên thử option do người khác build và ghi lỗi/breakdown.
- [ ] Chuẩn hóa link A/B/C, bảo đảm có reset path về common context.
- [ ] Kiểm tra Gate 4: người không build có thể tự mở, làm cùng task với A/B/C, tự hiểu và quay về context ban đầu.

## 5. Chuẩn bị usability test — 15 phút

- [ ] Viết 1 câu relevant-context question, tối đa 2 phút, không dẫn dắt.
- [ ] Viết cùng một outcome task cho A/B/C (mô tả kết quả cần đạt, không mô tả nút bấm).
- [ ] Chọn tối đa 5 observation focus: first action, hesitation, evidence read/ignored, misunderstanding, help needed, correction/recovery, option chosen/trade-off.
- [ ] Soạn neutral probes: “Bạn đang nghĩ gì?”, “Bạn mong điều gì xảy ra tiếp theo?”, “Bạn vừa dựa vào thông tin nào để quyết định?”.
- [ ] Loại bỏ câu hỏi dẫn dắt như “Bạn có thích không?” hoặc phần giới thiệu pitch giải pháp.
- [ ] Chuẩn bị form Feedback Note cho từng facilitator.

## 6. Test, synthesis và next change

- [ ] Mỗi thành viên facilitate 1 tester ngoài nhóm; mỗi tester trải nghiệm đầy đủ A/B/C.
- [ ] Ghi Feedback Note riêng cho phiên do bản thân facilitate: context, task, hành vi theo từng option, quote chính xác (nếu có), breakdown, lựa chọn/trade-off và diễn giải tách biệt.
- [ ] Không hỗ trợ thao tác, không lấp im lặng, không giải thích icon/chức năng khi test.
- [ ] Thu đủ 3 Feedback Notes của nhóm.
- [ ] Tổng hợp feedback: patterns, differences, observed behaviors và trade-offs của A/B/C.
- [ ] Chốt **một Group Next Change** cụ thể cho vòng lặp kế tiếp, dựa trên evidence.
- [ ] Ghi **Still Unproven**: những điều chưa thể kết luận từ 3 tester.
- [ ] Kiểm tra Gate 5: có 3 feedback notes, pattern/khác biệt, Next Change và Still Unproven; không chỉ đếm số người “thích” option nào.

## 7. Hoàn thiện repository cá nhân trước khi nộp

- [ ] Cập nhật `README.md`: thông tin cá nhân/nhóm/case; Hypothesis Problem; mô tả và link A/B/C; đóng góp cá nhân; prototype feedback; AI Support Log.
- [ ] Tạo `three-option-design-sheet.md` hoặc thêm link board chung: comparison contract + Human–AI Decision Table.
- [ ] Tạo `prototype-link.md`: link mở được của cả A/B/C và hướng dẫn reset/test ngắn gọn.
- [ ] Tạo `prototype-feedback-note.md`: Feedback Note của phiên do chính người nộp facilitate.
- [ ] Tạo `group-feedback-synthesis.md`: 3 feedback notes, patterns/differences, Group Next Change và Still Unproven.
- [ ] Tạo `ai-support-log.md`: AI đã hỗ trợ gì, đầu ra nào sai/hời hợt và bản thân đã sửa gì; không để AI viết thay reflection/đóng góp cá nhân.
- [ ] Kiểm tra các link mở được cho giảng viên/TA.
- [ ] Kiểm tra README phản ánh đúng phần việc cá nhân và tất cả tệp bắt buộc đều tồn tại.

## Checklist cuối cùng

- [ ] A/B/C cùng learner, situation, task, content/data fixture và desired outcome.
- [ ] A/B/C khác nhau rõ ràng về mechanism và phân chia quyền quyết định user–AI.
- [ ] Mỗi option có expectation, agency, evidence/uncertainty và control/recovery.
- [ ] Cả 3 prototype test-ready, không cần facilitator giải thích.
- [ ] Đủ 3 tester ngoài nhóm, mỗi người đã dùng A/B/C.
- [ ] Kết luận chỉ ở mức: đã thử 3 cách giải, quan sát được hành vi gì, và sẽ thay đổi gì tiếp theo.
- [ ] Các artifact/repo được đặt tên và chia sẻ đúng yêu cầu nộp bài.