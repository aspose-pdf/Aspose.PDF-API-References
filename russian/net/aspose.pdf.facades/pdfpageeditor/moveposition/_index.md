---
title: MovePosition
second_title: Aspose.PDF для справочника API .NET
description: Перемещает начало координат из 0 0 в назначенную точку. Исходная точка находится слева внизу а единицей измерения является точка 1 дюйм  72 точки.
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

Перемещает начало координат из (0, 0) в назначенную точку. Исходная точка находится слева внизу, а единицей измерения является точка (1 дюйм = 72 точки).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| moveX | Single | X-координата. |
| moveY | Single | Y-координата. |

### Примеры

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Смотрите также

* class [PdfPageEditor](../../pdfpageeditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfpageeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->