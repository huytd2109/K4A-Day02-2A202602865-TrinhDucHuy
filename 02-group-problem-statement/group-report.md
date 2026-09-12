# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Đỗ Quốc An | 2A202602892 | facilitator |
| 2   | Trịnh Đức Huy | 2A202602865 | writer |
| 3   | Trịnh Hoàng Tùng | 2A202602937 | workflow | 
| 4   | Nguyễn Hoàng Sơn | 2A202602457 | research |

**Candidate problem nhóm chọn (1 câu): #3 – Các thành viên trong nhóm thường hiểu khác nhau về yêu cầu bài tập, dẫn đến làm sai định dạng hoặc trùng công việc.
**


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Đỗ Quốc An | Sau vài ngày không mở project, học viên phải đọc lại nhiều file và lịch sử commit mới nhớ mình đã làm gì, đang vướng ở đâu | Sinh viên | Thông tin về tiến độ và ngữ cảnh làm việc nằm rải rác trong code, commit và ghi chú; mất thời gian để khôi phục context | Pain khá rõ, xảy ra thường xuyên; có tiềm năng dùng AI để tự động tóm tắt trạng thái project |
| 2 | Đỗ Quốc An | Ảnh chụp màn hình tài liệu, lỗi và hướng dẫn được lưu rời rạc, khiến học viên không tìm lại được đúng ảnh khi cần. | Sinh viên | Ảnh không có cấu trúc, metadata hoặc khả năng tìm kiếm theo nội dung | Hữu ích nhưng phạm vi hơi hẹp; cần kiểm chứng tần suất và thời gian thực sự bị lãng phí |
| 3 | Đỗ Quốc An | Các thành viên trong nhóm thường hiểu khác nhau về yêu cầu bài tập, dẫn đến làm sai định dạng hoặc trùng công việc | Sinh viên | Requirement chưa được chuẩn hóa và chưa có một nguồn thông tin chung để mọi người đối chiếu | Impact cao vì có thể gây rework; phù hợp với bài toán AI hỗ trợ phân tích và chuẩn hóa requirement |
| 4 | Trịnh Hoàng Tùng | Khi debug phải lần theo nhiều lớp từ API → Service → Database → Log để tìm nguyên nhân | Intern | Phải thủ công liên kết thông tin giữa nhiều tầng của hệ thống để xác định nơi phát sinh lỗi | Pain rõ, effort cao; là candidate mạnh vì AI có thể hỗ trợ truy vết và khoanh vùng nguyên nhân |
| 5 | Trịnh Hoàng Tùng | Khi gặp lỗi phải tìm kiếm Google, Stack Overflow, GitHub và documentation ở nhiều nơi | Intern | Kiến thức phân tán trên nhiều nguồn; mất thời gian tìm, đọc và đánh giá giải pháp phù hợp | Rất phổ biến nhưng giải pháp AI hiện có khá nhiều; cần xác định điểm khác biệt hoặc phạm vi cụ thể |
| 6 | Trịnh Hoàng Tùng | Khi nhận task mới phải tìm code tương tự để hiểu cách project đang triển khai chức năng | Intern | Khó xác định nhanh file, module hoặc implementation tương tự trong codebase lớn | Pain thực tế và dễ đo; AI semantic search/code understanding có khả năng tạo impact tốt |
| 7 | Nguyễn Hoàng Sơn | Tổng hợp báo cáo tiến độ hằng tuần | Sinh viên | Phải thu thập thủ công công việc từ nhiều nguồn rồi viết lại thành báo cáo | Workflow rõ, lặp lại thường xuyên và dễ tự động hóa; impact chủ yếu là tiết kiệm thời gian |
| 8 | Nguyễn Hoàng Sơn | Tìm root cause khi debugging | Sinh viên | Có nhiều nguyên nhân tiềm năng; phải đọc code, log và thử nhiều giả thuyết trước khi xác định lỗi | Pain cao và tương đồng với candidate #4, #11; nên gom thành một cluster debugging |
| 9 | Nguyễn Hoàng Sơn | Nghiên cứu công nghệ hoặc giải pháp kỹ thuật | Sinh viên | Phải đọc và tổng hợp nhiều tài liệu để so sánh các phương án trước khi lựa chọn | Hữu ích nhưng khá rộng; cần thu hẹp thành một workflow hoặc quyết định cụ thể để dễ đo impact |
| 10 | Trịnh Đức Huy | Đọc ticket, tài liệu và chat để hiểu requirement | Intern | Requirement bị phân tán giữa nhiều nguồn và có thể chứa thông tin không đồng nhất hoặc thiếu context | Candidate mạnh vì workflow rõ, xảy ra thường xuyên và ảnh hưởng trực tiếp đến việc thực hiện task |
| 11 | Trịnh Đức Huy | Debug bằng cách đọc log và thử nhiều hướng | Intern | Log dài, nhiều tín hiệu nhiễu; phải thử nhiều giả thuyết để tìm đúng nguyên nhân | Pain cao, tốn nhiều thời gian; tiềm năng AI lớn nếu có thể phân tích log và đề xuất root cause |
| 12 | Trịnh Đức Huy | Tổng hợp Git/ticket để viết báo cáo tiến độ | Intern | Phải chuyển đổi thông tin kỹ thuật từ commit và ticket thành nội dung báo cáo dễ hiểu | Workflow lặp lại, dữ liệu đầu vào rõ và dễ đo thời gian tiết kiệm; phù hợp để prototype nhanh |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A – Hiểu requirement & khôi phục context | #1, #3, #10 | Người dùng phải đọc lại nhiều nguồn như ticket, chat, tài liệu, commit hoặc code để hiểu mình cần làm gì và trạng thái hiện tại của công việc | |
| B – Debug & tìm root cause | #4, #8, #11 | Phải đọc log, lần theo nhiều tầng của hệ thống và thử nhiều giả thuyết để xác định nguyên nhân lỗi | |
| C – Tìm kiếm kiến thức & giải pháp kỹ thuật | #2, #5, #6, #9 | Thông tin cần thiết nằm phân tán trong ảnh, codebase, documentation, GitHub, Stack Overflow và các nguồn khác; người dùng mất thời gian tìm và đánh giá thông tin phù hợp | |
| D – Tổng hợp & báo cáo tiến độ | #7, #12 | Phải thu thập dữ liệu từ Git, ticket hoặc lịch sử công việc rồi tổng hợp lại thành báo cáo | |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #3 | Actor cụ thể là sinh viên làm bài tập/project theo nhóm. Workflow từ nhận yêu cầu → mỗi người tự hiểu → chia việc → thực hiện → ghép kết quả khá rõ và nhóm có trải nghiệm trực tiếp. Impact có thể đo qua số lần phải sửa lại, số task bị trùng và thời gian rework. | Cần xác định rõ bottleneck nằm ở bước diễn giải và thống nhất requirement trước khi chia việc, tránh biến bài toán thành vấn đề giao tiếp nhóm quá rộng. Evidence hiện chủ yếu dựa trên trải nghiệm của nhóm, chưa có số liệu thực tế. |
| #4 | Actor rõ là intern/sinh viên lập trình. Pain lớn, workflow tương đối rõ: gặp lỗi → đọc log → lần code → đặt giả thuyết → thử sửa → kiểm tra lại. Có thể đo thời gian debug và số vòng thử trước khi tìm được root cause. | Khó làm prototype đủ tốt trong thời gian lab vì cần codebase, log và lỗi thực tế. Root cause debugging cũng có thể trở nên quá rộng nếu không giới hạn một loại lỗi cụ thể. |
| #7 | Workflow rất rõ và lặp lại: lấy commit/ticket → lọc công việc → nhóm thông tin → viết báo cáo. Dữ liệu đầu vào và đầu ra rõ, dễ xây dựng before/after workflow và đo thời gian tiết kiệm. | Pain không lớn bằng hai candidate còn lại; phần lớn công việc mang tính tổng hợp nên giải pháp AI khá dễ đoán. Khó thể hiện rõ sự khác biệt mạnh giữa Workflow và Agent. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #3 | 5 – actor là sinh viên làm project nhóm, rất cụ thể | 5 – có chuỗi nhận requirement → hiểu → thống nhất → chia việc → làm | 4 – nhóm đã gặp thực tế nhưng chưa có số liệu định lượng | 4 – đo được rework, task trùng, số lần sửa format | 5 – có thể mô phỏng bằng requirement và hội thoại nhóm nhỏ | 5 – Rule, Workflow và Agent cho cách xử lý khác nhau rõ ràng | 5 – nhóm trực tiếp trải nghiệm workflow này | 33/35 |
| #4 | 5 – intern/sinh viên lập trình cụ thể | 4 – workflow rõ nhưng thay đổi tùy loại bug | 5 – pain xảy ra thường xuyên và tốn nhiều thời gian | 5 – đo được thời gian debug, số lần thử và thời gian tìm root cause | 3 – cần codebase/log đủ thực tế, khó kiểm soát trong lab ngắn | 4 – so sánh được nhưng Agent dễ phụ thuộc mạnh vào context/codebase | 5 – nhóm có kinh nghiệm debug thực tế | 31/35 |
| #7  | 5 – actor là sinh viên/intern cần báo cáo tiến độ | 5 – input/output và các bước rất rõ | 3 – có xảy ra nhưng mức pain chưa chắc đủ lớn | 5 – dễ đo thời gian tiết kiệm mỗi tuần | 5 – prototype đơn giản, dữ liệu dễ chuẩn bị | 3 – Rule và Workflow đã có thể xử lý khá tốt, Agent chưa chắc tạo thêm nhiều giá trị | 5 – workflow quen thuộc với cả nhóm | 31/35 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
#3 – Các thành viên trong nhóm thường hiểu khác nhau về yêu cầu bài tập, dẫn đến làm sai định dạng hoặc trùng công việc.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn candidate #3 vì đây là vấn đề mà các thành viên đã trực tiếp gặp khi làm bài tập và project nhóm, nên hiểu workflow đủ sâu để mô tả chính xác. Actor rất cụ thể là sinh viên làm việc theo nhóm và bottleneck có thể thu hẹp vào bước đọc, diễn giải và thống nhất requirement trước khi chia task. Impact có thể đo bằng số task bị trùng, số lần phải sửa lại do hiểu sai yêu cầu và thời gian rework của cả nhóm. Bài toán cũng đủ nhỏ để dựng được before/after workflow ngay trong lab và có thể tạo một scenario đơn giản để kiểm chứng. Đặc biệt, candidate này cho phép so sánh khá rõ ba cách tiếp cận Rule / Workflow / Agent thay vì mặc định rằng cứ dùng AI Agent là tốt nhất.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
ebug và tìm root cause (#4): Đây là candidate có pain và impact rất lớn, nhưng phạm vi dễ trở nên quá rộng vì mỗi bug có codebase, log và nguyên nhân khác nhau. Để thử nghiệm đáng tin cậy trong lab, nhóm sẽ phải chuẩn bị một hệ thống và bộ lỗi đủ thực tế, khiến effort triển khai cao hơn candidate #3. Tổng hợp Git/ticket để viết báo cáo tiến độ (#7): Candidate này có workflow rõ, dễ prototype và dễ đo thời gian tiết kiệm. Tuy nhiên pain chưa mạnh bằng vấn đề hiểu sai requirement, đồng thời Rule hoặc Workflow thông thường đã có thể giải quyết phần lớn bài toán nên giá trị bổ sung của Agent chưa thật sự rõ.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Một số thành viên đánh giá bài toán debugging có impact lớn hơn vì thời gian tìm root cause có thể chiếm nhiều giờ. Tuy nhiên nhóm lo rằng debugging quá phụ thuộc vào codebase và loại lỗi, nên khó tạo một thử nghiệm công bằng trong thời gian lab. Sau khi đối chiếu 7 câu hỏi worksheet, nhóm thống nhất chọn candidate #3 vì actor, bottleneck và workflow đều rõ hơn, nhóm có trải nghiệm trực tiếp, có thể đo impact và đặc biệt dễ xây dựng một so sánh Rule / Workflow / Agent trong cùng một scenario.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 2 | Cả 2 người đều từng gặp việc các thành viên hiểu requirement khác nhau. Người 1: “Có. Trong một bài nhóm gần đây, mình và một bạn hiểu khác nhau về phạm vi của một chức năng nên mỗi người triển khai theo một hướng.” Người 2: “Có, nhóm tôi từng có lúc hiểu khác nhau về một số yêu cầu của bài.” Cả hai đều chỉ phát hiện khá muộn khi ghép/review: “Bọn mình phát hiện khi ghép phần code lại và review…” và “Nhóm phát hiện khi bắt đầu ghép và kiểm tra phần làm của từng thành viên.” Hậu quả gồm làm lệch yêu cầu, làm trùng/bỏ sót và mất khoảng 30–60 phút để trao đổi, sửa lại. | Vấn đề không phải lúc nào cũng gây hậu quả lớn: một người nói “May là không bị làm trùng quá nhiều”, người còn lại cho biết nếu vấn đề nhỏ thì chỉ mất khoảng 30 phút. Ngoài ra, cả hai nhóm hiện đã có biện pháp thủ công như thống nhất phạm vi, đầu vào/đầu ra và xác nhận lại trước khi làm. | Thu hẹp problem từ “thành viên hiểu khác nhau về yêu cầu” thành “sau khi phân công task, nhóm thiếu một bước xác nhận chung về phạm vi, đầu vào/đầu ra và tiêu chí hoàn thành trước khi bắt đầu làm”. Bottleneck chính nằm ở bước alignment/confirmation trước implementation, không chỉ ở việc đề bài khó hiểu. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không nằm chủ yếu ở việc requirement khó hiểu, mà ở việc mỗi thành viên tự diễn giải requirement rồi bắt đầu làm mà chưa có bước xác nhận lại cách hiểu sau khi phân công. Sai lệch thường chỉ được phát hiện khi ghép/review, khiến nhóm phải rework, xử lý phần trùng hoặc bổ sung phần bị bỏ sót, mất khoảng 30–60 phút hoặc hơn tùy mức độ.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-interview-01.png`, `02-group-problem-statement-interview-02.png`, `02-group-problem-statement-interview-03.png`, `02-group-problem-statement-interview-04.png`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| User Story + Acceptance Criteria – Atlassian | https://www.atlassian.com/work-management/project-management/acceptance-criteria/?utm_source=chatgpt.com | Chuẩn hóa requirement trước khi implementation bằng các điều kiện rõ ràng, đo được và kiểm tra được để cả nhóm thống nhất “done” nghĩa là gì. | Đơn giản, không cần AI; giúp giảm ambiguity và tạo chuẩn chung để review kết quả. | Vẫn phụ thuộc vào người viết requirement có đầy đủ hay không. Nếu chỉ viết template nhưng không có bước xác nhận của từng thành viên thì mọi người vẫn có thể hiểu khác nhau. | Solution của nhóm nên bắt buộc tạo ra scope + input/output + acceptance criteria trước khi thành viên bắt đầu task. |
| GitHub Issue Forms / Issue Templates | https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms?utm_source=chatgpt.com | Chuẩn hóa bước tạo/giao task bằng các field cố định; có thể yêu cầu người tạo điền các thông tin cần thiết và đặt validation cho field bắt buộc. | Có cấu trúc rõ, dễ tích hợp vào workflow lập trình và ngăn task quá thiếu thông tin ngay từ đầu. | Template chỉ kiểm tra đã điền thông tin, không kiểm tra được hai thành viên có hiểu giống nhau hay không. Form quá dài cũng tạo thêm overhead. | Không cần build một task manager mới; có thể dùng pattern form/template nhưng bổ sung bước “confirm understanding” sau khi task được giao. |
| Notion AI / Notion Agent | https://www.notion.com/help/guides/notion-ai-for-docs?utm_source=chatgpt.com | AI đọc requirement/tài liệu rồi tóm tắt key points, tổ chức nội dung thành bảng hoặc giúp trả lời câu hỏi dựa trên context của workspace. | Giảm thời gian đọc và biến requirement dài/rời rạc thành nội dung dễ hiểu hơn; phù hợp khi thông tin nằm ở nhiều tài liệu. | AI summary vẫn có thể bỏ sót hoặc diễn giải sai; tài liệu của Notion cũng khuyến nghị kiểm tra lại độ chính xác của output AI. Quan trọng hơn, việc AI tóm tắt requirement chưa đảm bảo các thành viên đã thống nhất cách hiểu. | AI nên đóng vai trò phát hiện ambiguity và tạo câu hỏi xác nhận, không nên tự quyết requirement hoặc tự coi bản tóm tắt là nguồn sự thật cuối cùng. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm không nên build thêm một task manager hay một công cụ chỉ để tóm tắt requirement, vì template, acceptance criteria và các AI workspace hiện có đã làm khá tốt phần đó. Thứ còn thiếu là một “alignment checkpoint” trước khi implementation: hệ thống chuyển requirement thành scope, input/output, acceptance criteria, yêu cầu từng thành viên xác nhận cách hiểu và phát hiện điểm mâu thuẫn hoặc còn mơ hồ. AI nên hỗ trợ đặt câu hỏi và highlight inconsistency, còn quyết định cuối cùng vẫn do nhóm xác nhận.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 Nhận đề bài/requirement: ~5' - cả nhóm]
→ [2 Mỗi thành viên tự đọc và diễn giải yêu cầu: ~5-10' - từng thành viên]
→ [3 Trao đổi và phân công task: ~10' - cả nhóm]
→ [4 Mỗi người triển khai theo cách hiểu của mình: 60-180'+ - từng thành viên]
→ [5 Ghép code/kết quả và review: ~15-30' - cả nhóm]
→ [6 Phát hiện lệch scope, trùng hoặc bỏ sót: ~5-10' - cả nhóm]
→ [7 Thống nhất lại requirement và sửa/rework: ~30-60'+ - thành viên liên quan]

Bottleneck: Bước 2-3 không có checkpoint xác nhận rằng các thành viên đang hiểu cùng một scope,
nên sai lệch thường chỉ được phát hiện muộn ở bước 5-6.
```

| Bước | Actor | Input  | Output | Thời gian / tần suất  | Ghi chú (handoff? bottleneck?) |
| --- | --- | --- | ---| --- | --- |
| 1 | Cả nhóm / trưởng nhóm | Đề bài, tài liệu, yêu cầu giảng viên | Requirement ban đầu  | ~5 phút / đầu mỗi bài hoặc task| Requirement có thể dài hoặc chưa nói rõ scope  |
| 2 | Từng thành viên  | Requirement ban đầu  | Cách hiểu riêng của từng người  | ~5-10 phút/người  | Bắt đầu bottleneck: mỗi người tự diễn giải nhưng chưa đối chiếu với nhau  |
| 3 | Cả nhóm / người phân công | Requirement + cách hiểu cá nhân| Danh sách task và người phụ trách | ~10 phút/lần phân công| Có handoff từ requirement → task nhưng thường thiếu xác nhận scope, input/output, acceptance criteria |
| 4 | Từng thành viên  | Task được giao  | Code/tài liệu/kết quả cá nhân  | 60-180 phút hoặc hơn/task| Thành viên bắt đầu làm dựa trên cách hiểu của mình     |
| 5 | Cả nhóm   | Kết quả của các thành viên | Bản ghép / kết quả review | ~15-30 phút/lần   | Điểm phát hiện lỗi muộn: hai interview đều cho biết vấn đề thường lộ ra khi ghép/review  |
| 6 | Cả nhóm  | Kết quả ghép không khớp  | Danh sách phần sai, trùng hoặc bỏ sót | ~5-10 phút   | Phải truy ngược lại requirement để xác định ai hiểu sai hoặc thiếu phần nào   |
| 7 | Thành viên liên quan | Requirement đã thống nhất lại + phần cần sửa | Kết quả đã chỉnh sửa   | ~30-60 phút hoặc hơn khi xảy ra | Rework trực tiếp; đây là phần pain đã được interview xác nhận     |


**Bottleneck chính (2-3 câu):**

```text
Bottleneck chính nằm giữa bước đọc requirement và bắt đầu implementation: sau khi phân công, nhóm chưa có một checkpoint bắt buộc để xác nhận rằng mọi người hiểu giống nhau về scope, input/output và điều kiện hoàn thành. Vì vậy sai lệch thường không được phát hiện ngay mà chỉ lộ ra khi ghép hoặc review kết quả. Hai interview cho thấy khi điều này xảy ra, nhóm có thể mất thêm khoảng 30-60 phút hoặc hơn để trao đổi và rework.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Người dùng nhập requirement/task: ~2-5' - người]
→ [2 Kiểm tra các field bắt buộc: <1' - Rule/máy]
→ [3 AI chuẩn hóa thành scope + input/output + acceptance criteria: ~1' - AI]
→ [4 AI phát hiện điểm mơ hồ/mâu thuẫn và sinh câu hỏi xác nhận: ~1' - AI]
→ [5 Mỗi thành viên review và confirm cách hiểu: ~3-5' - người, HUMAN BOUNDARY]
→ [6 Chỉ khi đã confirm mới chốt task và bắt đầu implementation: ~1-2' - Rule + người]

Boundary:
AI chỉ đề xuất cách diễn giải, điểm mơ hồ và acceptance criteria.
Requirement cuối cùng chỉ được coi là hợp lệ sau khi người phụ trách và các thành viên xác nhận.

Fallback:
Nếu AI tạo nội dung sai, bỏ sót thông tin, confidence thấp hoặc các thành viên vẫn không đồng ý,
hệ thống đánh dấu "Needs clarification" và quay về trao đổi thủ công với người ra requirement.
Không tự động chốt task hoặc thay đổi requirement khi chưa có human approval.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
| ---| --- | --- | --- |
| Tổng thời gian | Khoảng 45-80 phút/case có lệch requirement| 10-20 phút/case | Ghi timestamp từ lúc đọc/phân công đến khi requirement được thống nhất; cộng thời gian rework |
| Số bước |7 bước | 6 bước | Đếm các bước từ nhận requirement đến bắt đầu implementation / xử lý mismatch                  |
| Số bước thủ công |7/7 bước chủ yếu do người thực hiện | Khoảng 3/6 bước cần người thao tác trực tiếp | Phân loại từng bước thành Machine / AI / Human |
| Bottleneck chính | Sai lệch chỉ được phát hiện khi merge/review | Sai lệch được phát hiện trước implementation | Đo tỷ lệ mismatch được phát hiện trước khi code so với sau khi code |
| Risk mới | Chủ yếu là hiểu sai giữa người với người | AI tóm tắt sai, bỏ sót hoặc tạo acceptance criteria không đúng | Review sample AI output; ghi số lần human phải sửa hoặc reject output AI |


### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Actor chính là sinh viên làm bài tập/project theo nhóm, đặc biệt là nhóm có nhiều thành viên cùng triển khai các phần phụ thuộc nhau. Họ cùng nhận một requirement nhưng mỗi người có thể diễn giải scope và đầu ra theo cách khác nhau.         |
| **Workflow** | Nhóm nhận requirement → từng người tự đọc/diễn giải → phân công task → triển khai → ghép/review kết quả. Hiện tại không có một checkpoint có cấu trúc để mọi người xác nhận lại cách hiểu trước khi bắt đầu làm.                                     |
| **Bottleneck** | Bottleneck nằm ở bước sau khi phân công nhưng trước implementation, khi scope, input/output và acceptance criteria chưa được xác nhận chung. Sai lệch vì thế chỉ được phát hiện muộn khi merge hoặc review.                                      |
| **Impact** | Khi hiểu khác nhau, nhóm có thể làm lệch requirement, làm trùng hoặc bỏ sót một phần công việc. Interview cho thấy một case có thể làm mất thêm khoảng 30-60 phút hoặc hơn để trao đổi và sửa lại.                                               |
| **Success Metric** | Giảm thời gian rework do hiểu sai requirement và tăng tỷ lệ mismatch được phát hiện trước implementation. Pilot hướng tới giảm ít nhất **50% thời gian rework và để phần lớn ambiguity được phát hiện trước khi thành viên bắt đầu code.           |
| **Boundary** | Bài toán chỉ xử lý alignment requirement trước implementation: chuẩn hóa scope, input/output, acceptance criteria và câu hỏi cần xác nhận. Không tự quyết requirement, không tự phân công lại nhân sự và không thay người review/owner của nhóm. |


**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Success Metric vẫn dựa một phần vào mục tiêu kỳ vọng vì mới có 2 interview; chưa có baseline trên nhiều task thực tế. Khái niệm “hiểu giống nhau” cũng cần biến thành thứ đo được thay vì đánh giá cảm tính.
- Tôi sửa gì: Đo bằng các proxy cụ thể: thời gian rework, số mismatch phát hiện sau khi bắt đầu code, số task phải sửa do sai scope, và tỷ lệ AI output được nhóm chấp nhận mà không cần sửa lớn.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao:
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao:

**Bài toán nhóm nằm ở ô nào:**

```text
Độ mơ hồ cao + độ phức tạp tương đối cao.

Tuy nhiên workflow có cấu trúc khá cố định, nên chưa cần một Agent hoàn toàn tự chủ.
```

**Vì sao (2-3 câu):**

```text
Requirement là dữ liệu ngôn ngữ tự nhiên nên Rule thuần túy khó nhận ra các trường hợp “có vẻ đầy đủ nhưng mỗi người có thể hiểu khác nhau”. Tuy vậy, trình tự xử lý của nhóm khá cố định: validate input → AI phân tích → human confirm → mới cho phép bắt đầu task. Vì thế bài toán phù hợp với một AI-assisted Workflow hơn là một Agent tự lập kế hoạch.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|

| **Rule** | Dùng form/template bắt buộc có `scope`, `input`, `output`, `owner`, `acceptance criteria`; không cho chuyển trạng thái sang “Ready” nếu thiếu field | Đủ với task đơn giản, requirement rõ và vấn đề chủ yếu là thiếu thông tin | Field có thể được điền đầy đủ nhưng nội dung vẫn mơ hồ hoặc mâu thuẫn; Rule không hiểu semantics tốt | Có, nhưng chỉ hỗ trợ. Dùng ở bước validate field, status và checkpoint |
| **Workflow** | Chuỗi cố định: Rule kiểm tra input → AI chuẩn hóa requirement → AI highlight ambiguity → người review/confirm → Rule mở khóa task | Phù hợp khi quy trình lặp lại, các bước biết trước nhưng một số bước cần hiểu ngôn ngữ tự nhiên | AI có thể hallucinate hoặc diễn giải sai; workflow cần human boundary rõ | Chọn. Đây là mức chính cho pilot   |
| **Agent** | Agent tự đọc nhiều nguồn, tự quyết định cần hỏi ai, tự tạo/chỉnh task, theo dõi phản hồi và lặp đến khi requirement đủ rõ  | Chỉ đáng dùng khi input phân tán ở nhiều hệ thống và đường xử lý thay đổi mạnh theo từng case | Quá phức tạp cho lab; khó kiểm soát, khó debug, dễ tự thay đổi requirement ngoài ý muốn  | Không chọn hiện tại. Chỉ cân nhắc sau nếu workflow cố định không đủ  |


**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không?
Không. Rule có thể bắt buộc người dùng điền đủ scope, input/output và acceptance criteria, nhưng không biết hai mô tả có mâu thuẫn hay một câu requirement có nhiều cách hiểu hợp lý. Rule phù hợp làm lớp kiểm tra đầu vào, không đủ để giải quyết semantic ambiguity.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?
Phần lớn các bước đi theo một đường cố định. Chỉ cần một nhánh chính: nếu AI hoặc thành viên phát hiện ambiguity thì quay về Needs clarification; nếu mọi người xác nhận thì chuyển sang Ready to implement.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?
Chưa cần. Bài toán hiện tại không yêu cầu AI tự quyết định chiến lược hoặc tự thực hiện chuỗi tool động; nhóm đã biết rõ input, output và checkpoint cần có.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?
Thành viên được giao task hoặc người phụ trách requirement sẽ là người review output trước khi task được mở khóa. Với một alignment card ngắn, kỳ vọng việc kiểm tra và sửa chỉ mất khoảng 3-5 phút, thay vì để lỗi đi tới giai đoạn merge rồi rework 30-60 phút.
5. Có hạ được từ Agent → Workflow → Rule không?
Có thể hạ từ Agent xuống Workflow, và đây là lựa chọn của nhóm. Không nên hạ hoàn toàn xuống Rule vì Rule không xử lý tốt ambiguity và inconsistency trong ngôn ngữ tự nhiên.
**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Nhóm chọn Workflow vì chuỗi xử lý đã biết trước và có thể thiết kế rõ ràng từ input đến human approval. AI chỉ cần thực hiện các bước semantic mà Rule làm kém: chuẩn hóa requirement, phát hiện ambiguity và sinh câu hỏi xác nhận. Rule vẫn được dùng cho validation và trạng thái, còn con người giữ quyền quyết định cuối cùng tại boundary trước implementation. Cách này đủ giải quyết pain chính mà không phải chịu độ phức tạp và rủi ro của một Agent tự chủ.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule-only có thể ép người dùng điền form nhưng không thể đáng tin cậy phát hiện một requirement tuy đủ field nhưng vẫn có nhiều cách diễn giải hoặc mâu thuẫn ngữ nghĩa. Vì pain đã được validation cho thấy nằm ở “mọi người tưởng mình đã hiểu đúng” chứ không chỉ là thiếu field, nhóm cần một lớp AI để đọc và phản biện nội dung trước khi human confirm.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor**  | Sinh viên làm bài tập/project phần mềm theo nhóm, trong đó nhiều thành viên triển khai các task có liên quan hoặc phụ thuộc nhau. Người trực tiếp chịu pain là thành viên nhận task và người phụ trách ghép/review kết quả.   |
| **Workflow**  | Requirement được nhận → nhóm đọc → phân công → từng người triển khai → merge/review. Hiện thiếu một checkpoint có cấu trúc giữa phân công và implementation để xác nhận scope, input/output và acceptance criteria.  |
| **Bottleneck** | Sau khi phân công, từng thành viên có thể tự suy diễn phần chưa rõ nhưng không phát hiện rằng cách hiểu của mình khác người khác. Mismatch thường chỉ lộ ra ở merge/review, tức là sau khi effort implementation đã bỏ ra.    |
| **Impact**    | Hậu quả là code/kết quả lệch yêu cầu, trùng việc hoặc bỏ sót và phải rework. Hai interview đều xác nhận pattern này và ghi nhận khoảng 30-60 phút hoặc hơn để thống nhất và sửa khi vấn đề xảy ra.  |
| **Success Metric**   | Trong pilot, mục tiêu là giảm ít nhất 50% thời gian rework do hiểu sai requirement, giảm số mismatch chỉ được phát hiện sau implementation và tăng tỷ lệ ambiguity được phát hiện trước khi code. Đồng thời đo tỷ lệ alignment card được human chấp nhận và số lần phải sửa AI output. |
| **Boundary** (làm / không làm)    | Làm: chuẩn hóa requirement, trích scope/input/output/acceptance criteria, highlight ambiguity và tạo câu hỏi confirmation. Không làm: tự sửa requirement gốc, tự quyết business requirement, tự assign/reassign người hoặc tự approve task thay con người.   |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào)    | AI can thiệp sau khi requirement/task đã được nhập và phân công sơ bộ, nhưng trước khi implementation bắt đầu. Output AI phải được human review và confirm trước khi task chuyển sang trạng thái `Ready`. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao)   | Workflow — vì chuỗi bước và boundary đã biết trước, chỉ một số bước semantic cần AI; không cần Agent tự lập kế hoạch hoặc tự gọi tool một cách động.   |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI diễn giải sai hoặc thêm acceptance criteria không có trong requirement gốc. Task owner/người ra requirement phải đối chiếu alignment card với nguồn gốc và approve; thành viên nhận task cũng phải confirm trước khi bắt đầu.  |


### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|

| Actor + workflow rõ chưa?    | **Yes**    | Actor đã thu hẹp thành sinh viên làm project nhóm và intervention point được xác định rõ giữa phân công và implementation.        |
| Baseline + metric đo được chưa? | **Not Yet**  | Đã có tín hiệu 30-60 phút rework từ 2 interview và đã xác định metric, nhưng cần pilot trên nhiều task hơn để có baseline đáng tin cậy.                                  |
| Data/input đủ dùng chưa?  | **Yes**    | Pilot chỉ cần một tập requirement/task thực tế của nhóm cùng với cách phân công và output kỳ vọng; không cần dataset lớn để bắt đầu.       |
| AI sai, hậu quả chấp nhận được không? | **Yes**   | AI không được tự approve hoặc thay đổi requirement; mọi output đều có human review trước implementation nên lỗi có thể rollback với chi phí thấp.     |
| Có người review/owner không?   | **Yes**   | Task owner/người nắm requirement review nội dung, còn thành viên nhận task xác nhận rằng cách hiểu phù hợp trước khi bắt đầu.      |
| Có cách non-AI đơn giản hơn không?  | **Yes**  | Checklist/template là baseline bắt buộc phải so sánh. Tuy nhiên nó không xử lý tốt semantic ambiguity, nên pilot cần kiểm tra AI Workflow có tạo thêm giá trị hay không. |


**Decision:**

```text
Go
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Hai interview độc lập đều xác nhận cùng một pattern: thành viên hiểu requirement khác nhau nhưng chỉ phát hiện khi ghép/review, dẫn tới rework khoảng 30-60 phút hoặc hơn. Intervention point đã được thu hẹp rõ vào trước implementation, nên có thể thử nghiệm với rủi ro thấp và human approval đầy đủ. Nhóm cũng có một baseline non-AI rõ ràng là checklist/template để so sánh công bằng. Vì vậy đủ bằng chứng để Go với một pilot nhỏ, nhưng chưa đủ để kết luận hiệu quả trước khi đo trên task thực tế.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Data:
- Chọn 5-10 requirement/task thật hoặc task cũ của nhóm.
- Ưu tiên task từng có điểm mơ hồ về scope, input/output hoặc acceptance criteria.
- Giữ lại requirement gốc để đối chiếu, không chỉnh cho “đẹp” trước khi test.

Chạy tay:
1. Với mỗi task, thử baseline Rule-only: điền checklist scope / input / output / acceptance criteria.
2. Chạy AI Workflow: đưa cùng requirement vào AI để tạo Alignment Card và các câu hỏi ambiguity.
3. Task owner review output AI; thành viên khác đọc và xác nhận cách hiểu.
4. Với một số task mới, dùng alignment card trước khi code rồi theo dõi xem có mismatch/rework hay không.
5. So sánh với workflow cũ và baseline checklist.

Đo 3 số chính:
1. Thời gian alignment + rework cho mỗi task (phút).
2. Số ambiguity/mismatch được phát hiện trước implementation so với sau implementation.
3. Tỷ lệ AI Alignment Card được human chấp nhận mà không cần sửa lớn.

Metric phụ có thể ghi thêm:
- Số task bị trùng/bỏ sót.
- Số acceptance criteria AI tự thêm sai.
- Thời gian human review AI output.
```

**Nếu Not Yet — cần validate gì trước:**

```text
Không áp dụng cho decision hiện tại vì nhóm chọn Go.

Nếu pilot cho tín hiệu yếu, cần mở rộng interview/survey và đo baseline trên ít nhất 5-10 task thực tế để xác định tần suất mismatch, thời gian rework trung vị và xem checklist non-AI có thực sự đã giải quyết phần lớn pain hay chưa.
```

**Nếu No-Go — làm gì thay AI:**

```text
Không áp dụng cho decision hiện tại.

Phương án fallback non-AI là dùng một Definition of Ready/checklist bắt buộc gồm: scope, input, output, acceptance criteria, owner và bước “receiver restates understanding”. Chỉ cho phép task chuyển sang Ready khi người giao và người nhận đều xác nhận.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng hoặc rollback AI nếu sau pilot AI không giảm được thời gian rework so với checklist Rule-only, nếu AI thường xuyên thêm/sửa requirement sai, hoặc thời gian human review AI output lớn hơn lợi ích tiết kiệm được. Một ngưỡng thực dụng là nếu trên 20-30% task, AI tạo lỗi nghiêm trọng cần sửa hoặc không phát hiện được ambiguity quan trọng, nhóm quay về checklist + human confirmation. Vì dữ liệu gốc và quyết định cuối vẫn thuộc về con người, rollback chỉ cần bỏ bước AI và tiếp tục workflow bằng template/checklist hiện có.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
