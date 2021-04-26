# STM32-TONGHOP
 ## ĐỀ BÀI TẬP:
- Sử dụng 2 nút nhấn để điều khiển số LED sáng như sau:
	+ Khi nhấn Button 1: Có thêm 1 LED sáng lên, nếu đã có 3 LED sáng, thì lần nhấn tiếp theo sẽ không có LED nào sáng lên.
	+ Khi nhấn Button 2: Tắt bớt đi 1 LED, nếu đã không còn LED nào sáng thì lần nhấn tiếp theo sẽ có 3 LED sáng.
- Sử dụng 1 biến trở vặn:
	+ Nếu biến trở đang ở nửa đầu vòng quay thì các LED sáng cố định như trạng thái ở trên.
	+ Nếu biến trở đang ở nửa sau vòng quay thì các LED đang sáng cố định sẽ chuyển qua sáng nhấp nháy (tính năng nhấn nút vẫn còn hoạt động để thêm 1 LED nhấp nháy hoặc tắt bớt 1 LED nhấp nháy).
- Từ phần mềm Hercules, nhập bất kỳ 1 số nào từ 0-3 thì sẽ có số LED sáng tương ứng. Ví dụ, nhập "1" thì 1 LED sáng và LED này sẽ sáng cố định hay nhấp nháy thì tùy thuộc vào giá trị của biến trở.
