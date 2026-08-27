---
title: "PdfFileEditor.SplitToBulks"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileEditor. تقسم ملف PDF إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات."
type: docs
weight: 350
url: /ar/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

يقسم ملف Pdf إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFile | String | ملف PDF الإدخال. |
| numberOfPage | Int32[][] | مصفوفة تحتوي على مصفوفة من عناصر مزدوجة، تمثل الصفحات البداية والنهاية للمستند. |

### قيمة الإرجاع

تدفقات PDF الناتجة، كل تدفق يخزن مؤقتًا مستند PDF.

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

يقسم ملف Pdf إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق PDF الإدخال. |
| numberOfPage | Int32[][] | صفحة البداية والصفحة النهاية لكل مستند. |

### قيمة الإرجاع

تدفقات PDF الناتجة، كل تدفق يخزن مؤقتًا مستند PDF.

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


