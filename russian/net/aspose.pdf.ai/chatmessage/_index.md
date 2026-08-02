---
title: "Класс ChatMessage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.ChatMessage. Сообщение завершения чата, сгенерированное моделью"
type: docs
weight: 190
url: /ru/net/aspose.pdf.ai/chatmessage/
---
## ChatMessage class

Сообщение завершения чата, сгенерированное моделью.

```csharp
public class ChatMessage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | Инициализирует новый экземпляр класса `ChatMessage`. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | Инициализирует новый экземпляр класса `ChatMessage`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Получает или задаёт содержимое сообщения. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Получает или задаёт необязательное имя участника. Предоставляет модели информацию для различения участников с одинаковой ролью. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Получает или задаёт роль автора сообщения. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Получает или задаёт вызов инструмента, на который отвечает это сообщение. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Получает или задаёт вызовы инструментов, сгенерированные моделью, например вызовы функций. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Создаёт новый объект ChatMessage, представляющий сообщение помощника. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Создает новый объект ChatMessage, представляющий системное сообщение. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Создает новый объект ChatMessage, представляющий сообщение пользователя. |

### См. также

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


