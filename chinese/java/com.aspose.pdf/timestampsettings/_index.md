---
title: TimestampSettings
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示在签名过程中使用的 ocsp 设置。
type: docs
weight: 391
url: /zh/java/com.aspose.pdf/timestampsettings/
---
**遗产：**
java.lang.Object
```
public class TimestampSettings
```

表示在签名过程中使用的 ocsp 设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TimestampSettings(String serverUrl, String basicAuthCredentials)](#TimestampSettings-java.lang.String-java.lang.String-) | 初始化 TimestampSettings 类的新实例。 |
| [TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm)](#TimestampSettings-java.lang.String-java.lang.String-int-) | 初始化 TimestampSettings 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasicAuthCredentials()](#getBasicAuthCredentials--) | 获取基本的认证凭证，Username和password组合成一个字符串“username:password”。 |
| [getClass()](#getClass--) |  |
| [getDigestHashAlgorithm()](#getDigestHashAlgorithm--) | 获取/设置内部哈希函数的摘要算法。 |
| [getServerUrl()](#getServerUrl--) | 获取时间戳服务器 url。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBasicAuthCredentials(String value)](#setBasicAuthCredentials-java.lang.String-) | 设置基本的认证凭证，用户名和密码组合成一个字符串“username:password”。 |
| [setDigestHashAlgorithm(int value)](#setDigestHashAlgorithm-int-) | 获取/设置内部哈希函数的摘要算法。 |
| [setServerUrl(String value)](#setServerUrl-java.lang.String-) | 设置时间戳服务器 url。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TimestampSettings(String serverUrl, String basicAuthCredentials) {#TimestampSettings-java.lang.String-java.lang.String-}
```
public TimestampSettings(String serverUrl, String basicAuthCredentials)
```


初始化 TimestampSettings 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| serverUrl | java.lang.String | 时间戳服务器 url。 |
| basicAuthCredentials | java.lang.String | 基本身份验证凭据、用户名和密码组合成一个字符串“用户名:密码”。 |

### TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm) {#TimestampSettings-java.lang.String-java.lang.String-int-}
```
public TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm)
```


初始化 TimestampSettings 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| serverUrl | java.lang.String | 时间戳服务器 url。 |
| basicAuthCredentials | java.lang.String | 基本身份验证凭据、用户名和密码组合成一个字符串“用户名:密码”。 |
| digestHashAlgorithm | int | 哈希算法名称，如果省略则使用 sha1。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getBasicAuthCredentials() {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```


获取基本的认证凭证，Username和password组合成一个字符串“username:password”。

**退货：**
java.lang.String - 字符串值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDigestHashAlgorithm() {#getDigestHashAlgorithm--}
```
public final int getDigestHashAlgorithm()
```


获取/设置内部哈希函数的摘要算法。

**退货：**
int - DigestHashAlgorithm 元素
### getServerUrl() {#getServerUrl--}
```
public String getServerUrl()
```


获取时间戳服务器 url。

**退货：**
java.lang.String - 字符串值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBasicAuthCredentials(String value) {#setBasicAuthCredentials-java.lang.String-}
```
public void setBasicAuthCredentials(String value)
```


设置基本的认证凭证，用户名和密码组合成一个字符串“username:password”。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setDigestHashAlgorithm(int value) {#setDigestHashAlgorithm-int-}
```
public final void setDigestHashAlgorithm(int value)
```


获取/设置内部哈希函数的摘要算法。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | DigestHashAlgorithm 元素 |

### setServerUrl(String value) {#setServerUrl-java.lang.String-}
```
public void setServerUrl(String value)
```


设置时间戳服务器 url。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
