---
title: "PdfContentEditor.CreateCustomActionLink"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Создаёт ссылку на пользовательские действия в PDF‑документе."
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink method

Создаёт ссылку на пользовательские действия в PDF‑документе.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Rectangle | Прямоугольник для активного клика. |
| originalPage | Int32 | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к ссылке. |
| color | Color | Цвет прямоугольника для активного клика. |
| actionName | Enum[] | Массив действий (члены перечисления PredefinedAction), соответствующих выполнению пунктов меню в просмотрщике Acrobat. |

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


