![image-20200608195922439](images/image-20200608195922439.png)



![image-20200608200018078](images/image-20200608200018078.png)



Dựa vào tài khoản develop từ bài [Entry Point](EntryPoint.md) đăng nhập vào thử ta thu được:

![image-20200608200207603](images/image-20200608200207603.png)



Ta nhận thấy tài khoản **jimmyTehAdmin** được in đậm và có từ **Admin** trong chuỗi, nên rất có thể là tài khoản admin. Thử sqli với form đăng nhập

Payload: username=**jimmyTehAdmin' or password LIKE 'a%’—**&password=1

Flag: **ractf{!!!4dm1n4buse!!!}**

![image-20200608200347540](images/image-20200608200347540.png)