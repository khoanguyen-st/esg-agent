# Tài Liệu Yêu Cầu Sản Phẩm (PRD) Chatbot AI Agent ESG

## Mục Tiêu và Bối Cảnh Nền

### Mục Tiêu

- **Tự Động Hóa Việc Tạo Báo Cáo ESG:** Cho phép người dùng Amigo tạo báo cáo ESG chuyên nghiệp, tuân thủ tiêu chuẩn trong vài giờ thay vì vài ngày hoặc vài tháng thông qua tự động hóa được hỗ trợ bởi AI
- **Loại Bỏ Rào Cản Chuyên Môn:** Làm cho báo cáo ESG có thể tiếp cận được với các công ty ở mọi quy mô mà không cần nhân sự chuyên về ESG hoặc tư vấn viên
- **Đảm Bảo Tuân Thủ Tiêu Chuẩn:** Hỗ trợ tất cả các khung ESG chính (GRI, SASB, TCFD, CDP, ISO 14001, tiêu chuẩn khu vực) với xác minh tuân thủ tích hợp
- **Mang Lại Tiết Kiệm Thời Gian và Chi Phí:** Đạt được giảm 90%+ thời gian tạo báo cáo và giảm chi phí 70-90% so với cách tiếp cận dựa trên tư vấn truyền thống
- **Thúc Đẩy Việc Chấp Nhận Amigo:** Định vị Amigo là giải pháp hoàn chỉnh từ năng lượng đến báo cáo ESG, thu hút khách hàng mới và tăng tỷ lệ giữ chân
- **Cung Cấp Thông Tin Theo Ngữ Cảnh:** Làm phong phú dữ liệu vận hành Amigo bằng dữ liệu môi trường công khai, điểm chuẩn ngành và thông tin chi tiết theo vị trí
- **Mở Rộng Quy Mô Trên Các Nhân Vật Người Dùng:** Phục vụ các nhà quản lý bền vững, người vận hành cơ sở và giám đốc điều hành SME một cách bình đẳng thông qua mô hình tương tác kết hợp trực quan

### Bối Cảnh Nền

Amigo là một nền tảng quản lý năng lượng đã được thiết lập, cung cấp các API toàn diện để theo dõi tiêu thụ điện và dữ liệu phát thải theo thiết bị và tòa nhà. Trong khi Amigo thành công trong việc giúp các tổ chức giám sát và quản lý dấu chân năng lượng của họ, người dùng phải đối mặt với những thách thức đáng kể khi cố gắng chuyển đổi dữ liệu vận hành này thành báo cáo ESG chính thức cho các bên liên quan.

**Thách Thức Hiện Tại:**

Các công ty ở mọi quy mô đang gặp khó khăn với việc tạo báo cáo ESG thủ công. Nhân viên thủ công trích xuất dữ liệu từ giao diện Amigo và chép nó vào tài liệu Excel hoặc Word—một quy trình mất từ vài giờ đến vài tháng tùy thuộc vào kinh nghiệm và nguồn lực của công ty. Nhiều người thiếu nhân sự chuyên về ESG, dẫn đến các báo cáo không đáp ứng tiêu chuẩn chuyên nghiệp hoặc yêu cầu quy định. Các SMEs thường phải sử dụng các tư vấn viên đắt đỏ (tốn hàng nghìn đến hàng chục nghìn đô la), trong khi những người khác tránh báo cáo ESG hoàn toàn mặc dù có nhu cầu ngày càng tăng từ khách hàng và nhà đầu tư.

**Cơ Hội Thị Trường:**

Kỳ vọng ngày càng tăng của các bên liên quan về tính minh bạch ESG, kết hợp với các yêu cầu quy định ngày càng tăng trên toàn cầu, tạo ra nhu cầu cấp thiết cho các giải pháp báo cáo ESG có thể tiếp cận và giá cả phải chăng. Các công ty có thể cung cấp báo cáo ESG chất lượng một cách hiệu quả sẽ có lợi thế cạnh tranh trong việc đảm bảo hợp đồng và đầu tư. Bằng cách thêm khả năng báo cáo ESG toàn diện, Amigo có thể chuyển đổi từ nền tảng quản lý năng lượng thành giải pháp bền vững hoàn chỉnh, nắm bắt thị phần đáng kể giữa các SMEs và doanh nghiệp đang tìm kiếm tự động hóa ESG từ đầu đến cuối.

**Giải Pháp:**

Chatbot AI Agent ESG là một plugin cho Amigo tự động tạo báo cáo ESG toàn diện, tuân thủ tiêu chuẩn bằng cách kết hợp dữ liệu năng lượng và phát thải của tòa nhà theo thời gian thực từ các API hiện có của Amigo với dữ liệu môi trường công khai. Sử dụng mô hình tương tác kết hợp (biểu mẫu khởi động nhanh + AI đàm thoại), chatbot hướng dẫn người dùng qua việc tạo báo cáo bất kể mức độ chuyên môn ESG của họ, tạo ra các báo cáo chuyên nghiệp ở định dạng PDF, Word và Markdown đáp ứng các yêu cầu cụ thể theo khung.

---

## Yêu Cầu

### Yêu Cầu Chức Năng

#### Tạo Báo Cáo & Tiêu Chuẩn ESG

**FR1:** Hệ thống sẽ hỗ trợ tạo báo cáo cho tất cả các khung báo cáo ESG chính bao gồm GRI (Sáng kiến Báo cáo Toàn cầu), SASB (Hội đồng Tiêu chuẩn Kế toán Bền vững), TCFD (Lực lượng Đặc nhiệm về Công bố liên quan đến Khí hậu), CDP (Dự án Công bố Carbon), ISO 14001 (Quản lý Môi trường), và các tiêu chuẩn khu vực (EU CSRD, v.v.).

**FR2:** Hệ thống sẽ cho phép người dùng chọn tiêu chuẩn ESG ưa thích của họ khi bắt đầu tạo báo cáo thông qua menu thả xuống hoặc lựa chọn đàm thoại.

**FR3:** Hệ thống sẽ tự động tạo cấu trúc báo cáo hoàn chỉnh cụ thể cho khung ESG đã chọn, bao gồm tất cả các phần yêu cầu, danh mục công bố và bảng dữ liệu như được định nghĩa bởi tiêu chuẩn đó.

**FR4:** Hệ thống sẽ xác minh rằng tất cả các công bố yêu cầu cho tiêu chuẩn ESG đã chọn có mặt trong báo cáo được tạo và đánh dấu bất kỳ yếu tố nào bị thiếu.

**FR5:** Hệ thống sẽ xác thực tính đầy đủ của báo cáo theo yêu cầu của khung và cung cấp tóm tắt trạng thái tuân thủ làm nổi bật các lĩnh vực cần chú ý.

#### Giao Diện & Tương Tác Chatbot

**FR6:** Hệ thống sẽ cung cấp mô hình tương tác kết hợp kết hợp biểu mẫu khởi động nhanh (cho người dùng có kinh nghiệm) với hướng dẫn AI đàm thoại (cho người dùng cần trợ giúp).

**FR7:** Chatbot sẽ hướng dẫn người dùng qua các tham số báo cáo thiết yếu bao gồm lựa chọn tòa nhà/cơ sở, kỳ báo cáo (hàng tháng/hàng quý/hàng năm/nhiều năm), và lựa chọn tiêu chuẩn ESG.

**FR8:** Chatbot sẽ hỗ trợ hội thoại ngôn ngữ tự nhiên cho các làm rõ, điều chỉnh và câu hỏi trong quá trình tạo báo cáo.

**FR9:** Hệ thống sẽ hiển thị theo dõi tiến độ cho người dùng thấy họ đang ở đâu trong quy trình tạo báo cáo.

**FR10:** Chatbot sẽ cung cấp trợ giúp theo ngữ cảnh và giải thích phù hợp cho người dùng với các mức độ chuyên môn ESG khác nhau (từ người mới đến chuyên gia).

**FR11:** Chatbot sẽ ghi nhớ ngữ cảnh hội thoại và tùy chọn người dùng trong một phiên để tránh các câu hỏi lặp lại.

#### Tích Hợp API Amigo & Quản Lý Dữ Liệu

**FR12:** Hệ thống sẽ tích hợp với các API hiện có của Amigo để trích xuất dữ liệu tiêu thụ năng lượng toàn diện theo tòa nhà và thiết bị.

**FR13:** Hệ thống sẽ trích xuất dữ liệu phát thải theo thiết bị và tổng hợp tòa nhà từ API Amigo.

**FR14:** Hệ thống sẽ hỗ trợ lựa chọn phạm vi ngày linh hoạt bao gồm các kỳ báo cáo hàng tháng, hàng quý, hàng năm và nhiều năm.

**FR15:** Hệ thống sẽ xử lý nhiều tòa nhà/cơ sở trong một tổ chức, cho phép người dùng tạo báo cáo cá nhân hoặc tổng hợp.

**FR16:** Hệ thống sẽ xác thực tính đầy đủ và chất lượng dữ liệu từ Amigo, đánh dấu các điểm dữ liệu bị thiếu hoặc bất thường.

**FR17:** Hệ thống sẽ xác thực an toàn với API Amigo bằng cách sử dụng cơ chế xác thực hiện có của nền tảng.

#### Tạo Nội Dung Báo Cáo Được Hỗ Trợ Bởi AI

**FR18:** Hệ thống sẽ điền dữ liệu năng lượng và phát thải định lượng từ API Amigo vào các phần phù hợp của mẫu khung ESG đã chọn.

**FR19:** Hệ thống sẽ tạo các phần tường thuật do AI điều khiển bao gồm tóm tắt điều hành, các phát hiện chính, thông tin chi tiết phân tích và bình luận theo ngữ cảnh về các chỉ số hiệu suất.

**FR20:** Hệ thống sẽ tạo giọng điệu và ngôn ngữ chuyên nghiệp phù hợp cho các bên liên quan (nhà đầu tư, khách hàng, cơ quan quản lý).

**FR21:** Hệ thống sẽ cung cấp giải thích rõ ràng, chính xác phù hợp với đối tượng phi kỹ thuật trong khi duy trì độ chính xác kỹ thuật.

**FR22:** Hệ thống sẽ tạo các khuyến nghị có thể thực hiện để cải thiện hiệu suất dựa trên phân tích dữ liệu.

**FR23:** Hệ thống sẽ tạo tóm tắt điều hành làm nổi bật các phát hiện chính và điểm nổi bật/thấp về hiệu suất.

#### Tích Hợp & Làm Giàu Dữ Liệu Công Khai

**FR24:** Hệ thống sẽ tích hợp các hệ số phát thải khu vực để tính toán carbon chính xác dựa trên thành phần lưới điện địa phương, được cập nhật theo khu vực/quốc gia.

**FR25:** Hệ thống sẽ kết hợp các quy định môi trường địa phương và yêu cầu tuân thủ cụ thể theo khu vực pháp lý có liên quan đến vị trí của tòa nhà.

**FR26:** Hệ thống sẽ bao gồm các điểm chuẩn ngành và dữ liệu hiệu suất so sánh để cung cấp bối cảnh để đánh giá hiệu suất ("tốt" vs. "cần cải thiện").

**FR27:** Hệ thống sẽ tham khảo các thực hành bền vững tốt nhất có liên quan đến ngành và loại tòa nhà của người dùng.

**FR28:** Hệ thống sẽ kết hợp bối cảnh môi trường cụ thể theo vị trí bao gồm dữ liệu thời tiết cơ bản để tạo ngữ cảnh cho việc sử dụng năng lượng và điều kiện môi trường địa phương ảnh hưởng đến hiệu suất tòa nhà.

**FR29:** Hệ thống sẽ tự động làm mới các nguồn dữ liệu công khai theo nhịp độ thường xuyên để đảm bảo thông tin hiện tại.

#### Đầu Ra & Xuất Báo Cáo

**FR30:** Hệ thống sẽ tạo báo cáo ở định dạng PDF với định dạng chuyên nghiệp phù hợp cho phân phối cho các bên liên quan, bao gồm biểu đồ, bảng và đồ họa nhúng.

**FR31:** Hệ thống sẽ tạo báo cáo ở định dạng Word/DOCX cho phép người dùng tùy chỉnh và bổ sung trong khi duy trì định dạng để dễ dàng chỉnh sửa.

**FR32:** Hệ thống sẽ tạo báo cáo ở định dạng Markdown cho người dùng kỹ thuật, hệ thống kiểm soát phiên bản và xuất bản web.

**FR33:** Tất cả các định dạng đầu ra sẽ bao gồm các phần được định dạng đúng theo tiêu chuẩn ESG đã chọn, công bố và bảng dữ liệu yêu cầu, tóm tắt điều hành, các phát hiện chính và các yếu tố trực quan (biểu đồ, bảng) nếu phù hợp.

**FR34:** Hệ thống sẽ cho phép người dùng tải xuống các báo cáo được tạo ngay sau khi hoàn thành.

**FR35:** Hệ thống sẽ cung cấp khả năng xem trước báo cáo trước khi tải xuống/xuất cuối cùng.

#### Khuyến Nghị Thông Minh & Xác Định Khoảng Trống

**FR36:** Hệ thống sẽ xác định các lĩnh vực cải thiện dựa trên phân tích dữ liệu hiệu suất và làm nổi bật các chỉ số hoạt động kém.

**FR37:** Hệ thống sẽ đề xuất các thực hành bền vững tốt nhất có liên quan đến bối cảnh của người dùng và kết nối các khuyến nghị với các tiêu chuẩn ngành.

**FR38:** Hệ thống sẽ chỉ ra dữ liệu hoặc các yếu tố báo cáo còn thiếu và hướng dẫn người dùng hướng tới báo cáo toàn diện.

**FR39:** Hệ thống sẽ cung cấp các khuyến nghị được ưu tiên dựa trên tiềm năng tác động và tính khả thi.

---

## Mục Tiêu Thiết Kế Giao Diện Người Dùng

### Tầm Nhìn UX Tổng Thể

Giao diện Chatbot AI Agent ESG thể hiện **chuyên môn dễ tiếp cận**—làm cho báo cáo ESG phức tạp trở nên đơn giản và có hướng dẫn trong khi duy trì độ tin cậy chuyên nghiệp. Trải nghiệm nên giống như có một tư vấn viên ESG am hiểu có sẵn 24/7, kiên nhẫn hướng dẫn người dùng qua việc tạo báo cáo bất kể nền tảng của họ.

**Nguyên Tắc UX Cốt Lõi:**

- **Tiết Lộ Dần:** Bắt đầu đơn giản (biểu mẫu khởi động nhanh), chỉ tiết lộ độ phức tạp khi cần thiết (độ sâu đàm thoại)
- **Tin Tưởng Thông Qua Tính Minh Bạch:** Luôn cho người dùng thấy dữ liệu nào đang được sử dụng và các khuyến nghị đến từ đâu
- **Hướng Dẫn Không Hạ Thấp:** Giúp người mới mà không làm chuyên gia chán; thích nghi với sự tinh vi của người dùng
- **Rõ Ràng Trong Sự Phức Tạp:** Sử dụng ngôn ngữ đơn giản cho các khái niệm ESG trong khi duy trì độ chính xác kỹ thuật
- **Xây Dựng Tự Tin:** Cung cấp xác thực và khuyến khích tích cực khi người dùng tiến triển qua việc tạo báo cáo

### Các Mô Hình Tương Tác Chính

**1. Mô Hình Nhập Kết Hợp:**

- **Chế Độ Khởi Động Nhanh:** Biểu mẫu một trang cho người dùng có kinh nghiệm biết chính xác họ muốn gì (tòa nhà, kỳ, tiêu chuẩn, tạo)
- **Chế Độ Có Hướng Dẫn:** Luồng đàm thoại cho người dùng cần trợ giúp quyết định về tham số hoặc hiểu các tùy chọn
- **Chuyển Đổi Liền Mạch:** Người dùng có thể chuyển đổi giữa biểu mẫu và đàm thoại bất cứ lúc nào

**2. Các Mẫu AI Đàm Thoại:**

- **Câu Hỏi Làm Rõ:** Chatbot đặt các câu hỏi có mục tiêu khi đầu vào của người dùng mơ hồ hoặc không đầy đủ
- **Đề Xuất Theo Ngữ Cảnh:** Dựa trên dữ liệu tòa nhà và ngành của người dùng, đề xuất các tiêu chuẩn ESG và kỳ báo cáo có liên quan
- **Giải Thích Khi Bạn Đi:** Cung cấp giải thích tùy chọn cho thuật ngữ ESG và yêu cầu khung nội tuyến
- **Xác Nhận:** Tóm tắt lại lựa chọn của người dùng trước khi tạo báo cáo ("Chỉ để xác nhận, bạn muốn báo cáo GRI cho Tòa nhà A bao gồm Q3 2025?")

**3. Tầm Nhìn Tiến Độ & Trạng Thái:**

- **Chỉ Báo Tiến Độ:** Thanh tiến độ trực quan hoặc danh sách kiểm tra cho thấy: Tham Số Đã Đặt → Dữ Liệu Đã Truy Xuất → Báo Cáo Đã Tạo → Sẵn Sàng Tải Xuống
- **Cập Nhật Thời Gian Thực:** Cho người dùng thấy những gì đang xảy ra ("Đang trích xuất dữ liệu năng lượng từ Amigo...", "Đang tạo tóm tắt điều hành...", "Đang áp dụng khung TCFD...")
- **Ước Tính Thời Gian:** Hiển thị thời gian ước tính còn lại để tạo báo cáo

**4. Phục Hồi Lỗi & Xác Thực:**

- **Xác Thực Nội Tuyến:** Ngay lập tức xác thực đầu vào của người dùng (ví dụ: phạm vi ngày, lựa chọn tòa nhà) và cung cấp thông báo lỗi hữu ích
- **Giảm Nhẹ Duyên Dáng:** Nếu dữ liệu Amigo không đầy đủ, hiển thị những gì còn thiếu và đề nghị tạo báo cáo một phần hoặc đợi dữ liệu
- **Thử Lại & Tiếp Tục:** Cho phép người dùng thử lại các hoạt động thất bại mà không mất tiến độ

### Các Màn Hình và Chế Độ Xem Cốt Lõi

Từ góc độ sản phẩm, các màn hình quan trọng nhất cần thiết để cung cấp giá trị và mục tiêu của PRD:

**1. Màn Hình Đích/Trang Chủ**

- Thông điệp chào mừng với giải thích ngắn gọn về khả năng chatbot ESG
- Hai điểm nhập rõ ràng: nút "Khởi Động Nhanh" và công cụ khởi động đàm thoại "Hướng Dẫn Tôi"
- Danh sách báo cáo gần đây (nếu là người dùng quay lại) với các tùy chọn tạo lại nhanh
- Truy cập tài liệu trợ giúp và báo cáo mẫu

**2. Màn Hình Cấu Hình Báo Cáo (Chế Độ Khởi Động Nhanh)**

- Bộ Chọn Tòa Nhà/Cơ Sở (menu thả xuống hoặc tìm kiếm với danh sách tòa nhà Amigo)
- Bộ Chọn Kỳ Báo Cáo (cài đặt sẵn: Tháng Này, Quý Trước, Năm Này, Phạm Vi Tùy Chỉnh)
- Bộ Chọn Tiêu Chuẩn ESG (menu thả xuống với mô tả của mỗi khung)
- Tùy chọn: Lựa chọn ngành (để đánh giá tốt hơn)
- Nút Tạo Báo Cáo

**3. Giao Diện Chatbot Đàm Thoại (Chế Độ Có Hướng Dẫn)**

- Cửa sổ trò chuyện với AI đàm thoại hướng dẫn thu thập tham số
- Trường nhập tin nhắn người dùng với các chỉ báo gõ
- Nút phản hồi được đề xuất cho các câu trả lời phổ biến
- Bảng điều khiển bên hiển thị các tham số đã chọn khi đàm thoại tiến triển
- Khả năng chỉnh sửa tham số trực tiếp trong bảng điều khiển bên
- Nút Tạo Báo Cáo (xuất hiện khi tất cả tham số được thu thập)

**4. Màn Hình Tiến Độ Tạo Báo Cáo**

- Chỉ báo tiến độ cho thấy giai đoạn hiện tại
- Thông báo trạng thái thời gian thực
- Thời gian ước tính còn lại
- Nút Hủy (có xác nhận)
- Tùy chọn tạo nền (người dùng có thể điều hướng đi và quay lại)

**5. Màn Hình Xem Trước & Tải Xuống Báo Cáo**

- Khung xem trước hiển thị báo cáo được tạo (các tab PDF/Word/Markdown)
- Tóm tắt các chỉ số chính ở trên cùng (điểm báo cáo, trạng thái tuân thủ, yếu tố còn thiếu)
- Nút tải xuống cho mỗi định dạng
- Tùy chọn Chỉnh sửa/Tạo lại nếu người dùng muốn điều chỉnh tham số
- Tùy chọn chia sẻ (nếu có)
- Cơ chế phản hồi (đánh giá chất lượng báo cáo này)

**6. Màn Hình Đánh Giá Báo Cáo (Kiểm Tra Tuân Thủ)**

- Tổng quan trạng thái tuân thủ (ví dụ: "95% tuân thủ với tiêu chuẩn GRI")
- Danh sách các vấn đề được đánh dấu hoặc công bố còn thiếu với giải thích
- Bảng điều khiển khuyến nghị với các đề xuất cải thiện được ưu tiên
- Tùy chọn chấp nhận báo cáo như hiện tại hoặc giải quyết khoảng trống
- Nút Tạo lại với các cải tiến

**7. Màn Hình Cài Đặt & Tùy Chọn**

- Tùy chọn tiêu chuẩn ESG mặc định
- Tòa nhà/cơ sở mặc định để truy cập nhanh
- Tùy chọn thông báo
- Tùy chỉnh mẫu báo cáo (thương hiệu, tải lên logo)
- Tùy chọn nguồn dữ liệu (dữ liệu công khai nào để bao gồm)

### Thương Hiệu

**Tích Hợp Với Thương Hiệu Amigo:**

- Sử dụng bảng màu hiện có và các token thiết kế của Amigo cho sự nhất quán về hình ảnh
- Chatbot nên cảm thấy như một phần mở rộng tự nhiên của nền tảng Amigo, không phải một công cụ riêng biệt
- Duy trì kiểu chữ, kiểu nút và các mẫu UI của Amigo
- Thương hiệu chatbot ESG là "Amigo ESG Reporting" hoặc tương tự (tên cuối cùng TBD)

**Độ Tin Cậy Chuyên Nghiệp:**

- Thiết kế hình ảnh nên truyền tải sự đáng tin cậy và chuyên môn phù hợp cho báo cáo ESG
- Sử dụng các điểm nhấn màu liên quan đến tính bền vững (màu xanh lá cây, xanh dương) khi phù hợp
- Biểu tượng và hình minh họa truyền đạt trách nhiệm môi trường
