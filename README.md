# RSAEncrypt
RSA加解密
1, 生成private_key.pem
2, rsaCerReq.csr 证书请求文件, 公司信息
3,  生成证书rsaCert.crt, 有限期一年

4, ios公public_key.der
5, ios私钥private_key.p12     密码: ru123456

6, java公钥rsa_public_key.pem
7, java私钥pkcs8_private_key.pem

备注java的公钥, 私钥可以直接用

java公钥
-----BEGIN PUBLIC KEY-----
MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQDNhulUeNvPTuI3EvyxIJDJ2qhY
jx4jhIofRnHeE1FxkLMHgJeUA8eIqodgHYu5W0oT333hsPiniCqjEgt8YOccpc6e
j3Wi2entlEy1MGJDa852jWEcYghQSTLpVJQ4ZwMQNCMlfoFyiayUQMh2pfs5lIsH
9YuV/D+7P8MnjJCwMQIDAQAB
-----END PUBLIC KEY-----


java私钥
-----BEGIN PRIVATE KEY-----
MIICdwIBADANBgkqhkiG9w0BAQEFAASCAmEwggJdAgEAAoGBAM2G6VR4289O4jcS
/LEgkMnaqFiPHiOEih9Gcd4TUXGQsweAl5QDx4iqh2Adi7lbShPffeGw+KeIKqMS
C3xg5xylzp6PdaLZ6e2UTLUwYkNrznaNYRxiCFBJMulUlDhnAxA0IyV+gXKJrJRA
yHal+zmUiwf1i5X8P7s/wyeMkLAxAgMBAAECgYAdyUGjpmhk4Q/T34KTwR56wp/H
ReaeSyUhZzo1byNMjCYGHlLZdrrCScSY329Si7JusuMxhE5lKUzUmVbkzb5wm/GB
0Ic0vh12snets4A1HvJYNI4fDyaBu6COT/cGuuc+eOZWR71qvwqu/r3dEDqYljDn
wnuHJtFbjI6uItWDyQJBAOfGIBH1mV/lDb6F+8IA7QMPbClYx7Gi9R+HaRHslrl/
jdDB2aEFZiun+L91qCFBrvuHdQgtWAXGsvd7QPgVlBsCQQDjAnaQqces9Gk+WAz0
LXaPW3+4VTYXC3iJuQh3jfQaIppfXoPs6OztejrCXW50j+dnHFFypKc7Z6oqJCRs
YlmjAkEAv/ov3jBcVj3X4JQCMHOr3fkMUkMjRVQBTZhPw3UAc63fvaaTqPhb5JVB
SPUfykwpsFZG7fsBCefHnY4OBm95OQJAFS9RqUZu3/EfMTY+Xzsu6Un8rVMmbRgg
85lU9PNGaHn6NhQ384/5LGBPw3u8pxwW2ESIRU6gXKbb9nrQ+1xiSQJBAN6hGK/j
oe0lf3lsjr3ksnvhtRFRr56oV9jrT4UJYkPogUld5OLGFskJ950p8/1TLWMNMYIj
f7Vw7ygBAlkYEDo=
-----END PRIVATE KEY-----
