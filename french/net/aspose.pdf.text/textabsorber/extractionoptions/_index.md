---
title: "TextAbsorber.ExtractionOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextAbsorber. Obtient ou définit les options d'extraction de texte."
type: docs
weight: 30
url: /fr/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

Obtient ou définit les options d'extraction de texte.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Remarques

Permet de définir le mode de formatage du texte [`TextExtractionOptions`](../../textextractionoptions/) pendant l'extraction. Le mode par défaut est Pure.

## Exemples

L'exemple montre comment définir le mode de formatage de texte Pure et effectuer l'extraction de texte.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// créez un objet TextAbsorber pour extraire du texte avec formatage
TextAbsorber absorber = new TextAbsorber();

// définissez le mode de formatage de texte pur
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accepter l'absorbeur pour toutes les pages du document
doc.Pages.Accept(absorber);

// obtenir le texte extrait
string extractedText = absorber.Text;
```

### Voir aussi

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


