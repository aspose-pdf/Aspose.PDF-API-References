---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает аннотацию квадрат-круг
type: docs
weight: 280
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## Метод PdfContentEditor.CreateSquareCircle

Создает аннотацию квадрат-круг.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| clr | Color | Цвет квадрата или круга. |
| square | Boolean | True (квадрат), false (круг). |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| borderWidth | Int32 | Ширина границы квадрата или круга. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)