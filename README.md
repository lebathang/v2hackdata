# Hướng dẫn tạo server V2ray
### Các bước để cài đặt server v2ray
- Tạo một cái account [**Heroku**](https://www.heroku.com)
- <ins>Cách 1</ins>: Fork lại cái repository này của mình 
    - Vì có ông moderator nick name là **Fioren** tại **VOZ** 4rum đã bị ban một tài khoản **Heroku** rồi nên mình khuyên là mọi người nên đổi tên cái repository vừa mới Fork thành 1 cái tên nào đó lạ lạ chứ đừng sử dụng mấy cái tên như **V2ray** hay mấy cái tên tương tự!
- Copy và Paste cái đường link của cái repository vừa mới fork và đổi tên đó vào đây 
    -  `https://dashboard.heroku.com/new?template=https://github.com/XXX tên user/Tên project`
    -  Ví dụ:`https://dashboard.heroku.com/new?template=https://github.com/FiorenMas/myapp`
- <ins>Cách 2</ins>: Hoặc bạn cũng có thể click vào đây

     [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/lebathang/v2hackdata)
    - Dành cho người thích `mì ăn liền`, tuy nhiên cái repository mà bạn đang deloy trên **Heroku** là của mình chứ không phải của bạn nên bạn ko có quyền nào khác, còn nếu bạn làm theo <ins>cách 1</ins> thì cái repo là do bạn sở hữu nên bạn có quyền chỉnh sửa theo ý thích của bạn, và mình có thể sẽ bị xóa cái repo này trong 1 ngày nào đó, nên hãy tạo bản sao cho bạn
- Khi nó hiện ra cái bảng deloy thì đừng chỉnh sửa gì, chỉ chyển lựa chọn vùng từ mỹ sang EU để cho ping nó thấp
- Cuối cùng thì ấn deloy rồi ngồi chờ tầm 1 ~ 2 phút
- Sau khi xong xuôi bước cài đặt server rồi thì tải **v2rayNG** về add thủ công VMess:
    - **address**: là địa chỉ của app **Heroku**. VD: `abcxyz.herokuapp.com`
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
    - Vì **Heroku** cứ mỗi 30p thì tắt VPS, nên nếu muốn để giữ nó được lâu thì dùng cái repository này ping cho nó thức -->[Kaffeine](https://github.com/RomainButteaud/Kaffeine), tuy nhiên nó chỉ thức liên tục 22 ngày/tháng thôi đó 😃
  > Mình hy vọng mọi người không share bài `vô tội vạ` vì nếu mấy ông bên Heroku mà biết thì sẽ ban tài khoản của mình cũng như ông mod Fioren do đây là đồ **illegal**, lúc đầu ông mod còn kêu ko được viết **readme** để hướng dẫn nữa cơ
  
