<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thể loại sách</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            padding: 0;
        }

        h1 {
            text-align: center;
            margin-top: 20px;
        }

        .categories {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
            flex-wrap: wrap; /* Đảm bảo ảnh tự động xuống dòng khi không đủ không gian */
            max-width: 100%;
            padding: 0 20px;
        }

        .category {
            width: 200px;
            text-align: center;
        }

        .category img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 8px;
            transition: transform 0.3s ease; /* Tạo hiệu ứng khi hover */
        }

        .category img:hover {
            transform: scale(1.05); /* Phóng to nhẹ khi di chuột vào */
        }

        .category h3 {
            margin-top: 10px;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <h1>Thể loại sách</h1>
    <div class="categories">
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/van_hoc_v2.jpg?raw=true" alt="Văn học">
            <h3>Văn học</h3>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/khoa_hoc_v2.jpg?raw=true" alt="Khoa học">
            <h3>Khoa học</h3>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/lich_su_v2.jpg?raw=true" alt="Lịch sử">
            <h3>Lịch sử</h3>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/kinh_doanh_v2.jpg?raw=true" alt="Kinh doanh">
            <h3>Kinh doanh</h3>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/thieu_nhi_v2.jpg?raw=true" alt="Thiếu nhi">
            <h3>Thiếu nhi</h3>
        </div>
    </div>
</body>
</html>
