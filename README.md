# Embedded-System---ESP32
# Đồ án hệ thống nhúng
  Thầy hướng dẫn: Ths. Nguyễn Trọng Kiên
# Đề tài: Hệ thống chữa cháy thông minh
  Môn này mình đồng hành cùng những người bạn:
      1.Phan Minh Trung – N19DCCN217
      2. Nguyễn Duy Tài – N19DCCN163
      3. Nguyễn Tiến Tài – N19DCCN164
      4. Nguyễn Thị Thanh Tuyền – N19DCCN183
      5. Đỗ Văn Tuyền – N19DCCN182
      6. Trần Hữu Trưởng – N19DCCN222
      7. Mai Đức Thắng – N19DCCN193
      5. Lê Quốc Thiên – N19DCCN195
  - Mục tiêu của nhóm đề ra: Mục tiêu của đề tài là xây dựng hệ thống chữa cháy thông minh nhằm giảm thiểu và hạn chế tối đa tác hại, tổn thất do các vụ cháy nổ, hỏa hoạn gây ra.  
Hệ thống sử dụng và kết hợp những công nghệ hiện đại để đảm bảo tính chính xác, độ hiệu quả của một hệ thống chữa cháy.
  - Ý tưởng thực hiện của nhóm:
      * Dùng Arduino thu thập dữ liệu từ cảm biến nhiệt độ, cảm biến khí gas và ESP32 Camera thu thập dữ liệu hình ảnh theo thời gian thực rồi gửi lên server.
      * Server xử lý dữ liệu và trả kết quả cho Arduino để thực hiện xử lý, điều khiển thiết bị (bật động cơ bơm nước nếu phát hiện có cháy), đồng thời trả kết quả về giao diện để hiển thị cho người dùng.
  - Luồng giao tiếp của hệ thống: Các bạn xem luồng giáo tiếp của hệ thống trong phần slide của mình (HTN - Slide(1).pptx
  - Các thiết bị chúng mình sử dụng: Arduino, Cảm biến nhiệt (LM35), Cảm biến ga (MQ2), ESP32-Cam, Relay và động cơ bơm nước
  - AI 
    * Bộ dataset sử dụng: https://www.kaggle.com/datasets/antrosafin/fire-dataset-in-yolo-format![image](https://user-images.githubusercontent.com/108974521/232848330-ed8a38a0-9d1e-4325-acca-33b77193eb80.png)
        + Sử dụng OpenCV và YOLO để phát hiện và nhận diện cháy
        + Dung YOLO để train bộ Dataset để được file trích xuất đặc trưng (best.pt) từ bộ dataset, file model này dùng để nhận dạng và phát hiện lửa
   - Firebase & Note - RED     

  

 




