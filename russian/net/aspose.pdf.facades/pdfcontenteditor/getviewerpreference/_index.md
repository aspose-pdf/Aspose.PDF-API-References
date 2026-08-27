---
title: "PdfContentEditor.GetViewerPreference"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Возвращает предпочтение просмотра"
type: docs
weight: 390
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


