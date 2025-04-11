---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.ChatMessage. Сообщение о завершении чата, сгенерированное моделью
type: docs
weight: 190
url: /ru/net/aspose.pdf.ai/chatmessage/
---
## Класс ChatMessage

Сообщение о завершении чата, сгенерированное моделью.

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
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Получает или задает содержимое сообщения. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Получает или задает необязательное имя участника. Предоставляет модели информацию для различения участников одной роли. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Получает или задает роль автора сообщений. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Получает или задает вызов инструмента, на который отвечает это сообщение. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Получает или задает вызовы инструментов, сгенерированные моделью, такие как вызовы функций. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Создает новый объект ChatMessage, представляющий сообщение помощника. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Создает новый объект ChatMessage, представляющий системное сообщение. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Создает новый объект ChatMessage, представляющий сообщение пользователя. |

### См. также

* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)