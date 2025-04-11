---
title: OpenAIImageDescriptionCopilotExtensions.AddPdfImageDescriptionsAsync
second_title: Aspose.PDF for .NET API Reference
description: Метод OpenAIImageDescriptionCopilotExtensions. Асинхронно добавляет описания изображений в PDF файл и сохраняет новые документы в указанные папки
type: docs
weight: 10
url: /ru/net/aspose.pdf.ai/openaiimagedescriptioncopilotextensions/addpdfimagedescriptionsasync/
---
## Метод OpenAIImageDescriptionCopilotExtensions.AddPdfImageDescriptionsAsync

Асинхронно добавляет описания изображений в PDF файл и сохраняет новые документы в указанные папки.

```csharp
public static Task AddPdfImageDescriptionsAsync(
    this IImageDescriptionCopilot imageDescriptionCopilot, string outputDirectory, 
    CancellationToken? cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageDescriptionCopilot | IImageDescriptionCopilot | Копилот описания изображения. |
| outputDirectory | String | Выходной каталог, в который будут сохранены выходные PDF файлы. |
| cancellationToken | Nullable`1 | Токен отмены (необязательно). |

### Возвращаемое значение

Задача, представляющая асинхронную операцию.

### См. также

* интерфейс [IImageDescriptionCopilot](../../iimagedescriptioncopilot/)
* класс [OpenAIImageDescriptionCopilotExtensions](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)