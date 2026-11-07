Phần 1: So sánh Trade-off & Kết luận
1. So sánh 2 Phương án:

Downtime: Phương án 1 bị kéo dài do chờ Senior Dev; Phương án 2 giảm 80%, KTV tự sửa trong 5–10 phút.

Áp lực Senior Devs: Phương án 1 gây áp lực rất cao do bị phân tâm bởi lỗi cơ bản; Phương án 2 tối ưu chi phí, Senior Dev chỉ nhận các ca lỗi phức tạp.

Năng lực KTV: Phương án 1 làm KTV thụ động và sợ tiếng Anh; Phương án 2 giúp KTV chủ động và tư duy phân tích tốt.

Lưu vết tri thức: Phương án 1 bị thất thoát trên Zalo; Phương án 2 lưu trữ tập trung thành kho tài liệu Wiki nội bộ.

2. Kết luận:
Ban Giám đốc bắt buộc chọn Phương án 2 để ngăn thiệt hại rủi ro downtime (500k/giờ/trụ) khi mở rộng lên 1,000 trạm, bảo vệ tài nguyên Senior Dev và tạo khả năng mở rộng hệ thống bền vững.

Phần 2: Quy trình Gỡ lỗi 4 Chặng
Chặng 1 (Google Operators): Khi có Error Pop-up, KTV bóc tách từ khóa chính và dùng toán tử site:, "", -. Nếu sửa xong thì dừng, nếu mơ hồ chuyển Chặng 2.

Chặng 2 (StackOverflow/GitHub): Đọc lướt 30s, ưu tiên câu trả lời có tích xanh (✓) hoặc nhiều Upvote. Nếu sửa xong thì dừng, nếu không khớp chuyển Chặng 3.

Chặng 3 (Hỏi AI): Gửi Prompt 3 thành phần ([Context] + [Raw Error] + [Instruction]) lấy giải thích tiếng Việt. Nếu xong thì lưu Wiki rồi dừng, nếu thất bại sau 15 phút chuyển Chặng 4.

Chặng 4 (Bug Report): Điền phiếu báo lỗi chuẩn 4 bước (Bối cảnh -> Mong muốn -> Thực tế -> Error Log) gửi về IT Helpdesk/Senior Dev.