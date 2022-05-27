# Hướng dẫn cài đặt server V2ray
### Các bước để cài đặt server v2ray
- Tạo một cái account [**Heroku**](https://www.heroku.com)
- Fork lại cái repository này của bác có nick name là **Fioren** ( là 1 moderator tại **VOZ** 4rum) ---> [**FiorenMas/v2**](https://github.com/FiorenMas/v2)
    - Do ông moderator đó đã bị ban một tài khoản **Heroku** rồi nên mình khuyên là mọi người nên đổi tên cái repository vừa mới Fork thành 1 cái tên nào đó lạ lạ chứ đừng sử dụng mấy cái tên như **V2ray** hay mấy cái tên tương tự!
- Copy và Paste cái đường link của cái repository vừa mới fork và đổi tên đó vào đây 
    -  `https://dashboard.heroku.com/new?template=https://github.com/XXX tên user/Tên project`
    -  Ví dụ:`https://dashboard.heroku.com/new?template=https://github.com/FiorenMas/myapp`
- Khi nó hiện ra cái bảng deloy thì đừng chỉnh sửa gì, chỉ chyển lựa chọn vùng từ mỹ sang EU để cho ping nó thấp
- Cuối cùng thì ấn deloy rồi ngồi chờ tầm 1 ~ 2 phút
- Sau khi xong xuôi bước cài đặt server rồi thì tải **v2rayNG** về add thủ công VMess:
    - **adress**: là địa chỉ của app **Heroku**. VD: `abcxyz.herokuapp.com`
    - `Port: 80` (mặc định); Nếu như dùng mạng vẫn bị trừ tiền, thì deploy lại, cái bảng deploy sửa thành port 443, khi vào app v2rayNG cũng chỉnh lại 443 luôn
    - Mấy cái này cũng là mặc định hết luôn nha:
    ```
    ID: ad806487-2d26-4636-98b6-ab85cc8521f7
    AlterID: 0
    security: auto
    network: ws
    tls: tls  
    ```
    - Riêng `SNI`: thì tùy nhà mạng
        1. Viettel: `livestream2.tv360.vn`
        2. Mobifone: `mobiedu.vn`
        3. Vietnamobile: `Vietnamobile.com.vn`
 - <ins>Mình hy vọng mọi người không share bài `vô tội vạ` vì nếu mấy ông bên Heroku mà biết thì sẽ ban tài khoản của mình cũng như ông mod Fioren do đây là đồ **illegal**, lúc đầu ông mod còn kêu ko được viết **readme** để hướng dẫn nữa cơ</ins> 
  
