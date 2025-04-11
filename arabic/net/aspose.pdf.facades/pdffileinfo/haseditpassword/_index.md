---
title: PdfFileInfo.HasEditPassword
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfFileInfo. تُرجع true إذا كانت كلمة المرور مطلوبة لتعديل الأذونات أو خاصية أمان المستند. انتبه إلى أنه يمكن قراءة هذه الخاصية فقط إذا تم توفير كلمة مرور صالحة في مُنشئ PdfFileInfo. في حالة كون PasswordType غير قابل للوصول، فهذا يعني أنه تم توفير كلمة مرور غير صالحة، وستفشل قراءة هذه الخاصية مع InvalidPasswordException.
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdffileinfo/haseditpassword/
---
## خاصية PdfFileInfo.HasEditPassword

تُرجع true إذا كانت كلمة المرور مطلوبة لتعديل الأذونات أو خاصية أمان المستند. انتبه إلى أنه يمكن قراءة هذه الخاصية فقط إذا تم توفير كلمة مرور صالحة في [`PdfFileInfo`](../) مُنشئ. في حالة كون PasswordType غير قابل للوصول (يعني أنه تم توفير كلمة مرور غير صالحة) ستفشل قراءة هذه الخاصية مع [`InvalidPasswordException`](../../../aspose.pdf/invalidpasswordexception/).

```csharp
public bool HasEditPassword { get; }
```

### انظر أيضًا

* class [PdfFileInfo](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)