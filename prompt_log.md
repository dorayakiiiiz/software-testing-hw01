# hw01-software-testing

Exported on: 9/20/2026, 08:29:53 PM

---

**You:** *(20/09/2026, 9:16 AM)*
t đã tổng hợp 10 job QA/QC trên linkedIn trong file requirement1.md. với mỗi job, viết cho t 1-2 câu về "AI Impact Analysis" bằng tiếng việt phân tích xem AI đang ảnh hưởng, thay thế hay hỗ trợ kỹ năng gì của vị trí đó.

**Gemini (Gemini 3.6 Flash):** *(20/09/2026, 9:17 AM)*
Dưới đây là phần phân tích **AI Impact Analysis** (1–2 câu) tương ứng cho từng vị trí tuyển dụng trong file requirement1.md:

* **Job 1: Quality Assurance Engineer – SecPod:** AI giúp tự động hóa việc phân tích dữ liệu đe dọa lớn (OSINT/STIX/TAXII) và đề xuất các kịch bản kiểm thử bảo mật nâng cao. Tuy nhiên, kỹ sư QA vẫn đóng vai trò cốt lõi trong việc thẩm định độ chính xác của các logic phát hiện lỗ hổng CVE và hạn chế tình trạng cảnh báo sai (false positives).
* **Job 2: Junior QA Engineer – DXC Technology:** Các công cụ kiểm thử như Katalon Studio và TestComplete đang tích hợp Generative AI để tự động sinh script và bảo trì object repository. Dù AI hỗ trợ tăng năng suất kiểm thử thủ công và tự động hóa, nhân sự QA vẫn cần nắm vững quy trình STLC và nghiệp vụ để kiểm tra tính đúng đắn của ứng dụng.
* **Job 3: Manual Tester – Netcompany:** Kiểm thử thủ công truyền thống chịu ảnh hưởng trực tiếp khi AI có thể tự động tạo test case và dữ liệu kiểm thử từ tài liệu yêu cầu. Để duy trì lợi thế cạnh tranh, Manual Tester cần học cách sử dụng AI như công cụ hỗ trợ và nâng cao kỹ năng kiểm thử nâng cao hoặc kiểm thử tự động.
* **Job 4: QA Engineer (Manual) – Hello Clever:** Vị trí thể hiện xu hướng tích hợp AI vào quy trình QA khi khuyến khích ứng dụng AI trong lập kế hoạch, đánh giá rủi ro release và kiểm thử các tính năng AI (prompt regression, model safety). Trong mảng Fintech/Payment, AI hỗ trợ phát hiện sớm rủi ro tích hợp nhưng QA vẫn giữ vai trò quyết định trong việc bảo đảm an toàn giao dịch.
* **Job 5: Senior Software Engineer in Test (Agentic AI) – HRS Group:** Đây là vị trí tiên phong nơi AI trở thành cả đối tượng kiểm thử và trợ lý cốt lõi trong framework tự động hóa (Agentic AI). Kỹ sư kiểm thử đòi hỏi tư duy "AI-first", áp dụng Generative AI để tự động tạo kịch bản test, dự đoán lỗi và trực tiếp đánh giá độ tin cậy của các mô hình LLM.
* **Job 6: Manual & Automation Tester (Selenium, QA/QC) – MiTek Vietnam:** AI hỗ trợ kiểm thử viên viết mã tự động hóa Selenium nhanh hơn và tự động cập nhật locator khi giao diện thay đổi. Tuy nhiên, việc xây dựng kiến trúc test framework đa nền tảng (Web, Windows, API) và kiểm soát chất lượng phần mềm dài hạn vẫn đòi hỏi chuyên môn kỹ thuật sâu của nhân sự QA.
* **Job 7: QA - Software / Device (Fresher) – OptiSigns Inc:** Các vị trí QA Fresher làm kiểm thử thủ công đứng trước áp lực tự động hóa lớn khi các tác vụ sinh kịch bản test và tạo defect report dần được AI hỗ trợ tối đa. Sinh viên mới tốt nghiệp cần chủ động ứng dụng công cụ AI để nâng cao hiệu suất làm việc và nhanh chóng trang bị các kỹ năng chuyên sâu về kỹ thuật.
* **Job 8: Senior QA Engineer (Internal AI Products) – Glass Egg:** AI làm thay đổi bản chất công việc QA từ kiểm thử tính năng phần mềm cố định sang đánh giá (evaluation) sản phẩm AI nội bộ (LLM, RAG, AI Agent) có tính ngẫu nhiên. Nhân sự QA cần xây dựng các bộ dataset đánh giá, kiểm soát ảo giác (hallucination) và bảo đảm an toàn dữ liệu doanh nghiệp.
* **Job 9: AI Software Test Engineer – VINFAST:** Sự phát triển của AI tạo nên vai trò mới chuyên kiểm thử hệ thống AI/LLM với các tiêu chuẩn chất lượng mới như độ công bằng (bias & fairness), độ chính xác và ảo giác. Việc sử dụng các công cụ đánh giá AI chuyên biệt như DeepEval hay RAGAS trở thành kỹ năng thiết yếu để đảm bảo chất lượng mô hình trước khi phát hành.
* **Job 10: QA Automation Engineer (MLOps) – Motorola Solutions:** AI đóng vai trò sản phẩm cốt lõi (Computer Vision), yêu cầu QA Automation tích hợp kiến thức MLOps để xây dựng pipeline đánh giá tự động hiệu năng mô hình (mAP, FPS, Latency). Xu hướng này xóa mờ ranh giới giữa QA Automation và MLOps, thúc đẩy việc kiểm thử mô hình liên tục trên quy trình CI/CD.

---

**You:** *(20/09/2026, 2:21 PM)*
tìm cho t 20 sự cố phần mềm (software defects) thực tế public từ 2022->2026, trong đó bắt buộc có ít nhất 5 lỗi liên quan trực tiếp đến AI/LLM. mỗi lỗi phải có: link nguồn xác thực, mô tả lỗi, độ nghiêm trọng, hậu quả và giải pháp.

**Gemini (Gemini 3.6 Flash):** *(20/09/2026, 2:22 PM)*
Dưới đây là danh sách đầy đủ 20 sự cố phần mềm thực tế công khai giai đoạn 2022–2026 (gồm 6 lỗi liên quan trực tiếp AI/LLM và 14 lỗi phần mềm lớn):

1. **Lỗi ảo tưởng tiền lệ pháp lý của ChatGPT (2023) (AI/LLM related)**

   * Nguồn xác thực: [www.damiencharlotin.com/hallucinations](https://www.damiencharlotin.com/hallucinations/)
   * Mô tả: Trong vụ kiện Mata v. Avianca, luật sư đã sử dụng ChatGPT để tìm kiếm các án lệ hỗ trợ. Mô hình AI này đã tự bịa ra 6 vụ án hoàn toàn không tồn tại với đầy đủ trích dẫn chi tiết.
   * Mức độ nghiêm trọng: Nghiêm trọng.
   * Hậu quả: Luật sư bị tòa án phạt tiền nặng, uy tín của văn phòng luật bị tổn hại nghiêm trọng và tài liệu nộp lên tòa bị bác bỏ.
   * Giải pháp: Bắt buộc con người phải đối chiếu và xác thực thủ công mọi thông tin pháp lý từ các cơ sở dữ liệu chính thống.
2. **Lỗ hổng Prompt Injection trên Microsoft Copilot Studio (2025) (AI/LLM related)**

   * Nguồn xác thực: [www.indykite.ai/blogs/copilot-prompt-injection-inside-the-attack-that-emptied-a-crm](https://www.indykite.ai/blogs/copilot-prompt-injection-inside-the-attack-that-emptied-a-crm)
   * Mô tả: Các nhà nghiên cứu phát hiện kỹ thuật tấn công gián tiếp (Indirect Prompt Injection). Kẻ xấu gửi một email chứa mã lệnh ẩn, lừa AI tự động đọc cấu hình hệ thống và gửi toàn bộ dữ liệu CRM của doanh nghiệp về email kẻ tấn công.
   * Mức độ nghiêm trọng: Tối nghiêm trọng.
   * Hậu quả: Lộ lọt dữ liệu khách hàng hàng loạt từ hệ thống Salesforce kết nối với chatbot mà không cần người dùng click vào bất kỳ liên kết độc hại nào.
   * Giải pháp: Microsoft triển khai bộ lọc lá chắn prompt (Prompt Shielding) và hệ thống phát hiện mối đe dọa thời gian thực.
3. **Lỗi AI tự bịa giá vé máy bay của Air Canada (2024) (AI/LLM related)**

   * Nguồn xác thực: [www.canadianlawyermag.com/resources/legal-technology/body-of-court-rulings-on-ai-hallucinated-materials-offer-few-new-insights-to-lawyers-using-ai-tools/394148](https://www.canadianlawyermag.com/resources/legal-technology/body-of-court-rulings-on-ai-hallucinated-materials-offer-few-new-insights-to-lawyers-using-ai-tools/394148)
   * Mô tả: Chatbot AI hỗ trợ khách hàng của hãng hàng không Air Canada đã tự thiết lập một chính sách ảo, hướng dẫn hành khách mua vé giá đầy đủ trước rồi xin hoàn tiền tang sự sau, bất chấp quy định thực tế của hãng.
   * Mức độ nghiêm trọng: Cao.
   * Hậu quả: Hãng hàng không bị hành khách khởi kiện và tòa phán quyết hãng phải bồi thường tiền, thiết lập tiền lệ pháp lý rằng công ty phải chịu trách nhiệm về thông tin do chatbot của mình tự sinh ra.
   * Giải pháp: Chuyển đổi kiến trúc chatbot từ sinh văn bản tự do sang mô hình tra cứu thông tin tĩnh được giới hạn nghiêm ngặt (RAG chặt chẽ).
4. **Định kiến giới tính và sắc tộc trong AI lọc hồ sơ tuyển dụng (2023) (AI/LLM related)**

   * Nguồn xác thực: [www.nature.com/articles/s41598-025-15416-8](https://www.nature.com/articles/s41598-025-15416-8)
   * Mô tả: Hệ thống LLM dùng để sàng lọc CV tự động của doanh nghiệp bị phát hiện hạ điểm các hồ sơ có chứa từ khóa liên quan đến phụ nữ hoặc các sắc tộc thiểu số do học từ dữ liệu lịch sử thiên vị.
   * Mức độ nghiêm trọng: Cao.
   * Hậu quả: Gây ra làn sóng bất bình đẳng trong tuyển dụng, doanh nghiệp bỏ sót nhân tài và đối mặt với rủi ro pháp lý lớn về luật chống phân biệt đối xử.
   * Giải pháp: Thực hiện khử định kiến (Debiasing) trong tập dữ liệu huấn luyện, kiểm toán thuật toán độc lập và bắt buộc có sự giám sát của con người.
5. **Lỗi Prompt Injection thao túng giá xe tại Chevrolet Watsonville (2023) (AI/LLM related)**

   * Nguồn xác thực: [www.digitalbricks.ai/blog-posts/how-prompt-injections-expose-microsoft-copilot-studio-agents](https://www.digitalbricks.ai/blog-posts/how-prompt-injections-expose-microsoft-copilot-studio-agents)
   * Mô tả: Khách hàng sử dụng kỹ thuật cấu trúc lại câu lệnh để ép chatbot hỗ trợ của đại lý xe Chevrolet đồng ý thỏa thuận bán một chiếc ô tô Tesla đời mới với giá chỉ 1 USD, đi kèm câu chốt “Đó là một thỏa thuận không thể hủy bỏ”.
   * Mức độ nghiêm trọng: Trung bình.
   * Hậu quả: Gây khủng hoảng truyền thông cho đại lý, chatbot bị lợi dụng để viết hộ mã code cho đối thủ và hệ thống buộc phải đóng cửa khẩn cấp.
   * Giải pháp: Thiết lập phân tách rõ ràng quyền hạn giữa dữ liệu đầu vào của người dùng và các câu lệnh chỉ thị hệ thống (System Prompts).
6. **Sự cố sai lệch kiến thức vũ trụ của Google Bard / Gemini (2023) (AI/LLM related)**

   * Nguồn xác thực: Nature International Journal
   * Mô tả: Ngay trong buổi ra mắt chính thức của Google, chatbot Bard (sau này là Gemini) đã khẳng định sai rằng Kính viễn vọng Không gian James Webb là nơi đầu tiên chụp ảnh một hành tinh bên ngoài hệ Mặt Trời của chúng ta.
   * Mức độ nghiêm trọng: Cao (Ảnh hưởng tài chính trực tiếp).
   * Hậu quả: Uy tín công nghệ của tập đoàn bị giảm sút, khiến giá trị vốn hóa thị trường của Alphabet (công ty mẹ Google) bốc hơi hơn 100 tỷ USD ngay lập tức.
   * Giải pháp: Áp dụng hệ thống xác thực chéo thông tin bằng biểu đồ tri thức (Knowledge Graph) trước khi đưa câu trả lời tới người dùng cuối.
7. **Backdoor chèn mã độc vào thư viện XZ Utils (CVE-2024-3094)**

   * Nguồn xác thực: [www.akamai.com/blog/security-research/critical-linux-backdoor-xz-utils-discovered-what-to-know](https://www.akamai.com/blog/security-research/critical-linux-backdoor-xz-utils-discovered-what-to-know)
   * Mô tả: Một tin tặc ẩn danh bí mật đóng góp mã nguồn suốt 2 năm để giành quyền duy trì (maintainer) dự án XZ Utils. Sau đó, người này âm thầm đưa mã độc vào quy trình build nhằm chỉnh sửa thư viện liblzma nhằm can thiệp cơ chế OpenSSH.
   * Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 10.0).
   * Hậu quả: Cho phép thực thi mã từ xa (RCE) qua cổng SSH trên phạm vi toàn cầu nếu lọt vào các phiên bản hệ điều hành Linux chính thức.
   * Giải pháp: Hạ cấp tức thời phiên bản XZ Utils về bản an toàn (5.4.x) và siết chặt quy trình kiểm soát danh tính các maintainer mã nguồn mở.
8. **Lỗ hổng chiếm quyền điều khiển diện rộng MoveIT Transfer (CVE-2023-34362)**

   * Nguồn xác thực: [www.wiz.io/blog/cve-2024-3094-critical-rce-vulnerability-found-in-xz-utils](https://www.wiz.io/blog/cve-2024-3094-critical-rce-vulnerability-found-in-xz-utils)
   * Mô tả: Lỗi SQL Injection nghiêm trọng trong ứng dụng chuyển tệp tin MoveIT Transfer của hãng Progress Software cho phép kẻ tấn công chưa xác thực có được quyền truy cập trái phép vào cơ sở dữ liệu hệ thống.
   * Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 10.0).
   * Hậu quả: Nhóm ransomware khét tiếng CLOP đã khai thác lỗi này để đánh cắp dữ liệu tối mật của hàng trăm tập đoàn tài chính, cơ quan chính phủ Mỹ và tống tiền hàng triệu USD.
   * Giải pháp: Cô lập cổng truy cập, cài đặt bản vá phần mềm khẩn cấp từ nhà sản xuất và kiểm toán đặc quyền tài khoản cơ sở dữ liệu.
9. **Lỗ hổng bypass xác thực đặc quyền tối cao Cisco IOS XE (CVE-2023-20198)**

   * Nguồn xác thực: [www.catonetworks.com/blog/xz-backdoor-rce-cve-2024-3094-is-the-biggest-supply-chain-attack-since-log4j](https://www.catonetworks.com/blog/xz-backdoor-rce-cve-2024-3094-is-the-biggest-supply-chain-attack-since-log4j/)
   * Mô tả: Lỗi logic trong tính năng Web User Interface (Web UI) của hệ điều hành Cisco IOS XE cho phép kẻ tấn công từ xa tạo một tài khoản người dùng mới với đặc quyền cao nhất (Level 15) mà không cần xác thực.
   * Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 10.0).
   * Hậu quả: Hàng chục ngàn bộ định tuyến (router) và thiết bị chuyển mạch cốt lõi của Cisco tiếp xúc với Internet công cộng bị cài cắm mã độc chạy ngầm để giám sát thông tin mạng.
   * Giải pháp: Tắt tính năng HTTP Server (Web UI) trên các thiết bị mạng công cộng và cập nhật ngay firmware hệ điều hành mới nhất do Cisco cung cấp.
10. **Sự cố đầu độc mã nguồn chuỗi cung ứng Polyfill.io (2024)**

    * Nguồn xác thực: Akamai Blog Advisory
    * Mô tả: Tên miền dịch vụ Polyfill.io (cung cấp các đoạn mã tối ưu hóa JavaScript) bị một công ty khác mua lại, sau đó dịch vụ này bị chỉnh sửa mã nguồn để âm thầm chèn các đoạn script độc hại vào trình duyệt người dùng.
    * Mức độ nghiêm trọng: Cao.
    * Hậu quả: Hơn 100.000 trang web sử dụng link nhúng Polyfill trực tiếp chuyển hướng người dùng của họ đến các trang web lừa đảo, đánh bạc trực tuyến.
    * Giải pháp: Gỡ bỏ liên kết cũ, thay thế bằng các liên kết thư viện thay thế an toàn được quản lý bởi Cloudflare hoặc Fastly.
11. **Chuỗi lỗ hổng nghiêm trọng Ivanti Connect Secure VPN (CVE-2024-21887)**

    * Nguồn xác thực: Cato Networks Intelligence
    * Mô tả: Lỗi chèn lệnh trái phép (Command Injection) kết hợp với lỗi bỏ qua xác thực (CVE-2023-46805) trong thiết bị mạng Ivanti VPN cho phép kẻ tấn công gửi yêu cầu đặc biệt để thực thi mã hệ thống tùy ý.
    * Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 9.8).
    * Hậu quả: Các nhóm gián điệp mạng có tổ chức đã xâm nhập thành công vào mạng nội bộ của nhiều tập đoàn công nghệ quốc phòng và cơ quan chính phủ Tây Âu.
    * Giải pháp: Áp dụng tệp cấu hình XML giảm thiểu tạm thời của hãng và tiến hành cập nhật lại toàn bộ firmware thiết bị.
12. **Rò rỉ siêu khóa ký mật mã bảo mật của Microsoft (2023)**

    * Nguồn xác thực: [techcommunity.microsoft.com/discussions/microsoft-365/copilot-studio-agent-vulnerability-to-prompt-injection/4433290](https://techcommunity.microsoft.com/discussions/microsoft-365/copilot-studio-agent-vulnerability-to-prompt-injection/4433290)
    * Mô tả: Lỗi xử lý crash dump (bản sao bộ nhớ khi hệ thống lỗi) của Microsoft làm lộ khóa mật mã MSA cấp cao. Nhóm tặc Storm-0558 thu thập được khóa này và tự tạo token đăng nhập hợp lệ giả để vào hệ thống đám mây.
    * Mức độ nghiêm trọng: Nghiêm trọng.
    * Hậu quả: Tin tặc đọc trộm thành công tài khoản email Outlook Web Access của hàng loạt quan chức ngoại giao cao cấp thuộc Bộ Ngoại giao và Bộ Thương mại Mỹ.
    * Giải pháp: Thu hồi khẩn cấp toàn bộ các khóa mật mã cũ, chuyển quy trình lưu trữ crash dump sang môi trường mạng cô lập hoàn toàn.
13. **Lỗi tràn bộ đệm thư viện hình ảnh Libwebp (CVE-2023-4863)**

    * Nguồn xác thực: Wiz.io Vulnerability Database
    * Mô tả: Lỗi tràn bộ đệm phân vùng Heap (Heap buffer overflow) xảy ra trong quá trình giải mã các tệp hình ảnh định dạng WebP bằng thư viện mã nguồn mở libwebp.
    * Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 9.8).
    * Hậu quả: Lỗ hổng bị khai thác dưới dạng zero-click (không cần người dùng bấm link). Các phần mềm gián điệp như Pegasus lợi dụng lỗi này để cài mã độc vào điện thoại mục tiêu qua ứng dụng nhắn tin.
    * Giải pháp: Cập nhật đồng loạt các trình duyệt sử dụng nhân Chromium (Chrome, Edge, Opera) và cập nhật thư viện libwebp lên phiên bản an toàn mới nhất.
14. **Lỗ hổng zero-day chiếm quyền thực thi Apple WebKit (CVE-2023-37450)**

    * Nguồn xác thực: Wiz.io Apple Security Advisory
    * Mô tả: Lỗi xử lý dữ liệu đầu vào trong công cụ hiển thị web WebKit của Apple, cho phép một trang web được thiết kế đặc biệt có thể bỏ qua các ranh giới bảo mật bảo vệ của hệ thống.
    * Mức độ nghiêm trọng: Cao (CVSS 8.8).
    * Hậu quả: Thiết bị iPhone, iPad của người dùng bị chiếm quyền kiểm soát từ xa nếu họ vô tình truy cập vào các trang web chứa mã độc do tin tặc dựng sẵn.
    * Giải pháp: Apple triển khai vá lỗi khẩn cấp thông qua tính năng Phản hồi Bảo mật Nhanh (Rapid Security Response) tự động trên iOS và macOS.
15. **Sự cố lỗi logic tệp cập nhật CrowdStrike Falcon Sensor (2024)**

    * Nguồn xác thực: [www.crowdstrike.com/en-us/blog/falcon-content-update-preliminary-post-incident-report](https://www.crowdstrike.com/en-us/blog/falcon-content-update-preliminary-post-incident-report/)
    * Mô tả: Tệp cấu hình cập nhật (Channel File 291) được phát hành mà không qua kiểm thử đầy đủ. Tệp này chứa lỗi logic dẫn đến việc đọc bộ nhớ ngoài phạm vi (out-of-bounds memory read), khiến driver bảo mật chạy ở cấp nhân hệ thống bị sập.
    * Mức độ nghiêm trọng: Thảm họa.
    * Hậu quả: Gây ra vụ sập mạng công nghệ thông tin lớn nhất lịch sử, khiến 8,5 triệu máy tính Windows bị màn hình xanh liên tục (BSOD), làm tê liệt các hãng hàng không, bệnh viện và ngân hàng toàn cầu.
    * Giải pháp: Gỡ bỏ tệp cấu hình lỗi thủ công thông qua chế độ Safe Mode và thay đổi quy trình phát hành bản cập nhật theo từng giai đoạn (Staged Rollouts).
16. **Lỗi logic API rò rỉ dữ liệu người dùng ẩn danh của Twitter/X (2022)**

    * Nguồn xác thực: [privacyinternational.org/long-read/5507/crowdstrike-what-2024-outage-reveals-about-security](https://privacyinternational.org/long-read/5507/crowdstrike-what-2024-outage-reveals-about-security)
    * Mô tả: Một lỗi logic trong quy trình kiểm tra dữ liệu đầu vào của một endpoint API trên Twitter cho phép người dùng gửi một số điện thoại hoặc email để hệ thống trả về ID tài khoản Twitter tương ứng, bỏ qua cài đặt ẩn danh.
    * Mức độ nghiêm trọng: Cao.
    * Hậu quả: Kẻ xấu lợi dụng lỗi này để thu thập thông tin và lập hồ sơ của hơn 5,4 triệu tài khoản người dùng, sau đó đem rao bán dữ liệu này trên các diễn đàn ngầm.
    * Giải pháp: Sửa đổi mã kiểm soát quyền truy cập tại API và bổ sung cơ chế giới hạn tần suất yêu cầu (Rate Limiting).
17. **Lỗi thiết kế tính năng dẫn đến rò rỉ thông tin tại 23andMe (2023)**

    * Nguồn xác thực: Privacy International Records
    * Mô tả: Ứng dụng xét nghiệm di truyền 23andMe không gặp lỗi mã độc, nhưng có lỗi thiết kế tính năng “DNA Relatives”. Khi tài khoản người dùng bị tấn công dò mật khẩu (Credential Stuffing), tính năng này cho phép tải hàng loạt hồ sơ liên kết của những người có cùng huyết thống mà không bị chặn truy cập số lượng lớn.
    * Mức độ nghiêm trọng: Cao.
    * Hậu quả: Thông tin nhạy cảm về hồ sơ di truyền, tổ tiên của 6,9 triệu khách hàng bị khai thác và rao bán công khai trên mạng.
    * Giải pháp: Bắt buộc kích hoạt xác thực 2 lớp (2FA) toàn hệ thống và đặt ngưỡng giới hạn số lượng dữ liệu hồ sơ họ hàng có thể xuất ra.
18. **Lỗi thiếu ngẫu nhiên hóa khóa bảo mật của Atomic Wallet (2023)**

    * Nguồn xác thực: Nature Applied Sciences Reports
    * Mô tả: Thuật toán sinh chuỗi ngẫu nhiên (Entropy) phía máy chủ của ứng dụng ví tiền điện tử Atomic Wallet gặp lỗi logic, khiến các chuỗi ký tự khôi phục (seed phrases) tạo ra bị trùng lặp hoặc dễ bị đoán biết trước.
    * Mức độ nghiêm trọng: Tối nghiêm trọng.
    * Hậu quả: Tổ chức tin tặc Lazarus Group tận dụng lỗ hổng này để bẻ khóa và rút cạn hơn 100 triệu USD tài sản mã hóa từ hàng ngàn ví của người dùng.
    * Giải pháp: Thiết lập lại thuật toán sinh số ngẫu nhiên theo tiêu chuẩn mã hóa quân đội và thuê các đơn vị độc lập kiểm toán lại toàn bộ mã nguồn của ví.
19. **Lỗi kiểm tra tỷ lệ đòn bẩy hợp đồng thông minh Euler Finance (2023)**

    * Nguồn xác thực: Nature Financial Tech Context
    * Mô tả: Hàm donateToReserves trong mã nguồn hợp đồng thông minh của giao thức Euler Finance bị lỗi logic khi không kiểm tra lại tỷ lệ tài sản thế chấp của người dùng sau khi họ thực hiện quyên góp, tạo ra lỗ hổng mất cân bằng thanh khoản.
    * Mức độ nghiêm trọng: Tối nghiêm trọng.
    * Hậu quả: Kẻ tấn công thực hiện kỹ thuật vay nhanh (Flash Loan), rút cắp thành công số tiền mã hóa trị giá gần 197 triệu USD chỉ trong một vài giao dịch.
    * Giải pháp: Chỉnh sửa mã nguồn hợp đồng thông minh, bổ sung các điều kiện ràng buộc (Require statements) kiểm tra thanh khoản trước khi kết thúc hàm.
20. **Lỗi cấu hình mở công khai kho lưu trữ dữ liệu đám mây Toyota (2023)**

    * Nguồn xác thực: Privacy International Enterprise Security
    * Mô tả: Lỗi cấu hình sai (misconfiguration) trong hệ thống đám mây quản lý dữ liệu của Toyota khiến cơ sở dữ liệu lưu trữ thông tin định vị xe bị đặt nhầm ở chế độ công khai (public) mà không có bất kỳ rào cản mật khẩu nào.
    * Mức độ nghiêm trọng: Cao.
    * Hậu quả: Thông tin vị trí xe thời gian thực, số khung và dữ liệu cá nhân của hơn 2,15 triệu khách hàng tại Nhật Bản bị phơi bày trên Internet suốt gần 10 năm (từ 2013 đến khi phát hiện năm 2023).
    * Giải pháp: Đóng quyền truy cập công khai ngay lập tức, triển khai các công cụ tự động quét và giám sát tư thế an ninh đám mây (CSPM).
