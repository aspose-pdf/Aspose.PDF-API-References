---
title: Page.BleedBox
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la page. Obtient ou définit la zone de débordement de la page
type: docs
weight: 70
url: /fr/net/aspose.pdf/page/bleedbox/
---
## Propriété Page.BleedBox

Obtient ou définit la zone de débordement de la page.

```csharp
public Rectangle BleedBox { get; set; }
```

## Exemples

L'exemple démontre comment obtenir la zone de débordement de la page:

```csharp
Document document = new Document("sample.pdf");
Rectangle bleedBox = document.Pages[1].BleedBox;
```

### Voir aussi

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)