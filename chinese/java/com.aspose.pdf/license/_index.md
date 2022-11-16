---
title: License
second_title: 用于 Java API 参考的 Aspose.PDF
description: 提供许可组件的方法。
type: docs
weight: 192
url: /zh/java/com.aspose.pdf/license/
---
**遗产：**
java.lang.Object
```
public class License
```

提供许可组件的方法。

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及组件的嵌入式资源中查找名为 MyLicense.lic 的许可证文件调用程序集。

许可证 license = new License();
license.setLicense("MyLicense.lic");
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License--) | 初始化此类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | 默认情况下，我们使用默认的 jdk 安全性。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | 默认情况下，我们使用默认的 jre 安全性。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 许可组件。 |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 许可组件。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


初始化此类的新实例。

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及组件的嵌入式资源中查找名为 MyLicense.lic 的许可证文件调用程序集。

许可证 license = new License();
license.setLicense("MyLicense.lic");

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


默认情况下，我们使用默认的 jdk 安全性。默认值 == 假。在某些情况下，自定义的 java 环境无法支持所需的算法，因此我们建议使用内部内置的 FIPS 安全性。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


默认情况下，我们使用默认的 jre 安全性。默认值 == 假。在某些情况下，自定义的 java 环境无法支持所需的算法，因此我们建议使用内部内置的 FIPS 安全性。

另请注意：根据某些操作系统上的 JVM SecureRandom 算法 /dev/random 等待一定数量的\\u201c噪音\\u201d 在返回结果之前在主机上生成。 Oracle中用于随机数生成的库\\u2019s JVM 默认依赖于 UNIX 平台的 /dev/random。尽管 /dev/random 更安全，但它\如果默认 JVM 配置有延迟，建议使用 /dev/urandom，或者添加为 /dev/random 生成熵的设备。

以下 java 选项可以帮助避免延迟并覆盖 securerandom.source 设置。 -Djava.security.egd=文件:/dev/./urandom

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| internalFIPSSecurity | boolean | 布尔值 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


许可组件。

包含许可证的流。

使用此方法从流中加载许可证。

许可证 license = new License();
license.setLicense(myStream);

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 许可证流 |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


许可组件。

尝试在以下位置查找许可证：

1. 显式路径。

2. 组件 jar 文件的文件夹。

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及组件的嵌入式资源中查找名为 MyLicense.lic 的许可证文件调用程序集。

许可证 license = new License();
license.setLicense("MyLicense.lic");

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | java.lang.String | 可以是完整或简短的文件名或嵌入资源的名称使用空字符串切换到评估模式 |

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
