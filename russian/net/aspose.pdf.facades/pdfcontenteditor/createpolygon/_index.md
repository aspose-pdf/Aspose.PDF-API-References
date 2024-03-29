---
title: CreatePolygon
second_title: Aspose.PDF для справочника API .NET
description: Создает полигональную аннотацию.
type: docs
weight: 230
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## PdfContentEditor.CreatePolygon method

Создает полигональную аннотацию.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| lineInfo | LineInfo | Экземпляр класса LineInfo. |
| page | Int32 | Номер исходной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| annotContents | String | Содержание аннотации. |

### Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Смотрите также

* class [LineInfo](../../lineinfo)
* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
