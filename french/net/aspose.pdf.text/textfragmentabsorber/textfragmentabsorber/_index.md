---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Constructeur de TextFragmentAbsorber. Initialise une nouvelle instance de TextFragmentAbsorber qui effectue la recherche de tous les segments de texte du document ou de la page
type: docs
weight: 10
url: /fr/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Initialise une nouvelle instance de [`TextFragmentAbsorber`](../) qui effectue la recherche de tous les segments de texte du document ou de la page.

```csharp
public TextFragmentAbsorber()
```

## Remarques

Effectue une recherche de texte et fournit un accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple démontre comment trouver du texte sur la première page du document PDF et remplacer le texte.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Make the absorber to search all "hello world" text occurrences
absorber.Phrase = "hello world";

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initialise une nouvelle instance de [`TextFragmentAbsorber`](../) avec des options d'édition de texte, qui effectue la recherche de tous les segments de texte du document ou de la page.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Options d'édition de texte (Permet d'activer certaines fonctionnalités d'édition). |

## Remarques

Effectue une recherche de texte et fournit un accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple démontre comment trouver tous les fragments de texte sur la première page du document PDF et remplacer la police pour eux.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Find Courier font
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Set the font for all the text fragments
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### Voir aussi

* classe [TextEditOptions](../../texteditoptions/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase de texte spécifiée.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase que le [`TextFragmentAbsorber`](../) recherche |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit un accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple démontre comment trouver du texte sur la première page du document PDF et remplacer le texte et sa police.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour l'objet de classe spécifié System.Text.RegularExpressions.Regex.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | Regex | Objet de classe System.Text.RegularExpressions.Regex que le [`TextFragmentAbsorber`](../) recherche |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit un accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple démontre comment trouver du texte sur la première page du document PDF et remplacer le texte et sa police.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextAbsorber object to find all instances of the input regex
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### Voir aussi

* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase de texte spécifiée et les options de recherche de texte.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase que le [`TextFragmentAbsorber`](../) recherche |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (Permet d'activer certaines fonctionnalités de recherche. Par exemple, recherche avec expression régulière) |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit un accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple démontre comment trouver du texte avec une expression régulière sur la première page du document PDF et remplacer le texte.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase de texte spécifiée et les options de recherche de texte.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | Regex | Objet de classe System.Text.RegularExpressions.Regex que le [`TextFragmentAbsorber`](../) recherche |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (Permet d'activer certaines fonctionnalités de recherche.) |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit un accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple démontre comment trouver du texte avec une expression régulière sur la première page du document PDF et remplacer le texte.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### Voir aussi

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour le tableau de phrases de texte spécifié et les options de recherche de texte.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| regexes | Regex[] | Tableau d'objets de classe System.Text.RegularExpressions.Regex que le [`TextFragmentAbsorber`](../) recherche. |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (Permet d'activer certaines fonctionnalités de recherche.). |

## Remarques

Effectue une recherche de texte du tableau spécifié de phrases et fournit un accès aux résultats de recherche via le dictionnaire [`RegexResults`](../regexresults/).

## Exemples

L'exemple démontre comment trouver du texte avec un tableau d'expressions régulières sur la première page du document PDF.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results of 
var results = absorber.RegexResults;
```

### Voir aussi

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase de texte spécifiée, les options de recherche de texte et les options d'édition de texte.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase que le [`TextFragmentAbsorber`](../) recherche |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (Permet d'activer certaines fonctionnalités de recherche. Par exemple, recherche avec expression régulière) |
| textEditOptions | TextEditOptions | Options d'édition de texte (Permet d'activer certaines fonctionnalités d'édition). |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit un accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple démontre comment trouver du texte avec une expression régulière sur la première page du document PDF et remplacer le texte.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextEditOptions](../../texteditoptions/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase de texte spécifiée et les options d'édition de texte.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase que le [`TextFragmentAbsorber`](../) recherche |
| textEditOptions | TextEditOptions | Options d'édition de texte (Permet d'activer certaines fonctionnalités d'édition). |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit un accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

### Voir aussi

* classe [TextEditOptions](../../texteditoptions/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase de texte spécifiée et les options d'édition de texte.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | Regex | Objet de classe System.Text.RegularExpressions.Regex que le [`TextFragmentAbsorber`](../) recherche |
| textEditOptions | TextEditOptions | Options d'édition de texte (Permet d'activer certaines fonctionnalités d'édition). |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit un accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

### Voir aussi

* classe [TextEditOptions](../../texteditoptions/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)