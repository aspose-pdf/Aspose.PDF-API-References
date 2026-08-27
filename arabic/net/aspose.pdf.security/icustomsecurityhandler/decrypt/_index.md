---
title: "ICustomSecurityHandler.Decrypt"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة ICustomSecurityHandler. فك تشفير مصفوفة البيانات"
type: docs
weight: 70
url: /ar/net/aspose.pdf.security/icustomsecurityhandler/decrypt/
---
## ICustomSecurityHandler.Decrypt method

فك تشفير مصفوفة البيانات.

```csharp
public byte[] Decrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| data | Byte[] | البيانات لفك التشفير. |
| objectNumber | Int32 | رقم الكائن الذي يحتوي على البيانات المشفرة. |
| الجيل | Int32 | توليد الكائن. |
| المفتاح | Byte[] | المفتاح المستخرج بواسطة طريقة CalculateEncryptionKey |

### قيمة الإرجاع

البيانات المفكوكة.

### انظر أيضًا

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


