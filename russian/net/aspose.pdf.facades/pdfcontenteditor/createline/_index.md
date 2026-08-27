---
title: "PdfContentEditor.CreateLine"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Создает аннотацию линии"
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

Создаёт линейную аннотацию.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| x1 | Single | Начальная горизонтальная координата линии. |
| y1 | Single | Начальная вертикальная координата линии. |
| x2 | Single | Конечная горизонтальная координата линии. |
| y2 | Single | Конечная вертикальная координата линии. |
| страница | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| border | Int32 | Ширина границы в пунктах. Если это значение равно 0, граница не рисуется. Значение по умолчанию — 1. |
| clr | Color | Цвет линии. |
| borderStyle | String | Стиль границы, определяющий ширину и шаблон штриховки, используемые при рисовании линии. Это значение может быть: \"S\" (сплошной), \"D\" (пунктирный), \"B\" (скошенный), \"I\" (внутренний), \"U\" (подчёркнутый). |
| dashArray | Int32[] | Массив штрихов, определяющий шаблон пунктиров и пробелов, используемых при рисовании пунктирной границы. Если он используется, borderSyle должен быть соответственно установлен в \"D\". |
| LEArray | String[] | Массив из двух значений, соответственно определяющих начальный и конечный стиль рисуемой линии. Значения могут быть: \"Square\", \"Circle\", \"Diamond\", \"OpenArrow\", \"ClosedArrow\", \"None\", \"Butt\", \"ROpenArrow\", \"RClosedArrow\", \"Slash\". |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


