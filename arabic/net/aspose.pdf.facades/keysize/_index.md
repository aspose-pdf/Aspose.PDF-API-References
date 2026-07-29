---
title: "تعداد KeySize"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "تعداد Aspose.Pdf.Facades.KeySize. يحدد أحجام مفاتيح مختلفة يمكن استخدامها لتشفير مستندات pdf"
type: docs
weight: 4510
url: /ar/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

يحدد أحجام المفاتيح المختلفة التي يمكن استخدامها لتشفير مستندات pdf.

```csharp
public enum KeySize
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| x40 | `0` | مفتاح 40 بت. يُستخدم هذا الحجم من المفتاح مع خوارزمية RC4 ويوفر مستوى أمان منخفض. ومع ذلك، يمكن تشفير إصدارات pdf القديمة فقط باستخدام مثل هذه المفاتيح (الإصدار 1.3 وما أدنى). |
| x128 | `1` | مفتاح 128 بت. يمكن لكل من خوارزمية RC4 وخوارزمية AES استخدام هذا الحجم من المفتاح. |
| x256 | `2` | مفتاح 256 بت. يمكن استخدام هذا الحجم من المفتاح فقط مع AES ويُعترف به في أحدث إصدارات Adobe Reader (بدءًا من الإصدار 9). |

### انظر أيضًا

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


