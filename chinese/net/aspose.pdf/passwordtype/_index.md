---
title: Enum PasswordType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PasswordType 枚举。此枚举表示用于受密码保护的 PDF 文档的已知密码类型
type: docs
weight: 8290
url: /zh/net/aspose.pdf/passwordtype/
---
## PasswordType 枚举

此枚举表示用于受密码保护的 PDF 文档的已知密码类型。

```csharp
public enum PasswordType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | PDF 文档未受密码保护。 |
| User | `1` | PDF 文档是使用文档打开密码（受限访问）打开的。 |
| Owner | `2` | PDF 文档是使用更改权限密码（完全访问）打开的。 |
| Inaccessible | `3` | PDF 文档受密码保护，但用户和所有者密码均不为空，并且未定义的密码或提供的密码不正确。因此，无法推断密码的类型。 |

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)