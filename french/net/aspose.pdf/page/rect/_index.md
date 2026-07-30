---
title: "Page.Rect"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Page. Obtient ou définit le rectangle de la page. Pour la lecture, la zone de recadrage de la page est renvoyée si elle est spécifiée, sinon la boîte média de la page est renvoyée. Pour l’écriture, la boîte média de la page est toujours définie. Veuillez noter que cette propriété ne prend pas en compte la rotation de la page. Pour obtenir le rectangle de la page en tenant compte de la rotation, utilisez ActualRect."
type: docs
weight: 230
url: /fr/net/aspose.pdf/page/rect/
---
## Page.Rect property

Obtient ou définit le rectangle de la page. Pour l'obtention : la boîte de rognage de la page est renvoyée si spécifiée, sinon la boîte média de la page est renvoyée. Pour la définition : la boîte média de la page est toujours définie. Veuillez noter que cette propriété ne tient pas compte de la rotation de la page. Pour obtenir le rectangle de la page en tenant compte de la rotation, veuillez utiliser ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Exemples

L'exemple montre comment obtenir le rectangle de la page :

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Voir aussi

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


