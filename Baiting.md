![image-20200608200436815](images/image-20200608200436815.png)



Dựa vào tài khoản develop từ bài [Entry Point](EntryPoint.md) đăng nhập vào thử ta thu được:

![image-20200608200207603](images/image-20200608200207603.png)



Đề bài có gợi ý sử dụng tài khoản **loginToGetFlag**

=> Ta thử sqli với form đăng nhập, có thể truy vấn tay hoặc sử dụng sqlmap :v

Payload: username=**loginToGetFlag’—**&password=

Flag: **ractf{injectingSQLLikeNobody'sBusiness}**

![image-20200608200841039](images/image-20200608200841039.png)

