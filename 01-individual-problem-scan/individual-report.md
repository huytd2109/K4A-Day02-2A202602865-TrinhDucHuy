# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Trịnh Đức Huy
- Mã học viên: 2A202602865
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm cuối, intern Developer
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
-Nhận task từ mentor/team, đọc requirement, code tính năng mới hoặc sửa bug.
-Debug, test lại chức năng và xử lý các lỗi phát sinh trong quá trình phát triển.
-Tham gia daily/weekly meeting, cập nhật tiến độ và trao đổi blocker với mentor.
-Tìm tài liệu, tra cứu cách sử dụng framework/library/API khi gặp vấn đề kỹ thuật.
-Viết báo cáo tiến độ, cập nhật ticket/document và chuẩn bị nội dung phục vụ báo cáo thực tập.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại / Tốn thời gian | Đọc lại ticket, chat và tài liệu để hiểu requirement | Intern Developer | ~35 phút/task |
| 2 | Lặp lại / AI có thể tốt hơn | Tra cứu lại cú pháp, API hoặc lỗi đã từng gặp | Intern Developer | ~12 lần/tuần, 5-10 phút/lần |
| 3 | Tốn thời gian / AI có thể tốt hơn | Đọc log và thử nhiều hướng để debug bug | Intern Developer | ~40 phút/bug |
| 4 | Lặp lại | Test thủ công lại các luồng sau mỗi lần sửa code | Developer, Tester | ~20-30 phút/lần test |
| 5 | Lặp lại | Viết lại progress từ Git/ticket sang daily hoặc weekly report | Intern Developer, Mentor | ~50 phút/tuần |
| 6 | Pain từ người khác | Requirement trong ticket chưa rõ nên phải hỏi lại mentor | Intern Developer, Mentor | ~4/10 ticket phải hỏi lại |
| 7 | Lặp lại / AI có thể tốt hơn | Copy log, error và code giữa IDE, browser và AI để tìm lỗi | Intern Developer | ~15 lần/tuần |
| 8 | Pain từ người khác | PR bị comment nhiều lỗi nhỏ như naming, format, convention | Developer, Reviewer | ~2 comment nhỏ/PR |
| 9 | Tốn thời gian | Đọc lại code để viết documentation cho feature | Intern Developer, Team | ~25 phút/lần |
| 10 | Pain từ người khác / Tốn thời gian | Mở nhiều nguồn để trả lời trạng thái task khi được hỏi | Intern Developer, Mentor/PM | ~4 lần/tuần, 5-10 phút/lần |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Tôi là Intern Developer trong một công ty làm về lĩnh vực y tế.
Công việc hằng tuần gồm: 
-Nhận task từ mentor/team, đọc requirement, code tính năng mới hoặc sửa bug.
-Debug, test lại chức năng và xử lý các lỗi phát sinh trong quá trình phát triển.
-Tham gia daily/weekly meeting, cập nhật tiến độ và trao đổi blocker với mentor.
-Tìm tài liệu, tra cứu cách sử dụng framework/library/API khi gặp vấn đề kỹ thuật.
-Viết báo cáo tiến độ, cập nhật ticket/document và chuẩn bị nội dung phục vụ báo cáo thực tập.


Tôi đã nghĩ ra các vấn đề sau:
1. Phải đọc nhiều tài liệu, ticket với chat nội bộ đầu tuần
2. Lặp đi lặp lại các cú pháp của code, api và các thư viện
3. Thường xuyên copy code/log giữa AI và IDE.

Hãy gợi ý thêm problem theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác.
Với mỗi gợi ý, ghi actor, workflow sơ bộ và cách đo.
Đừng đưa ý tưởng quá rộng kiểu "xây trợ lý AI toàn năng".
- Ý dùng được:Mất thời gian đọc lại ticket, tài liệu và chat để hiểu requirement trước khi bắt đầu task.
  - Mất thời gian đọc lại ticket, tài liệu và chat để hiểu requirement trước khi bắt đầu task.
  - Mất thời gian đọc log và thử nhiều hướng khác nhau khi debug lỗi.
  - Phải tra cứu lại cú pháp, API hoặc lỗi đã từng gặp trước đó.
  - Phải test thủ công lại nhiều luồng sau mỗi lần sửa code.
  - Phải tổng hợp lại tiến độ từ Git/ticket để viết daily hoặc weekly report.
  - Requirement chưa rõ khiến Developer phải hỏi lại mentor nhiều lần.
  - PR thường bị comment các lỗi nhỏ như naming, format hoặc coding convention.

- Ý bỏ vì không phải pain thật:
  - AI tự động viết toàn bộ code thay Developer → quá rộng, không phải một pain cụ thể.
  - Xây một trợ lý AI quản lý toàn bộ công việc → solution quá lớn, chưa xác định vấn đề thực tế.
  - AI tự quyết định task nào Developer cần làm → không phải vấn đề thường gặp trong workflow.
  - Tự động hóa toàn bộ meeting → chưa có bằng chứng meeting đang gây mất nhiều thời gian.
  - AI tự động viết toàn bộ documentation → documentation chưa phải pain đủ lớn hoặc xảy ra đủ thường xuyên.
**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Đọc ticket, tài liệu và chat để hiểu requirement | Workflow rõ, xảy ra thường xuyên, đo được thời gian/task | Thực tế mất bao lâu và có bao nhiêu task/tuần |
| 2 | Debug bằng cách đọc log và thử nhiều hướng | Pain rõ, tốn nhiều thời gian, AI có thể hỗ trợ tìm nguyên nhân | Thời gian chủ yếu mất ở đọc log, tìm nguyên nhân hay test lại |
| 3 | Tổng hợp Git/ticket để viết báo cáo tiến độ | Workflow đơn giản, lặp lại định kỳ, dễ đo thời gian tiết kiệm | Tần suất và thời gian có đủ lớn để đáng giải quyết hay không |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Đọc ticket, tài liệu và chat để hiểu requirement

```text
Problem 1 câu: Mỗi khi nhận task mới, Intern Developer mất khoảng 30-40 phút đọc ticket, tài liệu và chat nội bộ để hiểu đủ requirement trước khi bắt đầu code.

Actor: Intern Developer 

Thời điểm / bối cảnh: Khi bắt đầu một task hoặc feature mới, đặc biệt khi requirement nằm rải rác ở nhiều nguồn.

Current workflow 3-7 bước:
1. Nhận task từ mentor hoặc ticket. 
2. Đọc mô tả và acceptance criteria trong ticket. 
3. Mở tài liệu liên quan. 
4. Tìm lại các đoạn chat hoặc trao đổi cũ. 
5. Tự tổng hợp requirement và các điểm chưa rõ. 
6. Hỏi lại mentor nếu cần. 
7. Bắt đầu code.


Bottleneck: Bước 3-5 — phải tìm và ghép context từ nhiều nguồn, mất nhiều thời gian và dễ bỏ sót thông tin.

Impact: Khoảng 35 phút/task. Nếu có 4 task/tuần thì mất khoảng 140 phút/tuần chỉ để thu thập và hiểu context.

Success metric: Giảm thời gian hiểu context từ khoảng 35 phút xuống dưới 15 phút/task, không tăng số lần phải hỏi lại mentor hoặc sửa do hiểu sai requirement.

Non-AI alternative: Chuẩn hóa template ticket, checklist requirement và đính kèm đầy đủ link tài liệu liên quan trong ticket.

AI hypothesis: AI tổng hợp ticket, tài liệu và chat liên quan thành một task brief gồm mục tiêu, requirement, acceptance criteria, dependency và các điểm còn chưa rõ. Developer vẫn kiểm tra nguồn trước khi code.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 35 phút 
[1 Đọc ticket: 5'] 
→ [2 Đọc tài liệu: 10'] 
→ [3 Tìm chat cũ: 8'] 
→ [4 Tổng hợp requirement: 7'] <-- bottleneck 
→ [5 Xác nhận điểm chưa rõ: 5']

FUTURE STATE — 14 phút 
[1 Chọn task + nguồn: 2'] 
→ [2 AI tổng hợp context: 1'] 
→ [3 Developer đọc + kiểm tra: 8'] <-- human boundary 
→ [4 Xác nhận điểm chưa rõ: 3']

Fallback: nếu AI thiếu hoặc hiểu sai context thì Developer mở lại nguồn gốc và tự tổng hợp.
```


---

#### Problem Card #2 — Debug bằng cách đọc log và thử nhiều hướng

```text
Problem 1 câu: Khi gặp bug, Intern Developer mất khoảng 40-60 phút đọc log, tìm nguyên nhân và thử nhiều cách sửa trước khi xác định được hướng đúng.

Actor: Intern Developer

Thời điểm / bối cảnh: Khi feature phát sinh lỗi trong quá trình code, test hoặc integration.

Current workflow 3-7 bước:
1. Reproduce bug. 
2. Đọc error message và log. 
3. Xác định khu vực code có khả năng gây lỗi. 
4. Tìm tài liệu, search web hoặc hỏi AI. 
5. Thử một hướng sửa. 
6. Chạy lại và kiểm tra kết quả. 
7. Lặp lại nếu bug chưa được giải quyết.

Bottleneck: Bước 2-5 — xác định nguyên nhân và chọn hướng sửa đúng, thường phải thử nhiều giả thuyết.

Impact: Khoảng 40-60 phút/bug. Nếu gặp 3 bug/tuần thì có thể mất khoảng 120-180 phút/tuần cho quá trình debug.

Success metric: Giảm thời gian trung bình xử lý một bug từ khoảng 45 phút xuống dưới 25 phút và giảm số lần thử sai trước khi tìm được nguyên nhân.

Non-AI alternative: Chuẩn hóa logging, thêm error code, checklist debug và lưu lại knowledge base các lỗi đã gặp.

AI hypothesis: AI đọc error message, log và đoạn code liên quan để gợi ý nguyên nhân có khả năng cao, vị trí cần kiểm tra và các bước debug tiếp theo. Developer quyết định và kiểm chứng trước khi sửa.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 45 phút 
[1 Reproduce bug: 5'] 
→ [2 Đọc log: 8'] 
→ [3 Tìm nguyên nhân: 15'] <-- bottleneck 
→ [4 Search / thử hướng sửa: 10'] 
→ [5 Test lại: 7']

FUTURE STATE — 22 phút 
[1 Reproduce bug: 5'] 
→ [2 Đưa log + context cho AI: 2'] 
→ [3 AI gợi ý nguyên nhân: 1'] 
→ [4 Developer kiểm tra + chọn hướng sửa: 8'] <-- human boundary 
→ [5 Fix + test lại: 6']

Fallback: nếu gợi ý của AI không phù hợp thì Developer quay lại quy trình debug thủ công và kiểm tra từng giả thuyết.
```

---

#### Problem Card #3 — Tổng hợp Git/ticket để viết báo cáo tiến độ

```text
Problem 1 câu: Intern Developer phải định kỳ mở Git, ticket và ghi chú cá nhân để nhớ lại công việc đã làm rồi tổng hợp thành báo cáo tiến độ.

Actor: Intern Developer

Thời điểm / bối cảnh: Cuối ngày, cuối tuần hoặc trước buổi weekly meeting.

Current workflow 3-7 bước:
1. Mở danh sách ticket đã làm. 
2. Kiểm tra commit hoặc pull request trong Git. 
3. Xem lại note hoặc chat để nhớ blocker. 
4. Tổng hợp các việc đã hoàn thành. 
5. Viết progress, blocker và kế hoạch tiếp theo. 
6. Review và chỉnh format. 
7. Gửi cho mentor/team.

Bottleneck: Bước 1-5 — phải thu thập lại thông tin đã tồn tại ở nhiều nguồn rồi viết lại thành báo cáo.

Impact: Khoảng 30-50 phút/tuần cho một báo cáo. Công việc mang tính lặp lại và phần lớn thông tin đã có sẵn trong Git và ticket.

Success metric: Giảm thời gian chuẩn bị báo cáo từ khoảng 40 phút xuống dưới 15 phút mà vẫn đầy đủ progress, blocker và next action.

Non-AI alternative: Dùng template cố định, checklist hoặc cập nhật progress trực tiếp vào ticket trong ngày để giảm việc nhớ lại cuối tuần.

AI hypothesis: AI lấy thông tin từ Git và ticket để tạo draft báo cáo gồm completed tasks, progress, blocker và next action. Developer review, bổ sung context và gửi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 40 phút 
[1 Xem ticket: 8'] 
→ [2 Xem Git/PR: 7'] 
→ [3 Xem note/chat: 5'] 
→ [4 Tổng hợp tiến độ: 10'] <-- bottleneck 
→ [5 Viết + review report: 10']

FUTURE STATE — 13 phút 
[1 Auto-pull Git + ticket: 2'] 
→ [2 AI tổng hợp progress: 1'] 
→ [3 AI draft report: 1'] 
→ [4 Developer review + bổ sung context: 7'] <-- human boundary 
→ [5 Gửi report: 2']

Fallback: nếu AI bỏ sót task hoặc hiểu sai progress thì Developer kiểm tra lại Git/ticket và chỉnh draft thủ công.
```


---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Đọc ticket, tài liệu và chat để hiểu requirement trước khi bắt đầu task.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow khá rõ: nhận task → đọc ticket → tìm tài liệu/chat liên quan → tổng hợp requirement → hỏi lại mentor → bắt đầu code. Có thể đo trực tiếp bằng thời gian/task, số nguồn phải mở và số lần phải hỏi lại mentor. Nếu mỗi task mất khoảng 30-40 phút để gom context và có 3-4 task/tuần thì tổng thời gian mất có thể lên tới 90-160 phút/tuần.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Bottleneck thật sự nằm ở việc tìm thông tin hay ở việc requirement vốn chưa đầy đủ/không rõ?
2. Nếu chỉ chuẩn hóa ticket và đính kèm đầy đủ link tài liệu thì có giải quyết phần lớn pain mà không cần AI không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: 
Số liệu 30-40 phút/task hiện mới là giả định, chưa có dữ liệu bấm giờ thực tế.
Pain có thể đến từ chất lượng requirement kém chứ không hẳn do phải đọc nhiều nguồn.
Nếu workflow đã có ticket template tốt thì AI có thể không tạo thêm nhiều giá trị.
AI tổng hợp sai context có thể làm Developer hiểu sai requirement nhanh hơn thay vì đúng hơn.
- Tôi sửa gì:
Bấm giờ ít nhất 5 task để đo thời gian thực tế ở từng bước: đọc ticket, tìm tài liệu, tìm chat, tổng hợp requirement.
Ghi lại số nguồn phải mở và số lần phải hỏi lại mentor cho mỗi task.
Tách rõ hai pain: "tìm context rải rác" và "requirement chưa rõ", chỉ giữ pain có bằng chứng mạnh hơn.
Giữ human review trong future workflow để Developer kiểm tra lại nguồn trước khi bắt đầu code.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
