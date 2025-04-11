---
title: PdfContentEditor.CreatePolygon
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает аннотацию в виде полигона
type: docs
weight: 230
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## Метод PdfContentEditor.CreatePolygon

Создает аннотацию в виде полигона.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| lineInfo | LineInfo | Экземпляр класса LineInfo. |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| annotContents | String | Содержимое аннотации. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### См. также

* класс [LineInfo](../../lineinfo/)
* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)