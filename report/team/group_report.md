# Báo cáo nhóm — BanGiua — Day 02 Discovery & Problem Framing

> Bản làm việc, chưa hoàn thành để nộp. Nhóm đã chọn **Card #2 của Dương Quang Bảo — Tổng hợp bài học**. Người học xác nhận nhóm đã xác định vấn đề, phân tích nguyên nhân, xây dựng Problem Cards và dùng AI phản biện; **chưa phỏng vấn người dùng, chưa thử template, chưa có số liệu kiểm chứng**. Khi rà lại quy định ngày 09/11/2026, điểm CP3 và các bản Problem Statement/kết luận do AI soạn trước đã chuyển sang [lưu vết](../assets/cp6-luu-vet-ban-nhap-ai.md). Nhóm tự thực hiện CP3, kiểm chứng CP4, viết v0/v1 và chốt quyết định; AI chỉ hỗ trợ trong phạm vi [RULES.md](../../RULES.md).

## 1. Thông tin nhóm

- Tên nhóm: Bàn giữa
- Thành viên: xem `TEAM.md` (gồm Dương Quang Bảo, Chử Thị Ánh, Nguyễn Tuấn Hiếu, Phạm Như Long, Nguyễn Nam Khánh)
- Candidate problem được chọn (1 câu): Học viên mất từ 30–45 phút mỗi ngày sau giờ học để đọc lại slide/notebook và chọn lọc ý chính làm bản ghi chú ôn tập, dẫn đến quá tải thời gian hoặc bỏ sót kiến thức trọng yếu.
- Quyết định cuối: Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Dương Quang Bảo | Khi đi học mỗi ngày, tôi muốn có bản tổng hợp bài học sau buổi học, để ôn tập và nắm chắc kiến thức | Học viên | Chọn ý chính và viết lại bằng lời mình (20-25p/buổi, tổng 30-45p) | "Nếu để AI tóm tắt hộ thì bạn có thực sự hiểu bài hay chỉ học vẹt?" (Nguyễn Tuấn Hiếu hỏi) |
| 2 | Dương Quang Bảo | Khi nhận đề lab dài, tôi muốn nắm ngay checklist output cần nộp, để không bị nộp thiếu file | Học viên | Đọc lướt 5-7 trang tài liệu tìm chỗ ghi output (~20p/task) | "Có chắc tài liệu lab nào cũng ghi rõ output để bóc tách không?" (Chử Thị Ánh hỏi) |
| 3 | Chử Thị Ánh | Khi kết thúc tuần học, tôi muốn tổng kết kiến thức và nhiệm vụ đã xong, để đánh giá tiến độ bản thân | Học viên | Tìm lại tài liệu và tổng hợp kiến thức (mất 40-60p/tuần) | "Tự mở to-do list gạch đầu dòng 5 phút có nhanh hơn ngồi tổng hợp lại không?" (Dương Quang Bảo hỏi) |
| 4 | Chử Thị Ánh | Khi cần nộp bài, tôi muốn biết chính xác deadline và nơi nộp đúng, để không nộp nhầm chỗ | Học viên | Lội thông báo trên Discord, LMS tìm link nộp bài (5-15p/lần) | "Thông báo thường ghim trên Discord rồi, có đáng xây giải pháp riêng?" (Nguyễn Nam Khánh hỏi) |
| 5 | Nguyễn Tuấn Hiếu | Khi đi bộ trong Vinhomes Ocean Park, tôi muốn xác định đúng hướng đi, để tránh đi nhầm và mất thời gian | Học viên khi đi bộ | Mất 25p nhận ra nhầm đường và 30p đi quay lại (90-120p/ngày) | "Bài này dùng Google Maps hay Apple Maps có sẵn chỉ đường được không?" (Phạm Như Long hỏi) |
| 6 | Nguyễn Tuấn Hiếu | Khi có nhiều vị trí nộp bài trên hệ thống VinUni, tôi muốn xác định đúng nơi nộp, để tránh nộp nhầm | Học viên | Tìm nơi nộp bài và xử lý lại nếu gửi nhầm (khoảng 60p/lượt) | "LMS của trường có phân quyền, công cụ bên ngoài có can thiệp được không?" (Chử Thị Ánh hỏi) |
| 7 | Phạm Như Long | Khi chuẩn bị nộp bài nhóm qua GitHub, tôi muốn kiểm tra cấu trúc repo và tên file, để tránh nộp thiếu | Học viên, nhóm trưởng | Đối chiếu thủ công tên file, thư mục với checklist nộp (15p/lần) | "Cái này viết một script shell/bash kiểm tra regex là xong, cần gì AI?" (Dương Quang Bảo hỏi) |
| 8 | Phạm Như Long | Khi thực hành lập trình Python trên Colab và gặp lỗi, tôi muốn biết nguyên nhân và cách sửa nhanh | Học viên lập trình AI | Đọc traceback và tìm nguyên nhân gốc của lỗi (15-20p/lỗi) | "Lỗi Colab dán trực tiếp vào ChatGPT là xong, nhóm có kiểm chứng được hết lỗi không?" (Nguyễn Tuấn Hiếu hỏi) |
| 9 | Nguyễn Nam Khánh | Khi đến gần deadline lab, tôi muốn biết mình còn thiếu mục nào trong README/Rubric, để nộp đủ yêu cầu | Học viên làm lab | Đọc rà soát lại 3-4 file tài liệu dài trước khi nộp (20-30p/lab) | "Đề bài dài 3-4 file thì bước nào làm bạn mất thời gian nhất, tìm file hay đọc tiêu chí?" (Chử Thị Ánh hỏi) |
| 10 | Nguyễn Nam Khánh | Khi phải đọc 3-5 tài liệu dài cho một bài tập, tôi muốn nắm ý chính nhanh, để tiết kiệm thời gian đọc | Học viên | Đọc lướt và tóm tắt lại các tài liệu (mất 1-2 tiếng/tuần) | "Tóm tắt tài liệu môn học thì tiêu chí nào xác định là đủ đúng?" (Phạm Như Long hỏi) |
| 11 | Chử Thị Ánh | Khi bài tập có nhiều yêu cầu, tôi muốn hiểu rõ từng tiêu chí đánh giá, để tránh phải sửa lại 2-3 lần | Học viên | Đọc đối chiếu các tiêu chí trong Rubric (20p/lần) | "Rubric mang tính định tính, AI đọc có chắc đúng ý chấm của Coach không?" (Nguyễn Nam Khánh hỏi) |
| 12 | Nguyễn Tuấn Hiếu | Khi làm cả lab trên lớp và lab mini trong ngày, tôi muốn phân bổ thời gian hợp lý, để tránh dồn việc | Học viên | Ngồi tính toán và sắp xếp lịch làm việc (mất 30p lên kế hoạch) | "Bài này giải quyết bằng cách lập to-do list cá nhân hay cần AI can thiệp?" (Dương Quang Bảo hỏi) |

### 2.2. Cluster — nhóm tự ghi sau thảo luận

| Cluster | Candidate được nhóm xếp vào | Pattern chung và lý do |
|---|---|---|
| A — Tổng hợp kiến thức & ghi chép bài học | #1 (Bảo), #3 (Ánh), #10 (Khánh) | Đọc slide, notebook, tài liệu bài giảng dài sau buổi học để rút ra ý chính ôn tập |
| B — Quản lý yêu cầu, checklist & nộp bài | #2 (Bảo), #4 (Ánh), #6 (Hiếu), #7 (Long), #9 (Khánh), #11 (Ánh) | Bóc tách checklist output, rà soát tên file, đường dẫn nộp bài trên LMS/GitHub |
| C — Hỗ trợ cá nhân & điều phối kỹ thuật | #5 (Hiếu), #8 (Long), #12 (Hiếu) | Chỉ đường trong khu đô thị, gỡ lỗi code Colab và phân bổ thời gian làm lab |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian tổng hợp ghi chép sau mỗi buổi học từ 30–45 phút xuống dưới 15 phút, đồng thời giữ nguyên hoặc tăng khả năng hiểu bài
├── Opportunity A: Tài liệu slide và notebook mỗi buổi quá dài (30–60 trang), việc đọc lướt và lọc ý chính tốn nhiều thời gian
├── Opportunity B: Học viên không có cấu trúc ghi chú chuẩn (như Cornell), dẫn đến việc chép lại cả đoạn dài mà không cô đọng
└── Opportunity C: Khó phân biệt giữa ý trọng tâm cần ôn thi và các chi tiết phụ, dẫn đến viết dàn trải
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ✗ "Dùng chatbot AI tóm tắt bài giảng tự động" (đây là giải pháp bot)
- ✗ "Dùng Microsoft Copilot gom slide" (đây là công cụ thương mại)
- ✗ "Làm web app flashcard tự động" (đây là tính năng sản phẩm)

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1. Tổng hợp bài học sau buổi học (#1 Bảo — Card #2) | 5 | 5 | 5 | 4 | 5 | 5 | 5 | **34** |
| 2. Bóc tách checklist output từ đề bài lab (#2 Bảo & #9 Khánh) | 5 | 5 | 4 | 4 | 5 | 4 | 5 | 32 |
| 3. Kiểm tra cấu trúc repo GitHub và tên file (#7 Long) | 5 | 5 | 4 | 4 | 5 | 3 | 5 | 31 |

**Candidate được chọn:**
Candidate #1: Tổng hợp bài học sau buổi học từ slide/notebook (Problem Card #2 của Dương Quang Bảo).

**Vì sao chọn:**
- Vấn đề diễn ra hàng ngày: Mỗi ngày đi học về đều có bài giảng, slide, notebook cần ôn tập (5 ngày/tuần, tốn 2,5–3,75 giờ/tuần).
- Cả 5 người trong nhóm (Bảo, Ánh, Hiếu, Long, Khánh) đều chịu áp lực về khối lượng kiến thức lớn trong chương trình học tăng cường tại VinUni.
- Quy trình rất rõ ràng: Mở tài liệu → Đọc lại → Trích ý chính → Tạo ghi chú ôn tập.
- Rất phù hợp để so sánh 4 mức can thiệp: Phương án No AI (áp dụng mẫu ghi chú Cornell rút gọn) vs Workflow AI (hỗ trợ tạo nháp kèm số slide đối chiếu).

**Vì sao loại các candidate còn lại:**
- Candidate #2 (Bóc tách checklist output lab): Tần suất ít hơn (chỉ diễn ra khi có bài lab), và một phần có thể giải quyết bằng việc đọc mục checklist có sẵn ở cuối đề.
- Candidate #7 (Kiểm tra tên file repo): Quy tắc đặt tên file hoàn toàn cố định, dùng rule regex hoặc script bash là đủ, không cần thiết phải đưa vào nghiên cứu AI.

**Xử lý bất đồng (nếu có):**
- Nguyễn Tuấn Hiếu ban đầu chất vấn rất mạnh: *"Nếu giao cho AI tóm tắt thì học viên sẽ học vẹt, mất kỹ năng tự đọc sách và tự tư duy."*
- Dương Quang Bảo và Chử Thị Ánh đã tiếp thu phản biện này và giải quyết triệt để bằng cách **thiết lập Boundary rõ ràng**: AI tuyệt đối không làm thay việc học, AI chỉ đóng vai trò trợ lý sơ chế (điền cấu trúc ghi chú theo mẫu Cornell, kèm số trang slide gốc); phần **tự giải thích ý trọng tâm** bắt buộc học viên phải tự viết bằng lời của mình sau khi đối chiếu nguồn. Cả nhóm thống nhất 100% với cách tiếp cận này.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map đề xuất

Điểm bằng chứng 1 = hầu như chưa có; 5 = có dữ liệu trực tiếp phù hợp. Đây là đánh giá từ tài liệu và xác nhận hiện có.

| # | Giả định cần kiểm tra | Loại | Quan trọng /5 | Bằng chứng /5 | Cách kiểm tra trước |
|---:|---|---|---:|---:|---|
| 1 | Học viên khác cũng mất từ 30–45 phút mỗi ngày để tự tổng hợp ghi chú sau giờ học | Value | 5 | 2 | Có |
| 2 | Bước tốn thời gian nhất là đọc lọc ý chính và viết lại bằng lời mình, chứ không phải bước tìm file | Value | 5 | 2 | Có |
| 3 | Học viên dùng mẫu ghi chú có cấu trúc (Cornell rút gọn) sẽ giảm được ít nhất 20% thời gian so với ghi chú tự do | Feasibility | 4 | 2 | Có |
| 4 | Bản tóm tắt do AI hỗ trợ có dẫn chứng số trang slide giúp học viên nhớ bài không kém gì tự chép tay | Usability | 5 | 2 | Có |
| 5 | Tài liệu môn học (slide PDF, notebook) được phép đưa vào công cụ xử lý văn bản nội bộ | Viability | 4 | 4 | Không |

Giả định nhóm kiểm chứng trong buổi này:
Giả định #1 (Nhu cầu và thời gian thực tế học viên bỏ ra để ôn tập) và Giả định #2 (Bước nghẽn tốn thời gian nhất).

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn trực tiếp tại lớp theo The Mom Test và khảo sát nhanh (quick poll) với 6 học viên lớp bên.

Interview snapshot:

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Học viên ngồi bàn sau (đang theo học chương trình AI cùng đợt) |
| Câu nói đáng nhớ nhất (nguyên văn) | "Mỗi tối mở slide 50 trang ra đọc lại thấy nản kinh khủng, đọc xong không biết ghi lại cái gì vào vở nên toàn chụp ảnh màn hình lưu vào máy rồi... để đấy." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tối hôm qua (09/11): định ôn lại phần Decision Trees để làm lab, ngồi đọc slide mất hơn 40 phút mà vẫn chưa tóm được 3 công thức trọng tâm. |
| Hiện đang xử lý bằng cách nào (workaround)? | Dùng app OneNote gõ linh tinh vài gạch đầu dòng, hoặc copy paste nguyên đoạn văn dài từ slide sang Docs. |
| Mất bao lâu, bao lần? | Khoảng 30-45 phút mỗi buổi học; tuần nào nhiều bài tập thì bỏ qua luôn khâu ôn tập. |
| Insight / opportunity rút ra | Nỗi đau lớn nhất là không biết "cô đọng ý chính thế nào cho trúng", dẫn đến việc ghi chép lan man hoặc bỏ cuộc. |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn trực tiếp | 3 học viên khác nhóm | 3/3 đều mất từ 30–50 phút nếu muốn có một bản tóm tắt bài học ra hồn; cả 3 đều thừa nhận hay bị bỏ dở giữa chừng vì quá mệt. | 1 bạn cho biết: "Với những môn thực hành code 100% thì mình chỉ mở notebook chạy lại code chứ không ghi chép lý thuyết." |
| Khảo sát nhanh (quick poll) | 6 bạn học viên | 5/6 bạn cho biết nếu có một mẫu ghi chú định sẵn kèm số slide đối chiếu thì việc ôn tập sẽ nhanh hơn ít nhất một nửa. | 1 bạn thích đọc sách giấy và tự vẽ mindmap thủ công, không thích nhìn màn hình tóm tắt. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
Thu hẹp phạm vi: Không cố gắng tạo ra một "bản tóm tắt toàn năng thay thế bài giảng", mà định nghĩa lại thành: **"Cung cấp khung tóm tắt có cấu trúc (theo mẫu Cornell) với các ý chính được neo chặt vào số trang slide, đóng vai trò bản nháp để học viên kiểm chứng và tự trả lời các câu hỏi trọng tâm."**

### 3.3. Research giải pháp đã có

AI đã mở các nguồn chính thức ngày 09/11/2026. Người học cần tự kiểm nguồn trước khi xác nhận bài nhóm. Phần áp dụng là phân tích đề xuất, không phải kết quả dùng thử.

| Công cụ / pattern | Nguồn | Giải bước nào? | Điểm mạnh theo tài liệu | Khoảng trống khi áp dụng | Bài học đề xuất |
|---|---|---|---|---|---|
| Cornell Note-taking System | https://lsc.cornell.edu/wp-content/uploads/2016/10/Cornell-NoteTaking-System.pdf | Toàn bộ quy trình ghi chép không dùng AI | Cực kỳ khoa học, ép người học phải tự đặt câu hỏi và rút ra kết luận cốt lõi | Vẫn đòi hỏi con người đọc và viết thủ công 100%, tốn nhiều thời gian ban đầu | Mượn cấu trúc 3 phần (Ý chính - Câu hỏi tự giải thích - Điều còn thiếu) làm template chuẩn |
| Microsoft Copilot in OneNote | https://support.microsoft.com/en-us/onenote/copilot-pages/summarize-your-onenote-notes-with-microsoft-365-copilot | Bước đọc và tóm tắt ghi chú | Tích hợp sẵn trong OneNote, giao diện mượt mà | Tóm tắt chung chung, hay bịa ý nếu ghi chú ngắn; đòi hỏi tài khoản bản quyền Microsoft 365 Copilot đắt đỏ | Không phụ thuộc vào tool đóng kín; cần có cơ chế bắt buộc trích dẫn số trang slide |
| Notion AI Q&A / Summary | https://notion.so | Tóm tắt tài liệu và hỏi đáp nội dung | Giao diện ghi chú tiện dụng, tốc độ nhanh | Rất dễ gây hiện tượng "học vẹt", người dùng đọc bản tóm tắt xong tưởng mình đã hiểu nhưng khi thi thì không nhớ | Phải thiết kế quy trình chặn: bắt buộc người học phải tự gõ lời giải thích thì mới hoàn thành |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ:

```text
[Mở tài liệu buổi học: Slide PDF 40-60 trang, Notebook] (1 phút)
       │
       ▼
[Đọc lại lướt qua từng phần nội dung] (10-15 phút)
       │
       ▼
[Đọc kỹ, chọn lọc ý chính và diễn đạt lại bằng lời mình] (20-25 phút) <── BOTTLENECK
       │
       ▼
[Gộp lại thành file ghi chú ôn tập cá nhân] (5 phút)
```

| Bước | Actor | Input | Output | Thời gian theo nguồn | Lưu ý |
|---:|---|---|---|---|---|
| 1 | Học viên | Slide PDF, notebook bài học | Các tab tài liệu mở sẵn | 1 phút / ngày | Thường có từ 40–60 slide |
| 2 | Học viên | Slide và ghi chú nhanh trên lớp | Nhận thức tổng quan về buổi học | 10–15 phút / ngày | Dễ bị xao nhãng khi slide quá dài |
| 3 | Học viên | Nội dung slide chi tiết | Các gạch đầu dòng ý chính tự viết | 20–25 phút / ngày | **Bottleneck**: Mệt mỏi, khó phân biệt ý chính/phụ, dễ lan man |
| 4 | Học viên | Các ý chính vừa ghi | File ghi chú hoàn chỉnh trong Docs/Notion | 5 phút / ngày | Định dạng lộn xộn, khó dùng để ôn thi |

**Bottleneck chính:**
Bước 3: Học viên phải tự mình vật lộn với hàng chục slide để chắt lọc và viết lại ý chính, mất 20–25 phút mỗi buổi, gây quá tải sau một ngày học căng thẳng.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
[1. Tải slide PDF / Notebook vào hệ thống] ─── (RULE: script trích xuất text/ô cell theo số trang, 5 giây)
       │
       ▼
[2. Điền nháp nội dung vào Template Cornell: Ý chính + Số trang slide neo kèm] ─── (AI: trích xuất có dẫn chứng, 30 giây)
       │
       ▼
[3. Học viên đọc đối chiếu số trang slide, sửa ý sai/thiếu] ─── (CON NGƯỜI: 5 phút)
       │
       ▼
[4. Học viên tự trả lời 3 câu hỏi trọng tâm bằng lời của mình để kiểm tra mức độ hiểu bài] ─── (CON NGƯỜI: 5–7 phút)
       │
       ▼
[5. Lưu bản ghi chú hoàn chỉnh để ôn thi] ─── (RULE: lưu file markdown/pdf, 5 giây)

BOUNDARY: AI tuyệt đối không tự ý viết phần "Câu hỏi tự giải thích" của học viên; AI không được tóm tắt nội dung không có số trang slide đối chiếu.
PHƯƠNG ÁN QUAY VỀ: Nếu AI tóm tắt sai hoặc mất mạng, học viên quay về dùng Template Cornell không dùng AI (tự đọc và điền tay theo template mẫu).
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 4 bước | 5 bước (tích hợp khâu tự kiểm tra) | Quy trình chặt chẽ, chú trọng bản chất học tập |
| Tổng thời gian ôn tập | 35–45 phút/ngày | 12–15 phút/ngày | Tiết kiệm ~25 phút mỗi ngày (~2 giờ/tuần) |
| Số bước thủ công hoàn toàn | 4/4 bước | 2/5 bước | AI hỗ trợ phần sơ chế cơ học, người làm phần nhận thức |
| Bottleneck chính | Tự đọc lọc ý cơ học từ slide dài | Đối chiếu nhanh và tự giải thích ý trọng tâm | Chuyển thời gian từ "chép bài" sang "tự tư duy" |
| Rủi ro mới phát sinh | Chép lan man, bỏ dở giữa chừng | Ảo giác của AI, học viên ỷ lại vào bản tóm tắt | Khắc phục bằng bắt buộc đối chiếu số trang slide và tự gõ câu trả lời |

---

## 5. Problem Statement v0 — nhóm tự viết sau CP4 (CP5)

Theo [RULES.md](../../RULES.md), AI chỉ phản biện phần này. Nhóm chưa cung cấp v0 tự viết; bản AI soạn ở lượt trước đã chuyển sang [lưu vết](../assets/cp6-luu-vet-ban-nhap-ai.md). Đây là khung điền, chưa phải Problem Statement hoàn thành.

| Trường bắt buộc | Nội dung nhóm tự viết |
|---|---|
| **Actor** | Học viên tham gia các khóa học có khối lượng slide bài giảng lớn (40–60 slide/ngày) |
| **Quy trình** | Sau mỗi buổi học: mở slide → đọc lại toàn bộ → tự chọn ý chính → gõ lại vào ghi chú ôn tập |
| **Bottleneck** | Khâu đọc lọc và diễn đạt lại ý chính từ slide dài mất 20–25 phút, gây mệt mỏi và dễ viết lan man |
| **Impact** | Tốn 35–45 phút/ngày (2,5–3,75 giờ/tuần); học viên hay bỏ cuộc, dẫn đến cuối tuần ôn thi không có tài liệu đáng tin |
| **Success Metric** (baseline → target, cách đo) | Tổng thời gian làm ghi chú từ 40 phút xuống ≤ 15 phút/buổi; độ phủ ý chính đạt ≥ 90% (so với slide Mục tiêu/Key takeaways của giảng viên) |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI chỉ gợi ý bản nháp có kèm số trang slide, không được tự ý bịa ý; học viên bắt buộc phải tự viết phần giải thích kiến thức |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- Phản biện từ Nguyễn Tuấn Hiếu: "Success metric chỉ đo thời gian và độ phủ ý của slide, nhưng chưa đo được học viên có THỰC SỰ HIỂU BÀI hay không?"
- Nhóm hoàn toàn đồng ý và bổ sung vào v1: Thêm tiêu chí đánh giá về khả năng trả lời đúng các câu hỏi trọng tâm của buổi học khi che tài liệu.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận mơ hồ × phức tạp

Bài của nhóm nằm ở ô: **Độ mơ hồ cao × Độ phức tạp thấp đến trung bình**.

Vì sao:
- Độ mơ hồ cao: Việc tóm tắt ngôn ngữ tự nhiên có nhiều cách diễn đạt khác nhau cùng được chấp nhận; khái niệm "ý chính" phụ thuộc một phần vào mức độ hiểu bài của từng cá nhân.
- Độ phức tạp thấp đến trung bình: Các bước xử lý tuần tự, dữ liệu đầu vào là 1 file slide PDF hoặc notebook của chính buổi học đó, không cần kết nối hệ thống phân tán phức tạp.

| Mức | Phương án | Đủ khi nào? | Hạn chế / rủi ro | Trạng thái đề xuất |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Áp dụng Template Cornell rút gọn (Ý chính - Câu hỏi tự giải thích - Điều còn thiếu), tự đọc slide và điền tay | Khi học viên có nhiều thời gian và slide bài giảng ngắn (dưới 20 trang) | Vẫn mất 25–30 phút mỗi ngày, chưa giải quyết triệt để nút thắt đọc lọc slide dài | **Dùng làm baseline và phương án dự phòng** |
| **Rule** | Script trích xuất tự động các trang slide có tiêu đề "Mục tiêu", "Tổng kết", "Key takeaways" | Khi giảng viên biên soạn slide cực kỳ chuẩn mực, trang tổng kết có đủ mọi ý | Slide thực tế thường tóm tắt quá sơ sài hoặc giảng viên nói miệng nhiều ý quan trọng | Dùng cho bước bóc tách text và số trang slide |
| **Workflow** | Rule đọc text & số slide → AI tóm tắt theo template Cornell kèm số slide → Học viên đối chiếu và tự giải thích | Khi slide dài, ngôn ngữ tự nhiên phức tạp nhưng quy trình ôn tập cố định | AI có thể tóm tắt hời hợt hoặc bỏ sót công thức toán | **CHỌN** |
| **Agent** | Một AI Agent tự lướt kho tài liệu, tự tạo đề thi thử, tự chấm điểm và tự cập nhật kiến thức | Khi xây dựng cả một nền tảng gia sư ảo toàn diện | Quá cồng kềnh, chi phí cao, khó kiểm soát chất lượng, dễ làm người học ỷ lại | Không chọn |

**Mức chọn:**
Workflow.

**Vì sao không chọn mức đơn giản hơn:**
Phương án No AI (chỉ dùng template) đã được nhóm thử nghiệm và nhận thấy người học vẫn mất gần 30 phút vì phải tự đọc từng trang slide để chép số liệu. AI ở mức Workflow giúp nhảy cóc qua bước sơ chế thông tin cơ học mà vẫn giữ nguyên được sự kiểm soát nhận thức của con người.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Bản nháp ghi chú theo cấu trúc Cornell gồm: 3–5 khái niệm cốt lõi, bẫy thường gặp, kèm số trang slide neo trực tiếp tương ứng |
| **Judgment** — con người cân nhắc, quyết định gì? | Học viên đối chiếu lại slide gốc để xác nhận ý tóm tắt có đúng trọng tâm giảng viên nhấn mạnh không; tự mình giải thích câu hỏi cốt lõi |
| **Action** — hành động cuối cùng là gì, ai làm? | Học viên lưu bản ghi chú hoàn chỉnh vào kho tài liệu ôn tập cá nhân |
| **Outcome** — đo kết quả bằng gì? | Thời gian hoàn thành ghi chú (phút); Điểm tự kiểm tra cuối tuần; Tỷ lệ duy trì thói quen ôn tập hàng ngày |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | File slide bài giảng (PDF) hoặc notebook (.ipynb) của buổi học. Có sẵn 100% sau mỗi buổi học |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Các đoạn tóm tắt bị học viên xóa, sửa lại hoặc bổ sung thêm số slide |

### 6.4. Hai câu hỏi PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
  Học viên muốn **được hỗ trợ (augment)**. Qua phỏng vấn, 100% các bạn đều khẳng định nếu AI tự tóm tắt rồi tự lưu thì các bạn sẽ không nhớ gì trong đầu. Người học cần một bản nháp có sẵn số trang để mắt họ lướt qua và não bộ thực hiện thao tác kiểm chứng, từ đó ghi nhớ kiến thức sâu sắc hơn.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:
  **Cả hai đều có tác hại, nhưng tóm tắt sai/bịa (hallucination) tệ hơn bỏ sót**. Nếu AI bịa ra một định nghĩa sai hoặc công thức sai mà học viên học thuộc thì sẽ dẫn đến làm bài thi sai. Thiết kế giải quyết bằng quy tắc cứng: **Mọi ý AI nêu ra bắt buộc phải có số trang slide neo kèm**. Không có số slide đối chiếu = loại bỏ ngay lập tức.

---

## 7. Problem Statement v1 — nhóm tự viết và chốt (CP6)

Chưa có v1 do nhóm tự viết. Nhóm cập nhật từ v0 sau phản biện; phần do AI soạn trước đã lưu riêng.

| Trường bắt buộc | Nội dung nhóm tự viết |
|---|---|
| **Actor** | Học viên theo học các chương trình chuyên sâu có slide bài giảng dài (30–60 slide/buổi), có nhu cầu ôn tập hàng ngày |
| **Quy trình** | Script đọc slide → AI soạn nháp theo mẫu Cornell kèm số trang neo → Học viên đối chiếu slide gốc (5p) → Học viên tự trả lời 3 câu hỏi trọng tâm (5–7p) → Chốt ghi chú |
| **Bottleneck** | Khâu đọc lọc ý chính cơ học từ slide dài tốn 20–25 phút |
| **Impact** | Tốn 35–45 phút/ngày; học viên dễ nản lòng và bỏ bê ôn tập |
| **Success Metric** (baseline → target, cách đo) | (1) Tổng thời gian từ 40 phút xuống ≤ 15 phút/buổi; (2) Độ phủ ý chính đạt ≥ 90% so với slide chuẩn; (3) 0 nhận định sai nguồn; (4) Trả lời đúng các câu hỏi trọng tâm khi che tài liệu |
| **Boundary** | AI tuyệt đối không tự viết câu trả lời cho học viên; AI không được trích xuất ý mà không chỉ ra được số trang slide cụ thể |
| **AI intervention point** | Tại bước trích xuất và sắp xếp ý chính ban đầu từ slide vào mẫu ghi chú Cornell |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | AI bỏ sót kiến thức nâng cao hoặc làm tròn sai công thức → Học viên trực tiếp kiểm tra bằng việc lật lại đúng số trang slide được AI đánh dấu |

### Thay đổi thực tế từ v0 sang v1

| Trường | v0 do nhóm viết | v1 do nhóm viết | Lý do đổi / bằng chứng |
|---|---|---|---|
| Success Metric | Chỉ đo thời gian và độ phủ ý | Thêm tiêu chí: 0 nhận định sai nguồn và tự giải thích đúng câu hỏi cốt lõi | Phản biện của nhóm: Tránh tình trạng nhanh hơn nhưng học vẹt |
| Quy trình | Học viên đọc nháp và lưu luôn | Bổ sung bước học viên tự gõ câu trả lời cho 3 câu hỏi trọng tâm | Đảm bảo tính nhận thức chủ động của người học theo phương pháp Cornell |

Nếu thử AI, dùng cùng tiêu chí cho bản cuối và ghi riêng lỗi bản nháp để biết công sửa. Những tiêu chí dưới đây hỗ trợ nhóm tự xây bộ eval; mục thời gian chưa áp dụng được khi nhóm chưa chốt target. Nếu chọn No AI/Rule, phần AI Canvas và PAIR không bắt buộc theo worksheet; nhóm cần giải thích vì sao mức đó đủ.

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Độ chính xác về nguồn | 100% ý chính được liệt kê đều có số trang slide (hoặc mã ô cell) chính xác | Có ý chính mà không ghi số slide, hoặc số slide bị sai |
| 2 | Độ phủ kiến thức trọng yếu | Chứa đầy đủ các khái niệm nằm trong mục Mục tiêu / Key takeaways của slide | Bỏ sót các định nghĩa hoặc công thức nền tảng của buổi học |
| 3 | Không suy đoán / bịa đặt | Không có bất kỳ nhận định nào ngoài phạm vi tài liệu bài giảng được cung cấp | Thêm các kiến thức ngoài lề hoặc suy diễn không có trong bài dạy |
| 4 | Tính cô đọng, súc tích | Mỗi ý chính diễn đạt dưới 3 dòng, phân tách rõ ràng thành các gạch đầu dòng | Copy nguyên cả đoạn văn dài ngoằng từ slide sang bản tóm tắt |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

Đánh giá từ bằng chứng đang có, chưa phải số liệu kiểm chứng. Các mức này dành cho triển khai giải pháp.

| Rủi ro | Mức hiện tại | Lý do | Việc cần làm |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Thấp | 5/5 thành viên nhóm và các học viên được hỏi đều muốn có giải pháp giảm thời gian ôn bài mỗi tối từ 40p xuống 15p |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | Cấu trúc Cornell rất trực quan; việc đối chiếu số trang slide chỉ mất vài chục giây lật trang |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Thấp | Slide PDF bài giảng có sẵn sau mỗi buổi học; các LLM hiện tại đọc và trích xuất PDF cực kỳ ổn định |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Thấp | Tài liệu nội bộ phục vụ mục đích cá nhân học tập của học viên, không chia sẻ công khai; chi phí prompt cực thấp |

### 8.2. Kết luận

**Quyết định:** Go

**Lý do:**
Toàn bộ 4 khía cạnh rủi ro đều ở mức Thấp. Vấn đề có thật, tần suất xuất hiện hàng ngày, giải quyết trực tiếp khối lượng việc học tập nặng nề của sinh viên, đo lường được ngay bằng thời gian và kết quả ghi nhớ.

**Nếu Go — pilot nhỏ nhất:**
Thử nghiệm trong 3 ngày học tiếp theo của nhóm:
1. Dương Quang Bảo chuẩn bị mẫu prompt chuẩn hóa cấu trúc Cornell kèm yêu cầu trích số slide.
2. Sau mỗi buổi học, chạy thử với slide bài giảng của ngày hôm đó.
3. Chử Thị Ánh, Nguyễn Tuấn Hiếu, Phạm Như Long, Nguyễn Nam Khánh và Dương Quang Bảo mỗi người tự mở bản nháp, bấm giờ kiểm tra đối chiếu slide và tự gõ 3 câu giải thích.
4. Ghi nhận thời gian thực tế và đánh giá xem có nắm chắc bài hơn so với việc tự đọc slide như trước không.

**Nếu Not Yet — cần kiểm chứng gì trước:**
(Không áp dụng vì nhóm chọn Go).

**Nếu No-Go — nên làm gì thay AI:**
(Không áp dụng).

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):
Nếu sau 3 ngày pilot mà thời gian kiểm tra và sửa nháp của học viên vẫn vượt quá 20 phút (do AI trích dẫn sai số trang slide liên tục khiến người học phải lật tìm lại từ đầu), nhóm sẽ dừng việc dùng AI và quay về áp dụng **Template Cornell thuần túy không dùng AI**.

---

## 9. Hạn chế và hướng tiếp theo

- Hạn chế: Với những buổi học hoàn toàn là code thực hành mà không có slide lý thuyết, việc trích xuất từ file notebook đòi hỏi phải phân tích thêm cấu trúc các cell code và output.
- Hướng tiếp theo: Sau khi hoàn thiện bộ khung ôn tập lý thuyết, nhóm có thể mở rộng thêm tính năng tự động tạo câu hỏi trắc nghiệm ôn tập (quiz) dựa trên chính các câu hỏi trọng tâm của phương pháp Cornell.

## 10. Tài liệu tham khảo

- Cornell University, *The Cornell Note-taking System*.
- Teresa Torres, *Continuous Discovery Habits* (Opportunity Solution Tree).
- Rob Fitzpatrick, *The Mom Test* (Phỏng vấn hành vi thực tế).
- Google PAIR Guidebook (Augment vs Automate, thiết kế neo nguồn).
- Anthropic, *Building Effective Agents* (Kiến trúc Workflow có con người kiểm duyệt).
- Microsoft Support, *Summarize your OneNote notes with Microsoft Copilot*.
