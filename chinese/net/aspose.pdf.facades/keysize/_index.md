---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.KeySize 枚举。定义可以用于加密 PDF 文档的不同密钥大小
type: docs
weight: 4390
url: /zh/net/aspose.pdf.facades/keysize/
---
## KeySize 枚举

定义可以用于加密 PDF 文档的不同密钥大小。

```csharp
public enum KeySize
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| x40 | `0` | 40 位密钥。此密钥大小与 RC4 算法一起使用，提供低级别的安全性。然而，旧版本的 PDF 文档只能使用此类密钥进行加密（v. 1.3 及更低版本）； |
| x128 | `1` | 128 位密钥。RC4 和 AES 算法均可使用此密钥大小。 |
| x256 | `2` | 256 位密钥。此密钥大小仅可与 AES 一起使用，并且在最新的 Adobe Reader 版本中被识别（从 v.9 开始）。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../)