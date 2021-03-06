---
layout: page
title: 稳定版本
permalink: /releases/
---

# 版本发布和下载

BabaSSL使用Github的Release功能来实现版本的发布，请移步以下页面进行下载：

[https://github.com/BabaSSL/BabaSSL/releases](https://github.com/BabaSSL/BabaSSL/releases)

需要注意的是，BabaSSL目前只提供源代码的版本发布，暂不提供任何二进制版本的发布（包括但不限于RPM, DEB等）。

# 项目公钥

BabaSSL在发布新的版本的时候，会使用项目的私钥对源代码包进行签名，使用者应当使用BabaSSL的项目公钥对其下载到的源代码包进行签名验证，以防止源代码包的内容被篡改。公钥内容如下：

~~~
-----BEGIN PGP PUBLIC KEY BLOCK-----

mQINBGC5xZkBEAC/f09tTFF6g4YfGkEFH3igrsiBxPDe9h9BLABa922G9vuLGT71
BHH1fVAxVOWvDsD8NA+cjEgqDTEZfT3dLbbeK3ZDtq2ntz6SZZGyXuKZ2kmYeRvK
rZytAyPv9a441wFde/wWEnYxoC2CGGPAXoEq40W4G9gGtWguGJq5+0JrzeP/48P4
7Bx1XJwIieuxMd24Dv7QLEBqITvmURvAaxTsbwji3pdcHNpGpy/oDjlWF9XJJoaR
L/AzycOxmK4+FT8jpj8GbkSLjQ/3dqfgEjSmLAf1MgJt+ximeTTz4/iV8CQ+0Bu7
KH8y2lrSNdVN2H/yqnp2YMvsoeTcfwno5PJbSUUXSPfH7yMWZy+dHpLgLxuCwC8w
lKvv9Xbtbm/bH4VYkXs4SOSeHNXx+FjOdOQ7QZUg9miU0bZun8WmR+FgARzyqNr7
j+84i6eNrIRrwvPsu4mwDqCk4AhGOaLsRFWkZHrPO/BoXMfCuY9Aeec/BRLwmlWg
oBO4Fk16aDRVEselDowWMXn9h5s14Uq6enJf7jGq7oa0i84RhQWBR6Tpv/Blk1ub
wpMUMIsDxzmB0kpRoOYpH1Mpb64C12LIYY3kygttD7kPklPABdlwpRP2tastq3g8
Ib0WgK15S1F0LwVujIPFCQH8GcswNEY3ziZQhn06xmOsqM7yfXfzKpxT8wARAQAB
tFhCYWJhU1NMIFByb2plY3QgVGVhbSAoVGhlIGtleSB1c2VkIHRvIHNpZ24gQmFi
YVNTbCByZWxlYXNlIGZpbGUpIDxrYWlzaGVuLnl5QGFsaXBheS5jb20+iQJUBBMB
CAA+FiEEPbRoN42fc+LA4Wxkz4c+oAhREeQFAmC5xZkCGwMFCRLMAwAFCwkIBwIG
FQoJCAsCBBYCAwECHgECF4AACgkQz4c+oAhREeRXMQ/+JzQvcYmadaD8HYT3EESX
B99S0e0bXF4ijxEz9bOkGy+vjxd8krOn54cKcCMDxbnlzY6P4Ha9fR38AfR4hii7
zoUMUi5a9Iq8YlmyXj5IA4JWSl7TYkbQUPSmQ3hlcbA1iV8cSKE77WY0hDcHIyDP
Xronfo0BH23OXGlKmAUEODCQYJFAIUgK5uPvvxsQ5A/N6F9mHk3+1BQ/RKT6iYxN
vXT/BsDNwpssZPCgfIFbPcC2i+Owq+XcYdPRRb7NQ7B3onP/vbMVwbZPEiHt7CVo
hcH34Bb/oWtACbkHoKDA8KBdtDjkaaKcuNXeVv9ThccKLGBJgl4saXGQq589pQ8Z
y+o+jvVN68e86lSVYvkDUX+JZcPBYAPl7HvDMeSLuRyayZMfvaKMxGMQkBA5YlNI
jI77mB/fllxjABtbiEuHBbbTu5rFpLnetzCFES7AVxTTiddnft+A2PbhwU9DuTNX
LK0Zop53Xl0rJ0qByM72CoFZdQdjzBkLmNP4FxoxtMPdWbE3rn+Keek3eL32pwke
tDm+u6mGW9075hRsXgFy6qe1g8S/vJKSxYqhAeZ7tV9g3pSeKe3t4mXYeN9e4+cT
1nDKV6FcszLssiMSasMEjWs9uzqzkrjLDx5+h/FTH+a8rbGtMKJeKp0YjqNZvWCT
WTxmt7iN2kiccigq9n7ODKG5Ag0EYLnFmQEQAMOvHPBgLm3gOiklmZ47qm5dQ9xk
rNuf/2VLh7HApobnwfKvu8M9ae3scHH4yux6AqrQCiY/smORH4Eq+7SuoV08SilJ
7+oQv1A0xvOrmCW/1zCS6wX04oFGVJqE3Hq1OP3M2aPvlSLlk1FHEpsKwHcb7BNW
6xTOdaMysZwS/7bfQsqyPdvi1lA7z54EJ086E6cRd8gygfIT35tj3yp1PZNawtvy
vt6O8Zfv++jyJwm1JQc8Jr47+EsoZsiulfbniZCq3q+6CvJfwdiwAjfja/6+NULs
1oHTpwKwvLZLyTdf/yJ8lj0w/2kLUCTUiZwuOUmRegErZI1ka77bMpLfcCE96g9J
HXw2WYyV9S0Nmo2RLjTUjMW9+T918B1OS3m5AMnpWpZnwlhXKGpckVXAeajhrxgA
PDqRtt49oVhgVICS04bzdoNeeysXGpJ/ex+De1ugbGiboeXUzbWiRdiixkPd2bCY
apn7kGRjCKitI6FYhjM0xXV2izdtMh47W+0Z7gi2q7Cq5UrfHu0wIUw/5nOYWr6J
yiz3Qbx1huTsCi+GtJup34wqMQXeM6JRNevPwRbWhr1spXN16IKJ9mY2JSh4f2D4
fdoi4UTjkFmtEvCil0ERv2RqMaAAdKC1dp+XdqBdJsQ3CXhffy5dHPTMKxaWPC9r
shRAF2O4SuRn+DBvABEBAAGJAjwEGAEIACYWIQQ9tGg3jZ9z4sDhbGTPhz6gCFER
5AUCYLnFmQIbDAUJEswDAAAKCRDPhz6gCFER5A2lD/0V4YMzecotrvPowhroK8Jx
IaDMtdGD8fuskJRXHlN+UyUOo3VYyuWlzU4CxGtdeDmjyOYANRrxFc4Ob/jrfhAp
iSyP596aJVdORCgOxvWwW2RIHRi9tjoEfKykWYzzW6GINMkIbUIzObiAWAWpIIZo
mwlV81/csJpSRW9EzLXwdtDb00sK7UYeOosIKtAojeU6dAUCBA6roju+4YZugL9c
jCQnaV5w3TQjyw9gxoL14S4khMjR4Rif03gS5+1G2mUFeuwYjGVK4Qf8zUkY+pOK
RLSdLxlTRWpi8svdl32Hc0uVBL3FjMxeYY6ThCVtB1fbucQXs6zD1871C+ahLa2E
q2himu5cK5Y2cRrI1QtNQ0JyS1MzLA3FQ+nsqh225LFOycxf7tF3YsaVZs2EnFmH
cDL7rzpjoa/v773QG246qFmRMYLh2zYS0C0Mvj7joDUNQ6QXtseUOYWX9lUcXnz9
hCRSe/imNXQdxQuUIAcTWuUr8TvJopJPv3Jzkz29WKEB6kFUG2Gt3f4AOEatXhgw
5wmbDGZbZYYmtBonWh4KvzQMBQFGfSH9tZIy64SE/nIGnuQXzq8XZn0ztiTOkLRy
ZHCIz+FVERKc6Z3V7R8q+OfxdnkF2glJ3FFbT+OSKWb2yX4DL6HRSV1WCK2HZ3CO
0r7KG+pwj3+3Xs4KTTwtpw==
=n+IJ
-----END PGP PUBLIC KEY BLOCK-----
~~~

## 公钥的使用方法

BabaSSL使用PGP来对发布的源代码包进行签名，签名值单独以`.asc`结尾的文件保存在Github的源代码包下载页面上：

~~~
BabaSSL-8.2.0.tar.gz.asc
BabaSSL-8.2.0.zip.asc
~~~

在验证某个下载了的源代码包之前，需要准备好可用的PGP工具并保存本页面上公布的公钥内容。现在以在Linux/Unix环境下的命令行（使用GnuPG工具）来说明如何对一个BabaSSL的源代码释放版本进行完整性和来源校验，其他PGP的工具原理相同，使用方法各有差，这里不再赘述。

### 下载源码包和签名

在Github的Releases页面上下载BabaSSL的源代码包和对应的签名文件，例如：

~~~
BabaSSL-8.2.0.tar.gz
BabaSSL-8.2.0.tar.gz.asc
~~~

### 保存公钥

将前述公钥值保存为一个文件，例如BabaSSL-public.key；或者，如果你熟悉并且使用某个PGP的keyserver的话，也可以在其中搜索BabaSSL Project Team或者公钥ID：CF873EA0085111E4，来找到BabaSSL的官方公钥。

### 导入公钥

~~~
$ gpg --import BabaSSL-public.key
~~~

执行上述命令，将BabaSSL的公钥导入。

### 使用公钥对源码包进行验签

~~~
$ gpg --verify --default-key "BabaSSL Project Team" BabaSSL-8.2.0.tar.gz.asc BabaSSL-8.2.0.tar.gz
gpg: Signature made Fri Jun  4 15:07:37 2021 CST
gpg:                using RSA key 3DB468378D9F73E2C0E16C64CF873EA0085111E4
gpg:                issuer "kaishen.yy@alipay.com"
gpg: Good signature from "BabaSSL Project Team (The key used to sign BabaSSl release file) <kaishen.yy@alipay.com>" [ultimate]
~~~

这样，就可以利用公钥密码学的原理来确保你所下载的BabaSSL源代码包的内容没被篡改过且确实是由BabaSSL项目团队所发布的。
