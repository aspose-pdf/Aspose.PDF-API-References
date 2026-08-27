---
title: "فئة Stamp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Facades.Stamp. فئة تمثل Stamp"
type: docs
weight: 4840
url: /ar/net/aspose.pdf.facades/stamp/
---
## Stamp class

فئة تمثل الختم.

```csharp
public sealed class Stamp
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Stamp](stamp/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | يحصل أو يعيّن قيمة BlendingColorSpace التي تحدد مساحة اللون المستخدمة لإجراء عمليات الشفافية والدمج على الصفحة. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | يحصل أو يعيّن حالة الخلفية. إذا كانت true سيتم وضع الطابع كخلفية للصفحة المختومة. بشكل افتراضي يتم تعيينها إلى false. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | يحصل أو يعيّن شفافية الطابع. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | يحصل أو يعيّن رقم الصفحة. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | يحصل أو يعيّن مصفوفة بأرقام الصفحات التي سيتأثر بها الطابع. إذا كان Pages = null فإن جميع صفحات المستند ستتأثر. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | يحصل أو يعيّن جودة طابع الصورة بالنسبة المئوية. القيم المقبولة 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | يحصل أو يعيّن دوران الطابع بالدرجات. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | يحصل أو يعيّن معرف الطابع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | يعيّن الصورة التي ستُستخدم كطابع. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | يعيّن الصورة كطابع. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | يعيّن النص كطابع. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | يعيّن ملف PDF ورقم الصفحة التي ستُستخدم كطابع. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | يعيّن ملف PDF ورقم الصفحة التي ستُستخدم كطابع. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | يعيّن حالة نص الطابع. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | يعيّن حجم طابع الصورة. سيتم تحجيم الصورة وفق القيم المحددة. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | يعيّن الموقع على الصفحة حيث سيتم وضع الطابع. |

### انظر أيضًا

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


