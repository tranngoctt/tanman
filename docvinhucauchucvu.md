### Bảng tâm lý cho QA/Tester khi làm việc cùng các vai trò khác

> Gợi ý dùng: trước mỗi cuộc trao đổi, tự hỏi: **“Họ đang cần gì nhất lúc này?”** rồi chọn đúng “món” ở cột cuối.

| STT | Vai trò làm việc cùng | Nhu cầu tâm lý thường gặp | Họ hay “đau” ở điểm nào (dấu hiệu) | Tester có thể “cho” họ (lâu dài) | Tránh làm (dễ phá quan hệ) |
|---:|---|---|---|---|---|
| 1 | **Project Manager (PM)** | **Kiểm soát tiến độ**, giảm rủi ro, báo cáo rõ ràng | Hay hỏi “bao giờ xong?”, sợ trễ deadline | **Update ngắn – đều – có dự báo** (ETA, rủi ro, plan B), **đưa lựa chọn** thay vì than khó | Báo “đến hạn mới nói”, nói mơ hồ “đang test” |
| 2 | **Delivery/Engineering Manager** | **Kết quả**, tính ổn định, hiệu suất đội nhóm | Dị ứng drama, muốn số liệu | **Metrics vừa đủ** (defect trend, escape rate), đề xuất cải tiến “nhẹ mà hiệu quả” | Đổ lỗi cá nhân, phóng đại vấn đề |
| 3 | **Test Lead / QA Lead** | **Chuẩn mực**, sự tin cậy, đồng bộ cách làm | Khó chịu khi thiếu quy trình, thiếu evidence | **Tuân thủ chuẩn** (test note, evidence, naming), chủ động xin review, hỗ trợ mentor | Làm “mỗi người một kiểu”, cãi theo cảm xúc |
| 4 | **Product Owner (PO)** | **Giá trị sản phẩm**, ưu tiên đúng, feedback từ user | Sợ build sai thứ người dùng cần | Báo bug theo **tác động business**, gợi ý **trade-off**, hỗ trợ refine acceptance criteria | Tranh luận “đúng/sai” theo kỹ thuật mà bỏ quên value |
| 5 | **Business Analyst (BA)** | **Rõ ràng yêu cầu**, logic nghiệp vụ, ít hiểu nhầm | Hay bị “yêu cầu mập mờ” | Hỏi “đúng câu hỏi”: **rule/edge case**, viết lại scenario dễ hiểu, confirm bằng ví dụ | Hỏi lan man, hỏi khi đã muộn |
| 6 | **Developer** | **Tập trung**, được tôn trọng chuyên môn, feedback dùng được | Ghét bug report mơ hồ, thiếu repro | Bug report chuẩn: **Steps + Expected/Actual + Env + Logs/Video**, ưu tiên theo severity/impact, **khen đúng chỗ** khi fix nhanh | Chụp mũ “code kém”, spam bug nhỏ không ưu tiên |
| 7 | **Tech Lead / Architect** | **Tính bền vững**, rủi ro hệ thống, quyết định có cơ sở | Quan tâm root cause, độ phủ test | Nói chuyện bằng **risk & evidence**: coverage, flaky rate, boundary; đề xuất test strategy | Kết luận vội, “em nghĩ” không có chứng cứ |
| 8 | **UX/UI Designer** | **Tính nhất quán**, trải nghiệm đúng ý đồ, được ghi nhận | Dễ tổn thương khi bị chê “xấu/khó dùng” | Feedback theo format: **Mục tiêu – quan sát – tác động – gợi ý**, dùng ảnh so sánh, tôn trọng guideline | Chê cảm tính, “xấu quá” “khó chịu” |
| 9 | **DevOps/SRE** | **Ổn định hệ thống**, ít incident, rõ nguyên nhân | Dị ứng request mơ hồ, thiếu thời điểm/log | Khi có lỗi môi trường: gửi **timestamp + request id + env + log**, phối hợp “triage 10 phút” | Đổ lỗi hạ tầng khi chưa kiểm tra |
| 10 | **Scrum Master/Agile Coach** | **Hợp tác**, minh bạch, team flow | Lo team “kẹt” vì giao tiếp tệ | Tham gia retro có chất lượng: nêu **1 vấn đề – 1 đề xuất**, giúp unblock, chia sẻ learning | Than vãn không giải pháp, công kích cá nhân |
| 11 | **Customer Support / CS** | **Giảm phàn nàn**, câu trả lời nhanh, dễ giải thích | Bị khách dí, stress cao | Cho họ **workaround**, status rõ ràng, FAQ ngắn, phân loại mức độ ảnh hưởng | “Không phải lỗi em”, hoặc im lặng lâu |
| 12 | **Stakeholder/Client** | **Niềm tin**, cảm giác được chăm sóc, ít bất ngờ | Sợ “đưa lên rồi chết” | Báo cáo theo ngôn ngữ họ hiểu: **rủi ro – tác động – kế hoạch**, demo evidence, nói thẳng nhưng mềm | Hứa quá tay, nói kỹ thuật khó hiểu |
| 13 | **Junior QA/Intern** | **An toàn tâm lý**, được hướng dẫn, được công nhận | Sợ hỏi, sợ sai | Tạo “không gian hỏi”: checklist, template, pair test 30’, khen nỗ lực + chỉnh đúng | Mắng kiểu “sao cái này cũng không biết” |
| 14 | **Security/Compliance** | **An toàn**, tuân thủ, dấu vết kiểm chứng | Lo rò rỉ dữ liệu, audit | Gắn test vào **risk/security** (PII, permission), lưu evidence, báo sớm | Xem nhẹ quy trình, thiếu ghi chép |

### Bảng “đọc vị” nhà tuyển dụng (QA / Manual / Automation) khi phỏng vấn

> Mục tiêu: hiểu **họ thật sự cần gì**, biết **họ hài lòng vì điều gì**, và chuẩn bị đúng “món” để đưa ra trong interview.

| STT | “Nhà tuyển dụng” thực chất là ai? | Nhu cầu tâm lý thường gặp | Yêu cầu/tiêu chí họ hay dùng để lọc | Mức độ hài lòng của họ tăng mạnh khi… | Ứng viên (em) có thể “cho” họ |
|---:|---|---|---|---|---|
| 1 | **HR / Talent Acquisition (TA)** | **Giảm rủi ro tuyển sai**, chốt nhanh, ứng viên hợp tác | CV rõ ràng, job-hop ít/giải thích hợp lý, giao tiếp lịch sự, thái độ tốt | Em **đúng “form”**: trả lời gọn, đúng trọng tâm, phản hồi nhanh, giấy tờ/khung lương rõ | **CV 1 trang chuẩn**, tóm tắt 30s, khung lương hợp lý, lịch phỏng vấn linh hoạt, follow-up lịch sự |
| 2 | **Hiring Manager (QA Manager/Eng Manager)** | **Tuyển người “làm được việc”**, tự chủ, đỡ tốn công kèm | Nền tảng testing vững, tư duy hệ thống, ưu tiên/risk-based, ownership | Em nói được **em đã làm gì – đo bằng gì – tác động ra sao** | Kể 2–3 case “đã cứu dự án” (bug critical, giảm defect escape, cải tiến process), thể hiện ownership |
| 3 | **QA Lead / Test Lead** | **Chuẩn hoá quy trình**, chất lượng evidence, teamwork | Viết test case/bug chuẩn, traceability, report, test strategy | Em có **kỷ luật nghề QA** + biết phối hợp Dev/BA/PO | Đưa **template** (bug report chuẩn, test checklist), nêu cách em quản lý test theo rủi ro |
| 4 | **Senior QA / Interview panel** | **Tìm người có tư duy**, chịu học, phản biện tốt | How-to breakdown feature, edge case, boundary, concurrency, data | Em không chỉ “biết” mà **giải thích được logic** | Trả lời theo khung: **Context → Approach → Example → Trade-off**; hỏi ngược câu chất lượng |
| 5 | **Developer/Tech interviewer** | **Giảm ma sát**, tester biết “nói chuyện kỹ thuật” | API basics, SQL cơ bản, log, repro rõ, hiểu CI/CD ở mức cần thiết | Em đưa bug mà Dev **fix được ngay** | Demo cách em debug: network tab, log, isolate, minimal repro; nói ngôn ngữ “signal” |
| 6 | **Automation Lead / SDET Lead** | **Test automation chạy ổn**, ít flaky, maintainable | Framework, locator strategy, POM, reporting, CI, test data, waits | Em chứng minh được **thiết kế + chống flaky** | Trình bày 1 mini-architecture Playwright: structure, fixtures, tags, retry, trace, report |
| 7 | **CTO/Head of Engineering (nếu có)** | **Tốc độ + chất lượng**, người đáng tin, mindset dài hạn | Tư duy sản phẩm, ưu tiên, cải tiến, ownership | Em nói được **roadmap nâng chất lượng** 30-60-90 ngày | Đưa plan 30-60-90: quick wins, test strategy, metrics, automation coverage |
| 8 | **Startup founder (công ty nhỏ)** | **Một người làm được nhiều**, linh hoạt, chịu áp lực | Hands-on, tự học, xử lý việc “lộn xộn” | Em chủ động, không kén việc, **đưa giải pháp** | Nêu ví dụ em tự build process: checklist release, smoke, regression, bug triage |
| 9 | **Enterprise/Ngân hàng (quy trình nặng)** | **Tuân thủ, audit**, documentation, ổn định | Test plan, evidence, sign-off, quy trình change/release | Em có thói quen **lưu vết** và làm việc chuẩn | Nêu cách em quản lý test artifacts, traceability, test report, quy trình UAT |
| 10 | **Khách hàng/Stakeholder nội bộ** | **Không bị “bất ngờ”**, chất lượng ổn | Báo cáo dễ hiểu, risk rõ, status minh bạch | Em giúp họ **yên tâm** bằng dự báo và minh chứng | Em trình bày status theo business: impact, risk, mitigation, timeline |
| 11 | **Team tương lai (peer)** | **Dễ làm cùng**, không toxic, biết hỗ trợ | Giao tiếp, chia sẻ, nhận feedback | Em hòa nhập nhanh, biết tự học và hỗ trợ | Thể hiện teamwork: pair testing, review chéo, chia sẻ template, retro góp ý có giải pháp |
| 12 | **Bản thân “công ty” (ẩn sau JD)** | **Giảm chi phí sai lầm**, tăng chất lượng release | Người ổn định, học nhanh, phù hợp văn hoá | Em fit văn hoá + có “động cơ” rõ ràng | Nói rõ động cơ: muốn làm QA dài hạn, thích chất lượng, thích hệ thống hoá, mục tiêu học |

---

## “Mức độ hài lòng” của nhà tuyển dụng thường đến từ 6 điểm chốt
1. **Clarity:** Em nói rõ mình làm được gì (không vòng vo).
2. **Evidence:** Có ví dụ thật (bug thật / dự án thật / metric hoặc kết quả).
3. **Ownership:** Có tinh thần nhận việc tới nơi tới chốn.
4. **Communication:** Viết bug/report dễ hiểu, phối hợp tốt.
5. **Risk mindset:** Biết ưu tiên, biết đánh đổi theo deadline.
6. **Growth:** Học nhanh, biết tự nâng trình (đặc biệt automation).

---

## Checklist “món quà” em nên mang vào phòng phỏng vấn (QA/Automation)
- 01 câu **giới thiệu 30 giây** (ai – mạnh gì – muốn gì).
- 02 câu chuyện **STAR** (Situation–Task–Action–Result) về:
  - 1 bug nghiêm trọng/incident em phát hiện hoặc ngăn chặn
  - 1 lần em cải tiến quy trình/test để giảm rủi ro
- 01 ví dụ **bug report chuẩn** (có steps, env, evidence).
- (Nếu automation) 01 sơ đồ **structure** project Playwright (tests/fixtures/pages/utils/reporting/CI).
- 03 câu hỏi ngược “đẹp”:
  - Tiêu chí “pass probation” của role này là gì?
  - Hiện team đang đau nhất về quality ở khâu nào?
  - Release cadence và cách triage bug đang vận hành ra sao?

---
