# Vạn Kiếp Tu Tiên Tool · Trợ Lý (Bản Mod 8.7.0)

## Bản 8.7.0 · Đoán đột phá, Ý cảnh, sự kiện ẩn
### Tính năng mới
- **Đoán trước đột phá:** bảng chọn đan ở Đột phá & Thọ có cột Dự đoán (Thành / Bại / Chết / Tâm ma) và phẩm đạo cơ, tính bằng chính hàm của game trên bản sao; dòng số rút và bộ đan rẻ nhất mà qua; gợi ý chờ thêm tháng nếu phẩm cao hơn. Đã kiểm (không lỗi).
- **Thẻ Ý Cảnh (Tổng Quan):** đủ 13 ý cảnh và Ngũ hành ý: ý đang theo, buff, điểm còn thiếu tới bậc kế, cách tích điểm; dị anh đang có (chiêu cùng hệ +15%) hoặc sẽ ra khi lên Nguyên Anh. Đã kiểm.
- **Soi sự kiện ẩn (mặc định tắt):** ô 🔓 ở khung Đang Quan Tâm / Tra cứu: báo khi sự kiện ẩn đã ★ có trên bản đồ, danh sách sự kiện ẩn đang có kèm Đi tới. Chưa kiểm.
- **Sổ Sự Kiện Vừa Gặp (Tra cứu Sự kiện):** tự ghi 40 sự kiện và thông báo lạ gần nhất, bấm mở thẻ, nút Chép. Đã kiểm.
- **Chấm đỏ trên nút ☯:** sự kiện ★ hiện lúc cửa sổ đang thu nhỏ thì nút nổi có chấm đỏ kèm số, mở cửa sổ là mất. Chưa kiểm.
- **Tâm ma & Nghiệp (Đột phá & Thọ):** tâm ma trong đó bao nhiêu là nghiệp, cách gỡ (khổ tu sám hối, việc thiện). Chưa kiểm.
- **Cơ duyên tích dần (Ngự Linh):** điểm xui từng nhóm (đồ quý rơi, đồ ngon, tư chất tiến hóa, Thánh huyết trứng quý). Chưa kiểm.
- **Đồ mượn của tông (Tàng Kinh Các):** món sẽ bị thu khi xuống núi, giá chuộc, phí xuống núi. Chưa kiểm.
- **Thu Được Theo Nguồn (Tìm & Săn Đồ):** sổ đồ thu được trong kiếp theo nguồn (trận, sự kiện, tiệm...). Chưa kiểm.
- **Màn trận:** dòng dự kiến của game ngay trên màn trận và nút Dự Kiến Thật (chỉ chạy khi bấm). Chưa kiểm.

### Nâng cấp tính năng
- **Tìm Đồ:** dùng hàm vẽ tiệm của game (viewShop) nên xét tồn kho, món khóa điều kiện, hàng giả đã nhìn ra; tiệm hết hàng ghi '~k năm có lại'; ghi 'Dự đoán có ... (còn N)'; cảnh báo sát mốc năm; tới nơi không thấy món thì báo lý do; Giá chợ bỏ món hết. Chưa kiểm.
- **Auto Săn yêu:** dự đoán trước khi chọn con (ô 'Dự đoán trước khi đánh', mặc định bật), bỏ con thua chắc ở Truy tìm và việc lạ; Truy tìm kiểm cả màu; thua trận ghi lại Dự Kiến Thật trước trận. Chưa kiểm.
- **Tra cứu Sự kiện:** dịch hết chữ thô (biến, nhóm người, ~150 hiệu ứng, tên cảnh), nút Kiểm chữ thô; huy hiệu sự kiện Ẩn / Mật bí, tìm theo id hoặc 'bất thường', lọc 'Chỉ sự kiện ẩn'. Đã kiểm.
- **Theo bản game nghiệp:** Auto sự kiện né lựa chọn cộng nghiệp, lời khuyên và nhãn đan ghi rõ đan/chùa không gỡ nghiệp. Chưa kiểm.
- **Ngự Linh:** bậc Thánh Huyết (tư chất 6), Thần Huyết tiến hóa có 3% lên Thánh Huyết; món biến thể tra đúng món gốc. Chưa kiểm.
- **Tổng Quan:** Ngũ hành ý cho linh căn Ngũ Hành (hệ yếu nhất quyết định bậc). Chưa kiểm.

### Sửa lỗi
- **Tự cập nhật:** không còn bị GitHub chặn (403) khi Nạp lại nhiều lần: nhớ kết quả 15 phút, bị chặn thì tạm nghỉ. Chưa kiểm.
- **Quan tâm sự kiện:** ★ một sự kiện ẩn không còn lộ tên khi chưa bật Soi sự kiện ẩn. Chưa kiểm.

## Bản 8.6.1 · Săn yêu không lặp Thôi
### Sửa lỗi
- **Auto Săn yêu:** khi chỉ tích Quái Thường mà việc lạ Săn yêu ra con Tinh Anh, Auto không còn lặp mãi "chọn Thôi" nữa mà xem loại quái thật trước rồi vào "Săn loài khác" chọn loài hợp loại và màu đã tích; nếu một nơi bị Thôi 3 lần thì bỏ qua nơi đó. Nhật ký không còn ô vuông lạ quanh tên quái. Chưa kiểm.

## Bản 8.6.0 · Quan tâm sự kiện
### Tính năng mới
- **Quan tâm sự kiện:** bấm ☆ trên thẻ ở Ngự Linh → Cơ Duyên hoặc Tra cứu Sự kiện để theo dõi. Khi sự kiện hiện trên bản đồ (hoặc có ngay tại nơi đang đứng) Tool báo, bấm báo là đi tới. Đầu tab Cơ Duyên có khung "Đang Quan Tâm": đang ở đâu, còn tới năm nào, đi mất mấy năm, cảnh báo đi không kịp, nút Đi tới / Ghim; cửa hàng trong thành gợi ý 3 nơi gần nhất. Sự kiện quan tâm được tô nổi trên bản đồ game. Chưa kiểm.

## Bản 8.5.0 · Đàn linh vật, Ngũ Hành, chuyển tab nhanh
### Tính năng mới
- **Auto Build · Đàn Linh Vật:** ô mới "Đàn Linh Vật" (Không Xét / Đủ Ngự Lực / Pet Đánh Chính / Bầy Đàn) và "Số Con Muốn Mang"; Auto Build chọn bộ kinh mạch đủ ngự lực để dắt đàn, tính cả giảm giá của tâm pháp đúng loại. Có dòng "Ngự lực hiện tại: dùng X / Y" kèm giá từng con; chọn Ngự Thú Tu thì tự bật Đủ Ngự Lực. Chưa kiểm.
- **Auto Reroll · Ước tính tỉ lệ:** hiện tỉ lệ khớp mỗi lần và số lần dò kỳ vọng, cảnh báo khi quá hiếm so với số lần đã đặt, gợi ý chọn thẳng bằng Thiên Mệnh; đếm số lần gặp phẩm/thể chất muốn sau mỗi lượt dò. Chưa kiểm.

### Nâng cấp tính năng
- **Auto Reroll · Ngũ Hành linh căn:** thêm phẩm Ngũ Hành (danh sách phẩm đọc thẳng từ game). Chọn Ngũ Hành thì 5 hệ Kim Mộc Thủy Hỏa Thổ tự có, chỉ chọn thêm hệ ngoài; hệ do thể chất mang cũng được tính (Cửu U Thể → Ám). Đã kiểm.
- **Auto Reroll · Số lần Dò Tỉ Lệ:** tự đặt số lần dò (10–20.000), Tool nhớ số đã đặt. Chưa kiểm.
- **Chuyển tab nhanh hơn:** bấm liên tục nhiều tab chỉ dựng tab cuối; Bộ món hết lag (trước ~1,5 giây mỗi lần mở); Đột phá & Thọ, Bản đồ, Bản mệnh pháp bảo vào lại gần như ngay; chỉ mục sự kiện dựng ngầm, không làm đơ game. Đã kiểm.

### Sửa lỗi
- **Thẻ nhân vật:** linh căn Ngũ Hành hiện đúng tên thay vì mã ngu_hanh. Đã kiểm.
- **Ô gợi ý tên:** không còn dồn thêm bộ nghe gõ phím mỗi lần mở tab (gõ càng lâu càng lag). Đã kiểm.

## Bản 8.4.1 · Sửa tự cập nhật
### Sửa lỗi
- **Tự cập nhật:** đọc version.json và main.js theo cùng một commit trên GitHub, nên vừa có bản mới là thấy ngay (trước có thể báo "đã là bản mới nhất" thêm vài phút) và không còn lỗi "sai kích thước (… ≠ …)" khi cập nhật đúng lúc GitHub chưa đồng bộ; lệch thì tự thử lại một lần. Chưa kiểm.
- **Auto Buôn Bán:** ô Vốn Dùng Mỗi Chuyến tự về trong khoảng 1–100% (trước gõ 120 vẫn hiện 120 dù Tool chỉ dùng 100%), ghi rõ luôn chừa phần Luôn Giữ Lại; ô Lãi Tối Thiểu cũng tự kẹp. Chưa kiểm.

## Bản 8.4.0 · So bộ kinh mạch, lọc hệ, tách cửa sổ
### Tính năng mới
- **Chấm Các Bộ Đã Lưu:** nút mới ở thẻ "Đang xếp trong game" (Auto Build): đánh thử từng bộ kinh mạch đã lưu bằng trận mẫu, không cần đánh thật. Mỗi bộ có 2 mức Hiện tại / Lĩnh Ngộ đầy (kèm số năm tới khi thuần thục), cột theo bảng Vận hành của game, sát thương TB / lượt, linh lực tiêu hao và dư (ước); phần gập Trận mẫu từng trận, Thành phần điểm, Món trong bộ. Đã kiểm.
- **Đóng góp từng món:** trong bảng so bộ, bấm "Tính đóng góp" để biết gỡ từng món thì bộ mất bao nhiêu điểm; 3 món yếu nhất tô đỏ để cân nhắc thay. Chưa kiểm.
- **Chỉ dùng các hệ:** Auto Build · Cài Đặt Chung có ô chọn các hệ được dùng (nút "Theo linh căn" chọn sẵn hệ linh căn + Vô sắc); món có hệ ngoài danh sách bị bỏ, món Chủ Đạo vẫn dùng. Chưa kiểm.
- **Vì sao còn ô trống?:** nút ở thẻ "Đang xếp trong game" và dưới kết quả Xếp: mỗi ô thông còn trống có lý do (không món nào vừa, bị lọc hệ / phẩm, không thông, thêm điểm nghịch, giảm điểm, hoặc lấp được). Chưa kiểm.
- **Tách cửa sổ:** nút ⧉ trên thanh đầu (hoặc menu ⋯) đưa Tool ra cửa sổ riêng, kéo sang màn hình khác được (Chrome/Edge: cửa sổ nổi; trình duyệt khác: popup). Đóng cửa sổ đó thì Tool về lại trong game. Chưa kiểm.

### Nâng cấp tính năng
- **Auto Build theo hệ linh căn:** khi bật "Ưu Tiên Theo Hệ Linh Căn Và Huyệt Đạo", Tool bỏ hẳn món có hệ khắc hoặc bị linh căn khắc (vd linh căn Hỏa + Mộc thì bỏ Thủy, Kim, Thổ), không còn chỉ trừ điểm nhẹ. Đã kiểm.
- **Auto Build tránh điểm nghịch:** mỗi điểm nghịch trừ 3% tổng điểm trận mẫu (trước gần như không phạt); Ma tu giữ như cũ. Đã kiểm.
- **Auto Build lấp ô trống:** sau khi xếp, nếu đặt Phẩm tối thiểu mà còn ô trống thì lấp thêm bằng món dưới phẩm tối thiểu (chỉ khi món thông, không thêm điểm nghịch, không giảm điểm). Chưa kiểm.
- **Bảng Đang xếp / Bản mới:** thêm Điểm Tool, sát thương TB / lượt, linh lực tiêu hao và dư (ước), cảnh báo dư / thiếu linh lực, so từng trận mẫu và cảnh báo khi bản mới thắng ít trận hơn; ghi rõ cả hai cột tính ở Lĩnh Ngộ đầy. Đã kiểm.

### Sửa lỗi
- **Món biến thể của mod khác:** theo bản game mới (món id dạng gốc~mã), Auto Build không xếp hai biến thể cùng một món gốc lên kinh mạch; Tra Cứu, Lưu Phái và các danh sách xếp theo hướng ẩn biến thể bạn chưa có. Chưa kiểm.

## Bản 8.3.1 · Hướng dẫn kĩ hơn
### Nâng cấp tính năng
- **Hướng dẫn nhanh:** tour 10 bước, chữ kĩ hơn, thêm bước Cập nhật (chỉ đúng nút ⟳, trên điện thoại là nút ⋯), Nhật ký, Thu gọn và Báo lỗi. Ai đã xem tour cũ sẽ thấy lại một lần. Chưa kiểm.
- **Hướng dẫn & Hỏi đáp:** thẻ trong Hệ Thống thêm 9 câu hỏi đáp gập/mở: cập nhật thế nào, chấm cam/chấm đỏ là gì, thu gọn và mở lại, Tool có khóa Tỉ thí không, gặp lỗi làm gì... Nút ? có thêm Mẹo chung và nút Hỏi đáp. Chưa kiểm.
- **Báo bản mới:** có bản mới thì hiện băng "Có bản mới · Cập nhật ngay · Để sau" ngay dưới thanh trên, thông báo nổi ghi rõ bấm vào để cập nhật; lên bản xong có thông báo "Đã lên bản X · bấm xem có gì mới". Chưa kiểm.
- **Tìm mục:** gõ "cap nhat" hoặc "huong dan" ra Hệ Thống. Chưa kiểm.

## Bản 8.3.0 · Báo Lỗi, sửa lỗi điện thoại
### Tính năng mới
- **Báo Lỗi:** mục mới trong Hệ Thống, gửi báo lỗi / đề xuất cải tiến / tính năng mới thẳng từ Tool, kèm tối đa 4 ảnh, Báo cáo nhanh và dữ liệu Excel. Ở Tự Kiểm Tra có nút Gửi báo lỗi này. Đã kiểm.
- **Nút ⋯ trên điện thoại:** gom Cập nhật, Mục này làm gì và Báo lỗi vào một nút cho thanh trên đỡ chật. Đã kiểm.

### Nâng cấp tính năng
- **Bản Mệnh Gợi Ý:** theo bản game 24/11, văn Thiêu / Độc / Huyết tính giá theo sức (Độc cấp 1 ~×0,92, Dị văn cấp 5 ~×0,77), Hàn / Tuyệt Hồi / Trói đọc thẳng từ game; văn Hiệu ứng và Hệ ghi rõ áp cả chiêu khống chế. Chưa kiểm.
- **Phím tắt:** máy không có bàn phím thì thẻ Phím tắt và Hướng dẫn nhanh báo phím tắt chỉ dùng trên máy tính. Đã kiểm.
- **Thẻ Cập nhật:** nhật ký bản mới in đậm đúng, chia Tính năng mới / Nâng cấp tính năng / Sửa lỗi, nút đúng kiểu Tool. Đã kiểm.

### Sửa lỗi
- **Điện thoại:** hết lỗi Nhận diện mod khác ở Tự Kiểm Tra; tên Tool và số bản không còn bị ép mất; nhóm Hệ Thống có icon. Đã kiểm.
- **Thanh nhóm dưới:** không còn tự nhảy sang Hệ Thống hay đơ sau khi hiện thông báo có bản mới. Đã kiểm.
- **Chữ nháy:** tiêu đề không còn nháy chữ thường khi chuyển mục. Đã kiểm.
- **Bản đồ:** dấu nơi đặc biệt đủ 4 cạnh hình thoi, mũi tên đường ghim khép kín. Đã kiểm.

## Bản 8.2.0 · Tự cập nhật, hướng dẫn nhanh
### Tính năng mới
- **Tự cập nhật:** Hệ Thống → Cập nhật kiểm bản mới trên GitHub (mỗi 5/15/30/60 phút, bật tắt được). Bấm Cập nhật là xong: Tool tải bản mới, chờ lúc không trong trận/sự kiện thì tự tải lại trang. Nút Nhật Ký có chấm đỏ khi vừa lên bản. Có nút Quay về bản đã cài; bản mới lỗi thì tự quay về. Chưa kiểm.
- **Hướng dẫn nhanh:** 6 bước chỉ vào phím mở, cây mục, ô Tìm mục, Tổng Quan, Auto, Hệ Thống; tự hiện lần đầu, xem lại ở Hệ Thống. Chưa kiểm.
- **Nút ? :** trên thanh trên, giải thích mục đang mở. Chưa kiểm.
- **Bảng nhân vật của game:** cuối khối Chỉ số có dòng Trợ Lý với nút Ngưỡng chỉ số và Đột phá. Chưa kiểm.

### Nâng cấp tính năng
- **Kế Hoạch Đi:** số năm tới mùa thuốc sau đọc thẳng từ game (bản game 23/11). Chưa kiểm.
- **Nhật Ký:** chia Tính năng mới / Nâng cấp tính năng / Sửa lỗi.

### Sửa lỗi
- **Dị Bảo:** Thái Hư Chu ghi đúng 7% và hồi chiêu 100 năm theo bản game 23/11 (hồi chiêu đọc từ game). Chưa kiểm.

## Bản 8.1.0 · Đấu giá, dọn kho, bế quan đúng năm
- **Auto Đấu Giá:** thấy Đại hội đấu giá trong mọi nhóm thế cục, có Lịch Đấu Giá Sắp Tới (xếp theo điểm), Đi vòng các nhà, bế quan đúng tới năm mở, không bế quan lặp ở chỗ có biến.
- **Tìm & Săn Đồ:** hiện giá cần trả và "thiếu X lt"; dò trước năm tiệm bày món rồi bế quan đúng số năm; Lặp tới khi thấy.
- **Kiếm Linh Thạch:** Dọn kho nâng cấp (có nút Giữ, tự giữ món đang cần), thẻ Bán ở đâu lời nhất, Chợ chọn bán kính và vùng đất.
- **Món Cần:** đếm cả kho động phủ, tĩnh thất, bộ đã lưu; món đủ thì gạch ngang; báo khi tiệm/đấu giá có món cần.

## Bản 8.0.1 · Bỏ nút Tải Source Game
- Bản công khai không còn nút tải nguyên code game (theo đề xuất của Kdarknessk, tránh bị dùng làm bản clone).
- Sao chép báo cáo nhanh và Xuất dữ liệu (Excel) vẫn dùng bình thường.

## Bản 8.0.0 · Giao diện mới, Auto mới, Tra cứu mới
- **Giao diện mới:** máy tính có cây mục bên trái, ô Tìm mục, tên + mô tả từng mục; điện thoại giữ thanh ngang. Nhóm mới Hệ Thống (Tự kiểm tra, Mod khác, Kho Dữ Liệu, Xuất Excel, Phím tắt).
- **Phím mở/đóng đổi thành Alt+T** (Hệ Thống → Phím tắt: đổi được, tắt được).
- **Auto Build:** chấm thêm trận khó, đổi nhiều món nhỏ lấy món lớn, lấp ô trống; Ưu tiên phẩm cao bật sẵn; Phẩm tối thiểu, Không dùng các món, giải thích "vì sao không xếp", Thử chèn; Độ Kỹ có ước giờ; Lộ trình theo cảnh giới; chạy nền không chặn Auto khác.
- **Auto mới:** Tìm & Săn Đồ, Auto Đấu Giá, Auto Sự Kiện (tab riêng, mặc định tắt); Auto chia "đi lại" (có hộp Dừng/Thôi) và "nền"; thanh trạng thái Auto.
- **Tra cứu mới:** Bộ Món, Lưu Phái, Thể Chất, Săn Yêu, Hái Thuốc, Kế Hoạch Đi, Địa Danh tìm gia tộc; Vật Phẩm lọc khoảng phẩm + công dụng.
- **Thêm thẻ:** Ngưỡng chỉ số, Tẩy tủy còn lại (sửa lỗi luôn ra 0), Cách nâng tỉ lệ đột phá, Trùng kết · Ôn dưỡng, Bản mệnh gợi ý, Tìm tông môn, Vực đánh thử, Gợi ý lượt trong trận, Dọn kho, Linh điền, Ghim lên bản đồ game…
- **Sửa:** nhận diện mod báo nhầm setOfItem; công tắc ẩn kết quả lựa chọn sự kiện; Auto Săn/Buôn có ô tự bấm sự kiện riêng.
- Phần lớn chưa kiểm trong game (đã kiểm: Tool nạp, cây mục, Tự kiểm tra, Auto Build chạy được).

## Bản 7.17.4 · Bí Cảnh Khai Mở Trong Cơ Duyên Sắp Hết Hạn
- **Bí cảnh khai mở (Tổng Quan):** khối Cơ duyên sắp hết hạn hiện mọi bí cảnh đang mở (kèm cảnh giới vào được và số năm còn lại), không cần tới tận nơi; vào xong thì mục mất.
- **Sửa lỗi bản 7.17.2:** tin chợ đêm, bí cảnh… không còn bị ẩn nhầm.
- Chưa kiểm trong game.

## Bản 7.17.3 · Hết Đơ Ô Gợi Ý Tên Món Trên Điện Thoại
- **Ô gợi ý tên món:** ở Auto Săn Yêu (Nguyên Liệu Cần Săn), Auto Buôn Bán và bộ lọc Sự Kiện, chạm ô không còn đơ; gõ chữ (không cần dấu) mới hiện tối đa 30 món khớp.
- **Bàn phím điện thoại:** cửa sổ Tool bớt tính lại kích thước liên tục khi đang gõ.
- Chưa kiểm trong game.

## Bản 7.17.2 · Cơ Duyên Sắp Hết Hạn Đúng Hơn · Nút Đi Tới, Chỉ Dẫn
- **Cơ duyên sắp hết hạn (Tổng Quan):** hiện cả bí cảnh chưa tới (khớp bản đồ game); đánh xong thì mục tự mất.
- **Nút Đi tới / Chỉ dẫn:** mỗi dòng cơ duyên có nút đi tới và chỉ dẫn đường như tab Bản Đồ.
- Chưa kiểm trong game.

## Bản 7.17.1 · Sửa Tên Đối Thủ Trong Sự Kiện · Tự Kiểm Kinh Mạch
- **Tên người tại chỗ:** dòng xem trước lựa chọn sự kiện hiện tên người (vd “Trận đánh: Nghiêm Muội (Hộ Vệ)”) thay vì chuỗi thô bắt đầu bằng @ao.
- **Nhãn thắng / thua:** lựa chọn có hai nhánh thưởng / phạt ghi rõ “thắng: …, thua: …” (hoặc “thành / bại”).
- **Tự Kiểm Tra:** mục “Kinh mạch + đánh thử” hết báo lỗi.
- Chưa kiểm trong game.

## Bản 7.17.0 · Thiên Mệnh Trong Auto Reroll · Theo Sức Dẫn Kinh Mạch Mới
- **Thiên Mệnh (mới):** Auto Reroll chọn được nước sinh ra, xuất thân, hệ linh căn, phẩm linh căn, thể chất cho kiếp tới; quyền chưa khắc thì khắc ngay trong Tool. Nghịch Thiên / Tuyệt Mệnh không có hiệu lực (Tool báo).
- **Giải thích rõ hơn:** xuất thân có ưu / nhược điểm; đạo lộ đúng thứ tự game, giải thích gập theo nhóm.
- **Sức dẫn kinh mạch:** Auto Build và Bế quan theo luật mới (Tu luyện từ mảnh vượt +60% bị nén).
- **Tab ẩn lâu:** đỡ dồn việc vẽ khi quay lại; Auto vẫn chạy nền.
- Chưa kiểm trong game.

## Bản 7.16.0 · Kết Quả Lựa Chọn Trong Cửa Sổ Sự Kiện · Auto Build Không Treo Với Lưới To
- **Kết quả ngay dưới nút lựa chọn (mới):** mở sự kiện, dưới mỗi lựa chọn hiện luôn được / mất gì, không phải kéo xuống khối “Sự kiện ở đây”.
- **Auto Build với lưới / túi rất to:** không còn hộp “Page Unresponsive”, vẫn bấm và cuộn được khi đang tính; lưới thường như cũ.
- **Auto Build nhanh hơn khi chạy lại:** nhớ điểm đã chấm và bộ xếp tốt nhất lần trước (chỉ trong lúc game mở).
- **Độ mạnh chung:** Hóa Thần không còn dòng “Hóa Thần Sơ” thứ hai; tên tiểu cảnh ghi đủ (Sơ Kỳ … Đại Viên Mãn).
- **Làm gọn mã**, credit Minhndt3 · Shgphuoc ngang hàng.
- Chưa kiểm trong game.

## Bản 7.15.1 · Tab Dị Bảo Đếm Đủ 30 Món (Game 0.0.3)
- **Đếm đủ 30 món:** trước tab Dị Bảo chỉ đếm 21 món; nay đọc thẳng content game nên cộng thêm các món mới vào số đã nhận / tổng.
- **Thẻ Rơi chung (9):** 9 dị bảo chiến đấu mới (Vạn Độc Hồ Lô, Liệu Nguyên Hỏa Kinh, Hám Thiên Quyền Kinh, Ẩm Huyết Ma Bát, Vạn Tái Hàn Tinh, Bồ Đề Xá Lợi, Vạn Linh Cốt Địch, Cửu Cung Trận Đồ, Thiên Môn Lôi Lục) không có sự kiện riêng, rơi từ boss có rơi dị bảo hoặc thủ quan Vô Nhai Uyên tầng 40+. Thẻ liệt kê nguồn và tỉ lệ.
- Chưa kiểm trong game.

## Bản 7.15.0 · Theo Game 0.3.0 (0.0.3 Thế Giới Sống) · Sửa Auto Săn Yêu, Auto Sự Kiện Chạy Cùng Auto, Nâng Cấp Auto Build
- **Theo kịp game 0.3.0:** 155 hàm / hằng lõi Tool dùng đều còn, chỉ `hangTong` thêm tham số (đã khớp lại); dữ liệu nhúng không thiếu id. Hộ Thể và Kháng Tâm Ma chấm theo trần mềm mới của game. Nhận lựa chọn đầu đàn theo dữ liệu sự kiện nên không lệch khi chơi bản tiếng Anh. Chưa kiểm trong game.
- **Auto Săn Yêu · xét đủ mọi con:** trước chỉ chọn lựa chọn đầu của sự kiện Săn yêu. Nay xét cả con đầu đàn; không con nào hợp (màu, loại đã tích, debuff) thì chọn loài hợp nhất trong sổ loài của ô (danh sách “Săn loài khác…” của game). Chưa kiểm trong game.
- **Auto Sự Kiện · sửa lúc chạy lúc không:** tự nối lõi game, lỗi tạm thì thử lại, nhịp kiểm 4 giây, không cần bật ô nổi. **Chạy cùng Auto Săn Yêu / Buôn Bán:** sự kiện thường gặp trên đường được chọn lối lời nhất, ghi vào Nhật Ký Auto. Chưa kiểm trong game.
- **Auto Build · Món Chủ Đạo (mới):** ghim tối đa 3 món, Tool dồn ô đúng màu, huyệt, món sinh, kinh lộ cho món đó trước rồi mới tính tổng; mức Vừa / Mạnh / Tối Đa. **Dò Hướng Build (mới):** thử nhiều hướng theo linh căn và thể chất, chấm cùng một thang, tính thêm lợi khi tẩy mạch; nút Chọn và Áp Dụng. Chưa kiểm trong game.
- **Auto Build · giao diện và lag:** thẻ xếp theo mức dùng, đổi tùy chọn không nhảy về đầu trang; Theo Dõi đỡ lag trên điện thoại (nhịp 5 giây, chờ túi yên 20 giây, xếp lại cách nhau ≥ 90 giây). Chưa kiểm trong game.
- **Tự Phá Bình Cảnh Tiểu Cảnh (mới):** tab Đột Phá & Thọ, mặc định tắt; từ Trúc Cơ, kẹt bình cảnh mà túi có đan / yêu tài đúng đại cảnh thì tự dùng món vừa đủ, rẻ nhất (kiểm 20 giây một lần). Chưa kiểm trong game.

## Bản 7.14.0 · Đại Cập Nhật Trước Thềm Bản Game 0.0.3
- **Auto Săn Yêu · an toàn:** chặn tử trận khi đang mang Thương Nặng, bỏ chạy trận dự đoán thua, bỏ chạy giữa trận khi khí huyết dưới ngưỡng (và bỏ chạy sớm theo Dự Kiến Thật); Tinh Anh/Boss không còn lọt khi chỉ tích Quái Thường, ô **Gặp Loại Quái Không Tích**; uống đan chữa thương từ Thương Nặng, hết đan mới **bế quan dưỡng thương** (tùy chọn). Lỗi lọt Tinh Anh/Boss đã thử trong game rồi sửa; phần còn lại chưa kiểm.
- **Auto Săn Yêu · chọn nơi và mục tiêu:** khoảng giai Từ–Đến, Kiểm Tra Sức đo từng giai, chọn nơi theo lượt và năm đường, báo thời gian hồi, thống kê; **Truy Tìm Đích Danh** theo loài an toàn; **Săn Nguyên Liệu** (truy loài rơi món cần tới khi đủ số). Chưa kiểm trong game.
- **Dự Kiến Thật (mới):** mô phỏng trận bằng chính cài đặt Tự chiến đấu của người chơi, 3 lựa chọn đánh đổi đan/phù và thương nặng, ô nổi, cổng cho Auto Săn Yêu. Chưa kiểm trong game.
- **Sự Kiện (mới):** tab **Tra Cứu Sự Kiện** (tìm không dấu, lọc thưởng, thẻ chi tiết, cây chuỗi sự kiện), ô nổi **Soi Sự Kiện** (mỗi lựa chọn cho gì, tỉ lệ, số thật theo công thức game, khối Tiếp Theo), dòng **Sự kiện ở đây** trong khung nơi chốn, vòng vàng trên bản đồ, ghi kết quả thật để đối chiếu, **Auto Sự Kiện** có chốt an toàn. Đã thử một phần trong game; Auto Sự Kiện chưa kiểm.
- **Kinh Mạch / Auto Build:** bộ **Đột Phá** theo cảnh giới, Nhiều Bộ tích mục đích và chọn thứ tự, thiếu bộ thì xếp bộ có sẵn; Tư Vấn Hướng Build coi trọng thể chất. Chưa kiểm trong game.
- **Auto Buôn Bán:** danh sách giữ / bán gõ tên có gợi ý. **Auto Reroll:** thêm Đạo Lộ **Tuyệt Mệnh** và ô Giải Thích Đạo Lộ Đang Chọn. Chưa kiểm trong game.
- **Giao diện:** thanh trượt cỡ giao diện, sửa kéo khung khi cỡ khác 100%, ô **Tìm trong mod**, thanh cuộn không bị che, chữ thể chất to hơn, tab Trận nhẹ hơn; credit nhỏ Shgphuoc khi rê logo. Chưa kiểm trong game.

## Bản 7.13.0 · Sửa 2 Lỗi, Nâng Cấp Auto Buôn Bán Và Auto Build
- **Sửa lỗi · ảnh Auto Build đè chữ:** ảnh lưới kinh mạch nay nằm trong khung cố định (rộng tối đa 480px, giữ đúng tỉ lệ), không còn tràn ra đè chữ phía sau. Chưa kiểm trong game.
- **Sửa lỗi · ô lọc Phái Tu không chọn được** (Tra Cứu): ô bị gán lại giá trị cũ mỗi lần vẽ nên chọn xong lại nhảy về; nay giữ đúng giá trị vừa chọn, chọn lại được “Mọi Phái Tu”. Chưa kiểm trong game.
- **Auto Buôn Bán:** kiểm túi trước khi mua (túi game tính theo số loại), dùng năm đường thật giữa hai nơi, nhìn trước chuyến kế, mua kèm món khác ở cùng tiệm khi còn lãi, trừ giá một năm đường vào lãi, tính ngập hàng liên chuyến; thêm mục **Bán luôn đồ có sẵn trong túi** (mặc định tắt) chọn loại, phẩm tối đa, số giữ lại, danh sách không bán và giữ riêng từng món. Chưa kiểm trong game.
- **Auto Build · chặn món tà:** hướng Tiên Tu hoặc hướng build chính đạo không bao giờ xếp công pháp / pháp khí tà (ma, độc, hợp hoan, thi, quỷ, nghịch); món tà đang nằm sẵn bị gỡ; không cấm mà món tà chiếm từ 1/3 ô thông thì cảnh báo vàng. Chưa kiểm trong game.
- **Auto Build · bộ lọc theo cảnh giới:** ô Cảnh Giới / Tiểu Cảnh Giới của “Xếp Theo Cảnh Giới” tự theo nhân vật khi lên cảnh giới mới (cả khi Theo Dõi đang chạy). **Số Bộ Kinh Mạch:** ô chọn Một Bộ / Hai Bộ, có lựa chọn dự phòng khi chưa có hoặc chưa cho mở bộ 2, mốc so sánh tính riêng từng bộ. Chưa kiểm trong game.
- **Auto Build · Lĩnh Ngộ:** ô “Cân Nhắc Lĩnh Ngộ” (Theo Thọ Còn Lại / Nhìn Lâu Dài / Nhìn Hiện Tại): đổi cách xếp có tính món mới yếu ×0,5 lúc mới đặt và thọ còn lại; nhật ký ghi món gỡ, món mới, số năm, ba mốc điểm. **Huyệt ×2:** bước tìm có hệ thống cho từng huyệt, nhật ký ghi món nằm trên mỗi huyệt. Chưa kiểm trong game.
- **Auto Build · chế độ mới:** Thuần Thủ (hộ thể, khí huyết) và Thuần Công (sát thương, hạ nhanh), đánh thử thêm 3 quái Tinh Anh. **Gợi ý tẩy mạch:** có lượt chuyển hệ thì Tool hỏi trước khi đổi màu ô (không tự tẩy). **Mở ô nhìn 2 bước** và **Theo Dõi nhẹ** khi chỉ đồ trong túi đổi. Chưa kiểm trong game.
- **Auto Build · hướng kết hợp nhiều hệ** (tối đa 3 hệ, tích ô chọn; cảnh báo cặp khắc nhau), thẻ **Tư Vấn Hướng Build** (top 5, bảng điểm 0–100 là ước lượng của Tool, phương án, nút chọn) và mục **Tông Môn Nên Vào** (chỉ tư vấn, Tool không vào hay rời tông giúp). Chưa kiểm trong game.

## Bản 7.12.4 · Theo Bản Game Mới (index-DVZq2Jz8 · content-CSuoOK5S) · Sửa Auto Săn Yêu Khi Đối Phương Tháo Chạy
- **Không đổi logic theo game:** Tool tự kiểm 34 mục sạch lỗi trong game thật, đủ 69 hàm lõi và 31 hàm game, 644 mã gõ cứng còn nguyên, bảng nhúng khớp content.
- **Sửa:** đối phương mang thương tháo chạy sau trận thì Auto tự chọn Buông tha (nhặt nửa chiến lợi phẩm) nếu game không cảnh báo hậu quả; có cảnh báo hoặc không đọc được thì dừng. Không bao giờ tự Đuổi theo.
- **Đã kiểm trong game thật:** AI tự đánh trận Đỏ/Tím (thắng, bại, tháo chạy), Tinh Anh, dừng đúng khi Trọng Thương, Tốc Chiến 20 trận, Auto Buôn Bán 3 chuyến.
- **Chưa kiểm:** Quái Boss làm mục tiêu, cảnh báo hậu quả khi Buông tha, Auto Kinh Mạch và Reroll trên bản game này.

## Bản 7.12.3 · AI Tự Đánh Và Loại Quái Mục Tiêu Cho Auto Săn Yêu
- **AI tự đánh:** trận game không cho Tốc Chiến (Đỏ, Tím, Tinh Anh, Boss, khí huyết từng dưới 60%) mà màu và loại quái đã tích thì Auto giao chiến và để AI tự chiến đấu của game ra chiêu từng lượt. Dùng cài đặt “Tự chiến đấu” trong game (chưa cài thì không dùng đan/phù). Màu Đỏ đang tích sẵn mặc định nên trận Đỏ sẽ do AI đánh; bỏ tích Đỏ/Tím nếu muốn Auto dừng như cũ.
- **Loại Quái Mục Tiêu:** tickbox Quái Thường (mặc định), Tinh Anh (Lùng con đầu đàn, tốn 2 lượt săn), Boss (lựa chọn giao chiến Boss trong việc lạ giữa đường).
- **Chưa kiểm được:** chưa chạy trong game thật.

## Bản 7.12.2 · Chọn Giai Mục Tiêu Cho Auto Săn Yêu
- **Ô “Mục Tiêu Săn”:** Mọi giai (mặc định) hoặc Vô Giai - Phàm Nhân, Nhất Giai - Luyện Khí, Nhị Giai - Trúc Cơ, Tam Giai - Kết Đan, Tứ Giai - Nguyên Anh, Ngũ Giai - Hóa Thần. Auto chỉ săn ở nơi hoang dã có cấp nền thuộc giai đó (yêu thú ở nơi ấy cùng cảnh giới với giai), và vẫn phải thuộc màu đã tích.
- **Bỏ tickbox “Không săn Thực Thiết Thú/Ấu Thú”:** tickbox né yêu thú dính debuff không né chúng vì game không gắn debuff cho Thực Thiết Thú khi bị giết.

## Bản 7.12.1 · Theo Bản Game Mới (index-DuwMVmDS · content-DSWFs6yv)
- **Dược kháng theo luật mới:** game đổi từ “mỗi cảnh giới đặt lại” sang “mỗi loại đan được thấm N viên cho mỗi cảnh giới, lượt chưa dùng được dồn lại”. Thẻ Hạn Mức Đan và cột Đan ở tab Đột Phá hiện số viên còn thấm theo luật này.
- **Auto Săn Yêu:** bỏ tickbox “Không săn Hạc”, thay bằng “Né tránh yêu thú bị dính debuff sau khi bị giết” (mặc định bật). Tool đọc bảng rơi của game để biết con nào để lại hậu quả xấu (hiện là các loài Hạc trừ Khí Vận), bỏ chạy trước khi Tốc Chiến.
- **Đối chiếu:** 68 hàm lõi còn đủ (chỉ đổi realmDrugUses → drugUsesLeft), bảng nhúng khớp content.
- **Chưa kiểm được:** chưa chạy trong game thật.

## Bản 7.12.0 · Tự Nhận Diện Mod Khác
- **Tool tự thấy mod người khác cài:** đọc danh sách mod game đang nạp và so dữ liệu sống với bản gốc của game để biết mục nào do mod thêm, mục nào mod sửa. Chỉ đọc, không đổi save.
- **Thẻ “Mod Khác Đang Chạy” (Tổng Quan):** từng mod với số mục thêm/sửa, bảng theo bộ dữ liệu, giá trị lạ chưa có nhãn, nút Quét Lại và Sao Chép Danh Sách Mod.
- **Tra Cứu:** món hoặc quái do mod thêm có nhãn MOD, mục mod sửa có nhãn MOD · sửa; bộ lọc nâng cao có ô “Chỉ Mục Của Mod” khi có mod.
- **Không báo nhầm “game đổi”:** mốc ghi cả bộ mod. Cài hay gỡ mod mà game giữ nguyên bản thì Tool báo “bộ mod đã đổi”, vẫn tự chạy thử và cập nhật mốc.
- **Giới hạn:** game không cho biết mod nào đổi luật hay cân bằng, nên Tool chỉ nhắc chung. Mục nào không gán được cho mod cụ thể thì ghi “chưa rõ chủ”. Đã thử trên game thật với mod giả; chưa thử với mod thật của người khác.

## Bản 7.11.1 · Theo Bản Game Mới (index-CtfSr123 · content-Ddm1ZYNO)
- **Không đổi logic:** Tool tự đối chiếu không thấy hàm lõi, hằng số hay luật nào của game đổi. Bảng nhúng Ngự Linh (267 vật, 169 quái, 84 sự kiện, 6 nghi thức), Thể Chất (11) và Dị Bảo (21) vẫn khớp content.
- **Thêm 14 trận văn khôi lỗi vào bảng nhúng:** Tỏa Cốt, Tiễn Vũ, Ti Thuẫn, Liên Khôi, Thiên Ti, Hạc Vũ, Thi Bạo, Thiết Thuẫn, Chấn Địa, Trấn Hồn, Xuyên Giáp, Lôi Tiêu, Lôi Vực, Liên Quân. Game nay có 27 trận văn. 14 món này trước vẫn hiện nhờ luật đoán nhóm; thêm vào để Tự Kiểm Tra hết báo "mục mới".
- **Đối chiếu:** 41 mã gõ cứng trong Tool đều còn trong game; 17 mô tả bổ sung vẫn cần vì game chưa ghi mo_ta.
- **Chưa kiểm được:** chưa chạy trong game thật; dựa trên đọc content và báo cáo tự đối chiếu.

## Bản 7.11.0 · Lớp Bản Đồ Đánh Dấu Sự Kiện Và Nơi Đặc Biệt
- **Không cần mở Trợ Lý:** Tool vẽ thẳng lên bản đồ game (chỗ cắm `mapLayer`). Vòng giữ cỡ cố định khi phóng to; từ mức phóng 1,5 lần hiện tên (tối đa 40 tên, ưu tiên đang mở hoặc sắp hết hạn, rồi gần tâm).
- **Sự kiện (vòng tròn):** đỏ chiến đấu, vàng cửa hàng, tím bí cảnh, lam nhạt đột phá, xanh lá tu luyện, xanh dương sự kiện khác; huy hiệu xám là sự kiện game giấu tên (Mật bí); vòng cam: còn không quá 2 năm là hết hạn.
- **Nơi đặc biệt (hình thoi):** game không đưa di tích, bí cảnh… vào danh sách sự kiện, nên Tool quét thẳng dữ liệu thế giới. Mặc định bật: di tích, bí cảnh, linh mạch, khoáng mạch, sào huyệt yêu thú. Mặc định tắt: lãnh địa yêu thú, quan ải, phường thị, tông môn.
- **Bí cảnh:** hiện đang mở (còn bao lâu), đóng (mở lại sau bao lâu) hoặc đã vào kỳ này, lấy từ chính game. Vòng xanh: đang mở; vòng cam: còn không quá 2 năm là đóng.
- **Sương mù:** mặc định chỉ hiện nơi trong vùng đã mở hoặc đã từng tới (giống game), nên đầu kiếp ít, đi đến đâu hiện đến đó. Ô **Hiện cả nơi còn phủ mây** hiện hết (mờ). Nơi game giấu hẳn không bao giờ lộ.
- **Điều khiển:** khung **Sự Kiện Trên Bản Đồ** trong nút nổi Mod: bật tắt lớp, tên, từng loại sự kiện, quét nơi đặc biệt, từng loại nơi, phủ mây. Mặc định bật; cài đặt nhớ theo trình duyệt.
- **An toàn:** chỉ đọc dữ liệu game, không đổi save, không đổi luật nên không khóa Tỉ thí.
- **Đã kiểm trên game thật (0.0.2):** toạ độ, tên, trạng thái bí cảnh, mở rộng sương mù, đóng Trợ Lý vẫn hiện, khung điều khiển và lưu cài đặt.
- **Chưa kiểm:** vòng cam hết hạn và Mật bí chỉ thử bằng giả lập; chưa thử độ mượt khi hiện rất nhiều điểm hay trên cảm ứng. Luật giấu nơi thuộc khu chưa khám phá là suy ra từ game; nếu thiếu nơi lẽ ra phải hiện, báo Claude.

## Bản 7.10.0 · Sửa Auto Buôn Bán, Tự Xử Lý Việc Lạ
- **Auto Buôn Bán chạy được:** hàm game `facilitiesAt` trả tên tiệm chứ không phải mã sự kiện nên Tool trước đó không thấy tiệm nào và luôn báo "không tìm thấy chuyến buôn". Nay lấy mã tiệm qua `placeActivities`, cùng nguồn giao diện game dùng. Tab Chợ Quanh Đây cũng được sửa theo.
- **Tự xử lý việc lạ (Auto Buôn Bán và Auto Săn Yêu, ô mới, mặc định bật):** khi gặp biến cố không có lối thoát miễn phí, Tool chấm thiệt hại tệ nhất của từng lối theo định nghĩa sự kiện trong game và chọn lối nhẹ nhất (hao thương nhẹ, tốn ít Linh Thạch). Tool vẫn dừng cho bạn quyết định khi mọi lối đều nguy hiểm: tâm ma, hao thọ, mất đồ, giao chiến Đỏ hay Tím hoặc không đọc được màu, mất quá 30% Linh Thạch, việc cần xác nhận hay nhận việc. Tắt ô này nếu muốn Auto dừng ở mọi việc lạ như trước.
- **Kế hoạch buôn:** gộp các dòng giống hệt (nhiều tiệm cùng nơi, cùng giá). **Nhãn phiên bản** đầu cửa sổ lấy theo bản thật.
- **Tự kiểm tra 33 mục:** thêm kiểm mã tiệm quanh nơi và kiểm chấm lối xử trí việc lạ.
- **Đã thử trên game thật** (game_1.zip, game 0.0.2, index-DawzPvUA · content-ClG6Ha-i) chạy trong Chromium cùng mod: Auto Buôn Bán 4 chuyến lãi ròng +3.703 Linh Thạch trong 3,2 năm; Auto Săn Yêu đi đến nơi săn, đánh và dừng đúng khi gặp trận game dự đoán thua; Auto Kinh Mạch xếp lại thật (điểm 100 → 149, gỡ 3 đặt 4); Auto Reroll Tư Chất đổi từ Linh Căn Vô sang Biến Dị (Ám) đúng điều kiện. Nhân vật thử được tăng chỉ số bằng công cụ dev của sandbox nên con số chỉ để kiểm cơ chế, không phản ánh độ khó thật.
- **Đối chiếu game mới:** game_1 thêm 3 hàm (`modDistribution`, `fallenAllyIds`, `woundFallenAllies`) và đổi số tham số của `pickFactionGuest` (đấu giá); không hàm nào Tool dùng bị ảnh hưởng.

## Bản 7.9.1 · Sửa Báo Nhầm Khi Đối Chiếu Bản Game
- **Game mới (0.0.2, index-DawzPvUA · content-ClG6Ha-i) không đổi hàm lõi, dữ liệu hay luật** so với bản trước. Chỗ duy nhất Tool từng báo khác là `kernel/labels.VI_FORMATS` (map(1) → map(2)): bộ nhớ đệm định dạng số, tự đầy khi chơi.
- **Đã sửa:** hằng kiểu bộ nhớ đệm (tên có CACHE, MEMO, FORMATS, hoặc Map chứa toàn máy định dạng Intl) không còn tính vào so mốc và dấu cấu trúc. Nhờ vậy Tool không còn chạy thử lại toàn bộ mỗi lần mở game; cùng một bản game chỉ kiểm một lần.
- **Đối chiếu:** 67 hàm lõi Tool dùng còn đủ trong bản build; bảng nhúng Ngự Linh, nghi thức, Dị Bảo, Thể Chất khớp content mới. Không đổi logic tính toán.
- **Chưa kiểm được:** chưa chạy trong game thật. Lần mở đầu có thể chạy thử lại một lần rồi tự chốt mốc mới.

## Bản 7.9.0 · Tự Động Đối Chiếu Bản Game · Tab Auto Build
- **Bỏ hết nút bấm tay:** xóa các nút **So với mốc**, **Đối chiếu toàn bộ hàm game**, **Chốt mốc mới** và **Tự kiểm tra**. Mỗi lần mở game Tool tự đọc mọi hàm, hằng số và dữ liệu của game (chỉ đọc, không gọi hàm nào nên không đổi save), so với mốc và với danh sách hàm Tool đang dùng.
- **Tự chạy thử khi cần:** bản game chưa từng kiểm sạch lỗi, hoặc có hàm Tool dùng bị đổi/mất → Tool tự chạy toàn bộ mục kiểm tra ngay khi bạn vào một nhân vật (nếu chưa có nhân vật thì chờ, vào là chạy). Kết quả nhớ theo dấu cấu trúc của game nên cùng một bản game không chạy lại.
- **Sạch lỗi thì tự chốt mốc mới; có lỗi thì giữ mốc cũ** và báo ở thẻ Cảnh báo (đầu Tổng Quan) cùng thẻ Tự kiểm tra (nay chỉ hiển thị kết quả, mở "Xem các mục đã kiểm" để xem từng dòng).
- **Kho Dữ Liệu Game:** hiện trạng thái tự đối chiếu, lần đổi gần nhất và bảng chi tiết (mở ra xem). Khi có LỖI, bấm **Sao chép báo cáo nhanh** hoặc **Tải source game** rồi gửi Claude, hai nút này giữ nguyên.
- **Đổi tên tab Hướng Build thành Auto Build** (vẫn trong nhóm Tự Động, giữ nguyên chức năng; "Hướng Build" vẫn là tên lựa chọn hướng trong phần cài đặt).
- **Chưa kiểm được:** chưa chạy trong game thật. Logic tự đối chiếu đã thử bằng môi trường giả lập (cập nhật sạch lỗi, chạy thử lỗi, mất hàm bắt buộc, đổi tham số hàm lõi, chưa có nhân vật, lần đầu chưa có mốc). Nếu hằng số nào của game đổi giá trị trong lúc chơi, dấu cấu trúc thay đổi và Tool chạy thử lại mỗi lần mở game, chỉ tốn thời gian chứ không sai.

## Bản 7.8.0 · Mỗi Tab Xếp Chức Năng Theo Ưu Tiên Từ Cao Xuống Thấp
- **Thứ tự khi cuộn:** thẻ quan trọng, cần xử lý ngay hiện trước; công cụ phải bấm mới chạy, tra cứu, nhật ký, luật chung xuống sau. Áp cho Tổng Quan, Tàng Kinh Các, Bản Mệnh, Đột Phá & Thọ, Trận, Kiếm Linh Thạch, Luyện Đan, Chế Phù, Luyện Bảo, Trận Pháp, Treo Thưởng, Bản Đồ, Dị Bảo, Hướng Build, Thiên Kiêu Bảng, Nhân Mạch, Dự Tính Điểm và ba tab Auto.
  - **Tổng Quan:** Cảnh báo → Tình trạng → nhân vật → Cơ duyên sắp hết hạn → Sư môn → Độ mạnh chung → Tự kiểm tra → Kho Dữ Liệu Game.
  - **Đột Phá & Thọ:** Kế hoạch tới Đại viên mãn → Muốn đạt tỉ lệ đột phá cao nhất → Hạn mức đan → Đan giúp tu vi và thọ → Chỗ bế quan tốt nhất gần đây.
  - **Bản Mệnh:** trạng thái → Chăm Bản Mệnh → Món trong túi tế luyện được → Nuốt món ngộ văn → Cách bản mệnh lớn lên.
  - **Luyện Đan, Chế Phù, Luyện Bảo, Trận Pháp:** công thức đã thuộc (lãi) trước, thi nghề sau. **Thiên Kiêu Bảng:** dự báo hạng nếu bảng cập nhật trước, bảng hiện tại (dài) sau cùng.
  - **Auto Build:** Cài Đặt Chung → Đang Xếp và Kiểm Tra Lưới → Auto Kinh Mạch → Tiến Trình → Xếp Theo Hướng Này → Hai Bộ → Ô Nên Mở → Xếp Theo Cảnh Giới → Phép Tính Giả Định → Hướng Khả Dụng → Cốt Lõi → Nhật Ký, Luật.
  - **Tab Auto:** cài đặt → Tiến Trình → Nhật Ký.
- **Cách làm:** một bảng ưu tiên duy nhất trong mã (`TAB_PRIO`) và một bộ xếp chạy mỗi khi khung nội dung đổi, nên thẻ chèn thêm lúc chạy cũng vào đúng chỗ. Chỉ đổi vị trí thẻ, không đổi nội dung hay cách tính. Thẻ không có trong bảng giữ thứ tự cũ và xuống cuối. Tab Vật Phẩm, Quái Vật, Địa Danh, Đồ Nên Săn, Ngự Linh giữ nguyên.
- **Đối chiếu game 0.0.2 (index-pyGvwuOa · content-AFgvANiO):** 67 hàm lõi Tool dùng còn đủ và đúng số tham số; 49 hằng bản mệnh và hằng độ khó đúng dạng; mọi hàm `game.*` còn; bảng nhúng Ngự Linh (253 vật, 169 quái, 84 sự kiện) và Thể Chất (11) khớp content mới. Không đổi logic tính toán.
- **Sau khi cập nhật:** vào Nhân Vật → Tổng Quan, chạy **Tự Kiểm Tra**; nếu sạch lỗi thì bấm **Chốt mốc mới** ở Kho Dữ Liệu Game.

## Bản 7.7.0 · Theo Hai Đợt Cập Nhật Mới Của Game (Công Phá Sơn Môn · Độ Khó, Đấu Giá, Bảng Dữ Liệu Mod)
- **Đối chiếu game mới:** cả 63 hàm lõi Tool dùng vẫn còn đúng tên module và số tham số (so với danh sách API và chữ ký trong gói mod mẫu mới); bảng nhúng Ngự Linh (253 vật, 169 quái, 84 sự kiện) và Thể Chất (11) vẫn khớp content mới nên không đổi.
- **Dược kháng cứng (Nghịch Thiên, Tuyệt Mệnh):** mỗi loại đan chỉ thấm tối đa 3 viên mỗi cảnh giới ở Nghịch Thiên, 2 viên ở Tuyệt Mệnh; lên cảnh giới mới thì thấm lại. Tool đọc `DIFFICULTY.drugUsesPerRealm` sống từ game.
  - Tab **Đột Phá** thêm thẻ **Hạn mức đan trong cảnh giới này**: Đạo Lộ đang chơi, số viên đã thấm theo từng loại (n/hạn mức), loại nào đã kháng.
  - Bảng **Đan giúp tu vi và thọ**: mỗi đan thọ nguyên ghi thọ nguyên của viên kế tiếp (đã nhân dược kháng), số viên còn thấm và tổng nếu dùng hết; đan đã kháng xếp xuống cuối. Đan đặt bỏ qua dược kháng (như Nghịch Mệnh Đan) ghi rõ không bị dược kháng.
  - Độ khó khác thì thẻ ghi không giới hạn số viên.
  - Dùng hàm game `drugCapped`, `realmDrugUses`, `drugTargetsOf`, `drugRetention` (thiếu thì dùng số dự phòng 3 và 2 theo độ khó).
- **Bản Mệnh:** game sửa lỗi nuốt hoặc tế luyện món dư trong túi khi đang có món cùng loại gắn trên kinh mạch. Tool bỏ lời nhắc "gỡ ra trước" gây hiểu lầm và sửa câu hướng dẫn ở mục Nuốt Món Ngộ Văn. Có làm được hay không vẫn do hàm kiểm tra của game quyết định.
- **Tự Kiểm Tra:** thêm dòng **Dược kháng cứng (7.7.0)**; bảng chữ ký thêm 4 hàm lõi tùy chọn.
- **Không cần sửa:** địch Nghịch Thiên và Tuyệt Mệnh mạnh hơn (bậc AI, bộ đồ đủ vai, đan phù, điểm sở trường) do hàm dựng địch của game áp nên mô phỏng trận của Tool tự theo; bản dịch tiếng Trung, bộ component cho mod, bảng dữ liệu CSV, đấu giá, Thám Bí Cảnh, Công Phá Sơn Môn nằm ngoài phạm vi Tool.
- **Sau khi cập nhật:** vào Nhân Vật → Tổng Quan, chạy **Tự Kiểm Tra**; nếu sạch lỗi thì bấm **Chốt mốc mới** ở Kho Dữ Liệu Game (lần đầu so mốc có thể báo nhiều hàm "mới", đó là phần nội bộ game).

## Bản 7.6.1 · Bản Đồ: Nút Chỉ Dẫn Mũi Tên Đứt
- Tab **Bản Đồ** thêm nút **⇢ Chỉ dẫn** (viền nét đứt) cạnh nút Đi tới ở từng sự kiện, và ở thẻ **Đường đi an toàn** (theo nơi đang chọn).
- Bấm vào sẽ hiện thẻ chỉ dẫn: sơ đồ nhỏ vẽ **mũi tên nét đứt** từ chỗ bạn đang đứng qua từng chặng tới đích, ghi tên địa điểm cụ thể, kèm chuỗi tên nối bằng mũi tên đứt, độ nguy hiểm từng chặng, số năm đi thẳng và đi theo chặng.
- Không tìm được chuỗi chặng đi bộ (khác đại lục, cần thuyền) thì chỉ vẽ một mũi tên thẳng tới đích và ghi rõ lý do.
- Nút chỉ vẽ và liệt kê, không tự đi. Muốn đi thì bấm **Đi tới** ngay trong thẻ chỉ dẫn (vẫn gọi game.travelTo như cũ).

## Bản 7.6.0 · Theo Bản Build Mới Của Game 0.0.2 (Có Mod API Mới)
- **Đối chiếu source build mới:** cả 62 hàm lõi Tool gọi đều còn, đúng tên module, đúng số tham số; 31 hàm `game.*` còn đủ; các bộ dữ liệu content Tool đọc còn đủ. Phần đổi của game (`xungKich` trả về kết quả, `ui.gamePanel`, sự kiện `itemUsed`, `readCtx({ live })`, `tuTien.hud`…) Tool không gọi nên không bị ảnh hưởng. `readCtx()` không tham số vẫn trả bản sao chỉ đọc.
- **Tab Đột Phá thêm cột Phẩm** và thẻ **Phẩm Đạo Cơ:** dùng hàm mới `breakthroughGrade` của game để cho biết phẩm đạo cơ nếu đột phá thành công với từng phương án đan và đốt thọ, kèm bảng **Cầu Phẩm** (cộng bao nhiêu tỉ lệ, phẩm còn lại là gì). Phẩm do game tung theo hạt giống của tháng xung kích nên nghỉ sang tháng khác có thể ra phẩm khác. Game cũ không có hàm này thì cột và thẻ tự ẩn, Tự Kiểm Tra có thêm dòng **Phẩm đạo cơ**.
- **Bảng dự phòng Ngự Linh cập nhật theo content mới:** 10 quái ma hồn (Oán Linh, Âm Hồn, Thủy Quỷ, Thủy Thi, Phù Thi, Hải U Linh, Trầm Uyên Thi, Trầm Giang Quỷ, Trầm Thi Khôi, Quỷ Tân Nương) đổi hệ từ Thủy sang Ám; thêm 3 quái mới: Huyền Dực Ấu Bức, Huyền Dực Bức, Dạ Ảnh Kiêu. Bảng Thể Chất, Nghi Thức đã khớp content, không đổi.
- **Báo cáo nhanh gọn hơn:** game nay mở cả hàm nội bộ qua `tuTien.core` (không cam kết ổn định giữa các bản) nên “Hàm lõi mới” lên tới hàng nghìn. Báo cáo chỉ giữ số lượng theo module và tên mới ở module Tool dùng, không còn dài tới mức bị cắt khi dán.
- **Sau khi cập nhật:** vào Nhân Vật → Tổng Quan, chạy **Tự Kiểm Tra**; nếu sạch lỗi thì bấm **Chốt mốc mới** ở Kho Dữ Liệu Game. Lần đầu so mốc có thể báo rất nhiều hàm “mới”, đó là phần nội bộ game vừa mở, không phải lỗi.
- Mod chỉ đọc dữ liệu, không patch nội dung nên không bị báo “Mod đè nhau”. Gói zip vẫn một thư mục `van_kiep_tro_ly/`, cài như cũ.

## Bản 7.5.0 · Cập Nhật Lõi Theo Game 0.0.2
- Đã thử mod trên bản build game 0.0.2 thật: mọi hàm lõi, hằng số, hàm `game.*` Tool dùng đều khớp `tuTien.core`; Tự Kiểm Tra qua hết.
- **Bảng chữ ký hàm lõi:** game đổi số tham số của hàm nào, Tự Kiểm Tra báo LỖI đúng hàm đó. Gặp thì bấm **Sao chép báo cáo nhanh** ở thẻ Kho Dữ Liệu Game (Tổng Quan) gửi Claude.
- Thêm dòng kiểm tra “Chữ ký hàm lõi” và “Cửa mod của game (tuTien)”; sửa dòng Auto Kinh Mạch báo thiếu Lĩnh Ngộ do khóa cũ.
- Tab **Dị Bảo** thêm thẻ “Dị bảo ngẫu nhiên”, đọc sống từ dữ liệu game.


## Bản 7.4.0 · Hướng Build: Xếp Chạm Trần, Dồn Buff Cho Món Mạnh, Kiểm Tra Lưới
- **Trần chỉ số của game:** Đột Phá từ công pháp tối đa 12%, Hộ Thể trong trận tối đa 60% (thể chất nới thêm), Kháng Tâm Ma tối đa 100%; Tốc Độ Tu Luyện và Khí Huyết không có trần. Tool đọc trần từ game, chỉ thưởng tới trần và trừ phần thừa để nhường ô cho món khác; kế hoạch chọn đồ bỏ qua món chỉ cộng chỉ số đã chạm trần.
- **Dồn buff cho công pháp mạnh nhất:** điểm huyệt, sinh, khắc, kinh lộ nhân theo sức món; sau khi xếp có thêm bước thử đặt riêng từng món mạnh vào mọi chỗ hợp lệ, kể cả chiếm huyệt của món yếu hơn.
- **Thẻ Kiểm Tra Lưới Kinh Mạch:** đếm ô, liệt kê huyệt, thống kê màu ô, bảng trần chỉ số, món mạnh nhất và danh sách Việc Nên Làm xếp theo ưu tiên.
- **Tab Hướng Build sắp lại theo ưu tiên:** Cài Đặt Chung → Đang Xếp và Kiểm Tra Lưới → Auto Kinh Mạch → Xếp Từ Túi → Hai Bộ → Ô Nên Mở → Xếp Theo Cảnh Giới → Phép Tính Giả Định → Hướng Khả Dụng → Cốt Lõi → Nhật Ký → Luật.
- Chạy **Tự Kiểm Tra** (có thêm phép thử Trần Chỉ Số và Kiểm Tra Lưới) trước khi dùng.

## Bản 7.3.0 · Theo Source Game Mới (index-B9-KhXqd · content-CsJvUlAl)
- Đối chiếu source mới: mọi hàm Tool dùng vẫn đủ, không hàm nào mất. Phần đổi thật nằm ở Bản Mệnh, đan đột phá và dữ liệu Ngự Linh.
- **Sửa đọc số liệu văn Bản Mệnh:** game đổi bảng giá trị văn từ 3 lên 5 mốc nên bản trước có thể rơi về bảng dự phòng; nay đọc đúng.
- **Văn có 5 cấp:** cấp 1–3 theo điểm nuốt món (có 20% hụt, 10% nhân đôi); cấp 3→4 và 4→5 là bình cảnh bồi bằng xác suất (20%, 10%), hụt thì cộng may mắn; món không được thấp hơn bản mệnh quá 1 phẩm.
- **Dị văn** (5%, 15% khi chạm cấp tối đa; uy lực ×1,5) và 5 văn mới: Tuyệt Hồi, Nhiễm Lôi, Nhiễm Băng, Nhiễm Phong, Nhiễm Ám.
- **Đan đột phá có trần dược lực** (canh_gioi_toi_da): các bảng đan chỉ liệt kê đan còn hiệu lực ở cửa sắp lên.
- Thêm trứng Dạ Ảnh Kiêu, trứng Huyền Dực Bức và bốn sự kiện khôi lỗi tông môn vào bảng nhúng.
- Chạy Tự kiểm tra sạch lỗi rồi bấm **Chốt mốc mới** ở Kho Dữ Liệu Game.

## Bản 7.2.0 · Giả Định Full Tẩy Tủy Theo Linh Căn
- Nút mới **Giả Định Full Tẩy Tủy Theo Linh Căn** trong **Kinh Mạch → Phép Tính Giả Định** (có chọn độ kỹ Nhanh/Chuẩn/Kỹ).
- Tool lấy linh căn kiếp này (ví dụ Song linh căn Kim–Mộc), xét các hệ liên quan (Kim, Mộc, Thủy là hệ nối hai hệ kia, và Vô sắc), với mỗi hệ giả định đã có món mạnh nhất của hệ đó trong cả game, cho phép đổi màu MỌI ô sang hệ linh căn, rồi xếp lại tối ưu và đánh trận mẫu.
- Kết quả: bảng so từng kịch bản với mốc hiện tại, kịch bản nghiêng về, ảnh cách xếp, đồ nên săn (kèm giá, nơi có) và số ô cần đổi màu. Hợp để chọn đồ săn ở cuối game.
- Chỉ tính trên bản sao nhân vật, không đụng save. Mốc xếp hạng "mạnh nhất" và điểm là ước lượng của Tool; giá, độ khó săn và số lượt đổi màu thật chưa tính.

## Bản 7.1.2 · Né mục tiêu và hối lộ an toàn
- Auto Săn Yêu có hai lựa chọn né **Hạc** và **Thực Thiết Thú/Thực Thiết Ấu Thú**, đều mặc định bật; hai loài Thực Thiết được nhận diện bằng ID dữ liệu game.
- Khi cần bỏ chạy, Tool đọc policy và giá thoát từ helper game; chỉ ném gói vật phẩm khi helper game tính xác suất thoát đạt 100%. Ưu tiên đồ phẩm thấp, bỏ qua đồ khóa, phẩm 8 và item có tag đánh dấu đặc biệt/cổ/Ngự Linh. Phẩm 7 chỉ là dự phòng với món thông thường có giá không quá 26.000.
- Nếu không có gói hối lộ chắc chắn, chỉ dùng Huyết Độn khi vẫn giữ được ngưỡng Thọ Nguyên đã đặt. Nếu trận đã giao chiến, Huyết Độn còn gây thêm 1 bậc Thương Thế nên Tool cũng kiểm tra ngưỡng Thương Thế; nếu không an toàn hoặc không xác minh được thì Auto dừng, không tự tấn công mục tiêu cần né.

## Bản 7.1.1 · Đối chiếu toàn bộ hàm game
- Nút **Đối chiếu toàn bộ hàm game** (thay cho “Đối chiếu bảng nhúng”): quét mọi hàm và hằng số của `tuTien.core`, mọi hàm của đối tượng game, bộ dữ liệu content, thuộc tính/state và khóa `tuTien`, so với mốc. Cho biết hàm nào đổi thân, đổi tham số, mới, mất và cái nào chạm vào hàm Tool đang dùng. Bảng nhúng Ngự Linh/Dị Bảo/Thể Chất vẫn được kiểm ở cuối kết quả.
- Chỉ đọc chữ ký và mã nguồn hàm, **không gọi** hàm nào của game nên không đổi save.
- Mốc mới lưu thêm thân hàm của đối tượng game. Mốc cũ (7.1.0) chưa có, nên lần đầu chỉ so được số tham số; sau khi Tự kiểm tra sạch lỗi, bấm **Chốt mốc mới** để lần sau so được cả thân hàm.
- Bỏ **Tải gói đầy đủ (.json)** và **Tải gói nén (.json.gz)**, thay bằng **Tải source game**: gom mọi tệp cùng nguồn gốc mà trang game đã nạp thành `game.zip` rồi tải xuống (cần tải được JSZip từ cdnjs).
- Tự kiểm tra thêm mục **Hàm game Tool gọi**.

## Bản 7.1.0 · Kho Dữ Liệu Game (API sống)
- Thẻ **Kho Dữ Liệu Game** ở cuối **Nhân Vật → Tổng Quan**: Tool tự đọc hàm, hằng số, dữ liệu từ game đang chạy.
- **So với mốc**: lần đầu mở Tool sẽ tự lưu mốc. Game cập nhật thì bấm nút này để thấy hàm/hằng/trường dữ liệu nào đổi và cái nào chạm vào Tool.
- **Sao chép báo cáo nhanh**: gửi cho Claude (báo cáo đã kèm mã nguồn hàm đã đổi/thiếu). Từ 7.1.1 nút tải gói .json/.json.gz được thay bằng **Tải source game**.
- Hàm lõi đổi chỗ/đổi tên được Tool tự dò lại; bảng nhúng Ngự Linh/Dị Bảo tự ẩn mục game đã xóa.
- Sau khi sửa Tool cho bản game mới và Tự kiểm tra sạch lỗi, bấm **Chốt mốc mới**.

## Bản 7.0.7
- Nút Đi tới ở Bản Đồ/Dị Bảo và nút Đi Đến ở Tra Cứu Địa Danh bỏ hộp xác nhận dư thừa; xác nhận riêng cho truyền tống vẫn giữ nguyên.
- Auto Săn Yêu thêm tùy chọn Không săn Hạc, mặc định bật. Trước Tốc Chiến, nếu gặp địch sống có chữ Hạc trong tên, Auto bỏ chạy theo luật game: ưu tiên linh thạch nếu địch nhận linh thạch và đủ giá; nếu không thì dùng Huyết Độn. Không tự vứt vật phẩm trong túi.
- Thanh nhóm Vật Phẩm/Quái Vật hỗ trợ kéo ngang bằng chuột, lăn chuột và tự cuộn tới nhóm đang chọn; mobile vẫn vuốt ngang được.
- Đồng bộ kiểu ô tìm kiếm ở Địa Danh và tab Trận với thanh tìm kiếm Vật Phẩm/Quái Vật.

## Bản 7.0.6
- Chi tiết chiêu: chỉ hiện phí sử dụng thực tế và hồi chiêu; bỏ phí gốc YAML, uy × tương đối và tag nội bộ khỏi giao diện người chơi.
- Quy đổi sát thương chiêu theo nhân vật bằng helper game; chiêu thể tu dùng sức mạnh thân khi đã thông Tâm Pháp Luyện Thể, nếu chưa thì game vẫn tính theo pháp lực. Không hiển thị số tương đối như sát thương thật.
- Chuẩn hóa nhãn hiệu ứng của mọi loại vật phẩm; ẩn các dòng payload/metadata chung chung nếu không có nội dung hữu ích.

## Bản 7.0.2
- Tra cứu Địa Danh: khi chọn loại Tông Môn mới hiện bộ lọc Hệ Linh Căn và Phái Tu; danh sách lọc lấy trực tiếp từ dữ liệu bản đồ đang chạy.
- Tra cứu Vật Phẩm: thêm bộ lọc Phái Tu cho Tâm Pháp, Đấu Pháp, Pháp Khí chiến đấu và Bảo Vật bị động; Hệ Linh Căn dùng bộ lọc hiện có và đổi nhãn rõ ràng hơn.
- Chi tiết vật phẩm: bổ sung phí/hồi/uy lực, mô tả chiêu, hiệu ứng trận, tác dụng đan/phù, đột phá/bế quan/yêu đan, dị hỏa, trận bàn, trận văn và dữ liệu Ngự Linh khi game có khai báo.
- Ưu tiên helper mô tả chính thức từ `core/character/describe` và `core/character/pham`; không tự dựng thông số game còn thiếu.
- Giữ nguyên ID mod, cấu trúc save và các khóa cài đặt cũ.

## Cài
1. Trong game: **Cấu hình → Mods → Cài mod**, chọn file `.zip` này, bật mod.
2. Tải lại trang (lần đầu game có thể tự tải lại một lần để nạp service worker).
3. Mở Trợ Lý bằng nút ☯ hoặc khung **Trợ Lý** trong nút nổi **Mod** của game.

## Lưu ý
- **Tắt hoặc xóa userscript Tampermonkey cũ** (bản 6.x): hai bản cùng chạy sẽ tranh nhau cửa sổ.
- Cài đặt cũ của Tool (giao diện, cỡ chữ, vị trí nút ☯) giữ nguyên vì dùng cùng khóa localStorage.
- Gặp lỗi: tab **Nhân Vật → Tổng Quan → Tự kiểm tra**, chụp màn hình gửi Claude. Game hỏng vì mod thì mở lại với `?nomods` sau địa chỉ.

## Có gì mới so với 6.20.0
- Đóng gói thành mod; bỏ cách dò ~70 hàm bằng regex và bản sao thứ hai của game.
- Mọi hàm lõi lấy theo tên gốc qua `tuTien.core` nên không vỡ khi game đổi tên rút gọn sau cập nhật.
- Tính toán trên `game.readCtx()` (bản sao chỉ đọc); hằng số cân bằng đọc sống từ `core['balance/…']`.
