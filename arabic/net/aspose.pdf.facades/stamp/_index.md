---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.Stamp. تمثيل فئة الختم
type: docs
weight: 4720
url: /ar/net/aspose.pdf.facades/stamp/
---
## فئة الختم

تمثيل فئة الختم.

```csharp
public sealed class Stamp
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Stamp](stamp/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | يحصل أو يحدد قيمة BlendingColorSpace التي تعرف مساحة اللون المستخدمة لأداء عمليات الشفافية والدمج على الصفحة. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | يحصل أو يحدد حالة الخلفية. إذا كانت صحيحة، سيتم وضع الختم كخلفية للصفحة المختومة. بشكل افتراضي، يتم تعيينها على خطأ. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | يحصل أو يحدد شفافية الختم. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | يحصل أو يحدد رقم الصفحة. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | يحصل أو يحدد مصفوفة بأرقام الصفحات التي ستتأثر بالختم. إذا كانت Pages = null، ستتأثر جميع صفحات المستند. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | يحصل أو يحدد جودة صورة الختم كنسبة مئوية. القيم الصالحة 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | يحصل أو يحدد دوران الختم بالدرجات. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | يحصل أو يحدد معرف الختم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | يحدد الصورة التي ستستخدم كختم. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | يحدد الصورة كختم. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | يحدد النص كختم. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | يحدد ملف PDF ورقم الصفحة التي ستستخدم كختم. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | يحدد ملف PDF ورقم الصفحة التي ستستخدم كختم. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | يحدد حالة نص الختم. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | يحدد حجم صورة الختم. سيتم تغيير حجم الصورة وفقًا للقيم المحددة. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | يحدد الموضع على الصفحة حيث سيتم وضع الختم. |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../)