# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Dương Quang Bảo  
- MSSV: 2A202603362
- Email trường (không bắt buộc, repo có thể để public):26ai.baodq3@vinuni.edu.vn
- Tên nhóm: Bàn giữa
- Link repo nhóm: https://github.com/chuanh1214/K5-L3A-Day02-BanGiua-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Cần đọc, tổng hợp nhiều thông tin |Khi mỗi ngày đi học tôi muốn có thông tin tổng hợp của bài học hôm đó trước khi vào học hoặc sau khi học xong để chuẩn bị trước và ôn tập bài học | Tôi | 30-45 phút/ngày tổng hợp thông tin |
| 2 |Lặp lại | Khi vào các buổi trong này tôi muốn có thông tin chi tiết lịch học đúng nhất để tham dự đúng buổi học | Tôi | Mỗi ngày khoảng 3-4 lần, 5p/lần |
| 3 |Pain từ người khác | Khi commit bài tập, các thành viên trong team muốn xác nhận rõ các thông tin cần commit để tránh commit nội dung không chính xác | Tôi, Team | Team hỏi lại 2-3 lần/bài tập |
| 4 | Tốn thời gian | Khi nhận 1 task tôi muốn nắm nhanh các output và yêu cầu để commit đúng hạn | Tôi, team | Khoảng 30p/task, 10 tasks/tuần |
| 5 | Cần đọc, tổng hợp nhiều thông tin |Khi có quá nhiều task cùng hạn, tôi muốn biết nên làm việc nào trước, để không trễ việc quan trọng|Tôi, team |Tuần trước trễ 2 task vì ưu tiên sai
| 6 | Cần đọc, tổng hợp nhiều thông tin|Khi có quá nhiều task, tôi muốn biết task nào nộp ở link nào, để tránh nộp sai link|tôi, team, coach |Tuần trước nộp sai 2 tasks
| 7 | Lặp lại|	Khi cần viết AI log / phản ánh sau mỗi lab, tôi muốn nhớ lại chính xác mình đã hỏi gì và sửa gì, để không phải ngồi nhớ lại cuối buổi|	Tôi| 20p viết log mỗi lab; 2 mục bị quên hoặc ghi thiếu
| 8 | Tốn thời gian|	Khi lỡ một buổi học hoặc hội thảo, tôi muốn nắm nhanh nội dung chính và việc cần làm, để theo kịp mà không phải xem lại cả buổi	|Tôi|	Xem lại khoảng 30p/buổi

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Nắm nhanh output và yêu cầu của task (#4) | Tốn thời gian nhất, có baseline đo thật, đề task cũ làm bộ test được | "Đủ đúng" đo thế nào (bỏ sót output hay yêu cầu)? 30p là số đo thật hay ước chừng? |
| 2 | Tổng hợp bài học mỗi ngày (#1) | Lặp lại hằng ngày, 30–45p/ngày, nguồn có sẵn (slide, notebook), tự kiểm chứng được | Bản tóm tắt "đủ tốt" đo thế nào? Nếu phải kiểm tra lại thì còn tiết kiệm không? |
| 3 | Viết AI log sau mỗi lab (#7) | Phạm vi hẹp, có số đo (20p/lab, 2 mục quên/lab), nguồn là lịch sử chat của chính mình | Xuất được lịch sử chat từ mọi công cụ không? Log phải đúng sự thật nên ai là người xác nhận? |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận một task mới, tôi muốn nắm nhanh các output cần nộp và yêu cầu kèm theo, để commit đúng hạn và đúng nội dung |
| Actor | Tôi (học viên)|
| Thời điểm / bối cảnh | Mỗi lần nhận task trong tuần (khoảng 10 task/tuần), trước khi bắt đầu làm |
| Quy trình hiện tại | 1. Nhận task 2. Mở đề hoặc thông báo, đọc toàn bộ 3. Tìm những chỗ nói về output cần nộp 4. Tìm yêu cầu kèm theo (định dạng, tiêu chí, deadline) 5. Tự ghi chú lại hoặc hỏi lại team / coach nếu chưa rõ |
| Bottleneck | Bước 3 khoảng 20 phút/task  |
| Impact | ~5 giờ/tuần (30p × 10 task). Khi hiểu sai yêu cầu: team hỏi lại 2–3 lần/bài tập, tuần trước nộp sai 2 task |
| Success metric | Thời gian nắm yêu cầu: 20p/task → ≤ 5p/task; số output/yêu cầu bị bỏ sót so với đề: đo trên các task cũ, mục tiêu 0 bỏ sót; số lần hỏi lại team, coach: 2–3 lần → ≤ 1 lần/bài |
| Phương án không dùng AI | Một template checklist cố định cho mọi task (Output / Yêu cầu / Deadline / Link nộp / Ai làm), tự điền khi đọc đề |
| Giả thuyết về AI | Đưa đề task vào, mô hình trích ra đúng template trên kèm đoạn trích nguyên văn từ đề để đối chiếu; tôi là người xác nhận trước khi dùng. AI chỉ có giá trị nếu nó nhanh hơn template tự điền mà không bỏ sót nhiều hơn |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
1. Nhận task
2. Mở đề hoặc thông báo, đọc toàn bộ (5p)
3. Tìm những chỗ nói về output cần nộp(15) <- BOTTLENECK
4. Tìm yêu cầu kèm theo (định dạng, tiêu chí, deadline) (5p)
5. Tự ghi chú lại hoặc hỏi lại team / coach nếu chưa rõ (5p)
```


### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi đi học mỗi ngày, tôi muốn có bản tổng hợp nội dung của buổi học trước hoặc sau khi học, để chuẩn bị trước và ôn tập hiệu quả |
| Actor | Tôi (học viên) |
| Thời điểm / bối cảnh | Mỗi ngày có buổi học, trước buổi học (chuẩn bị) hoặc sau buổi học (ôn tập) |
| Quy trình hiện tại | 1. Mở tài liệu của buổi (slide, notebook, ghi chú) 2. Đọc lại qua từng phần 3. Chọn ý chính và ghi lại bằng lời của mình 4. Gộp thành một bản ghi chú ôn tập |
| Bottleneck | Bước 3 (chọn ý chính và viết lại)|
| Impact | ~2,5–3,75 giờ/tuần (30–45p × 5 ngày học). Nếu không giải: vào buổi học chưa chuẩn bị, hoặc ôn tập thiếu bản tổng hợp đáng tin |
| Success metric | Thời gian tổng hợp: 30–45p/ngày → ≤ 10p/ngày; độ phủ ý chính: ≥ 90% ý trong checklist ý chính do tôi lập tay từ 3 buổi cũ, và 0 ý sai; kết quả tự kiểm tra cuối tuần không thấp hơn khi tự tổng hợp |
| Phương án không dùng AI | Template ghi chú cố định (Mục tiêu buổi / 3–5 khái niệm / Bẫy hay gặp / Việc cần làm), tự điền từ phần Mục tiêu và Tổng kết có sẵn trong slide |
| Giả thuyết về AI | Đưa slide hoặc notebook của buổi vào, mô hình điền đúng template trên kèm số slide hoặc tên ô để đối chiếu; tôi đọc và sửa trước khi dùng. AI chỉ đáng giá nếu nhanh hơn tự điền template và không bỏ sót ý hơn |
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```text
1. Mở tài liệu của buổi (1p)
2. Đọc lại qua từng phần (10-15p)
3. Chọn ý chính và ghi lại bằng lời của mình (20-25p) <- BOTTLENECK
4. Gộp thành bản ghi chú ôn tập (5p)
```


### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi viết AI log sau mỗi lab, tôi muốn nhớ lại chính xác mình đã hỏi AI gì và đã sửa hoặc kiểm chứng gì, để không phải ngồi nhớ lại cuối buổi và không bỏ sót mục nào |
| Actor | Tôi (học viên); người đọc log: giảng viên, coach |
| Thời điểm / bối cảnh | Cuối mỗi buổi lab, trước khi nộp bài (có sử dụng AI ở bất kỳ phần nào) |
| Quy trình hiện tại | 1. Mở lại lịch sử chat với AI trong buổi lab 2. Cuộn lại tìm từng lần hỏi AI 3. Ghi mỗi lần: phần nào, hỏi gì, AI trả lời hoặc viết gì 4. Nhớ lại mình đã sửa hoặc kiểm chứng gì 5. Điền vào bảng AI log |
| Bottleneck | Bước 2 và 3 (cuộn lịch sử, tìm lại các lần hỏi)  |
| Impact | ~20p × 5 lab/tuần . Mỗi lab bị quên hoặc ghi thiếu ~2 mục, nên log không phản ánh đúng thực tế sử dụng AI |
| Success metric | Thời gian viết log: 20p/lab → ≤ 7p/lab; số mục bị quên hoặc ghi thiếu: 2/lab → 0, đo bằng cách đối chiếu với lịch sử chat; 100% mục có ghi nguồn (lượt chat nào) để kiểm tra lại |
| Phương án không dùng AI | Ghi log ngay trong lúc làm (thêm một dòng vào bảng mỗi lần hỏi AI, thay vì dồn đến cuối buổi) |
| Giả thuyết về AI | Đưa lịch sử chat vào, mô hình liệt kê các lần hỏi AI theo từng phần của lab, kèm trích đoạn để đối chiếu. Phần "tôi đã sửa / kiểm chứng gì" mô hình không được tự điền, vì chỉ tôi biết việc đó. AI chỉ đáng giá nếu nhanh hơn thói quen ghi log trong lúc làm |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
1. Mở lại lịch sử chat trong buổi lab (2p)
2. Cuộn lại, tìm từng lần hỏi AI (10p) <- BOTTLENECK
3. Ghi phần nào, hỏi gì, AI trả lời gì (5p)
4. Nhớ lại đã sửa hoặc kiểm chứng gì
5. Điền vào bảng AI log (5p)
```

### Card muốn pitch nhất

- Card số: 2
- Vì sao: Ảnh hường trực tiếp đến điểm đạt được trong quá trình học tập và xét tuyển
- Câu hỏi muốn nhóm phản biện: Nếu AI làm bước gom và định dạng còn mình tự chọn ý chính, thì "bản tổng hợp đủ tốt" nên đo bằng cách nào mà không tốn gần bằng tự làm?

### AI đã phản biện card thế nào
| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| 1. Job Story gộp hai việc: chuẩn bị trước buổi học và ôn tập sau buổi học (đầu vào khác nhau, trước buổi học có thể chưa có tài liệu) | Đồng ý | Chọn một thời điểm cho card này (nên là sau buổi học vì tài liệu đã đủ); thời điểm còn lại tách card khác hoặc bỏ |
| 2. Bước 3 (chọn ý chính bằng lời mình) chính là phần học; giao cho AI thì tiết kiệm thời gian nhưng có thể học kém đi | Đồng ý | AI chỉ làm bản nháp kèm số slide để đối chiếu, tôi là người chọn và chỉnh ý chính |
| 3. Success metric chưa ổn: "tự kiểm tra cuối tuần" quá nhiễu (và quy trình đã bỏ bước đó); target ≤10p chưa tính thời gian review bản AI | Đồng ý | Bỏ chỉ số tự kiểm tra; giữ độ phủ ý chính và số ý sai trên 3 buổi cũ (lấy Mục tiêu/Key takeaways của slide làm đáp án chuẩn); cộng thời gian review vào target |
| 4. Chưa thử template (phương án không dùng AI) nên chưa biết AI thêm được bao nhiêu; "Cảm nhận nhanh: LLM feature" nghe như đã quyết định | Đồng ý | Dùng template 3 ngày, bấm giờ; đổi "Cảm nhận nhanh" thành "Chưa biết / Not Yet", nghiêng Rule nếu template đã xuống dưới ~15p |
---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
- Chung môi trường thì chung problem
- Không phải problem nào cũng cần AI can thiệp
- Problem có thể là những điều nhỏ nhưng khó chịu
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
- Có. Khi đó nhóm cần nhìn lại giải pháp có liên quan đến vấn đề hiện tại không? Nếu không sẽ phải rollback lại bối cảnh và xem xét rõ ràng vấn đề đó, từ đó nhận ra pain point, workflow, cost, xem xét tính khả thi. Nếu có liên quan thì sẽ từ đó reverse ngược lại để vấn đề và giải pháp gặp nhau tại 1 điểm
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
- Có đổi ý.
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
- Phải xác nhận đấy có đúng là problem không hay chỉ là phenomena
**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
- Chưa biết
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Problem: [Ai] đang gặp [bottleneck nào] trong [workflow nào], gây [tổn thất gì, bao nhiêu].
Quy trình: Hiện tại họ làm qua các bước [A → B → C], trong đó bước [?] tốn nhất vì [lý do].
Metric: Nhóm đo thành công bằng [metric chính], từ [baseline] xuống/lên [target], và đối chiếu bằng [cách đo/đáp án chuẩn].
Boundary: Hệ thống được phép [làm gì], không được [làm gì], và [người nào] xác nhận ở bước [nào].
Mức can thiệp AI: Trước hết thử [rule/template/cách đơn giản]; AI chỉ vào khi [điều kiện], và chỉ làm phần [cụ thể], còn phần [phần học/phán đoán] là của người.
Quyết định: Nhóm chọn [Go / Not Yet / No-Go] vì [căn cứ], và thí nghiệm nhỏ nhất tiếp theo là [việc gì, đo trong bao lâu].
---

## 7. Tài liệu tham khảo

-
