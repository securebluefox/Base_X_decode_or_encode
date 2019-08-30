# 多种base编码的编码/译码器

本项目目前支持对以下编码的编码/译码

```
1.Base16
2.Base32
3.Base36
4.Base62
5.Base64
6.Base58
7.Base85
```

同时本脚本支持两种使用模式，完整模式和快速模式

在未给定参数时自动进入完整模式，完整模式下程序会询问您相关信息

快速模式的参数列表如下:

```
python Base.py [16/32/36/62/64/58/85] [0/1] [plain_text/cipher_text]
[16/32/36/62/64/58/85]:使用的base编码类型
[0/1]:加密or解密(0 or 1)
[plain_text/cipher_text]:明文or密文
```

使用时请安装以下模块

```
base36
base58
base62
base64
```

本代码在`Python 3.6.5`下测试通过！

**Base 92的模块导入存在问题，会产生与内置函数冲突的问题~如有大佬解决请提issue联系我。**