---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает аннотацию линии
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## Метод PdfContentEditor.CreateLine

Создает аннотацию линии.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| x1 | Single | Начальная горизонтальная координата линии. |
| y1 | Single | Начальная вертикальная координата линии. |
| x2 | Single | Конечная горизонтальная координата линии. |
| y2 | Single | Конечная вертикальная координата линии. |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| border | Int32 | Ширина границы в пунктах. Если это значение равно 0, граница не рисуется. Значение по умолчанию - 1. |
| clr | Color | Цвет линии. |
| borderStyle | String | Стиль границы, определяющий ширину и шаблон штрихов, которые будут использоваться при рисовании линии. Это значение может быть: "S" (Сплошная), "D" (Пунктирная), "B" (Скошенная), "I" (Вставленная), "U" (Подчеркивание). |
| dashArray | Int32[] | Массив штрихов, определяющий шаблон штрихов и пробелов, который будет использоваться при рисовании пунктирной границы. Если он используется, borderSyle должен быть соответственно установлен на "D". |
| LEArray | String[] | Массив из двух значений, соответственно определяющих начальный и конечный стиль рисуемой линии. Значения могут быть: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)