---
title: "PdfPageEditor.MovePosition"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfPageEditor. Перемещает начало координат от 0 0 к указанной точке. Начало находится в левом нижнем углу, единица измерения — пункт (1 дюйм = 72 пункта)"
type: docs
weight: 170
url: /ru/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

Перемещает начало координат из (0, 0) в указанную точку. Начало координат находится в левом нижнем углу, единица измерения — пункт (1 дюйм = 72 пункта).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| moveX | Single | Координата X. |
| moveY | Single | Координата Y. |

## Примеры

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### См. также

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


