# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trịnh Đức Huy
- Mã học viên: 2A202602865
- Nhóm: B1
- Candidate problem nhóm chọn: #3 – Các thành viên trong nhóm thường hiểu khác nhau về yêu cầu bài tập, dẫn đến làm sai định dạng hoặc trùng công việc.


---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi liệt kê các công việc thường gây tốn thời gian trong quá trình làm việc/intern, sau đó chọn ra 3 vấn đề chính: đọc ticket/tài liệu/chat để hiểu requirement; debug bằng log; tổng hợp Git/ticket để viết báo cáo. | Nhóm có thêm 3 candidate cụ thể để so sánh với các vấn đề của các thành viên khác. |
| Pitch Problem Card | Tôi trình bày candidate của mình theo actor, workflow, bottleneck và impact thay vì chỉ mô tả một khó chịu chung chung. | Giúp nhóm có thêm cơ sở để so sánh các candidate theo cùng một format. |
| Challenge bài của bạn khác | [Tự điền một câu hỏi bạn thực sự đã hỏi. Ví dụ: Tôi hỏi candidate #3 rằng bottleneck thật sự nằm ở đề bài khó hiểu hay ở việc nhóm không xác nhận lại cách hiểu sau khi phân công.] | [Điền kết quả thực tế: câu hỏi đó có giúp nhóm thu hẹp problem hay không.] |
| Gom trùng / cluster | Tôi cùng nhóm nhận ra các bài về debug/root cause có thể gom thành một cluster, còn các bài về requirement/context có thể gom thành một cluster khác. | Giảm số ý rời rạc và giúp nhóm nhìn được pattern chung giữa 12 candidate. |
| Chọn candidate problem | Tôi tham gia so sánh candidate #3 với debugging và báo cáo tiến độ theo actor, workflow, pain, impact, khả năng làm trong lab và khả năng so sánh Rule/Workflow/Agent. | Nhóm thống nhất chọn candidate #3 vì scope rõ và dễ validate trong thời gian lab. |
| Validation / research | [Điền việc bạn thực sự làm: ví dụ đọc kết quả interview, tổng hợp quote, hoặc research Acceptance Criteria / GitHub Issue Forms / Notion AI.] | Validation giúp nhóm sửa cách hiểu từ “đề bài khó hiểu” sang “thiếu bước xác nhận chung trước implementation”. |
| Workflow nhóm | Tôi tham gia bóc workflow hiện tại thành các bước từ nhận requirement → tự diễn giải → phân công → làm → merge/review → rework. | Bottleneck được đặt rõ trước implementation nhưng hậu quả lại chỉ xuất hiện khi merge/review. |
| Problem Statement | Tôi góp phần làm rõ actor, bottleneck, impact, success metric và boundary của bài toán. | Problem Statement không còn quá rộng thành “giao tiếp nhóm kém” mà tập trung vào requirement alignment trước implementation. |
| Rule / Workflow / Agent | Tôi cùng nhóm so sánh Rule-only, AI Workflow và Agent trên cùng một bài toán. | Nhóm chọn Workflow vì cần AI xử lý semantic ambiguity nhưng chưa cần Agent tự lập kế hoạch hay gọi tool động. |
| Decision | Tôi tham gia kiểm tra các điều kiện Go/Not Yet/No-Go và đề xuất pilot nhỏ bằng requirement/task thật. | Nhóm quyết định Go với pilot nhỏ, có human review và baseline checklist để so sánh. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu ấn rõ nhất của tôi là việc thuyết phục nhóm lựa chọn mô hình AI Workflow thay vì Agent, giúp hệ thống tập trung giải quyết độ nhập nhằng ngữ nghĩa của requirement thông qua các bước kiểm soát chặt chẽ mà không làm phức tạp hóa bài toán bằng việc lập kế hoạch hay gọi tool động.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan  | Tôi dùng AI để gợi ý cách nhóm các công việc tốn thời gian theo impact/effort và chuyển chúng thành candidate problem. | AI giúp tôi nhìn các công việc hằng ngày dưới dạng actor – workflow – bottleneck thay vì chỉ là danh sách việc khó chịu. | Một số gợi ý ban đầu khá chung chung và chưa gắn với trải nghiệm intern thực tế của tôi. | Tôi giữ lại các bài thực sự gần với công việc của mình như đọc requirement, debug và viết báo cáo từ Git/ticket. |
| Problem Card  | Tôi dùng AI để kiểm tra xem problem card đã có workflow, metric và impact đủ rõ chưa.  | AI giúp đặt câu hỏi về những phần còn thiếu như tần suất, thời gian mất và cách đo impact.    | AI có xu hướng đưa ra metric giả định khi chưa có evidence.   | Tôi phân biệt rõ đâu là số liệu đã có và đâu chỉ là giả thuyết cần validation.   |
| Workflow    | Tôi dùng AI để gợi ý cách tách current workflow và future workflow thành từng bước.    | AI hữu ích trong việc chỉ ra handoff, bottleneck và human boundary.     | AI ban đầu có thể thêm quá nhiều bước hoặc ước lượng thời gian chưa có bằng chứng.   | Tôi giữ workflow ngắn, bám vào kết quả interview và đánh dấu số kỳ vọng là mục tiêu pilot.    |
| Research  | Tôi dùng AI để tìm các pattern/tool liên quan như Acceptance Criteria, Issue Forms và AI hỗ trợ tài liệu.      | AI giúp tôi so sánh giải pháp hiện có và tìm khoảng trống giữa “đủ thông tin” với “mọi người hiểu giống nhau”.  | AI có thể dễ đi theo hướng solution-first và đề xuất xây một tool lớn.     | Tôi quay lại pain đã validate và chỉ giữ intervention point trước implementation.   |
| Problem Statement | Tôi dùng AI để phản biện các field Actor, Workflow, Bottleneck, Impact, Metric và Boundary.   | AI giúp phát hiện các từ mơ hồ như “hiểu giống nhau” cần chuyển thành metric đo được.  | AI đôi lúc viết scope rộng hơn evidence mà nhóm đang có.    | Tôi thu hẹp thành requirement alignment của nhóm sinh viên trước khi implementation.   |
| Rule / Workflow / Agent | Tôi dùng AI để dựng bảng so sánh ba mức trên cùng một problem.    | AI giúp tách rõ Rule dùng cho validation, AI dùng cho semantic ambiguity và người dùng cho approval.   | AI dễ mặc định Agent là phương án mạnh nhất nếu không ép so sánh với giải pháp đơn giản hơn. | Tôi ưu tiên mức đơn giản nhất đủ dùng và chọn Workflow thay vì Agent.  |
| Decision    | Tôi dùng AI để gợi ý checklist Go/Not Yet/No-Go và cách thiết kế pilot. | AI giúp chuyển quyết định thành tiêu chí đo được thay vì cảm tính.     | Một số success metric ban đầu chưa có baseline thật.     | Tôi giữ quyết định Go cho pilot nhỏ nhưng đánh dấu baseline là `Not Yet` và cần đo thêm trên task thật.    |


> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Trong quá trình thảo luận, nhóm tôi từng có thời điểm rơi vào bẫy solution-first khi một số thành viên hào hứng muốn dựng ngay một Autonomous Agent toàn năng để tự động hóa từ khâu đọc requirement đến sinh task. Tuy nhiên, khi đối chiếu lại với thực tế, tôi nhận ra bài toán cốt lõi không nằm ở việc thiếu công cụ tự động mà là sự lệch pha về ngữ nghĩa giữa các thành viên trước khi bắt tay vào code. Điều khó khăn nhất đối với tôi và nhóm khi chốt Problem Statement không phải là metric mà chính là việc khoanh vùng boundary: phải kiên quyết cắt bỏ mong muốn giải quyết toàn bộ vòng đời dự án để chỉ tập trung vào điểm nghẽn duy nhất là requirement alignment trước implementation. Dấu tay rõ nhất của tôi trong artifact cuối chính là việc kéo nhóm trở lại mặt đất bằng cách phân tích rủi ro hallucination và sự phân mảnh ngữ cảnh của Agent, từ đó thuyết phục mọi người chốt phương án AI Workflow tuyến tính có human-in-the-loop. Quyết định này giúp giải pháp vừa đủ giải quyết tính nhập nhằng của đề bài, vừa giữ được sự minh bạch và kiểm soát chặt chẽ trong phạm vi pilot của lab. Nếu được làm lại từ đầu, tôi sẽ challenge nhóm quyết liệt hơn ngay từ bước scan cá nhân về việc thiết lập baseline metric thực tế, thay vì để đến pha Decision mới nhận ra các chỉ số đo lường hiệu quả phần lớn vẫn đang dựa trên giả định.

```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

