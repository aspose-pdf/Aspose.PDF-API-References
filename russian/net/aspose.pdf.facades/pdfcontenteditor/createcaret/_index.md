---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает аннотацию курсора
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## Метод PdfContentEditor.CreateCaret

Создает аннотацию курсора.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | Rectangle | Прямоугольник аннотации, определяющий местоположение аннотации на странице. |
| caretRect | Rectangle | Фактические границы подлежащего курсора. |
| symbol | String | Символ, который будет ассоциирован с курсором. Значение может быть: "P" (Параграф), "None". |
| annotContents | String | Содержимое аннотации. |
| color | Color | Цвет аннотации. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)