---
title: "PdfContentEditor.GetViewerPreference"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تُرجع تفضيل العرض"
type: docs
weight: 390
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

يرجع تفضيل العرض.

```csharp
public int GetViewerPreference()
```

### قيمة الإرجاع

إرجاع مجموعة من أعلام ViewerPrefernece

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


