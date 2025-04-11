---
title: Document.OpenAction
second_title: Aspose.PDF for .NET API Reference
description: Свойство документа. Получает или устанавливает действие, выполняемое при открытии документа
type: docs
weight: 390
url: /ru/net/aspose.pdf/document/openaction/
---
## Свойство Document.OpenAction

Получает или устанавливает действие, выполняемое при открытии документа.

```csharp
public IAppointment OpenAction { get; set; }
```

## Примеры

Пример демонстрирует, как получить флаг CenterWindow:

```csharp
Document document = new Document("sample.pdf");
IAppointment value = document.OpenAction;
```

### См. также

* интерфейс [IAppointment](../../../aspose.pdf.annotations/iappointment/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)