#Hello!
#Đây là phần backend mình đã xây dựng của website bán phụ kiện gaming.
#Website mình xây dựng theo mô hình MVC.
-**Model** : Là nơi tương tác trực tiếp với Database( mongodb)
-**View**: Mình sử dụng react
-**Controller**: Là nơi trung gian nhận yêu cầu từ View sau đó xử lý, giao tiếp với Model để lấy dữ liệu trả về View. Trong phạm vi dự án này, sử dụng framwork ExpressJs để xây dựng server backend.
#Về phần backen.
-**B1**: Index.js mình xây dựng sever với `Port: 3001`, và kết nới với MongoDB Alas (cơ sở dữ liệu online)
-**B2**: từ index.js chạy đên index.js trong file routes nơi mình tạo những routes : user, product, order và xác định các phương thức của routes.
-**B3**: routes kết nối với controllers và kết nối với service.
