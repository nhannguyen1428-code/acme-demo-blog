---
title: "Sắp xếp kệ hàng là thiết kế hệ thống nhớ, không phải trang trí kho"
description: "Cách sắp xếp kệ hàng trong kho nhỏ để ai cũng tìm đúng và đếm đúng: mã vị trí, chia khu theo tần suất, quy tắc đếm và ví dụ cụ thể."
permalink: /posts/sap-xep-ke-hang-la-thiet-ke-he-thong-nho-khong-phai-trang-tri-kho/
lang: vi-VN
author:
  name: "Nguyễn An"
  url: "https://github.com/acme-an"
tags: ["quan-ly-kho","sap-xep-ke-hang","kiem-ke","cua-hang-nho"]
---

Bạn bước vào kho, cần lấy một thùng mì gói để bổ sung ra quầy. Kho chỉ rộng chừng mười lăm mét vuông, kệ sắt bốn tầng đặt sát tường. Giả sử bạn mất mười phút để tìm đúng thùng mì, rồi đếm tồn ba lần vẫn ra ba con số khác nhau. Vấn đề không nằm ở diện tích. Vấn đề nằm ở chỗ cách bố trí kệ đang dựa vào trí nhớ của một người, và khi người đó nghỉ một buổi, cả kho trở thành mớ hỗn độn.

Sắp xếp kệ hàng không phải là việc dọn dẹp cho gọn mắt. Đó là việc thiết kế một hệ thống để bất kỳ ai bước vào kho cũng có thể tìm đúng vị trí và đếm đúng số lượng mà không cần hỏi ai. Bài viết này hướng dẫn từng bước để làm việc đó trong một kho nhỏ của cửa hàng tạp hoá, ki-ốt mặt tiền hay nhà phố.

## Nguyên tắc gốc: mã hoá vị trí thay vì ghi nhớ

Câu nói “hỏi chị Lan, chị ấy biết hết” không phải là một hệ thống. Chị Lan có thể nghỉ, chuyển việc, hoặc đơn giản là quên. Khi kho vận hành dựa vào trí nhớ của một người, mỗi lần kiểm kê là một lần đối chiếu với trí nhớ đó, và kết quả thường sai lệch.

Cách thay thế là mã hoá vị trí. Mỗi vị trí trong kho được gán một mã cố định theo cấu trúc: khu → kệ → tầng → ô. Ví dụ mã `A-K2-T3-O4` có nghĩa: khu A, kệ số 2, tầng thứ 3, ô số 4. Mã này không mô tả hàng hoá, chỉ mô tả vị trí vật lý. Khi hàng đổi chỗ, mã vị trí vẫn giữ nguyên; bảng quy chiếu sẽ cho biết mã đó đang chứa loại hàng gì.

Nhãn dán phải đọc được từ lối đi. Dùng cùng một kiểu chữ, cùng một kích thước và dán ở cùng một vị trí trên mọi kệ. Ví dụ: nhãn luôn dán ở mép trái của mỗi ô, chữ in hoa, cao ít nhất hai phân. Người mới đi một vòng kho là hiểu cách đọc mã mà không cần giải thích nhiều.

## Chia khu theo tần suất lấy hàng và nhóm hàng

Trong kho nhỏ dưới 50 mét vuông, không nên chia quá nhiều khu. Ba vùng là đủ:

- **Vùng nóng**: hàng lấy mỗi ngày, đặt ngang tầm tay, từ tầng 1 đến tầng 3.
- **Vùng ấm**: hàng lấy vài lần mỗi tuần, đặt ở tầng cao hơn hoặc phía trong.
- **Vùng lạnh**: hàng dự trữ, hàng mùa vụ, đặt trên cao nhất hoặc ở góc sâu.

Nhóm hàng theo logic bán hàng, không theo cảm tính. Trong cửa hàng tạp hoá, nhóm mì gói đặt gần nhóm gia vị vì thường được lấy cùng lúc. Nước mắm và dầu ăn đặt ở tầng thấp vì nặng. Bột giặt để tách riêng, tránh mùi ám vào thực phẩm. Quy tắc đơn giản: hàng nặng ở tầng thấp, hàng nhẹ ít lấy ở tầng cao, hàng dễ vỡ không đặt trên lối đi.

Kệ sắt mua sẵn thường có bốn đến năm tầng. Hãy đánh số kệ theo chiều đi vào kho: kệ đầu tiên bên trái là K1, kệ tiếp theo bên phải là K2, cứ thế tăng dần. Người mới đi một vòng là hiểu sơ đồ mà không cần bản vẽ phức tạp.

## Quy tắc đếm được: mỗi ô một đơn vị đếm

Một ô kệ chỉ chứa một đơn vị đếm. Đơn vị đếm có thể là một thùng mì, một két nước ngọt, hoặc một chồng gồm mười chai nước mắm. Khi đếm, bạn không đếm từng gói mì bên trong thùng, mà đếm số thùng còn nguyên cộng với số gói lẻ ở khay riêng.

Nhãn ô phải ghi rõ số lượng tối đa chứa được và đơn vị tính. Ví dụ: `A-K1-T2-O1 | Mì gói loại 30 gói/thùng | Tối đa 6 thùng`. Khi ô đầy, bạn biết không thể nhập thêm mà không cần kiểm tra.

Để biết khi nào cần nhập hàng, dùng dấu hiệu thiếu hụt. Cách đơn giản nhất là vẽ một vạch mức tối thiểu trên thành kệ: khi chồng hàng thấp hơn vạch, cần nhập thêm. Cách khác là treo thẻ hai mặt: mặt xanh nghĩa là đủ, mặt đỏ nghĩa là cần nhập. Nhân viên lấy hàng thấy mặt đỏ thì lật thẻ và ghi vào phiếu cần nhập.

Không để hai loại hàng chung một ô. Hàng lẻ như gói mì rời, chai dầu gió, gói bột ngọt nhỏ để vào khay riêng có nhãn “hàng lẻ”. Khi đếm, đếm ô đầy trước, cộng ô lẻ sau, ghi vào sổ theo đúng mã vị trí. Trình tự này giúp lần đếm sau lặp lại đúng y hệt, không bỏ sót ô nào.

## Ví dụ cụ thể: bố trí lại một kệ 4 tầng cho cửa hàng tạp hoá

Giả sử cửa hàng có một kệ sắt 4 tầng đang để lộn xộn: mì gói nằm cạnh bột giặt, nước mắm đặt trên cao, gia vị trộn lẫn với dầu ăn. Nhãn viết tay dán lộn xộn, có ô không nhãn, có ô hai nhãn chồng lên nhau.

Sau khi bố trí lại, kệ này được chia như sau:

```
Kệ K1 — Khu A (hàng bán chạy)
Tầng 1: Nước mắm, dầu ăn — hàng nặng, lấy mỗi ngày
  O1: Nước mắm chai 500ml — tối đa 24 chai
  O2: Dầu ăn chai 1 lít — tối đa 12 chai
Tầng 2: Mì gói — lấy mỗi ngày
  O1: Mì gói loại 30 gói/thùng — tối đa 6 thùng
  O2: Mì ly — tối đa 4 thùng
  O3: Hàng lẻ mì gói — khay riêng
Tầng 3: Gia vị — lấy vài lần mỗi tuần
  O1: Bột ngọt — tối đa 10 gói
  O2: Nước mắm chai nhỏ — tối đa 20 chai
  O3: Muối, đường — tối đa 15 gói
Tầng 4: Dự trữ — lấy khi hết hàng ở tầng dưới
  O1: Mì gói dự trữ — tối đa 10 thùng
  O2: Nước mắm dự trữ — tối đa 8 két
```

Ví dụ trước khi bố trí lại, người làm kho phải nhớ mơ hồ kiểu “mì gói ở đâu đó tầng 2 hoặc tầng 3”. Sau khi bố trí, chỉ cần đọc mã `A-K1-T2-O1` là biết chính xác vị trí. Việc đếm tồn cũng đi theo đúng trình tự mã, từ tầng 1 đến tầng 4, mỗi tầng từ ô O1 trở đi, không bỏ sót.

## Đưa quy tắc vào vận hành

Lập một bảng mã vị trí dán ở cửa kho và lưu một bản trong điện thoại. Bảng này liệt kê tất cả các mã và loại hàng tương ứng. Khi nhập hàng, ghi mã vị trí lên phiếu nhập thay vì ghi “để chỗ cũ”. Ví dụ: phiếu nhập ghi `A-K1-T2-O1 | Mì gói | 3 thùng`. Người nhập hàng chỉ cần đối chiếu mã trên phiếu với nhãn trên kệ.

Kiểm tra định kỳ theo mã. Mỗi tuần quét nhanh một khu, đối chiếu số lượng thực tế với số ghi trên thẻ hoặc trong sổ. Trước Tết, khi cần kiểm kê nhanh, chỉ cần đi theo đúng thứ tự mã từ K1 đến hết, mỗi ô đếm một lần.

Khi đổi vị trí hàng, cập nhật nhãn và bảng mã ngay trong ngày. Đây là quy tắc quan trọng nhất. Nếu không, chỉ sau một lần đổi chỗ, hệ thống mã sẽ sai và mọi người quay lại thói quen ghi nhớ.

## Vai trò của phần mềm quản lý kho

Khi dùng phần mềm quản lý kho như [Acme](https://acme.example/vi/quan-ly-kho), mã vị trí trên hệ thống phải khớp một-một với nhãn trên kệ. Nếu trên kệ dán `A-K1-T2-O1`, thì trong phần mềm cũng phải có đúng mã đó cho mặt hàng mì gói. Mã vị trí nhập một lần khi tạo phiếu nhập, sau đó in nhãn từ hệ thống để dán lên kệ, tránh nhập tay hai lần dẫn đến sai lệch.

Với kho chỉ có một đến ba người, không cần phần mềm phức tạp. Một phần mềm đơn giản có trường vị trí cho từng mặt hàng là đủ. Điều cần tránh là hệ thống ghi mã cũ trong khi kệ đã đổi chỗ. Lỗi này khiến đếm sai mà không ai phát hiện, vì mọi người tin vào hệ thống hơn là nhìn vào kệ thực tế. Do đó, bất kỳ thay đổi vị trí nào cũng phải được cập nhật trên cả nhãn kệ lẫn phần mềm.

## Kết bài: checklist 5 việc làm trong một buổi chiều

Nếu kho của bạn đang lộn xộn, hãy dành một buổi chiều để làm năm việc sau:

1. Đánh số kệ theo chiều đi vào kho.
2. Vẽ sơ đồ khu và dán ở cửa kho.
3. Dán nhãn ô kèm số lượng tối đa và đơn vị tính.
4. Lập bảng mã vị trí và lưu vào điện thoại.
5. Đếm thử một kệ theo đúng trình tự mã để kiểm tra quy tắc.

Mục tiêu cuối cùng rất đơn giản: người mới vào làm ngày đầu tiên cũng có thể tìm đúng hàng và đếm đúng số lượng mà không cần hỏi ai. Sau buổi chiều đó, việc còn lại là duy trì kiểm tra định kỳ và cập nhật mã ngay khi đổi bố trí. Kho nhỏ không cần diện tích lớn hơn; nó cần một hệ thống nhớ mà ai cũng đọc được.
