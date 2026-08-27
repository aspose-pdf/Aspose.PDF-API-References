---
title: "Page.Duration"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Page. Obtient ou définit la durée d'affichage de la page. Il s'agit du temps en secondes pendant lequel la page doit être affichée lors d'une présentation. Retourne 1 si la durée n'est pas définie."
type: docs
weight: 110
url: /fr/net/aspose.pdf/page/duration/
---
## Page.Duration property

Obtient ou définit la durée d'affichage de la page. Il s'agit du temps en secondes pendant lequel la page doit être affichée pendant la présentation. Retourne -1 si la durée n'est pas définie.

```csharp
public double Duration { get; set; }
```

## Exemples

L'exemple montre comment obtenir la durée de la page.

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Voir aussi

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


