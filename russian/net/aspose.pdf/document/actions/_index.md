---
title: "Document.Actions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Document. Получает действия документа. Это свойство является экземпляром класса DocumentActions, который позволяет получать/устанавливать действия BeforClosing, BeforSaving и т.д."
type: docs
weight: 30
url: /ru/net/aspose.pdf/document/actions/
---
## Document.Actions property

Получает действия документа. Это свойство является экземпляром класса DocumentActions, который позволяет получать/устанавливать действия BeforClosing, BeforSaving и т.д.

```csharp
public DocumentActionCollection Actions { get; }
```

## Примеры

В этом примере показано, как получить действие после открытия документа:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### См. также

* class [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


