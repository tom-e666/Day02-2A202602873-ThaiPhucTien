# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Thái Phúc Tiến
- Mã học viên: 2A202602873
- Nhóm: Nhóm 1 (Lab Day 02)
- Candidate problem nhóm chọn: Lên kế hoạch di chuyển thông minh đa biến số (chuyến bay, giao thông real-time, thủ tục sân bay) bằng AI Agent linh hoạt cho sinh viên và người di chuyển xa không thường xuyên.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Đưa ra 7 bài toán cá nhân, chọn ra Top 3 Problem Cards (Lên kế hoạch di chuyển sân bay, Phân loại thu chi, Cập nhật CV/Cover Letter). | Đóng góp 3 candidate bài toán vào danh sách 18 ý tưởng chung của cả nhóm. |
| Pitch Problem Card | Đóng vai trò Facilitator & Problem Owner, trình bày Problem Card #1 về lập kế hoạch di chuyển đa biến số cho người di chuyển xa. | Thuyết phục nhóm thấy được pain point thực tế và rủi ro lớn khi tự trừ hao thời gian thủ công. |
| Challenge bài của bạn khác | Đặt câu hỏi phản biện bài toán "Tự luyện TOEIC" của Việt và "Thống kê chi tiêu phòng trọ" của Vũ về tính cấp bách và ranh giới với App/Rule đơn thuần. | Giúp nhóm loại bỏ các bài toán thiên về Prompt/OCR đơn giản để tập trung vào môi trường động. |
| Gom trùng / cluster | Nhóm 18 ý tưởng thành 4 cụm (A, B, C, D) và xếp bài toán di chuyển vào Cụm A (Lập kế hoạch di chuyển & Sinh hoạt phòng trọ). | Giúp nhóm dễ phân loại và thu hẹp danh sách xuống 3 bài toán shortlist. |
| Chọn candidate problem | Bảo vệ bài toán di chuyển sân bay qua bảng score (đạt 32/35 điểm), giải trình rõ lý do vì sao bài toán vượt trội so với bài Postman doc và Chi tiêu trọ. | Nhóm đạt 100% đồng thuận chọn bài toán di chuyển sân bay làm Candidate Problem duy nhất. |
| Validation / research | Tiến hành phỏng vấn 3 sinh viên/người di chuyển xa và làm survey 8 mẫu; đồng thời nghiên cứu TripIt, Google Maps, FlightAware. | Thu thập được quote bằng chứng thực tế và phát hiện khoảng trống thị trường (Siloed data) để thiết kế Agent. |
| Workflow nhóm | Vẽ Current Workflow 5 bước thủ công và Future Workflow phân định ranh giới giữa Rule, AI Agent và Human-in-the-loop. | Xác định chính xác Bottleneck nằm ở Bước 3 (trừ hao cảm tính) và thiết lập Fallback an toàn. |
| Problem Statement | Viết và tinh chỉnh 6 field cho Problem Statement v0 và v1, hạ cam kết ảo tưởng xuống metric thực tế (≥ 95% an toàn, sai số ±15'). | Problem Statement của nhóm đạt độ chặt chẽ cao, được giáo viên/PM kiểm chứng khen ngợi. |
| Rule / Workflow / Agent | Phân tích ma trận độ mơ hồ/phức tạp, đưa ra 5 câu hỏi chốt để chọn mức Agent kèm ranh giới kiểm soát Human-in-the-loop. | Định hình rõ kiến trúc hệ thống: Dùng Agent cho việc tổng hợp đa nguồn real-time và Rule cho fallback. |
| Decision | Thiết lập tiêu chí Go kèm điều kiện Pilot nhỏ (20 chuyến bay) và xây dựng cơ chế Rollback ngắt Agent nếu sai số > 25 phút. | Chốt quyết định GO có căn cứ khoa học, đảm bảo tính khả thi và an toàn tuyệt đối cho người dùng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người để lại dấu tay rõ nhất trong việc định hình bài toán "Lên kế hoạch di chuyển sân bay" ngay từ bước Pitch cá nhân, trực tiếp thiết kế ranh giới bán tự động (Human-in-the-loop) để giải quyết lo ngại trễ chuyến của nhóm, và hoàn thiện toàn bộ bảng so sánh Rule/Workflow/Agent kèm cơ chế Fallback an toàn trong báo cáo nhóm.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | | | | |
| Problem Card | | | | |
| Workflow | | | | |
| Research | | | | |
| Problem Statement | | | | |
| Rule / Workflow / Agent | | | | |
| Decision | | | | |

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



```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [ ] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [ ] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

