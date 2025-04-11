---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: 许可证方法。为组件授权
type: docs
weight: 20
url: /zh/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

为组件授权。

```csharp
public void SetLicense(string licenseName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | 字符串 | 可以是完整或简短的文件名或嵌入资源的名称。使用空字符串切换到评估模式。 |

## 备注

尝试在以下位置查找许可证：

1. 显式路径。

2. 包含 Aspose 组件程序集的文件夹。

3. 包含客户端调用程序集的文件夹。

4. 包含入口（启动）程序集的文件夹。

5. 客户端调用程序集中的嵌入资源。

**注意：**在 .NET Compact Framework 上，仅尝试在以下位置查找许可证：

1. 显式路径。

2. 客户端调用程序集中的嵌入资源。

[Java]

2. 包含 Aspose 组件 JAR 文件的文件夹。

3. 包含客户端调用 JAR 文件的文件夹。

### 另请参阅

* 类 [License](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

为组件授权。

```csharp
public void SetLicense(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | 流 | 包含许可证的流。 |

## 备注

使用此方法从流加载许可证。

### 另请参阅

* 类 [License](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)