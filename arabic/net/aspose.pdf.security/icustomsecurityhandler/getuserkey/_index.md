---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة ICustomSecurityHandler. تنشئ مصفوفة مشفرة بناءً على كلمة مرور المستخدم. تُستخدم هذه القيمة عادةً للتحقق مما إذا كانت كلمة المرور تنتمي إلى المستخدم أو المالك وللحصول على مفتاح التشفير. تُستدعى أثناء التشفير لإعدادها وتعبئة قاموس التشفير. تُمرَّر كلمة المرور المحددة من قبل المستخدم كمعامل عند استدعاء تشفير المستند."
type: docs
weight: 110
url: /ar/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

ينشئ مصفوفة مشفرة بناءً على كلمة مرور المستخدم. تُستخدم هذه القيمة عادةً للتحقق مما إذا كانت كلمة المرور تخص المستخدم أو المالك، وللحصول على مفتاح التشفير. يُستدعى أثناء التشفير لإعداده وتعبئة القاموس المشفر. يتم تمرير كلمة مرور المستخدم المحددة كوسيط عند استدعاء تشفير المستند.

```csharp
public byte[] GetUserKey(string userPassword)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |

### قيمة الإرجاع

مصفوفة مفتاح المستخدم.

### انظر أيضًا

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


