---
title: "Класс CreateEmbeddingRequest"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.CreateEmbeddingRequest. Представляет запрос к конечной точке Create Embeddings."
type: docs
weight: 270
url: /ru/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

Представляет запрос к конечной точке Create Embeddings.

```csharp
public class CreateEmbeddingRequest
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Получает или задает количество измерений, которые должны иметь полученные выходные эмбеддинги. Поддерживается только в моделях text-embedding-3 и более поздних. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Получает или задает формат, в котором возвращаются эмбеддинги. Может быть либо float, либо base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Получает или задает входной текст для встраивания, закодированный как строка или массив токенов. Чтобы встроить несколько входов в одном запросе, передайте массив строк или массив массивов токенов. Ввод не должен превышать максимальное количество токенов для модели (8192 токена для text-embedding-ada-002), не может быть пустой строкой, и любой массив должен иметь 2048 измерений или меньше. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Получает или задает модель, для которой генерируется эмбеддинг. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Получает или задает уникальный идентификатор, представляющий вашего конечного пользователя, который может помочь OpenAI отслеживать и выявлять злоупотребления. |

### См. также

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


