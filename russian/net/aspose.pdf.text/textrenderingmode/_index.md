---
title: Enum TextRenderingMode
second_title: Aspose.PDF for .NET API Reference
description: Enum TextRenderingMode Aspose.Pdf.Text. Режим рендеринга текста Tmode определяет, будет ли отображение текста вызывать обводку глифов, заполнение, использование в качестве границы обрезки или их комбинацию.
type: docs
weight: 11000
url: /ru/net/aspose.pdf.text/textrenderingmode/
---
## Перечисление TextRenderingMode

Режим рендеринга текста, Tmode, определяет, будет ли отображение текста вызывать обводку глифов, заполнение, использование в качестве границы обрезки или их комбинацию.

```csharp
public enum TextRenderingMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| FillText | `0` | Заполнить текст. |
| StrokeText | `1` | Обвести текст. |
| FillThenStrokeText | `2` | Сначала заполнить, затем обвести текст. |
| Invisible | `3` | Ни заполнение, ни обводка текста (невидимый). |
| FillTextAndAddPathToClipping | `4` | Заполнить текст и добавить в путь для обрезки (см. 9.3.6, "Режим рендеринга текста"). |
| StrokeTextAndAddPathToClipping | `5` | Обвести текст и добавить в путь для обрезки. |
| FillThenStrokeTextAndAddPathToClipping | `6` | Сначала заполнить, затем обвести текст и добавить в путь для обрезки. |
| AddPathToClipping | `7` | Добавить текст в путь для обрезки. |

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)