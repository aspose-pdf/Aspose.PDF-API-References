---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.CreateChatCompletionChunkResponse. Представляет собой потоковый фрагмент ответа на завершение чата, возвращаемый моделью на основе предоставленного ввода
type: docs
weight: 250
url: /ru/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## Класс CreateChatCompletionChunkResponse

Представляет собой потоковый фрагмент ответа на завершение чата, возвращаемый моделью на основе предоставленного ввода.

```csharp
public class CreateChatCompletionChunkResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Получает или задает список вариантов завершения чата. Может содержать более одного элемента, если n больше 1. Также может быть пустым для последнего фрагмента, если вы установите stream_options: {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Получает или задает временную метку Unix (в секундах) времени создания завершения чата. Каждый фрагмент имеет одинаковую временную метку. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Получает или задает уникальный идентификатор для завершения чата. Каждый фрагмент имеет одинаковый ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Получает или задает модель для генерации завершения. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Получает или задает отпечаток, который представляет конфигурацию бэкенда, с которой работает модель. Может использоваться вместе с параметром запроса seed для понимания, когда были внесены изменения в бэкенд, которые могут повлиять на детерминизм. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Получает или задает необязательное поле, которое будет присутствовать только тогда, когда вы установите stream_options: {"include_usage": true} в вашем запросе. Когда оно присутствует, содержит значение null, за исключением последнего фрагмента, который содержит статистику использования токенов для всего запроса. |

### См. также

* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)