# SMx
国产加密算法 SMx 
## SM2
椭圆曲线公钥加密算法
## SM3
HASH摘要算法
## SM4
分组对称加密算法
## doc
标准与说明文档


# lucifer 编译补充
## SM2

vs2019下，sm2编译用的openssl链接库比较早，需要调整

//修正/lucifer/2023年3月1日
// 1.sdl检查关闭
// 2.openssl升级
//https://blog.csdn.net/Zenor_one/article/details/89791118
//https://ask.csdn.net/questions/7616392

#pragma comment(lib, "libssl.lib")
#pragma comment(lib, "libcrypto.lib")

## SM3
##
//https://blog.csdn.net/sgfmby1994/article/details/80432205

## SM4

>无补充
