---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Propriété Page. Obtient ou définit le rectangle de la page. Pour obtenir, la boîte de recadrage de la page est renvoyée si spécifiée, sinon la boîte de médias de la page est renvoyée. Pour définir, la boîte de médias de la page est toujours définie. Veuillez noter que cette propriété ne prend pas en compte la rotation de la page. Pour obtenir le rectangle de la page en tenant compte de la rotation, veuillez utiliser ActualRect.
type: docs
weight: 230
url: /fr/net/aspose.pdf/page/rect/
---
## Propriété Page.Rect

Obtient ou définit le rectangle de la page. Pour obtenir : la boîte de recadrage de la page est renvoyée si spécifiée, sinon la boîte de médias de la page est renvoyée. Pour définir : la boîte de médias de la page est toujours définie. Veuillez noter que cette propriété ne prend pas en compte la rotation de la page. Pour obtenir le rectangle de la page en tenant compte de la rotation, veuillez utiliser ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Exemples

L'exemple démontre comment obtenir le rectangle de la page :

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Voir aussi

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)