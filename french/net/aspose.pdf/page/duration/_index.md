---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la page. Obtient ou définit la durée d'affichage de la page. C'est le temps en secondes que la page doit être affichée pendant la présentation. Renvoie 1 si la durée n'est pas définie
type: docs
weight: 110
url: /fr/net/aspose.pdf/page/duration/
---
## Propriété Page.Duration

Obtient ou définit la durée d'affichage de la page. C'est le temps en secondes que la page doit être affichée pendant la présentation. Renvoie -1 si la durée n'est pas définie.

```csharp
public double Duration { get; set; }
```

## Exemples

L'exemple démontre comment obtenir la durée de la page

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Voir aussi

* classe [Page](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)