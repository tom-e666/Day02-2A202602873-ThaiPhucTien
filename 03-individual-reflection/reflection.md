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
| Challenge bài của bạn khác | Challenge pitch của bạn long về workflow giải quyết khó khăn trong giao tiếp khi cấp cứu y tế | Thống nhất cùng nhóm loại bỏ các ý tưởng còn thiếu sót và tìm ra ý tưởng phù hợp|
| Gom trùng / cluster | Nhóm 18 ý tưởng thành 4 cụm (A, B, C, D) và xếp bài toán di chuyển vào Cụm A (Lập kế hoạch di chuyển & Sinh hoạt phòng trọ). | Giúp nhóm dễ phân loại và thu hẹp danh sách xuống 3 bài toán shortlist. |
| Chọn candidate problem | Bảo vệ bài toán di chuyển sân bay qua bảng score, đạt 32 điểm | Nhóm đạt đồng thuận chọn bài toán di chuyển sân bay làm Candidate Problem duy nhất. |
| Validation / research |  Đề xuất hướng khảo sát | Kết quả khảo sát và các tính năng liên quan |
| Workflow nhóm | Đề xuất và chỉnh sửa Current Workflow 5 bước thủ công và Future Workflow phân định ranh giới giữa Rule, AI Agent và Human-in-the-loop. | Xác định rõ Bottleneck nằm ở Bước 3 (trừ hao cảm tính) và thiết lập Fallback an toàn. |
| Problem Statement | Đề xuất và chỉnh sửa Problem Statement. | Problem Statement của nhóm đạt độ chặt chẽ cao, vượt qua sự soi xét của các leader|
| Rule / Workflow / Agent | Phân tích ma trận độ mơ hồ/phức tạp, đưa ra 5 câu hỏi chốt để chọn mức Agent kèm ranh giới kiểm soát Human-in-the-loop. | Định hình rõ kiến trúc hệ thống: Dùng Agent cho việc tổng hợp đa nguồn real-time và Rule cho fallback. |
| Decision | Đồng thuận tiêu chí Go kèm điều kiện Pilot nhỏ (20 chuyến bay) và xây dựng cơ chế Rollback ngắt Agent nếu sai số > 25 phút. | Chốt quyết định GO có căn cứ khoa học, đảm bảo tính khả thi và an toàn cho người dùng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người để lại dấu tay trong việc định hình bài toán "Lên kế hoạch di chuyển sân bay" ngay từ bước Pitch cá nhân, thiết kế ranh giới bán tự động (Human-in-the-loop) để giải quyết lo ngại trễ chuyến của nhóm, và hoàn thiện toàn bộ bảng so sánh Rule/Workflow/Agent kèm cơ chế Fallback an toàn trong báo cáo nhóm.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý góc nhìn phát hiện problem cá nhân và brainstorm từ thói quen hàng ngày. | Phân loại nhanh các ý tưởng thành các cụm đề tài rõ ràng. | Đưa ra các bài toán chung chung, thiếu bối cảnh và pain point thực tế. | Tự lọc lấy 7 bài toán bản thân thực sự gặp và chọn ra Top 3 Problem Cards sát thực tế nhất. |
| Problem Card | Hỗ trợ diễn đạt và chuẩn hóa câu chữ cho các mục Actor, Bottleneck, Impact. | Giúp câu từ trong Problem Card chuyên nghiệp, rõ ràng và gãy gọn hơn. | Đưa giải pháp AI vào mọi bài toán một cách gượng ép (solution-first). | Tự định hình lại Bottleneck là do trừ hao thủ công và đưa ra giả thuyết Human-in-the-loop. |
| Workflow | Gợi ý các bước cơ bản trong Current và Future Workflow di chuyển sân bay. | Liệt kê nhanh các điểm mốc chuẩn (check-in, an ninh, di chuyển). | Đánh giá thấp độ phức tạp của khâu làm thủ tục sân bay và dữ liệu giao thông động. | Phân định rõ bước nào dùng Rule, bước nào dùng Agent và thiết lập boundary User review. |
| Research | Tổng hợp thông tin tính năng của TripIt, Google Maps, FlightAware. | Thu thập nhanh điểm mạnh/yếu của các công cụ hiện có trên thị trường. | Không tự phân tích được khoảng trống thị trường (Opportunity Gap) giữa các ứng dụng. | Tự đúc kết 4 khoảng trống lớn (chưa kết nối 3 nguồn data real-time, bỏ qua buffer an ninh sân bay). |
| Problem Statement | Phản biện v0 và gợi ý cách đo lường các metric trong Problem Statement. | Phát hiện ra từ ngữ mơ hồ như "khung giờ vàng", "thiệt hại tài chính". | Đưa ra metric ảo tưởng như "loại bỏ 100% rủi ro trễ chuyến". | Sửa metric thành định lượng cụ thể (≥ 95% đúng khung giờ an toàn, sai số ±15') và chốt boundary. |
| Rule / Workflow / Agent | Gợi ý tiêu chí phân loại bài toán trên ma trận độ phức tạp và độ mơ hồ. | Cung cấp khung lý thuyết so sánh giữa Rule tĩnh, Workflow và Agent. | Coi Agent là "vạn năng", tự động làm hết mọi thứ mà không cần kiểm soát. | Khai phá ranh giới: Dùng Rule cho quy định cố định, Agent cho data động, giữ Human-in-the-loop. |
| Decision | Gợi ý khung đánh giá rủi ro và các điều kiện để đưa ra quyết định Go/No-Go. | Liệt kê các kịch bản rủi ro cần lường trước khi triển khai hệ thống. | Thiếu cơ chế kiểm soát thực tế khi Agent ra quyết định sai hoặc gặp sự cố. | Tự thiết lập điều kiện Pilot nhỏ (20 chuyến bay) và xây dựng Rule Rollback nếu sai số > 25 phút. |

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
Khi nghe các bạn pitch bài toán, tôi nhận ra có nhiều bài toán rất hay và có ý nghĩa, nhưng không phải lúc nào cũng có thể giải quyết một cách thực tế. Trong quá trình thảo luận, nhóm tôi từng có lúc rơi vào bẫy solution-first khi muốn xây dựng một AI Agent hoàn toàn tự động để tự điều chỉnh lịch trình cho người dùng. Tuy nhiên, tôi nhận ra ý tưởng nào cũng có hạn chế nếu tìm hiểu kỹ, và một giải pháp không thể hiệu quả tuyệt đối với tất cả mọi người. Việc nhóm lắng nghe phản biện từ các thành viên khác đã giúp đưa hệ thống về đúng ranh giới Bán tự động (Human-in-the-loop). Điều khó nhất đối với tôi khi hoàn thiện Problem Statement chính là việc định lượng Boundary và Metric. Việc loại bỏ 100% rủi ro trễ giờ là ảo tưởng trong môi trường thực tế, nên mọi người đã chủ động điều chỉnh metric thành tỉ lệ hoàn thiện thủ tục đúng mốc an toàn đạt ≥ 95% với sai số dự báo ±15 phút. Dấu tay rõ nhất của tôi nằm ở việc thiết kế Future Workflow phân định ranh giới giữa Rule tĩnh, Agent động và kiểm duyệt của con người, đồng thời xây dựng cơ chế Rollback an toàn nếu Agent ra quyết định sai. Trải nghiệm này giúp tôi hiểu rõ hơn cách cân bằng giữa bài toán kinh doanh và năng lực công nghệ. Nếu được làm lại, nhóm sẽ challenge mạnh hơn ngay từ khâu validation để thu thập nhiều bằng chứng định lượng từ thực tế hơn.
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

