---
title: "Класс CreateChatCompletionChunkResponse"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.CreateChatCompletionChunkResponse. Представляет потоковый фрагмент ответа завершения чата, возвращаемый моделью на основе предоставленного ввода."
type: docs
weight: 260
url: /ru/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

Представляет потоковый фрагмент ответа завершения чата, возвращённого моделью, на основе предоставленного ввода.

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
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Получает или задаёт список вариантов завершения чата. Может содержать более одного элемента, если n больше 1. Также может быть пустым для последнего фрагмента, если установить stream_options: {\"include_usage\": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Получает или задаёт Unix‑временную метку (в секундах) создания завершения чата. Каждый фрагмент имеет одинаковую метку времени. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Получает или задаёт уникальный идентификатор завершения чата. Каждый фрагмент имеет тот же ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Получает или задаёт модель для генерации завершения. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Получает или задаёт тип объекта, который всегда равен chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Получает или задает отпечаток, представляющий конфигурацию бэкенда, с которой работает модель. Может использоваться вместе с параметром seed запроса, чтобы понять, когда были внесены изменения в бэкенд, которые могут повлиять на детерминированность. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Получает или задает необязательное поле, которое будет присутствовать только при установке stream_options: {\"include_usage\": true} в вашем запросе. Когда присутствует, оно содержит значение null, за исключением последнего фрагмента, который содержит статистику использования токенов для всего запроса. |

### См. также

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


