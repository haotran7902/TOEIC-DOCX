# BÀI THUYẾT TRÌNH
## TỪ LƯỢNG ĐẾN CHẤT: ĐƯỜNG ĐI CỦA TRÍ TUỆ NHÂN TẠO VÀ BÀI HỌC CHO SINH VIÊN KHOA HỌC MÁY TÍNH

*Vận dụng quy luật chuyển hóa từ những thay đổi về lượng thành những thay đổi về chất và ngược lại*

> **Cách dùng bản này:**
> - Chữ thường là lời nói. Chữ *nghiêng trong ngoặc vuông* là ghi chú cho bạn (chuyển slide, ngừng, nhấn giọng), không đọc thành tiếng.
> - Các thuật ngữ khó đã được giải thích ngay trong lời nói, mỗi chỗ không quá 20 chữ. Bạn có thể đọc nguyên văn hoặc nói lại theo cách riêng.
> - Thời lượng ước tính khoảng **13–15 phút** nếu nói với tốc độ vừa phải.
> - Lưu ý: bản nội dung gốc mở đầu nói có năm phần, nhưng file chỉ có **ba phần** (mở đầu, cơ sở lý luận, vận dụng, chiều ngược lại). Phần kết bên dưới có sẵn câu chuyển để bạn nối sang các phần còn lại.

---

## 1. MỞ ĐẦU *(khoảng 2 phút)*

Xin chào cô và các bạn. Hôm nay nhóm em xin trình bày đề tài: **"Từ lượng đến chất: đường đi của trí tuệ nhân tạo và bài học cho sinh viên Khoa học máy tính."**

Trước hết, em xin hỏi các bạn một câu. *[Ngừng một nhịp, nhìn cả lớp]* Các bạn có cảm giác là AI *"đột nhiên"* xuất hiện khắp nơi không?

Mới vài năm trước, AI vẫn khá âm thầm. Mỗi hệ thống chỉ làm tốt một việc hẹp, ví dụ chỉ chơi cờ, hoặc chỉ nhận diện khuôn mặt. Vậy mà chỉ trong một thời gian ngắn, AI đã nhận dạng hình ảnh, dịch ngôn ngữ, trò chuyện với chúng ta bằng tiếng người, và còn viết được cả mã nguồn (tức là chương trình máy tính) giúp lập trình viên.

Từ đó, một câu hỏi được đặt ra: **sự bùng nổ này là ngẫu nhiên, hay có quy luật đứng sau?**

Nhóm em cho rằng đây không phải là chuyện ngẫu nhiên. Nó là biểu hiện của một quy luật trong **phép biện chứng duy vật** *(cách nhìn thế giới luôn vận động, các sự vật liên hệ và tác động lẫn nhau)*. Đó là **quy luật chuyển hóa từ những thay đổi về lượng thành những thay đổi về chất, và ngược lại.**

Nói đơn giản: *tích lũy đủ nhiều những thay đổi nhỏ, đến một lúc sẽ tạo ra một thay đổi lớn về bản chất.*

Giáo trình Triết học chia sự phát triển của khoa học kỹ thuật thành hai dạng:

- **Dạng tiến hóa:** phát triển từ từ, chủ yếu là tích lũy dần, không có đột biến.
- **Dạng cách mạng:** phát triển bằng những bước nhảy vọt, gắn với các phát minh lớn, làm đảo lộn hướng đi, quy mô và tốc độ phát triển của cả lĩnh vực.

Giáo trình cũng nhận định rằng ngày nay, dạng cách mạng đang chiếm ưu thế hơn hẳn. Và con đường của AI nằm đúng ở chỗ hai dạng này gặp nhau: **tích lũy từ từ trong thời gian dài, rồi nhảy vọt.**

*[Chuyển slide: mốc thời gian]*

Để các bạn hình dung, đây là vài mốc tiêu biểu của AI:

- **1950:** Alan Turing đặt câu hỏi *"Máy móc có thể suy nghĩ không?"*
- **1956:** tại Hội nghị Dartmouth, cụm từ "trí tuệ nhân tạo" chính thức ra đời.
- **1997:** máy tính Deep Blue đánh bại nhà vô địch cờ vua thế giới.
- **2012:** mạng nơ-ron AlexNet tạo bước ngoặt trong nhận dạng ảnh. *(Mạng nơ-ron là mô hình máy tính mô phỏng cách các tế bào thần kinh liên kết.)*
- **2017:** kiến trúc Transformer được công bố. *(Đây là thiết kế mô hình giúp máy hiểu và tạo văn bản tốt hơn.)*
- **2020:** mô hình GPT-3 ra đời.
- **Cuối 2022:** ChatGPT đến với công chúng.

Bài trình bày của nhóm em đi theo mạch sau: đầu tiên là cơ sở lý luận; tiếp đến là quá trình tích lũy về lượng dẫn đến bước nhảy về chất của AI; sau đó là chiều tác động ngược lại, khi chất mới đòi hỏi lượng mới. Cuối cùng là ý nghĩa và bài học cho sinh viên ngành mình.

---

## 2. PHẦN 1: CƠ SỞ LÝ LUẬN *(khoảng 3 phút)*

### 2.1. Quy luật này nằm ở đâu?

Phép biện chứng duy vật có **ba quy luật** phổ biến, đúng với cả tự nhiên, xã hội và tư duy. Mỗi quy luật trả lời một câu hỏi riêng:

1. **Quy luật thống nhất và đấu tranh giữa các mặt đối lập** trả lời: *vì sao sự vật vận động và phát triển?* Tức là tìm nguồn gốc và động lực.
2. **Quy luật phủ định của phủ định** trả lời: *sự phát triển đi theo hướng nào?* Đó là hướng đi lên, có kế thừa cái cũ.
3. **Quy luật lượng – chất**, chính là quy luật hôm nay nhóm em dùng, trả lời: ***sự phát triển diễn ra bằng cách nào?***

Đề tài của nhóm em hỏi "AI đã phát triển như thế nào", nghĩa là hỏi về **cách thức**. Vì vậy quy luật lượng – chất là công cụ phù hợp nhất. Giáo trình cũng khẳng định quy luật này tồn tại khách quan và phổ biến trong mọi lĩnh vực. Chính điều đó cho phép ta áp dụng nó vào Khoa học máy tính.

### 2.2. Chất và lượng là gì?

Đây là hai khái niệm nền tảng, em xin giải thích thật dễ hiểu.

**Chất** là cái làm cho sự vật *là chính nó* và khác với sự vật khác. Chất do các **thuộc tính cơ bản** tạo nên. *(Thuộc tính là các đặc điểm của sự vật; thuộc tính cơ bản là những đặc điểm quyết định bản chất.)*

Ví dụ: nước vẫn là nước dù nóng hay lạnh. Nhưng nếu tách nước thành khí hydro và oxy thì nó không còn là nước nữa.

Có một ý mà nhóm em xin nhấn mạnh, vì nó sẽ được dùng xuyên suốt bài: **muốn nói AI có "chất mới", ta phải chỉ ra được các thuộc tính cơ bản của nó đã thay đổi, chứ không phải chỉ là máy chạy nhanh hơn.**

**Lượng** là những gì đo đếm được bằng con số, như quy mô hay trình độ phát triển. Ví dụ: nhiệt độ 60 độ, lớp có 40 học sinh, hay mô hình AI có hàng trăm tỷ tham số. *(Tham số là những con số bên trong mô hình, được điều chỉnh khi học.)*

Có thể nhớ nhanh thế này:
- **Chất** trả lời câu hỏi: *"Nó là cái gì?"*
- **Lượng** trả lời câu hỏi: *"Nó nhiều hay ít, lớn hay nhỏ đến mức nào?"*

Giáo trình còn lưu ý: **ranh giới giữa chất và lượng chỉ mang tính tương đối.** Cùng một yếu tố, ở góc nhìn này là lượng, ở góc nhìn khác lại góp phần tạo nên chất. Điều này giúp ta tránh **cách nhìn siêu hình** *(cách nhìn coi các mặt đối lập tách rời hẳn nhau, không chuyển hóa được)*.

### 2.3. Độ, điểm nút và bước nhảy

Ba khái niệm này là "xương sống" của quy luật. Em giải thích bằng ví dụ **đun nước** cho dễ nhớ.

- **Độ** là khoảng mà lượng thay đổi nhưng sự vật vẫn là chính nó. Nước từ 20°C lên 90°C vẫn là nước lỏng. Đó là "độ".
- **Điểm nút** là giới hạn mà lượng chạm tới thì không thể giữ nguyên chất cũ nữa. Với nước, đó là 100°C.
- **Bước nhảy** là quá trình chuyển từ chất cũ sang chất mới. Nước lỏng chuyển thành hơi nước.

Giáo trình lưu ý thêm: bước nhảy diễn ra với **quy mô và nhịp độ khác nhau**. Nghĩa là không phải lĩnh vực nào cũng nhảy cùng lúc và theo cùng một kiểu. Ý này sẽ rất quan trọng khi ta xem các lĩnh vực của AI.

### 2.4. Chiều ngược lại: chất tác động đến lượng

Quy luật không chỉ đi một chiều. Khi chất mới ra đời, nó **quay lại tác động lên lượng**, làm thay đổi cả cấu trúc, quy mô, tốc độ và trình độ phát triển của sự vật.

Gộp hai chiều lại, ta có một chu trình:

> **Lượng tích lũy trong "độ" → chạm điểm nút → bước nhảy → chất mới ra đời → chất mới đòi hỏi lượng mới trong một "độ" mới → ...**

Chu trình này **không khép kín** như một vòng tròn. Nó đi lên theo **đường xoáy ốc**, tức là mỗi vòng quay lại gần điểm cũ nhưng ở tầm cao hơn.

*[Chuyển slide: sơ đồ xoáy ốc]* Có bộ công cụ này rồi, giờ mình cùng xem AI đã đi qua các bước đó như thế nào.

---

## 3. PHẦN 2: VẬN DỤNG - TÍCH LŨY VỀ LƯỢNG DẪN ĐẾN BƯỚC NHẢY VỀ CHẤT *(khoảng 5 phút)*

### 3.1. Xác định đối tượng phân tích

Trước khi vận dụng, phải nói rõ ta đang phân tích cái gì. Ở đây, đối tượng là **năng lực của hệ thống máy tính và AI.**

- **Lượng** gồm những thứ đo đếm và tích lũy được: tri thức, dữ liệu, sức mạnh tính toán, công nghệ và kỹ năng.
- **Chất** là các thuộc tính cơ bản, tức **cách thức và phạm vi hoạt động** của hệ thống.

Hai ví dụ cho thấy sự khác nhau về chất:
- Hệ thống chỉ làm theo chỉ dẫn được lập trình sẵn **khác về chất** với hệ thống biết tự học từ dữ liệu.
- Hệ thống chỉ giải một loại việc **khác về chất** với hệ thống xử lý được nhiều loại việc.

### 3.2. Bốn dòng tích lũy về lượng

AI hiện đại không phải kết quả của một phát minh duy nhất. Nó là kết quả của **bốn dòng tích lũy** chạy song song và hỗ trợ lẫn nhau.

**Dòng thứ nhất: Tri thức.** Đó là toán học, xác suất thống kê, tối ưu hóa và thuật toán, được tích lũy qua nhiều thế hệ. Đây đúng là dạng "tiến hóa", tiến bộ từ từ. Giáo trình nói tri thức "đi trước một bước, giữ vai trò dẫn đường" và thậm chí trở thành lực lượng sản xuất trực tiếp.

Một ví dụ rất rõ: thuật toán **lan truyền ngược** *(cách giúp mạng nơ-ron học bằng cách tự sửa sai từng bước)* đã được công bố từ **năm 1986**. Nhưng phải rất lâu sau mới có đủ điều kiện vật chất để nó phát huy tác dụng.

**Dòng thứ hai: Dữ liệu.** Đời sống được số hóa tạo ra lượng thông tin khổng lồ. Giáo trình gọi đó là **"bộ nhớ xã hội điện tử"** *(kho lưu trữ thông tin của cả xã hội bằng máy tính, mạng và thiết bị nhớ)*. Ví dụ: bộ dữ liệu **ImageNet** dùng để dạy AlexNet có hơn **1,2 triệu ảnh** đã được gán nhãn.

**Dòng thứ ba: Năng lực tính toán.** Thuật toán hay và dữ liệu nhiều mà máy yếu thì cũng không làm được gì. Bộ xử lý đồ họa **GPU** *(chip chuyên tính toán song song, ban đầu dùng cho đồ họa)* chính là điều kiện để huấn luyện AlexNet năm 2012.

**Dòng thứ tư: Công nghệ và kỹ năng.** Gồm hạ tầng mạng, hệ thống lưu trữ, phần mềm, công cụ và đội ngũ kỹ sư. Giáo trình gọi đây là cuộc cách mạng thông tin, cách mạng số, được xem là quan trọng nhất.

Bốn dòng này **kéo nhau đi lên**: dữ liệu lớn đòi hỏi máy mạnh; máy mạnh cho phép huấn luyện mô hình lớn hơn; và tri thức mới quyết định cách tận dụng cả hai.

### 3.3. Độ: lượng tăng nhưng chất chưa đổi

Đây là điểm dễ hiểu sai, nên em nói kỹ. Quy luật **không** nói rằng cứ tăng thêm một chút là có chất mới.

Từ năm 1956 trở đi, lượng của AI hầu như không ngừng tăng: thuật toán nhiều hơn, máy nhanh hơn, dữ liệu lớn hơn. Nhưng suốt thời gian rất dài đó, máy tính về cơ bản vẫn là **công cụ làm theo chỉ dẫn**: con người viết luật, máy chạy theo, và mỗi hệ thống chỉ giải một bài toán hẹp.

**Deep Blue là ví dụ điển hình.** Năm 1997, máy của IBM thắng nhà vô địch cờ vua Garry Kasparov, với khả năng tính khoảng **200 triệu thế cờ mỗi giây**. Về lượng, đó là bước tiến vượt bậc. Nhưng về chất thì sao?

- Deep Blue chọn nước đi bằng **hàm đánh giá** *(công thức chấm điểm thế cờ)* do các chuyên gia soạn sẵn.
- Ngoài bàn cờ ra, nó không làm được gì khác.

Tức là nó **vẫn "còn là nó"**, vẫn nằm trong giới hạn của độ.

Bài học tương tự đến từ hai giai đoạn **"mùa đông AI"** *(thời kỳ niềm tin và tiền đầu tư vào AI sụt giảm mạnh)*, vào giữa thập niên 1970 và cuối thập niên 1980 đến đầu 1990. Khi đó, người ta hứa hẹn cỗ máy "thông minh như người" trong lúc lượng tích lũy còn cách ngưỡng rất xa. Kết quả là thất vọng. Điều đó cho thấy **không thể "đốt cháy giai đoạn"**, tức không thể bỏ qua bước tích lũy.

### 3.4. Điểm nút và bước nhảy

Điểm nút **không đến từ một yếu tố đơn lẻ**. Nó chỉ xuất hiện khi *các dòng tích lũy cùng chạm ngưỡng.*

**Điểm nút thứ nhất: năm 2012.** Mạng AlexNet thắng cuộc thi nhận dạng ảnh ImageNet với tỷ lệ lỗi top-5 là **15,3%**. *(Top-5 nghĩa là máy đoán 5 đáp án, sai khi cả 5 đều trật.)* Đội xếp thứ hai dùng phương pháp truyền thống có tỷ lệ lỗi **26,2%**.

Điều đáng nói là AlexNet **không dựa vào một phát minh hoàn toàn mới**. Nó là sự **hội tụ của ba dòng lượng**: hơn 1,2 triệu ảnh có nhãn, GPU đủ mạnh, và vốn tri thức về mạng nơ-ron nhiều lớp đã tích lũy từ trước.

Và đây là thay đổi về chất: **trước đây con người phải mô tả từng đặc điểm cho máy; từ đây máy tự học đặc điểm từ dữ liệu.**

*[Chuyển slide: biểu đồ tỷ lệ lỗi. Nhấn giọng ở phần này]*

Nhìn vào dãy số sẽ thấy bước nhảy rất rõ. Tỷ lệ lỗi của đội thắng cuộc là **28,2% năm 2010**, rồi **25,8% năm 2011**. Nghĩa là mỗi năm chỉ giảm khoảng 2 điểm phần trăm, tiến chậm từng chút một. Nhưng sang **2012 tụt hẳn xuống 15,3%**, rồi **11,7% năm 2013**, **6,7% năm 2014** và **3,57% năm 2015**.

Tóm lại: *trước điểm nút, lượng nhích từng chút; sau điểm nút, cả lĩnh vực chuyển sang một quỹ đạo phát triển hoàn toàn khác.*

**Điểm nút thứ hai: giai đoạn 2020–2022.** Sau 2012, AI bước vào một "độ" mới. Học sâu *(mạng nơ-ron rất nhiều lớp)* đạt nhiều thành tựu, nhưng mỗi mô hình vẫn chủ yếu phục vụ một việc riêng. Trong lúc đó, lượng tiếp tục tăng: Transformer năm 2017, GPT-3 năm 2020 với **175 tỷ tham số**, và ChatGPT ra mắt công chúng ngày **30/11/2022**.

Một nghiên cứu năm 2022 của Wei và cộng sự ghi nhận hiện tượng **"năng lực đột sinh"** *(một khả năng mới bỗng xuất hiện khi mô hình lớn vượt một ngưỡng nhất định)*. Ở một số nhiệm vụ, mô hình nhỏ làm không hơn đoán mò. Nhưng khi quy mô vượt ngưỡng thì năng lực xuất hiện khá đột ngột. Đây chính là hình ảnh của **điểm nút** trong đời thực.

### 3.5. Mỗi lĩnh vực nhảy vào một thời điểm khác nhau

Nhớ lại ý giáo trình: bước nhảy có "quy mô và nhịp độ khác nhau". Thực tế AI đúng như vậy:

| Lĩnh vực | Điểm nút | Biểu hiện |
|---|---|---|
| Nhận dạng ảnh | 2012 | AlexNet: lỗi top-5 là 15,3%, so với 26,2% của phương pháp truyền thống |
| Nhận dạng tiếng nói | 2016 | Hệ thống của Microsoft đạt tỷ lệ lỗi 5,9%, ngang người chép lời chuyên nghiệp |
| Dịch máy | 2016 | Dịch máy nơ-ron của Google giảm khoảng 60% lỗi so với cách dịch theo cụm từ |
| Ngôn ngữ tổng quát | 2020–2022 | GPT-3 và ChatGPT: một mô hình làm được nhiều nhiệm vụ ngôn ngữ |
| Xe tự lái hoàn toàn | Chưa đạt | Chưa có hệ thống đạt cấp độ 5 (tự lái hoàn toàn); lĩnh vực vẫn "trong độ" |

*(Về "cấp độ 5": theo chuẩn SAE J3016, đây là mức xe tự lái hoàn toàn mọi điều kiện, không cần người.)*

Vì sao có sự chênh lệch? Có hai nhóm điều kiện:

- **Điểm nút đến sớm** nếu dữ liệu dễ số hóa và có nhiều, có thước đo đánh giá rõ ràng, và sai sót ít gây hậu quả nặng.
- **Điểm nút đến muộn** nếu lĩnh vực phải tương tác với thế giới thật và đòi hỏi mức an toàn rất cao, như xe tự lái.

Cùng một quy luật, nhưng điều kiện cụ thể khác nhau thì nhịp độ khác nhau.

### 3.6. Chất mới của AI biểu hiện ở đâu?

Nhắc lại tiêu chí: muốn nói có chất mới, phải chỉ ra **thuộc tính cơ bản đã đổi**. Nhóm em chỉ ra ba biểu hiện:

**Một, từ làm theo chỉ dẫn sang học từ dữ liệu.** Lập trình truyền thống thì con người đặt quy tắc. Học máy thì hệ thống tự tìm ra quy luật từ dữ liệu.

**Hai, từ công cụ chuyên biệt sang hệ thống đa nhiệm.** Trước kia mỗi công cụ chỉ làm một việc. Nay một hệ thống xử lý được nhiều loại việc và biết "suy rộng" ra những tình huống mới.

**Ba, máy móc tham gia vào xử lý thông tin và lôgích.** Đây là luận cứ sâu sắc nhất. Giáo trình chỉ ra cách mạng khoa học công nghệ bắt đầu giải phóng con người khỏi cả chức năng kiểm tra, quản lý, và cả chức năng **lôgích** *(tức suy luận, xử lý thông tin)*. Lao động dần trở thành **lao động xử lý thông tin**.

Do đó, AI **không chỉ là "máy tính cũ chạy nhanh hơn"**. Theo giáo trình, cách mạng kỹ thuật là bước nhảy về chất của máy móc, công cụ; cách mạng công nghệ là bước nhảy về chất của cách thức, quy trình. AI là một nấc tiếp theo trên con đường từ lao động thủ công, đến máy móc, rồi đến tự động hóa. Nó nằm trong **cách mạng công nghiệp lần thứ tư**, nơi nhiều công nghệ mới đang kết hợp thế giới vật lý, kỹ thuật số và sinh học.

Nhưng câu chuyện chưa dừng ở đây. **Khi chất mới xuất hiện, chính nó lại đặt ra những yêu cầu mới về lượng.**

---

## 4. PHẦN 3: CHIỀU NGƯỢC LẠI - CHẤT MỚI ĐẶT RA YÊU CẦU MỚI VỀ LƯỢNG *(khoảng 3 phút)*

Nhắc lại: khi chất mới ra đời, nó tác động ngược lại lượng, làm thay đổi kết cấu, quy mô, tốc độ và trình độ. Chất mới của AI gồm ba thứ: học từ dữ liệu, xử lý nhiều nhiệm vụ, và tham gia xử lý lôgích. Chính chúng đòi hỏi lượng mới ở bốn phương diện.

### 4.1. Quy mô mới

Khi AI được dùng rộng hơn, chỉ có **nhiều dữ liệu** là chưa đủ. Dữ liệu còn phải **phù hợp, được chuẩn hóa, làm sạch, bảo mật và cập nhật liên tục.** Đi kèm là hạ tầng tính toán, thiết bị lưu trữ, mạng, điện năng và vốn đầu tư ở tầm cao hơn.

Nói cách khác, phát triển AI không phải là làm một phần mềm. Đó là xây cả **hệ sinh thái** *(một mạng lưới nhiều thành phần cùng hỗ trợ nhau)* thông tin và công nghệ xung quanh nó.

### 4.2. Tốc độ mới

Giáo trình cho rằng việc **rút ngắn khoảng cách từ ý tưởng khoa học đến ứng dụng thực tế** là một trong những đặc điểm quan trọng nhất của cách mạng khoa học công nghệ. Con số minh họa rất ấn tượng:

- Thế kỷ 19: khoảng **60–70 năm**.
- Đầu thế kỷ 20: khoảng **30 năm**.
- Thập niên 90: chỉ còn khoảng **3 năm**.

Với AI, công cụ, cách làm việc và kỹ năng được cập nhật nhanh hơn bao giờ hết. Cá nhân và tổ chức buộc phải **học liên tục**.

Nhưng có một lưu ý: nhanh **không có nghĩa là chạy theo mọi xu hướng**. Nếu thiếu kiến thức nền và khả năng kiểm chứng thì càng chạy càng dễ lạc.

### 4.3. Kết cấu mới

Giáo trình chỉ ra rằng khoa học, kỹ thuật, công nghệ và sản xuất ngày nay **hòa lẫn vào nhau thành một khối thống nhất**. Với AI cũng vậy: một sản phẩm giá trị không thể chỉ do lập trình viên làm ra. Cần người hiểu bài toán thực tế, người xử lý dữ liệu, người xây mô hình, người kiểm thử, và cả người lo bảo mật, pháp lý, đạo đức.

**Ví dụ thực tế ở Việt Nam:** Năm 2023, Viettel thử nghiệm **trợ lý ảo pháp luật** cho hệ thống Tòa án. Sản phẩm dựa trên kho tri thức gồm hơn **160.000 văn bản pháp luật, 63 án lệ** *(bản án được chọn làm mẫu để áp dụng cho vụ việc tương tự)* và hơn **1 triệu bản án**, do Tòa án nhân dân tối cao cung cấp. Và để làm ra nó, các kỹ sư Viettel AI **phải học thêm kiến thức luật**.

Nghĩa là chất mới của AI **buộc kỹ thuật và chuyên môn của ngành ứng dụng phải gắn chặt với nhau.**

### 4.4. Trình độ mới của người lao động

Cuối cùng, mọi thay đổi ở trên dẫn đến yêu cầu về **trình độ mới của con người**. Giáo trình khẳng định người lao động cần **vừa có chuyên môn sâu, vừa hiểu biết rộng, vừa biết hợp tác.**

Với sinh viên Khoa học máy tính như chúng ta, có thể hiểu như sau:

- **Chuyên môn sâu:** nền tảng toán, thuật toán, lập trình và hệ thống.
- **Hiểu biết rộng:** biết lĩnh vực ứng dụng, tác động xã hội, giới hạn và rủi ro của AI.
- **Hợp tác:** biết trình bày vấn đề kỹ thuật và làm việc cùng người thuộc chuyên môn khác.

Ở tầm xã hội, khi thông tin và tri thức trở thành yếu tố quyết định, giáo trình chỉ ra rằng giáo dục con người là lĩnh vực quan trọng hàng đầu. Đầu tư cho **"tư bản người"** *(tức đầu tư vào con người, như học tập và đào tạo)* mang lại hiệu quả kinh tế và xã hội cao nhất. Vì vậy, đầu tư cho AI **không thể chỉ tính bằng máy móc, phần mềm hay dữ liệu.**

---

## 5. KẾT LUẬN *(khoảng 1 phút)*

Em xin tóm tắt lại bằng ba ý chính:

1. **Sự bùng nổ của AI không phải ngẫu nhiên.** Đó là kết quả của bốn dòng tích lũy (tri thức, dữ liệu, sức mạnh tính toán, công nghệ và kỹ năng), cùng chạm ngưỡng ở những thời điểm như 2012 và 2020–2022.
2. **Chất mới của AI** nằm ở việc học từ dữ liệu, xử lý nhiều nhiệm vụ, và tham gia vào xử lý lôgích. Nó không chỉ là máy chạy nhanh hơn.
3. **Bước nhảy về chất không phải điểm kết thúc.** Nó đòi hỏi lượng mới về quy mô, tốc độ, kết cấu và trình độ con người, tức là mở ra một vòng phát triển mới theo **đường xoáy ốc chứ không phải đường thẳng.**

*[Câu chuyển sang các phần còn lại, nếu nhóm có thêm phần ý nghĩa phương pháp luận và giải pháp cho sinh viên]*
Từ những phân tích trên, phần tiếp theo sẽ rút ra ý nghĩa phương pháp luận và những việc sinh viên Khoa học máy tính cần làm để không bị bỏ lại phía sau trong chu kỳ phát triển mới này.

*[Nếu đây là phần kết cuối cùng, dùng câu này thay thế]*
Nhóm em xin chốt lại bằng một thông điệp: **muốn có bước nhảy về chất, hãy kiên trì tích lũy về lượng một cách đúng hướng, và luôn chuẩn bị cho vòng phát triển tiếp theo.** Xin cảm ơn cô và các bạn đã lắng nghe!

---

## PHỤ LỤC: MẸO NÓI ĐỂ BUỔI THUYẾT TRÌNH TỰ NHIÊN HƠN

- **Mở đầu bằng câu hỏi** ("AI có đột nhiên xuất hiện không?") để thu hút sự chú ý của lớp.
- **Dùng ví dụ đun nước** xuyên suốt khi giải thích độ, điểm nút, bước nhảy. Đây là ví dụ dễ nhớ nhất.
- **Chậm lại ở các con số** (28,2% → 25,8% → 15,3%...). Bạn có thể chỉ vào biểu đồ trên slide thay vì đọc hết.
- **Với các trích dẫn giáo trình:** không cần đọc nguyên văn, chỉ cần nói ý chính bằng lời của mình và ghi nguồn trên slide.
- **Nếu bị thiếu giờ,** có thể rút gọn: bỏ phần 3.5 (bảng các lĩnh vực) và phần 4.2 (tốc độ mới), giữ lại AlexNet và Viettel làm ví dụ trọng tâm.
- **Nếu bị hỏi vặn "sao không gọi Deep Blue là bước nhảy?"**, trả lời: *Deep Blue tăng mạnh về lượng (200 triệu thế cờ/giây) nhưng vẫn làm theo luật con người viết và chỉ chơi được cờ, nên chất chưa đổi.*
