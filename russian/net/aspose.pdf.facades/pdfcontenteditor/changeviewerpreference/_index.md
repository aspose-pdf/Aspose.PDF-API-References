---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Изменяет предпочтения просмотра."
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference method

Изменяет предпочтения просмотра.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| viewerAttribution | Int32 | Атрибуция просмотра, определённая в классе ViewerPreference. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


