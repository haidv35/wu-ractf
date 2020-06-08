![image-20200608013311823](images/image-20200608013311823.png)

Login với tài khoản của chall trước

![image-20200608013527987](images/image-20200608013527987.png)

Decrypt JWT: eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VyIjogIkRhdmUiLCAicHJpdmlsZWdlIjogMX0.jxWh4j1ZvT3nsOQY6B1h-mniCtyx535TUG9hDsg3s_g

![image-20200608013623685](images/image-20200608013623685.png)

=> Có ít nhất 3 trường: id, user, privilege => Bypass bằng cách cho privilege khác 1, SQLi tay hoặc sử dụng sqlmap với payload như sau: 

Payload: ' union select 2,2,2--

Path: /admin

Flag: **ractf{j4va5cr1pt_w3b_t0ken}**