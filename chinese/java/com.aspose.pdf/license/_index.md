---
title: "许可证"
linktitle: "许可证"
second_title: "Aspose.PDF for Java API 参考"
description: "提供对组件进行授权的方法。在此示例中，将尝试在包含组件的文件夹中查找名为 MyLicense.lic 的许可证文件。"
type: docs
weight: 2670
url: /zh/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

提供对组件进行授权的方法。在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。 License license = new License(); license.setLicense("MyLicense.lic");

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License](#License--) | 初始化此类的新实例。在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。License license = new License(); license.setLicense("MyLicense.lic"); |

## 方法

| 方法 | 描述 |
| --- | --- |
| [clearLicense](#clearLicense--) | 清除当前许可证。 |
| [getLicenseInfo](#getLicenseInfo--) | 获取当前许可证信息。 |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | 默认情况下，我们使用默认的 JDK 安全。默认值 == false。在某些情况下，定制的 Java 环境可能不支持所需的算法，因此我们建议使用内部内置的 FIPS 安全。 |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | 默认情况下，我们使用默认的 JRE 安全。默认值 == false。在某些情况下，定制的 Java 环境可能不支持所需的算法，因此我们建议使用内部内置的 FIPS 安全。<p> 另请注意：根据 JVM SecureRandom 算法，在某些操作系统上 /dev/random 会在返回结果前等待主机生成一定量的“噪声”。Oracle 的 JVM 用于随机数生成的库在 UNIX 平台上默认依赖 /dev/random。虽然 /dev/random 更安全，但如果默认的 JVM 配置导致延迟，建议使用 /dev/urandom，或添加生成熵的设备供 /dev/random 使用。<p> 以下 java 选项可以帮助避免延迟并覆盖 securerandom.source 设置。-Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | 为组件授权。包含许可证的流。使用此方法从流中加载许可证。License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | 为组件授权。尝试在以下位置查找许可证：1. 明确路径。2. 组件 jar 文件的文件夹。在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

初始化此类的新实例。在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

清除当前许可证。

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

获取当前许可证信息。

**Returns:**
LicenseInfo 实例

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

默认情况下，我们使用默认的 JDK 安全。默认值 == false。在某些情况下，定制的 Java 环境可能不支持所需的算法，因此我们建议使用内部内置的 FIPS 安全。

**Returns:**
布尔值

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

默认情况下，我们使用默认的 JRE 安全。默认值 == false。在某些情况下，定制的 Java 环境可能不支持所需的算法，因此我们建议使用内部内置的 FIPS 安全。<p> 另请注意：根据 JVM SecureRandom 算法，在某些操作系统上 /dev/random 会在返回结果前等待主机生成一定量的“噪声”。Oracle 的 JVM 用于随机数生成的库在 UNIX 平台上默认依赖 /dev/random。虽然 /dev/random 更安全，但如果默认的 JVM 配置导致延迟，建议使用 /dev/urandom，或添加生成熵的设备供 /dev/random 使用。<p> 以下 java 选项可以帮助避免延迟并覆盖 securerandom.source 设置。-Djava.security.egd=file:/dev/./urandom

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| internalFIPSSecurity |  | 布尔值 |

### setLicense {#setLicense-java.io.InputStream-}
为组件授权。包含许可证的流。使用此方法从流中加载许可证。License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
为组件授权。尝试在以下位置查找许可证：1. 明确路径。2. 组件 jar 文件的文件夹。在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。License license = new License(); license.setLicense("MyLicense.lic");
