---
title: SplitToBulks
second_title: Aspose.PDF لمرجع .NET API
description: يقسم ملف Pdf إلى عدة مستندات  ويمكن أن تكون المستندات من صفحة واحدة أو متعددة الصفحات.
type: docs
weight: 380
url: /ar/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

يقسم ملف Pdf إلى عدة مستندات ، ويمكن أن تكون المستندات من صفحة واحدة أو متعددة الصفحات.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFile | String | إدخال ملف PDF. |
| numberOfPage | Int32[][] | مصفوفة تحتوي على مصفوفة من العناصر المزدوجة ، وهي صفحات البداية والنهاية للمستند. |

### قيمة الإرجاع

تدفقات إخراج PDF ، يقوم كل دفق بتخزين مستند PDF مؤقتًا.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

يقسم ملف Pdf إلى عدة مستندات ، ويمكن أن تكون المستندات من صفحة واحدة أو متعددة الصفحات.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | إدخال دفق PDF. |
| numberOfPage | Int32[][] | صفحة البداية وصفحة النهاية لكل مستند. |

### قيمة الإرجاع

تدفقات إخراج PDF ، يقوم كل دفق بتخزين مستند PDF مؤقتًا.

### أنظر أيضا

* class [PdfFileEditor](../../pdffileeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffileeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->