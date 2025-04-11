---
title: PdfAnnotationEditor.ImportAnnotationsFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfAnnotationEditor. Импортирует все аннотации из файла XFDF
type: docs
weight: 110
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

Импортирует все аннотации из файла XFDF.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfFile | String | Входной файл XFDF. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

Импортирует все аннотации из потока данных XFDF.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xfdfStream | Stream | Входной поток данных XFDF. |

## Примеры

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfAnnotationEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)