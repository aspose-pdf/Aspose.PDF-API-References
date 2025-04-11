---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextAbsorber. Obtient ou définit les options d'extraction de texte
type: docs
weight: 30
url: /fr/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## Propriété TextAbsorber.ExtractionOptions

Obtient ou définit les options d'extraction de texte.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Remarques

Permet de définir le mode de formatage du texte [`TextExtractionOptions`](../../textextractionoptions/) lors de l'extraction. Le mode par défaut est Pur

## Exemples

L'exemple démontre comment définir le mode de formatage de texte Pur et effectuer l'extraction de texte.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### Voir aussi

* classe [TextExtractionOptions](../../textextractionoptions/)
* classe [TextAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)