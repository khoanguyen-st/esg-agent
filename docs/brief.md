# Tóm Tắt Dự Án: Chatbot AI Agent ESG

## Tóm Tắt Tổng Quan

Chatbot AI Agent ESG là một plugin được hỗ trợ bởi AI cho nền tảng quản lý năng lượng Amigo, tự động tạo ra các báo cáo ESG (Môi trường, Xã hội, Quản trị) toàn diện và tuân thủ các tiêu chuẩn. Bằng cách kết hợp dữ liệu năng lượng và phát thải của tòa nhà theo thời gian thực từ các API hiện có của Amigo với dữ liệu môi trường công khai, chatbot tạo ra các báo cáo được định dạng chuyên nghiệp phù hợp với vị trí và hoạt động của từng cơ sở.

**Vấn Đề Chính:** Các công ty, đặc biệt là các doanh nghiệp vừa và nhỏ (SMEs), gặp khó khăn với việc tạo báo cáo ESG thủ công mất nhiều thời gian. Nhiều công ty thiếu nhân sự chuyên về ESG và phải đối mặt với các báo cáo mất từ vài giờ đến vài tháng để hoàn thành. Những công ty cố gắng tự làm báo cáo thường không đáp ứng được các tiêu chuẩn phù hợp, trong khi thuê ngoài các tư vấn viên lại tốn kém chi phí cao.

**Giá Trị Cốt Lõi:** Mở rộng khả năng quản lý năng lượng/phát thải của Amigo với tính năng tạo báo cáo ESG tự động và tuân thủ tiêu chuẩn. Người dùng có thể chọn khung ESG ưa thích của họ (GRI, SASB, TCFD, CDP, ISO 14001, v.v.) và nhận được các báo cáo được định dạng chuyên nghiệp mà không cần chuyên môn ESG chuyên sâu. Giải pháp này chuyển đổi một quy trình mất hàng tháng và tốn kém thành một quy trình tự động chỉ mất vài giờ và giá cả phải chăng.

---

## Vấn Đề

### Tình Trạng Hiện Tại

Người dùng Amigo hiện tại tạo báo cáo ESG thông qua một quy trình thủ công, tốn nhiều công sức:

- Nhân viên xem dữ liệu năng lượng và phát thải trong giao diện Amigo
- Dữ liệu được chép tay vào các tài liệu báo cáo (thường là Excel hoặc Word)
- Công việc này được thực hiện bởi nhân viên thường thiếu chuyên môn ESG chuyên sâu
- Quy trình này thay đổi rất nhiều về thời lượng tùy thuộc vào kinh nghiệm và nguồn lực của công ty

### Pain Points Chính

**Cực Kỳ Tốn Thời Gian:**
Việc tạo báo cáo ESG thủ công mất từ vài giờ đối với các nhóm có kinh nghiệm đến vài tháng đối với các công ty mới làm quen với báo cáo ESG. Khoản đầu tư thời gian không thể dự đoán này tạo ra những thách thức đáng kể trong việc lập kế hoạch nguồn lực.

**Chi Phí Thuê Ngoài Cao:**
Các SMEs và các công ty không có chuyên môn ESG nội bộ phải thuê các tư vấn viên bên ngoài đắt đỏ để tạo ra các báo cáo chất lượng, khiến cho việc tuân thủ ESG trở nên gánh nặng về tài chính.

**Nhu Cầu Tần Suất Thay Đổi:**
Các công ty cần báo cáo ESG với các tần suất khác nhau—hàng tháng, hàng quý, hàng năm, hoặc nhiều năm—khiến gánh nặng thủ công trở nên không thể dự đoán và khó mở rộng.

**Chất Lượng Không Nhất Quán:**
Các báo cáo thay đổi đáng kể về mức độ đầy đủ, định dạng và tuân thủ các tiêu chuẩn ESG. Nhiều công ty cố gắng tạo báo cáo nhưng tạo ra các kết quả không đạt tiêu chuẩn chuyên nghiệp và yêu cầu quy định.

**Vấn Đề Về Phạm Vi Dữ Liệu & Bối Cảnh:**
Nhân viên gặp khó khăn trong việc:

- Đảm bảo phạm vi dữ liệu đầy đủ trên tất cả các chỉ số yêu cầu
- Kết hợp các điểm chuẩn ngành và dữ liệu so sánh
- Bao gồm các yếu tố môi trường và quy định cụ thể theo vị trí
- Cung cấp bối cảnh tường thuật phù hợp và phân tích ngoài các con số thô

### Tác Động

Các công ty phải đối mặt với sự tiêu hao nguồn lực đáng kể và gánh nặng tài chính để đáp ứng nhu cầu ngày càng tăng từ khách hàng và nhà đầu tư về báo cáo ESG chuyên nghiệp. Sự phức tạp và chi phí tạo ra rào cản gia nhập, ngăn cản nhiều người dùng Amigo tiềm năng tiếp cận khả năng báo cáo ESG và hạn chế khả năng cạnh tranh của họ cho các cơ hội kinh doanh yêu cầu thông tin xác thực ESG.

### Tính Cấp Thiết

Nhu cầu cho giải pháp này được thúc đẩy bởi:

- **Kỳ vọng của các bên liên quan ngày càng tăng:** Khách hàng và nhà đầu tư ngày càng yêu cầu tính minh bạch ESG và báo cáo chuyên nghiệp
- **Cơ hội thị trường:** Các công ty có thể cung cấp báo cáo ESG chất lượng một cách hiệu quả sẽ có lợi thế cạnh tranh
- **Giá trị đề xuất của Amigo:** Thêm khả năng ESG toàn diện giúp Amigo trở thành giải pháp hoàn chỉnh từ năng lượng đến báo cáo, thu hút khách hàng mới và giữ chân khách hàng hiện tại

---

## Giải Pháp Đề Xuất

### Khái Niệm Cốt Lõi

Một AI agent chatbot plugin được hỗ trợ bởi AI tích hợp liền mạch với các API hiện có của Amigo để tự động tạo ra các báo cáo ESG chuyên nghiệp và tuân thủ tiêu chuẩn. Chatbot sử dụng mô hình tương tác kết hợp giữa biểu mẫu khởi động nhanh với hướng dẫn đàm thoại, giúp người dùng với các mức độ chuyên môn ESG khác nhau có thể dễ dàng tiếp cận.

### Khả Năng Chính

**1. Tạo Báo Cáo Đa Tiêu Chuẩn**

- Hỗ trợ tất cả các khung ESG chính: GRI, SASB, TCFD, CDP, ISO 14001, và các tiêu chuẩn khu vực
- Lựa chọn tiêu chuẩn do người dùng chọn với các mẫu cụ thể cho từng khung
- Cấu trúc báo cáo tự động theo tiêu chuẩn đã chọn
- Xác minh tuân thủ tích hợp

**2. Tích Hợp Dữ Liệu Tự Động**

- Kết nối liền mạch với các API hiện có của Amigo
- Trích xuất dữ liệu tiêu thụ năng lượng theo tòa nhà và thiết bị
- Trích xuất dữ liệu phát thải với tổng hợp cấp tòa nhà
- Hỗ trợ phạm vi ngày linh hoạt (hàng tháng, hàng quý, hàng năm, nhiều năm)
- Xử lý nhiều tòa nhà/cơ sở trong một tổ chức

**3. Làm Giàu Bằng AI**

_Làm Giàu Dữ Liệu:_

- Kết hợp dữ liệu thời tiết địa phương cho bối cảnh sử dụng năng lượng
- Áp dụng các hệ số phát thải khu vực để tính toán carbon chính xác
- Thêm bối cảnh môi trường cụ thể theo vị trí

_Tuân Thủ Quy Định:_

- Tích hợp các quy định ESG địa phương và yêu cầu công bố
- Đảm bảo tuân thủ cụ thể theo khu vực pháp lý

_Đánh Giá So Sánh:_

- So sánh hiệu suất với các tiêu chuẩn ngành
- Tham khảo các thực hành bền vững tốt nhất
- Cung cấp bối cảnh cho các chỉ số hiệu suất

_Tạo Nội Dung Tường Thuật:_

- Tạo bình luận và thông tin chi tiết phân tích ngoài các con số thô
- Tạo tóm tắt điều hành và các phát hiện chính
- Tạo ra các giải thích theo ngữ cảnh về xu hướng hiệu suất

_Kiểm Tra Tuân Thủ:_

- Xác minh tất cả các công bố yêu cầu được bao gồm theo tiêu chuẩn đã chọn
- Đánh dấu các điểm dữ liệu bị thiếu hoặc các phần không đầy đủ
- Xác thực tính đầy đủ và chất lượng dữ liệu

_Khuyến Nghị Thông Minh:_

- Đề xuất các lĩnh vực cải thiện dựa trên phân tích hiệu suất
- Làm nổi bật các thực hành bền vững có liên quan
- Xác định cơ hội để nâng cao hiệu suất

**4. Tùy Chỉnh Báo Cáo Thông Minh**

- Thích ứng với các tần suất báo cáo khác nhau (hàng tháng, hàng quý, hàng năm, nhiều năm)
- Phù hợp với nhu cầu và bối cảnh cụ thể của công ty
- Mở rộng từ một tòa nhà đến danh mục nhiều cơ sở

**5. Nhiều Định Dạng Xuất**

- PDF (định dạng chính—chuyên nghiệp, có thể chia sẻ)
- Word/DOCX (định dạng có thể chỉnh sửa để tùy chỉnh)
- Markdown (cho người dùng kỹ thuật, kiểm soát phiên bản, xuất bản web)

### Tại Sao Điều Này Sẽ Thành Công

**Loại Bỏ Rào Cản Chuyên Môn:**
Không cần chuyên gia ESG—AI nhúng kiến thức về khung và các thực hành tốt nhất, giúp báo cáo chuyên nghiệp có thể tiếp cận được với tất cả người dùng.

**Giảm Thời Gian Đáng Kể:**
Chuyển đổi một quy trình mất hàng tháng hoặc ngày thành một quy trình chỉ mất vài giờ, giải phóng nhân viên cho công việc chiến lược thay vì biên soạn dữ liệu thủ công.

**Hiệu Quả Chi Phí:**
Thay thế các tư vấn viên đắt đỏ (thường tốn hàng nghìn đến hàng chục nghìn đô la) bằng việc tạo tự động được hỗ trợ bởi AI đi kèm với nền tảng Amigo.

**Tuân Thủ Tiêu Chuẩn:**
Kiến thức tích hợp về các khung ESG chính đảm bảo các báo cáo đáp ứng các tiêu chuẩn chuyên nghiệp và quy định mà không cần chuyên môn của người dùng.

**Phong Phú Về Ngữ Cảnh:**
Kết hợp dữ liệu vận hành nội bộ của Amigo với thông tin tình báo môi trường bên ngoài, cung cấp các báo cáo vừa dựa trên dữ liệu vừa có ý nghĩa về ngữ cảnh.

**Tích Hợp Liền Mạch:**
Kiến trúc plugin tận dụng đầu tư Amigo hiện có, không yêu cầu nền tảng riêng biệt hoặc nhập dữ liệu trùng lặp.

**Mô Hình Tương Tác Kết Hợp:**
Phù hợp với cả người dùng khởi động nhanh (qua biểu mẫu) và những người cần hướng dẫn (qua AI đàm thoại), phục vụ các mức độ tinh vi khác nhau của người dùng.

---

## Người Dùng Mục Tiêu

### Phân Khúc Người Dùng Chính

Chatbot AI Agent ESG phục vụ ba nhân vật chính khác nhau trên phổ quy mô công ty và mức độ trưởng thành về ESG. Cả ba đều quan trọng như nhau cho sự thành công của MVP.

### Người Dùng/Bên Liên Quan Thứ Cấp

#### Người Đánh Giá Báo Cáo

- **Vai Trò:** Giám đốc điều hành cấp cao, thành viên Hội đồng quản trị, Cố vấn pháp lý
- **Trường Hợp Sử Dụng:** Đánh giá và phê duyệt báo cáo ESG trước khi xuất bản
- **Nhu Cầu:** Báo cáo rõ ràng, chuyên nghiệp với tóm tắt điều hành; khả năng yêu cầu điều chỉnh hoặc làm rõ từ chatbot

#### Kiểm Toán Viên Bên Ngoài

- **Vai Trò:** Kiểm toán viên ESG bên thứ ba, cơ quan xác minh
- **Trường Hợp Sử Dụng:** Xác minh tính chính xác và đầy đủ của các tuyên bố ESG
- **Nhu Cầu:** Truy cập các nguồn dữ liệu cơ bản, tính minh bạch về phương pháp, dấu vết kiểm toán cho thấy nguồn gốc dữ liệu

#### Người Tiêu Thụ Báo Cáo

- **Vai Trò:** Khách hàng, nhà đầu tư, cơ quan quản lý, công chúng
- **Trường Hợp Sử Dụng:** Đọc và đánh giá hiệu suất ESG của công ty
- **Nhu Cầu:** Báo cáo tuân thủ tiêu chuẩn, toàn diện đáp ứng tiêu chí đánh giá của họ và cho phép so sánh có ý nghĩa

---

## Mục Tiêu & Chỉ Số Thành Công

### Chỉ Số Thành Công Của Người Dùng

**1. Tiết Kiệm Thời Gian**

- **Chỉ Số:** Giảm thời gian tạo báo cáo từ hàng tháng/ngày xuống còn vài giờ
- **Mục Tiêu:** Giảm 90%+ thời gian dành cho việc tạo báo cáo ESG
- **Đo Lường:** Khảo sát người dùng, so sánh theo dõi thời gian trước/sau khi áp dụng

**2. Tiết Kiệm Chi Phí**

- **Chỉ Số:** Giảm chi phí báo cáo ESG đáng kể so với phí tư vấn
- **Mục Tiêu:** Giảm chi phí 70-90% so với thuê ngoài
- **Đo Lường:** Phân tích so sánh chi phí, tính toán ROI

**3. Tỷ Lệ Chấp Nhận**

- **Chỉ Số:** Tỷ lệ phần trăm người dùng Amigo tạo ít nhất 1 báo cáo ESG trong kỳ đầu tiên sau khi ra mắt
- **Mục Tiêu:** Được xác định dựa trên quy mô cơ sở người dùng và mục tiêu chấp nhận
- **Đo Lường:** Phân tích người dùng, theo dõi tạo báo cáo

**4. Chất Lượng Báo Cáo**

- **Chỉ Số:** Tỷ lệ phần trăm báo cáo được tạo đáp ứng các tiêu chuẩn tuân thủ mà không cần chỉnh sửa thủ công
- **Mục Tiêu:** Tỷ lệ tuân thủ cao cho thấy đầu ra chất lượng chuyên nghiệp
- **Đo Lường:** Kết quả kiểm toán tuân thủ, phản hồi người dùng về khả năng sử dụng báo cáo

**5. Sự Hài Lòng Của Người Dùng**

- **Chỉ Số:** Điểm NPS hoặc đánh giá mức độ hài lòng cho thấy người dùng sẽ giới thiệu cho người khác
- **Mục Tiêu:** Điểm hài lòng tích cực mạnh mẽ
- **Đo Lường:** Khảo sát người dùng, theo dõi NPS, thu thập phản hồi

### Các Chỉ Số Hiệu Suất Chính (KPIs)

Các chỉ số sau sẽ được theo dõi thường xuyên để đo lường sức khỏe hệ thống và sự tham gia của người dùng:

- **Số Báo Cáo Được Tạo Mỗi Tháng:** Chỉ số khối lượng cho thấy sự chấp nhận và sử dụng
- **Người Dùng Hoạt Động (Hàng Tháng):** Số lượng người dùng duy nhất tạo báo cáo mỗi tháng
- **Thời Gian Đến Báo Cáo Đầu Tiên:** Người dùng mới tạo báo cáo đầu tiên nhanh như thế nào sau khi có quyền truy cập
- **Tỷ Lệ Hoàn Thành Báo Cáo:** Tỷ lệ phần trăm báo cáo bắt đầu được hoàn thành
- **Giữ Chân Người Dùng:** Tỷ lệ phần trăm người dùng tạo báo cáo lặp lại
- **Phân Tích Sử Dụng Tính Năng:** Tiêu chuẩn ESG nào được chọn, khả năng AI nào được sử dụng nhiều nhất
- **Ticket Hỗ Trợ Trên Mỗi Báo Cáo:** Chỉ số về khả năng sử dụng hệ thống và các điểm đau

---

## Phạm Vi MVP

### Tính Năng Cốt Lõi (Bắt Buộc Có Cho MVP)

#### 1. Giao Diện & Tương Tác Chatbot

- **Mô hình tương tác kết hợp:** Biểu mẫu khởi động nhanh cho người dùng có kinh nghiệm + hướng dẫn đàm thoại cho những người cần trợ giúp
- **Thu thập tham số:** Hướng dẫn người dùng qua các tham số báo cáo (chọn tòa nhà, khoảng thời gian, tiêu chuẩn ESG)
- **Hội thoại ngôn ngữ tự nhiên:** Hỗ trợ câu hỏi, làm rõ và điều chỉnh
- **UX trực quan:** Có thể tiếp cận với người dùng có các mức độ chuyên môn ESG khác nhau (từ người mới đến chuyên gia)
- **Theo dõi tiến độ:** Hiển thị cho người dùng vị trí họ đang ở trong quy trình tạo báo cáo

#### 2. Tích Hợp API Amigo

- **Dữ liệu tiêu thụ năng lượng:** Trích xuất dữ liệu năng lượng toàn diện theo tòa nhà
- **Dữ liệu phát thải:** Trích xuất các chỉ số phát thải theo thiết bị và tổng hợp tòa nhà
- **Phạm vi ngày linh hoạt:** Hỗ trợ các kỳ hàng tháng, hàng quý, hàng năm và nhiều năm
- **Hỗ trợ nhiều cơ sở:** Xử lý nhiều tòa nhà/cơ sở trong một tổ chức
- **Xác thực dữ liệu:** Xác minh tính đầy đủ và chất lượng dữ liệu từ Amigo

#### 3. Hỗ Trợ Tiêu Chuẩn ESG Toàn Diện

Hỗ trợ tất cả các khung báo cáo ESG chính:

- **GRI** (Sáng kiến Báo cáo Toàn cầu)
- **SASB** (Hội đồng Tiêu chuẩn Kế toán Bền vững)
- **TCFD** (Lực lượng Đặc nhiệm về Công bố liên quan đến Khí hậu)
- **CDP** (Dự án Công bố Carbon)
- **ISO 14001** (Quản lý Môi trường)
- **Tiêu Chuẩn Khu Vực** (EU CSRD, v.v.)

Mỗi tiêu chuẩn bao gồm:

- Mẫu khung phù hợp
- Các phần công bố yêu cầu
- Định dạng cụ thể theo tiêu chuẩn
- Xác thực tuân thủ

#### 4. Tạo Báo Cáo Được Hỗ Trợ Bởi AI

**Cấu Trúc & Điền Dữ Liệu:**

- Tự động tạo cấu trúc báo cáo hoàn chỉnh theo tiêu chuẩn ESG đã chọn
- Điền dữ liệu định lượng từ API Amigo
- Sắp xếp dữ liệu vào các phần yêu cầu của khung

**Tạo Nội Dung Tường Thuật:**

- Tạo thông tin chi tiết phân tích và bình luận do AI điều khiển
- Tạo tóm tắt điều hành làm nổi bật các phát hiện chính
- Cung cấp giải thích theo ngữ cảnh về các chỉ số hiệu suất
- Phát triển các khuyến nghị dựa trên phân tích hiệu suất

**Chất Lượng Nội Dung:**

- Giọng điệu và ngôn ngữ chuyên nghiệp phù hợp cho các bên liên quan
- Giải thích rõ ràng, chính xác phù hợp với đối tượng phi kỹ thuật
- Thông tin chi tiết và đề xuất cải thiện có thể thực hiện

#### 5. Tích Hợp Dữ Liệu Công Khai

**Hệ Số Phát Thải Khu Vực:**

- Tính toán carbon chính xác dựa trên thành phần lưới điện địa phương
- Cập nhật các hệ số phát thải theo khu vực/quốc gia

**Quy Định Môi Trường Địa Phương:**

- Yêu cầu tuân thủ cụ thể theo khu vực pháp lý
- Công bố yêu cầu dựa trên vị trí

**Điểm Chuẩn Ngành:**

- Dữ liệu hiệu suất so sánh theo lĩnh vực ngành
- Bối cảnh để đánh giá hiệu suất ("tốt" vs. "cần cải thiện")

**Thực Hành Bền Vững Tốt Nhất:**

- Các thực hành tốt nhất có liên quan cho ngành và loại tòa nhà của người dùng
- Khuyến nghị phù hợp với các tiêu chuẩn bền vững hàng đầu

**Bối Cảnh Môi Trường Cụ Thể Theo Vị Trí:**

- Dữ liệu thời tiết cơ bản để tạo ngữ cảnh cho việc sử dụng năng lượng
- Điều kiện môi trường địa phương ảnh hưởng đến hiệu suất tòa nhà

#### 6. Định Dạng Đầu Ra Báo Cáo

**PDF (Định Dạng Chính):**

- Định dạng chuyên nghiệp phù hợp cho phân phối cho các bên liên quan
- Biểu đồ, bảng và đồ họa nhúng
- Phiên bản cuối cùng có thể chia sẻ, không thể chỉnh sửa

**Word/DOCX (Định Dạng Có Thể Chỉnh Sửa):**

- Cho phép người dùng tùy chỉnh và bổ sung
- Duy trì định dạng để dễ dàng chỉnh sửa
- Hỗ trợ quy trình đánh giá cộng tác

**Markdown:**

- Người dùng kỹ thuật và hệ thống kiểm soát phiên bản
- Xuất bản web và hệ thống tài liệu
- Chỉnh sửa và chuyển đổi văn bản thuần túy

Tất cả các định dạng bao gồm:

- Các phần được định dạng đúng theo tiêu chuẩn ESG
- Công bố và bảng dữ liệu yêu cầu
- Tóm tắt điều hành và các phát hiện chính
- Các yếu tố trực quan (biểu đồ, bảng) nếu phù hợp

#### 7. Kiểm Tra Tuân Thủ

**Xác Minh Công Bố:**

- Xác minh tất cả các công bố yêu cầu có mặt theo tiêu chuẩn ESG đã chọn
- Kiểm tra theo yêu cầu của khung

**Tính Đầy Đủ Dữ Liệu:**

- Đánh dấu các điểm dữ liệu bị thiếu hoặc các phần không đầy đủ
- Xác định các vấn đề về chất lượng dữ liệu

**Tóm Tắt Xác Thực:**

- Cung cấp tổng quan về trạng thái tuân thủ
- Làm nổi bật các lĩnh vực cần chú ý
- Cung cấp hướng dẫn để giải quyết khoảng trống

#### 8. Khuyến Nghị Thông Minh

**Đề Xuất Dựa Trên Hiệu Suất:**

- Xác định các lĩnh vực cải thiện dựa trên phân tích dữ liệu
- Làm nổi bật các chỉ số hoạt động kém

**Phù Hợp Với Thực Hành Tốt Nhất:**

- Đề xuất các thực hành bền vững có liên quan đến bối cảnh của người dùng
- Kết nối các khuyến nghị với các tiêu chuẩn ngành

**Xác Định Khoảng Trống:**

- Chỉ ra dữ liệu hoặc các yếu tố báo cáo còn thiếu
- Hướng dẫn người dùng hướng tới báo cáo toàn diện
