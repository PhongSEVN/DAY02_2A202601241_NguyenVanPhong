# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1   |Hoàng Anh Quân           |2A202601875             |Thành viên                   |
| 2   | Nguyễn Văn Phong          |  2A202601241           |Nhóm trưởng                     |
| 3   |   Phạm Khánh Linh        |2A202601507             | Thành viên                   |
| 4   | Vũ Huy Hoàng          |2A202601057             | Thành viên                   |
| 5   | Lê Thị Yến Nhi          |  2A202601031           | Thành viên                   |

---

# Phase 3 — Group Convergence: từ 15 candidates về 1

Nhóm 5 người, mỗi người pitch top 3 → 15 candidate problems.

Nhóm đi theo đúng 4 bước, **không bỏ phiếu ngay từ đầu**:

```text
Pitch top 3  →  gom trùng / cluster  →  shortlist  →  chấm nhanh + đồng thuận
```

Theo Double Diamond, nhóm đang ở **Diamond 1 — tìm đúng vấn đề**. Kết thúc Phase 3 nhóm chỉ chốt **candidate problem**, chưa viết Problem Statement.

## Bước 3.1 — Pitch top 3

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Quân | AI check form + đếm rep cho người mới tập gym | Người tập 0-6 tháng, tự tập, không thuê PT | Tự soi clip nhưng không có chuẩn để đối chiếu → sai form 2-3 tuần mới biết | Pain thật, người pitch là chính actor, có cả chấn thương làm bằng chứng |
| 2 | Quân | Viết & cập nhật tài liệu SQL schema / API | Dev sở hữu schema, BA đọc doc | Gõ lại kiểu dữ liệu + format bảng Markdown | Lặp lại đều nhưng generator thuần rule đã giải phần lớn |
| 3 | Quân | Khoanh vùng lỗi từ log dài | Người trực hệ thống | Phân biệt lỗi gốc vs lỗi dây chuyền | Metric rõ nhưng log có dữ liệu nhạy cảm |
| 4 | Phong | Nhận diện tài xế ngủ gật khi lái xe đường dài | Tài xế xe khách/xe tải chạy đêm, hành khách | Không ai đánh thức tài xế; buồn ngủ đến rất nhanh và tài xế **không tự nhận ra** | Impact xã hội lớn nhất trong 15 bài — nhưng nhóm không tiếp cận được actor |
| 5 | Phong | Tổng hợp biên bản họp CLB → action item hay bị rơi | Ban điều hành CLB | Sau họp không ai chốt ai làm gì, hạn nào | Quen thuộc, nhưng có thể chỉ cần template + rule nhắc hạn |
| 6 | Phong | Tìm lại quyết định cũ trong Discord/nhóm chat | Cả CLB | Search keyword ra hàng chục thread, phải đọc lại từng cái | Nhiều người đau nhưng scope dễ phình thành "search toàn năng" |
| 7 | Linh | Nhập tay dữ liệu đăng ký sự kiện từ Google Form sang Excel/báo cáo | Ban tổ chức sự kiện | Copy–paste thủ công, dễ sai họ tên/SĐT | Đây là bài **rule/automation thuần**, gần như không cần AI |
| 8 | Linh | Soạn caption/thông báo fanpage CLB lặp lại mỗi tuần | Ban truyền thông | Viết lại cùng một khuôn với nội dung khác nhau | AI hợp, nhưng impact nhỏ và metric là "hay hơn" — khó đo |
| 9 | Linh | Đọc tài liệu tiếng Anh dài cho môn học trước deadline | Sinh viên | Đọc hiểu + lọc phần cần dùng | Pain thật nhưng đã có quá nhiều tool sẵn, độ mới thấp |
| 10 | Hoàng | Nhận diện tư thế ngồi sai (gù lưng) khi học/làm việc lâu qua webcam | Sinh viên/dân văn phòng ngồi 6-8h/ngày | Ngồi sai nhưng chỉ nhận ra khi đã đau cổ vai gáy | **Rất giống bài #1 về bản chất** — cùng cluster |
| 11 | Hoàng | Trả lời tin nhắn hỏi lặp lại của khách shop online | Chủ shop nhỏ | 80% câu hỏi giống nhau: giá, size, ship | Rule/kịch bản sẵn giải được phần lớn |
| 12 | Hoàng | Ghi chép chi tiêu cá nhân rải rác nhiều ví/app | Cá nhân | Không gom được về một chỗ | Actor là "tôi", khó khái quát, metric mơ hồ |
| 13 | Nhi | Ôn thi từ nhiều nguồn rời rạc (slide + vở ghi + đề cũ) | Sinh viên trước kỳ thi | Không biết học phần nào trước | Cả nhóm đều là actor, dễ validate — nhưng bottleneck mơ hồ |
| 14 | Nhi | Sinh viên năm nhất hỏi lại cùng câu hỏi thủ tục (học phí, đăng ký môn) | Ban tư vấn, tân sinh viên | Trả lời lại cùng nội dung nhiều lần | FAQ + rule giải được ~80% |
| 15 | Nhi | Sắp lịch họp nhóm khi 5 người lệch lịch học | Nhóm sinh viên | Dò lịch chéo thủ công qua chat | Đã có Doodle/When2meet — bài đã được giải |

## Bước 3.2 — Gom trùng / cluster

| Cluster | Candidates | Pattern chung | Ghi chú |
|---|---|---|---|
| **A. Quan sát hành vi/tư thế con người theo thời gian thực rồi cảnh báo ngay** | #1 gym form, #4 tài xế ngủ gật, #10 tư thế ngồi | Con người đang làm sai hoặc đang gặp nguy hiểm **nhưng không tự nhận ra ngay**. Cần một "con mắt" quan sát liên tục và cảnh báo tức thì. Vấn đề gốc là **độ trễ feedback**, không phải thiếu kiến thức. | Cluster mạnh nhất: 3 người pitch độc lập nhưng ra cùng một dạng bài. Cả 3 đều là camera + nhận diện tư thế + rule ngưỡng. |
| **B. Tổng hợp / tra cứu thông tin từ nhiều nguồn rời rạc** | #3 log, #6 quyết định cũ, #9 tài liệu EN, #13 ôn thi | Thông tin có sẵn nhưng nằm rải rác; người dùng mất thời gian ở khâu tìm và lọc | Nhiều bài nhưng đều dễ phình scope và metric hay dừng ở "nhanh hơn" |
| **C. Viết/sinh nội dung lặp lại theo cùng một khuôn** | #2 doc SQL, #5 biên bản họp, #8 caption fanpage | Cấu trúc cố định, chỉ nội dung thay đổi | Phần khung giải được bằng template/generator; AI chỉ đáng dùng cho phần diễn đạt |
| **D. Trả lời câu hỏi lặp lại thay con người** | #11 khách shop, #14 tân sinh viên | 80% câu hỏi trùng nhau | Rule/FAQ giải được phần lớn → nhóm loại sớm |
| **E. Nhập liệu & điều phối thủ công** | #7 form→Excel, #12 chi tiêu, #15 lịch nhóm | Việc cơ học, có đáp án đúng/sai rõ ràng | **Đây là automation, không phải bài AI.** Nhóm loại ngay ở bước cluster |

Nhận xét của nhóm sau khi cluster:

```text
Cluster E bị loại đầu tiên vì độ mơ hồ gần bằng 0 — có đáp án đúng/sai rõ ràng thì
script/rule là đủ, đưa AI vào chỉ làm bài toán đắt hơn và rủi ro hơn.


Cluster D loại tiếp vì FAQ + kịch bản sẵn đã giải ~80% case.


Cluster C và B đều là bài "hợp lý nhưng đã có nhiều lời giải sẵn" — nhóm thấy nếu chọn
sẽ khó nói được mình thêm giá trị gì.


Cluster A nổi bật vì một lý do khác hẳn: đây là nhóm bài mà PHƯƠNG ÁN KHÔNG-AI KHÔNG
GIẢI ĐƯỢC PHẦN CỐT LÕI. Muốn biết mình đang tập sai form hay đang gật gù thì bắt buộc
phải có ai đó NHÌN mình liên tục — và đúng chỗ đó thì thuê người là bất khả thi về chi phí.
```

## Bước 3.3 — Shortlist

Nhóm lọc theo: actor có cụ thể không, bottleneck có phải một bước rõ ràng không, đo được không, vẽ before/after được không, có vừa phạm vi lab hôm nay không.

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| **#1 — AI check form + đếm rep cho người mới tập gym** | Người pitch chính là actor, có baseline thời gian tự bấm giờ, có hậu quả cụ thể (đau vai phải nghỉ 2 tuần), workflow một buổi tập vẽ được từng bước, boundary tự nhiên và dễ bảo vệ | "Form đúng" lấy chuẩn từ đâu? Cảnh báo sai giữa lúc gồng tạ nặng có nguy hiểm không? Camera ở phòng gym đông người có đủ góc không? |
| **#4 — Nhận diện tài xế ngủ gật** | Impact xã hội lớn nhất trong 15 bài, pain không thể chối cãi, cùng cluster A nên so sánh trực tiếp được với #1 | Nhóm **không tiếp cận được actor** để validate trong buổi lab; hậu quả khi AI sai là tính mạng; không thể pilot; nhóm không có ai hiểu domain vận tải |
| **#13 — Ôn thi từ nhiều nguồn rời rạc** | Cả 5 thành viên đều là actor → validate cực nhanh, evidence dễ lấy nhất | Bottleneck mơ hồ (không chỉ được **một** bước nghẽn); metric dừng ở "học hiệu quả hơn" — không đo được trong lab |

Ba candidate bị loại khỏi shortlist dù được nhắc nhiều: #10 (tư thế ngồi) bị coi là **bản nhẹ hơn của #1**, nếu chọn thì thà chọn #1 vì hậu quả rõ hơn; #6 và #5 bị loại vì dễ phình scope.

## Bước 3.4 — Chấm nhanh + đồng thuận

Chấm 1-5 cho từng tiêu chí. Điểm chỉ để **ép nhóm nói rõ lý do**, không phải để ra kết quả tự động.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **#1 Gym form + đếm rep** | 5 | 5 | 4 | 4 | 5 | 5 | 4 | **32** |
| #13 Ôn thi nhiều nguồn | 5 | 3 | 4 | 2 | 4 | 3 | 5 | 26 |
| #4 Tài xế ngủ gật | 4 | 3 | 5 | 3 | 2 | 4 | 2 | 23 |

Giải thích vài ô điểm thấp:

- **#4 "Làm trong lab" = 2:** nhóm không thể phỏng vấn tài xế đường dài, không thể quay dữ liệu thật, và không thể chạy thử — thử nghiệm sai trên xe đang chạy là không chấp nhận được.
- **#4 "Nhóm hiểu domain" = 2:** không ai trong nhóm lái xe đường dài. Mọi thứ nhóm biết đều là nghe kể lại.
- **#13 "Impact đo được" = 2:** nhóm không thống nhất được cách đo "ôn thi tốt hơn". Điểm thi phụ thuộc quá nhiều yếu tố khác.
- **#1 "Pain có evidence" = 4 chứ không phải 5:** baseline 12 phút/buổi hiện mới là **Quân tự bấm giờ cho chính mình**, chưa hỏi người khác. Đây là việc phải làm ở Phase 4.

### Candidate nhóm chọn

```text
#1 — AI check form + đếm rep cho người mới tự tập gym.


Phạm vi candidate nhóm chốt ở Phase 3 (chưa phải Problem Statement):
- Actor: người tập gym 0-6 tháng, tự tập, không đủ ngân sách thuê PT 1-1.
- Trọng tâm: hai bước trong một buổi tập — xác nhận form đúng/sai, và đếm rep + ghi log.
- KHÔNG ôm: giáo án tập luyện, dinh dưỡng/macro, chẩn đoán chấn thương.
```

### Vì sao chọn

1. **Non-AI không giải được phần cốt lõi.** Đây là tiêu chí quyết định của nhóm. App log tập (Strong, Hevy) lo được phần ghi số; gương và checklist form giúp được một phần — nhưng muốn biết mình sai ở đâu thì bắt buộc phải có người **nhìn**, mà thuê PT 1-1 dài hạn chính là thứ actor không kham nổi. Đối chiếu lại: #7, #12, #15 rule là đủ; #11, #14 FAQ là đủ; #2, #5 template là đủ. Chỉ cluster A có khoảng trống thật.

2. **Giá trị nằm ở độ trễ feedback, không phải ở số phút tiết kiệm.** Sai form ở tuần 1 mà tuần 3 mới biết thì cái mất không phải thời gian, mà là chấn thương. Rút độ trễ từ 2-3 tuần xuống còn ngay trong set là thay đổi về **chất**, không phải về lượng.

3. **Người pitch là chính actor và có hậu quả cụ thể để kể.** Cả nhóm nghe được một câu chuyện có thời điểm, có số buổi, có chấn thương thật — không phải một pain suy đoán.

4. **Vừa phạm vi lab.** Nhóm có thể ra phòng gym hỏi người thật ở Phase 4, và pilot chỉ cần một chiếc điện thoại.

5. **Boundary tự nhiên và dễ bảo vệ.** "AI chỉ nói gối bạn đang chụm vào trong; AI không kê giáo án, không chẩn đoán chấn thương" — ranh giới người-máy vạch được bằng một câu.

### Vì sao không chọn các candidate còn lại

**#4 — Nhận diện tài xế ngủ gật.** Đây là candidate nhóm tranh luận lâu nhất, và cần nói rõ lý do loại:

```text
Nhóm KHÔNG loại bài này vì nó ít quan trọng hơn. Ngược lại — nó quan trọng hơn bài gym
rất nhiều, vì hậu quả là tính mạng.


Nhóm loại nó CHÍNH VÌ hậu quả quá nặng:


- Khi AI bỏ sót (không cảnh báo dù tài xế đã gà gật), hậu quả là tai nạn. Không có
  fallback nào cứu được. Ở bài gym, AI bỏ sót thì tệ nhất là quay về đúng hiện trạng
  hôm nay — người tập tự soi clip như cũ.
- Nhóm không tiếp cận được actor. Không phỏng vấn được tài xế đường dài, không có
  dữ liệu thật, không được phép thử nghiệm trên xe đang chạy. Mọi thứ nhóm viết ra
  sẽ là phỏng đoán trong chân không — đúng thứ worksheet cảnh báo.
- Bài này đã có lời giải thương mại chín muồi (hệ thống DMS trên xe, và theo Phong nhớ
  thì châu Âu đã bắt buộc cảnh báo buồn ngủ trên xe mới — CẦN VERIFY LINK Ở PHASE 4,
  nhóm chưa kiểm chứng). Nếu chọn, nhóm sẽ đi vẽ lại một sản phẩm đã có mà không thêm
  được gì.
- Một bài toán an toàn tính mạng cần chuyên gia domain, dữ liệu chuẩn và quy trình
  kiểm định — không phải thứ 5 sinh viên nên chốt trong 4 tiếng.


Kết luận của nhóm: đây là bài toán ĐÚNG nhưng SAI NGƯỜI và SAI THỜI ĐIỂM.
```

**#13 — Ôn thi từ nhiều nguồn rời rạc.** Actor và evidence tốt nhất nhóm, nhưng không chỉ được **một** bước nghẽn cụ thể — cái đau trải đều khắp quá trình học. Metric dừng ở "học hiệu quả hơn", nhóm không thống nhất được cách đo trong lab.

**#10 — Tư thế ngồi gù lưng.** Cùng cluster, cùng kỹ thuật, nhưng hậu quả diễn ra chậm và mờ hơn → metric khó hơn bài gym. Nhóm ghi nhận đây là **hướng mở rộng tự nhiên** nếu bài gym chạy được.

**Cụm E (#7, #12, #15) và cụm D (#11, #14).** Loại từ bước cluster: độ mơ hồ thấp, có đáp án đúng/sai rõ → rule/script là đủ. Đưa AI vào chỉ làm bài đắt hơn và rủi ro hơn mà không tốt hơn.

**Cụm C (#2, #5, #8).** Phần khung giải được bằng template/generator, phần AI còn lại nhỏ và metric hay dừng ở "hay hơn".

### Nếu có disagreement, nhóm xử lý thế nào

```text
Bất đồng chính: Phong bảo vệ bài tài xế ngủ gật khá lâu, lập luận rằng chọn bài gym
là "chọn bài dễ" trong khi bài tài xế cứu được mạng người.


Cách nhóm xử lý — không bỏ phiếu để dập tắt tranh luận, mà đổi sang một câu hỏi
kiểm chứng được:


  "Trong 4 tiếng còn lại, nhóm lấy bằng chứng cho bài này ở đâu?"


Phong không trả lời được: không có tài xế để hỏi, không có dữ liệu, không có cách
thử nghiệm an toàn. Đây là lúc cả nhóm cùng thấy vấn đề không nằm ở giá trị của bài
toán mà nằm ở khả năng kiểm chứng của nhóm.


Nhóm chốt bằng đồng thuận, không bằng số phiếu. Hai điều nhóm ghi lại để giữ lập
luận của Phong:
1. Ghi rõ trong báo cáo rằng bài tài xế bị loại vì rào cản kiểm chứng và mức rủi ro,
   KHÔNG phải vì giá trị thấp.
2. Giữ lại tiêu chuẩn khắt khe mà Phong đặt ra cho cluster A — "AI bỏ sót thì sao?" —
   và bắt bài gym phải trả lời câu đó ở phần boundary và fallback.


Điều nhóm sẽ mang sang Phase 4 (do Hoàng challenge):
Nếu ở Phase 4 hỏi 5-7 người tập thật mà đa số nói họ KHÔNG lo về form (chỉ lo lười đi tập),
thì bottleneck nhóm đang giả định là sai, và nhóm sẽ phải sửa lại candidate — có thể
lùi về đúng phần đếm rep + auto-log, bỏ phần chấm form.
```

## Kết quả Phase 3

| Hạng mục | Kết quả |
|---|---|
| Số candidate ban đầu | 15 (5 người × top 3) |
| Số cluster | 5 (A → E) |
| Shortlist | 3 (#1 gym, #4 tài xế, #13 ôn thi) |
| Candidate được chọn | **#1 — AI check form + đếm rep cho người mới tự tập gym** |
| Cách chốt | Đồng thuận sau khi chấm nhanh, không bỏ phiếu |
| Việc phải làm ngay ở Phase 4 | (1) Verify baseline 12 phút/buổi với 5-7 người tập thật, vì hiện chỉ là số của một người. (2) Kiểm chứng giả định "người mới lo về form" — nếu sai thì đổi candidate, không thu nhỏ candidate (theo challenge của Linh). (3) Research xem app/thiết bị nào đã làm phần form, phần rep, và còn hở ở đâu. (4) Verify link quy định bắt buộc cảnh báo buồn ngủ ở châu Âu — nhóm đã nêu nhưng chưa kiểm chứng. |

---

# Phase 4 — Quick Validation + Research giải pháp

Mục tiêu của phase này **không phải** để chứng minh nhóm đã chọn đúng. Mục tiêu là tách **điều đã có bằng chứng** khỏi **giả định còn mở**, trước khi viết Problem Statement ở Phase 5.

Nguyên tắc nhóm tự đặt cho phase này:

```text
1. Không dùng số liệu nào mà nhóm chưa mở được nguồn gốc. Claim marketing của sản phẩm
   thương mại KHÔNG tính là bằng chứng.
2. Câu hỏi validation phải là câu có thể LÀM SAI giả định của nhóm. Câu nào hỏi xong ai
   cũng gật thì bỏ.
3. Chốt ngưỡng quyết định TRƯỚC khi đi hỏi, để không tự bẻ cong kết quả sau khi thấy số.
```

## Bước 4.1 — Quick validation

### 4.1.a — Bằng chứng nhóm đang có TRƯỚC khi đi hỏi

| Bằng chứng | Cỡ mẫu | Độ chắc | Vấn đề |
|---|---|---|---|
| Baseline 12'/buổi cho việc tra video + tự soi clip | N=1 (Quân tự bấm giờ) | Yếu | Tự đo cho chính mình, chưa lặp lại có kiểm soát |
| Đau vai trái ~2 tuần, phải bỏ hẳn bài đẩy ngực | N=1, sự kiện có thật | Trung bình | Là sự kiện thật nên không chối được, nhưng một ca không suy ra tỷ lệ |
| ~40% số set bị quên ghi log | N=1, ước lượng từ note | Yếu | Chưa đếm chính xác, chỉ nhìn note rồi ước |
| **Người khác cũng thiếu chuẩn đối chiếu**: bạn cùng phòng gym hỏi lại "bài này tập sao cho đúng" 2-3 lần/tuần (mục #10 bảng scan cá nhân) | 3-4 người, quan sát lặp lại | **Mạnh nhất trong nhóm bằng chứng hiện có** | Vì đây là tín hiệu từ người khác, không phải từ chính người pitch |
| Giá PT 1-1 khoảng 300-500k/buổi | Hỏi 1 phòng gym | Yếu | Một phòng không đại diện cho thị trường |

```text
Kết luận thẳng: toàn bộ evidence hiện có là N=1 cộng một quan sát gián tiếp.
Đủ để bảo vệ candidate ở Phase 3. KHÔNG đủ để viết Problem Statement.
```

### 4.1.b — Giả định cốt lõi cần phá

```text
GIẢ ĐỊNH CỐT LÕI: "Người mới tập gym lo về việc mình tập ĐÚNG KỸ THUẬT hay chưa."

Nếu giả định này sai — nếu người mới thật ra chỉ lo mình LƯỜI, không đi tập đều —
thì bottleneck nhóm chọn là bottleneck sai, và theo đúng challenge của Linh ở Phase 3,
nhóm phải ĐỔI candidate chứ không được thu nhỏ candidate về phần đếm rep + log
(vì phần đó Hevy đã giải xong và không cần AI).

Câu hỏi nhóm TUYỆT ĐỐI KHÔNG hỏi: "Bạn có muốn một app AI check form không?"
Ai cũng gật. Câu đó không phá được gì.
```

### 4.1.c — Option A: Interview script (hỏi trực tiếp tại phòng gym)

```text
Mở đầu bằng câu KỂ CHUYỆN, không mớm chủ đề form:

1. Buổi tập gần nhất mà bạn thấy bực hoặc khó chịu nhất là khi nào? Chuyện gì xảy ra?
2. Hôm nay bạn tập bài này theo ai/theo cái gì? (giáo án tự tìm, video, bạn chỉ, PT?)
3. Trong một buổi, bước nào tốn thời gian hoặc khó chịu nhất với bạn? Khoảng bao lâu?
4. Bạn có từng tự quay clip xem lại form không? Xem xong bạn có BIẾT mình sai ở đâu không?
5. Nếu đổi được đúng một thứ trong buổi tập, bạn muốn đổi gì?

Hai câu để phá giả định (hỏi cuối, sau khi họ đã tự nói):

6. Bạn từng đau khớp/chấn thương do tập chưa? Bao LÂU sau khi tập sai thì bạn nhận ra?
   → đo trực tiếp cái nhóm gọi là "độ trễ feedback". Nếu đa số trả lời "biết ngay",
     thì luận điểm trung tâm của nhóm sụp.
7. Nếu có app chấm form nhưng thỉnh thoảng báo sai, bạn có dùng không? Điều gì khiến
   bạn tắt nó đi?
   → lấy trực tiếp ngưỡng chịu đựng false positive từ actor, thay vì nhóm tự đoán.
```

### 4.1.d — Option B: Micro-survey (Google Form, 8 câu, ~2 phút)

| # | Câu hỏi | Dạng | Dùng để làm gì |
|---|---|---|---|
| 1 | Bạn tập được bao lâu rồi? | <6 tháng / 6-24 tháng / >24 tháng | Lọc đúng actor (0-6 tháng) |
| 2 | Bạn có thuê PT không? | Đang thuê / thuê vài buổi rồi thôi / chưa bao giờ | Xác nhận actor bị chặn ở chi phí |
| 3 | **Chọn 2 thứ cản trở bạn nhất** | lười/không đủ thời gian · không biết hôm nay tập gì · **không biết mình tập đúng kỹ thuật chưa** · đau/sợ chấn thương · không thấy tiến bộ | **Câu quyết định.** Đây là câu phá giả định cốt lõi |
| 4 | Bạn có tự quay clip xem lại form không? | chưa bao giờ / thỉnh thoảng / hầu như mỗi buổi | Kiểm chứng bước 4-5 trong workflow có thật không |
| 5 | Một buổi bạn mất khoảng bao nhiêu phút để tra video / soi clip? | số phút | **Thay baseline N=1 bằng trung vị nhiều người** |
| 6 | Bạn ghi log tập bằng gì? | không ghi / note điện thoại / app chuyên dụng / sổ | Kiểm chứng phần log có thật sự đau không |
| 7 | Bạn từng đau khớp do tập sai chưa? Bao lâu sau mới nhận ra? | chưa / ngay hôm đó / vài ngày / vài tuần | **Đo độ trễ feedback — luận điểm trung tâm của nhóm** |
| 8 | Mức độ đáng giải quyết của vấn đề này với bạn | 1-5 | Sàng nhanh |

### 4.1.e — Ngưỡng quyết định (chốt TRƯỚC khi chạy)

Nhóm ghi các ngưỡng này ra giấy trước khi đi hỏi, để sau khi thấy số không tự bẻ cong kết luận:

| Kết quả câu 3 (số người xếp "không biết mình tập đúng chưa" vào top-2) | Nhóm làm gì |
|---|---|
| ≥ 6/10 | **Giữ nguyên candidate.** Giả định cốt lõi đứng vững |
| 3-5/10 | **Giữ nhưng thu hẹp actor**: chỉ nhắm người mới tập các bài compound có tạ nặng (squat/deadlift/bench), không nhắm mọi người mới |
| < 3/10 | **Giả định sai → đổi candidate.** Không được lùi về phần đếm rep + log, vì phần đó Hevy đã giải và không cần AI |

| Kết quả câu 5 (trung vị thời gian tra cứu/soi clip) | Nhóm làm gì |
|---|---|
| ≥ 8 phút | Giữ metric "12' → dưới 4'" nhưng thay 12' bằng **trung vị thật**, bỏ số của Quân |
| 4-7 phút | Giữ metric nhưng hạ target tương ứng; ghi rõ trong PS rằng baseline gốc bị thổi phồng |
| < 4 phút | **Bỏ hẳn metric thời gian.** Chuyển metric chính sang **độ trễ phát hiện sai form** (câu 7), vì lúc đó tiết kiệm phút không còn là giá trị thật |

### 4.1.f — Bảng kết quả validation

| Nguồn | Số người / số mẫu | Người phụ trách | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|---|
| Interview tại phòng gym (Option A) | mục tiêu 5-7 | Quân (là người có mặt ở phòng gym 4 buổi/tuần) | `[CHƯA CHẠY — điền sau khi hỏi]` | `[CHƯA CHẠY]` | Theo bảng ngưỡng 4.1.e |
| Micro-survey (Option B) | mục tiêu 20-30 | Linh + Nhi phát trong lớp/CLB; Hoàng + Phong phát ở nhóm chat | `[CHƯA CHẠY — điền sau khi thu form]` | `[CHƯA CHẠY]` | Theo bảng ngưỡng 4.1.e |
| Hỏi giá PT tại ≥5 phòng gym | mục tiêu 5 phòng | Phong (nhóm trưởng, gom số) | `[CHƯA CHẠY]` | `[CHƯA CHẠY]` | Nếu giá thật thấp hơn nhiều so với 300-500k thì lập luận "actor bị chặn vì chi phí" yếu đi và phải viết lại phần Impact |

```text
Vì sao ba dòng này còn trống: nhóm chưa chạy được khảo sát thật trong khung giờ lab.
Nhóm chọn ĐỂ TRỐNG và ghi rõ ngưỡng quyết định, thay vì điền số ước lượng cho đẹp báo cáo.
Một con số bịa trong ô này sẽ đi thẳng vào Problem Statement ở Phase 5 và làm hỏng
mọi thứ phía sau. Đây là phần nợ nhóm phải trả trước khi chốt PS v1.
```

## Bước 4.2 — Research giải pháp đã có

Nhóm tìm xem ai đã giải bài này, giải đến đâu, và **giới hạn vật lý của kỹ thuật là bao nhiêu** — câu hỏi thứ ba mới là thứ đổi thiết kế của nhóm nhiều nhất.

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Nghiên cứu: Exercise quantification from single camera view markerless 3D pose estimation** (Mercadal-Baudart et al., *Heliyon*, 2024, N=8) | [pmc.ncbi.nlm.nih.gov/articles/PMC10951609](https://pmc.ncbi.nlm.nih.gov/articles/PMC10951609/) | Đo **sai số thật** của đúng kỹ thuật nhóm định dùng: 1 camera → góc khớp khi squat | Có số cụ thể: RMSE gối gập 4,3-5,8°; hông gập 3,5-4,9°; gối chụm/dạng 3,2-5,0°; thân người 5,0-6,2° | Kém nhất ở **shoulder flexion và ASIS asymmetry** với front squat / overhead squat (trong 15° nhưng vượt 10°). Chính tác giả ghi: cần test thêm ảnh hưởng của **ánh sáng, quần áo, vị trí camera** ngoài đời thật. Mẫu chỉ 8 vận động viên, trong lab, và đã **ưu tiên chọn bài ít tự che khuất** | **Phát hiện quan trọng nhất Phase 4.** Ngưỡng cảnh báo của nhóm KHÔNG được đặt nhỏ hơn ~6°, nếu không là đang cảnh báo trên nhiễu đo chứ không phải trên lỗi form. Và bài overhead press — một trong 4 bài Quân định làm — nằm đúng vào nhóm đo kém nhất → **loại khỏi pilot** |
| **MediaPipe Pose Landmarker** (Google AI Edge) | [ai.google.dev/edge/mediapipe/.../pose_landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker) | Bước 2 trong future workflow: nhận diện landmark cơ thể, trả cả toạ độ ảnh lẫn toạ độ thế giới 3D | Miễn phí, chạy on-device (Android/iOS/Web/Python) → không phải gửi video người tập lên server, giải luôn phần riêng tư | Chỉ trả về **toạ độ khớp**. Nó không biết và không quan tâm "form đúng" là gì | Phần khó của bài toán **không phải model** — model có sẵn và miễn phí. Phần khó là **định nghĩa ngưỡng đúng/sai và chịu trách nhiệm cho ngưỡng đó**. Đây đúng là câu Quân đã tự đặt ra để nhóm challenge ở Phase 2 |
| **Tonal — Smart View / Form Feedback** | [tonal.com/blogs/all/tonal-smart-view](https://tonal.com/blogs/all/tonal-smart-view) | Sản phẩm thương mại chín nhất: feedback form theo thời gian thực | Kết hợp **camera + 17 cảm biến trên chính máy tập** → biết cả lực kéo lẫn hình ảnh | Chỉ chạy trên chính thiết bị Tonal, giá thiết bị rất cao, và **không dùng được với tạ tự do ở phòng gym Việt Nam** | Sản phẩm mạnh nhất thị trường phải **kiểm soát cả thiết bị tập** mới dám phản hồi form. Nhóm chỉ có một chiếc điện thoại → phải khiêm tốn hơn nhiều về phạm vi: **3 bài, không phải mọi bài** |
| **Gymscore** — đối thủ trực tiếp gần nhất | [gymscore.ai](https://www.gymscore.ai/) | Chấm form từ video, 2500+ bài, có chấm điểm 0-100 và chat coaching | Không cần phần cứng riêng, freemium, phủ rất rộng | (1) Là **phân tích SAU khi quay hoặc upload** — tức đúng cái độ trễ feedback mà nhóm muốn xoá thì vẫn còn nguyên. (2) Trang chủ ghi "98% Accuracy Rate" **không kèm phương pháp đo**, và con số này mâu thuẫn với sai số đo được ở nguồn số 1 → **nhóm không dùng con số này** | Khoảng trống thật của nhóm **dịch chuyển**: không còn là "chưa ai chấm được form", mà là "chưa ai cảnh báo **ngay trong set** trên tạ tự do bằng một chiếc điện thoại, với ngưỡng công khai và biết tự im khi không chắc" |
| **Hevy — Workout Tracker** | [hevyapp.com/features/track-workouts](https://www.hevyapp.com/features/track-workouts/) | Bước 6-7: ghi log kg/set/rep, rest timer tự động, PR, biểu đồ tiến bộ | Miễn phí phần lớn, đã rất chín, có cả trên smartwatch | Vẫn phải **bấm tay từng set**; hoàn toàn không đụng tới form | Xác nhận đúng challenge của Linh ở Phase 3: **phần log không phải giá trị AI của bài này**. Nếu bỏ phần chấm form thì Hevy đã giải xong bài và nhóm không còn lý do tồn tại |
| **PAIR Guidebook — Errors + Graceful Failure** (Google) | [pair.withgoogle.com/guidebook-v2/chapter/errors-failing](https://pair.withgoogle.com/guidebook-v2/chapter/errors-failing/) | Không phải tool — là **mẫu thiết kế cho phần fallback** | Phân loại 7 kiểu lỗi, trong đó có **"background errors": lỗi mà cả hệ thống lẫn người dùng đều không nhận ra** | Là hướng dẫn thiết kế, không phải giải pháp kỹ thuật — nhóm vẫn phải tự viết ngưỡng | "Background error" chính là rủi ro Phong cảnh báo ở Phase 3 ("AI sai một cách thầm lặng") — hoá ra nó có tên gọi và có mẫu xử lý |

### Research takeaway

```text
1. KHÔNG build agent, và cũng không cần tự train model. Pose estimation đã miễn phí và
   chạy được on-device. Mức Workflow mà nhóm chọn ở Phase 3 được research xác nhận.

2. Khoảng trống của nhóm ĐÃ THU HẸP LẠI sau research — và đây là điều tốt.
   Trước research nhóm tưởng khoảng trống là "chấm form". Sai — Tonal và Gymscore đã làm.
   Khoảng trống thật còn lại là ba chữ: NGAY TRONG SET, trên tạ tự do, bằng điện thoại.

3. Xuất hiện một RÀNG BUỘC KỸ THUẬT CỨNG mà trước Phase 4 nhóm không hề biết:
   sai số đo góc khớp từ một camera là khoảng 3-6°. Mọi ngưỡng cảnh báo nhỏ hơn 6°
   là cảnh báo trên nhiễu. Điều này ép nhóm phải bỏ bớt bài tập, không phải thêm.

4. PHẠM VI PILOT BỊ CẮT do nguồn số 1: overhead press nằm đúng vào nhóm góc đo kém nhất
   (shoulder flexion, sai số >10°). Nhóm loại overhead press khỏi pilot.
   Còn lại: squat, deadlift, bench press.
```

## Bước 4.3 — Áp PAIR Guidebook vào thiết kế của nhóm

| Khuyến nghị của PAIR | Nhóm áp vào bài toán thế nào |
|---|---|
| Khi độ tin cậy thấp: **giải thích vì sao không đưa được kết quả, và đưa ra đường đi tiếp** — chứ không im lặng | Fallback ở Phase 3 mới chỉ nói "tắt cảnh báo". Chưa đủ. Sửa lại: app phải hiện rõ **"Không thấy đủ rõ khớp gối — hãy xoay điện thoại sang ngang, cách 2m"**, nghĩa là nói cả lý do lẫn hành động tiếp theo |
| **"Background errors"** — lỗi mà cả hệ thống lẫn người dùng đều không nhận ra — là loại nguy hiểm nhất | Đây là kịch bản tệ nhất của bài này: người tập **sai form nhưng app im lặng vì không nhận ra**, và người tập hiểu sự im lặng đó là "mình đang tập đúng". Nhóm phải phân biệt rõ trên màn hình: **"đang theo dõi, chưa thấy lỗi"** ≠ **"không theo dõi được"**. Hai trạng thái này tuyệt đối không được trông giống nhau |
| **Dùng trạng thái lỗi để dạy người dùng hệ thống cần input gì** | Trước mỗi buổi, app hướng dẫn đặt máy đúng góc; nếu chất lượng khung hình kém thì báo ngay từ đầu buổi chứ không đợi tới giữa set |
| **Khi hỏng, thường cách tốt nhất là trả quyền cho người dùng** | Người tập luôn có nút tắt cảnh báo trong 1 set / cả buổi, và app vẫn tiếp tục đếm rep + ghi log. Mất phần AI không được làm mất phần cơ bản |
| **Cho người dùng sửa/gán nhãn lại để cải thiện dữ liệu** | Sau buổi, người tập xem lại các rep bị flag và bấm **"cảnh báo này sai"**. Đây vừa là dữ liệu để chỉnh ngưỡng, vừa là **metric false-positive đo được thật** — thứ nhóm đang thiếu |

## Kết quả Phase 4

| Hạng mục | Kết quả |
|---|---|
| Validation đã chạy | Chưa. Instrument (interview script + survey 8 câu) đã dựng xong và **ngưỡng quyết định đã chốt trước** — đây là phần nợ phải trả trước khi viết PS v1 |
| Bằng chứng mạnh nhất hiện có | Tín hiệu từ người khác: 3-4 bạn cùng phòng gym hỏi lại "tập sao cho đúng" 2-3 lần/tuần |
| Nguồn research đã verify | 6 nguồn, tất cả đều mở được link |
| Phát hiện đổi thiết kế nhiều nhất | Sai số đo góc khớp từ 1 camera là **3-6°** → **mọi ngưỡng cảnh báo phải ≥ 6°** |
| Phạm vi bị **cắt** sau research | Bỏ **overhead press** khỏi pilot (nằm đúng nhóm góc đo kém nhất). Còn: squat, deadlift, bench press |
| Định vị lại khoảng trống | Không phải "chấm form" (Tonal, Gymscore đã làm) mà là **"cảnh báo ngay trong set, trên tạ tự do, bằng một chiếc điện thoại, có ngưỡng công khai và biết tự im khi không chắc"** |
| Số liệu bị nhóm **từ chối dùng** | "98% Accuracy Rate" của Gymscore — claim marketing không kèm phương pháp đo, mâu thuẫn với sai số đo được trong nghiên cứu |
| Điều kiện Go cho phần chấm form | ≥1 huấn luyện viên có chứng chỉ duyệt bộ ngưỡng cho 3 bài compound. Không có → pilot chỉ chạy phần đếm rep + log |
| Mang sang Phase 5 | (1) Chạy validation và điền bảng 4.1.f. (2) Viết lại fallback theo PAIR: phân biệt rõ "đang theo dõi, chưa thấy lỗi" với "không theo dõi được". (3) Thêm metric false-positive đo được từ nút "cảnh báo này sai" |

*(Đóng việc tồn đọng Phase 3)* EU **thật sự** bắt buộc hệ thống cảnh báo buồn ngủ (DDAW) theo Regulation (EU) 2019/2144: từ 06/07/2022 với kiểu xe mới và **07/07/2024 với mọi xe mới**. Nguồn: [EUR-Lex — DDAW](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=PI_COM:Ares(2021)1075107&rid=11) → lý do loại card #10 của Hoàng ở Phase 3 nay đã có nguồn, không còn là "nhóm nhớ mang máng".

---

# Phase 5 — Workflow + Problem Statement

Nguyên tắc của phase này: **vẽ workflow xong mới được viết Problem Statement**. Nếu viết PS trước, nhóm sẽ mô tả cái mình muốn làm thay vì cái đang xảy ra.

Workflow before/after cũng được nộp riêng ở file [02-group-problem-statement-workflow.md](02-group-problem-statement-workflow.md).

## Bước 5.1 — Current workflow bản nhóm

```text
CURRENT STATE — ~12' chết/buổi (N=1, CHƯA VERIFY), độ trễ feedback 2-3 TUẦN

[1 Xem note lịch tập: 1']
→ [2 Mở YouTube xem lại form bài lạ: 3'/bài]
→ [3 Vào set: tập + tự đếm rep trong đầu: suốt set]
→ [4 Dựng điện thoại quay clip: 2']          <-- handoff người↔người DUY NHẤT
→ [5 Tua clip tự soi form: 4']               <-- BOTTLENECK
→ [6 Ghi tay kg/set/rep vào note: 2']        <-- ~40% set bị bỏ quên
→ [7 Cuối tuần nhìn note quyết tăng tạ: 5'/tuần]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Handoff | Ghi chú |
|---|---|---|---|---|---|---|
| 1 | Người tập | Note tuần trước | Quyết định hôm nay tập gì, bao nhiêu kg | 1', đầu mỗi buổi (4 buổi/tuần) | Note → người tập | Note khuyết ~40% set nên quyết định đã dựa trên dữ liệu thiếu ngay từ bước 1 |
| 2 | Người tập | Tên bài tập | Hình dung trong đầu về "form đúng" | 3'/bài lạ, ~2 bài/buổi | YouTube → người tập | Mỗi video dạy một kiểu; không ai xác nhận người tập hiểu đúng |
| 3 | Người tập | Thanh tạ | Số rep đếm trong đầu | Suốt set | Không có | Mất đếm ở set cuối khi đã mệt |
| 4 | Người tập (hoặc nhờ bạn cùng phòng gym) | — | Clip 30-60 giây | 2', chỉ khi nghi ngờ | **Handoff người↔người duy nhất trong cả workflow** | Ngại làm phiền bạn → thực tế thường bỏ qua bước này |
| 5 | Người tập | Clip vừa quay | Một phán đoán: "chắc ổn" hoặc "hình như sai" | 4' | Clip → người tập | **BOTTLENECK** |
| 6 | Người tập | Trí nhớ ngắn hạn sau set | Dòng text trong note | 2'/buổi | Người tập → note | Quên ghi khi mệt → chính là nguồn của lỗi ở bước 1 và 7 |
| 7 | Người tập | Note khuyết | Kế hoạch tuần sau | 5'/tuần | Note → người tập | Quyết định tăng tạ dựa trên dữ liệu khuyết |

### Bottleneck chính

```text
Bước 5 — tua clip tự soi form.

Bước 5 là bottleneck vì nó là bước duy nhất TỐN THỜI GIAN MÀ KHÔNG TẠO RA OUTPUT DÙNG ĐƯỢC.
Người tập bỏ 4 phút vào và nhận lại một phán đoán không đáng tin — vì họ có dữ liệu (clip)
nhưng không có CHUẨN để đối chiếu. Mọi bước phía sau (có nên sửa form không, có nên tăng
tạ không) do đó chạy trên một input rỗng.

Hệ quả đo được: độ trễ phát hiện sai form là 2-3 TUẦN — tới khi cơ thể tự báo bằng cơn đau.

Cả workflow 7 bước chỉ có ĐÚNG MỘT handoff giữa người với người (bước 4, nhờ bạn quay clip),
và đó lại là bước hay bị bỏ nhất vì ngại. Mọi handoff còn lại đều là người ↔ một nguồn thông
tin câm (YouTube, note). Không có chỗ nào trong quy trình có người thật xác nhận điều gì.

Đây chính là lý do bài này không giải được bằng rule hay bằng tổ chức lại quy trình:
KHÔNG CÓ AI TRONG QUY TRÌNH ĐỂ TỔ CHỨC LẠI.
```

## Bước 5.2 — Future workflow bản nhóm

Phạm vi đã bị Phase 4 cắt: **chỉ 3 bài compound — squat, deadlift, bench press**. Overhead press bị loại vì nằm đúng nhóm góc mà nghiên cứu đo kém nhất (shoulder flexion, sai số vượt 10°).

```text
FUTURE STATE — dưới 4' chết/buổi, feedback NGAY TRONG SET
Chỉ 3 bài: squat · deadlift · bench press

[0 Kiểm chất lượng khung hình: 30"]              -- RULE (đủ sáng? đủ khớp trong khung? đúng khoảng cách?)
     └─ KHÔNG ĐẠT → "Không thấy rõ khớp gối — xoay điện thoại ngang, lùi ra 2m"
                    → dừng tại đây, KHÔNG chấm form, vẫn đếm rep
→ [1 Người tập chọn 1 trong 3 bài: 10"]          -- NGƯỜI
→ [2 Pose estimation → góc khớp: real-time]      -- AI (MediaPipe, chạy on-device, video không rời máy)
→ [3 So ngưỡng, mọi ngưỡng ≥ 6°: real-time]      -- RULE (ngưỡng do HLV có chứng chỉ duyệt)
→ [4 Phát cảnh báo giọng nói trong set]          -- RULE phát câu TEMPLATE do HLV soạn sẵn
→ [5 Đếm rep + auto-log: real-time]              -- AI
→ [6 Sau buổi: người tập xem lại 3 rep bị flag: 2']  <-- HUMAN BOUNDARY
→ [7 Bấm "cảnh báo này sai" nếu máy sai: 10"]    -- NGƯỜI → đây là dữ liệu đo false positive
→ [8 Người tập tự quyết tuần sau tăng tạ hay giữ: 1']  -- NGƯỜI
```

### Before / after impact

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| **Độ trễ phát hiện sai form** | 2-3 tuần | Ngay trong set | **Đây là metric chính.** Thay đổi về chất, không phải về lượng |
| Số bước | 7 | 9 | **Số bước TĂNG** — nhóm ghi thẳng thay vì giấu. Giá trị của bài này không nằm ở việc bớt bước |
| Số bước người phải tự làm | 7/7 | 3/9 (chọn bài, review rep flag, quyết tăng tạ) | Sáu bước còn lại là máy |
| Thời gian "chết"/buổi | ~12' *(N=1, chưa verify)* | Dưới 4' | Baseline này **phải thay bằng trung vị của ≥5 người** trước khi lên PS v1 |
| Tỷ lệ set có log | ~60% | 100% | **Không tính là giá trị AI** — Hevy đã giải phần này |
| Bottleneck chính | Bước 5 — soi clip không có chuẩn | Bước 6 — người tập review 3 rep bị flag | Bottleneck mới là **điểm kiểm soát**, và đã giảm từ "soi mò 4 phút" xuống "xem đúng 3 rep có vấn đề" |
| Risk mới | Không có | (1) false positive lúc gồng tạ nặng; (2) background error — im lặng bị hiểu thành "đang ổn"; (3) ngưỡng sai → sai hàng loạt | Thang fallback 1-4 nhắm đúng ba rủi ro này |

## Bước 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Người tập gym **chưa từng được ai sửa form trực tiếp** (thường là 0-6 tháng đầu), tự tập ở phòng gym bình dân, không đủ ngân sách thuê PT 1-1. Bối cảnh: ~4 buổi/tuần, đau nhất ở các bài compound có tạ nặng. |
| **Workflow** | 7 bước mỗi buổi: xem note lịch tập → mở YouTube xem lại form → tập và tự đếm rep → quay clip → tua clip tự soi form → ghi tay kg/set/rep vào note → cuối tuần nhìn note quyết định tăng tạ. Cả 7 bước chỉ có **một** handoff giữa người với người (nhờ bạn quay clip), và đó là bước hay bị bỏ nhất. |
| **Bottleneck** | **Bước 5 — tua clip tự soi form.** Không phải bước lâu nhất, mà là bước duy nhất tốn thời gian (~4') mà **không tạo ra output dùng được**: người tập có clip nhưng không có chuẩn để đối chiếu, nên xem xong vẫn không kết luận được mình sai ở đâu. Mọi quyết định phía sau chạy trên input rỗng. |
| **Impact** | Hậu quả chính **không phải thời gian mà là chấn thương**: sai form ở tuần 1 thì tuần 3 mới biết, khi cơ thể đã báo bằng cơn đau — trong nhóm đã có một ca đau vai trái ~2 tuần phải bỏ hẳn bài đẩy ngực. Hậu quả phụ: ~48 phút/tuần cho việc tra cứu và tự soi *(số của 1 người, chưa verify)*; log khuyết ~40% khiến người tập không biết mình có tiến bộ không → mất động lực. |
| **Success Metric** | (1) Độ trễ phát hiện sai form: 2-3 tuần → **ngay trong set**. (2) **Đồng thuận với HLV: chưa có → ≥80%** trên cùng 30 clip. (3) False positive: chưa có → <1 lần/buổi/bài, đo bằng nút "cảnh báo này sai". (4) Thời gian chết/buổi: ~12' *(N=1, chờ trung vị ≥5 người)* → dưới 4'. (5) Tỷ lệ set có log: 60% → 100% *(không tính là giá trị AI)*. |
| **Boundary** | **AI làm:** pixel → góc khớp; đếm rep; ghi log. **Rule làm:** kiểm chất lượng khung hình; so ngưỡng **≥6°** do HLV duyệt; phát câu **template** do HLV soạn. **Người làm:** chọn bài, review 3 rep bị flag, chấm "cảnh báo này sai", quyết tăng tạ. **AI KHÔNG:** kê giáo án, tư vấn dinh dưỡng, chẩn đoán chấn thương, tự tăng/giảm tạ, **tự sinh câu cảnh báo bằng ngôn ngữ tự do**. |

---

# Phase 6 — Rule / Workflow / Agent + Decision

## Bước 6.0 — Đặt bài toán vào ma trận độ mơ hồ × độ phức tạp

### Tự kiểm nhanh

| Câu hỏi | Trả lời của nhóm | Kết luận |
|---|---|---|
| Output có thể khác nhau mỗi lần mà vẫn chấp nhận được không? | **Không.** Một rep hoặc là gối chụm vào trong, hoặc không. Có đáp án đúng/sai | **Độ mơ hồ THẤP** |
| Cần phối hợp 3+ bước hoặc 3+ nguồn dữ liệu không? | Chỉ **một** nguồn (camera điện thoại). Pipeline 4 bước nối tiếp, cố định, không có nhánh động | **Độ phức tạp THẤP** |
| AI có cần tự quyết định bước tiếp theo không? | Không. Bước sau không phụ thuộc nội dung bước trước | **Rule/Workflow là đủ** |

### Bài toán nằm ở ô nào

```text
Ô: ĐỘ MƠ HỒ THẤP × ĐỘ PHỨC TẠP THẤP
→ Theo ma trận, ô này ghi: "Rule hoặc workflow đơn giản thường đủ."

Và nhóm VẪN không chọn Rule thuần. Đây là chỗ nhóm phải giải thích, không được lờ đi.
```

### Vì sao ma trận nói Rule mà nhóm vẫn không chọn Rule

```text
Vì ma trận đo độ mơ hồ của QUYẾT ĐỊNH, không đo độ mơ hồ của INPUT.

Quyết định trong bài này rõ như ban ngày:
    góc gối lệch quá ngưỡng → cảnh báo. Viết được thành if/else trong ba dòng.

Nhưng để CÓ được con số "góc gối" thì phải đọc được một khung hình video quay ở phòng
gym: ánh sáng vàng, người qua lại phía sau, áo rộng che khớp, góc máy lệch.
Không ai viết được if/else từ pixel.

Nói cách khác: bottleneck của bài này nằm ở TRI GIÁC, không nằm ở LUẬT.
AI được dùng đúng một lần, đúng chỗ đó, rồi trả quyền lại cho rule.
```

## Bước 6.1 — So sánh No AI / Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI / process fix** | Thuê PT 2-3 buổi đầu chỉ để học form 3 bài compound; checklist form dán ở khu tạ; tập trước gương; dùng Hevy để log | Đủ **nếu actor có tiền thuê PT**, hoặc nếu validation cho thấy người mới không lo về kỹ thuật | Đúng chỗ actor bị chặn (chi phí). Và người mới **không tự thấy lỗi của mình khi đang gồng** — gương chỉ giúp được người đã biết mình đang tìm gì | **Không chọn làm toàn bộ — nhưng bắt buộc phải khuyến nghị nó ngay trong app.** |
| **Rule / Script** | (a) Cảm biến IMU gắn thanh tạ + ngưỡng → đếm rep, đo bar path. (b) Ngưỡng góc thuần nếu có sẵn góc khớp | Đủ cho phần **đếm rep** và phần **so ngưỡng** | IMU biết thanh tạ đi đường nào nhưng **không biết đầu gối đang ở đâu** — nó không nhìn thấy cơ thể | **Chọn cho 3/5 bước máy**: bước 0 (kiểm khung hình), bước 3 (so ngưỡng ≥6°), bước 4 (phát câu template) |
| **Workflow** ✅ | Camera → **AI: pose estimation → góc khớp** → **Rule: so ngưỡng do HLV duyệt** → **Rule: phát template** → **Người: review rep bị flag** → **Người: chấm "cảnh báo này sai"** | Đủ vì các bước cố định và AI chỉ lo đúng **một** khâu tri giác | False positive giữa lúc gồng tạ nặng; background error; ngưỡng sai thì sai hàng loạt | **CHỌN** |
| **Agent** | Tự lập giáo án buổi tập, tự đổi bài khi thấy người tập mệt, tự gọi tool, tự điều chỉnh khối lượng theo tiến độ | Chỉ đủ lý do khi **bước tiếp theo phụ thuộc nội dung bước trước theo cách không đoán trước được** | Muốn Agent có nghĩa thì phải cho nó quyền **kê giáo án** — mà đó đúng là thứ nhóm đã cấm trong boundary | **Không chọn** |

Mức chọn:

```text
WORKFLOW.

Vì sao chọn:
- AI được dùng đúng MỘT lần, cho đúng MỘT việc mà không gì khác làm được:
  biến pixel thành góc khớp.
- Mọi thứ còn lại là rule với ngưỡng người soạn và người duyệt.
- Có điểm dừng của con người ở bước 6, và có kênh phản hồi lỗi ở bước 7.

Vì sao không chọn mức đơn giản hơn:
- No AI: giải được phần log (Hevy) và giúp một phần ở phần form (PT, gương, checklist),
  nhưng đúng chỗ actor bị chặn là chi phí PT — tức không giải được cho ĐÚNG actor này.
- Rule thuần: giải được 3/5 bước máy nhưng 0% bottleneck. Không viết được if/else từ pixel.

Vì sao không lên mức cao hơn:
- Agent chỉ có nghĩa nếu được quyền kê giáo án và tự đổi bài — đúng thứ boundary đã cấm.
- Không có bước nào mà nội dung bước trước làm đổi bước sau. Không có gì để "tự lập kế hoạch".
```

## Bước 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Người tập gym **chưa từng được ai sửa form trực tiếp** (thường 0-6 tháng đầu), tự tập ở phòng gym bình dân, không đủ ngân sách thuê PT 1-1. ~4 buổi/tuần, đau nhất ở bài compound tạ nặng |
| **Workflow** | 7 bước/buổi: xem note lịch tập → mở YouTube xem form → tập và tự đếm rep → quay clip → tua clip tự soi form → ghi tay vào note → cuối tuần quyết tăng tạ. Cả 7 bước chỉ có **một** handoff người↔người, và đó là bước hay bị bỏ nhất |
| **Bottleneck** | **Bước 5 — tua clip tự soi form.** Không phải bước lâu nhất, mà là bước duy nhất tốn thời gian (~4') mà **không tạo ra output dùng được**: có clip nhưng không có chuẩn để đối chiếu |
| **Impact** | Chấn thương là hậu quả chính: sai form tuần 1 → tuần 3 mới biết, khi cơ thể đã báo bằng cơn đau (đã có 1 ca đau vai ~2 tuần, bỏ hẳn bài đẩy ngực). Phụ: ~48 phút/tuần tra cứu và tự soi *(N=1, chưa verify)*; log khuyết ~40% → không biết mình có tiến bộ → mất động lực |
| **Success Metric** | (1) Độ trễ phát hiện sai form: 2-3 tuần → **ngay trong set**. (2) **Đồng thuận với HLV: chưa có → ≥80%** trên cùng 30 clip. (3) False positive: chưa có → <1 lần/buổi/bài, đo bằng nút "cảnh báo này sai". (4) Thời gian chết/buổi: ~12' *(N=1, chờ trung vị ≥5 người)* → dưới 4'. (5) Tỷ lệ set có log: 60% → 100% *(không tính là giá trị AI)* |
| **Boundary** | **AI làm:** pixel → góc khớp; đếm rep; ghi log. **Rule làm:** kiểm chất lượng khung hình; so ngưỡng **≥6°** do HLV duyệt; phát câu **template** do HLV soạn. **Người làm:** chọn bài, review 3 rep bị flag, chấm "cảnh báo này sai", quyết tăng tạ. **AI KHÔNG:** kê giáo án, tư vấn dinh dưỡng, chẩn đoán chấn thương, tự tăng/giảm tạ, **tự sinh câu cảnh báo bằng ngôn ngữ tự do** |
| **AI intervention point** | **Đúng một điểm:** giữa "camera thu khung hình" và "rule so ngưỡng". AI không xuất hiện ở bất kỳ chỗ nào khác trong 9 bước |
| **Mức chọn** | **Workflow.** Không phải Rule (không viết được if/else từ pixel). Không phải Agent (không có bước nào tự đổi theo bước trước; và Agent đòi quyền kê giáo án — thứ boundary đã cấm) |
| **Rủi ro & người thật kiểm tra** | **Rủi ro:** (1) false positive lúc gồng tạ nặng có thể tự nó gây nguy hiểm; (2) **background error** — máy im lặng bị hiểu thành "đang tập đúng"; (3) ngưỡng sai → sai hàng loạt. **Người kiểm tra:** HLV có chứng chỉ duyệt bộ ngưỡng trước khi bật cảnh báo, và chấm độc lập 30 clip để đo đồng thuận; người tập kiểm tra liên tục qua nút "cảnh báo này sai"; ba trạng thái hiển thị 🟢/🟡/🔴 tách bạch để chống rủi ro (2) |

## Bước 6.3 — Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | **Yes** | 7 bước có actor/input/output/handoff; actor được định nghĩa lại bằng tiêu chí hỏi một câu là biết |
| Baseline và success metric đã đo được chưa? | **Not Yet** | 5 metric đều đã có *cách đo* cụ thể — nhưng metric (2) và (3) chưa có số nào, và baseline metric (4) vẫn là N=1 |
| Có data/input đủ dùng chưa? | **Not Yet** | Chưa quay được clip nào có nhãn; chưa mời được HLV; chưa có bộ ngưỡng |
| Nếu AI sai, hậu quả có chấp nhận được không? | **Tách đôi** | Phần **đếm rep/log** sai → lệch vài số, chấp nhận thoải mái. Phần **cảnh báo form** sai → có thể góp phần gây chấn thương; chỉ chấp nhận được **sau khi** có HLV duyệt ngưỡng |
| Có người review/owner vận hành không? | **Yes** | Quân vừa là actor vừa là owner; HLV là người duyệt ngưỡng; nút "cảnh báo này sai" là kênh review thường trực từ người dùng |
| Có cách non-AI đơn giản hơn không? | **Yes cho một phần** | Hevy đã giải xong phần log. Thuê PT 2-3 buổi giải phần form **tốt hơn app** — và app có nghĩa vụ nói ra điều đó |

### Decision

```text
GO CÓ ĐIỀU KIỆN — tách làm hai, không chốt một cục.

  GO NGAY  → phần KHÔNG phát cảnh báo: đếm rep + auto-log + kiểm chất lượng khung hình
             + thu clip có nhãn.
  NOT YET  → phần CHẤM FORM và phát cảnh báo, cho tới khi đủ 3 điều kiện bên dưới.
```

### Lý do

```text
1. Nhóm không chốt một cục vì hai nửa của bài này có mức rủi ro khác hẳn nhau.
   Nửa đầu không nói gì với người tập nên không thể làm ai chấn thương.
   Nửa sau nói vào tai người đang gồng tạ nặng.

2. Nhóm áp đúng chuẩn đã dùng để xếp card của Nhi là Not Yet ở Phase 3:
   phần nào cần chuyên gia duyệt mà chưa có chuyên gia thì phần đó là Not Yet.

3. Điểm mấu chốt khiến đây là GO chứ không phải Not Yet toàn phần:
   PILOT CỦA NỬA ĐẦU CHÍNH LÀ DỤNG CỤ THU BẰNG CHỨNG CHO NỬA SAU.
   Chạy nửa đầu 2 tuần thì tự nhiên có 30 clip để đưa HLV chấm, có baseline thời gian
   thật từ nhiều người, và có số liệu chất lượng khung hình ở phòng gym thật —
   đúng ba thứ đang chặn nửa sau.
```

### Pilot nhỏ nhất (phần Go)

```text
Phạm vi:  1 bài duy nhất — SQUAT. Không phải 3 bài.
Người:    Quân + 4-6 người tập cùng phòng gym.
Thời gian: 2 tuần (~8 buổi).
Thiết bị: 1 điện thoại, MediaPipe chạy on-device, video KHÔNG rời máy.

Làm gì:
1. Đếm rep tự động + auto-log (thay việc bấm tay).
2. Kiểm chất lượng khung hình và hiện 🟢/🟡 — test luôn xem hai trạng thái này có
   thật sự phân biệt được bằng mắt ở phòng gym hay không.
3. Lưu 30 clip squat có gắn góc khớp máy đo được. KHÔNG hiện đánh giá form nào
   cho người tập.
4. Bấm giờ "thời gian chết" của từng người → lấy trung vị, thay baseline N=1.

Đo gì:
- Sai số đếm rep (đếm tay đối chiếu).
- Tỷ lệ buổi bị rơi vào trạng thái 🟡 ở phòng gym thật.
- Trung vị thời gian chết của ≥5 người.
```

### Nếu Not Yet — cần validate gì trước khi bật phần chấm form

```text
Ba điều kiện, phải đủ CẢ BA:

1. Mời được ≥1 huấn luyện viên có chứng chỉ duyệt bộ ngưỡng cho squat.
2. Đạt ≥80% đồng thuận giữa máy và HLV trên 30 clip thu được ở pilot 1.
   Dưới 80% → KHÔNG bật cảnh báo, quay lại chỉnh ngưỡng.
3. Có baseline thời gian thật từ ≥5 người, và kết quả câu 3 micro-survey đạt ngưỡng
   đã chốt ở Phase 4 (≥6/10 xếp "không biết mình tập đúng chưa" vào top-2).

Và một điều kiện thiết kế: mọi ngưỡng phải ≥ 6°, vì sai số đo góc khớp từ một camera
là 3-6° theo nghiên cứu ở Phase 4. Ngưỡng nhỏ hơn là cảnh báo trên nhiễu.
```

### Nếu No-Go — làm gì thay AI

```text
Kịch bản No-Go: câu 3 micro-survey cho kết quả <3/10 — người mới KHÔNG lo về form,
họ chỉ lo mình lười.

Lúc đó nhóm KHÔNG được lùi về "làm app đếm rep cho lành", vì Hevy đã giải xong.
Theo đúng ràng buộc Linh đặt ra ở Phase 3: bottleneck sai thì ĐỔI candidate,
không thu nhỏ candidate.

Việc nên làm thay AI, dù nhóm có làm tiếp hay không:
1. Khuyến nghị thẳng: thuê PT 2-3 buổi chỉ để học form 3 bài compound.
2. Dùng Hevy cho phần log — miễn phí và đã chín.
3. Dán checklist form ở khu tạ tự do — chi phí gần bằng 0.
```

### Rollback — điều kiện tắt

```text
- Sai số đếm rep >10% sau 2 tuần → dừng, vấn đề nằm ở khâu cơ bản nhất.
- >30% số buổi rơi vào trạng thái 🟡 (không theo dõi được) → sản phẩm không sống nổi
  ở phòng gym thật; dừng, hoặc đổi sang thiết bị cố định thay vì điện thoại.
- Người tập bấm "cảnh báo này sai" >3 lần/buổi liên tục 2 tuần → tắt cảnh báo, quay
  lại bộ ngưỡng, không cố vá.
- Có bất kỳ ca nào người tập nói bị mất tập trung/nguy hiểm vì cảnh báo giữa set
  → tắt cảnh báo real-time ngay, chuyển sang chấm điểm SAU set. Không chờ đủ mẫu.
```

## Kết quả Phase 6

| Hạng mục | Kết quả |
|---|---|
| Ô trong ma trận | Độ mơ hồ **thấp** × độ phức tạp **thấp** — ô mà ma trận nói "Rule là đủ" |
| Vì sao vẫn không chọn Rule | Ma trận đo độ mơ hồ của **quyết định**, không đo độ mơ hồ của **input**. Bottleneck nằm ở **tri giác**, không ở luật |
| Mức chọn | **Workflow** |
| Tỷ lệ Rule/AI trong các bước máy | **3 rule / 2 AI** — bài này gần Rule hơn cảm giác ban đầu |
| Điểm can thiệp của AI | **Đúng một điểm**: giữa camera và rule so ngưỡng |
| Decision | **Go có điều kiện, tách đôi**: Go ngay phần không phát cảnh báo; Not Yet phần chấm form |
| Pilot nhỏ nhất | 1 bài (squat), 4-6 người, 2 tuần, 1 điện thoại, **không hiện đánh giá form nào** |
| Vai trò thật của pilot 1 | **Dụng cụ đo**, không phải sản phẩm — nó sinh ra đúng 3 thứ đang chặn phần Not Yet |
| Điều kiện mở khoá phần chấm form | HLV duyệt ngưỡng · ≥80% đồng thuận trên 30 clip · baseline thật từ ≥5 người · mọi ngưỡng ≥6° |

---

*Day 02 Lab — 02 Group Problem Statement — Phase 3 Convergence · Phase 4 Validation & Research · Phase 5 Workflow & PS v0 · Phase 6 Rule/Workflow/Agent & Decision*
