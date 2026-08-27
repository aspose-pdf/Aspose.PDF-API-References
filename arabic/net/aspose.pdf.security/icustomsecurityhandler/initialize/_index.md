---
title: "ICustomSecurityHandler.Initialize"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة ICustomSecurityHandler. تُستدعى لتهيئة الكائن الحالي للتشفير. لاحظ أنه عند التشفير سيتم ملء البيانات بخصائص ICustomSecurityHandler المنقولة وعند فتح المستند من قاموس التشفير. إذا تم استدعاء الطريقة أثناء تشفير جديد فإن UserKey و OwnerKey سيكونان فارغين."
type: docs
weight: 120
url: /ar/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

تُستدعى لتهيئة الكائن الحالي للتشفير. لاحظ أنه عند التشفير، سيتم ملء البيانات بخصائص [`ICustomSecurityHandler`](../) المنقولة، وعند فتح المستند من قاموس التشفير. إذا تم استدعاء الطريقة أثناء تشفير جديد، فإن [`UserKey`](../../encryptionparameters/userkey/) و [`OwnerKey`](../../encryptionparameters/ownerkey/) سيكونان فارغين.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| معلمات | EncryptionParameters | معلمات التشفير. |

### انظر أيضًا

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


