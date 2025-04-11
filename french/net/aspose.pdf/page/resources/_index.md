---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la page. Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices. Resources
type: docs
weight: 240
url: /fr/net/aspose.pdf/page/resources/
---
## Propriété Page.Resources

Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices. `Resources`

```csharp
public Resources Resources { get; }
```

## Exemples

L'exemple démontre le scan à travers les images de la page :

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### Voir aussi

* classe [Resources](../../resources/)
* classe [Page](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)