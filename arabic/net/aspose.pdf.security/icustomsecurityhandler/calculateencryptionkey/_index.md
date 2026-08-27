---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة ICustomSecurityHandler. حساب EncryptionKey. عادةً يتم حساب المفتاح بناءً على UserKey. يمكنك استخدام القيم من EncryptionParams التي تحتوي على المعلمات الحالية في وقت الاستدعاء. يتم تمرير هذه القيمة كمعامل المفتاح في Encrypt و Decrypt."
type: docs
weight: 60
url: /ar/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

احسب EncryptionKey. عادةً يتم حساب المفتاح بناءً على UserKey. يمكنك استخدام القيم من EncryptionParams، التي تحتوي على المعلمات الحالية في وقت الاستدعاء. يتم تمرير هذه القيمة كمعامل المفتاح في [`Encrypt`](../encrypt/) و [`Decrypt`](../decrypt/).

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| password | String | كلمة المرور التي أدخلها المستخدم. |

### قيمة الإرجاع

مصفوفة مفتاح التشفير.

### انظر أيضًا

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


