---
title: PdfAnnotationEditor.DeleteAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Удаляет все аннотации в документе
type: docs
weight: 30
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

Удаляет все аннотации в документе.

```csharp
public void DeleteAnnotations()
```

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

Удаляет все аннотации указанного типа в документе.

```csharp
public void DeleteAnnotations(string annotType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotType | String | Тип аннотации, который будет удален. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)