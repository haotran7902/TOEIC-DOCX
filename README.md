## L1 Tổng quan
## Dữ liệu
Dữ liệu ở khắp mọi nơi.
Ubiquitous (Ubiquitous computing) - tính toán rộng
- Dữ liệu: là số, chữ, hình ảnh, video,... phục vụ người dùng,
- Dữ liệu (theo tín hiệu) gồm:
  + Tín hiệu tương tự (Analog): tín hiệu liên tục
  + Tín hiệu số (Digital): Tín hiệu rời rạc
- Dữ liệu (theo đo đạc) gồm:
  + Định tính (Categorical)
    ++ Norminal (định danh) - không thứ tự
    ++ Ordinal (thứ bậc) - có thứ tự
  + Định lượng (Numerical) - Đo được
    ++ Discrete (rời rạc) - đếm được, ví dụ: số đơn hàng
    ++ Continous (liên tục) - đo được, ví dụ: chiều cao, cân nặng

- Xử lý dữ liệu là thêm | sửa | xóa dữ liệu
## IOT
- IOT là nối PC, Sensor, Mobile
- Sensor: là thiết bị chuyển từ tín hiệu tương tự sang tín hiệu số

## Máy tính
- Máy tính là công cụ để tính toán và lưu trữ thông tin.
- Máy vi tính là máy tính dựa trên bộ vi xử lý
- Máy tính
    + Máy tính tương tự
    + Máy tính số
        ++ Lớn
        ++ Mini
        ++ micorprocesser 
            +++ Motorola M68000 (Apple MAC)
            +++ Intel PC
                ++++ 8088: XT
                ++++ 80286: AT
*Ví dụ từng loại máy tính*
Máy tính
├── Tương tự → Máy tính analog quân sự tính toán đường đạn, máy đo analog
└── Số
     ├── Lớn (Mainframe) → IBM System/360, IBM z15: Dùng cho tổ chức lớn, xử lý khối lượng giao dịch khổng lồ
     ├── Mini (Minicomputer) → DEC PDP-11, DEC VAX: Nhỏ hơn Mainframe
     └── Vi tính (Micro) → IBM PC/XT (8088), IBM PC/AT (80286),
                            Apple Macintosh (Motorola 68000),
                            Laptop hiện đại (Intel/AMD)

- IBM: International Business Machine

## Thống kê
- Thống kê là ngành khoa học dựa vào quan sát để kiểm định các giả thuyết
- Có 2 loại thống kê:
    + Mô tả: Mô tả về hiện tượng
    + Suy luận: Để suy ra cái gì đấy
- Lập luận (Reasoning): từ những cái đã biết rút ra cái mới
    + Ví dụ: Biết "Trời có mây đen" và "Mây đen thường báo hiệu mưa" → lập luận ra "Có thể trời sắp mưa".
- Suy luận (Inference): 
    + Lập luận trong hệ chuyên gia (Expert system)
    + Đây là cơ chế mà "Động cơ suy diễn" của hệ chuyên gia sử dụng để xử lý các luật (rules) và sự kiện (facts) trong cơ sở tri thức nhằm đưa ra kết luận/giải pháp cho vấn đề)
    + Có 2 chiến lược suy luận chính:
        ++ Suy luận tiến: từ dữ kiện có sẵn -> áp luật -> ra kết luận
        ++ Suy diễn lùi: từ giả thiết -> tìm ngược lại dữ kiện hỗ trợ
    + Ví dụ (hệ chuyên gia chẩn đoán bệnh):
        Luật: "NẾU sốt cao VÀ ho VÀ mất vị giác THÌ có thể mắc COVID-19"
        Dữ kiện: bệnh nhân có sốt cao, ho, mất vị giác
        → Suy luận: có thể bệnh nhân mắc COVID-19

- Suy diễn (deduction): Lập luận theo Modus Ponens
    + Quy tắc Modus Ponens
    ```
    Nếu A → B (đúng)
    Và A (đúng)
    Thì B (đúng)
    ```
