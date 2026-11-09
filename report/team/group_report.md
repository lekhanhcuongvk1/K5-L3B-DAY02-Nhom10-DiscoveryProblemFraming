# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm. Khi chốt bản cuối, **mỗi thành viên copy file này vào repo cá nhân**.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm 10
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Nhân viên văn phòng đặt cơm trưa qua app mất 30–60 phút mỗi lần để biết quán quen nào rẻ nhất sau voucher, vì voucher chỉ áp được sau khi đã chọn món và có tổng tiền.
- Quyết định cuối: Go (phạm vi nhỏ)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Nguyễn Hoàng Ân | Khi đặt đồ ăn, tôi muốn biết quán nào có tổng tiền thấp nhất sau voucher, để đặt nhanh mà không phải thử nhiều quán và voucher | Khách đặt đồ ăn quan tâm đến giá | Lặp lại chọn món + thử voucher ở từng quán (~5'/quán × 5 quán) | "Voucher chỉ áp được khi đã có tổng tiền giỏ hàng, nếu khách chưa chọn món thì làm sao hiển thị giá sau voucher ngay từ đầu?" (Trần Bảo Long) |
| 2 | Nguyễn Hoàng Ân | Khi có nhiều bài tập và mốc dự án AI20K cùng lúc, tôi muốn biết việc nào đến hạn và cần làm trước, để nộp đúng hạn | Học viên AI20K | Ước lượng thời gian và xếp lịch (10–20'/ngày) |  |
| 3 | Nguyễn Hoàng Ân | Khi xem kết quả bài luyện trước kỳ thi, học viên muốn biết phần nào cần ưu tiên ôn, để tập trung cải thiện phần yếu | Học viên luyện thi online | Chờ giáo viên hướng dẫn (15–20') |  |
| 4 | Lê Khánh Cường | Khi dự hội thảo Google Meet có diễn giả nói tiếng Anh, tôi muốn hiểu nội dung ngay trong buổi, để không bỏ lỡ kiến thức quan trọng | Sinh viên nghe hiểu tiếng Anh hạn chế | Nghe hiểu tiếng Anh theo thời gian thực (chưa đo số phút) | |
| 5 | Lê Khánh Cường | Khi nhận bài tập và deadline từ nhiều môn qua nhiều kênh, tôi muốn nắm đủ các bài cần làm và hạn nộp, để không bỏ sót | Sinh viên học nhiều học phần | Mở lại và đối chiếu thông báo ở 3 kênh (chưa đo số phút) |  |
| 6 | Lê Khánh Cường | Khi muốn ăn một món mà chưa biết quán nào gần mình phù hợp, tôi muốn tìm quán hợp khẩu vị, ngân sách, khoảng cách, để không phân vân lâu | Sinh viên, người hay ăn ngoài | Xem thông tin và đọc đánh giá từng quán (~35'/lần chọn) |  |
| 7 | Trần Bảo Long | Khi yêu cầu công việc rải rác trên Gmail, Zalo, Slack, Messenger, tôi muốn gom các đầu việc kèm deadline vào một danh sách, để không bỏ sót nhiệm vụ | Sinh viên vừa học vừa làm, nhân viên văn phòng trẻ | Đọc, lọc yêu cầu và chép lại to-do (25–35'/ngày) |  |
| 8 | Trần Bảo Long | Khi tuyển bác sĩ/điều dưỡng, HR muốn đối chiếu nhanh chứng chỉ hành nghề và kinh nghiệm với tiêu chuẩn, để lọc ứng viên đạt chuẩn | HR bệnh viện / phòng khám | Đọc bản scan CCHN và tra cứu cổng Bộ Y tế (15–20'/hồ sơ) |  |
| 9 | Trần Bảo Long | Khi xử lý nghi vấn sau ca thi, cán bộ khảo thí muốn định vị mốc thời gian có hành vi bất thường trên video camera, để lấy bằng chứng mà không tua lại cả buổi | Giám thị, cán bộ khảo thí | Tua lại 90' video để tìm đoạn nghi vấn (45–60'/phòng) | Quyền riêng tư dữ liệu hình ảnh, kinh phí lắp camera, không có dữ liệu phòng thi thật để kiểm chứng trong buổi lab (Nguyễn Văn Lên) |
| 10 | Nguyễn Văn Lên | Khi chuẩn bị nộp bài lab trước deadline, tôi muốn đối chiếu bài làm với rubric và đề bài, để không bị trừ điểm vì thiếu tiêu chí hoặc sai format | Sinh viên làm lab/assignment có rubric | Đối chiếu thủ công từng tiêu chí rubric với bài làm (22–25'/bài) | "Nếu sinh viên nộp ảnh chụp hoặc scan bài viết tay thì hệ thống đọc và chấm đúng rubric thế nào?" (Nguyễn Hoàng Ân) |
| 11 | Nguyễn Văn Lên | Khi sắp đến buổi họp sync tối Chủ nhật, tôi muốn tổng hợp trạng thái và khó khăn của từng bạn, để kịp điều chỉnh kế hoạch | Nhóm trưởng / người quản lý tiến độ | Kiểm tra chéo tin nhắn với Drive/GitHub (~15'), tổng cộng ~55'/tuần | "Chỉ cần một Google Form chuẩn hóa điền trước 18h (No AI) đã giải được 80% vấn đề chưa?" (Trần Bảo Long) |
| 12 | Nguyễn Văn Lên | Khi nhận task mới trong dự án phần mềm, tôi muốn nắm đủ context và quyết định kỹ thuật từ issue, PR, chat cũ, để code đúng ngay lần đầu | Intern / lập trình viên mới | Lội thread chat tìm quyết định cũ (~15'), tổng cộng ~75'/task | "Dữ liệu task và chat nội bộ có tính bảo mật cao, cấp quyền cho AI đọc thế nào để không lộ dữ liệu?" (Lê Khánh Cường) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | #2 Deadline AI20K, #5 Deadline nhiều môn, #7 Gom task đa kênh, #11 Tiến độ project nhóm | Việc cần làm và deadline nằm rải rác ở nhiều kênh, phải tự gom lại mới biết hôm nay làm gì |
| B | #1 So giá sau voucher, #6 Chọn quán ăn gần mình | Phải mở và thử từng lựa chọn mới biết lựa chọn nào tốt nhất (giá, khẩu vị, khoảng cách) |
| C | #8 Sàng lọc hồ sơ y tế, #10 Kiểm tra bài theo rubric, #12 Hiểu context task | Phải đọc nhiều tài liệu và đối chiếu thủ công với một bộ tiêu chí hoặc câu hỏi cụ thể |
| D | #3 Học viên chưa biết phần cần ôn, #9 Gắn cờ video phòng thi | Dữ liệu đã có sẵn (kết quả bài làm, video) nhưng phải xem thủ công từng phần mới tìm ra điểm cần chú ý |
| E | #4 Hội thảo tiếng Anh | Nội dung trình bày ở dạng người nghe khó tiếp nhận kịp (ngoại ngữ, thời gian thực) |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm số phút người dùng phải tự gom, đọc và so sánh thông tin trước khi ra một quyết định lặp lại hằng ngày
├── Opportunity A: Việc cần làm và deadline rải rác nhiều kênh, phải tự gom mới biết hôm nay làm gì
├── Opportunity B: Phải mở và thử từng lựa chọn mới biết lựa chọn nào rẻ hoặc hợp nhất   ← nhóm chọn đào sâu
│    ├── B1: Giá sau voucher chỉ biết được khi đã chọn món và có tổng tiền
│    ├── B2: Lựa chọn lặp lại giữa vài quán quen, món quen nhưng mỗi ngày vẫn phải so lại từ đầu
│    └── B3: Voucher đổi theo ngày nên lựa chọn rẻ nhất hôm qua chưa chắc rẻ nhất hôm nay
├── Opportunity C: Phải đọc nhiều tài liệu và đối chiếu thủ công với bộ tiêu chí
├── Opportunity D: Dữ liệu có sẵn nhưng phải xem thủ công từng phần mới thấy điểm cần chú ý
└── Opportunity E: Nội dung bằng ngoại ngữ khó theo kịp trong thời gian thực
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "Danh sách gợi ý quán + món + giá sau voucher", "Agent tự đặt cơm trưa mỗi ngày", "Chatbot gợi ý món" (nhánh B)
- "Công cụ AI tự gom task từ Gmail/Zalo vào to-do" (nhánh A)
- "LLM tự chấm bài theo rubric" (nhánh C)
- "Camera AI phát hiện gian lận", "AI tự quyết định đình chỉ thi" (nhánh D)
- "Phụ đề dịch tiếng Việt thời gian thực" (nhánh E)

### 2.4. Chấm điểm shortlist (1–5)

Shortlist gồm 3 card được pitch chính: #1 (Ân), #9 (Long), #10 (Lên).

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 So giá sau voucher (cơm trưa) | 5 | 5 | 3 | 4 | 5 | 5 | 4 | **31** |
| #10 Kiểm tra bài nộp theo rubric | 5 | 5 | 4 | 4 | 4 | 4 | 5 | **31** |
| #9 Gắn cờ hành vi bất thường trên video phòng thi | 5 | 4 | 2 | 4 | 1 | 3 | 2 | **21** |

**Candidate được chọn:** #1 So giá sau voucher, thu hẹp thành bài toán nhân viên văn phòng đặt cơm trưa.

**Vì sao chọn:** Đồng điểm cao nhất với #10. Nhóm chọn #1 vì: (1) mang tính thực tế trong doanh nghiệp (nhân viên product đề xuất tính năng cho một sản phẩm có sẵn dữ liệu); (2) dễ tiếp cận người dùng thật là nhân viên văn phòng quanh nhóm, và có app thật để kiểm tra tính năng hiện có; (3) bước nghẽn giải được bằng phép tính xác định trên dữ liệu app đã có, nên so sánh rõ được Rule với Workflow và Agent.

**Vì sao loại các candidate còn lại:**

- #9 Video phòng thi: rào cản quyền riêng tư dữ liệu hình ảnh và kinh phí lắp camera; nhóm không có dữ liệu phòng thi thật để kiểm chứng trong buổi lab (điểm "Vừa sức lab" = 1, "Pain có bằng chứng" = 2). Đưa vào hướng phát triển dài hạn.
- #10 Kiểm tra bài theo rubric: bước nghẽn là đối chiếu ngữ nghĩa giữa bài làm và tiêu chí, cần AI phán đoán "đạt / chưa đạt" nên khó định nghĩa tiêu chí đánh giá rõ ràng trong thời gian lab; bài nộp dạng ảnh chụp/scan làm phạm vi phình to (điểm "Vừa sức lab" và "So sánh 4 mức" = 4).
- Các candidate ngoài shortlist (#2–#8, #11, #12) có actor hoặc bằng chứng yếu hơn, hoặc trùng pattern với cluster A đã có nhiều giải pháp sẵn (lịch, checklist, Google Form).

**Xử lý bất đồng (nếu có):** Trần Bảo Long ban đầu đề xuất #9 vì giá trị xã hội cao. Sau khi nhóm phản biện về quyền riêng tư, chi phí và khả năng kiểm chứng trong buổi lab, Long đồng thuận đưa #9 vào hướng phát triển dài hạn; nhóm thống nhất chọn #1.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Phần lớn đơn cơm trưa của nhân viên văn phòng lặp lại giữa vài quán quen và món quen | Value | 5 | 2 | ✅ |
| 2 | Khách áp thử voucher ở nhiều quán trước khi đặt, và đây là bước tốn thời gian nhất | Value | 5 | 2 | ✅ |
| 3 | Khách chấp nhận chọn từ danh sách gợi ý thay vì tự lướt | Usability | 4 | 1 | ✅ |
| 4 | Giá và voucher tính trước cho giỏ quen vẫn đúng ở bước thanh toán | Feasibility | 5 | 3 | — |
| 5 | Quán đối tác chấp nhận việc app so giá cuối giữa các quán | Viability | 3 | 1 | Sau lab |

Giả định nhóm kiểm chứng trong buổi này: chưa kiểm chứng trực tiếp với người dùng. Nhóm ưu tiên #1, #2, #3 và đã thiết kế cách kiểm chứng ở mục 3.2; trong buổi chỉ thực hiện research giải pháp đã có (mục 3.3).

### 3.2. Kiểm chứng

Cách đã dùng: Research tính năng của các app giao đồ ăn hiện có (đã làm). Phỏng vấn + survey người dùng: **đã thiết kế, chưa thực hiện** do giới hạn thời gian. Dưới đây là kế hoạch kiểm chứng nhóm dự kiến chạy trước pilot.

**Trạng thái:** Chưa có dữ liệu phỏng vấn. Mọi bảng kết quả bên dưới để trống, nhóm không điền số giả định vào phần này.

#### Kế hoạch kiểm chứng

**Mục tiêu:** kiểm 3 giả định "quan trọng cao, bằng chứng thấp" ở mục 3.1:

| Giả định | Câu hỏi cần trả lời | Bằng chứng mạnh nhất có thể lấy |
|---|---|---|
| #1 Đơn trưa lặp lại giữa vài quán quen, món quen | Trong 2 tuần gần nhất, bao nhiêu % đơn trưa rơi vào ≤ 5 quán? | Lịch sử đơn trên app của người được hỏi (họ tự mở, tự đếm) |
| #2 Áp thử voucher ở nhiều quán là bước tốn thời gian nhất | Lần đặt gần nhất: xem mấy quán, áp thử voucher mấy lần, mất bao lâu? | Người được hỏi kể lại từng bước của lần đặt gần nhất |
| #3 Khách chấp nhận chọn từ danh sách có sẵn | Hiện họ có dùng "Đặt lại" / "Quán yêu thích" không, bao lâu một lần? | Hành vi đang dùng các danh sách có sẵn của app |

**Đối tượng:** nhân viên văn phòng đặt cơm trưa qua app ít nhất 2 lần/tuần trong tháng gần nhất. Lấy từ ít nhất 2 công ty khác nhau. Không phỏng vấn thành viên nhóm, không phỏng vấn người đang làm cho công ty app giao đồ ăn.

**Cỡ mẫu và hình thức:**

- Phỏng vấn 1–1: 5 người, mỗi buổi 15 phút, trực tiếp hoặc gọi video, ưu tiên ngay sau giờ trưa khi lần đặt gần nhất còn nhớ rõ.
- Survey (Google Forms): 20 người, gửi qua nhóm chat công ty/bạn bè, để kiểm giả định #1 ở quy mô lớn hơn.

**Phân vai:** một người hỏi, một người ghi chép. Người đề xuất candidate không dẫn phỏng vấn, để tránh hỏi dẫn dắt xác nhận điều mình tin.

**Dự đoán trước khi phỏng vấn (để biết kết quả nào là xác nhận, kết quả nào là phản bác):**

| Giả định | Xác nhận nếu | Phản bác nếu | Nếu bị phản bác, nhóm sẽ |
|---|---|---|---|
| #1 | ≥ 3/5 người phỏng vấn và ≥ 60% người survey có ≥ 60% đơn trưa 2 tuần qua rơi vào ≤ 5 quán | Đa số đổi quán liên tục, ít khi quay lại quán cũ | Bỏ hướng "giỏ quen"; quay lại CP3 hoặc chuyển sang No-Go |
| #2 | ≥ 3/5 người kể lần gần nhất đã áp thử voucher ở ≥ 2 quán và mất ≥ 10 phút | Đa số đặt ngay quán đầu tiên hoặc bấm "Đặt lại" | Bottleneck sai; vẽ lại quy trình ở CP5 |
| #3 | ≥ 3/5 người dùng "Đặt lại" hoặc "Quán yêu thích" ít nhất 1 lần/tuần | Đa số không dùng các danh sách có sẵn | Giữ Rule nhưng thiết kế lại cách hiển thị (ví dụ thông báo thay vì danh sách) |

#### Kịch bản phỏng vấn (theo The Mom Test)

**Mở đầu (1 phút):** "Nhóm mình đang tìm hiểu thói quen đặt cơm trưa của dân văn phòng. Không có đúng sai, mình chỉ muốn nghe bạn kể lại những lần đặt gần đây." Không giới thiệu ý tưởng danh sách gợi ý.

**Phần chính (10 phút):**

1. Tuần này bạn đặt cơm trưa qua app mấy lần? Ở những quán nào?
2. Kể lại lần đặt gần nhất từ lúc mở app đến lúc bấm đặt. Bạn làm những bước nào?
3. Lần đó bạn xem mấy quán, áp thử voucher mấy lần? Mất khoảng bao lâu?
4. Có lần nào đặt xong mới thấy quán khác rẻ hơn không? Gần nhất là khi nào?
5. Bạn đang làm gì để đặt nhanh hơn? (Đặt lại, quán yêu thích, đặt chung với đồng nghiệp…)
6. Bạn có thể mở lịch sử đơn 2 tuần gần nhất để mình cùng đếm số quán khác nhau không?

**Câu hỏi đào sâu khi cần:** "Lúc đó bạn làm gì tiếp?", "Vì sao bạn chọn quán đó?", "Bước nào làm bạn thấy mất thời gian nhất?"

**Câu không được hỏi:** "Bạn có muốn app gợi ý quán rẻ không?", "Nếu có tính năng X bạn có dùng không?", "Ý tưởng này hay không?". Đây là câu hỏi giả định về tương lai, chỉ nhận được lời khen.

**Kết thúc (1 phút):** cảm ơn; hỏi có đồng nghiệp nào hay đặt cơm trưa để giới thiệu thêm không. Lời giới thiệu là một cam kết hành động, mạnh hơn lời khen.

#### Form survey (Google Forms, 6 câu)

1. Trong 2 tuần gần nhất, bạn đặt cơm trưa qua app bao nhiêu lần? (0 / 1–3 / 4–6 / 7–10 / trên 10)
2. Mở lịch sử đơn: số đơn trưa đó đến từ bao nhiêu quán khác nhau? (nhập số)
3. Lần đặt gần nhất, bạn xem bao nhiêu quán trước khi đặt? (1 / 2–3 / 4–5 / trên 5)
4. Lần đặt gần nhất, bạn mất khoảng bao lâu từ lúc mở app đến lúc đặt? (dưới 5 phút / 5–10 / 10–20 / 20–40 / trên 40)
5. Bạn có dùng "Đặt lại" hoặc "Quán yêu thích" không? (Chưa bao giờ / Thỉnh thoảng / Hằng tuần / Gần như mỗi lần)
6. Bước nào làm bạn mất thời gian nhất? (Chọn quán / Chọn món / Tìm và áp voucher / So sánh giá giữa các quán / Khác: …)

#### Quy tắc ghi chép và bảo mật

- Ghi người được hỏi theo vai trò, ví dụ "Nhân viên kế toán, công ty 100 người"; không ghi họ tên, số điện thoại, email.
- Mỗi buổi ghi ngay thành một Interview Snapshot, lưu tại `report/assets/cp4-interview-snapshot-N.md`.
- Ảnh chụp lịch sử đơn (nếu có) phải che tên, địa chỉ, số điện thoại trước khi đưa vào repo.

#### Mẫu Interview Snapshot

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Research tính năng app | 2 tính năng | Chưa có chỗ nào cho khách thấy giá cuối của nhiều giỏ quen cùng lúc | "Đặt lại" đơn cũ đã giải phần lớn pain cho khách chỉ ăn một quán quen duy nhất |
| Phỏng vấn 1–1 | Chưa thực hiện (kế hoạch: 5) | | |
| Survey | Chưa thực hiện (kế hoạch: 20) | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** (các thay đổi dưới đây đến từ research và thảo luận nhóm, chưa đến từ phỏng vấn người dùng)

- Thu hẹp actor từ "khách đặt đồ ăn nói chung" thành "nhân viên văn phòng đặt cơm trưa", nhóm có hành vi lặp lại rõ nhất.
- Bỏ hướng ban đầu "hiển thị giá sau voucher trên thẻ quán" vì voucher phụ thuộc vào giỏ hàng: chưa chọn món thì chưa tính được giá cuối. Chuyển sang dùng lịch sử đặt hàng để biết trước "giỏ quen" rồi mới tính giá. Thay đổi này bắt nguồn từ câu phản biện của Trần Bảo Long khi pitch ở CP3 (mục 2.1).

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| "Đặt lại" đơn cũ trên app giao đồ ăn | [Ảnh chụp màn hình app](../assets/cp4-research-1.png) | Chọn quán + chọn món | Một chạm là có lại giỏ cũ | Chỉ một đơn, không so giá giữa các quán, không cho biết voucher hôm nay | Lịch sử đơn đã được dùng; còn thiếu bước so giá |
| "Quán yêu thích" / "Đã đặt gần đây" | [Ảnh chụp màn hình app](../assets/cp4-research-2.png) | Lướt chọn quán | Tìm quán quen nhanh | Không kèm món, không kèm giá cuối | Ghép "quán quen + món quen + giá sau voucher" là khoảng trống |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — khoảng 30 phút/lần khi so 5 quán, có lúc tới 60 phút; 5 lần/tuần

[Mở quán quen: 1'] → [Chọn món quen: 2'] → [Áp thử voucher: 2']
        ↑                                              │
        └──── lặp lại cho khoảng 5 quán (≈25') ────────┘ ← BOTTLENECK
→ [So sánh, đặt đơn: 5']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Khách | Danh sách quán quen | Menu một quán | 1 phút/quán | |
| 2 | Khách | Menu | Giỏ hàng | 2 phút/quán | Thường chọn lại món quen |
| 3 | Khách | Giỏ hàng, danh sách voucher quán + app | Tổng tiền sau ưu đãi | 2 phút/quán | |
| 4 | Khách | Tổng tiền từng quán | So sánh trong đầu | Lặp bước 1–3 cho khoảng 5 quán, khoảng 25 phút | **Bottleneck** |
| 5 | Khách | Các tổng tiền | Đơn hàng | 5 phút | 5 lần/tuần (ngày làm việc) |

**Bottleneck chính:** Bước 4, lặp lại chọn món + áp thử voucher ở từng quán (~5 phút/quán × 5 quán ≈ 25 phút). Nguyên nhân gốc: voucher chỉ áp được khi đã có giỏ hàng, nên muốn biết giá cuối của quán nào cũng phải làm lại cả giỏ ở quán đó.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — mục tiêu ≤ 5 phút/lần đặt

1. [RULE]       Lấy top 5 cặp quán + món khách đặt nhiều nhất trong 30 ngày (lịch sử của chính khách)
2. [RULE]       Tính giá sau voucher tốt nhất cho từng giỏ quen với voucher còn hiệu lực hôm nay
3. [HỆ THỐNG]   Hiển thị danh sách "Gợi ý trưa nay": quán – món – giá sau voucher, sắp xếp theo giá (10h–13h)
4. [CON NGƯỜI]  Khách chọn một dòng, vào giỏ, kiểm tra tổng tiền, có thể sửa món
5. [CON NGƯỜI]  Khách bấm đặt đơn

Mở rộng sau (Workflow): [AI] gợi ý thêm 1–2 quán tương tự có giá sau voucher bằng hoặc rẻ hơn giỏ quen,
                         chèn vào danh sách ở bước 3; bước 4–5 giữ nguyên.

BOUNDARY:  Hệ thống không tự đặt đơn. Chỉ dùng lịch sử của chính khách.
           Giá trong danh sách phải khớp giá thanh toán. Không ẩn các lựa chọn ngoài danh sách.

QUAY VỀ:   Voucher hết hạn hoặc giá đổi → tính lại; không tính được thì ẩn dòng đó.
           Khách luôn có thể bỏ qua danh sách và đặt như cũ.
           Tỉ lệ lệch giá > 5% đơn → tắt tính năng bằng feature flag.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 (lặp bước 1–3 × 5 quán) | 3 bước phía khách | Rule làm bước lấy giỏ quen và tính giá |
| Tổng thời gian | 30–60 phút | ≤ 5 phút | Đo bằng thời gian từ lúc mở app đến lúc đặt đơn |
| Số bước thủ công | 5 | 2 | Chọn dòng; kiểm tra và đặt |
| Bottleneck chính | Lặp lại chọn món + áp voucher ở từng quán | Không còn | Rule tính sẵn giá sau voucher cho các giỏ quen |
| Rủi ro mới phát sinh | — | Giá lệch giá thanh toán; khách mới chưa có lịch sử; khách ít thử quán mới | Xử lý ở boundary và phương án quay về |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Nhân viên văn phòng đặt cơm trưa qua app, thường lặp lại giữa vài quán quen và món quen |
| **Quy trình** | Mở quán quen → chọn món → áp thử voucher → lặp lại ở khoảng 5 quán → so sánh → đặt |
| **Bottleneck** | Lặp lại chọn món + áp thử voucher ở từng quán (~5 phút/quán × 5 quán ≈ 25 phút), vì voucher chỉ áp được khi đã có giỏ hàng |
| **Impact** | 30–60 phút/lần, 5 lần/tuần, mất phần lớn giờ nghỉ trưa; đôi khi vẫn không chọn được lựa chọn rẻ nhất |
| **Success Metric** (baseline → target, cách đo) | Thời gian từ lúc mở app đến lúc đặt đơn trưa: 30–60 phút → ≤ 5 phút; đo bằng analytics của app trong A/B test 2 tuần |
| **Boundary** (AI không được làm gì) | Hệ thống không tự đặt đơn, không dùng lịch sử của người khác, không hiển thị giá khác giá thanh toán |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- Metric chỉ đo tốc độ, không đo khách có thật sự dùng danh sách hay không. **Đồng ý** → thêm metric tỉ lệ đơn đặt từ danh sách ở v1.
- Giá tính sẵn có thể lệch giá ở bước thanh toán, làm khách mất lòng tin. **Đồng ý** → thêm metric độ khớp giá và phương án quay về.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Độ mơ hồ thấp × Độ phức tạp trung bình**

Vì sao: Lựa chọn của khách lặp lại nên giỏ quen xác định được bằng cách đếm tần suất; giá sau voucher là phép tính có đáp án đúng duy nhất. Độ phức tạp nằm ở số lượng quán × voucher có điều kiện và việc cập nhật theo ngày, không nằm ở việc cần phán đoán.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Khách tự lưu quán quen, dùng "Đặt lại" | Khách chỉ ăn một quán quen | Vẫn phải áp thử voucher từng quán khi so nhiều quán | Không |
| **Rule** | Lấy top 5 giỏ quen theo tần suất 30 ngày + tính giá sau voucher tốt nhất + sắp xếp theo giá | Khách có hành vi đặt lặp lại | Logic tổ hợp voucher phải xây mới (app chưa có); giá lệch giá thanh toán; khách mới chưa có lịch sử | **Chọn** |
| **Workflow** | Rule + AI gợi ý quán tương tự có giá sau voucher bằng hoặc rẻ hơn giỏ quen | Khách muốn đổi vị; danh sách Rule ít được chọn | Gợi ý không hợp khẩu vị | Hướng mở rộng |
| **Agent** | AI tự chọn và đặt cơm trưa mỗi ngày | Không cần cho bài này | Khách mất quyền kiểm soát; đặt sai món, sai giá | Không |

**Mức chọn:** Rule, với hướng mở rộng lên Workflow.

**Vì sao không chọn mức đơn giản hơn:** No AI không xóa được vòng lặp áp voucher. Khách không thể tự tính giá cuối cho nhiều giỏ cùng lúc, trong khi app đã có sẵn lịch sử đơn, giá món và dữ liệu voucher. Chọn tổ hợp voucher tốt nhất cho một giỏ đã biết là phép tính xác định nên làm được bằng Rule.

### 6.3. AI Canvas rút gọn

Áp dụng cho phần mở rộng Workflow (gợi ý quán tương tự); phần Rule không cần AI.

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | 1–2 quán tương tự giỏ quen (món giống hoặc cùng loại) có giá sau voucher bằng hoặc rẻ hơn |
| **Judgment** — con người cân nhắc, quyết định gì? | Khách quyết định có thử quán mới hay giữ giỏ quen |
| **Action** — hành động cuối cùng là gì, ai làm? | Khách chọn một dòng và tự bấm đặt đơn |
| **Outcome** — đo kết quả bằng gì? | Tỉ lệ khách chọn gợi ý tương tự; đánh giá sau bữa ăn; thời gian đặt đơn |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Lịch sử đơn của khách, menu và mô tả món, giá, voucher còn hiệu lực, khu vực giao. Có sẵn trong hệ thống app |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Khách chọn hay bỏ qua gợi ý; đánh giá sao sau bữa; tỉ lệ đặt lại quán được gợi ý |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: **Augment.** Hiện khách tự so và tự chọn; ngay cả với "Đặt lại", khách vẫn tự bấm. Khách cần thấy sẵn các lựa chọn kèm giá cuối, không cần app quyết định thay.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: **Báo nhầm tệ hơn.** Hiển thị giá thấp hơn giá thanh toán làm khách mất lòng tin vào cả tính năng; bỏ sót một lựa chọn chỉ khiến khách tự tìm như hiện tại. Thiết kế tính lại giá ngay trước khi hiển thị, ẩn dòng nếu không tính được, và tắt tính năng khi tỉ lệ lệch giá vượt 5%.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Nhân viên văn phòng đặt cơm trưa qua app, có từ 4 đơn trưa/tháng trở lên |
| **Quy trình** | Mở quán quen → chọn món → áp thử voucher → lặp lại ở khoảng 5 quán → so sánh → đặt |
| **Bottleneck** | Lặp lại chọn món + áp thử voucher ở từng quán (~5 phút/quán × 5 quán ≈ 25 phút), vì voucher chỉ áp được khi đã có giỏ hàng |
| **Impact** | 30–60 phút/lần, 5 lần/tuần, mất phần lớn giờ nghỉ trưa |
| **Success Metric** (baseline → target, cách đo) | (1) Thời gian đặt đơn trưa 30–60 phút → ≤ 5 phút; (2) ≥ 30% đơn trưa đặt từ danh sách gợi ý; (3) giá trong danh sách khớp giá thanh toán ở ≥ 99,5% đơn. Đo bằng analytics trong A/B test 2 tuần |
| **Boundary** | Không tự đặt đơn; chỉ dùng lịch sử của chính khách; không hiển thị giá khác giá thanh toán; không ẩn lựa chọn ngoài danh sách |
| **AI intervention point** | Bước chọn quán + chọn món + áp voucher (Rule); bước gợi ý quán tương tự (Workflow, mở rộng sau) |
| **Mức chọn** | Rule (mở rộng: Workflow) |
| **Rủi ro & người kiểm tra** | Giá lệch giá thanh toán → khách kiểm tra tổng tiền trước khi đặt, team vận hành theo dõi tỉ lệ lệch giá hằng ngày; khách mới chưa có lịch sử → không hiển thị danh sách |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor | Nhân viên văn phòng đặt cơm trưa | Thêm điều kiện ≥ 4 đơn trưa/tháng | Rule cần đủ lịch sử để xác định giỏ quen |
| Success Metric | Chỉ đo thời gian đặt đơn | Thêm tỉ lệ đặt từ danh sách và độ khớp giá | Phản biện: metric v0 chỉ đo tốc độ; PAIR cho thấy báo nhầm giá là lỗi tệ nhất |
| AI intervention point, Mức chọn | Chưa có | Rule, mở rộng Workflow | Kết quả so sánh 4 mức ở mục 6 |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Giá khớp thanh toán | Giá trong danh sách bằng đúng giá ở bước thanh toán | Chênh lệch bất kỳ |
| 2 | Đúng voucher tốt nhất | Tổng tiền là mức thấp nhất trong các tổ hợp voucher hợp lệ | Có tổ hợp hợp lệ rẻ hơn |
| 3 | Đúng giỏ quen | Mỗi dòng là quán + món khách đã đặt ≥ 2 lần trong 30 ngày | Có món khách chưa từng đặt (ngoài phần gợi ý tương tự) |
| 4 | Còn bán | Món còn bán và quán đang mở tại thời điểm hiển thị | Món hết hoặc quán đã đóng |
| 5 | Gợi ý tương tự hợp lệ (Workflow) | Giá sau voucher ≤ giỏ quen và cùng loại món | Đắt hơn giỏ quen hoặc khác hẳn loại món |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | TB | Dựa trên trải nghiệm của thành viên nhóm và research; chưa phỏng vấn người dùng ngoài nhóm |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | Khách chỉ chọn một dòng, vẫn kiểm tra và sửa được giỏ trước khi đặt |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | TB | Lịch sử đơn, giá món và dữ liệu voucher đã có trong app, nhưng app chưa có logic tự chọn voucher tốt nhất; phải xây mới logic tính tổ hợp voucher hợp lệ (đơn tối thiểu, khung giờ, khu vực, voucher quán + app). Khối lượng tính nhỏ vì chỉ khoảng 5 giỏ/khách |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | TB | Quán có thể phản đối bị so giá; voucher được dùng hiệu quả hơn có thể làm tăng chi phí khuyến mãi; team product vận hành |

### 8.2. Kết luận

**Quyết định:** Go (phạm vi nhỏ)

**Lý do:** Không có rủi ro mức Cao. Usability thấp vì khách chỉ chọn một dòng. Ba rủi ro TB đều kiểm được ngay trong pilot: Value qua tỉ lệ đơn đặt từ danh sách, Feasibility qua tỉ lệ lệch giá giữa danh sách và thanh toán, Viability qua phản hồi của quán và chi phí voucher.

**Nếu Go — pilot nhỏ nhất:** Bật danh sách "Gợi ý trưa nay" trong khung 10h–13h cho 5% khách có từ 4 đơn trưa/tháng trở lên, chạy 2 tuần, so với nhóm đối chứng. Trước pilot, phỏng vấn 5 nhân viên văn phòng để kiểm chứng giả định #1–#3.

**Nếu Not Yet — cần kiểm chứng gì trước:** Không áp dụng.

**Nếu No-Go — nên làm gì thay AI:** Không áp dụng.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

- Nếu tỉ lệ đơn lệch giá giữa danh sách và thanh toán > 5% → tắt tính năng, sửa logic tính giá.
- Nếu sau 2 tuần < 15% đơn trưa đặt từ danh sách → xem lại cách chọn giỏ quen, cân nhắc lên Workflow.
- Nếu sau 2 tuần thời gian đặt đơn giảm < 10% so với nhóm đối chứng → chuyển sang Not Yet, xem lại bottleneck.

Ngưỡng 5% là mức sàn để dừng pilot; mục tiêu vận hành vẫn là ≥ 99,5% đơn khớp giá (mục 7). Nếu tỉ lệ lệch nằm giữa 0,5% và 5%, nhóm giữ pilot nhưng phải sửa logic tính giá trước khi mở rộng cho nhiều khách hơn.

---

## 9. Hạn chế và hướng tiếp theo

- Chưa phỏng vấn người dùng ngoài nhóm (lược do không đủ thời gian); giả định #1–#3 cần kiểm chứng trước pilot.
- Các con số thời gian và chỉ tiêu là giả định hợp lý trong tình huống đề xuất, chưa có dữ liệu nội bộ của app.
- Khách mới chưa có lịch sử đặt hàng thì chưa có danh sách (cold start).
- Danh sách theo tần suất có thể khiến khách ít thử quán mới; hướng mở rộng Workflow (gợi ý quán tương tự) giúp giảm rủi ro này.

## 10. Tài liệu tham khảo

- Design Council. *Framework for Innovation (Double Diamond)*. https://www.designcouncil.org.uk/resources/framework-for-innovation/
- Torres, T. *Opportunity Solution Trees*. Product Talk. https://www.producttalk.org/opportunity-solution-trees/
- Bland, D. & Osterwalder, A. (2019). *Testing Business Ideas*. Wiley. https://www.strategyzer.com/library/how-assumptions-mapping-can-focus-your-teams-on-running-experiments-that-matter
- Fitzpatrick, R. (2013). *The Mom Test*. https://www.momtestbook.com/
- Google PAIR. *People + AI Guidebook — User Needs*. https://pair.withgoogle.com/chapter/user-needs/
- Anthropic (2024). *Building effective agents*. https://www.anthropic.com/research/building-effective-agents
- Agrawal, A., Gans, J. & Goldfarb, A. (2018). *A Simple Tool to Start Making Decisions with the Help of AI*. Harvard Business Review. https://hbr.org/2018/04/a-simple-tool-to-start-making-decisions-with-the-help-of-ai
- Cagan, M. *The Four Big Risks*. SVPG. https://www.svpg.com/four-big-risks/
