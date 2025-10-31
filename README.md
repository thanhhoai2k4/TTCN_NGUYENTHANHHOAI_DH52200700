# TTCN_NGUYENTHANHHOAI_DH52200700
Đây là nơi báo cáo thực tập chuyên ngành

# Thông Tin Sinh Viên
<b>SV</b>: Nguyễn Thanh Hoài.</br>
<b>Gmail</b>: disbray100@gmail.com.</br>
<b>MSSV</b>: DH52200700</br>
<b>Giáo Viên Hướng dẫn</b>: Trần Quốc Trường.

Link đến github chính: [Revit Viet Kit](https://github.com/thanhhoai2k4/RevitVietKit)



# Bao Cáo

<table>
  <tr>
    <td>
      <img src="images/image001.png" alt="Ảnh 1" width="700px">
    </td>
    <td>
      <img src="images/image002.png" alt="Ảnh 2" width="700px">
    </td>
  </tr>
</table>

Chuẩn bị dữ liệu:
- Tải dữ liệu từ [Cubicassa5k](https://zenodo.org/records/2613548): 5k hình ảnh với nhãn là các file svg. Đọc các file SVG. trích xuất các labels ra. Và lưu vào thư mục riêng. Chuẩn đầu vào của YOLO SEG. Với định dạng(polygon):
> label x1,y1 x2,y2 x3,y3 x4,y4.

- Đăng data lên drive: sau đó sử dụng colab. để huấn luyện. Tuy nhiên với lượng dữ liệu lớn và tần suất của các label xuất hiện dày đặc vì thế cần huấn luyện với thời gian dài. Thực tế khi em huấn luyện model trên colab dù em đả chọn model với tham số ít nhất (nano). thì nó vẫn bị chậm.=>Em nghỉ đến 1 lựa chọn là Thue 1 GPU. Trước đây em đả từng thuê GPU để huấn luyện [PHÁT HIỆN ĐỐI TƯỢNG YOLO V3](https://github.com/thanhhoai2k4/yolo-v3-by-tensorflow) và keras CV cho phát hiện đèn giao thông.

Danh sách việc cần làm tuần sau:
- Viết 1 dự án nhỏ để có thể tự động huấn luyện model từ máy tính khác.
- Thuê  [GPU](https://thuegpu.vn/) để huấn luyện.</td>
- Đánh giá.
- Cân nhắc làm việc tiếp theo nếu hoàng thành sớm.