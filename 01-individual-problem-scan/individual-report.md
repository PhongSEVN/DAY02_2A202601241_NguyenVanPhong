# 01 — Individual Problem Scan

## Phase 1 — Bảng scan (10 problems)

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | AI có thể tốt | Khó hình dung và vẽ sai phối cảnh nét đứt/liền trong không gian 3D | Học sinh cấp 3 | Vẽ xong hình mất 10 phút nhưng nhìn rối mắt không giải được |
| 2 | Tốn thời gian | Tìm và vẽ mặt cắt (thiết diện) của hình chóp với một mặt phẳng | Học sinh lớp 11 | Lúng túng, gạch xóa nhiều lần trên giấy |
| 3 | Tốn thời gian | Tìm góc giữa 2 mặt phẳng hoặc góc giữa đường và mặt | Học sinh lớp 11, 12 | Không nhìn ra đường vuông góc chung do vẽ hình 2D bị bẹt |
| 4 | Lặp lại | Phải vẽ đi vẽ lại một hình nhiều lần do góc nhìn ban đầu bị che khuất | Học sinh ôn thi | Mất 5-10 phút vẽ lại hình to hơn hoặc đổi góc nhìn |
| 5 | Lặp lại | Chậm chạp khi vẽ các bài toán quỹ tích (điểm di động) trong hình học phẳng | Học sinh cấp 2, 3 | Phải chấm rất nhiều điểm thủ công để mường tượng |
| 6 | AI có thể tốt | Không tưởng tượng được sự giao cắt giữa hình nón, trụ và mặt phẳng | Học sinh lớp 12 | Thường bỏ qua các câu hình học xoay tròn trong đề thi |
| 7 | Tốn thời gian | Đọc đề bài dài nhiều dữ kiện không biết bắt đầu vẽ từ đâu | Học sinh yếu/trung bình | Đọc đề 5 phút vẫn chưa vẽ được nét nào |
| 8 | Lặp lại | Làm trắc nghiệm Hình học cần vẽ hình siêu tốc nhưng toàn vẽ chậm | Học sinh thi Đại học | Tốn 2-3 phút chỉ để phác thảo hình cho 1 câu trắc nghiệm |
| 9 | Pain người khác| Giáo viên dạy Toán online khó diễn đạt hình không gian qua bảng 2D | Giáo viên Toán | Phải dùng tay mô tả lóng ngóng, học sinh không hiểu |
| 10 | AI có thể tốt | Chia tỷ lệ thể tích các khối đa diện phức tạp bị sai | Học sinh lớp 12 | Nhìn sai tỷ lệ cạnh trên hình vẽ tay dẫn đến tính toán sai |

---

## Phase 2 — Top 3 Problem Cards

### Tiêu chí chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Dựng hình 3D tổng quát từ đề bài (nét đứt/liền, phối cảnh) | Đây là rào cản đầu tiên và lớn nhất khiến học sinh sợ môn Hình | AI có hiểu chính xác ngôn ngữ của đề bài Toán không? |
| 2 | Tìm và dựng thiết diện cắt bởi mặt phẳng | Rất khó tưởng tượng trên giấy, học sinh hay bị ảo giác thị giác | Rủi ro AI cắt hình không chính xác |
| 3 | Xác định góc giữa 2 mặt phẳng | Tác động trực tiếp đến khả năng tính toán độ dài, diện tích | Cần AI đánh dấu rõ góc trên mô hình |

---

### CARD 1: Dựng hình 3D tổng quát từ đề bài *(card muốn pitch nhất)*

**Problem 1 câu:**
Khi giải bài tập hình học không gian, học sinh cấp 3 thường mất 5-10 phút loay hoay vẽ hình ra nháp nhưng vẫn vẽ sai phối cảnh (nét đứt/liền) khiến hình bị rối và không thể giải tiếp.

**Actor:** Học sinh lớp 11, 12 đang học hoặc ôn thi môn Hình học không gian.
**Thời điểm / bối cảnh:** Khi tự học, làm bài tập về nhà hoặc luyện đề Toán.

**Current workflow:**
1. Đọc đề bài Toán.
2. Phân tích các dữ kiện.
3. Cố gắng vẽ phác thảo hình ra nháp. (Bottleneck)
4. Sửa lại hình nhiều lần vì sai tỷ lệ hoặc các nét đè lên nhau gây rối mắt.
5. Nhìn hình để suy luận cách giải.

**Bottleneck:** Bước 3 và 4 - Dịch từ text sang hình vẽ 2D (nhưng mang tính chất 3D) rất khó, tốn thời gian và dễ nản.
**Impact:** Mất nhiều thời gian ôn tập, học sinh sinh ra tâm lý sợ môn Hình học, thường bỏ trắng các câu này trong đề thi.
**Success metric:** Giảm thời gian có được hình vẽ chuẩn xác xuống dưới 1 phút. Hình có thể xoay 3D để xem các góc khuất.
**Non-AI alternative:** Dùng phần mềm GeoGebra (nhưng học sinh phải tự vẽ thủ công từng điểm, từng đường rất phức tạp).
**AI hypothesis:** AI nhận input là "đề bài Toán bằng văn bản", tự động phân tích và sinh ra mô hình 3D có thể xoay/phóng to để học sinh quan sát.
**Quick gut:** Workflow.

### Workflow - Dựng hình 3D từ đề bài
**CURRENT STATE — 15 phút**
[1 Đọc đề: 2'] → [2 Phân tích dữ kiện: 3'] → [3 Vẽ phác thảo ra giấy: 5' (bottleneck)] → [4 Bôi xóa vẽ lại vì hình rối: 5'] → [5 Bắt đầu giải]

**FUTURE STATE — 3 phút**
[1 Học sinh chụp ảnh/nhập đề bài (text): 1'] → [2 AI phân tích dữ kiện thành thông số: 1'] → [3 Hệ thống render ra mô hình 3D tương tác: 1'] → [4 Học sinh xoay hình để quan sát và giải]

---

### CARD 2: Tìm và dựng thiết diện

**Problem 1 câu:**
Học sinh lớp 11 gặp khó khăn cực lớn trong việc tưởng tượng và vẽ thiết diện (mặt cắt) của hình chóp/lăng trụ khi bị cắt bởi một mặt phẳng, thường xuyên nối sai các đường nét.

**Actor:** Học sinh lớp 11.
**Thời điểm / bối cảnh:** Khi học chương Quan hệ song song và vuông góc trong không gian.

**Current workflow:**
1. Đọc đề bài và vẽ hình gốc.
2. Tìm các giao tuyến của mặt phẳng cắt với các mặt của hình gốc. (Bottleneck)
3. Vẽ nối các giao tuyến tạo thành thiết diện.
4. Tính diện tích thiết diện đó.

**Bottleneck:** Bước 2 và 3 - Rất khó nhìn ra các đường giao nhau bên trong khối hình nếu chỉ vẽ tay trên giấy.
**Impact:** Tốn hàng giờ cắn bút không giải được bài.
**Success metric:** Học sinh có thể nhìn thấy mặt phẳng cắt khối hình 3D animation trong vòng 1-2 phút.
**Non-AI alternative:** Làm mô hình giấy/cắt đất sét thủ công để xem trực quan (rất mất công).
**AI hypothesis:** Nhập đề bài, AI dựng hình và có thanh trượt (slider) cho phép mặt phẳng từ từ cắt qua khối 3D.
**Quick gut:** Workflow.

### Workflow - Dựng thiết diện
**CURRENT STATE — 25 phút**
[1 Vẽ hình gốc: 5'] → [2 Loay hoay tìm giao tuyến: 10' (bottleneck)] → [3 Nối bừa hoặc vẽ sai: 5'] → [4 Không tính được kết quả: 5']

**FUTURE STATE — 4 phút**
[1 Nhập đề: 1'] → [2 AI dựng khối gốc và mặt phẳng cắt: 2'] → [3 Học sinh xem animation cắt 3D: 1'] → [4 Nắm được hình dáng thiết diện để giải]

---

### CARD 3: Xác định góc giữa 2 mặt phẳng

**Problem 1 câu:**
Khi cần tính góc giữa hai mặt phẳng, học sinh không thể xác định được đường vuông góc chung do hình vẽ tay trên giấy 2D làm méo mó các góc vuông thực tế.

**Actor:** Học sinh lớp 11, 12.
**Thời điểm / bối cảnh:** Làm bài tập Hình học không gian liên quan đến góc và khoảng cách.

**Current workflow:**
1. Vẽ khối hình ban đầu.
2. Tìm giao tuyến của 2 mặt phẳng.
3. Dựng 2 đường thẳng vuông góc với giao tuyến. (Bottleneck)
4. Đánh dấu góc cần tính.

**Bottleneck:** Bước 3 - Học sinh hay bị ngộ nhận các góc nhìn vuông trên giấy là vuông, và góc không vuông lại tưởng là vuông.
**Impact:** Sai lầm ngay từ bước xác định góc dẫn đến toàn bộ phép tính đạo hàm/lượng giác phía sau đều vô nghĩa.
**Success metric:** Hiển thị rõ góc cần tìm và các đường kẻ phụ trên mô hình 3D trong 1 phút.
**Non-AI alternative:** Học thuộc lòng các mẫu (pattern) kinh điển của từng loại chóp.
**AI hypothesis:** AI nhận đề bài, dựng hình 3D và highlight (đổi màu) góc giữa 2 mặt phẳng, tự động kẻ thêm đường phụ trợ.
**Quick gut:** Workflow.

### Workflow - Xác định góc 3D
**CURRENT STATE — 15 phút**
[1 Vẽ hình: 5'] → [2 Kẻ đường vuông góc sai: 5' (bottleneck)] → [3 Đánh dấu góc sai: 2'] → [4 Tính toán ra kết quả ra sai: 3']

**FUTURE STATE — 3 phút**
[1 Nhập đề: 1'] → [2 AI dựng hình 3D: 1'] → [3 AI highlight góc và vẽ đường phụ trợ: 1'] → [4 Học sinh quan sát và tự tính độ lớn của góc]

---

## Card tôi muốn pitch nhất

**Card 1: Dựng hình 3D tổng quát từ đề bài.**

**Vì sao:**
- Đây là rào cản ĐẦU TIÊN và LỚN NHẤT khiến học sinh sợ môn Hình học không gian. Chưa vẽ được hình thì không thể giải bài — mọi bước phía sau (thiết diện, góc, khoảng cách) đều bị chặn ngay từ đây.
- Thực chất cả 3 card của tôi là **ba tính năng của cùng một sản phẩm**: dựng hình → cắt thiết diện → highlight góc. Nếu giải được Card 1, hai card còn lại là phần mở rộng tự nhiên.
- Pain rất phổ biến: ai đã từng học Toán hình không gian cấp 3 đều trải qua cảm giác "vẽ mãi không xong, nhìn mãi không ra". Workflow before/after vẽ được sạch nhất trong 3 card (15 phút → 3 phút).
- Non-AI (GeoGebra) đã tồn tại nhưng đòi hỏi người dùng tự vẽ thủ công từng điểm, từng đường — tức vẫn chưa giải bottleneck "dịch từ text sang hình".

**Câu hỏi tôi muốn nhóm challenge:**
1. Nhóm có ai đang là actor (học sinh lớp 11-12) không? Nếu không, validate kiểu gì?
2. Phần khó thật nằm ở đâu — render 3D hay parse đề bài tiếng Việt thành ràng buộc hình học? Nếu AI hiểu sai một dữ kiện thì hình sai hoàn toàn mà học sinh không đủ trình phát hiện.
3. Đây là sản phẩm "nice to have" (tính năng nhỏ) hay giải được pain thật sự của actor?
