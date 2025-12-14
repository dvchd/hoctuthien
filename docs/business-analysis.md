# Phân tích nghiệp vụ

* Học Từ Thiện
  * Tính năng
    * Đăng ký/Đăng nhập
      * Đăng ký, đăng nhập với Google
        * Ưu điểm
          * Không cần xác thực email
          * Không cần mật khẩu
            * Không cần quên mật khẩu
      * Đăng ký
        * Vai trò mặc định là Mentee
        * Số tài khoản thiện nguyện kích hoạt mặc định
          * 2000
    * Vai trò
      * Mentor
        * Xem thông tin của bản thân
          * Xem và sửa hồ sơ giảng dạy của Mentor
            * Chọn lại tài khoản thiện nguyện mặc định
            * Thay đổi bio, CV, giới thiệu thông tin cá nhân
              * Cần được Admin phê duyệt
            * Chọn lại môn học sẽ giảng dạy
              * Cần được Admin phê duyệt
            * Tính năng nâng cao
              * Có thể thay đổi thời gian được phép đặt lịch trước buổi học
                * Ghi đè mặc định của hệ thống
                * Ít nhất là phải 10 phút
          * Lịch sử giảng dạy
          * Dạy được bao nhiêu buổi
          * Từ thiện bao nhiêu tiền
          * Khi trở thành Mentor, thì sẽ ẩn thông tin cá nhân khi còn là Mentee
          * Xem bảng thành tích học tập của Mentee
            * Tương tự Mentee
          * Xem bảng thành tích giảng dạy của Mentor
            * Tương tự Mentee
        * Sau khi dạy xong, Mentee thanh toán thành công
          * Nâng cao
            * Mentor có thể đánh giá buổi học của Mentee
              * Ví dụ như tinh thần thái độ
              * Không cần chọn số sao
        * Đăng ký lịch dạy
          * Chọn thời gian dạy
            * Chọn thời điểm bắt đầu
            * Chọn thời gian buổi dạy, tính theo tiếng, mặc định là 1 tiếng
          * Đặt lịch định kỳ
            * Lặp theo ngày, hoặc lặp theo tuần, hoặc lặp theo tháng
            * Lặp theo ngày
              * Có thể chọn nhiều mốc trong ngày
            * Lặp theo tuần
              * Có thể chọn các ngày trong tuần
            * Lặp theo tháng
              * Có thể chọn nhiều ngày trong tháng
        * Hủy buổi dạy
          * Nhắn tin thông báo với Mentee trước 1 tiếng diễn ra buổi dạy
          * Chỉ được phép hủy buổi dạy cách thời điểm bắt đầu buổi dạy trên 1 tiếng
          * Nếu trong vòng 1 tiếng mà muốn hủy
            * Nhắn tin thông báo với Mentee
              * Qua gmail
            * Hệ thống vẫn tính là buổi dạy
              * Mentee vẫn đánh giá được Mentor
              * Sau buổi học, Mentor chọn là buổi học đã bị hủy, khi đấy Mentee không cần phải trả tiền cho buổi học
      * Mentee
        * Kích hoạt tài khoản
          * Đăng ký trở thành Mentor
            * Chọn môn học sẽ dạy
            * Chọn tài khoản thiện nguyện mặc định
              * Mục đích là để Mentor có thể tự do quyên góp tới các quỹ thiện nguyện mình mong muốn
            * Chọn số tiền/1 tiếng mặc định
              * Ví dụ 1 buổi dạy có 2 tiếng, 1 tiếng 100k, thì buổi đó hết 200k
            * Nhập CV, bio của Mentor
            * Chờ Admin phê duyệt
            * Thêm thông tin liên hệ của Mentor
              * Zalo
              * Facebook
              * Email
          * Đăng ký lịch học với Mentor
            * Thanh toán sau khi buổi học kết thúc
              * Có thể thanh toán trước chi phí học của buổi học
                * Tùy chọn, không bắt buộc thanh toán trước, ưu tiên thanh toán sau khi đã học, vì nếu thanh toán trước mà buổi học bị hủy, thì phải chịu
              * Có thể thanh toán thừa tiền, khi thanh toán tiền lớn hơn số tiền thực tế của buổi học, thì coi như làm từ thiện thêm
            * Hủy buổi học
              * Trước 1 tiếng mới được phép hủy
                * Nhắn tin liên hệ riêng với Mentor nếu có hủy đột xuất trong 1 tiếng
                * Sau này có thể để Admin cấu hình toàn bộ hệ thống, hoặc Mentor cấu hình riêng
              * Nếu không hủy, mà bùng buổi học, thì sẽ bị Mentor đánh giá
                * Đánh giá 2 chiều
                * Sau khi diễn ra xong, Mentor có thể chọn là buổi học được hủy, khi đấy Mentee không cần thanh toán
                * Sau khi diễn ra xong, Mentee có thể chọn vào phần buổi học đã bị hủy, khi đấy sẽ gửi phê duyệt sang cho Mentor, nếu Mentor Reject thì Admin
            * Nếu như học phí buổi trước chưa thanh toán, thì không được phép đăng ký thêm lịch học
            * Buổi học phải được đặt trước 1 tiếng, nếu 1 tiếng nữa sẽ diễn ra, thì không được phép đặt lịch này
              * Nếu buối học sắp diễn ra trong vòng 1 tiếng, thì Mentee sẽ phải thanh toán số tiền của buổi học mặc dù không học
            * Sau khi thanh toán thành công
              * Mentee có thể đánh giá chất lượng buổi dạy của Mentor
                * Có thể để sẵn một số tag để chọn
                * Chọn từ 1 đến 5 sao
                * Nội dung đánh giá buổi học
                  * Báo cáo vi phạm của Mentor
                    * Mentor quấy rối, Mentor dạy sai kiến thức, Mentor bán hàng đa cấp...
                  * Đánh giá thêm về Mentor
          * Xem thông tin của bản thân
            * Học được bao nhiêu buổi
            * Học hết bao nhiêu tiền
            * Lịch sử học tập
            * Xem bảng thành tích học tập của Mentee
              * Top 10 người học chăm chỉ
                * Theo tuần, theo tháng, theo quý, theo năm
              * Top 10 người đóng học phí
                * Theo tuần, theo tháng, theo quý, theo năm
            * Xem bảng thành tích giảng dạy của Mentor
              * Top 10 người dạy chăm chỉ
                * Theo tuần, theo tháng, theo quý, theo năm
              * Tóp 10 người từ thiện nhiều nhất
                * Theo tuần, theo tháng, theo quý, theo năm
        * Xem danh sách buổi học của các Mentor
          * Khi đăng ký buổi học với Mentor, thì tài khoản phải đang kích hoạt
          * Lọc theo môn học, thời gian bắt đầu
            * Ưu tiên sắp xếp theo số sao giảm dần của Mentor
      * Admin
        * Cấu hình
          * Số tài khoản thiện nguyện kích hoạt mặc định
            * Mặc định hiện tại là số tài khoản 2000
          * Thêm sửa xóa tài khoản thiện nguyện
            * Mentor có thể chọn tài khoản thiện nguyện mặc định trong danh sách tài khoản thiện nguyện khi đăng ký dạy có phí
              * Ưu điểm là sẽ tạo động lực cho Mentor để vận động thiện nguyện
          * Thêm sửa xóa danh sách môn học
            * Subject Tags
          * Số tiền kích hoạt mặc định
            * 10000 VND
          * Xem thống kê tình trạng bùng không trả tiền buổi học, bỏ nick không sử dụng, đăng ký nick mới
            * Nâng giá tiền kích hoạt tài khoản mặc định lên
        * Mở rộng sau thiết kế thêm
          * Localization
            * Cài đặt ngôn ngữ mặc định của hệ thống
            * Cài đặt múi giờ mặc định của hệ thống
            * Đơn vị tiền tệ mặc định
          * Cấu hình gửi email
          * Cấu hình tài khản service account của Google để tạo Event của Google Meet
          * Xem thống kê toàn bộ hệ thống
          * Xác thực Mentor (KYC)
            * Vì Mentor dạy người khác, cần upload ảnh CCCD hoặc Bằng cấp để Admin duyệt. Tránh trường hợp lừa đảo hoặc trình độ kém.
        * Phê duyệt
          * Phê duyệt Mentee trở thành Mentor
          * Phê duyệt buổi học mà Mentee báo cáo Mentor hủy (Sau khi Mentee report là buổi học bị hủy, nhưng Mentor từ chối, hoặc trong vòng 24h không đồng ý)
  * API
  * Database
  * Model
  * UI

