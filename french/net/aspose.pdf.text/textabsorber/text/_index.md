---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextAbsorber. Obtient le texte extrait que le TextAbsorber extrait du document ou de la page PDF
type: docs
weight: 50
url: /fr/net/aspose.pdf.text/textabsorber/text/
---
## Propriété TextAbsorber.Text

Obtient le texte extrait que le [`TextAbsorber`](../) extrait du document ou de la page PDF.

```csharp
public virtual string Text { get; }
```

## Exemples

L'exemple démontre comment extraire du texte de toutes les pages du document PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Voir aussi

* classe [TextAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)