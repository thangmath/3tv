### Launcher nổi nhẹ, đơn giản cho Android TV

Cài launcher cho ATV đã quá quen thuộc với mọi người rồi. Nhưng tại sao chúng ta không xem TV mà "không cần launcher" :D Hình nền video ư, đồng hồ, thời tiết ư, hãy để nó cho screensaver như Aerial Views làm thay.
Chạy theo kiểu overlay, khởi động tv tự mở app cuối & screensaver. 10s khi mở launcher mà ko làm gì cũng chạy screensaver.
Tích hợp nút "tắt nguồn" (tắt hẳn, giúp tiết kiệm điện khi nút nguồn chỉ ngủ) khi giữ vào nút "nhà phát triển" (cần kết nối adb). Bấm giữ icon app để thêm vào thanh dock trên cùng. Dock trên cùng để di chuyển, xoá là ném xuống dưới, ẩn là mất luôn, hiện là hiện lại cái ẩn. Thay đổi icon smarttube standard và tizentube để người già dễ nhận ra.
Tự động xoá ram, kill app chạy ngầm (nên kết nối adb để kill tốt hơn)

Launcher siêu nhẹ, tự làm sơ sài đơn giản, dành cho ai thích phong cách này như mình. Làm hơi nghiệp dư, ae pro xin đừng chê hehe (nhớ bật đầy đủ quyền, quyền vị trí để hiển thị tên wifi, adb chỉ hỏi 1 lần)

Cài creensaver này khá đẹp https://github.com/theothernt/AerialViews/releases
Android đời cao cần mã này để kích hoạt screensaver:
settings put secure screensaver_components com.neilturner.aerialviews/.ui.screensaver.DreamActivity
settings put system screen_off_timeout 360000
