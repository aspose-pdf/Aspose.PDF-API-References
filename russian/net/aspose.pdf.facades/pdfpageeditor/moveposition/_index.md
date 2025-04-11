---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfPageEditor. Перемещает начало координат из (0, 0) в указанную точку. Начало координат находится в левом нижнем углу, а единица измерения - пункт (1 дюйм = 72 пункта).
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## Метод PdfPageEditor.MovePosition

Перемещает начало координат из (0, 0) в указанную точку. Начало координат находится в левом нижнем углу, а единица измерения - пункт (1 дюйм = 72 пункта).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| moveX | Single | X-координата. |
| moveY | Single | Y-координата. |

## Примеры

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### См. также

* класс [PdfPageEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)