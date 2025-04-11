---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Удаляет аннотацию с указанным именем аннотации
type: docs
weight: 20
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## Метод PdfAnnotationEditor.DeleteAnnotation

Удаляет аннотацию с указанным именем аннотации.

```csharp
public void DeleteAnnotation(string annotName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotName | String | Имя аннотации |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)