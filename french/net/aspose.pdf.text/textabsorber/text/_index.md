---
title: "TextAbsorber.Text"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextAbsorber. Obtient le texte extrait que le TextAbsorber récupère dans le document PDF ou la page."
type: docs
weight: 50
url: /fr/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

Obtient le texte extrait que le [`TextAbsorber`](../) récupère dans le document PDF ou la page.

```csharp
public virtual string Text { get; }
```

## Exemples

L'exemple montre comment extraire du texte de toutes les pages du document PDF.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// créer un objet TextAbsorber pour extraire du texte
TextAbsorber absorber = new TextAbsorber();

// accepter l'absorbeur pour toutes les pages du document
doc.Pages.Accept(absorber);

// obtenir le texte extrait
string extractedText = absorber.Text;

```

### Voir aussi

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


