---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileEditor. تقسم ملف Pdf إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات
type: docs
weight: 350
url: /ar/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

تقسم ملف Pdf إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | ملف PDF المدخل. |
| numberOfPage | Int32[][] | مصفوفة تحتوي على مصفوفة من العناصر المزدوجة، والتي هي صفحات البداية والنهاية للمستند. |

### Return Value

تيارات PDF الناتجة، كل تيار يخزن مستند PDF.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

تقسم ملف Pdf إلى عدة مستندات. يمكن أن تكون المستندات صفحة واحدة أو متعددة الصفحات.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تيار PDF المدخل. |
| numberOfPage | Int32[][] | صفحة البداية وصفحة النهاية لكل مستند. |

### Return Value

تيارات PDF الناتجة، كل تيار يخزن مستند PDF.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)