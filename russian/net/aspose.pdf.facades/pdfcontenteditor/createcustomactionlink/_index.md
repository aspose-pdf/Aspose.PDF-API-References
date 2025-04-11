---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Создает ссылку на пользовательские действия в PDF документе
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## Метод PdfContentEditor.CreateCustomActionLink

Создает ссылку на пользовательские действия в PDF документе.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник для активного клика. |
| originalPage | Int32 | Номер оригинальной страницы, на которой будет создан прямоугольник, связанный со ссылкой. |
| color | Color | Цвет прямоугольника для активного клика. |
| actionName | Enum[] | Массив действий (члены перечисления PredefinedAction), соответствующий выполняемым элементам меню в просмотрщике Acrobat. |

## Примеры

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)