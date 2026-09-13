# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: [Điền tên thật]
- Mã học viên: [Điền mã học viên]
- Nhóm: [Điền tên nhóm]
- Candidate problem nhóm chọn: Tổng hợp bài tập nhóm — merge phần từ nhiều thành viên thành 1 bài nộp đồng nhất

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 problems từ trải nghiệm thật, phân theo 4 lăng kính; bỏ 2 ý AI gợi ý vì không có workflow thật | Nhóm có nhiều candidate phong phú về cluster Tổng hợp và Báo cáo định kỳ |
| Pitch Problem Card | Pitch Card #1 (Tổng hợp bài nhóm) — trình bày workflow 7 bước, bottleneck ở bước merge + đoạn nối, metric 60-90 phút | Card vào shortlist và được nhóm chọn làm candidate chính |
| Challenge bài của bạn khác | Hỏi Lê Minh Cường về bài "Đọc spec kỹ thuật": "Spec là tài liệu nội bộ — nhóm có tính đến vấn đề data boundary không?" | Nhóm nhận ra rủi ro quan trọng, loại bài này khỏi shortlist vì không đủ thời gian giải quyết trong lab |
| Gom trùng / cluster | Đề xuất cụm A (Tổng hợp/merge) và cụm C (Báo cáo định kỳ) — giải thích pattern chung | Nhóm thống nhất 4 cluster nhanh hơn, tránh vote lộn xộn |
| Chọn candidate problem | Lập luận chọn #1 thay vì #3 dựa trên tiêu chí "nhóm hiểu domain" và "không có rủi ro data boundary trong lab" | Nhóm đồng thuận nhanh sau khi so sánh rõ hai phương án |
| Validation / research | Tổng hợp kết quả 3 interview + 8 poll Discord; phát hiện insight "pain thật nằm ở đoạn nối, không chỉ format" | Nhóm sửa lại Problem Statement v0 để tập trung vào bước ngôn ngữ, không phải bước format |
| Workflow nhóm | Vẽ current state 7 bước và future state 4 bước, gắn thời gian cho từng bước | Nhóm dùng làm nền tảng cho PS v0 và bảng before/after impact |
| Problem Statement | Draft PS v0; sửa v1 sau khi AI phản biện chỉ ra metric "chất lượng bài không giảm" còn mơ hồ | PS v1 có metric cụ thể hơn (số comment giảng viên + thời gian bấm giờ) và baseline được ghi rõ là ước lượng |
| Rule / Workflow / Agent | Lập luận chọn Workflow (không phải Agent) dựa trên phân tích "workflow tuyến tính, AI chỉ cần 1 bước ngôn ngữ" | Nhóm thống nhất chọn Workflow và xác định rõ intervention point |
| Decision | Đề xuất Go với pilot nhỏ (3 lần nộp bài), thiết kế 3 số đo cho pilot | Nhóm chấp nhận — quyết định có exit condition rõ ràng |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi đã phát hiện và đặt câu hỏi về rủi ro data boundary của spec kỹ thuật nội bộ —
điều này giúp nhóm loại một candidate có vẻ hấp dẫn ra khỏi shortlist và chọn được
bài toán có thể thực sự làm đến quyết định cuối trong thời gian lab.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi thêm gợi ý problem sau khi tự scan 7 bài | Gợi ý thêm 2 bài hữu ích (onboarding intern, bài đọc trước lớp) | Gợi ý 2 bài không có workflow thật ("quản lý ăn uống", "tìm nhà trọ") | Bỏ 2 bài AI gợi ý — giữ lại 10 bài có actor và dấu hiệu thật |
| Problem Card | Nhờ AI phản biện Card #1 theo vai skeptical PM | Chỉ ra metric "chất lượng bài không giảm" còn mơ hồ và vấn đề data privacy khi paste bài vào AI tool | AI đề xuất dùng Agent ngay — skip hoàn toàn bước Workflow | Giữ Workflow, bổ sung metric phụ (số comment giảng viên) và ghi rõ boundary data |
| Workflow | Nhờ AI chuyển mô tả workflow sang format ASCII có time stamp | Nhanh hơn khi format bảng và gắn thời gian từng bước | AI gộp bước 4-5-6 thành "chỉnh và đọc lại" — che khuất 3 bottleneck khác nhau | Tách lại 3 bước vì bottleneck nằm ở từng bước riêng biệt, cần rõ khi vẽ future state |
| Research | Dùng AI tìm tool đã có giải bài tổng hợp văn bản | Gợi ý Notion AI, Gemini in Drive, Overleaf workflow — có link để verify | AI đưa ra con số "tiết kiệm 70% thời gian" cho Notion AI không có nguồn rõ | Không dùng con số không verify — chỉ giữ link tool chính thức và nhận xét định tính |
| Problem Statement | Nhờ AI phản biện PS v0 | Chỉ ra baseline metric chưa có data thật; boundary chưa nói rõ "không thay đổi ý nghĩa nội dung" | AI đề xuất thêm nhiều field phức tạp không cần thiết cho scope lab | Giữ đúng 6 field của PS v0 và 9 field của PS v1 theo template worksheet |
| Rule / Workflow / Agent | Không dùng AI — nhóm tự thảo luận | — | — | Nhóm tự quyết định sau khi trả lời 5 câu hỏi chốt trong worksheet. AI không được phép quyết định thay. |
| Decision | Không dùng AI — nhóm tự chốt | — | — | Quyết định Go dựa trên validation thật và phân tích rủi ro của nhóm, không phải vì AI nói Go. |

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
Điều tôi học được nhiều nhất trong lab hôm nay không phải từ bài mình pitch, mà là từ lúc nghe
Lê Minh Cường pitch bài "Đọc spec kỹ thuật". Nghe xong tôi cảm thấy rõ ràng pain là thật và
tần suất cao — nhưng khi hỏi về data boundary, Cường không có câu trả lời ngay. Đó là lúc tôi
nhận ra "pain thật" chưa đủ để chọn candidate problem, mà phải hỏi thêm "nhóm có thể làm đến
quyết định cuối trong phạm vi lab không?".

Nhóm tôi cũng có lúc bị kéo về phía solution-first. Ban đầu khi chọn Workflow, một thành viên
muốn đề xuất ngay việc build tool tự động gom file từ Google Drive. Tôi phải nhắc lại câu hỏi
trong worksheet: "Workflow tuyến tính không cần Agent — tại sao lại build thêm tool khi ChatGPT
hoặc Notion AI hiện tại đã làm được bước này?" Sau đó nhóm mới đồng ý pilot tay trước thay vì
nghĩ đến build.

Điều khó nhất khi viết Problem Statement là phần Success Metric. Lần đầu nhóm chỉ viết "giảm
thời gian" — AI phản biện chỉ ra đây chưa đủ vì không có baseline thật và không có cách đo rõ.
Tôi và Trần Thị Bảo phải ngồi lại tách metric thành 2 phần: metric chính (thời gian bấm giờ,
đo được bằng pilot) và metric phụ (số comment giảng viên về format, đo được qua bài nộp kế tiếp).
Sau khi tách ra như vậy, boundary cũng trở nên rõ hơn tự nhiên — vì biết mình đo gì thì biết
AI được làm gì và không được làm gì.

Nếu làm lại, tôi sẽ validate số liệu baseline sớm hơn, thay vì để đến lúc viết PS mới phát hiện
"75-90 phút" chỉ là ước lượng từ trí nhớ. Dù chỉ bấm giờ 1-2 lần thật sự trước lab, số liệu đó
sẽ làm cho toàn bộ lập luận từ workflow đến decision chặt hơn nhiều.
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
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI:
  - **Problem**: Người tổng hợp bài nhóm mất 75-90 phút vì bước merge + đoạn nối tốn sức nhất.
  - **Workflow**: 7 bước hiện tại → bottleneck chính ở bước 4-6 → future state 4 bước với AI hỗ trợ bước detect + draft đoạn nối.
  - **Metric**: Giảm thời gian tổng hợp từ 75-90 phút xuống dưới 25 phút, đo bằng bấm giờ trong pilot 3 lần nộp bài kế tiếp.
  - **Boundary**: AI không tự quyết định bỏ ý của thành viên, không tự nộp bài, không dùng cho bài thi hoặc bài yêu cầu bảo mật nội dung.
  - **Độ phù hợp AI**: Workflow (không phải Agent) — vì bước AI cần làm là tuyến tính, không có nhánh động, không cần gọi tool, người tổng hợp review toàn bộ output trước khi nộp.
