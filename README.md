# SharedPreference
Saving data

BTVN
API : http://g-service.herokuapp.com/api/techkids/login…
URL như thế nhé.
Yêu cầu là Activity Login có 2 cái textbox username và password nhập vào ấn Button Login thì mọi người chạy cái API kia nó sẽ trả về file json
Nếu login OK thì nó trả về như thế này 
http://g-service.herokuapp.com/api/techkids/login…
Còn không thì : http://g-service.herokuapp.com/api/techkids/login…
Nhiệm vụ của mọi người là đọc cái json đó. Nếu login đéo đc thì báo đéo đc, Còn được thì lưu username, password vào SharedPrefercences, từ các lần sau đéo cần đăng nhập nữa Biểu tượng cảm xúc pacman
Login được thì làm những nhiệm vụ sau:
+Trong JSON có trường link, đọc cái đó ra lấy fiel text về. Vì file này là file tạm nên để ở cache.
+ĐỌc cái file text về. có 2 cái link. cái link đầu là file nhạc, mọi người tải về lưu trong mục MUSIC của thẻ nhớ. Link tiếp theo là file ảnh. Mọi người save nó vào mục files của ứng dụng Biểu tượng cảm xúc colonthree
