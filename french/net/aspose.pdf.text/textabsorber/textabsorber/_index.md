---
title: "TextAbsorber.TextAbsorber"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Constructeur TextAbsorber. Initialise une nouvelle instance de TextAbsorber"
type: docs
weight: 10
url: /fr/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Initialise une nouvelle instance de [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Remarques

Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet [`Text`](../text/).

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

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Initialise une nouvelle instance de [`TextAbsorber`](../) avec des options d'extraction.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Options d'extraction de texte |

## Remarques

Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet [`Text`](../text/).

## Exemples

L'exemple montre comment extraire du texte de toutes les pages du document PDF.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// créez un objet TextAbsorber pour extraire du texte avec formatage
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

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

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Initialise une nouvelle instance de [`TextAbsorber`](../) avec des options d'extraction et de recherche de texte.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Options d'extraction de texte |
| textSearchOptions | TextSearchOptions | Options de recherche de texte |

## Remarques

Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet [`Text`](../text/).

### Voir aussi

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Initialise une nouvelle instance de [`TextAbsorber`](../) avec des options de recherche de texte.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Options de recherche de texte |

## Remarques

Effectue l'extraction de texte et fournit l'accès au texte extrait via l'objet [`Text`](../text/).

### Voir aussi

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


