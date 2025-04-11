---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.CreateEmbeddingRequest. Представляет запрос для конечной точки Создания Встраиваний
type: docs
weight: 260
url: /ru/net/aspose.pdf.ai/createembeddingrequest/
---
## Класс CreateEmbeddingRequest

Представляет запрос для конечной точки Создания Встраиваний.

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
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Получает или задает количество измерений, которые должны иметь результирующие встраивания. Поддерживается только в моделях text-embedding-3 и более поздних. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Получает или задает формат для возврата встраиваний. Может быть либо float, либо base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Получает или задает входной текст для встраивания, закодированный как строка или массив токенов. Чтобы встроить несколько входов в одном запросе, передайте массив строк или массив массивов токенов. Вход не должен превышать максимальное количество входных токенов для модели (8192 токена для text-embedding-ada-002), не может быть пустой строкой, и любой массив должен содержать 2048 измерений или меньше. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Получает или задает модель для генерации встраивания. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Получает или задает уникальный идентификатор, представляющий вашего конечного пользователя, который может помочь OpenAI отслеживать и обнаруживать злоупотребления. |

### См. также

* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)