# Proxy xoay giá rẻ: Chọn gói theo IP hay theo GB để không trả tiền cho phần bạn không dùng

Bạn gõ "proxy xoay giá rẻ", mở vài chục tab so sánh, và tất cả đều đang hét vào mặt bạn hai con số: giá trên mỗi IP và giá trên mỗi GB. Vấn đề là hai con số đó không đo cùng một thứ. Người mua 100 IP rồi chạy tool cào dữ liệu 12 tiếng một ngày đang trả tiền cho băng thông không dùng đến. Người nạp 5 GB rồi ngồi canh session đăng nhập Facebook sẽ hết dung lượng trước khi kịp làm xong việc.

Hiểu sai mô hình tính tiền là cách nhanh nhất để "proxy giá rẻ" hoá thành đắt. Dưới đây là cách đọc giá cho đúng, kèm một nhà cung cấp cụ thể — 9Proxy — với bảng giá đầy đủ để bạn tự tính.

## "Giá rẻ" trong thị trường proxy xoay nghĩa là bao nhiêu?

Nhóm proxy dân cư xoay giá rẻ thường nằm trong khoảng **0,70–2 USD/GB**. Ở nhóm này có DataImpulse và 9Proxy, với 9Proxy được ghi nhận quanh mức ~1,30 USD/GB ở các gói nhỏ.

Để có mốc so sánh, bảng giá khởi điểm của một số nhà cung cấp phổ biến (theo tổng hợp của Scrapeless, dựa trên dữ liệu Proxyway tháng 5/2026):

| Nhà cung cấp | Giá khởi điểm |
| --- | --- |
| DataImpulse | 1 USD/GB, không hết hạn |
| Webshare | 1,75 USD/GB |
| 9Proxy | từ ~0,68 USD/GB ở gói lớn |
| Rayobyte | 3,5 USD/GB |
| Decodo | ~4 USD/GB |
| IPRoyal | 7 USD/GB |
| Oxylabs | 30 USD/5 GB (~6 USD/GB) |

Chính bài tổng hợp đó cũng lưu ý: các báo cáo đo hiệu năng của Proxyway và AIMultiple dùng khối lượng request, mục tiêu và thời điểm khác nhau, nên số liệu chỉ nên đọc trong nguồn gốc của nó, đừng gộp thành một bảng xếp hạng duy nhất. Cùng logic đó, đừng so giá/GB giữa hai nhà cung cấp rồi kết luận bên nào rẻ hơn — hãy so theo đúng loại việc bạn làm.

## Điểm quyết định giá thật: theo IP hay theo GB

Hầu hết nhà cung cấp chỉ bán một kiểu. 9Proxy bán cả hai, và đây là khác biệt thực tế giữa chúng:

| Tiêu chí | Gói theo IP | Gói theo GB |
| --- | --- | --- |
| Cách tính tiền | Trả theo số lượng IP | Trả theo tổng dung lượng |
| Băng thông | Không giới hạn trong thời gian IP hoạt động | Giới hạn bởi số GB đã mua |
| Vòng đời mỗi IP | Vài giờ, tối đa khoảng 24 giờ | Xoay tự động theo request hoặc theo session |
| Số endpoint | 1 IP = 1 lượt dùng khi forward | Tạo endpoint không giới hạn, chỉ trừ GB |
| Hạn dùng phần chưa dùng | IP chưa dùng không hết hạn | 180 ngày |
| Cách xoay | Không xoay tự nhiên; xoay qua Auto Rotation Proxy theo port và khoảng thời gian tự đặt | Chế độ rotating tự đổi IP, hoặc sticky đổi khi hết session |

Đọc bảng này ra được một câu: gói theo IP bán **sự ổn định**, gói theo GB bán **số lần đổi danh tính**. Nếu công việc của bạn là đăng nhập, giữ phiên, thao tác nhiều bước trên cùng một tài khoản, cái bạn cần là IP sống đủ lâu — và mỗi request nhẹ thì gói GB chỉ làm bạn hết tiền nhanh hơn. Ngược lại, cào giá sản phẩm, kiểm tra quảng cáo, quét SERP, gọi API liên tục thì mỗi request chỉ vài chục KB, và trả theo IP là trả thừa.

## 9Proxy thực tế cung cấp gì

Trước khi đi vào giá, vài thông số nền để bạn biết mình đang mua gì:

- Pool dân cư **hơn 20 triệu IP**, trải trên **90+ quốc gia**
- Giao thức **HTTP/HTTPS và SOCKS5**
- Nhắm mục tiêu theo **quốc gia, bang, thành phố, ZIP và ISP**
- Xác thực bằng **username/password hoặc whitelist IP**
- Bốn cách truy cập: **Proxy Program** (client Windows, định tuyến ở tầng hệ điều hành, dùng được với phần mềm không hỗ trợ proxy), **Proxy2Web** (chạy trên trình duyệt, xác thực user:pass), **ProxyHub / ProxyHub Lite** (quản lý proxy trên thiết bị di động), và **Public API** cho pipeline tự động
- **Gói Enterprise**: một chủ sở hữu + tối đa 5 thành viên, băng thông chia sẻ không hết hạn trong team, giới hạn dung lượng theo từng thành viên, log hoạt động đầy đủ
- Có **chương trình dành cho đại lý** với giá bán buôn theo IP và theo GB

Một mốc thời gian đáng biết: 9Proxy điều chỉnh giá **từ 0:00 UTC ngày 1/6/2026** đối với gói theo IP và gói bundle. Gói theo GB giữ nguyên giá. Vì hệ thống tính theo số dư, các gói mua trước mốc đó được giữ nguyên mức giá cũ.

## Bảng giá đầy đủ các gói 9Proxy

Toàn bộ gói đang niêm yết, chia theo ba nhóm.

### Gói proxy dân cư theo IP

| Gói | Số IP | Tổng tiền | Giá mỗi IP |
| --- | --- | --- | --- |
| 100 IP | 100 | 24 USD | 0,24 USD |
| 500 IP | 500 | 72 USD | 0,144 USD |
| 1.000 + 500 IP | 1.500 (tặng thêm 500) | 126 USD | 0,084 USD |
| 2.500 IP | 2.500 | 210 USD | 0,084 USD |
| 5.000 IP | 5.000 | 360 USD | 0,072 USD |
| 15.000 IP | 15.000 | 720 USD | 0,048 USD |
| 25.000 IP | 25.000 | 863 USD | 0,035 USD |
| 50.000 IP | 50.000 | 1.438 USD | 0,029 USD |
| 100.000 IP | 100.000 | 2.300 USD | 0,023 USD |
| 200.000 IP | 200.000 | 4.140 USD | 0,021 USD |
| 500.000 IP | 500.000 | 8.625 USD | 0,018 USD |

👉 [Xem các gói theo IP của 9Proxy](https://bit.ly/9-Proxy)

Băng thông không giới hạn trên từng IP, và IP chưa dùng thì không mất. Đây là lý do nhóm MMO chuộng kiểu gói này: mua 1.500 IP dùng dần trong nhiều tháng vẫn còn nguyên số dư.

### Gói proxy dân cư theo GB

| Gói | Tổng tiền | Giá mỗi GB | Hiệu lực |
| --- | --- | --- | --- |
| 5 GB | 15 USD | 3,00 USD | 180 ngày |
| 50 GB + tặng 5 GB | 105 USD | — | 180 ngày |
| 100 GB | 150 USD | 1,50 USD | 180 ngày |
| 200 GB | 200 USD | 1,00 USD | 180 ngày |
| 1.000 GB | 800 USD | 0,80 USD | 180 ngày |
| 2.000 GB | 1.500 USD | 0,75 USD | 180 ngày |
| 3.000 GB | 2.160 USD | 0,72 USD | Không giới hạn |
| 6.000 GB | 4.200 USD | 0,70 USD | Không giới hạn |
| 10.000 GB | 6.800 USD | 0,68 USD | Không giới hạn |

👉 [Nạp GB cho tài khoản 9Proxy](https://bit.ly/9-Proxy)

Ba gói từ 3.000 GB trở lên là nhóm Enterprise, có hiệu lực vĩnh viễn, kèm chế độ team. Nếu bạn chỉ cần vài chục GB mỗi tháng, gói 50 GB hoặc 100 GB là điểm vào hợp lý — mức giá 1,50 USD/GB đã nằm trong nhóm rẻ của thị trường.

### Gói bundle (IP + GB)

| Gói | Thành phần | Giá |
| --- | --- | --- |
| Starter | 100 IP + 5 GB | 30 USD |
| Popular | 1.500 IP + 50 GB | 180 USD |
| Pro | 5.000 IP + 500 GB | 720 USD |

👉 [Chọn gói bundle 9Proxy](https://bit.ly/9-Proxy)

Bundle sinh ra cho kiểu làm việc lẫn lộn: phần lớn task cần IP ổn định trong session, một phần nhỏ cần luân chuyển liên tục qua nhiều IP. Nhóm này cũng hưởng hạn dùng băng thông 180 ngày, nên dự án chạy theo đợt không bị ép tiêu hết trong 30 ngày.

> Giá có thể thay đổi. Trước khi nạp số tiền lớn, hãy mở lại trang giá chính thức trong tài khoản để đối chiếu — đặc biệt với gói theo IP và bundle, vì đây là hai nhóm từng bị điều chỉnh.

## Gói nào hợp với ai

**Nuôi tài khoản, đăng nhập nhiều bước, quản lý nhiều acc mạng xã hội.** Chọn gói theo IP. Một tài khoản cần một địa chỉ ổn định trong suốt phiên thao tác, và việc IP đổi giữa chừng là nguyên nhân checkpoint hàng đầu. IP sống vài giờ tới ~24 giờ là đủ cho một phiên làm việc.

**Checkpoint, xác minh, thao tác dài nhiều ngày.** Đây là lúc cần IP tĩnh (ISP) chứ không phải xoay. Proxy xoay là sai công cụ nếu bạn cần một địa chỉ bám theo tài khoản hàng tuần.

**Cào giá, theo dõi đối thủ, kiểm tra quảng cáo, quét SERP.** Chọn gói theo GB. Bạn không quan tâm IP nào, chỉ cần mỗi request ra một địa chỉ khác, và mỗi request nhẹ nên chi phí trên mỗi lần đổi danh tính rất thấp.

**Team nhỏ đang chạy pipeline liên tục.** Gói Enterprise: băng thông không hết hạn, chia sẻ trong nhóm 5 người, giới hạn theo từng thành viên. Nếu bạn từng phải mua riêng từng gói GB cho từng người, đây là chỗ tiết kiệm thật.

**Mới thử lần đầu.** Bắt đầu bằng gói nhỏ nhất trong nhóm phù hợp với công việc, chạy đúng bộ test trên đúng mục tiêu bạn nhắm tới, rồi mới quyết định nạp thêm. Kiểm tra tỉ lệ request thành công trên chính site của bạn, không phải trên trang test của nhà cung cấp.

## Xoay IP: ba chế độ và khi nào dùng chế độ nào

Thứ tự từ nhẹ tới nặng:

1. **Rotating theo request.** Mỗi request ra một IP mới. Phù hợp cào dữ liệu số lượng lớn, không cần giữ phiên.
2. **Sticky session.** Giữ cùng một IP trong khoảng thời gian bạn đặt, chỉ đổi khi hết session. Đây là chế độ mặc định cho các luồng đăng nhập và thanh toán.
3. **Auto Rotation Proxy.** Với gói theo IP, cơ chế xoay nằm ở các port bạn chọn — bạn cấu hình khoảng thời gian xoay, hệ thống tự đổi IP. Dùng khi muốn chia một khối IP ra làm nhiều luồng chạy song song mà không quản lý tay từng con.

Cả ba chế độ đều cấu hình được trong dashboard, không cần app riêng nếu bạn đi qua Proxy2Web hoặc API.

## Bắt đầu trong bao lâu

Quy trình gọn: tạo tài khoản, chọn gói theo IP hoặc theo GB, rồi chọn cách truy cập. Muốn nhanh thì dùng Proxy2Web với xác thực user:pass, dán thẳng vào anti-detect browser hoặc extension đổi proxy. Muốn chạy tool không hỗ trợ proxy thì dùng Proxy Program trên Windows — nó định tuyến ở tầng hệ điều hành nên mọi ứng dụng đi qua đều ăn proxy mà không cần cấu hình riêng. Script Python thì đi đường SOCKS5 hoặc Public API.

Ai đang dùng anti-detect browser, proxychains hay script tự viết đều không phải chuyển đổi giao thức — SOCKS5 được hỗ trợ sẵn.

👉 [Tạo tài khoản 9Proxy và chọn gói phù hợp](https://bit.ly/9-Proxy)

## Cảnh báo về "miễn phí" và mua qua trung gian

Hai con đường rẻ hơn nữa mà bạn sẽ gặp khi tìm proxy xoay giá rẻ, và cả hai đều có giá của nó.

**Pool proxy miễn phí.** Có những dự án mã nguồn mở dựng proxy xoay từ danh sách proxy ẩn danh công khai, có cả extension cho Burp, hỗ trợ nhiều chế độ xoay và giao diện theo dõi. Nghe hấp dẫn cho tới khi bạn đọc kỹ: các dự án này tự nhận phải fetch hơn 2.000 proxy ứng viên rồi kiểm tra đồng thời, chỉ giữ lại số còn sống, và phải retry giữa request khi proxy chết. Tỉ lệ sống thấp đến mức chính tác giả phải viết cơ chế chịu lỗi. Với việc cần IP sạch và ổn định, đây là lựa chọn tự làm khó mình.

**Mua qua đại lý/trung gian trong nước.** Ở Việt Nam có các chợ proxy bán lại CDKey của 9Proxy, tính bằng VND, kèm hỗ trợ cài đặt qua TeamViewer và cam kết hoàn tiền nếu key không hoạt động. Cách này tiện nếu bạn không muốn thanh toán quốc tế, nhưng có hai điểm cần nhớ: giá có thể cao hơn mua trực tiếp, và mọi vấn đề về tài khoản — hạn dùng, GB bị trừ sai, khôi phục key — đều đi qua bên bán lại thay vì qua nhà cung cấp. Hãy đọc kỹ điều khoản bảo hành trước khi nạp tiền.

Một lưu ý nữa: khi tìm mua, bạn sẽ thấy nhiều nơi đứng tên gần giống thương hiệu. Chỉ nên nạp tiền ở kênh chính thức của nhà cung cấp.

## Vài câu hỏi hay gặp

**9Proxy có cho dùng thử không?** Có chương trình dùng thử, và theo thông tin nhà cung cấp công bố cho người dùng mới thì có tặng một số proxy miễn phí để test. Số lượng cụ thể thay đổi theo thời điểm — kiểm tra trong dashboard sau khi đăng ký.

**Gói theo IP có giới hạn băng thông không?** Không. Bạn trả theo IP, băng thông không giới hạn trong thời gian IP đó hoạt động.

**Mua 1.500 IP rồi có bị mất vì không dùng hết không?** Không. IP chưa dùng không hết hạn. Chỉ số IP bị trừ khi bạn thực sự forward qua nó.

**GB nạp vào có hết hạn không?** Gói GB thường có hiệu lực 180 ngày. Ba gói Enterprise từ 3.000 GB trở lên có hiệu lực vĩnh viễn.

**Thanh toán bằng gì?** Thẻ Visa/Mastercard, và phương thức thanh toán nội địa theo khu vực — hệ thống tự hiển thị lựa chọn phù hợp với vị trí của bạn ở bước checkout. Ô nhập mã giảm giá nằm cùng màn hình đó.

**Có nhắm mục tiêu tới cấp thành phố không?** Có, tới cấp quốc gia, bang, thành phố, ZIP và ISP.

## Tóm lại cách chọn

Nếu bạn đang tìm proxy xoay giá rẻ, thứ tự đúng là: xác định công việc cần IP ổn định hay cần nhiều lần đổi danh tính, chọn mô hình tính tiền theo đúng câu trả lời đó, rồi mới so giá. Ở nhóm giá rẻ, 9Proxy có lợi thế ở cấu trúc gói: gói theo IP không giới hạn băng thông và không hết hạn phần chưa dùng, gói theo GB xuống tới 0,68 USD/GB mà vẫn giữ hạn dùng 180 ngày cho gói thường.

Với người mới, gói 5 GB (15 USD) hoặc 100 IP (24 USD) là điểm vào đủ rẻ để test thật trên đúng mục tiêu của bạn trước khi nạp số lớn.

👉 [Bắt đầu với 9Proxy và chạy thử trên mục tiêu của bạn](https://bit.ly/9-Proxy)
