---
title: PdfContentEditor.DrawCurve
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает аннотацию кривой
type: docs
weight: 360
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## Метод PdfContentEditor.DrawCurve

Создает аннотацию кривой.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### См. также

* класс [LineInfo](../../lineinfo/)
* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)