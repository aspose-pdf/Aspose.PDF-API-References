---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تغير تفضيل العرض
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## طريقة PdfContentEditor.ChangeViewerPreference

تغير تفضيل العرض.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| viewerAttribution | Int32 | نسبة العرض المحددة في فئة ViewerPreference. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* فئة [PdfContentEditor](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)