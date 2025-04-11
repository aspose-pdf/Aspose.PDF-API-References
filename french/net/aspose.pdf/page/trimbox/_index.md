---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la page. Obtient ou définit la zone de rognage de la page
type: docs
weight: 290
url: /fr/net/aspose.pdf/page/trimbox/
---
## Propriété Page.TrimBox

Obtient ou définit la zone de rognage de la page.

```csharp
public Rectangle TrimBox { get; set; }
```

## Exemples

L'exemple démontre comment obtenir la zone de rognage de la page :

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### Voir aussi

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)