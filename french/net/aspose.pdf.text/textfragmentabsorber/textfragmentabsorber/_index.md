---
title: TextFragmentAbsorber
second_title: Référence de l'API Aspose.PDF pour .NET
description: Initialise une nouvelle instance duTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber qui effectue la recherche de tous les segments de texte du document ou de la page.
type: docs
weight: 10
url: /fr/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Initialise une nouvelle instance du[`TextFragmentAbsorber`](../../textfragmentabsorber) qui effectue la recherche de tous les segments de texte du document ou de la page.

```csharp
public TextFragmentAbsorber()
```

### Remarques

Effectue une recherche de texte et donne accès aux résultats de la recherche via[`TextFragments`](../textfragments) le recueil.

### Exemples

L'exemple montre comment rechercher du texte sur la première page du document PDF et remplacer le texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouve la police qui sera utilisée pour changer la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Créer un objet TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Faire en sorte que l'absorbeur recherche toutes les occurrences de texte "hello world"
absorber.Phrase = "hello world";

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Change le texte de la première occurrence de texte
absorber.TextFragments[1].Text = "hi world";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir également

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Initialise une nouvelle instance du[`TextFragmentAbsorber`](../../textfragmentabsorber)avec des options d'édition de texte, qui effectue la recherche de tous les segments de texte du document ou de la page.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Options d'édition de texte (permet d'activer certaines fonctionnalités d'édition). |

### Remarques

Effectue une recherche de texte et donne accès aux résultats de la recherche via[`TextFragments`](../textfragments) le recueil.

### Exemples

L'exemple montre comment trouver tous les fragments de texte sur la première page du document PDF et remplacer la police pour eux.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créer un objet TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Trouver la police Courier
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Définit la police pour tous les fragments de texte
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");
```

### Voir également

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Initialise une nouvelle instance du[`TextFragmentAbsorber`](../../textfragmentabsorber) classe pour la phrase de texte spécifiée.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| phrase | String | Phrase que le[`TextFragmentAbsorber`](../../textfragmentabsorber) recherches |

### Remarques

Effectue une recherche textuelle de la phrase spécifiée et donne accès aux résultats de la recherche via[`TextFragments`](../textfragments) collection.

### Exemples

L'exemple montre comment rechercher du texte sur la première page du document PDF et remplacer le texte et sa police.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouve la police qui sera utilisée pour changer la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crée un objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// Changer le texte et la police de la première occurrence de texte
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir également

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Initialise une nouvelle instance du[`TextFragmentAbsorber`](../../textfragmentabsorber) classe pour l'objet de classe System.Text.RegularExpressions.Regex spécifié.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| regex | Regex | objet de classe System.Text.RegularExpressions.Regex que le[`TextFragmentAbsorber`](../../textfragmentabsorber) recherches |

### Remarques

Effectue une recherche textuelle de la phrase spécifiée et donne accès aux résultats de la recherche via[`TextFragments`](../textfragments) collection.

### Exemples

L'exemple montre comment rechercher du texte sur la première page du document PDF et remplacer le texte et sa police.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Trouve la police qui sera utilisée pour changer la police du texte du document
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crée un objet TextAbsorber pour trouver toutes les instances de la regex d'entrée
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accepte l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// nous devrions trouver le mot "bonjour" et le remplacer par "Salut"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");
```

### Voir également

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Initialise une nouvelle instance du[`TextFragmentAbsorber`](../../textfragmentabsorber)classe pour la phrase de texte spécifiée et les options de recherche de texte.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| phrase | String | Phrase que le[`TextFragmentAbsorber`](../../textfragmentabsorber) recherches |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (permet d'activer certaines fonctionnalités de recherche. Par exemple, rechercher avec une expression régulière) |

### Remarques

Effectue une recherche textuelle de la phrase spécifiée et donne accès aux résultats de la recherche via[`TextFragments`](../textfragments) collection.

### Exemples

L'exemple montre comment rechercher du texte avec une expression régulière sur la première page du document PDF et remplacer le texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Crée un objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// nous devrions trouver le mot "bonjour" et le remplacer par "Salut"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir également

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Initialise une nouvelle instance du[`TextFragmentAbsorber`](../../textfragmentabsorber) classe pour la phrase de texte spécifiée et les options de recherche de texte.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| regex | Regex | objet de classe System.Text.RegularExpressions.Regex que le[`TextFragmentAbsorber`](../../textfragmentabsorber) recherches |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (Permet d'activer certaines fonctionnalités de recherche.) |

### Remarques

Effectue une recherche textuelle de la phrase spécifiée et donne accès aux résultats de la recherche via[`TextFragments`](../textfragments) collection.

### Exemples

L'exemple montre comment rechercher du texte avec une expression régulière sur la première page du document PDF et remplacer le texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Crée un objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// nous devrions trouver le mot "bonjour" et le remplacer par "Salut"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");
```

### Voir également

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Initialise une nouvelle instance du[`TextFragmentAbsorber`](../../textfragmentabsorber) classe pour la phrase de texte spécifiée, les options de recherche de texte et les options d'édition de texte.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| phrase | String | Phrase que le[`TextFragmentAbsorber`](../../textfragmentabsorber) recherches |
| textSearchOptions | TextSearchOptions | Options de recherche de texte (permet d'activer certaines fonctionnalités de recherche. Par exemple, rechercher avec une expression régulière) |
| textEditOptions | TextEditOptions | Options d'édition de texte (permet d'activer certaines fonctionnalités d'édition). |

### Remarques

Effectue une recherche textuelle de la phrase spécifiée et donne accès aux résultats de la recherche via[`TextFragments`](../textfragments) collection.

### Exemples

L'exemple montre comment rechercher du texte avec une expression régulière sur la première page du document PDF et remplacer le texte.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Crée un objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// nous devrions trouver le mot "bonjour" et le remplacer par "Salut"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Enregistrer le document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir également

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Initialise une nouvelle instance du[`TextFragmentAbsorber`](../../textfragmentabsorber) classe pour la phrase de texte spécifiée et les options d'édition de texte.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| phrase | String | Phrase que le[`TextFragmentAbsorber`](../../textfragmentabsorber) recherches |
| textEditOptions | TextEditOptions | Options d'édition de texte (permet d'activer certaines fonctionnalités d'édition). |

### Remarques

Effectue une recherche textuelle de la phrase spécifiée et donne accès aux résultats de la recherche via[`TextFragments`](../textfragments) collection.

### Voir également

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Initialise une nouvelle instance du[`TextFragmentAbsorber`](../../textfragmentabsorber) classe pour la phrase de texte spécifiée et les options d'édition de texte.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| regex | Regex | objet de classe System.Text.RegularExpressions.Regex que le[`TextFragmentAbsorber`](../../textfragmentabsorber) recherches |
| textEditOptions | TextEditOptions | Options d'édition de texte (permet d'activer certaines fonctionnalités d'édition). |

### Remarques

Effectue une recherche textuelle de la phrase spécifiée et donne accès aux résultats de la recherche via[`TextFragments`](../textfragments) collection.

### Voir également

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* espace de noms [Aspose.Pdf.Text](../../textfragmentabsorber)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
