---
title: "枚举 KeySize"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.KeySize 枚举。定义可用于加密 pdf 文档的不同密钥大小。"
type: docs
weight: 4510
url: /zh/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

定义可用于加密 pdf 文档的不同密钥大小。

```csharp
public enum KeySize
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| x40 | `0` | 40 位密钥。此密钥大小与 RC4 算法一起使用，提供低级别的安全性。然而，旧版本的 pdf 文档只能使用此类密钥进行加密（v. 1.3 及以下）。 |
| x128 | `1` | 128 位密钥。RC4 和 AES 算法均可使用此密钥大小。 |
| x256 | `2` | 256 位密钥。此密钥大小只能与 AES 一起使用，并在最新的 Adobe Reader 版本（从 v.9 开始）中得到支持。 |

### 另请参见

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


