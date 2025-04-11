---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает аннотацию разметки в PDF документе
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## Метод PdfContentEditor.CreateMarkup

Создает аннотацию разметки в PDF документе.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник, определяющий местоположение аннотации на странице. |
| contents | String | Содержимое аннотации. |
| type | Int32 | Тип аннотации разметки. Может быть 0 (Выделение), 1 (Подчеркивание), 2 (Зачеркивание), 3 (Кривое). |
| page | Int32 | Номер оригинальной страницы, на которой будет создана аннотация. |
| clr | Color | Цвет разметки. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)