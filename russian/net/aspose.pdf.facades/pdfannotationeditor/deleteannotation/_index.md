---
title: DeleteAnnotation
second_title: Aspose.PDF для справочника API .NET
description: Удаляет аннотацию с указанным именем аннотации.
type: docs
weight: 20
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation method

Удаляет аннотацию с указанным именем аннотации.

```csharp
public void DeleteAnnotation(string annotName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotName | String | Имя аннотации |

### Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Смотрите также

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfannotationeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->