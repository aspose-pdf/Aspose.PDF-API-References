---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Удаляет указанные изображения на указанной странице
type: docs
weight: 320
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

Удаляет указанные изображения на указанной странице.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы, на которой изображения должны быть удалены. |
| index | Int32[] | Массив, представляющий индексы изображений. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

Удаляет все изображения из PDF документа.

```csharp
public void DeleteImage()
```

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)