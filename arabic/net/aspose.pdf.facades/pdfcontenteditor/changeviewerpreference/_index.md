---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تغير تفضيل العرض"
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference method

يغيّر تفضيل العرض.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| viewerAttribution | Int32 | تعيين العرض المحدد في فئة ViewerPreference. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


