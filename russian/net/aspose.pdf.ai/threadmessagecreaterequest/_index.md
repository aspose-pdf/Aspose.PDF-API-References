---
title: "Класс ThreadMessageCreateRequest"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.ThreadMessageCreateRequest. Представляет запрос на создание сообщения в рамках потока"
type: docs
weight: 1210
url: /ru/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## ThreadMessageCreateRequest class

Представляет запрос на создание сообщения в ветке.

```csharp
public class ThreadMessageCreateRequest
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Получает или задает список файлов, прикреплённых к сообщению. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Получает или задает содержимое сообщения. Может быть строкой или массивом частей содержимого. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Получает или задает набор из 16 пар «ключ‑значение», которые могут быть прикреплены к объекту. Это может быть полезно для хранения дополнительной информации об объекте в структурированном формате. Ключи могут быть длиной до 64 символов, а значения — до 512 символов. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Получает или задает роль сущности, создающей сообщение. Допустимые значения включают: "user", "assistant". |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Создаёт новый `ThreadMessageCreateRequest` с ролью, установленной в Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Создаёт новый `ThreadMessageCreateRequest` с ролью, установленной в User. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Устанавливает вложения для запроса сообщения потока. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Добавляет содержимое сообщения в запрос сообщения потока. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Устанавливает содержимое сообщения для запроса сообщения потока. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Устанавливает метаданные для запроса сообщения потока. |

### См. также

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


