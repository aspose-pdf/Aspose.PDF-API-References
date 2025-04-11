---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la page. Obtient ou définit la zone de rognage de la page
type: docs
weight: 100
url: /fr/net/aspose.pdf/page/cropbox/
---
## Propriété Page.CropBox

Obtient ou définit la zone de rognage de la page.

```csharp
public Rectangle CropBox { get; set; }
```

## Exemples

L'exemple démontre comment obtenir la zone de rognage de la page:

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### Voir aussi

* classe [Rectangle](../../rectangle/)
* classe [Page](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)