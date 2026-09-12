# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Vũ Hải Đăng
- Mã học viên: 2A202602821
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm cuối
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): 
    - Làm bài tập, nghiên cứu và hoàn thành các môn học liên quan đến AI.
    - Thực hiện các project AI/ML theo nhóm và cá nhân.
    - Tìm hiểu, thử nghiệm và triển khai các mô hình AI/LLM.
    - Làm việc nhóm, phân chia task và theo dõi tiến độ project.
    - Tìm kiếm tài liệu, đánh giá giải pháp và chuẩn bị báo cáo/thuyết trình.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Khó khăn khi thực hiện thủ tục online của người lớn tuổi | Người lớn tuổi | Ước tính 40-55 phút cho một lần thực hiện; thường cần đọc hướng dẫn, tìm thông tin và điền nhiều trường. Đây là problem nhóm đang phát triển, cần đo baseline thực tế trong pilot. |
| 2 | AI có thể tốt hơn | Khó tìm và hiểu thông tin cũ trong nhiều file/tài liệu | Sinh viên, người làm việc với nhiều tài liệu | Có thể mất 10-20 phút để tìm đúng thông tin trong nhiều file; cần kiểm chứng bằng thời gian tìm kiếm thực tế. |
| 3 | Tốn thời gian | Khó bàn giao công việc khi có người mới thay thế | Nhân viên/người tiếp nhận task | Có thể phải đọc nhiều tài liệu và hỏi lại người cũ; thời gian cụ thể cần đo qua interview. |
| 4 | AI có thể tốt hơn | Khó biết phải làm gì trước khi nhận một task chưa rõ ràng | Người nhận task | Có thể mất 5-15 phút để đọc task và xác định bước tiếp theo; cần kiểm chứng qua quan sát/interview. |
| 5 | Pain từ người khác | Khó phân biệt thông tin sai lệch trên Internet | Người đọc thông tin online | Người dùng phải kiểm tra nhiều nguồn trước khi tin; số lần kiểm chứng cần khảo sát thực tế. |


> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Khó khăn khi thực hiện thủ tục online của người lớn tuổi | Actor rõ; bottleneck tập trung ở đọc hiểu và điền form; impact có thể đo bằng thời gian, lỗi và nhu cầu hỗ trợ. | Baseline thực tế và loại thủ tục pilot cần được xác nhận. |
| 2 | Khó tìm và hiểu thông tin cũ trong nhiều file/tài liệu | Pain phổ biến; workflow dễ vẽ; RAG có thể tạo prototype nhanh. | Khó tạo khác biệt so với các công cụ tìm kiếm/RAG hiện có. |
| 3 | Khó bàn giao công việc khi có người mới thay thế | Có giá trị trong môi trường làm việc; impact về thời gian và số lần hỏi lại có thể đo. | Cần dữ liệu workflow thực tế và người dùng để validate. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Khó khăn khi thực hiện thủ tục online của người lớn tuổi

```text
Problem 1 câu: Người lớn tuổi gặp khó khăn khi thực hiện thủ tục trực tuyến vì phải đọc hiểu hướng dẫn và tự điền nhiều trường thông tin.

Actor: Người lớn tuổi hoặc người có kỹ năng số hạn chế.

Thời điểm / bối cảnh: Khi cần tự thực hiện một thủ tục hành chính hoặc dịch vụ trực tuyến.

Current workflow 3-7 bước:
1. Truy cập website/dịch vụ.
2. Tìm thủ tục cần thực hiện.
3. Đọc và hiểu hướng dẫn.
4. Chuẩn bị thông tin/giấy tờ và điền form.
5. Kiểm tra thông tin.
6. Nhờ người thân hỗ trợ nếu gặp khó khăn.
7. Xác nhận và gửi hồ sơ.

Bottleneck: Đọc hiểu hướng dẫn và điền form, đặc biệt khi có nhiều trường thông tin hoặc thuật ngữ khó hiểu.

Impact: Tăng thời gian hoàn thành, tăng nguy cơ nhập sai/bỏ sót và làm người dùng phụ thuộc vào người khác.

Success metric: Thời gian hoàn thành, tỷ lệ hoàn thành, độ chính xác trường thông tin và số lần cần người hỗ trợ.

Non-AI alternative: Đơn giản hóa form, viết lại hướng dẫn bằng ngôn ngữ dễ hiểu và cung cấp hướng dẫn từng bước.

AI hypothesis: Voice-based AI Agent có thể giải thích hướng dẫn, hỏi từng thông tin, chuyển câu trả lời thành dữ liệu, hỗ trợ điền form và yêu cầu người dùng xác nhận trước khi gửi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ~40-55 phút

[1 Truy cập: 2'] → [2 Tìm thủ tục: 5'] → [3 Đọc hướng dẫn: 10'] → [4 Điền form: 15'] → [5 Kiểm tra: 5'] → [6 Nhờ hỗ trợ: 10-15'] → [7 Gửi: 3']  <-- bottleneck

FUTURE STATE — ~15-20 phút

[1 Xác định thủ tục: 1'] → [2 AI hỏi/giải thích: 8'] → [3 AI điền + kiểm tra: 5'] → [4 Người dùng review: 3'] → [5 Gửi: 1']  <-- human boundary

Fallback: nếu AI không hiểu hoặc thông tin mơ hồ thì hỏi lại; nếu vẫn không xử lý được thì chuyển sang hướng dẫn thủ công/người hỗ trợ.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

#### Problem Card #2 — Khó tìm và hiểu thông tin cũ trong nhiều file/tài liệu

```text
Problem 1 câu: Người dùng mất thời gian tìm lại thông tin cũ nằm rải rác trong nhiều file và tài liệu.

Actor: Sinh viên hoặc người thường xuyên làm việc với nhiều tài liệu.

Thời điểm / bối cảnh: Khi cần tìm lại một thông tin, quy trình hoặc nội dung đã lưu trước đó.

Current workflow 3-7 bước:
1. Nhớ hoặc xác định từ khóa cần tìm.
2. Mở các thư mục/file liên quan.
3. Tìm kiếm bằng tên file hoặc từ khóa.
4. Mở và đọc nhiều tài liệu.
5. So sánh để xác định thông tin đúng.

Bottleneck: Đọc và kiểm tra nhiều file sau khi tìm kiếm được kết quả.

Impact: Mất thời gian và dễ bỏ sót thông tin liên quan.

Success metric: Thời gian tìm thông tin, tỷ lệ tìm đúng tài liệu và số file phải mở.

Non-AI alternative: Chuẩn hóa tên file, thư mục và hệ thống tagging.

AI hypothesis: RAG có thể lập chỉ mục tài liệu và trả lời câu hỏi dựa trên nội dung đã lưu, kèm nguồn tham chiếu.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ~10-20 phút

[1 Xác định từ khóa] → [2 Tìm file] → [3 Mở nhiều file] → [4 Đọc/so sánh]  <-- bottleneck

FUTURE STATE — ~2-5 phút

[1 Nhập câu hỏi] → [2 RAG tìm/chọn đoạn liên quan] → [3 Người dùng review nguồn]  <-- human boundary

Fallback: nếu không tìm thấy bằng chứng phù hợp thì trả về trạng thái không đủ thông tin và yêu cầu người dùng tìm thủ công.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-2.png`

#### Problem Card #3 — Khó bàn giao công việc khi có người mới thay thế

```text
Problem 1 câu: Người mới gặp khó khăn khi tiếp nhận công việc vì thông tin bàn giao không đầy đủ hoặc phân tán.

Actor: Người mới tiếp nhận công việc và người bàn giao.

Thời điểm / bối cảnh: Khi có thành viên mới thay thế hoặc tiếp nhận một task đang dang dở.

Current workflow 3-7 bước:
1. Nhận tài liệu/task từ người cũ.
2. Đọc tài liệu bàn giao.
3. Tìm thêm thông tin trong các file/kênh liên quan.
4. Hỏi người cũ về phần chưa rõ.
5. Bắt đầu thực hiện task.
6. Quay lại hỏi khi phát sinh vấn đề.

Bottleneck: Tìm hiểu context và hỏi lại những thông tin chưa được bàn giao.

Impact: Tăng thời gian onboarding, phụ thuộc người cũ và có nguy cơ bỏ sót context.

Success metric: Thời gian để người mới có thể bắt đầu task, số lần hỏi lại và số lỗi do thiếu context.

Non-AI alternative: Chuẩn hóa template bàn giao và checklist bắt buộc.

AI hypothesis: AI có thể tổng hợp tài liệu/task thành handover brief, chỉ ra thông tin còn thiếu và trả lời câu hỏi dựa trên tài liệu bàn giao.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ~30-60 phút

[1 Nhận bàn giao] → [2 Đọc tài liệu] → [3 Tìm context] → [4 Hỏi người cũ] → [5 Bắt đầu task]  <-- bottleneck

FUTURE STATE — ~10-20 phút

[1 Upload tài liệu/task] → [2 AI tổng hợp context + checklist] → [3 Người mới review] → [4 Bắt đầu task]  <-- human boundary

Fallback: nếu AI không tìm thấy thông tin trong tài liệu, đánh dấu thiếu context và yêu cầu người bàn giao bổ sung.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-3.png`


### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Khó khăn khi thực hiện thủ tục online của người lớn tuổi
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow có bottleneck rõ ở bước đọc hiểu và điền form, đồng thời có thể đo được thời gian hoàn thành, số lỗi và số lần cần người hỗ trợ. Impact trực tiếp là giảm thời gian và tăng khả năng tự hoàn thành thủ tục. AI Agent cũng tạo giá trị rõ hơn so với chỉ đơn giản hóa giao diện.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Liệu người lớn tuổi có thực sự muốn dùng voice AI để thực hiện thủ tục, hay việc đơn giản hóa giao diện và hướng dẫn là đủ? Với các trường thông tin quan trọng, cơ chế nào đảm bảo AI không hiểu sai và điền sai dữ liệu?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Baseline thời gian và tỷ lệ lỗi hiện mới là ước tính; loại thủ tục cụ thể chưa được chốt.
- Tôi sửa gì: Chọn một thủ tục cụ thể để pilot và đo baseline thực tế trước khi so sánh với AI.

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
