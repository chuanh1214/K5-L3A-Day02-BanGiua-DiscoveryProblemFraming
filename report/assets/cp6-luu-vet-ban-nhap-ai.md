# CP6 — Lưu vết nội dung AI đã soạn trong lượt trước

> Nội dung lưu để truy vết, không dùng làm phần nhóm tự làm. Khi đối chiếu lại [RULES.md](../../RULES.md), việc AI viết sẵn Problem Statement và kết luận vượt phạm vi “chỉ để phản biện”. Bảng điểm AI cũng không thay cho nhóm tự chấm 7 tiêu chí. Các nội dung dưới đây đã được đưa ra khỏi phần trả lời chính. Nhóm cần tự thực hiện CP3, CP4 và tự viết/chốt v0, v1, quyết định; chỉ đổi nhãn hoặc sao chép lại bản này không đáp ứng yêu cầu đó.
## 2. Hội tụ nhóm (CP3)

### 2.1. Candidate chuẩn bị cho pitch

Chỉ tổng hợp 6 card từ 2 báo cáo đã có nguồn; chưa có bài của các thành viên khác. Chưa có biên bản pitch hoặc câu hỏi trực tiếp giữa các thành viên. CP3 yêu cầu người học tự trình bày và đặt câu hỏi; nhận xét của AI không thay cho hoạt động đó.

| Người đưa ra | Candidate / nhu cầu | Actor | Bước nghẽn theo nguồn | Câu hỏi nhận tại CP3 |
|---|---|---|---|---|
| Hiếu — Card #1 | Xác định hướng để tránh đi bộ nhầm đường | Người học đi bộ | Quay lại khoảng 30 phút; nhận ra nhầm sau 25 phút, theo ước lượng | Chưa được cung cấp |
| Hiếu — Card #2 | Xác định đúng mục nộp bài trên LMS | Người học nộp bài | Chậm phát hiện nhầm khoảng 25 phút; chưa tách thao tác/chờ | Chưa được cung cấp |
| Hiếu — Card #3 | Nắm đủ yêu cầu và luồng làm/nộp lab | Người học làm lab | Đọc hướng dẫn 15 phút trong luồng 45 phút ước lượng | Chưa được cung cấp |
| Bảo — Card #1 | Nắm đầu ra và điều kiện của task | Người học nhận task | Mốc thời gian bước tìm đầu ra chưa thống nhất trong nguồn | Chưa được cung cấp |
| **Bảo — Card #2** | **Tổng hợp bài học để ôn tập** | **Người học sau buổi học** | **Chọn ý/viết lại 20–25 phút theo lời kể; cần đo lại** | Chưa được cung cấp; candidate đã chọn |
| Bảo — Card #3 | Ghi đúng việc sử dụng AI sau lab | Người học viết AI log | Tìm lại lịch sử và ghi các lượt trao đổi | Chưa được cung cấp |

### 2.2. Cluster phân tích đề xuất

| Cluster | Candidate liên quan | Pattern chung |
|---|---|---|
| A — Nắm nội dung để học và làm bài | Bảo #2; Hiếu #3; Bảo #1 | Đọc, xác định thông tin quan trọng và tổ chức lại |
| B — Xác định đúng cách thực hiện | Hiếu #1, #2; Bảo #1 | Chọn sai, phát hiện muộn và mất công sửa |
| C — Nhớ lại việc đã thực hiện | Bảo #3 | Thông tin phân tán, dễ bỏ sót khi ghi cuối buổi |

Đây là phân tích từ tài liệu, chưa phải kết quả workshop đã được nhóm duyệt. Chỉ đào sâu **tổng hợp bài học** trong cluster A; không cộng tác động của các candidate khác nhau.

### 2.3. Opportunity Solution Tree đề xuất

~~~text
OUTCOME: Giảm thời gian tổ chức ghi chú sau buổi học,
         vẫn giữ nội dung đúng, đủ và học viên giải thích được ý chính.
├── Nhận diện được ý quan trọng trong tài liệu của buổi học.
├── Đối chiếu nhanh ghi chú với đúng vị trí trong nguồn.
└── Có bản ghi chú nhất quán, dễ sửa và dùng lại khi ôn tập.
~~~

“Xây chatbot”, “tự tạo flashcard”, “dùng agent tìm tài liệu” là giải pháp/tính năng, không phải opportunity. Chưa có biên bản chứng minh nhóm từng đề xuất/gạch bỏ các ý này.

### 2.4. Shortlist và lý do thu hẹp

Điểm sơ bộ **do AI đánh giá từ tài liệu**, không phải điểm nhóm đã chấm. Điểm 1–5 cao hơn nghĩa là rõ hơn/dễ thử hơn; điểm pain phản ánh độ mạnh bằng chứng. Tiêu chí hiểu domain cần nhóm tự chấm; chưa tính tổng /35 hoặc suy ra thứ hạng nhóm.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng 6 tiêu chí |
|---|---:|---:|---:|---:|---:|---:|---|---:|
| Bảo #2 — Tổng hợp bài học | 5 | 4 | 2 | 3 | 5 | 5 | Nhóm tự chấm | 24/30 |
| Hiếu #1 — Đi nhầm đường | 5 | 4 | 2 | 3 | 3 | 3 | Nhóm tự chấm | 20/30 |
| Hiếu #3 — Nắm yêu cầu lab | 5 | 4 | 2 | 3 | 5 | 5 | Nhóm tự chấm | 24/30 |

**Candidate đã chọn:** Bảo #2, theo xác nhận trực tiếp của Hiếu. Lý do cụ thể trong cuộc thảo luận lựa chọn chưa được cung cấp.

**Lập luận đề xuất:** phạm vi một buổi học giới hạn được, có thể đối chiếu đầu ra với tài liệu và so sánh với template tự điền. Điều kiện là có bộ tài liệu thực tế, quyền sử dụng và chuẩn ý chính; hiện chưa có file đầu vào được cung cấp.

**Vì sao chưa đào sâu các candidate khác:** đi nhầm đường cần quan sát thực địa và xác minh nguyên nhân; nắm yêu cầu lab có phạm vi khác với tổng hợp bài học dù cũng phù hợp để thử. Chưa có bằng chứng hai candidate đó ít giá trị hơn. Điểm sơ bộ hòa nhau không thay cho thảo luận nhóm.

**Xử lý bất đồng:** chưa có thông tin; không suy ra nhóm không có bất đồng.
## 5. Problem Statement v0 — bản nháp từ candidate (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Học viên cần ôn sau buổi học, có tài liệu của buổi đó |
| **Quy trình** | Mở tài liệu → đọc → chọn/viết ý chính → gộp ghi chú |
| **Bottleneck** | Chọn/viết lại được ước lượng 20–25 phút; chưa tách hiểu bài với công tổ chức |
| **Impact** | Một nguồn tự thuật báo tốn nhiều thời gian; chưa có bằng chứng giảm điểm hoặc tác động chung cho cả lớp |
| **Success Metric** | Candidate ban đầu đặt 30–45 → ≤ 10 phút, phủ ≥ 90% ý chính, 0 ý sai; baseline và công review chưa được đo |
| **Boundary** | Học viên đối chiếu và xác nhận bản ghi chú; không dùng nháp chưa kiểm làm nguồn học chính |

**Phản biện AI trong lần rà soát này:** baseline mâu thuẫn; target 10 phút chưa có phép thử; giảm phần chọn ý có thể giảm việc học; thiếu người dùng ngoài nhóm, file đầu vào và chuẩn ý chính; chưa thử template. Nhóm xác nhận đã dùng AI phản biện nhưng chưa cung cấp việc chấp thuận riêng từng nhận xét. v1 dưới đây là đề xuất sửa, chưa phải biên bản nhóm đã thông qua.
## 7. Problem Statement v1 và tiêu chí đánh giá — đề xuất (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Học viên sau buổi học, có tài liệu đầy đủ và được phép sử dụng |
| **Quy trình** | Chuẩn bị nguồn → tự tổng hợp theo template → đối chiếu/sửa/giải thích → lưu bản đã kiểm |
| **Bottleneck** | Công đọc/chọn/viết lại được báo dài nhất; đo để tách phần học cần thiết và công tổ chức có thể giảm |
| **Impact** | Một thành viên báo tốn nhiều thời gian; chưa ngoại suy giờ/tuần cho nhóm hoặc coi toàn bộ là lãng phí |
| **Success Metric** | Baseline chưa thống nhất. Đo ít nhất 3 cặp lượt cách hiện tại/template, tài liệu khác nhau nhưng tương đương. Mục tiêu pilot: trung vị tổng thời gian template thấp hơn ≥ 20%; phủ ≥ 90% ý chuẩn, đủ ý trọng yếu, 0 nhận định sai trong bản cuối, nguồn đúng. Học viên vẫn giải thích được ý trọng tâm. Pilot nhỏ chỉ cho tín hiệu định hướng |
| **Boundary** | Học viên tự đọc, chọn, kiểm và duyệt; chỉ dùng nguồn được phép; không bỏ việc hiểu bài để đạt thời gian. Nếu có AI sau này, không tự duyệt/nộp nháp |
| **AI intervention point** | Không có trong phép thử No AI đầu tiên; chưa chứng minh lợi ích của sinh nháp sau kiểm tra |
| **Mức chọn** | Đề xuất No AI để thử trước; nhóm tự xác nhận mức cuối |
| **Rủi ro & người kiểm tra** | Bỏ ý, hiểu sai, công template tăng; học viên kiểm và một người khác đối chiếu checklist chuẩn. Chưa phân công người kiểm |

### Thay đổi đề xuất từ v0 sang v1

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Bối cảnh | Trước/sau buổi học | Chỉ sau buổi học, nguồn sẵn | Tránh gộp hai loại đầu vào |
| Baseline | Một tổng chưa khớp bước | Giữ chênh lệch, đo lại | Phép cộng không biến ước lượng thành số đo |
| Target | ≤ 10 phút | Giảm tương đối ≥ 20% từ baseline đo lại | Chưa hứa thời gian tuyệt đối; ngưỡng mới vẫn là đề xuất chưa được thử |
| Đối chứng | Template chưa thử | Thử No AI trước | Đánh giá cách đơn giản trước |
| Chất lượng | Độ phủ/lỗi, chuẩn chưa rõ | Chuẩn lập trước, nguồn đúng, đủ ý trọng yếu, tự giải thích | Tránh nhanh hơn nhờ cắt mất việc học |

### Tiêu chí đánh giá template không AI

Nếu thử AI, dùng cùng tiêu chí cho bản cuối và ghi riêng lỗi bản nháp để biết công sửa.

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Độ phủ | ≥ 90% checklist chuẩn, đủ mọi ý trọng yếu đánh dấu trước | Thiếu ngưỡng hoặc thiếu ý trọng yếu |
| 2 | Độ đúng | Không có nhận định sai/làm đổi nghĩa trong bản cuối | Có ý sai hoặc không xác minh được |
| 3 | Truy xuất nguồn | Mọi ý chính có vị trí nguồn đúng, đối chiếu được | Thiếu/sai nguồn hoặc nguồn không hỗ trợ ý |
| 4 | Công sức và hiểu bài | Đạt mục tiêu thời gian; giải thích đúng các ý trọng tâm theo checklist | Nhanh do bỏ đọc/kiểm hoặc không hiểu ý trọng tâm |
| 5 | Phần chưa rõ | Báo thiếu/mâu thuẫn để hỏi lại | Tự điền thông tin thiếu thành sự thật |
### 8.2. Kết luận đề xuất

**Not Yet — chưa triển khai AI; đo và thử template không AI trước.** Phù hợp với nhận định nhóm cần phản hồi thực tế trước triển khai; chưa có biên bản chốt nhãn CP6.

**Bước tiếp theo:** thống nhất phạm vi và nguồn; phỏng vấn ngoài nhóm; thực hiện ≥ 3 cặp lượt cách hiện tại/template theo [phiếu kiểm chứng](../assets/cp4-kiem-chung-tong-hop-bai-hoc.md). Nhóm tự phân công và ấn định lịch.

**Điều kiện Go cho template trong pilot:** đạt ngưỡng thời gian/chất lượng, học viên hiểu và dùng được ghi chú. Chưa kết luận cho mọi học viên từ pilot nhỏ.

**Điều kiện thử AI:** sau đo, template vẫn để lại công tổ chức đáng kể; có nguồn được phép, chuẩn và người review. So AI với template trên lượt mới tương đương. Ngưỡng đề xuất: thêm ≥ 20% lợi ích thời gian sau review/fallback, giữ nguyên tiêu chí chất lượng.

**Ngưỡng dừng:** phát hiện một ý trọng yếu sai/thiếu trong bản đã duyệt → ngừng dùng bản đó, đối chiếu và sửa; sau 3 cặp lượt không đạt lợi ích thời gian hoặc hiểu bài giảm → dừng mở rộng và xem lại pain. Nếu thử AI mà sau 3 cặp AI/template không có lợi ích bổ sung → quay về template. Chưa có lý do nâng lên Agent khi không đạt target.
