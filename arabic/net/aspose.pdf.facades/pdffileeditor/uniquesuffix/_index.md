---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfFileEditor. تنسيق اللاحقة التي تضاف إلى اسم الحقل لجعلها فريدة عند دمج النماذج. يجب أن تحتوي هذه السلسلة على جزء فرعي NUM الذي سيتم استبداله بأرقام. على سبيل المثال، إذا كانت UniqueSuffix = ABCNUM، فإن أسماء الحقول fieldName ستكون fieldNameABC1، fieldNameABC2، fieldNameABC3، إلخ.
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## خاصية PdfFileEditor.UniqueSuffix

تنسيق اللاحقة التي تضاف إلى اسم الحقل لجعلها فريدة عند دمج النماذج. يجب أن تحتوي هذه السلسلة على جزء فرعي %NUM% الذي سيتم استبداله بأرقام. على سبيل المثال، إذا كانت UniqueSuffix = "ABC%NUM%"، فإن أسماء الحقل "fieldName" ستكون: fieldNameABC1، fieldNameABC2، fieldNameABC3، إلخ.

```csharp
public string UniqueSuffix { get; set; }
```

## أمثلة

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### انظر أيضًا

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)