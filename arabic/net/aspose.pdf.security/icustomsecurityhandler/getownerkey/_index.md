---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة ICustomSecurityHandler. تنشئ مصفوفة مشفرة بناءً على كلمات المرور التي سيتم كتابتها في الحقل O من قاموس التشفير. يجب الاعتماد فقط على الوسائط الممررة. يمكن حساب كلمة مرور المستخدم من هذا الحقل باستخدام كلمة مرور المالك. تُستدعى أثناء التشفير لإعدادها وتعبئة قاموس التشفير. ستكون القيمة متاحة في CalculateEncryptionKey للحصول على المفتاح من UserKey. سيتم تمرير كلمات المرور التي حددها المستخدم عند استدعاء تشفير المستند. قد لا يتم تحديد كلمات المرور أو قد يتم تحديد كلمة واحدة فقط."
type: docs
weight: 100
url: /ar/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

تنشئ مصفوفة مشفرة بناءً على كلمات المرور التي سيتم كتابتها في الحقل O من قاموس التشفير. يجب الاعتماد فقط على الوسائط الممررة. يمكن حساب كلمة مرور المستخدم من هذا الحقل باستخدام كلمة مرور المالك. تُستدعى أثناء التشفير لإعدادها وتعبئة قاموس التشفير. ستكون القيمة متاحة في [`CalculateEncryptionKey`](../calculateencryptionkey/) للحصول على المفتاح من UserKey. سيتم تمرير كلمات المرور التي حددها المستخدم عند استدعاء تشفير المستند. قد لا يتم تحديد كلمات المرور أو قد يتم تحديد كلمة واحدة فقط.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |

### قيمة الإرجاع

مصفوفة مفتاح المالك.

### انظر أيضًا

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


