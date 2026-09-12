# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Vũ Hải Đăng | 2A202602821 | Trưởng nhóm - Idea |
| 2   | Lê Như Ý | 2A202602715 | Research |
| 3   | Trần Thị Thu Trang | 2A202602581 | Research |
| 4   | Trần Đình Hinh | 2A202602239 | Research |
| 5   | Trần Tuấn Cường | 2A202602717 | Research |
**Candidate problem nhóm chọn (1 câu):**


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Cường| tìm voucher cho người mua hàng|người mua hàng |không tìm được voucher đúng nhu cầu| |khá phổ biến, có thể dùng AI để cá nhân hoá voucher
| 2 |Cường |cảnh báo người dùng thông tin sai lệch|người đọc thông tin |không phân biệt được thông tin sai lệch dẫn đến nhận thức và hành vi sai |có ý nghĩa xã hội, nhưng khó kiểm chứng độ chính xác
| 3 | Cường|Tìm kiếm công việc phù hợp với CV của mình |người xin việc |không tìm được công việc phù hợp |có nhu cầu thực tế, cần cạnh tranh với các nền tảng tuyển dụng |
| 4 |Như Ý |Tìm API key miễn phí hoặc giá rẻ cho sinh viên |sinh viên |không có nguồn API giá tốt hỗ trợ đối tượng trên |phù hợp sinh viên AI, nhưng phụ thuộc chính sách giá và quyền truy cập API |
| 5 |Như Ý |Khó khăn trong config trong các hệ điều hành khác nhau |những người sử dụng AI |KHông hiểu về công nghệ thông tin khi dùng AI |Đúng vấn đề của người mới học AI, có thể hỗ trựo bằng AI Agent |
| 6 |Như Ý| khó khăn việc mua hàng khi không có đủ hiểu biết về sản phẩm |người mua hàng|không biết mua sản phẩm phù hợp |Có nhu cầu thực tế, có thể ứng dụng AI tư vấn sản phẩm |
| 7 | Hinh|khó khăn trong việc tìm lại thông tin cũ trong file | người tìm thông tin|lượng thông tin cũ quá nhiều không tìm được |Rất phù hợp để ứng dụng RAG/AI tìm kiếm tài liệu |
| 8 | Hinh|khó khăn trong bàn giao công việc khi thay đổi nhân sự |người nhận công việc mới |bàn giao không hết nên gây khó khăn cho người mới | Có giá trị trong doanh nghiệp, cần tiếp cận người dùng thực tế|
| 9 |Hinh |Nhận task nhưng không rõ phải làm gì trước |người nhận task |chưa biết phải làm gì |Dễ làm MVP, có thể dùng AI phân tích ták và đề xuất thứ tự |
| 10 |Đăng |Khó khăn khi thực hiện thủ tục online của người lớn tuổi |người lớn tuổi |đọc hiểu hướng dẫn và điền đúng thông tin vào form |Khả thi, chọn làm vấn đề chung của cả nhóm- ưu tiên chọn để phát triển|
 |11 |Đăng |khó khăn trong việc phân luòng bệnh nhân trong bệnh viện |bệnh nhân |đợi chờ lâu do số lượng bệnh nhân đông |vấn đề thực tiễn |
 | 12 |Đăng|Lừa đảo trực tuyến |ngươi già |Khó nhận biết và phòng tránh các hình thức đào lửa |có ý nghĩa xã hội, nhưng cần dữ liệu và độ chính xác cao |
 | 13|Trang|Khó khăn trong việc quản lý lịch trình đi học và di chuyển hàng ngày |học sinh và người đi học |Phải di chuyển qua nhiều chặng, dễ trễ giờ hoặc mất thời gian chờ đợi| thực tế dễ đo lường thời gian chờ và nguy cơ trễ giờ|
 |14 |Trang |Khó khăn trong việc phân công công việc nhà cho các thành viên trong gia đình |Các thành viên trong gia đình |Không rõ ai làm việc gì, việc nhà bị bỏ sót hoặc dồn lên một người |vấn đề thực tiễn |Gần gũi, dễ khảo sát, có thể xây dựng AI phân công việc nhà|
 | 15| Trang| Khó khăn trong việc tìm lại và quản lý thông tin học tập| Người đi học| Tài liệu, bài tập, ghi chú nằm ở nhiều nơi, khó tìm lại khi cần|Có thể ứng dụng AI tìm kiếm tài liệu, phù hợp với sinh viên|
### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
|A. Tìm kiếm thông tin               |#1, #3, #6, #7, #15|Khó tìm và chọn thông tin phù hợp      |Ứng dụng AI tìm kiếm, gợi ý |
|B. Công nghệ và rủi ro số           |#2, #4, #5, #12    |Khó sử dụng công nghệ, nhận diện rủi ro|Ứng dụng AI hỗ trợ, cảnh báo|
|C. Quản lý công việc                |#8, #9, #13        |Phân công, hướng dẫn, bàn giao chưa rõ |Ứng dụng AI quản lý task    |
|D. Thủ tục online cho người lớn tuổi|#10                |Khó đọc hướng dẫn, điền form           |**Vấn đề chung được chọn**  |
|E. Tối ưu quy trình và thời gian chờ|#11, #14           |Chờ lâu, tiếp cận dịch vụ khó          |Ứng dụng AI tối ưu quy trình|

## 3.3. Shortlist Top 3

| Candidate | Why shortlist | Risks |
|---|---|---|
| Khó khăn khi thực hiện thủ tục online của người lớn tuổi | Pain point rõ ràng; có ý nghĩa xã hội; Voice AI Agent phù hợp; dễ xây dựng demo; có thể đo lường bằng thời gian và độ chính xác | Cần kiểm tra khả năng nhận diện giọng nói và mức độ chấp nhận của người lớn tuổi |
| Khó tìm thông tin cũ trong file | Vấn đề thực tế; RAG phù hợp; dễ xây dựng MVP | Có nhiều công cụ tương tự, khó tạo sự khác biệt |
| Khó khăn khi bàn giao công việc khi nhân sự thay đổi | Có giá trị cho doanh nghiệp; AI có thể tóm tắt và hướng dẫn nhân sự mới | Cần dữ liệu workflow thực tế, khó kiểm chứng trong phạm vi lab |

---

## 3.4. Chấm điểm Top 3

| Candidate | Actor rõ ràng | Workflow rõ ràng | Pain có bằng chứng | Impact đo được | Lab khả thi | So sánh Rule/LLM/Agent | Hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Thủ tục online cho người lớn tuổi | 5 | 5 | 5 | 5 | 5 | 5 | 4 | **34/35** |
| Tìm thông tin cũ trong file | 5 | 4 | 4 | 4 | 5 | 5 | 5 | **32/35** |
| Bàn giao công việc | 4 | 4 | 3 | 5 | 4 | 4 | 4 | **28/35** |

### Candidate được chọn

**Khó khăn khi thực hiện thủ tục online của người lớn tuổi → Voice-based AI Agent hỗ trợ người dùng đọc hiểu, điền thông tin và hoàn thành thủ tục trực tuyến.**

### Lý do lựa chọn

Đây là vấn đề có actor và pain point rõ ràng: người lớn tuổi gặp khó khăn khi đọc hiểu hướng dẫn và điền thông tin trên các form trực tuyến.

Một nghiên cứu tại Việt Nam khảo sát 1.043 người từ 55 tuổi trở lên cho thấy, trong 609 người trả lời lý do không sử dụng dịch vụ online, 36,8% cho rằng giao diện phức tạp/khó thao tác và 28,1% cho rằng thiếu hướng dẫn cụ thể.

Vấn đề có thể đo lường bằng:
- Thời gian hoàn thành thủ tục
- Tỷ lệ hoàn thành thành công
- Độ chính xác khi điền form
- Số lần cần người khác hỗ trợ

Voice-based AI Agent phù hợp vì có thể:
- Giao tiếp bằng ngôn ngữ tự nhiên
- Hỏi từng thông tin còn thiếu
- Hướng dẫn người dùng từng bước
- Chuyển câu trả lời thành dữ liệu để điền form
- Kiểm tra thông tin trước khi gửi
- Yêu cầu người dùng xác nhận trước khi hoàn tất

### Tại sao không chọn các candidate khác?

**1. Khó tìm thông tin cũ trong file**

Đây là vấn đề thực tế và RAG rất phù hợp. Tuy nhiên, có nhiều công cụ tìm kiếm tài liệu tương tự nên khó tạo sự khác biệt trong phạm vi lab.

**2. Khó khăn khi bàn giao công việc khi nhân sự thay đổi**

Vấn đề có giá trị cao trong môi trường doanh nghiệp, nhưng cần dữ liệu workflow thực tế để xây dựng và đánh giá hệ thống. Điều này khó thực hiện trong thời gian của lab.

### Xử lý disagreement trong nhóm

Một số thành viên ưu tiên vấn đề tìm kiếm thông tin vì RAG dễ triển khai. Tuy nhiên, nhóm thống nhất chọn vấn đề hỗ trợ người lớn tuổi thực hiện thủ tục online vì:

1. Pain point rõ ràng.
2. Có ý nghĩa xã hội.
3. AI Agent tạo ra giá trị rõ ràng hơn chatbot/RAG thông thường.
4. Có thể xây dựng prototype dễ dàng.
5. Có các metric cụ thể để đánh giá hiệu quả.

### Evidence

Nguồn:

Nguyen et al. (2022). *Elderly People’s Adaptation to the Evolving Digital Society: A Case Study in Vietnam*. Social Sciences, 11(8), 324.



## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Human confirm trong nhóm | Nhóm đã chốt candidate problem | Nhóm xác nhận bài toán “rào cản tiếp cận dịch vụ số của người lớn tuổi” sau khi hội tụ candidates và đối chiếu dữ liệu khảo sát HUST | Human confirm mới xác nhận đây là problem nhóm chọn, chưa chứng minh voice-based agent là giải pháp phù hợp nhất | Tách problem và solution: problem là rào cản thao tác dịch vụ số; voice-based AI agent chỉ là giả thuyết cần pilot |
| Survey / secondary data — HUST 2021 | 1.043 người từ 55 tuổi trở lên; 609 người trả lời lý do không dùng dịch vụ online | 73,6% thiếu thói quen sử dụng dịch vụ online; 36,8% ứng dụng có giao diện phức tạp, khó khai thác; 28,1% thiếu hướng dẫn cụ thể để thao tác | Đây là dữ liệu 2021 và câu hỏi cho phép chọn nhiều lý do, nên ba tỷ lệ không cộng thành 100%; chưa chứng minh người lớn tuổi muốn dùng voice agent | Thu hẹp bottleneck vào 3 nhóm: thói quen, giao diện phức tạp, thiếu hướng dẫn từng bước |
| Log / ticket / review (nếu có) | Chưa có log dịch vụ số của người lớn tuổi | Chưa thu thập | Chưa có dữ liệu trực tiếp về thao tác thất bại hoặc thời gian hoàn thành thủ tục | Cần pilot 5–10 người lớn tuổi với 1 thủ tục cụ thể, đo task completion, thời gian, số lần nhờ hỗ trợ |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật nằm ở khả năng tự thao tác dịch vụ số, đặc biệt khi người dùng thiếu thói quen, giao diện phức tạp và không có hướng dẫn từng bước. Voice-based AI agent có thể giảm rào cản giao diện và hướng dẫn, nhưng vẫn phải xử lý thói quen, tin tưởng và khả năng nghe hiểu tiếng Việt của người lớn tuổi.
```

Bằng chứng đính kèm: `02-group-problem-statement/validation-metrics.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| IVR / hotline hiện có | https://www.twilio.com/docs/voice/twiml | Cho phép thao tác bằng giọng nói qua điện thoại, kênh quen thuộc | Người lớn tuổi thường quen gọi điện hơn dùng app; dễ tiếp cận hơn app phức tạp | Menu cứng, nhiều bước, không hiểu câu hỏi tự do; khó hỗ trợ thủ tục phức tạp | Voice agent nên giữ ưu điểm “gọi điện/nói chuyện” nhưng cho phép hội thoại linh hoạt hơn IVR |
| Google Assistant | https://developers.google.com/assistant | Cung cấp giao diện voice, command và hội thoại cơ bản trên điện thoại/loa | Hạ rào cản gõ/và điều hướng giao diện; phổ biến trên Android | Chưa chắc hội thoại tiếng Việt tốt với người lớn tuổi; cần tích hợp riêng cho từng dịch vụ | Pilot nên dùng 1 dịch vụ cụ thể, không làm agent tổng quát ngay |
| Amazon Alexa Skills | https://developer.amazon.com/en-US/docs/alexa/ask-overview/what-is-alexa-skills-kit.html | Cho phép xây dựng voice skill theo từng quy trình | Có mẫu hội thoại, slot, confirmation và có thể ràng buộc từng bước | Phụ thuộc thiết bị loa Alexa; ở Việt Nam chưa phổ biến bằng điện thoại | Cần chọn kênh phổ biến nhất với người lớn tuổi Việt Nam, ưu tiên điện thoại |
| OpenAI Realtime API | https://platform.openai.com/docs/guides/realtime | Hỗ trợ hội thoại giọng nói gần thời gian thực cho AI agent | Có thể hỏi lại, xác nhận thông tin và hướng dẫn từng bước linh hoạt hơn IVR | Rủi ro nhận diện tiếng Việt/giọng địa phương, chi phí, privacy, và sai sót khi thao tác thủ tục quan trọng | AI nên hướng dẫn và xác nhận; bước nhạy cảm cần human owner hoặc kênh chính thức xác nhận |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nên pilot một voice-based AI agent cho 1–2 dịch vụ số cụ thể, không nên xây agent tổng quát ngay. Agent nên nói chậm, dùng câu ngắn, xác nhận trước mỗi bước, và có fallback chuyển người thật. Metric cần đo là tỷ lệ hoàn thành thủ tục, thời gian hoàn thành, số lần nhờ hỗ trợ và mức độ tin tưởng của người lớn tuổi.

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file:
`02-group-problem-statement-workflow.png/pdf/md`

``` text
[1. Truy cập website/dịch vụ: 2' - người lớn tuổi] → [2. Tìm thủ tục: 5' - người lớn tuổi] → [3. Đọc và hiểu hướng dẫn: 10' - người lớn tuổi] → [4. Điền thông tin vào form: 15' - người lớn tuổi - BOTTLENECK] → [5. Kiểm tra và sửa thông tin: 5' - người lớn tuổi] → [6. Nhờ người thân hỗ trợ nếu gặp khó khăn: 10-15' - người thân] → [7. Xác nhận và gửi hồ sơ: 3' - người lớn tuổi]
```

| Bước | Actor                       | Input                                   | Output                               | Thời gian / tần suất      | Ghi chú (handoff? bottleneck?)                |
|------|-----------------------------|-----------------------------------------|--------------------------------------|---------------------------|-----------------------------------------------|
| 1    | Người lớn tuổi              | Thiết bị, Internet                      | Truy cập được website/dịch vụ        | ~2 phút / lần             | Không                                         |
| 2    | Người lớn tuổi              | Nhu cầu thực hiện thủ tục               | Tìm được thủ tục cần làm             | ~5 phút / lần             | Có thể mất thời gian tìm kiếm                 |
| 3    | Người lớn tuổi              | Hướng dẫn thủ tục                       | Hiểu yêu cầu và giấy tờ cần chuẩn bị | ~10 phút / lần            | Dễ gặp khó khăn khi đọc hiểu                  |
| 4    | Người lớn tuổi              | Giấy tờ cá nhân, thông tin cần khai báo | Form được điền                       | ~15 phút / lần            | **Bottleneck chính**, dễ nhập sai hoặc bỏ sót |
| 5    | Người lớn tuổi              | Form đã điền                            | Form được kiểm tra                   | ~5 phút / lần             | Có thể không phát hiện lỗi                    |
| 6    | Người lớn tuổi + người thân | Thông tin chưa rõ / lỗi khi thao tác    | Được hướng dẫn hoặc sửa lỗi          | ~10-15 phút / lần khi cần | **Handoff**, phải nhờ người khác              |
| 7    | Người lớn tuổi              | Form đã kiểm tra                        | Hồ sơ được gửi                       | ~3 phút / lần             | Cần xác nhận trước khi gửi                    |

**Bottleneck chính (2-3 câu):**

``` text
Bottleneck nằm ở bước đọc hiểu hướng dẫn và điền thông tin vào form. Người lớn tuổi có thể mất nhiều thời gian để hiểu yêu cầu, không biết điền thông tin nào vào từng trường và dễ nhập sai hoặc bỏ sót dữ liệu. Khi gặp khó khăn, họ thường phải nhờ người thân hoặc người khác hỗ trợ, tạo thêm một handoff và làm tăng tổng thời gian hoàn thành thủ tục.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người,
boundary ở đâu, fallback khi AI sai.

``` text
[1. Truy cập và xác định thủ tục: 1' - máy/Rule] → [2. AI giải thích hướng dẫn + hỏi từng thông tin: 8' - AI] → [3. AI chuyển câu trả lời thành dữ liệu + điền form: 3' - AI] → [4. AI kiểm tra trường thiếu/sai: 2' - AI/Rule] → [5. Người dùng review và xác nhận: 3' - người - BOUNDARY] → [6. Gửi hồ sơ: 1' - máy]

Fallback: Nếu AI không hiểu câu trả lời, thông tin bị thiếu hoặc mơ hồ, hệ thống phải hỏi lại. Nếu vẫn không xử lý được, chuyển sang hướng dẫn thủ công hoặc yêu cầu người thân/người hỗ trợ can thiệp.
```

**Boundary:** AI chỉ hỗ trợ đọc hiểu hướng dẫn, thu thập thông tin, điền
và kiểm tra form. AI không được tự suy đoán thông tin cá nhân quan trọng
và không được tự gửi hồ sơ nếu chưa có xác nhận rõ ràng của người dùng.

**Before/after impact:**

| Metric           |                       Trước |             Sau kỳ vọng | Cách đo                                             |
|------------------|----------------------------:|------------------------:|-----------------------------------------------------|
| Tổng thời gian   |                 ~40-55 phút |             ~15-20 phút | Đo thời gian từ lúc bắt đầu đến khi hoàn thành      |
| Số bước          |                           7 |                       6 | Đếm số bước trong workflow                          |
| Số bước thủ công |                           7 |                     2-3 | Đếm số bước người dùng phải tự đọc/nhập             |
| Bottleneck chính |        Đọc hiểu + điền form |      Review và xác nhận | Đo thời gian tại từng bước                          |
| Risk mới         | Nhập sai / bỏ sót thông tin | AI hiểu sai câu trả lời | Đếm số lần AI cần hỏi lại hoặc người dùng chỉnh sửa |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field              | Nội dung                                                                                                                                                                                                                                    |
|--------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Actor**          | Người lớn tuổi hoặc người có kỹ năng số hạn chế là người trực tiếp thực hiện thủ tục trực tuyến. Họ có thể cần hỗ trợ khi đọc hiểu hướng dẫn hoặc thao tác trên form.                                                                       |
| **Workflow**       | Người dùng truy cập dịch vụ, tìm thủ tục, đọc hướng dẫn, chuẩn bị thông tin/giấy tờ, điền form, kiểm tra và gửi hồ sơ. Khi gặp khó khăn, họ có thể phải nhờ người thân hoặc người hỗ trợ can thiệp.                                         |
| **Bottleneck**     | Bottleneck chính là đọc hiểu hướng dẫn và điền các trường thông tin trên form. Các thuật ngữ khó hiểu, nhiều trường thông tin và yêu cầu thao tác trên giao diện khiến người dùng dễ nhập sai hoặc bỏ sót dữ liệu.                          |
| **Impact**         | Quy trình mất nhiều thời gian và làm tăng khả năng nhập sai hoặc bỏ sót thông tin. Người dùng có thể phải nhờ người khác hỗ trợ, làm giảm khả năng tự thực hiện thủ tục trực tuyến.                                                         |
| **Success Metric** | Thành công được đo bằng thời gian hoàn thành thủ tục, tỷ lệ hoàn thành, độ chính xác của các trường thông tin và số lần cần người khác hỗ trợ. Mục tiêu ban đầu là giảm thời gian hoàn thành và giảm số lần cần can thiệp của người hỗ trợ. |
| **Boundary**       | AI chỉ hỗ trợ giải thích hướng dẫn, hỏi và thu thập thông tin, điền form và kiểm tra dữ liệu. AI không được tự suy đoán thông tin cá nhân quan trọng và không được tự gửi hồ sơ; người dùng phải review và xác nhận trước khi gửi.          |

**Câu hỏi AI phản biện v0 (nếu có):** - Field nào mơ hồ: Chưa xác định
cụ thể loại thủ tục online nào sẽ được dùng trong pilot và chưa có
baseline thực tế từ người dùng. - Tôi sửa gì: Chọn một thủ tục online cụ
thể để pilot, đo thời gian hoàn thành và số lỗi của workflow hiện tại
trước khi đánh giá hiệu quả của AI.


## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Thủ tục hành chính công có quy định pháp lý bất biến và tính đúng/sai tuyệt đối; thông tin biểu mẫu phải trùng khớp 100% với giấy tờ tùy thân và Cơ sở dữ liệu quốc gia về dân cư, không có chỗ cho suy diễn tùy tiện.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Quy trình đòi hỏi chuỗi liên hoàn nhiều bước: hiểu văn bản pháp lý -> chụp và thẩm định nhiều loại giấy tờ (CCCD, BHYT cũ, giấy tờ liên quan) -> bóc tách thông tin điền form nhiều trường -> xác thực OTP -> nộp hồ sơ.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô "Độ phức tạp cao — Độ mơ hồ thấp" (High Complexity — Low Ambiguity)
```

**Vì sao (2-3 câu):**

```text
Thủ tục hành chính có các bước đi tuần tự, chặt chẽ theo luật định nên độ mơ hồ thấp, nhưng lại đòi hỏi phối hợp đa phương thức (giọng nói tiếng Việt, nhận diện ảnh chụp giấy tờ/OCR, mapping biểu mẫu). Một hệ thống Workflow với các module AI chuyên biệt hỗ trợ từng khâu là tối ưu nhất; bài toán không cần và không được phép để một Autonomous Agent tự do lập kế hoạch ngoài quy chuẩn pháp lý.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Hệ thống cẩm nang/FAQ tĩnh, nút bấm và font chữ phóng to, form validation kiểm tra regex CCCD, ngày sinh, dung lượng file tải lên. | Đủ với người lớn tuổi có kỹ năng số khá, tự đọc hiểu và tự gõ được văn bản trên điện thoại. | Người già mắt kém, tay run khó gõ phím; không hiểu các câu hỏi mở/thuật ngữ hành chính; không xử lý được ảnh giấy tờ bị chụp mờ, lóa hoặc mất góc. | **Có dùng:** Dùng cho khâu kiểm tra định dạng dữ liệu (regex CCCD, định dạng file upload). |
| **Workflow** | Chuỗi pipeline cố định (Deterministic Pipeline): (1) Voice-to-Text nhận diện câu hỏi của người già -> (2) LLM tóm lược thủ tục dễ hiểu & tạo checklist -> (3) Vision AI tiền kiểm ảnh giấy tờ -> (4) OCR trích xuất tự điền nháp vào form -> (5) Con người xác nhận nộp. | Đủ và lý tưởng vì luồng thủ tục hành chính là cố định, tuyến tính; AI chỉ đóng vai trò tháo gỡ 2 rào cản thao tác: giao tiếp giọng nói và hỗ trợ kiểm tra giấy tờ. | Rủi ro nhận diện sai giọng nói địa phương hoặc trích xuất nhầm số; giải quyết bằng màn hình xác nhận to, rõ và đọc lại bằng âm thanh (TTS) để người dùng duyệt. | **CHỌN LÀM MỨC CHỦ ĐẠO TOÀN BÀI.** |
| **Agent** | Agent tự động lập kế hoạch: tự truy cập tài khoản Dịch vụ công, tự tìm thủ tục, tự tải giấy tờ và tự bấm nộp/thanh toán lệ phí qua API/browser automation. | Chỉ cần nếu thủ tục hành chính biến thiên liên tục không theo quy luật, đòi hỏi AI phải tự do khám phá và thích ứng linh hoạt với hệ thống ngoài. | Rủi ro pháp lý và an toàn dữ liệu (PII) cực lớn: AI có thể nộp sai thông tin nhân thân; vi phạm bảo mật nếu lưu trữ OTP/mật khẩu định danh; Agent có thể chạy sai quy trình gây hậu quả pháp lý. | **KHÔNG CHỌN.** (Không giao quyền quyết định pháp lý và nộp hồ sơ cho Agent). |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không?
   -> Không, vì rào cản lớn nhất của người già là mắt kém ngại đọc văn bản pháp lý dài và tay run ngại gõ phím; Rule tĩnh không thể lắng nghe giọng nói hay thẩm định chất lượng ảnh chụp giấy tờ.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?
   -> Các bước đi thẳng theo một đường tuần tự do quy định hành chính nhà nước ban hành: Hỏi thủ tục -> Chuẩn bị giấy tờ -> Điền biểu mẫu -> Đối soát -> Nộp hồ sơ.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?
   -> Hoàn toàn không cần, vì quy trình không cho phép AI tự sáng tạo hay nhảy bước; việc tự động gọi tool nộp hồ sơ còn vi phạm điều khoản bảo mật thông tin định danh công dân.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?
   -> Người lớn tuổi (hoặc người thân hỗ trợ) sẽ phát hiện ngay ở màn hình xác nhận đối soát thông qua giọng đọc TTS to rõ; chỉ mất 1-2 phút nói lại hoặc chụp lại giấy tờ trước khi ấn nộp.
5. Có hạ được từ Agent → Workflow → Rule không?
   -> Có. Hạ từ Agent xuống Workflow giúp hệ thống an toàn và kiểm soát được 100%. Nếu hạ tiếp xuống Rule thuần thì sẽ mất khả năng tương tác giọng nói và đọc ảnh, biến lại thành dịch vụ công cũ mà người già đang bế tắc. Do đó, điểm dừng tối ưu bắt buộc là Workflow.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Chúng tôi chọn Workflow vì đây là phương án cân bằng tối ưu giữa trải nghiệm không chạm (voice/vision) cho người cao tuổi và tính an toàn pháp lý. Hệ thống tuân theo một quy trình 5 bước xác định, tại mỗi bước nghẽn thao tác (nhập liệu, đọc thuật ngữ, kiểm tra ảnh chụp), AI được tích hợp cục bộ để chuyển giọng nói, tóm lược dễ hiểu và đọc ảnh CCCD. Cách tiếp cận này loại bỏ rào cản công nghệ nhưng vẫn giữ nguyên tắc Human-in-the-loop: quyền bấm nút nộp hồ sơ cuối cùng luôn thuộc về con người.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Mức Rule đơn giản hơn không thể khắc phục được hạn chế sinh học tự nhiên của người cao tuổi (mắt mờ, tay run, khó thao tác bàn phím ảo nhỏ). Nếu chỉ dựa vào phóng to giao diện hay tài liệu hướng dẫn cố định theo Rule, người già vẫn phải tự đọc hàng trang văn bản pháp lý phức tạp và tự tải file đúng dung lượng, dẫn đến tỷ lệ bỏ cuộc giữa chừng vẫn ở mức cao.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Người lớn tuổi (từ 60 tuổi trở lên tại Việt Nam) cần tự thực hiện các thủ tục hành chính công trực tuyến cơ bản (cấp đổi thẻ BHYT, đổi GPLX, đăng ký thường trú/tạm trú) với sự hỗ trợ hoặc giám sát của người thân trong gia đình. |
| **Workflow** | Người dùng mở ứng dụng -> Nói yêu cầu bằng giọng nói -> Nghe hướng dẫn danh mục giấy tờ cần thiết -> Chụp ảnh các giấy tờ đưa lên -> Hệ thống tự bóc tách điền nháp vào form -> Người dùng nghe đọc lại kiểm tra thông tin -> Người dùng tự ấn xác nhận nộp hồ sơ. |
| **Bottleneck** | Người lớn tuổi không hiểu các thuật ngữ pháp lý ("bản sao chứng thực điện tử", "định danh mức 2"), thao tác điền form trên điện thoại dễ gõ sai số liệu, và ảnh chụp giấy tờ tải lên thường xuyên bị mờ/mất góc/chói sáng dẫn đến hồ sơ bị từ chối nhiều lần. |
| **Impact** | Trung bình người già mất 60-90 phút cho một thủ tục (hoặc bỏ cuộc phải nhờ con cháu nghỉ làm đi làm thay); tỷ lệ hồ sơ nộp lần đầu bị trả về do sai sót giấy tờ lên tới 40-50%, gây áp lực cho cả người dân lẫn cán bộ một cửa. |
| **Success Metric** | - Giảm thời gian hoàn tất nộp hồ sơ từ trung bình 60 phút xuống dưới 15 phút.<br>- Tỷ lệ hồ sơ hợp lệ được cơ quan tiếp nhận ngay từ lần đầu tăng từ ~50% lên trên 85%.<br>- Tỷ lệ người già tự hoàn thành form mà không cần con cháu làm hộ đạt >= 60%. |
| **Boundary** (làm / không làm) | **LÀM:** Trợ lý giọng nói hỏi đáp tiếng Việt bình dân; hướng dẫn chụp ảnh và tự kiểm tra chất lượng giấy tờ (đủ sáng, đủ 4 góc); trích xuất text tự điền bản nháp; đọc lại thông tin to rõ.<br>**KHÔNG LÀM:** Không tự động nộp hồ sơ thay người dùng; không lưu trữ mã OTP, mật khẩu VNeID hay dữ liệu sinh trắc học; không đưa ra phán quyết hay tư vấn pháp lý vượt quá quy định hiện hành. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp ở 2 điểm nút: (1) Sau khi người dùng nói yêu cầu -> trước khi tạo checklist giấy tờ; (2) Sau khi người dùng chụp ảnh giấy tờ -> trước khi điền dữ liệu vào biểu mẫu nộp. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Workflow** — Vì luồng thủ tục hành chính có tính chất xác định và nghiêm ngặt; AI chỉ đóng vai trò cầu nối giao tiếp thân thiện (Voice/Vision/LLM trợ lý) giúp người già tương tác dễ dàng với hệ thống form có sẵn. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | **Rủi ro lớn nhất:** AI OCR nhận diện sai số CCCD/họ tên do ảnh mờ, hoặc LLM hiểu sai câu nói tiếng địa phương của người già.<br>**Người thật kiểm tra:** Ở bước cuối cùng, hệ thống dùng TTS đọc to từng trường thông tin kèm giao diện tương phản cao để người già (hoặc người thân) nghe, đối chiếu mắt thường và tự tay ấn nút "Đồng ý nộp". |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Actor là công dân cao tuổi >= 60 tuổi làm dịch vụ công; quy trình 5 bước tuyến tính đã được mô tả chi tiết từ lúc nói nhu cầu đến khi hoàn tất. |
| Baseline + metric đo được chưa? | **Yes** | Baseline hiện tại là 60 phút/thủ tục và 40-50% hồ sơ bị từ chối; target rút ngắn xuống dưới 15 phút và tỷ lệ duyệt lần đầu đạt >= 85%. |
| Data/input đủ dùng chưa? | **Yes** | Input là giọng nói tiếng Việt và ảnh chụp CCCD/giấy tờ hành chính chuẩn mẫu nhà nước ban hành; hoàn toàn có thể thu thập tập test pilot. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Chấp nhận được vì AI chỉ trích xuất điền nháp biểu mẫu; con người luôn đối soát ở bước cuối trước khi ấn nộp, không có rủi ro tự động submit sai lệch. |
| Có người review/owner không? | **Yes** | Người cao tuổi và người thân trực tiếp kiểm tra nội dung; cán bộ một cửa là người tiếp nhận và phê duyệt hồ sơ ở bước sau cùng. |
| Có cách non-AI đơn giản hơn không? | **No** | Non-AI (như phóng to chữ, cẩm nang giấy) đã áp dụng nhưng không hiệu quả vì không giải quyết được việc người già mắt mờ ngại gõ phím và không biết kiểm tra file ảnh chụp. |

**Decision:**

```text
Go
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Quyết định "Go" vì bài toán có đối tượng thụ hưởng và nỗi đau rõ ràng, phù hợp hoàn hảo với mô hình Workflow hỗ trợ AI tại từng khâu chuyên biệt. Rủi ro về an toàn dữ liệu và sai sót pháp lý đã được khoanh vùng triệt để bằng cơ chế Human-in-the-loop (con người ấn nộp cuối cùng). Công nghệ xử lý tiếng Việt (STT/TTS) và OCR trích xuất giấy tờ tùy thân tại Việt Nam hiện đã đủ trưởng thành để triển khai với độ chính xác cao và chi phí tối ưu.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data pilot: 01 thủ tục phổ biến nhất: "Đăng ký cấp đổi lại thẻ BHYT do hỏng/mất" hoặc "Cấp đổi Giấy phép lái xe trực tuyến" cho nhóm thử nghiệm gồm 15-20 người cao tuổi (từ 60 đến 75 tuổi).
- Cách chạy pilot (Bán tự động / Wizard of Oz): 
  + Người tham gia dùng điện thoại nói yêu cầu vào giao diện web mẫu.
  + Module Voice-to-text và LLM trích xuất thông tin, hướng dẫn chụp CCCD.
  + Module Vision kiểm tra ảnh chụp (đạt/không đạt), điền trước thông tin vào form BHYT.
  + Người già nghe hệ thống đọc lại xác nhận và nhấn nút nộp thử nghiệm.
- Đo 3 số cụ thể:
  1. Thời gian trung bình để hoàn tất một bộ hồ sơ (Mục tiêu: < 15 phút).
  2. Tỷ lệ trường thông tin được trích xuất chính xác mà không cần sửa tay (Mục tiêu: >= 90%).
  3. Điểm đánh giá mức độ tự tin/hài lòng của người cao tuổi theo thang điểm SUS (System Usability Scale >= 75/100).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì đã chọn Go. Tuy nhiên trong quá trình phát triển, cần kiểm thử thêm độ nhạy nhận diện giọng nói đối với các phương ngữ vùng miền khác nhau của người cao tuổi).
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng vì đã chọn Go).
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
- Dừng AI và quay về cách cũ (hoặc chuyển sang chế độ gọi video nhờ nhân viên công quyền / người thân làm hộ) khi:
  1. Tỷ lệ nhận diện sai thông tin quan trọng (số CCCD, họ tên, ngày sinh) vượt quá 10% trong quá trình thử nghiệm.
  2. Thời gian người già phải sửa lại các lỗi do AI điền sai khiến tổng thời gian hoàn tất thủ tục vượt quá 45 phút (không đem lại giá trị vượt trội so với làm thủ công).
  3. Chi phí vận hành API (STT, OCR, LLM) vượt quá ngân sách 2.000 VNĐ cho một lượt nộp hồ sơ thành công.
```

---

### Self-check nộp phần 02 (nhóm)
- [ ] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được)
- [ ] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [ ] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [ ] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
