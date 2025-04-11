---
title: Enum TextEditOptions.ClippingPathsProcessingMode
second_title: Aspose.PDF for .NET API Reference
description: Enum TextEditOptionsClippingPathsProcessingMode от Aspose.Pdf.Text. Режимы обработки обрезных путей
type: docs
weight: 10830
url: /ru/net/aspose.pdf.text/texteditoptions.clippingpathsprocessingmode/
---
## Перечисление TextEditOptions.ClippingPathsProcessingMode

Режимы обработки обрезных путей

```csharp
public enum ClippingPathsProcessingMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| KeepIntact | `0` | Сохраняет обрезные пути оригинальной компоновки страницы. (По умолчанию) |
| Expand | `1` | Оригинальный обрезной путь будет расширен в случае, если отредактированный текст требует больше места. |
| Remove | `2` | Оригинальный обрезной путь будет удален в случае, если отредактированный текст требует больше места. Осторожно: из-за того, что обрезные пути могут взаимодействовать друг с другом, их удаление может привести к неожиданным результатам в компоновке страницы. |

### См. также

* класс [TextEditOptions](../texteditoptions/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)