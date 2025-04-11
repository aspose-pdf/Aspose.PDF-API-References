---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.ThreadResponse. Представляет поток, который содержит сообщения
type: docs
weight: 1180
url: /ru/net/aspose.pdf.ai/threadresponse/
---
## Класс ThreadResponse

Представляет поток, который содержит сообщения.

```csharp
public class ThreadResponse : BaseResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThreadResponse](threadresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Получает или задает метку времени Unix (в секундах) для момента создания потока. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP-ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP-ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Получает или задает идентификатор, который можно использовать в конечных точках API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар "ключ-значение", которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут иметь длину до 64 символов, а значения — до 512 символов. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда является потоком. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Получает или задает набор ресурсов, которые доступны инструментам помощника в этом потоке. Ресурсы специфичны для типа инструмента. Например, инструмент code_interpreter требует список идентификаторов файлов, в то время как инструмент file_search требует список идентификаторов векторного хранилища. |

### См. также

* класс [BaseResponse](../baseresponse/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)