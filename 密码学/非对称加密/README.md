# 非对称加密

## 公玥密码

### RSA

三个开发者的名字首字母
```
密文=明文^E mod(N)

公钥=E和N的组合

明文=密文^D mod(N)

公钥=D和N的组合
```

RSA可以解决密钥配送问题，但无法解决中间人攻击

RSA算法很慢