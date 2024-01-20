# Face Analysis
Cài đặt và import các thư viện cần thiết (python = 3.10 OpenCV version: 4.8.0) chạy file crop_img đẻ cắt tập dữ liệu đã được cung cấp Chuyển tập ảnh đã cắt về file trainmodel Chia train test cho tập dữ liệu 80/20 Training và chỉnh sửa tham số để train tập dữ liệu Tập test được chạy qua file DetectAndCropImage phần detect để detect ra bbox Rồi tập đã bbox chạy qua phần crop trong file DetectAndCropImage để cắt ảnh Tập ảnh được cắt được đưa vào file trainmdel để predict ra thông tin các thuộc tính Age Emotion Gender Race Masked Skintone

Lưu lại các thông tin vào file answer 



Note: Các file images_sample.html là các folder ảnh được chia sẻ và lấy đường dẫn kết nối từ máy server để đọc file và lấy đường dẫn vì nó quá nặng nên không lưu được trên máy cá nhân
