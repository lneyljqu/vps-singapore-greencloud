# Thuê VPS Singapore: bảng giá gói KVM từ $6/tháng, băng thông thực tế và những điều khoản cần đọc trước khi thanh toán

Ai gõ "thuê vps singapore" thường muốn một câu trả lời rất cụ thể: đặt máy chủ ở Singapore tốn bao nhiêu, cấu hình ra sao, và có cái bẫy nào giấu trong điều khoản không. Câu trả lời ngắn: GreenCloud bán VPS KVM tại Singapore từ **$6/tháng** (1 nhân Ryzen, 1 GB RAM, 15 GB NVMe), cùng dải giá $10 – $80/tháng cho các cấp cao hơn. Nhưng có hai điểm ít bài review nào nói rõ: băng thông ở khu vực châu Á – Thái Bình Dương bị cắt giảm đáng kể so với máy đặt ở Mỹ và châu Âu, còn các gói Budget tại Singapore thì **không hoàn tiền**. Hai chi tiết này đủ ảnh hưởng tới quyết định chi tiêu nên mình sẽ đặt ngay lên đầu bài.

> **Chọn nhanh**
> - Chỉ cần một máy Linux chạy app, bot, VPN, website nhỏ: gói **RyzenKVM-1**, $6/tháng, đủ dùng cho đa số nhu cầu cá nhân.
> - Cần 4 GB RAM cho web app hoặc database nhỏ: **RyzenKVM-3**, $20/tháng, 2 nhân, 2 TB băng thông.
> - Cần nhiều RAM với giá rẻ nhất: dòng Budget KVM tại Singapore (4 GB hoặc 8 GB), đổi lại băng thông thấp và không hoàn tiền.
> - Cần tuyến đường tối ưu hướng về Trung Quốc: dòng CN Premium (CN2GIA/CU PREMIUM/CMI).
>
> 👉 [Xem các gói VPS Singapore của GreenCloud đang mở bán](https://greencloudvps.com/billing/aff.php?aff=6679)

## Vì sao người dùng Việt Nam lại chọn đặt máy ở Singapore?

Singapore là điểm kết nối mạng trung tâm của Đông Nam Á, có độ trễ thấp tới Malaysia, Indonesia, Thái Lan, Việt Nam, Philippines, Ấn Độ và Úc. Với website hoặc dịch vụ có người dùng trải dài khắp khu vực, một máy ở Singapore gần như luôn phản hồi nhanh hơn máy đặt ở Mỹ hay châu Âu — dù cấu hình giống hệt nhau.

Một chi tiết ít người biết: trên cùng dòng gói Ryzen KVM của GreenCloud, khu vực châu Á không chỉ có Singapore mà còn có cả Việt Nam, Nhật Bản và Hong Kong, cùng mức giá $6 – $80/tháng. Nếu người dùng của bạn tập trung ở Việt Nam, bạn có thể cân nhắc luôn vị trí trong nước trên chính cái gói đó; nếu phục vụ cả khu vực, Singapore là lựa chọn cân bằng hơn.

## Các dòng VPS Singapore của GreenCloud hiện có

GreenCloud không bán một loại "VPS Singapore" duy nhất mà chia thành vài dòng sản phẩm, giá và tính chất khác nhau khá xa. Đây là điểm nhiều bài so sánh bỏ qua, khiến người đọc tưởng giá Singapore chỉ có một biểu.

**Dòng Ryzen KVM** — NVMe, cổng 10 Gbps, CPU Ryzen xung nhịp từ 3.5 GHz, chỉ chạy Linux, đầy đủ root. Đây là dòng có giá công khai rõ ràng nhất và cho phép chọn vị trí Singapore:

| Gói | CPU | RAM / NVMe | Băng thông | Giá/tháng | Đặt mua |
| --- | --- | --- | --- | --- | --- |
| RyzenKVM-1 | 1 nhân @ 3.5+ GHz | 1 GB / 15 GB | 750 GB | $6 | [Đăng ký gói RyzenKVM-1](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-2 | 1 nhân @ 3.5+ GHz | 2 GB / 30 GB | 1 TB | $10 | [Đăng ký gói RyzenKVM-2](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-3 | 2 nhân @ 3.5+ GHz | 4 GB / 50 GB | 2 TB | $20 | [Đăng ký gói RyzenKVM-3](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-4 | 4 nhân @ 3.5+ GHz | 8 GB / 80 GB | 4 TB | $40 | [Đăng ký gói RyzenKVM-4](https://greencloudvps.com/billing/aff.php?aff=6679) |
| RyzenKVM-5 | 8 nhân @ 3.5+ GHz | 16 GB / 150 GB | 6 TB | $80 | [Đăng ký gói RyzenKVM-5](https://greencloudvps.com/billing/aff.php?aff=6679) |

Con số băng thông trong bảng là mức áp dụng cho các vị trí châu Á. Trên trang giá chính thức, GreenCloud ghi rõ hạn mức truyền dữ liệu bị giảm một nửa ở các vị trí châu Á – Thái Bình Dương: cùng gói RyzenKVM-1, máy ở Mỹ có 1.5 TB thì máy ở châu Á chỉ còn 750 GB. Cấp càng cao chênh lệch càng lớn — RyzenKVM-5 ở Mỹ được 12 TB, ở châu Á còn 6 TB. Với VPN hay proxy truyền nhiều dữ liệu, đây là yếu tố quyết định, không phải chi tiết phụ.

**Dòng Budget KVM tại Singapore (DC1)** — rẻ hơn trên mỗi GB RAM, dùng SSD/NVMe RAID-10 với CPU EPYC Rome, quản trị qua panel Virtfusion, kèm 1 bản snapshot miễn phí. Theo trang giỏ hàng chính thức, hai cấp hiện hiển thị cho Singapore là:

- Cấp 4 GB: 2 nhân EPYC Rome, 4 GB RAM, 35 GB NVMe, 750 GB băng thông, cổng 10 Gbps.
- Cấp 8 GB: 4 nhân EPYC Rome, 8 GB RAM, 60 GB NVMe, 1.5 TB băng thông.

Trang theo dõi giá độc lập ghi nhận cấp 2 vCPU/4 GB tại Singapore ở mức **$20/tháng**, giảm còn $18/tháng nếu cam kết 12 tháng, và mức giá này giữ nguyên từ giữa tháng 9 đến nay. Lưu ý nhỏ nhưng quan trọng: mức 750 GB băng thông trên trang chính thức thấp hơn hẳn con số 2 TB mà bên theo dõi giá ghi nhận cho cấu hình tương đương, nên trước khi thanh toán, hãy dừng lại đọc đúng dòng băng thông của vị trí Singapore trên trang đặt hàng — chớ mặc định nó bằng máy Mỹ.

**Dòng CN Premium và Premium EPYC** — hai dòng cao cấp hơn cho Singapore. CN Premium Optimized (cấp Mini: 2 GB RAM, 20 GB NVMe, 1 nhân EPYC Milan, 500 GB băng thông, cổng 500 Mbps) chạy trên tuyến CN2GIA/CU PREMIUM/CMI tối ưu hướng Trung Quốc, có backup hàng ngày; lúc kiểm tra, cấp này hết hàng. Dòng Premium EPYC được bổ sung hàng vào cuối tháng 9 với giá từ $25/tháng, trong đó cấp 2 nhân EPYC Milan/4 GB RAM/40 GB NVMe/1 TB băng thông ở mức $45/tháng và cấp 4 nhân/8 GB/80 GB NVMe/2 TB ở mức $85/tháng theo site review độc lập. Cả hai dòng này đều đắt hơn rõ rệt so với Ryzen KVM và chỉ đáng tiền nếu bạn thật sự cần tuyến đường riêng đó.

👉 [Kiểm tra cấu hình và giá hiện tại của các gói Singapore trên trang chính thức](https://greencloudvps.com/billing/aff.php?aff=6679)

## Chi phí thật: ngoài giá niêm yết còn thứ gì nữa không?

Có, nhưng không nhiều, và đều nằm trên trang công khai.

Về khấu trừ tài nguyên, GreenCloud tính **$3/tháng cho mỗi 1 GB RAM, mỗi nhân CPU và mỗi 10 GB SSD** bổ sung. Giới hạn là tối đa gấp đôi cấu hình gốc: máy 4 GB RAM chỉ nâng thêm tối đa 4 GB nữa. Con số $3/GB này hợp lý để vá thiếu hụt nhỏ, nhưng nếu bạn cần gấp đôi RAM thì mua thẳng gói cao hơn thường rẻ hơn — ví dụ nhảy từ RyzenKVM-3 ($20) lên RyzenKVM-4 ($40) thay vì cộng thêm 4 GB lẻ.

Về chu kỳ thanh toán, các gói trong bảng trên chỉ tính theo tháng, không có hình thức trả theo giờ. Dòng Budget có mức giảm giá khi cam kết dài hơn ($19/tháng cho 3 tháng, $18/tháng cho 12 tháng ở cấp 4 GB). Nhân con số này ra: một máy RyzenKVM-1 tốn $72/năm, một máy Budget 4 GB ở Singapore tốn khoảng $216/năm nếu cam kết dài. Đó là hai mức tham chiếu tốt để so với các lựa chọn khác.

Còn một chi tiết thủ tục: khách hàng mới thanh toán bằng thẻ hoặc PayPal sẽ phải xác minh thanh toán một lần (mỗi phương thức chỉ một lần), và thời gian mở máy thông thường trong khoảng 15 phút, tối đa có thể tới 2 giờ.

## Chính sách hoàn tiền: chỗ dễ mất tiền nhất

Đây là phần cần đọc kỹ nhất trong bài. GreenCloud có chính sách hoàn tiền 7 ngày, nhưng chỉ áp dụng cho **khách hàng mới, trên máy VPS đầu tiên**, và loại trừ các gói giảm giá đặc biệt.

Riêng các gói Budget KVM — bao gồm cả hai cấp tại Singapore — trang đặt hàng ghi rõ **"No refund/Money back on this plan"**. Nghĩa là nếu bạn chọn Budget để rẻ hơn vài đô, bạn từ chối luôn tấm lưới an toàn 7 ngày.

Cách xử lý hợp lý: nếu đây là lần đầu dùng GreenCloud và bạn muốn có thời gian thử độ trễ từ vị trí Singapore về nhà mạng của mình, hãy đặt máy đầu tiên thuộc dòng Ryzen KVM tiêu chuẩn để giữ quyền hoàn tiền 7 ngày. Khi đã yên tâm về đường truyền, lần nâng cấp hay mua thêm sau đó mới chuyển sang Budget nếu cần.

👉 [Mở gói Ryzen KVM đầu tiên với chính sách hoàn tiền 7 ngày](https://greencloudvps.com/billing/aff.php?aff=6679)

## So sánh nhanh với các nhà cung cấp VPS Singapore khác

Thị trường VPS Singapore khá đông, và ở vài tình huống cụ thể, lựa chọn khác GreenCloud thực sự hợp hơn. Bảng dưới chỉ ghi thông tin để đối chiếu:

| Nhà cung cấp | Gói rẻ nhất | Cấu hình gói rẻ nhất | Điểm đáng chú ý |
| --- | --- | --- | --- |
| GreenCloud | $6/tháng | 1 nhân Ryzen, 1 GB RAM, 15 GB NVMe, 750 GB, 10 Gbps | Nhiều dòng sản phẩm, hoàn tiền 7 ngày (trừ Budget) |
| ExtraVM | $4.50/tháng | 1 nhân, 1 GB RAM, 15 GB NVMe, 1 TB, 1 Gbps | 14 cấp gói lên tới 64 GB RAM, Trustpilot 4.8/5, hoạt động từ 2014 |
| EDIS Global | €7.99/tháng | 1 vCPU Intel, 1 GB RAM, 15 GB SSD, 1 TB | Cho phép cài Windows Server, cộng thêm IP/RAM/CPU theo từng đơn vị, năm tặng 1 tháng |
| Anymhost | Rp 145.000/tháng | 1 vCPU, 2 GB RAM, 25 GB, unmetered ≤ 1 Gbps | Hoàn tiền 30 ngày, tính bằng rupiah |

Vài nhận xét thẳng thắn. ExtraVM rẻ hơn $1.50/tháng ở cấp thấp nhất và cho nhiều băng thông hơn (1 TB so với 750 GB), nên nếu giá tuyệt đối là ưu tiên số một và bạn chỉ cần gói nhỏ nhất, ExtraVM có lợi thế thật. EDIS Global là lựa chọn đáng cân nhắc nếu bạn cần chạy Windows Server ngay trên VPS Singapore, thứ mà các gói KVM của GreenCloud trong bài không hỗ trợ (dòng Ryzen KVM chỉ chạy Linux; GreenCloud có bán Windows VPS riêng ở sản phẩm khác). Anymhost mạnh ở chính sách hoàn tiền 30 ngày và băng thông unmetered, tuy nhiên mức giá quy đổi ra đô thường cao hơn cấp tương đương của các nhà cung cấp tính USD.

Còn GreenCloud mạnh ở đâu? Ở chỗ nó là đơn vị đã hoạt động từ 2013, tự sở hữu toàn bộ hạ tầng, là thành viên ARIN/APNIC/RIPE, từng nhận giải "#1 Top Provider" và "#1 Most Stable Provider" trên diễn đàn LowEndTalk, cam kết uptime 99.99% (có trang trạng thái công khai để kiểm chứng) và phản hồi ticket trung bình 9 phút. Trên khoảng $6 – $20/tháng, ít nhà cung cấp nào kết hợp được cả cổng 10 Gbps, NVMe và độ trưởng thành như vậy.

## Câu hỏi thường gặp

**VPS Singapore của GreenCloud có nhanh khi truy cập từ Việt Nam không?** Có. Singapore là điểm peering chính của khu vực nên độ trễ tới Việt Nam thấp, và nếu bạn muốn thử nghiệm, dòng Ryzen KVM cho phép chọn luôn vị trí Việt Nam với cùng giá để so sánh trực tiếp.

**Chạy được Windows trên các gói này không?** Không. Ryzen KVM và Budget KVM trong bài chỉ hỗ trợ Linux, với quyền root đầy đủ. Nếu cần Windows Server, bạn sẽ phải xem dòng Windows VPS riêng của GreenCloud hoặc nhà cung cấp khác như EDIS Global.

**Mua xong bao lâu thì dùng được, và ai quản trị máy?** Máy thường mở trong 15 phút, tối đa 2 giờ. Dịch vụ là unmanaged: GreenCloud chịu trách nhiệm phần cứng, mạng và uptime, còn hệ điều hành, phần mềm, bảo mật bên trong máy do bạn tự lo.

**Thanh toán bằng cách nào?** PayPal, thẻ tín dụng/ghi nợ, Alipay, UnionPay, chuyển khoản ngân hàng Mỹ/Anh/EU và tiền mã hóa (BTC, ETH, BNB, USDT...). Khách mới dùng thẻ hoặc PayPal cần xác minh một lần.

**Sau này nâng cấp được không?** Được. Bạn có thể cộng RAM, CPU, ổ đĩa theo từng đơn vị với giá $3/mỗi đơn vị, tối đa gấp đôi cấu hình gốc, quản lý qua panel Virtfusion.

## Nên chọn gói nào trước khi bấm đặt hàng?

Quyết định theo nhu cầu thì ngắn gọn như sau. Chạy bot, VPN cá nhân, website nhỏ → RyzenKVM-1 $6/tháng là đủ, đừng mua cao hơn. Web app hoặc database nhỏ có 4 – 8 kết nối thường xuyên → RyzenKVM-3 $20/tháng. Nhiều RAM nhưng ngân sách siết và chấp nhận không hoàn tiền → Budget KVM Singapore cấp 4 GB. Phục vụ người dùng tại Trung Quốc → chỉ lúc đó dòng CN Premium mới đáng giá. Cần Windows ngay trên máy Singapore → GreenCloud không có gói phù hợp trong bài này, hãy xem lựa chọn khác.

Trước khi thanh toán, còn hai việc nên làm: kiểm tra tình trạng hàng (cấp Singapore SSD và CN Premium Mini từng hiển thị hết kho tại thời điểm kiểm tra) và đọc đúng dòng băng thông của vị trí Singapore trên trang đặt hàng. Sau đó, 👉 [đặt máy VPS Singapore của GreenCloud](https://greencloudvps.com/billing/aff.php?aff=6679) trong lúc gói bạn cần vẫn còn slot.
