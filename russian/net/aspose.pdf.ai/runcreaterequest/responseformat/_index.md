---
title: RunCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: Свойство RunCreateRequest. Получает или задает формат ответа. Указывает формат, который модель должна выводить. Совместимо с GPT-4o, GPT-4 Turbo и всеми моделями GPT-3.5 Turbo с gpt-3.5turbo1106. Установка типа "type" "json_object" включает режим JSON, который гарантирует, что сообщение, генерируемое моделью, является допустимым JSON. Важно при использовании режима JSON вы также должны указать модели самостоятельно генерировать JSON через системное или пользовательское сообщение. Без этого модель может генерировать бесконечный поток пробелов, пока генерация не достигнет предела токенов, что приведет к длительному и, казалось бы, "застрявшему" запросу. Также обратите внимание, что содержимое сообщения может быть частично обрезано, если finish_reason="length", что указывает на то, что генерация превысила max_tokens или разговор превысил максимальную длину контекста.
type: docs
weight: 100
url: /ru/net/aspose.pdf.ai/runcreaterequest/responseformat/
---
## Свойство RunCreateRequest.ResponseFormat

Получает или задает формат ответа. Указывает формат, который модель должна выводить. Совместимо с GPT-4o, GPT-4 Turbo и всеми моделями GPT-3.5 Turbo с gpt-3.5-turbo-1106. Установка типа { "type": "json_object" } включает режим JSON, который гарантирует, что сообщение, генерируемое моделью, является допустимым JSON. Важно: при использовании режима JSON вы также должны указать модели самостоятельно генерировать JSON через системное или пользовательское сообщение. Без этого модель может генерировать бесконечный поток пробелов, пока генерация не достигнет предела токенов, что приведет к длительному и, казалось бы, "застрявшему" запросу. Также обратите внимание, что содержимое сообщения может быть частично обрезано, если finish_reason="length", что указывает на то, что генерация превысила max_tokens или разговор превысил максимальную длину контекста.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### См. также

* класс [ResponseFormat](../../responseformat/)
* класс [RunCreateRequest](../)
* пространство имен [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../../)