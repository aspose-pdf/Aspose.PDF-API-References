---
title: "Класс AssistantResponse"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.AI.AssistantResponse class. Представляет ассистента, который может вызывать модель и использовать инструменты."
type: docs
weight: 140
url: /ru/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse class

Представляет ассистента, который может вызывать модель и использовать инструменты.

```csharp
public class AssistantResponse : BaseResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Получает или задаёт Unix‑временную метку (в секундах) момента создания ассистента. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Получает или задает описание помощника. Максимальная длина — 512 символов. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP‑ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP‑ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Получает или задает идентификатор, который может использоваться в конечных точках API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Получает или задает системные инструкции, которые использует помощник. Максимальная длина — 256 000 символов. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар «ключ‑значение», которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут быть длиной до 64 символов, а значения — до 512 символов. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Получает или задаёт идентификатор модели для использования. Вы можете использовать API List models, чтобы увидеть все доступные модели, или просмотреть наш обзор моделей для их описаний. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Получает или задает имя помощника. Максимальная длина — 256 символов. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Получает или задаёт тип объекта, который всегда равен assistant. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Получает или задает формат, который модель должна выводить. Совместим с GPT-4o, GPT-4 Turbo и всеми моделями GPT-3.5 Turbo, начиная с gpt-3.5-turbo-1106. Установка значения { \"type\": \"json_object\" } включает режим JSON, который гарантирует, что сообщение, генерируемое моделью, является корректным JSON. Важно: при использовании режима JSON вы также должны инструктировать модель генерировать JSON самостоятельно через системное или пользовательское сообщение. Без этого модель может генерировать бесконечный поток пробелов, пока генерация не достигнет лимита токенов, что приводит к длительному и, казалось бы, \"застрявшему\" запросу. Также обратите внимание, что содержимое сообщения может быть частично обрезано, если finish_reason=\"length\", что указывает на превышение max_tokens или превышение максимальной длины контекста разговора. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Получает или задает температуру выборки, используемую в диапазоне от 0 до 2. Более высокие значения, такие как 0.8, делают вывод более случайным, тогда как более низкие значения, например 0.2, делают его более сфокусированным и детерминированным. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Получает или задаёт набор ресурсов, используемых инструментами ассистента. Ресурсы специфичны для типа инструмента. Например, инструмент code_interpreter требует список идентификаторов файлов, тогда как инструмент file_search требует список идентификаторов векторных хранилищ. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Получает или задает список включенных инструментов у помощника. Максимальное количество инструментов на одного помощника — 128. Инструменты могут быть типов code_interpreter, file_search или function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Получает или задает альтернативу выборке с температурой, называемую ядерной выборкой, при которой модель учитывает токены с массой вероятности top_p. Таким образом, 0.1 означает, что учитываются только токены, составляющие верхние 10 % вероятности. Как правило, мы рекомендуем изменять либо это значение, либо температуру, но не оба одновременно. |

### См. также

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


