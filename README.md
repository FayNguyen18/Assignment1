Task 2:

Tiếp theo, bạn sẽ cần phân tích dữ liệu có trong tệp bạn vừa mở để đảm bảo rằng nó ở đúng định dạng. Mỗi tệp dữ liệu chứa một loạt câu trả lời của học sinh ở định dạng sau:

N12345678,B,A,D,D,C,B,D,A,C,C,D,B,A,B,A,C,B,D,A,C,A,A,B,D,D
hoặc

N12345678,B,,D,,C,B,,A,C,C,,B,A,B,A,,,,A,C,A,A,B,D,
Giá trị đầu tiên là số ID của sinh viên. 25 chữ cái sau là câu trả lời của học sinh cho kỳ thi. Tất cả các giá trị được phân tách bằng dấu phẩy. Nếu không có chữ cái nào sau dấu phẩy, điều này có nghĩa là học sinh đã bỏ qua việc trả lời câu hỏi.

Lưu ý rằng một số dòng dữ liệu có thể bị hỏng! Ví dụ: dòng dữ liệu này không có đủ câu trả lời:

N12345678,B,A,D,D,C,B
Và dòng dữ liệu này có quá nhiều câu trả lời:

N12345678,B,A,D,D,C,B,D,A,C,C,D,B,A,B,A,C,B,D,A,C,A,A,B,D,D,A,B,C,D,E
Nhiệm vụ của bạn cho phần này của chương trình là thực hiện như sau:

2.1. Báo cáo tổng số dòng dữ liệu được lưu trữ trong tệp.

2.2. Báo cáo tổng số dòng dữ liệu không hợp lệ trong tệp.

Một dòng hợp lệ chứa danh sách 26 giá trị được phân tách bằng dấu phẩy
N# cho một học sinh là mục đầu tiên trên dòng. Nó phải chứa ký tự “N” theo sau là 8 ký tự số.
