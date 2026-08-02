---
title: "Класс LlamaChatCompletionResponse"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.AI.LlamaChatCompletionResponse класс. Представляет ответ завершения чата, возвращаемый моделью на основе предоставленного ввода."
type: docs
weight: 740
url: /ru/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## LlamaChatCompletionResponse class

Представляет ответ завершения чата, возвращённый моделью, на основе предоставленного ввода.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | Получает или задает список вариантов завершения чата. Может быть более одного, если n больше 1. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | Получает или задает Unix‑временную метку (в секундах) момента создания завершения чата. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP‑ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP‑ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | Получает или задает уникальный идентификатор для завершения чата. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | Получает или задает модель, используемую для завершения чата. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | Получает или задает отпечаток, представляющий конфигурацию бекенда, с которой работает модель. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | Получает или задает статистику использования для запроса завершения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | Возвращает строковое представление первого варианта. |

### См. также

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


