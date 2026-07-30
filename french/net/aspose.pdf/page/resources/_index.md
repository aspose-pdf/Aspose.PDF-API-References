---
title: "Page.Resources"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Page. Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices. Resources"
type: docs
weight: 240
url: /fr/net/aspose.pdf/page/resources/
---
## Page.Resources property

Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices. `Resources`

```csharp
public Resources Resources { get; }
```

## Exemples

L'exemple montre le balayage des images de la page :

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

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


