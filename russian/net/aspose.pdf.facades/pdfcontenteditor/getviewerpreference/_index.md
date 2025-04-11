---
title: PdfContentEditor.GetViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Возвращает предпочтение просмотра
type: docs
weight: 390
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## Метод PdfContentEditor.GetViewerPreference

Возвращает предпочтение просмотра.

```csharp
public int GetViewerPreference()
```

### Возвращаемое значение

Возвращает набор флагов ViewerPrefernece

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)