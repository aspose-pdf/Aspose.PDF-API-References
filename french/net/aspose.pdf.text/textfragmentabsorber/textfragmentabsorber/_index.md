---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Constructeur TextFragmentAbsorber. Initialise une nouvelle instance du TextFragmentAbsorber qui effectue la recherche de tous les segments de texte du document ou de la page."
type: docs
weight: 10
url: /fr/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Initialise une nouvelle instance du [`TextFragmentAbsorber`](../) qui effectue la recherche de tous les segments de texte du document ou de la page.

```csharp
public TextFragmentAbsorber()
```

## Remarques

Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouver la police qui sera utilisée pour modifier la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Créer un objet TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Faire en sorte que l'absorbeur recherche toutes les occurrences du texte "hello world"
absorber.Phrase = "hello world";

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier le texte de la première occurrence de texte
absorber.TextFragments[1].Text = "hi world";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initialise une nouvelle instance du [`TextFragmentAbsorber`](../) avec des options d'édition de texte, qui effectue la recherche de tous les segments de texte du document ou de la page.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Options d'édition de texte (Permet d'activer certaines fonctionnalités d'édition). |

## Remarques

Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple montre comment trouver tous les fragments de texte sur la première page du document PDF et remplacer la police pour ceux-ci.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Trouver la police Courier
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Définir la police pour tous les fragments de texte
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");
```

### Voir aussi

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase de texte spécifiée.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase que la [`TextFragmentAbsorber`](../) recherche |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit l'accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte ainsi que sa police.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouver la police qui sera utilisée pour modifier la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Modifier le texte et la police de la première occurrence de texte
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour l'objet de classe System.Text.RegularExpressions.Regex spécifié.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | Regex | Objet de classe System.Text.RegularExpressions.Regex que la [`TextFragmentAbsorber`](../) recherche |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit l'accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte ainsi que sa police.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouver la police qui sera utilisée pour modifier la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Créer un objet TextAbsorber pour trouver toutes les instances de l'expression régulière d'entrée
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// nous devrions trouver le mot "hello" et le remplacer par "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");
```

### Voir aussi

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase texte spécifiée et les options de recherche de texte.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase que la [`TextFragmentAbsorber`](../) recherche |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (Permet d'activer certaines fonctionnalités de recherche. Par exemple, rechercher avec une expression régulière) |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit l'accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple montre comment trouver du texte avec une expression régulière sur la première page du document PDF et remplacer le texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// nous devrions trouver le mot "hello" et le remplacer par "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase texte spécifiée et les options de recherche de texte.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | Regex | Objet de classe System.Text.RegularExpressions.Regex que la [`TextFragmentAbsorber`](../) recherche |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (Permet d'activer certaines fonctionnalités de recherche.) |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit l'accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple montre comment trouver du texte avec une expression régulière sur la première page du document PDF et remplacer le texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// nous devrions trouver le mot "hello" et le remplacer par "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");
```

### Voir aussi

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase texte spécifiée et les options de recherche de texte.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| regexes | Regex[] | Tableau d'objets de classe System.Text.RegularExpressions.Regex que la [`TextFragmentAbsorber`](../) recherche. |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (Permet d'activer certaines fonctionnalités de recherche.). |

## Remarques

Effectue une recherche de texte du tableau de phrases spécifié et fournit l'accès aux résultats de recherche via le dictionnaire [`RegexResults`](../regexresults/).

## Exemples

L'exemple montre comment trouver du texte avec un tableau d'expressions régulières sur la première page du document PDF.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Créer un objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Obtenir les résultats de 
var results = absorber.RegexResults;
```

### Voir aussi

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase texte spécifiée, les options de recherche de texte et les options d'édition de texte.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase que la [`TextFragmentAbsorber`](../) recherche |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (Permet d'activer certaines fonctionnalités de recherche. Par exemple, rechercher avec une expression régulière) |
| textEditOptions | TextEditOptions | Options d'édition de texte (Permet d'activer certaines fonctionnalités d'édition). |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit l'accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

## Exemples

L'exemple montre comment trouver du texte avec une expression régulière sur la première page du document PDF et remplacer le texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// nous devrions trouver le mot "hello" et le remplacer par "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase texte spécifiée et les options d'édition de texte.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| phrase | String | Phrase que la [`TextFragmentAbsorber`](../) recherche |
| textEditOptions | TextEditOptions | Options d'édition de texte (Permet d'activer certaines fonctionnalités d'édition). |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit l'accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

### Voir aussi

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initialise une nouvelle instance de la classe [`TextFragmentAbsorber`](../) pour la phrase texte spécifiée et les options d'édition de texte.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | Regex | Objet de classe System.Text.RegularExpressions.Regex que la [`TextFragmentAbsorber`](../) recherche |
| textEditOptions | TextEditOptions | Options d'édition de texte (Permet d'activer certaines fonctionnalités d'édition). |

## Remarques

Effectue une recherche de texte de la phrase spécifiée et fournit l'accès aux résultats de recherche via la collection [`TextFragments`](../textfragments/).

### Voir aussi

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


