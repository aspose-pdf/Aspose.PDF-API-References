---
title: PdfFileInfo.HasEditPassword
second_title: Aspose.PDF for .NET API Reference
description: PdfFileInfo 属性。如果需要密码来修改权限或文档安全属性，则返回 true。请注意，只有在 PdfFileInfo 构造函数中提供了有效密码时，此属性才能被读取。如果 PasswordType 为 Inaccessible（意味着提供了无效密码），则读取此属性将失败并抛出 InvalidPasswordException。
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/pdffileinfo/haseditpassword/
---
## PdfFileInfo.HasEditPassword 属性

如果需要密码来修改权限或文档安全属性，则返回 true。请注意，只有在 [`PdfFileInfo`](../) 构造函数中提供了有效密码时，此属性才能被读取。如果 PasswordType 为 Inaccessible（意味着提供了无效密码），则读取此属性将失败并抛出 [`InvalidPasswordException`](../../../aspose.pdf/invalidpasswordexception/)。

```csharp
public bool HasEditPassword { get; }
```

### 另请参阅

* 类 [PdfFileInfo](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)