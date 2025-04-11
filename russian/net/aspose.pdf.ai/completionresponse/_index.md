---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.CompletionResponse. Представляет собой ответ на завершение чата, возвращаемый моделью на основе предоставленного ввода
type: docs
weight: 240
url: /ru/net/aspose.pdf.ai/completionresponse/
---
## Класс CompletionResponse

Представляет собой ответ на завершение чата, возвращаемый моделью на основе предоставленного ввода.

```csharp
public class CompletionResponse : BaseResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CompletionResponse](completionresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Получает или задает список вариантов завершения чата. Может быть более одного, если n больше 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Получает или задает временную метку Unix (в секундах) времени создания завершения чата. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP-ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP-ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Получает или задает уникальный идентификатор для завершения чата. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Получает или задает модель, используемую для завершения чата. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда равен chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Получает или задает отпечаток, который представляет конфигурацию бэкенда, с которой работает модель. Может использоваться вместе с параметром запроса seed для понимания, когда были внесены изменения в бэкенд, которые могут повлиять на детерминизм. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Получает или задает статистику использования для запроса на завершение. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Возвращает содержимое первого варианта в виде строки. |

### Смотрите также

* класс [BaseResponse](../baseresponse/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)