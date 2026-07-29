---
title: "ICustomSecurityHandler.Encrypt"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة ICustomSecurityHandler. تشفير مصفوفة البيانات"
type: docs
weight: 80
url: /ar/net/aspose.pdf.security/icustomsecurityhandler/encrypt/
---
## ICustomSecurityHandler.Encrypt method

تشفير مصفوفة البيانات.

```csharp
public byte[] Encrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| data | Byte[] | البيانات للتشفير. |
| objectNumber | Int32 | رقم الكائن الذي يحتوي على البيانات المشفرة. |
| الجيل | Int32 | توليد الكائن. |
| المفتاح | Byte[] | المفتاح المستخرج بواسطة طريقة CalculateEncryptionKey |

### قيمة الإرجاع

البيانات المشفرة.

### انظر أيضًا

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


