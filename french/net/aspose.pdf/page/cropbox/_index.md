---
title: "Page.CropBox"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Page. Obtient ou définit la zone de rognage de la page."
type: docs
weight: 100
url: /fr/net/aspose.pdf/page/cropbox/
---
## Page.CropBox property

Obtient ou définit la boîte de rognage de la page.

```csharp
public Rectangle CropBox { get; set; }
```

## Exemples

L'exemple montre comment obtenir la zone de rognage de la page :

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### Voir aussi

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


