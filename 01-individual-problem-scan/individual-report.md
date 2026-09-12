# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Thái Phúc Tiến
- Mã học viên: 2A202602873
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm cuối 
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): 
    - Học
    - Ăn
    - Ngủ
    - Đi chơi
---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.
<!-- (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) -->
| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Cập nhật lịch học, thi cử lên Google Calendar | Sinh viên | Tốn 20ph/ngày, 140ph/tuần (nhập từ 5 file PDF/thông báo) |
| 2 | Tốn thời gian | Tìm đọc & lọc research paper trong domain đồ án | Sinh viên làm đồ án | Tốn 180ph/tuần (đọc lướt 10-15 paper PDF, note thủ công) |
| 3 | Tốn thời gian | Cập nhật CV và Cover Letter theo từng JD tuyển dụng | Sinh viên năm cuối tìm việc | Mất 45ph/JD, nộp 5 công ty/tuần = 225ph/tuần |
| 4 | AI có thể tốt hơn | Phân tích rubric, đề bài môn học thành checklist | Sinh viên làm bài tập lớn | Mất 40ph đọc file 20 trang, 2 lần/kỳ bị sót tiêu chí chấm điểm |
| 5 | Lặp lại | Ghi chép & phân loại thu chi cá nhân | Sinh viên | Mất 30ph/tuần nhập Excel, 3/4 tháng bị vượt ngân sách |
| 6 | AI có thể tốt hơn | Lên kế hoạch du lịch (lịch trình, chi phí, địa điểm) | Sinh viên / Nhóm bạn | Mất 3-4 tiếng/chuyến đi, so sánh 10-15 bài blog/review |
| 7 | Pain từ người khác | Lên kế hoạch di chuyển (sân bay, vé, thủ tục, thời gian) | Người đi du lịch/công tác | Mất 60ph tra cứu giờ bay, transit, trễ giờ 1 lần/năm |


> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Gợi ý các problem thường gặp của sinh viên năm cuối kèm số đo cụ thể để đưa vào bài toán phân tích AI."
- Ý dùng được: Cách chia lăng kính theo chuẩn metric (thời gian tốn/tuần, số lượng tài liệu/JD).
- Ý bỏ vì không phải pain thật: Bài toán gợi ý đồ ăn trưa (pain không đủ lớn, không có workflow rõ ràng).

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
| 1 | Lên kế hoạch di chuyển (sân bay, vé, thủ tục, thời gian) | Workflow rõ ràng từ tra cứu đến xuất phát. Tần suất gặp không quá cao nhưng pain lớn vì rủi ro trễ giờ/sai thủ tục. | Cách tích hợp dữ liệu thời gian thực (kẹt xe, delay chuyến bay) |
| 2 | Ghi chép & phân loại thu chi cá nhân | Pain lặp lại hằng tuần. Bottleneck ở khâu nhập liệu & phân loại thủ công. Impact giảm 80% thời gian quản lý tài chính. | Khả năng đọc chính xác hóa đơn/ảnh chụp chuyển khoản bị mờ |
| 3 | Cập nhật CV và Cover Letter theo từng JD tuyển dụng | Pain cấp bách của sinh viên năm cuối. Bottleneck rõ ở bước rewrite kinh nghiệm. Impact giảm thời gian chuẩn bị CV từ 45ph xuống 10ph. | Chưa biết AI có bị hallucinate kỹ năng không có thật hay không |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Lên kế hoạch di chuyển (sân bay, vé, thủ tục, thời gian)

```text
Problem 1 câu: Người đi du lịch/công tác mất nhiều thời gian tra cứu giờ giấc, tính toán thời gian xuất phát dự phòng kẹt xe và thủ tục sân bay, dễ dẫn đến trễ chuyến hoặc căng thẳng.

Actor: Người đi du lịch / công tác (Sinh viên di chuyển xa).

Thời điểm / bối cảnh: 1-2 ngày trước khi ra sân bay/bến xe hoặc chuẩn bị chuyến di chuyển phức tạp.

Current workflow 3-7 bước:
1. Tra cứu lại vé, giờ bay và mã đặt chỗ (5 phút)
2. Tra cứu quy định hành lý, giấy tờ thủ tục cần thiết (10 phút)
3. Tìm kiếm phương tiện di chuyển ra sân bay (10 phút)
4. Lên kịch bản tính toán thời gian xuất phát dự phòng kẹt xe/check-in (25 phút)  <-- bottleneck
5. Ghi chú lịch trình di chuyển vào điện thoại (10 phút)

Bottleneck: Bước 4 - Phải tự tính toán thủ công và trừ hao thời gian cho nhiều biến số (kẹt xe, thời gian xếp hàng check-in, soi chiếu an ninh).

Impact: Giảm thời gian lập kế hoạch di chuyển từ 60 phút xuống còn 10 phút, loại bỏ 100% rủi ro trễ giờ.

Success metric: Lịch trình chi tiết được lập < 10 phút, dự báo thời gian chính xác trong khoảng +/- 15 phút.

Non-AI alternative: Tra cứu Google Maps + cài báo thức thủ công trước 3 tiếng.

AI hypothesis: AI nhận thông tin chuyến bay/mã vé, tự động tính toán timeline chi tiết (mốc an toàn, mốc nguy hiểm, quầy làm thủ tục, tips & note) và sync trực tiếp vào Google Calendar kèm thông tin cá nhân cần thiết.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 60 phút

[1. Tra giờ bay: 5'] → [2. Tra thủ tục: 10'] → [3. Tìm phương tiện: 10'] → [4. Tính thời gian dự phòng: 25']  <-- bottleneck → [5. Ghi chú timeline: 10']

FUTURE STATE — 10 phút

[1. Nhập mã vé / giờ bay: 1'] → [2. AI sinh Timeline tối ưu & sync Google Calendar (quầy đến, mốc an toàn/nguy hiểm, tips, note): 2'] → [3. Human review & chốt báo thức: 7']  <-- human boundary

Fallback: Nếu AI tính sai thời gian cao điểm, chuyển sang quy tắc cố định (luôn có mặt tại sân bay trước 2 tiếng đối với nội địa, 3 tiếng đối với quốc tế).
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Ghi chép & phân loại thu chi cá nhân

```text
Problem 1 câu: Sinh viên tốn thời gian nhập liệu và dễ nản lòng khi phân loại thủ công các giao dịch tài chính, dẫn đến bỏ dở việc quản lý ngân sách.

Actor: Sinh viên cá nhân.

Thời điểm / bối cảnh: Cuối tuần hoặc cuối tháng khi muốn tổng kết toàn bộ thu chi.

Current workflow 3-7 bước:
1. Mở ứng dụng ngân hàng / thu thập hóa đơn (5 phút)
2. Mở file Excel hoặc ứng dụng ghi chép thu chi (3 phút)
3. Phân loại thủ công từng giao dịch vào mục (ăn uống, học tập, đi chơi) (15 phút)  <-- bottleneck
4. Tính toán tổng số tiền đã tiêu và so sánh với hạn mức (7 phút)

Bottleneck: Bước 3 - Mất thời gian đọc lại từng dòng giao dịch và phân loại thủ công ở cuối tuần/cuối tháng.

Impact: Giảm thời gian tổng kết thu chi từ 30 phút xuống 5 phút, tự động hóa 90% việc ghi nhận giao dịch.

Success metric: 100% giao dịch được tự động ghi lại và gắn nhãn chính xác, thời gian tổng kết < 5 phút.

Non-AI alternative: Dùng tính năng thống kê sẵn của 1 app ngân hàng duy nhất.

AI hypothesis: AI tự động theo dõi, ghi lại & gắn nhãn (automate tracking & tagging) mọi giao dịch online phát sinh trên điện thoại kèm timeline, hint gợi ý dễ nhớ, hỗ trợ đọc ảnh chụp màn hình/sao kê để trích xuất thu chi chính xác.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 30 phút

[1. Gom hóa đơn/sao kê: 5'] → [2. Mở app/Excel: 3'] → [3. Nhập & phân loại thủ công: 15']  <-- bottleneck → [4. Tính tổng & so sánh: 7']

FUTURE STATE — 5 phút

[1. Giao dịch phát sinh online / Upload sao kê cuối tháng: 1'] → [2. AI tự động ghi nhận, gắn nhãn danh mục kèm timeline & hint gợi ý dễ nhớ: 1'] → [3. Human review báo cáo tổng kết cuối tuần/tháng: 3']  <-- human boundary

Fallback: Nếu AI không nhận diện được danh mục giao dịch, đưa giao dịch đó vào mục "Khác" kèm hint gợi ý để người dùng xác nhận lại thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Cập nhật CV và Cover Letter theo từng JD tuyển dụng

```text
Problem 1 câu: Sinh viên năm cuối tốn quá nhiều thời gian tùy chỉnh CV & Cover Letter thủ công cho từng JD tuyển dụng, dẫn đến giảm số lượng và chất lượng nộp đơn.

Actor: Sinh viên năm cuối đang ứng tuyển việc làm / thực tập.

Thời điểm / bối cảnh: Mùa tuyển dụng, khi thấy JD phù hợp trên LinkedIn/ITViec và cần nộp đơn ngay.

Current workflow 3-7 bước:
1. Tìm & tải JD từ website tuyển dụng (5 phút)
2. Đọc JD & trích xuất thủ công các keyword/yêu cầu chính (10 phút)
3. Mở file CV master và đọc lại kinh nghiệm bản thân (5 phút)
4. Viết lại các bullet point kinh nghiệm & Cover Letter sao cho khớp keyword JD (20 phút)  <-- bottleneck
5. Định dạng lại văn bản & xuất file PDF (5 phút)

Bottleneck: Bước 4 - Mất thời gian suy nghĩ cách diễn đạt lại kinh nghiệm và lựa chọn keyword sao cho vừa đúng thực tế vừa khớp JD.

Impact: Giảm thời gian chuẩn bị 1 hồ sơ từ 45 phút xuống còn 10 phút (tiết kiệm ~75% thời gian), tăng tỉ lệ qua vòng lọc CV.

Success metric: Thời gian hoàn thiện 1 bộ CV + Cover Letter < 10 phút, tỉ lệ match keyword JD > 80%.

Non-AI alternative: Dùng bảng checklist từ vựng ngành + template Canva cố định.

AI hypothesis: AI có thể so sánh JD với CV master, tự động gợi ý cách viết lại bullet points theo công thức XYZ và chèn keyword JD.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 45 phút

[1. Tải JD: 5'] → [2. Trích keyword: 10'] → [3. Mở CV master: 5'] → [4. Rewrite bullet points: 20']  <-- bottleneck → [5. Export PDF: 5']

FUTURE STATE — 10 phút

[1. Tải JD & CV master: 2'] → [2. AI match & draft Bullet Points/Cover Letter: 2'] → [3. Human Review & Sửa đúng thực tế: 5']  <-- human boundary → [4. Export PDF: 1']

Fallback: Nếu AI chèn thông tin sai hoặc quá đà, lấy lại bản CV Master gốc và chỉnh sửa dựa trên danh sách keyword mà AI đã extract.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Lên kế hoạch di chuyển (sân bay, vé, thủ tục, thời gian)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Bài toán có workflow di chuyển rõ ràng với nhiều biến số gây rủi ro cao (kẹt xe, thời gian check-in). Thời gian lập kế hoạch thủ công hiện mất 60 phút nhưng dễ sót chi tiết, trong khi ứng dụng AI giúp chuẩn hóa timeline chỉ trong 10 phút, tự động sync Google Calendar kèm thông tin quầy, mốc an toàn/nguy hiểm và tips. Impact lớn nhất là giảm thiểu áp lực và rủi ro trễ chuyến bay/xe cho người đi xa.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Làm thế nào để AI cập nhật được dữ liệu thời gian thực (như kẹt xe đột xuất hoặc chuyến bay bị delay) để điều chỉnh timeline di chuyển kịp thời?
Nếu người dùng đi du lịch nhóm thì workflow này có hỗ trợ đồng bộ timeline di chuyển cho tất cả thành viên không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Tần suất đi xa của cá nhân không quá liên tục (không phải pain hằng ngày), dẫn đến retention của giải pháp có thể thấp nếu chỉ dành cho cá nhân.
- Tôi sửa gì: Mở rộng bối cảnh sang di chuyển công tác/du lịch nhóm để tăng tần suất sử dụng và tính đồng bộ giữa nhiều người.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge



