---
title: "Sai lầm khi nhập tồn kho đầu kỳ: vì sao lệch 40 thùng lại bắt nguồn từ ngày nhập số dư"
description: "Phân tích 5 sai lầm khi nhập tồn kho đầu kỳ và quy trình 4 bước giúp doanh nghiệp nhỏ tránh lệch kho, sai giá vốn ngay từ đầu."
permalink: /posts/sai-lam-khi-nhap-ton-kho-dau-ky-vi-sao-lech-40-thung-lai-bat-nguon-tu-ngay-nhap/
tags: ["quan-ly-kho","ton-kho-dau-ky","van-hanh","sai-lam"]
---

Giả sử buổi kiểm kho định kỳ, sổ ghi 200 thùng nhưng đếm trên kệ chỉ còn 160. Cả kho dừng lại để tìm nguyên nhân. Người thì đổ tại khâu xuất hàng, người thì nghi nhân viên bán lẻ lấy nhầm. Nhưng khi lần ngược chứng từ, lỗi không nằm ở người đếm hôm nay. Lỗi nằm ở ngày nhập tồn kho đầu kỳ vài tháng trước, khi ai đó chỉ gõ vội một con số cho xong việc.

Vấn đề nằm ở chỗ: nhập tồn kho đầu kỳ thường bị xem như một thao tác hành chính. Người nhập chỉ cần gõ đủ số lượng là xong. Nhưng thực tế, đây là một quyết định kế toán kiêm vận hành có hệ quả kéo dài suốt kỳ.

## Vì sao tồn kho đầu kỳ không phải là thao tác nhập liệu

Tồn kho đầu kỳ mang hai lớp thông tin. Lớp thứ nhất là số dư kế toán: giá trị hàng tồn, phục vụ báo cáo tài chính, tính giá vốn, tính lãi gộp. Lớp thứ hai là số lượng vận hành: có bao nhiêu thùng, bao nhiêu cái, nằm ở kho nào, phục vụ mua bán và giao hàng hằng ngày.

Khi nhập tồn đầu kỳ, một con số sai không tự sửa được. Nó chảy vào giá vốn, làm sai lãi gộp, rồi lan sang mọi phiếu xuất kho sau đó. Sai một ngày, lệch cả kỳ. Sửa càng muộn càng tốn công đối chiếu chứng từ, vì lúc đó đã có hàng trăm phát sinh chồng lên nhau.

## Sai lầm 1: nhập bằng số lượng đang thấy trên kệ

Tình huống phổ biến: nhân viên kho đếm hàng buổi sáng rồi gõ luôn vào phần mềm cho xong. Họ tin rằng mắt thấy là đúng. Nhưng hàng đang đi đường, hàng đã nhận nhưng chưa lên kệ, hàng khách trả chưa nhập lại — tất cả đều không hiện trên kệ vào lúc đếm.

Cách đúng là đối chiếu với phiếu nhập mua, biên bản giao nhận và danh sách hàng đang về. Số dư đầu kỳ phải là số đã đối soát chứng từ, không phải số đếm nhanh trong một buổi sáng.

## Sai lầm 2: gộp nhiều kho, nhiều đơn vị tính vào một dòng

Ví dụ một doanh nghiệp có kho chính, kho trưng bày, kho hàng nhập khẩu. Đơn vị tính lẫn lộn giữa thùng và cái. Khi nhập tồn đầu kỳ, nhiều người gộp tất cả vào một dòng cho nhanh: một mã hàng, một con số, xong.

Giả sử mã hàng A có quy cách 24 cái/thùng. Tồn thực tế tại kho chính là 10 thùng và 6 cái lẻ, tại kho trưng bày là 3 thùng và 18 cái lẻ. Nếu gộp chung một dòng, người nhập có thể gõ "13 thùng" vì chỉ cộng số thùng chẵn 10 + 3 mà quên 24 cái lẻ, trong khi tổng đúng là 14 thùng, tức 336 cái. Tệ hơn, có người gõ "336" mà không ghi đơn vị, phần mềm lại hiểu là 336 thùng. Khi xuất kho, phần mềm chọn nhầm đơn vị, hoặc kho chính âm trong khi kho trưng bày dư. Nguyên tắc đơn giản: một dòng nhập phải tương ứng với một mã hàng, một kho và một đơn vị tính. Quy đổi ghi rõ ở cột riêng.

## Sai lầm 3: không chốt thời điểm cắt dữ liệu

Tình huống thường gặp: nhập tồn đầu tháng nhưng trong lúc nhập vẫn có phiếu mua, phiếu bán phát sinh. Cùng một lô hàng bị tính hai lần. Hoặc hàng đã xuất nhưng vẫn nằm trong số dư đầu kỳ.

Cách làm là chốt mốc cắt dữ liệu rõ ràng: đầu tháng, đầu năm tài chính. Trong khoảng thời gian nhập, khóa phát sinh mua bán. Ghi rõ mốc cắt trên phiếu. Ai cũng biết số liệu đang nói đến thời điểm nào.

## Sai lầm 4: bỏ qua giá vốn

Nhiều doanh nghiệp nhỏ chỉ nhập số lượng vì nghĩ rằng "chỉ cần biết còn bao nhiêu". Giá vốn để sau. Nhưng khi bỏ qua giá vốn, tồn kho đúng số lượng nhưng sai giá trị. Giá vốn bình quân sai, lãi gộp sai, báo cáo lãi lỗ không dùng được để ra quyết định giá bán.

Giả sử đầu kỳ tồn 100 cái, giá nhập đợt gần nhất là 120.000 đồng/cái. Trong kỳ nhập thêm 200 cái với giá 150.000 đồng/cái. Nếu đầu kỳ nhập sai giá vốn là 100.000 đồng/cái, giá vốn bình quân sẽ thành (100 × 100.000 + 200 × 150.000) / 300 = 133.333 đồng/cái thay vì đúng là (100 × 120.000 + 200 × 150.000) / 300 = 140.000 đồng/cái. Mỗi cái xuất bán lệch 6.667 đồng giá vốn, tương ứng lãi gộp bị thổi phồng đúng bằng số đó. Bán 300 cái, lãi gộp sai lệch 2 triệu đồng.

Cách đúng là nhập kèm đơn giá theo chứng từ mua gần nhất hoặc giá trị đã đối soát. Ghi rõ nguồn giá: từ phiếu nhập nào, ngày nào. Khi cần truy vết, có chỗ để lần.

## Sai lầm 5: không đối soát ngược sau khi nhập

Nhập xong, in báo cáo tồn, cất đi. Không ai kiểm lại. Sai sót nằm im vài tháng, đến kỳ kiểm kho mới lộ ra thì đã khó truy nguyên.

Cách đúng là đối soát ngược ngay trong một đến hai ngày sau khi nhập. So tổng số lượng, tổng giá trị với chứng từ gốc. Kiểm tra vài mã có rủi ro cao: hàng giá trị lớn, hàng có nhiều đơn vị tính, hàng thường xuyên xuất nhập.

## Cách làm gọn cho doanh nghiệp nhỏ: quy trình 4 bước

Trước khi nhập: chốt mốc cắt dữ liệu, tập hợp chứng từ, phân loại theo kho và đơn vị tính, xác định nguồn giá vốn.

Trong khi nhập: nhập theo từng kho riêng, không gộp dòng. Ghi rõ đơn vị và quy đổi. Khóa phát sinh mua bán trong khoảng nhập.

Ngay sau khi nhập: đối soát ngược tổng số lượng và tổng giá trị với chứng từ. Kiểm tra chéo vài mã trọng yếu.

Sau khi chốt: khóa sổ kỳ đầu. Lưu biên bản chốt số dư. Phân công người kiểm tra độc lập với người nhập.

## Checklist đối soát ngược cho một lần nhập tồn

Chạy checklist này trong vòng 48 giờ sau khi nhập xong:

- Tổng số dòng nhập có bằng số mã hàng thực tế đang quản lý không? Nếu thiếu dòng, có mã chưa được nhập.
- Với mỗi mã có đơn vị thùng và cái, quy đổi thùng–cái có khớp với quy cách đóng gói trên phiếu nhập mua không?
- Tổng giá trị tồn đầu kỳ có khớp với biên bản kiểm kê đã ký không? Lệch một đồng cũng phải tìm nguyên nhân.
- Chọn 3 mã có giá trị tồn lớn nhất: in phiếu nhập kho gần nhất, đối chiếu số lượng và đơn giá từng dòng.
- Chọn 2 mã có tần suất xuất nhập cao nhất: kiểm tra xem có phiếu xuất nào ghi nhận trước mốc cắt dữ liệu nhưng lại nằm sau ngày chốt không.

## Vai trò của phần mềm quản lý kho

Phần mềm quản lý kho cho doanh nghiệp nhỏ như [Acme](https://acme.example/vi/quan-ly-kho) cần hỗ trợ quy trình nhập tồn đầu kỳ. Khi chọn phần mềm, nên kiểm tra xem có đáp ứng các yêu cầu sau không: tách kho, tách đơn vị tính, có mốc cắt dữ liệu rõ ràng. Nếu phần mềm không làm được những điều này, bạn vẫn phải tự làm thủ công bằng Excel, và rủi ro lệch kho vẫn còn nguyên.

## Kết

Nhập tồn kho đầu kỳ là một quyết định, không phải một thao tác. Nó đòi hỏi đối soát chứng từ, tách bạch kho và đơn vị tính, chốt mốc cắt dữ liệu, nhập đủ giá vốn, và kiểm tra ngược sau khi nhập. Khi bạn đối xử với nó như một quyết định, lệch kho 40 thùng sẽ không còn là chuyện phải truy tìm vào buổi sáng kiểm kê.

Câu hỏi để tự kiểm tra lần nhập tồn gần nhất của bạn: bạn có nhớ nguồn chứng từ cho từng dòng số dư đầu kỳ không? Nếu không nhớ, có lẽ đã đến lúc làm lại quy trình.
