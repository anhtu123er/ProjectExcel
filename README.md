# ProjectExcel
 
## Phân tích doanh thu và tình trạng giao hàng thông qua cơ sở dữ liệu bán hàng từ năm 2017 đến năm 2020:
    SOURCE: https://github.com/anhtu123er/ProjectExcel/tree/main/Power%20Query%26%20Power%20Pivot
    ANALYZE BY EXCEL: https://github.com/anhtu123er/ProjectExcel/blob/main/Practice.xlsx
## Các bước thực hiện:
    Bước 1: Xử lý và làm sạch dữ liệu (đây là bước quan trọng nhất trong quá trình phân tích dữ liệu bởi vì nếu không có khung dữ liệu được chuẩn hóa hay có nhiều yếu tố ngoại lai thì kết quả phân tích sẽ không có nhiều giá trị)
    Công cụ sử dụng: Power Query
    Trích xuất dữ liệu ở 4 file bán hàng từ năm 2017 đến năm 2020 ta import dữ liệu dưới dạng folder từ đó ta tiến hành tranform dữ liệu bằng các kiểm tra xem các dữ liệu có sai sót về kiểu dữ liệu hay giá trị hay không, các đầu mục đã được sử dụng đúng chưa bởi vì trong quá trình tập hợp dữ liệu dễ xảy ra các sai sót về đầu mục, làm tròn số tập phân,... Sau khi đã kiểm tra và chính sửa hoàn chỉnh ta tiến hành load data sang sheet cụ thể.
    Bước 2: Bước đầu tiên để nắm bắt được thông tin cần phân tích đó chính là xác định các dim và fact. 
    Cụ thể các FACT phân tích trong bài đó chính là doanh thu và thời gian giao hàng
    Các DIM: Khu vực, Loại sản phẩm, chuỗi thời gian, hình thức vận chuyển, đóng gói,...
    Để xác định được các dim và fact, ta có thể phân tích thông qua công cụ remove duplicate để tìm ra các dim phù hợp để phân tích, đối với các dim có số phần tử lớn ta khó có thể phân tích được hoặc sẽ phân tích bằng cách gộp nhóm lớn(có thể sử dụng tính năng ADD COLUMN trong PowerQuery). Cụ thể đã được tình bày ở sheet Phân tích DIM FACT.
    Bước 3: Dựa trên các DIM FACT đã được xác định, ta lựa chọn sử dụng các biểu đồ phù hợp với các khía cạnh cần mô tả.
    Bước 4: Xây dựng Dashboard và tùy chỉnh.
    
