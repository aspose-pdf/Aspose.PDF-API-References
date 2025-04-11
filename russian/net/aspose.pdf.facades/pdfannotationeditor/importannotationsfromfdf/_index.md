---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Импортирует все аннотации из FDF файла
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## Метод PdfAnnotationEditor.ImportAnnotationsFromFdf

Импортирует все аннотации из FDF файла.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fdfFile | String | Входной FDF файл. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)