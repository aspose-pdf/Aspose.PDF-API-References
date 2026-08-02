---
title: "PdfContentEditor.CreatePolygon"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Создаёт полигональную аннотацию"
type: docs
weight: 230
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## PdfContentEditor.CreatePolygon method

Создаёт полигональную аннотацию.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| lineInfo | LineInfo | Экземпляр класса LineInfo. |
| страница | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
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

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


