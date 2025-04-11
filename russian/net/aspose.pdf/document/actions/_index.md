---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: Свойство документа. Получает действия документа. Это свойство является экземпляром класса DocumentActions, который позволяет получать/устанавливать действия BeforClosing, BeforSaving и т.д.
type: docs
weight: 30
url: /ru/net/aspose.pdf/document/actions/
---
## Свойство Document.Actions

Получает действия документа. Это свойство является экземпляром класса DocumentActions, который позволяет получать/устанавливать действия BeforClosing, BeforSaving и т.д.

```csharp
public DocumentActionCollection Actions { get; }
```

## Примеры

Этот пример демонстрирует, как получить действие после открытия документа:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### См. также

* класс [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)