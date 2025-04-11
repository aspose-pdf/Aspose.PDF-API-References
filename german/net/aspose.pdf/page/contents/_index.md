---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: Seiten-Eigenschaft. Ruft die Sammlung von Operatoren im Inhaltsstrom der Seite ab. OperatorCollection
type: docs
weight: 90
url: /de/net/aspose.pdf/page/contents/
---
## Seite.Inhalte-Eigenschaft

Ruft die Sammlung von Operatoren im Inhaltsstrom der Seite ab. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Beispiele

Das Beispiel zeigt, wie man den Operatorenstrom der Seite scannt.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Siehe auch

* Klasse [OperatorCollection](../../operatorcollection/)
* Klasse [Seite](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)