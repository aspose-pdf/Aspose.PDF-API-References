---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Constructeur de TextAbsorber. Initialise une nouvelle instance de TextAbsorber
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

Effectue l'extraction de texte et fournit un accès au texte extrait via l'objet [`Text`](../text/).

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

Effectue l'extraction de texte et fournit un accès au texte extrait via l'objet [`Text`](../text/).

## Exemples

L'exemple démontre comment extraire du texte de toutes les pages du document PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

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

Effectue l'extraction de texte et fournit un accès au texte extrait via l'objet [`Text`](../text/).

### Voir aussi

* classe [TextExtractionOptions](../../textextractionoptions/)
* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
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

Effectue l'extraction de texte et fournit un accès au texte extrait via l'objet [`Text`](../text/).

### Voir aussi

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)