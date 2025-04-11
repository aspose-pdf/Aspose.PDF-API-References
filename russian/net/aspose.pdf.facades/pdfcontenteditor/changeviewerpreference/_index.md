---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Изменяет предпочтение просмотра
type: docs
weight: 90
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## Метод PdfContentEditor.ChangeViewerPreference

Изменяет предпочтение просмотра.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| viewerAttribution | Int32 | Атрибуция просмотра, определенная в классе ViewerPreference. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)