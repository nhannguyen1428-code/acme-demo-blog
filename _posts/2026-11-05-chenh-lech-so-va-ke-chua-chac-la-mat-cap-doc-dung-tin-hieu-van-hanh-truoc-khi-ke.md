---
title: "Chênh lệch sổ và kệ chưa chắc là mất cắp: đọc đúng tín hiệu vận hành trước khi kết luận"
description: "Chênh lệch sổ và kệ chưa chắc là mất cắp: cách phân loại nguyên nhân, đối chiếu ba lớp và dựng bảng theo dõi để tìm đúng gốc vấn đề."
permalink: /posts/chenh-lech-so-va-ke-chua-chac-la-mat-cap-doc-dung-tin-hieu-van-hanh-truoc-khi-ke/
lang: vi-VN
author:
  name: "Nguyễn An"
  url: "https://github.com/acme-an"
tags: ["quan ly kho","that thoat hang hoa","kiem ke","ban le nho"]
---

Chín giờ tối. Cửa hàng đã đóng, đèn huỳnh quang vẫn sáng trưng. Bạn và một nhân viên ngồi giữa lối đi, một tay cầm sổ tay, một tay cầm điện thoại để bấm máy tính. Kệ mì gói, nước mắm, sữa hộp được đếm lần lượt từ ngoài vào trong. Đến dãy mì tôm, bạn dừng lại: sổ ghi tồn 48 thùng, trên kệ chỉ còn 45. Chênh ba thùng. Cảm giác đầu tiên là nóng mặt, rồi ngay lập tức nghĩ đến chuyện mất cắp.

Nhưng lệch sổ chưa chắc là thất thoát. Đó là một tín hiệu vận hành, và tín hiệu này cần được đọc đúng trước khi kết luận bất kỳ điều gì. Cách đọc đúng nằm ở quy trình đối chiếu định kỳ, không phải ở việc soi camera hay quy trách nhiệm cho nhân viên.

## Bốn nguồn gây lệch và dấu hiệu nhận biết

Trước khi nghi ngờ ai đó, cần phân loại xem chênh lệch đến từ đâu. Trong cửa hàng bán lẻ nhỏ, có bốn nguồn chính.

**Sai nhập liệu.** Nhân viên kiêm nhiệm vừa bán hàng vừa nhập kho, một ngày có thể gõ nhầm số lượng hoặc ghi vào sai dòng. Dấu hiệu nhận biết: chênh lệch xuất hiện ngay sau ngày giao hàng, số chênh thường tròn trịa, và đối chiếu với phiếu nhập giấy thì thấy có một chuyến bị nhập sai.

**Sai đơn vị quy đổi.** Hàng nhập theo thùng nhưng bán theo gói, hoặc nhập theo bao nhưng bán theo kg. Dấu hiệu: chênh lệch lặp lại theo bội số cố định. Giả sử mì gói nhập theo thùng 30 gói, bán lẻ từng gói, nếu lệch đúng 30 hoặc 60 gói thì gần như chắc chắn là sai quy đổi thùng–gói, không phải mất cắp.

**Hàng hỏng hoặc trả nhà cung cấp chưa ghi sổ.** Trả hàng thường đi theo chuyến giao sau của nhà cung cấp, phiếu giấy kẹp ở cặp tài liệu nhưng chưa được cập nhật vào sổ. Dấu hiệu: lệch âm ở đúng mặt hàng vừa có đợt trả, có phiếu giấy nhưng không có bút toán tương ứng.

**Mất cắp thật.** Dấu hiệu khác biệt hẳn: lệch tập trung ở mặt hàng dễ tiêu thụ, giá trị cao, lặp lại ở cùng khung giờ hoặc cùng ca, và không tương ứng với bất kỳ chuyến nhập hay phiếu trả nào.

## Quy trình đối chiếu sổ–kệ ba lớp

Để phân biệt các nguồn trên, đừng nhảy thẳng từ "lệch sổ" sang "có người lấy hàng". Hãy đối chiếu theo ba lớp, mỗi lớp thu hẹp phạm vi nghi vấn.

**Lớp 1 — đếm theo vị trí kệ.** Chia kệ thành các ô có mã, mỗi ô một mặt hàng. Khi đếm, ghi nhận cả hàng trong thùng dự trữ phía sau, không chỉ hàng trưng bày phía trước. Nếu lệch, bạn biết chính xác lệch ở ô nào, mặt hàng nào, thay vì một con số tổng mơ hồ.

**Lớp 2 — đếm theo lô nhập.** Đối chiếu từng chuyến giao với phiếu nhập giấy. Kiểm tra quy đổi thùng–lốc–gói ngay tại thời điểm nhận hàng, không để đến cuối tháng mới xem lại. Giả sử một chuyến sữa hộp giao 5 thùng, mỗi thùng 48 hộp, nếu trên phiếu ghi 5 thùng mà kho nhập thành 200 hộp thì thiếu 40 hộp — sai số đã nằm ngay từ khâu nhận.

**Lớp 3 — đối chiếu chéo với phiếu nhập và phiếu bán trong kỳ.** Dùng công thức: tồn đầu kỳ + nhập − bán − trả = tồn lý thuyết. So tồn lý thuyết với số đếm thực tế. Chênh lệch còn lại sau khi đã đối chiếu đủ phiếu mới là con số đáng nghi thực sự.

## Bảng theo dõi chênh lệch theo tuần

Một con số lệch đơn lẻ không nói lên điều gì. Cần theo dõi liên tục để thấy mẫu hình. Hãy dựng một bảng đơn giản, trong đó quy cách đóng gói và đơn vị tính phải được ghi rõ ràng ngay từ đầu để tránh nhầm lẫn thùng–gói–chai:

```markdown
| Mặt hàng | Quy cách | Tồn sổ | Tồn thực | Chênh lệch | Đơn vị chênh | Ngày đếm | Ghi chú sự kiện trong tuần |
|---|---|---|---|---|---|---|---|
| Mì gói | Thùng 30 gói | 48 thùng | 45 thùng | -3 | thùng | 30/09 | Chuyến giao chiều thứ Bảy |
| Nước mắm | Chai 500ml | 60 chai | 57 chai | -3 | chai | 30/09 | Trả 3 chai cho NCC |
| Sữa hộp | Lốc 4 hộp | 25 lốc | 25 lốc | 0 | lốc | 30/09 | Không có sự kiện |
```

Mục đích của bảng là nhìn thấy quy luật. Một tuần lệch 3 gói là bình thường. Lệch 3 gói mỗi tuần ở cùng một mặt hàng, cùng một khung giờ, mới là tín hiệu cần điều tra.

Giả sử nước mắm lệch đều vào chiều thứ Bảy. Kiểm tra lại thì thấy đó là khung giờ giao hàng chuyến phụ, nhập liệu bị dồn sang hôm sau nên sổ chưa kịp cập nhật. Không có gì biến mất, chỉ là thời điểm ghi sổ bị trễ.

## Khi nào chuyển từ nghi ngờ sang xử lý

Cần đặt ngưỡng chênh lệch chấp nhận được theo từng mặt hàng. Hàng bán lẻ theo gói có ngưỡng khác hàng bán theo kg, vì sai số quy đổi và hao hụt tự nhiên khác nhau. Chênh lệch hệ thống — lặp lại, có quy luật — thường là lỗi quy trình. Chênh lệch ngẫu nhiên — một lần, không lặp — mới cần xem xét thêm.

Khi trao đổi với nhân viên, hãy nói về quy trình và con số, không nói về lòng tin. Hỏi "tuần này khâu nào dễ sai" thay vì "ai lấy hàng". Nguyên tắc: sửa quy trình trước, kỷ luật sau. Chỉ kỷ luật khi đã loại trừ ba nguồn lệch còn lại.

## Vai trò và giới hạn của phần mềm quản lý kho

Phần mềm quản lý kho như [Acme](https://acme.example/vi/quan-ly-kho) giúp khóa sổ theo thời điểm, ghi log thao tác nhập–xuất–trả, và cảnh báo lệch bất thường so với ngưỡng. Đó là công cụ tốt để phát hiện sớm và truy vết.

Nhưng phần mềm có giới hạn rõ ràng: nó không đếm hộ hàng trên kệ, không phân biệt được lệch do quy đổi với lệch do mất cắp. Dữ liệu đầu vào sai thì báo cáo cũng sai. Phần mềm chỉ là nơi lưu trữ và đối chiếu, còn chất lượng dữ liệu phụ thuộc vào người nhập.

## Checklist 5 việc làm được ngay tuần này

Nếu cửa hàng chưa có phần mềm, hãy bắt đầu bằng năm việc sau:

1. Chia kệ thành các ô có mã, mỗi ô một mặt hàng, dán nhãn rõ ràng.
2. Lập bảng theo dõi chênh lệch theo tuần như mẫu ở trên, điền ngay sau mỗi lần đếm, ghi rõ quy cách và đơn vị tính.
3. Kiểm tra lại toàn bộ phiếu trả hàng cho nhà cung cấp trong tháng, đối chiếu với sổ.
4. Quy định một khung giờ cố định trong ngày để nhập liệu, tránh dồn việc.
5. Đặt ngưỡng chênh lệch chấp nhận được cho từng nhóm hàng, ghi vào sổ tay vận hành.

Chênh lệch sổ và kệ không phải là bản án. Đó là tiếng chuông báo hiệu quy trình đang có khe hở. Đọc đúng tiếng chuông đó, bạn sẽ tìm được gốc rễ vấn đề — và thường thì gốc rễ nằm ở quy trình, không phải ở con người.
