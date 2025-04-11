---
title: Enum PasswordType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PasswordType enum. هذا التعداد يمثل أنواع كلمات المرور المعروفة المستخدمة في مستندات PDF المحمية بكلمة مرور
type: docs
weight: 8290
url: /ar/net/aspose.pdf/passwordtype/
---
## PasswordType enumeration

هذا التعداد يمثل أنواع كلمات المرور المعروفة المستخدمة في مستندات PDF المحمية بكلمة مرور.

```csharp
public enum PasswordType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | مستند PDF غير محمي بكلمة مرور. |
| User | `1` | تم فتح مستند PDF باستخدام كلمة مرور فتح المستند (وصول مقيد). |
| Owner | `2` | تم فتح مستند PDF باستخدام كلمة مرور تغيير الأذونات (وصول كامل). |
| Inaccessible | `3` | مستند PDF محمي بكلمة مرور ولكن كل من كلمات مرور المستخدم والمالك ليست فارغة ولم يتم تعريف أي من كلمات المرور أو كانت كلمة المرور المقدمة غير صحيحة. لذا من المستحيل استنتاج نوع كلمة المرور. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)