---
title: "PdfAnnotationEditor.ImportAnnotationsFromFdf"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfAnnotationEditor. Импортирует все аннотации из файла FDF"
type: docs
weight: 100
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf method

Импортирует все аннотации из файла FDF.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fdfFile | String | Входной файл FDF. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### См. также

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


