---
title: Class ComHelper
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.ComHelper. توفر طرقًا لعملاء COM لتحميل مستند إلى Aspose.Pdf
type: docs
weight: 3130
url: /ar/net/aspose.pdf/comhelper/
---
## ComHelper class

توفر طرقًا لعملاء COM لتحميل مستند إلى Aspose.Pdf.

```csharp
public class ComHelper
```

## Constructors

| Name | Description |
| --- | --- |
| [ComHelper](comhelper/)() | المُنشئ الافتراضي. |

## Methods

| Name | Description |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile)(string) | فقط قم بإنشاء وإرجاع مستند باستخدام *filename*. نفس الشيء مثل [`Document`](../document/document/). |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_1)(string, LoadOptions) | افتح مستندًا موجودًا من ملف مع توفير خيارات التحويل اللازمة للحصول على مستند PDF. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_2)(string, string) | قم بتهيئة وإرجاع مثيل جديد من فئة [`Document`](../document/) للعمل مع مستند مشفر. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_3)(string, string, bool) | قم بتهيئة مثيل جديد من فئة [`Document`](../document/) للعمل مع مستند مشفر. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream)(Stream) | قم بتهيئة وإرجاع مثيل جديد من المستند من *input* stream. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_2)(Stream, bool) | قم بتهيئة وإرجاع مثيل جديد من المستند من *input* stream. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_1)(Stream, LoadOptions) | افتح وأرجع مستندًا موجودًا من stream مع توفير التحويل اللازم للحصول على مستند PDF. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_3)(Stream, string) | قم بتهيئة وإرجاع مثيل جديد من المستند من *input* stream. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_4)(Stream, string, bool) | قم بتهيئة وإرجاع مثيل جديد من المستند من *input* stream. |

## Remarks

استخدم فئة ComHelper لتحميل مستند من ملف أو stream إلى كائن Document في تطبيق COM. توفر فئة Document مُنشئًا افتراضيًا لإنشاء مستند جديد وتوفر أيضًا مُنشئات مُحمّلة لتحميل مستند من ملف أو stream. إذا كنت تستخدم Aspose.Words من تطبيق .NET، يمكنك استخدام جميع مُنشئات Document مباشرة، ولكن إذا كنت تستخدم Aspose.Pdf من تطبيق COM، فإن مُنشئ Document الافتراضي فقط هو المتاح.

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)