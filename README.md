# STM32-UART
 ## ĐỀ BÀI TẬP:
1. Từ phần mềm Hercules gửi xuống chuỗi "LED ON\n" hoặc "LED OFF\n". Nếu nhận được chuỗi "LED ON" thì bật đèn LED trên board mạch thực hành, nếu nhận được chuỗi "LED OFF" thì tắt đèn LED.(Lưu ý gửi \n bằng cách nhập <LF>). Lưu ý: nhận dữ liệu ở chế độ Interrupt.
2. Từ phần mềm Hercules gửi xuống chuỗi "Temperature:xx", với xx là 2 kí tự có giá trị từ 00 -> 99. Hãy lập trình để nhận chuỗi trên và tách ra giá trị xx. Nếu xx nhỏ hơn 50 thì bật LED. Nếu xx lớn hơn hoặc bằng 50 thì tắt đèn LED. Lưu ý: nhận dữ liệu ở chế độ Interrupt.
3. Cho trước một chuỗi gồm các từ cách nhau bởi khoảng trắng (space): "Universal Asynchronous Receiver Transmitter". Thực hiện tách chuỗi này thành các chuỗi con và hiển thị lên màn hình. Ví dụ:
"Universal"
"Asynchronous"
"Receiver"
"Transmitter"
