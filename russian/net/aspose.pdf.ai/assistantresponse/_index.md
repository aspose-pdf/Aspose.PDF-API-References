---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.AssistantResponse. Представляет собой помощника, который может вызывать модель и использовать инструменты
type: docs
weight: 140
url: /ru/net/aspose.pdf.ai/assistantresponse/
---
## Класс AssistantResponse

Представляет собой помощника, который может вызывать модель и использовать инструменты.

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
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Получает или задает временную метку Unix (в секундах) для момента создания помощника. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Получает или задает описание помощника. Максимальная длина - 512 символов. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Получает или задает детали ответа. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Получает или задает ошибку HTTP-ответа. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Получает или задает информацию об ошибке. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Получает или задает заголовки HTTP-ответа. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Получает или задает код состояния HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Получает или задает идентификатор, который можно использовать в конечных точках API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Получает или задает системные инструкции, которые использует помощник. Максимальная длина - 256,000 символов. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Указывает, был ли ответ успешным. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Получает или задает набор из 16 пар "ключ-значение", которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут иметь максимальную длину 64 символа, а значения - максимальную длину 512 символов. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Получает или задает идентификатор модели, которую нужно использовать. Вы можете использовать API для получения списка моделей, чтобы увидеть все доступные модели, или ознакомиться с нашим обзором моделей для их описаний. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Получает или задает имя помощника. Максимальная длина - 256 символов. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Получает или задает тип объекта, который всегда является помощником. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Получает фразу причины ошибки. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Получает или задает формат, который модель должна выводить. Совместим с GPT-4o, GPT-4 Turbo и всеми моделями GPT-3.5 Turbo начиная с gpt-3.5-turbo-1106. Установка { "type": "json_object" } включает режим JSON, который гарантирует, что сообщение, генерируемое моделью, является допустимым JSON. Важно: при использовании режима JSON вы также должны указать модели, чтобы она сама генерировала JSON через системное или пользовательское сообщение. Без этого модель может генерировать бесконечный поток пробелов, пока генерация не достигнет предела токенов, что приведет к длительному и, казалось бы, "застрявшему" запросу. Также обратите внимание, что содержимое сообщения может быть частично обрезано, если finish_reason="length", что указывает на то, что генерация превысила max_tokens или разговор превысил максимальную длину контекста. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Получает или задает, какую температуру выборки использовать, от 0 до 2. Более высокие значения, такие как 0.8, сделают вывод более случайным, в то время как более низкие значения, такие как 0.2, сделают его более сосредоточенным и детерминированным. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Получает или задает набор ресурсов, которые используются инструментами помощника. Ресурсы специфичны для типа инструмента. Например, инструмент code_interpreter требует список идентификаторов файлов, в то время как инструмент file_search требует список идентификаторов векторного хранилища. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Получает или задает список инструментов, включенных в помощника. Максимальное количество инструментов на одного помощника - 128. Инструменты могут быть типов code_interpreter, file_search или function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Получает или задает альтернативу выборке с температурой, называемую выборкой по ядру, где модель учитывает результаты токенов с вероятностной массой top_p. Таким образом, 0.1 означает, что учитываются только токены, составляющие верхние 10% вероятностной массы. Мы обычно рекомендуем изменять это или температуру, но не оба. |

### См. также

* класс [BaseResponse](../baseresponse/)
* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)