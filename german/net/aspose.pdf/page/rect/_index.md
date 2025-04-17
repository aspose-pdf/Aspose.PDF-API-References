---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Seiten-Eigenschaft. Holt oder setzt das Rechteck der Seite. Für das Abrufen Das Seitenbeschnittfeld wird zurückgegeben, wenn angegeben, andernfalls wird das Seitenmedienfeld zurückgegeben. Für das Setzen Das Seitenmedienfeld wird immer gesetzt. Bitte beachten Sie, dass diese Eigenschaft die Seitenrotation nicht berücksichtigt. Um das Seitenrechteck unter Berücksichtigung der Rotation zu erhalten, verwenden Sie bitte ActualRect.
type: docs
weight: 230
url: /de/net/aspose.pdf/page/rect/
---
## Page.Rect-Eigenschaft

Holt oder setzt das Rechteck der Seite. Für das Abrufen: Das Seitenbeschnittfeld wird zurückgegeben, wenn angegeben, andernfalls wird das Seitenmedienfeld zurückgegeben. Für das Setzen: Das Seitenmedienfeld wird immer gesetzt. Bitte beachten Sie, dass diese Eigenschaft die Seitenrotation nicht berücksichtigt. Um das Seitenrechteck unter Berücksichtigung der Rotation zu erhalten, verwenden Sie bitte ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man das Seitenrechteck erhält:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Siehe auch

* Klasse [Rectangle](../../rectangle/)
* Klasse [Page](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)