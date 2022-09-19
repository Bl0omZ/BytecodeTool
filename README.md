# BytecodeTool

由于个人有需要，故开发可视化，字节码反编译，编码工具。

**反编译的代码均可以保存为.java文件**

------



## BCEL解码+反编译

![image-20220919233253396](./images/BcelDecode.png)



## BCEL编码

编码附件TOMCATEcho.class（输入Path）

`fastjson tomcat回显马`

添加http头`cmd:whoami`

![](./images/BcelEncode1.png)

解码查看代码

![image-20220919233702839](./images/BcelEncode2.png)



## Base64字节码反编译

反编译附件中gateway内存马

先base64解码一次

<img src="/Users/lvzhibo/Library/Application Support/typora-user-images/image-20220919234554253.png" alt="image-20220919234554253" style="zoom:50%;" />

获取实际加载的字节码，反编译

![image-20220919234720281](./images/Base64Decode2.png)

## Base64字节码编码

![image-20220919235027308](./images/Base64Encode.png)