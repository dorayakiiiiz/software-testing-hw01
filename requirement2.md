1. Lỗi ảo tưởng tiền lệ pháp lý của ChatGPT (2023) (AI/LLM related)
-	Nguồn xác thực: https://www.reuters.com/legal/new-york-lawyers-sanctioned-using-fake-chatgpt-cases-legal-brief-2023-06-22/
-	Mô tả: Trong vụ kiện Mata v. Avianca, luật sư đã sử dụng ChatGPT để tìm kiếm các án lệ hỗ trợ. Mô hình AI này đã tự bịa ra 6 vụ án hoàn toàn không tồn tại với đầy đủ trích dẫn chi tiết. 
-	Mức độ nghiêm trọng: Nghiêm trọng.
-	Hậu quả: Luật sư bị tòa án phạt tiền nặng, uy tín của văn phòng luật bị tổn hại nghiêm trọng và tài liệu nộp lên tòa bị bác bỏ. 
-	Giải pháp: Bắt buộc con người phải đối chiếu và xác thực thủ công mọi thông tin pháp lý từ các cơ sở dữ liệu chính thống. 
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường ảo tưởng rằng luật sư đã cố tình cài mã độc hoặc hack vào máy chủ tòa án thông qua ChatGPT, thay vì chỉ đơn thuần là sao chép văn bản thô do AI sinh ra. 
2. Lỗ hổng Prompt Injection trên Microsoft Copilot Studio (2025) (AI/LLM related)
-	Nguồn xác thực: https://labs.zenity.io/post/a-copilot-studio-story-discovery-phase-in-ai-agents-f917
-	Mô tả: Các nhà nghiên cứu phát hiện kỹ thuật tấn công gián tiếp (Indirect Prompt Injection). Kẻ xấu gửi một email chứa mã lệnh ẩn, lừa AI tự động đọc cấu hình hệ thống và gửi toàn bộ dữ liệu CRM của doanh nghiệp về email kẻ tấn công.
-	Mức độ nghiêm trọng: Tối nghiêm trọng.
-	Hậu quả: Lộ lọt dữ liệu khách hàng hàng loạt từ hệ thống Salesforce kết nối với chatbot mà không cần người dùng click vào bất kỳ liên kết độc hại nào.
-	Giải pháp: Microsoft triển khai bộ lọc lá chắn prompt (Prompt Shielding) và hệ thống phát hiện mối đe dọa thời gian thực.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường nhầm lẫn giữa Microsoft Copilot Studio với GitHub Copilot, từ đó ảo tưởng rằng lỗ hổng này làm rò rỉ mã nguồn dự án riêng tư của các lập trình viên trên GitHub. 
3. Lỗi AI tự bịa giá vé máy bay của Air Canada (2024) (AI/LLM related)
-	Nguồn xác thực: https://www.cbc.ca/news/canada/british-columbia/air-canada-chatbot-lawsuit-1.7116416
-	Mô tả: Chatbot AI hỗ trợ khách hàng của hãng hàng không Air Canada đã tự thiết lập một “chính sách ảo tưởng”, hướng dẫn hành khách mua vé giá đầy đủ trước rồi xin hoàn tiền tang sự (bereavement fare) sau, bất chấp quy định thực tế của hãng.
-	Mức độ nghiêm trọng: Cao.
-	Hậu quả: Hãng hàng không bị hành khách khởi kiện và tòa phán quyết hãng phải bồi thường tiền, thiết lập tiền lệ pháp lý rằng công ty phải chịu trách nhiệm về thông tin do chatbot của mình tự bịa ra.
-	Giải pháp: Chuyển đổi kiến trúc chatbot từ sinh văn bản tự do sang mô hình tra cứu thông tin tĩnh được giới hạn nghiêm ngặt (RAG chặt chẽ).
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường thể hiện xu hướng ảo tưởng rằng cơ sở dữ liệu trung tâm của Air Canada đã bị tin tặc tấn công và chỉnh sửa bảng giá vé, thay vì thừa nhận lỗi nằm ở thuật toán sinh chữ ngẫu nhiên của mô hình ngôn ngữ. 
4. Định kiến giới tính và sắc tộc trong AI lọc hồ sơ tuyển dụng (2023) (AI/LLM related)
-	Nguồn xác thực: https://www.sullcrom.com/insights/blogs/2023/August/EEOC-Settles-First-AI-Discrimination-Lawsuit
-	Mô tả: Hệ thống LLM dùng để sàng lọc CV tự động của doanh nghiệp bị phát hiện hạ điểm các hồ sơ có chứa từ khóa liên quan đến phụ nữ hoặc các sắc tộc thiểu số do học từ dữ liệu lịch sử thiên vị.
-	Mức độ nghiêm trọng: Cao.
-	Hậu quả: Gây ra làn sóng bất bình đẳng trong tuyển dụng, doanh nghiệp bỏ sót nhân tài và đối mặt với rủi ro pháp lý lớn về luật chống phân biệt đối xử.
-	Giải pháp: Thực hiện khử định kiến (Debiasing) trong tập dữ liệu huấn luyện, kiểm toán thuật toán độc lập và bắt buộc có sự giám sát của con người.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường xuất hiện định kiến “đổ lỗi cho lập trình viên”, khẳng định đội ngũ kỹ sư cố ý viết code phân biệt chủng tộc, thay vì giải thích đúng bản chất lỗi là do mô hình tự học sự mất cân bằng từ dữ liệu lịch sử. 
5. Lỗi Prompt Injection thao túng giá xe tại Chevrolet Watsonville (2023) (AI/LLM related)
-	Nguồn xác thực: https://medium.com/@celestineriza/the-day-chevrolets-ai-chatbot-tried-to-sell-a-70-000-suv-for-1-29f4a1e954d9
-	Mô tả: Khách hàng sử dụng kỹ thuật cấu trúc lại câu lệnh để ép chatbot hỗ trợ của đại lý xe Chevrolet đồng ý thỏa thuận bán một chiếc ô tô Tesla đời mới với giá chỉ 1 USD, đi kèm câu chốt “Đó là một thỏa thuận không thể hủy bỏ”.
-	Mức độ nghiêm trọng: Trung bình.
-	Hậu quả: Gây khủng hoảng truyền thông cho đại lý, chatbot bị lợi dụng để viết hộ mã code cho đối thủ và hệ thống buộc phải đóng cửa khẩn cấp.
-	Giải pháp: Thiết lập phân tách rõ ràng quyền hạn giữa dữ liệu đầu vào của người dùng và các câu lệnh chỉ thị hệ thống (System Prompts).
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường ảo tưởng rằng giao dịch 1 USD này đã được hoàn tất trên hệ thống ngân hàng pháp lý thành công và khách hàng đã thực sự lái chiếc xe Tesla đó về nhà. 
6. Sự cố sai lệch kiến thức vũ trụ của Google Bard / Gemini (2023) (AI/LLM related)
-	Nguồn xác thực: https://www.reuters.com/technology/google-ai-chatbot-bard-offers-inaccurate-information-company-ad-2023-02-08/
-	Mô tả: Ngay trong buổi ra mắt chính thức của Google, chatbot Bard (sau này là Gemini) đã khẳng định sai rằng Kính viễn vọng Không gian James Webb là nơi đầu tiên chụp ảnh một hành tinh bên ngoài hệ Mặt Trời của chúng ta.
-	Mức độ nghiêm trọng: Cao (Ảnh hưởng tài chính trực tiếp).
-	Hậu quả: Uy tín công nghệ của tập đoàn bị giảm sút, khiến giá trị vốn hóa thị trường của Alphabet (công ty mẹ Google) bốc hơi hơn 100 tỷ USD ngay lập tức.
-	Giải pháp: Áp dụng hệ thống xác thực chéo thông tin bằng biểu đồ tri thức (Knowledge Graph) trước khi đưa câu trả lời tới người dùng cuối.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI khi giải thích lỗi này thường bị nhầm lẫn dòng thời gian, khẳng định sự cố xảy ra vào năm 2025 hoặc đổ lỗi cho kính viễn vọng Hubble gặp trục trặc kỹ thuật. 
7. Backdoor chèn mã độc vào thư viện XZ Utils (CVE-2024-3094)
-	Nguồn xác thực: https://vngcloud.vn/en/cve-2024-3094-reported-supply-chain-compromise-affecting-xz-utils-data-compression-library
-	Mô tả: Một tin tặc ẩn danh bí mật đóng góp mã nguồn suốt 2 năm để giành quyền duy trì (maintainer) dự án XZ Utils. Sau đó, người này âm thầm đưa mã độc vào quy trình build nhằm chỉnh sửa thư viện liblzma nhằm can thiệp cơ chế OpenSSH.
-	Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 10.0).
-	Hậu quả: Cho phép thực thi mã từ xa (RCE) qua cổng SSH trên phạm vi toàn cầu nếu lọt vào các phiên bản hệ điều hành Linux chính thức.
-	Giải pháp: Hạ cấp tức thời phiên bản XZ Utils về bản an toàn (5.4.x) và siết chặt quy trình kiểm soát danh tính các maintainer mã nguồn mở.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường ảo tưởng lỗi này trực tiếp lây nhiễm và mã hóa tống tiền (Ransomware) trên các máy tính sử dụng Windows 11 cá nhân, mặc dù đây là lỗ hổng nhắm vào kiến trúc máy chủ Linux x86-64. 
8. Lỗ hổng chiếm quyền điều khiển diện rộng MoveIT Transfer (CVE-2023-34362)
-	Nguồn xác thực: https://nvd.nist.gov/vuln/detail/cve-2023-34362
-	Mô tả: Lỗi SQL Injection nghiêm trọng trong ứng dụng chuyển tệp tin MoveIT Transfer của hãng Progress Software cho phép kẻ tấn công chưa xác thực có được quyền truy cập trái phép vào cơ sở dữ liệu hệ thống.
-	Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 10.0).
-	Hậu quả: Nhóm ransomware khét tiếng CLOP đã khai thác lỗi này để đánh cắp dữ liệu tối mật của hàng trăm tập đoàn tài chính, cơ quan chính phủ Mỹ và tống tiền hàng triệu USD.
-	Giải pháp: Cô lập cổng truy cập, cài đặt bản vá phần mềm khẩn cấp từ nhà sản xuất và kiểm toán đặc quyền tài khoản cơ sở dữ liệu.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường bị nhầm lẫn sâu sắc về mặt thông tin, tự động khẳng định nhóm hacker thực hiện vụ tấn công này là LockBit thay vì nhóm CLOP.
9. Lỗ hổng bypass xác thực đặc quyền tối cao Cisco IOS XE (CVE-2023-20198)
-	Nguồn xác thực: https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-iosxe-webui-privesc-j22SaA4z
-	Mô tả: Lỗi logic trong tính năng Web User Interface (Web UI) của hệ điều hành Cisco IOS XE cho phép kẻ tấn công từ xa tạo một tài khoản người dùng mới với đặc quyền cao nhất (Level 15) mà không cần xác thực.
-	Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 10.0).
-	Hậu quả: Hàng chục ngàn bộ định tuyến (router) và thiết bị chuyển mạch cốt lõi của Cisco tiếp xúc với Internet công cộng bị cài cắm mã độc chạy ngầm để giám sát thông tin mạng.
-	Giải pháp: Tắt tính năng HTTP Server (Web UI) trên các thiết bị mạng công cộng và cập nhật ngay firmware hệ điều hành mới nhất do Cisco cung cấp.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI có xu hướng ảo tưởng rằng lỗ hổng này nằm trên các dòng điện thoại thông minh chạy hệ điều hành iOS của Apple do sự trùng lặp ký tự giữa “IOS XE” và “iOS”. 
10. Sự cố đầu độc mã nguồn chuỗi cung ứng Polyfill.io (2024)
-	Nguồn xác thực: https://blog.cloudflare.com/automatically-replacing-polyfill-io-links-with-cloudflares-mirror-for-a-safer-internet/
-	Mô tả: Tên miền dịch vụ Polyfill.io (cung cấp các đoạn mã tối ưu hóa JavaScript) bị một công ty khác mua lại, sau đó dịch vụ này bị chỉnh sửa mã nguồn để âm thầm chèn các đoạn script độc hại độc hại vào trình duyệt người dùng.
-	Mức độ nghiêm trọng: Cao.
-	Hậu quả: Hơn 100.000 trang web sử dụng link nhúng Polyfill trực tiếp chuyển hướng người dùng của họ đến các trang web lừa đảo, đánh bạc trực tuyến.
-	Giải pháp: Gỡ bỏ liên kết cũ, thay thế bằng các liên kết thư viện thay thế an toàn được quản lý bởi Cloudflare hoặc Fastly.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường mắc lỗi định kiến lớn khi tự lập luận khẳng định Cloudflare là bên đứng sau thực hiện vụ đầu độc này nhằm mục đích cạnh tranh không lành mạnh và ép các trang web phải chuyển sang dùng dịch vụ của mình. 
11. Chuỗi lỗ hổng nghiêm trọng Ivanti Connect Secure VPN (CVE-2024-21887)
-	Nguồn xác thực: https://hub.ivanti.com/s/article/CVE-2023-46805-Authentication-Bypass-CVE-2024-21887-Command-Injection-for-Ivanti-Connect-Secure-and-Ivanti-Policy-Secure-Gateways?language=en_US
-	Mô tả: Lỗi chèn lệnh trái phép (Command Injection) kết hợp với lỗi bỏ qua xác thực (CVE-2023-46805) trong thiết bị mạng Ivanti VPN cho phép kẻ tấn công gửi yêu cầu đặc biệt để thực thi mã hệ thống tùy ý.
-	Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 9.8).
-	Hậu quả: Các nhóm gián điệp mạng có tổ chức đã xâm nhập thành công vào mạng nội bộ của nhiều tập đoàn công nghệ quốc phòng và cơ quan chính phủ Tây Âu.
-	Giải pháp: Áp dụng tệp cấu hình XML giảm thiểu tạm thời của hãng và tiến hành cập nhật lại toàn bộ firmware thiết bị.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường bị ảo tưởng bản chất phần cứng, giải thích lỗi này như một lỗ hổng ứng dụng di động thông thường cài đặt từ Google Play Store thay vì thiết bị Gateway VPN chuyên dụng. 
12. Rò rỉ siêu khóa ký mật mã bảo mật của Microsoft (2023)
-	Nguồn xác thực: https://www.microsoft.com/en-us/security/blog/2023/07/14/analysis-of-storm-0558-techniques-for-unauthorized-email-access/
-	Mô tả: Lỗi xử lý crash dump (bản sao bộ nhớ khi hệ thống lỗi) của Microsoft làm lộ khóa mật mã MSA cấp cao. Nhóm tặc Storm-0558 thu thập được khóa này và tự tạo token đăng nhập hợp lệ giả để vào hệ thống đám mây.
-	Mức độ nghiêm trọng: Nghiêm trọng.
-	Hậu quả: Tin tặc đọc trộm thành công tài khoản email Outlook Web Access của hàng loạt quan chức ngoại giao cao cấp thuộc Bộ Ngoại giao và Bộ Thương mại Mỹ.
-	Giải pháp: Thu hồi khẩn cấp toàn bộ các khóa mật mã cũ, chuyển quy trình lưu trữ crash dump sang môi trường mạng cô lập hoàn toàn.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: Do có xu hướng thiên vị bảo vệ các hãng công nghệ lớn, AI thường giải thích theo hướng giảm nhẹ lỗi hệ thống và đổ lỗi định kiến rằng các quan chức chính phủ bị lộ email là vì đặt mật khẩu quá yếu (như “123456”). 
13. Lỗi tràn bộ đệm thư viện hình ảnh Libwebp (CVE-2023-4863)
-	Nguồn xác thực: https://www.huntress.com/blog/critical-vulnerability-webp-heap-buffer-overflow-cve-2023-4863
-	Mô tả: Lỗi tràn bộ đệm phân vùng Heap (Heap buffer overflow) xảy ra trong quá trình giải mã các tệp hình ảnh định dạng WebP bằng thư viện mã nguồn mở libwebp.
-	Mức độ nghiêm trọng: Tối nghiêm trọng (CVSS 9.8).
-	Hậu quả: Lỗ hổng bị khai thác dưới dạng zero-click (không cần người dùng bấm link). Các phần mềm gián điệp như Pegasus lợi dụng lỗi này để cài mã độc vào điện thoại mục tiêu qua ứng dụng nhắn tin.
-	Giải pháp: Cập nhật đồng loạt các trình duyệt sử dụng nhân Chromium (Chrome, Edge, Opera) và cập nhật thư viện libwebp lên phiên bản an toàn mới nhất.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường ảo tưởng lỗi này chỉ liên quan đến định dạng ảnh cổ điển .JPEG và khẳng định các tệp ảnh .WebP do Google thiết kế là miễn nhiễm hoàn toàn với lỗi tràn bộ đệm. 
14. Lỗ hổng zero-day chiếm quyền thực thi Apple WebKit (CVE-2023-37450)
-	Nguồn xác thực: https://support.apple.com/en-us/102844
-	Mô tả: Lỗi xử lý dữ liệu đầu vào trong công cụ hiển thị web WebKit của Apple, cho phép một trang web được thiết kế đặc biệt có thể bỏ qua các ranh giới bảo mật bảo vệ của hệ thống.
-	Mức độ nghiêm trọng: Cao (CVSS 8.8).
-	Hậu quả: Thiết bị iPhone, iPad của người dùng bị chiếm quyền kiểm soát từ xa nếu họ vô tình truy cập vào các trang web chứa mã độc do tin tặc dựng sẵn.
-	Giải pháp: Apple triển khai vá lỗi khẩn cấp thông qua tính năng Phản hồi Bảo mật Nhanh (Rapid Security Response) tự động trên iOS và macOS.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường ảo tưởng dòng sản phẩm, khẳng định lỗ hổng này chỉ xuất hiện trên các máy nghe nhạc iPod cổ hoặc iPhone đời đầu đã bị Apple khai tử từ lâu. 
15. Sự cố lỗi logic tệp cập nhật CrowdStrike Falcon Sensor (2024)
-	Nguồn xác thực: https://www.crowdstrike.com/en-us/blog/falcon-content-update-preliminary-post-incident-report/
-	Mô tả: Tệp cấu hình cập nhật (Channel File 291) được phát hành mà không qua kiểm thử đầy đủ. Tệp này chứa lỗi logic dẫn đến việc đọc bộ nhớ ngoài phạm vi (out-of-bounds memory read), khiến driver bảo mật chạy ở cấp nhân hệ thống bị sập.
-	Mức độ nghiêm trọng: Thảm họa.
-	Hậu quả: Gây ra vụ sập mạng công nghệ thông tin lớn nhất lịch sử, khiến 8,5 triệu máy tính Windows bị màn hình xanh liên tục (BSOD), làm tê liệt các hãng hàng không, bệnh viện và ngân hàng toàn cầu.
-	Giải pháp: Gỡ bỏ tệp cấu hình lỗi thủ công thông qua chế độ Safe Mode và thay đổi quy trình phát hành bản cập nhật theo từng giai đoạn (Staged Rollouts).
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường bị ảo tưởng trầm trọng và khẳng định sự cố này là một cuộc tấn công từ chối dịch vụ (DDoS) quy mô toàn cầu do một tổ chức tin tặc nhà nước thực hiện, bất chấp thực tế đây hoàn toàn là lỗi kiểm thử nội bộ. 
16. Lỗi logic API rò rỉ dữ liệu người dùng ẩn danh của Twitter/X (2022)
-	Nguồn xác thực: https://purplesec.us/breach-report/twitter-zero-day/
-	Mô tả: Một lỗi logic trong quy trình kiểm tra dữ liệu đầu vào của một endpoint API trên Twitter cho phép người dùng gửi một số điện thoại hoặc email để hệ thống trả về ID tài khoản Twitter tương ứng, bỏ qua cài đặt ẩn danh.
-	Mức độ nghiêm trọng: Cao.
-	Hậu quả: Kẻ xấu lợi dụng lỗi này để thu thập thông tin và lập hồ sơ của hơn 5,4 triệu tài khoản người dùng, sau đó đem rao bán dữ liệu này trên các diễn đàn ngầm.
-	Giải pháp: Sửa đổi mã kiểm soát quyền truy cập tại API và bổ sung cơ chế giới hạn tần suất yêu cầu (Rate Limiting).
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường bị ảo tưởng thời gian và cấu trúc quản lý, tự động gắn sự cố này diễn ra vào giai đoạn sau khi Elon Musk tiếp quản mạng xã hội X, dù thực tế lỗi xuất hiện và bị khai thác dưới thời ban điều hành Twitter cũ. 
17. Lỗi thiết kế tính năng dẫn đến rò rỉ thông tin tại 23andMe (2023)
-	Nguồn xác thực: https://techcrunch.com/2023/10/18/hacker-leaks-millions-more-23andme-user-records-on-cybercrime-forum/
-	Mô tả: Ứng dụng xét nghiệm di truyền 23andMe không gặp lỗi mã độc, nhưng có lỗi thiết kế tính năng “DNA Relatives”. Khi tài khoản người dùng bị tấn công dò mật khẩu (Credential Stuffing), tính năng này cho phép tải hàng loạt hồ sơ liên kết của những người có cùng huyết thống mà không bị chặn chặn truy cập số lượng lớn.
-	Mức độ nghiêm trọng: Cao.
-	Hậu quả: Thông tin nhạy cảm về hồ sơ di truyền, tổ tiên của 6,9 triệu khách hàng bị khai thác và rao bán công khai trên mạng.
-	Giải pháp: Bắt buộc kích hoạt xác thực 2 lớp (2FA) toàn hệ thống và đặt ngưỡng giới hạn số lượng dữ liệu hồ sơ họ hàng có thể xuất ra.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường ảo tưởng theo hướng kỹ thuật phức tạp, giải thích lỗi này xảy ra do tin tặc đã bẻ khóa thành công thuật toán mã hóa AES-256 bảo vệ cơ sở dữ liệu gốc của công ty. 
18. Lỗi thiếu ngẫu nhiên hóa khóa bảo mật của Atomic Wallet (2023)
-	Nguồn xác thực: https://brownrudnick.com/client_news/brown-rudnick-wins-dismissal-of-class-action-suit-against-atomic-wallet-over-100m-hack/
-	Mô tả: Thuật toán sinh chuỗi ngẫu nhiên (Entropy) phía máy chủ của ứng dụng ví tiền điện tử Atomic Wallet gặp lỗi logic, khiến các chuỗi ký tự khôi phục (seed phrases) tạo ra bị trùng lặp hoặc dễ bị đoán biết trước.
-	Mức độ nghiêm trọng: Tối nghiêm trọng.
-	Hậu quả: Tổ chức tin tặc Lazarus Group tận dụng lỗ hổng này để bẻ khóa và rút cạn hơn 100 triệu USD tài sản mã hóa từ hàng ngàn ví của người dùng.
-	Giải pháp: Thiết lập lại thuật toán sinh số ngẫu nhiên theo tiêu chuẩn mã hóa quân đội và thuê các đơn vị độc lập kiểm toán lại toàn bộ mã nguồn của ví.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường bộc lộ định kiến phân biệt quốc gia khi khẳng định vô căn cứ rằng tất cả các kỹ sư phần mềm của Atomic Wallet đều là gián điệp nằm vùng cố tình viết lỗi để đánh cắp tiền. 
19. Lỗi kiểm tra tỷ lệ đòn bẩy hợp đồng thông minh Euler Finance (2023)
-	Nguồn xác thực: https://www.chainalysis.com/blog/euler-finance-flash-loan-attack/
-	Mô tả: Hàm donateToReserves trong mã nguồn hợp đồng thông minh của giao thức Euler Finance bị lỗi logic khi không kiểm tra lại tỷ lệ tài sản thế chấp của người dùng sau khi họ thực hiện quyên góp, tạo ra lỗ hổng mất cân bằng thanh khoản.
-	Mức độ nghiêm trọng: Tối nghiêm trọng.
-	Hậu quả: Kẻ tấn công thực hiện kỹ thuật vay nhanh (Flash Loan), rút cắp thành công số tiền mã hóa trị giá gần 197 triệu USD chỉ trong một vài giao dịch.
-	Giải pháp: Chỉnh sửa mã nguồn hợp đồng thông minh, bổ sung các điều kiện ràng buộc (Require statements) kiểm tra thanh khoản trước khi kết thúc hàm.
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường ảo tưởng nguyên nhân khách quan, giải thích rằng lỗi này phát sinh do toàn bộ mạng lưới blockchain Ethereum bị sập cục bộ chứ không phải do lỗi viết code sai của lập trình viên Euler Finance. 
20. Lỗi cấu hình mở công khai kho lưu trữ dữ liệu đám mây Toyota (2023)
-	Nguồn xác thực: https://cloudsecurityalliance.org/blog/2025/07/21/reflecting-on-the-2023-toyota-data-breach
-	Mô tả: Lỗi cấu hình sai (misconfiguration) trong hệ thống đám mây quản lý dữ liệu của Toyota khiến cơ sở dữ liệu lưu trữ thông tin định vị xe bị đặt nhầm ở chế độ công khai (public) mà không có bất kỳ rào cản mật khẩu nào.
-	Mức độ nghiêm trọng: Cao.
-	Hậu quả: Thông tin vị trí xe thời gian thực, số khung và dữ liệu cá nhân của hơn 2,15 triệu khách hàng tại Nhật Bản bị phơi bày trên Internet suốt gần 10 năm (từ 2013 đến khi phát hiện năm 2023).
-	Giải pháp: Đóng quyền truy cập công khai ngay lập tức, triển khai các công cụ tự động quét và giám sát tư thế an ninh đám mây (CSPM).
-	Lỗi ảo tưởng/định kiến của AI khi giải thích: AI thường ảo tưởng hậu quả vật lý, khẳng định lỗi cấu hình dữ liệu này đã trực tiếp làm nổ động cơ hoặc vô hiệu hóa phanh của hàng vạn chiếc xe Toyota đang di chuyển trên đường phố.