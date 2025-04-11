---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la page. Obtient ou définit la boîte d'art de la page
type: docs
weight: 30
url: /fr/net/aspose.pdf/page/artbox/
---
## Propriété Page.ArtBox

Obtient ou définit la boîte d'art de la page.

```csharp
public Rectangle ArtBox { get; set; }
```

## Exemples

L'exemple démontre comment obtenir la boîte d'art de la page:

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### Voir aussi

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)