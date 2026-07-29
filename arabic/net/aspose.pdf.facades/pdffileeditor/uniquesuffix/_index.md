---
title: "PdfFileEditor.UniqueSuffix"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية PdfFileEditor. تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج. يجب أن تحتوي هذه السلسلة على الجزء الفرعي NUM الذي سيُستبدل بالأرقام. على سبيل المثال إذا كان UniqueSuffix هو ABCNUM، فستكون أسماء الحقول مثل fieldNameABC1 و fieldNameABC2 و fieldNameABC3 إلخ."
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

تنسيق اللاحقة التي تُضاف إلى اسم الحقل لجعله فريدًا عند دمج النماذج. يجب أن يحتوي هذا النص على الجزء %NUM% الذي سيُستبدل بالأرقام. على سبيل المثال إذا كان UniqueSuffix = "ABC%NUM%" فإن أسماء الحقول "fieldName" ستكون: fieldNameABC1، fieldNameABC2، fieldNameABC3، إلخ.

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


