---
title: "PdfContentEditor.DeleteImage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Удаляет указанные изображения на указанной странице."
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
| pageNumber | Int32 | Номер страницы, на которой необходимо удалить изображения. |
| index | Int32[] | Массив, представляющий индексы изображений. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

Удаляет все изображения из PDF‑документа.

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


