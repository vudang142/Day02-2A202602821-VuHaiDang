# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Vũ Hải Đăng
- Mã học viên: 2A202602821
- Nhóm: Người cao tuổi
- Candidate problem nhóm chọn: Khó khăn khi thực hiện thủ tục online của người lớn tuổi → Voice-based AI Agent hỗ trợ người dùng đọc hiểu, điền thông tin và hoàn thành thủ tục trực tuyến.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 5 problems từ công việc thật của mình (học AI/ML, làm project nhóm, tìm tài liệu), gán actor + dấu hiệu thật cho từng dòng theo 4 lăng kính. | Có bảng 5 problems đủ field làm nguyên liệu để chọn top 3 Problem Cards, trong đó problem "thủ tục online người lớn tuổi" sau này thành candidate của cả nhóm. |
| Pitch Problem Card | Pitch 3 candidates ở vòng trình bày top 3 mỗi người (candidate #10, #11, #12 trong bảng 3.1 nhóm), trong đó pitch kỹ nhất candidate #10 "Khó khăn khi thực hiện thủ tục online của người lớn tuổi" với workflow 7 bước và số đo thời gian cụ thể. | Nhóm nhận xét ngay "khả thi, chọn làm vấn đề chung của cả nhóm - ưu tiên chọn để phát triển"; candidate này sau đó chấm điểm cao nhất (34/35) và được chọn làm bài chung. |
| Challenge bài của bạn khác | Đặt câu hỏi challenge cho chính card của mình ("người già có thực sự muốn dùng voice AI hay chỉ cần đơn giản hoá giao diện là đủ?", "cơ chế nào đảm bảo AI không điền sai dữ liệu quan trọng?") để cả nhóm mổ xẻ trước khi chốt. | Câu hỏi này kéo nhóm đi tìm validation thật (survey HUST 2021) thay vì tin ngay vào giả thuyết voice agent, và buộc nhóm tách rõ problem với solution ở Phase 4. |
| Gom trùng / cluster | Đóng góp candidate #10 vào cluster D "Thủ tục online cho người lớn tuổi" và tham gia thảo luận xếp #11, #12 (phân luồng bệnh nhân, lừa đảo trực tuyến) vào các cluster khác. | Giúp nhóm hội tụ nhanh từ 15 candidates xuống 5 clusters, trong đó cluster D được ghi chú thẳng là "Vấn đề chung được chọn". |
| Chọn candidate problem | Là người đưa ra candidate #10, tham gia chấm điểm ma trận 7 tiêu chí (Actor/Workflow/Pain/Impact/Lab khả thi/So sánh/Domain) và bảo vệ lựa chọn khi có thành viên muốn ưu tiên hướng RAG tìm tài liệu. | Candidate #10 thắng với 34/35 điểm, trở thành Problem Statement chính thức của nhóm. |
| Validation / research | Tìm và đưa vào nguồn Nguyen et al. (2022) về khảo sát 1.043 người từ 55 tuổi ở Việt Nam để xác nhận pain thật (36,8% giao diện phức tạp, 28,1% thiếu hướng dẫn); research thêm các pattern công nghệ liên quan (IVR, Google Assistant, Alexa Skills, OpenAI Realtime API). | Insight validation ("pain thật nằm ở thói quen, giao diện, hướng dẫn — không phải chỉ thiếu voice AI") và research takeaway ("pilot 1-2 dịch vụ cụ thể, không build agent tổng quát") trực tiếp định hướng workflow và PS của nhóm. |
| Workflow nhóm | Dựng current workflow 7 bước (~40-55 phút, bottleneck ở bước điền form) và future workflow 6 bước (~15-20 phút) với boundary rõ AI không được tự gửi hồ sơ. | Bảng before/after impact (thời gian, số bước, bottleneck, risk mới) là căn cứ để nhóm viết Success Metric ở Problem Statement. |
| Problem Statement | Viết PS v0 rồi siết lại thành v1 cho cả 6 field, thêm 3 field cuối (AI intervention point, Mức chọn, Rủi ro & người thật kiểm tra) với số liệu cụ thể (60-90 phút, 40-50% hồ sơ bị trả về). | PS v1 có actor/metric/boundary rõ ràng, đủ điều kiện để nhóm chấm điểm và ra quyết định Go ở Phase 6. |
| Rule / Workflow / Agent | Dẫn dắt phân tích ma trận độ mơ hồ (thấp) × độ phức tạp (cao), điền bảng so sánh Rule/Workflow/Agent và trả lời đầy đủ 5 câu hỏi chốt (Rule có giải 70-80% không, có cần Agent tự lập kế hoạch không...). | Nhóm thống nhất chọn mức Workflow, loại bỏ phương án Agent tự động nộp hồ sơ vì rủi ro pháp lý và PII — quyết định này giữ nguyên tắc human-in-the-loop xuyên suốt bài. |
| Decision | Hoàn thiện bảng Final decision 6 câu hỏi Yes/Not Yet/No, viết lý do Go, thiết kế pilot nhỏ nhất (15-20 người 60-75 tuổi, 1 thủ tục BHYT/GPLX, đo 3 số: thời gian, % trích xuất đúng, điểm SUS) và điều kiện exit/rollback. | Nhóm có quyết định Go rõ ràng kèm kế hoạch pilot đo được, không dừng ở mức "cảm thấy nên làm". |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Candidate problem "thủ tục online cho người lớn tuổi" mà cả nhóm chọn là do chính tôi pitch từ Phase 3, và phần pilot plan cụ thể (đối tượng, cách chạy Wizard of Oz, 3 metric đo) ở Phase 6 là phần tôi viết chi tiết nhất trong bài nộp cuối.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Nhờ AI gợi ý thêm góc nhìn theo 4 lăng kính (lặp lại / tốn thời gian / AI tốt hơn / pain người khác) khi tôi bí ý tưởng. | Mở rộng nhanh số lượng problem để đủ 5+ dòng, tránh chỉ liệt kê những gì quen thuộc. | AI đưa "dấu hiệu thật" là con số ước lượng chung chung (ví dụ "10-20 phút") mà không có bằng chứng đo thật nào. | Ghi rõ trong bảng là "ước tính, cần đo baseline thực tế" thay vì để số liệu trông như đã được đo, và bỏ những ý AI đưa ra không map được với pain thật của bản thân. |
| Problem Card | Dùng AI để phác thảo workflow 7 bước current/future và gợi ý thời gian từng bước cho cả 3 cards. | Giúp cấu trúc hoá nhanh workflow before/after và tìm được success metric hợp lý (thời gian, tỷ lệ hoàn thành, số lỗi). | AI cho số liệu thời gian từng bước (ví dụ "15 phút điền form") như thể đã đo thật, trong khi thực tế chỉ là ước tính. | Giữ số liệu ở dạng khoảng ước tính, ghi rõ trong self-check là baseline thực tế cần đo qua interview/pilot chứ không lấy số của AI làm căn cứ cuối. |
| Workflow | Dùng AI hỗ trợ dựng future-state workflow, phân vai bước nào Rule/bước nào AI/bước nào người và tìm fallback. | Gợi ý tốt về vị trí boundary (người dùng phải review/xác nhận trước khi gửi) và fallback khi AI hiểu sai. | Bản nháp đầu AI đề xuất để AI tự động gửi luôn hồ sơ sau khi điền form cho nhanh. | Cùng nhóm giữ nguyên tắc human-in-the-loop, sửa lại bước cuối thành "người dùng xác nhận rồi mới gửi", không để AI tự submit. |
| Research | Dùng AI để tìm nhanh các pattern/tool liên quan (IVR, Google Assistant, Alexa Skills, OpenAI Realtime API) và tóm tắt điểm mạnh/khoảng trống từng cái. | Liệt kê nhanh nhiều lựa chọn kèm link để so sánh, tiết kiệm thời gian tìm kiếm thủ công. | AI có xu hướng đưa ra vài số liệu về người dùng lớn tuổi mà không kèm nguồn kiểm chứng được. | Chỉ giữ lại số liệu có nguồn xác minh được (khảo sát Nguyen et al. 2022, 1.043 người), loại bỏ mọi số liệu AI tự suy diễn không có link gốc. |
| Problem Statement | Dùng AI để soạn câu chữ cho từng field PS v0, rồi tự sửa sang v1. | Giúp diễn đạt đúng cấu trúc field, câu văn rõ ràng, không lan man. | Field Actor và Impact ở bản AI soạn đầu tiên rất chung chung, không có số cụ thể (kiểu "mất nhiều thời gian"). | Thu hẹp Actor về "người từ 60 tuổi trở lên tại Việt Nam làm thủ tục hành chính công cụ thể" và bổ sung số liệu thật vào Impact (60-90 phút/thủ tục, 40-50% hồ sơ bị trả về lần đầu). |
| Rule / Workflow / Agent | Dùng AI để dựng bảng so sánh Rule/Workflow/Agent và trả lời 5 câu hỏi chốt. | Liệt kê rõ rủi ro từng mức, đặc biệt là rủi ro pháp lý/PII nếu để Agent tự nộp hồ sơ. | Gợi ý đầu tiên của AI hơi nghiêng về chọn Agent vì "linh hoạt và ấn tượng hơn", tức là solution-first chứ chưa cân nhắc rủi ro. | Cùng nhóm phân tích lại độ mơ hồ (thấp) và hậu quả nếu AI tự quyết sai, từ đó hạ xuống Workflow — không chọn Agent chỉ vì nghe "cao cấp" hơn. |
| Decision | Dùng AI để phác thảo pilot plan (đối tượng, cách chạy, số đo) và điều kiện exit/rollback. | Đề xuất hợp lý 3 metric đo được (thời gian, % trích xuất đúng, điểm SUS) và cấu trúc rõ ràng cho bảng Yes/Not Yet/No. | Ngưỡng rollback AI đề xuất ban đầu không thực tế (ví dụ chi phí vận hành quá thấp so với giá API thật). | Điều chỉnh lại ngưỡng rollback (sai số nhận diện thông tin quan trọng >10%, chi phí vận hành vượt 2.000 VNĐ/lượt) dựa trên thảo luận và ước tính thực tế của nhóm. |

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
Khi nghe top 3 problems của Ý, Trang, Hinh và Cường, tôi nhận ra nhóm mình có rất nhiều pain point thật nhưng khác nhau hoàn toàn về độ khả thi trong phạm vi lab: có bài dễ đo (tìm tài liệu, bàn giao công việc) nhưng khó tạo khác biệt, có bài ý nghĩa xã hội lớn (lừa đảo trực tuyến, phân luồng bệnh nhân) nhưng khó kiểm chứng độ chính xác trong thời gian ngắn. Điều đó giúp tôi hiểu candidate "hay" chưa chắc là candidate "chọn được" nếu thiếu bằng chứng đo lường. Về phần mình, tôi đóng góp thật sự nhất ở candidate #10 "thủ tục online cho người lớn tuổi" — đây là problem tôi pitch từ vòng trình bày cá nhân, và dấu tay rõ nhất của tôi trong artifact cuối là phần pilot plan ở Phase 6 (đối tượng 15-20 người 60-75 tuổi, cách chạy Wizard of Oz, 3 metric đo cụ thể). Nhóm có lúc bị kéo về hướng solution-first thật: khi thảo luận mức Rule/Workflow/Agent, gợi ý đầu tiên của AI nghiêng về chọn Agent vì nghe "linh hoạt và hiện đại hơn", nhưng khi tôi và cả nhóm đặt câu hỏi "nếu AI tự nộp hồ sơ sai thông tin định danh thì ai chịu trách nhiệm", cả nhóm mới nhận ra đây là rủi ro pháp lý không chấp nhận được nên hạ xuống Workflow với nguyên tắc human-in-the-loop. Bản thân tôi cũng bị challenge ngược lại đúng vào lỗ hổng của mình: câu hỏi "liệu người già có thực sự muốn dùng voice AI hay chỉ cần giao diện đơn giản hơn là đủ" do chính tôi đặt ra để nhóm mổ xẻ card của mình, và validation bằng khảo sát HUST 2021 sau đó cho thấy pain thật nằm ở thói quen và thiếu hướng dẫn nhiều hơn là thiếu voice interface — nên tôi đã đồng ý sửa Boundary để AI chỉ hỗ trợ giải thích và điền nháp, không tự ý gửi hồ sơ. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở phần Success Metric của PS v0: lúc đó nhóm chấp nhận số liệu ước tính (60-90 phút, 40-50% hồ sơ bị trả) khá nhanh mà chưa có pilot thật nào để đối chiếu, trong khi đây chính là con số quyết định việc so sánh trước/sau có thuyết phục hay không. Lần sau tôi sẽ đề nghị nhóm chạy thử ít nhất 1-2 người thật trước khi chốt PS v1, thay vì chỉ dựa vào secondary data và ước lượng nội bộ.
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