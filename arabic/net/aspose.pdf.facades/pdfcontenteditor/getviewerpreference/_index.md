---
title: PdfContentEditor.GetViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تعيد تفضيل العرض
type: docs
weight: 390
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## طريقة PdfContentEditor.GetViewerPreference

تعيد تفضيل العرض.

```csharp
public int GetViewerPreference()
```

### قيمة الإرجاع

تعيد مجموعة من علامات ViewerPrefernece

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