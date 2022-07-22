---
title: TextFragmentAbsorber
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente un objet absorbeur de fragments de texte. Effectue une recherche de texte et permet daccéder aux résultats de la recherche viaTextFragments./textfragmentabsorber/textfragments collection.
type: docs
weight: 7110
url: /fr/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Représente un objet absorbeur de fragments de texte. Effectue une recherche de texte et permet d'accéder aux résultats de la recherche via[`TextFragments`](./textfragments) collection.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber#constructor)() | Initialise une nouvelle instance du[`TextFragmentAbsorber`](../textfragmentabsorber) qui effectue la recherche de tous les segments de texte du document ou de la page. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_6)(Regex) | Initialise une nouvelle instance du[`TextFragmentAbsorber`](../textfragmentabsorber) classe pour l'objet de classe System.Text.RegularExpressions.Regex spécifié. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_2)(string) | Initialise une nouvelle instance du[`TextFragmentAbsorber`](../textfragmentabsorber) classe pour la phrase de texte spécifiée. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_1)(TextEditOptions) | Initialise une nouvelle instance du[`TextFragmentAbsorber`](../textfragmentabsorber)avec des options d'édition de texte, qui effectue la recherche de tous les segments de texte du document ou de la page. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_7)(Regex, TextEditOptions) | Initialise une nouvelle instance du[`TextFragmentAbsorber`](../textfragmentabsorber) classe pour la phrase de texte spécifiée et les options d'édition de texte. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_8)(Regex, TextSearchOptions) | Initialise une nouvelle instance du[`TextFragmentAbsorber`](../textfragmentabsorber) classe pour la phrase de texte spécifiée et les options de recherche de texte. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_3)(string, TextEditOptions) | Initialise une nouvelle instance du[`TextFragmentAbsorber`](../textfragmentabsorber) classe pour la phrase de texte spécifiée et les options d'édition de texte. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_4)(string, TextSearchOptions) | Initialise une nouvelle instance du[`TextFragmentAbsorber`](../textfragmentabsorber)classe pour la phrase de texte spécifiée et les options de recherche de texte. |
| [TextFragmentAbsorber](textfragmentabsorber#constructor_5)(string, TextSearchOptions, TextEditOptions) | Initialise une nouvelle instance du[`TextFragmentAbsorber`](../textfragmentabsorber) classe pour la phrase de texte spécifiée, les options de recherche de texte et les options d'édition de texte. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors) { get; } | Liste des[`TextExtractionError`](../textextractionerror) objets. Il contient des informations sur les erreurs trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; Et cela peut diminuer les performances. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions) { get; set; } | Obtient ou définit les options d'extraction de texte. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors) { get; } | La valeur indique si des erreurs ont été trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; Et cela peut diminuer les performances. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase) { get; set; } | Obtient ou définit la phrase que le[`TextFragmentAbsorber`](../textfragmentabsorber) recherche sur le document ou la page PDF. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text) { get; } | Obtient le texte extrait que le[`TextAbsorber`](../textabsorber) extraits sur le document ou la page PDF. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions) { get; set; } | Obtient ou définit les options d'édition de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments) { get; set; } | Obtient une collection d'occurrences de recherche présentées avec[`TextFragment`](../textfragment) objets. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions) { get; set; } | Obtient ou définit les options de remplacement de texte. Les options définissent le comportement lorsque le texte fragmenté est remplacé par un texte plus court/long. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions) { get; set; } | Obtient ou définit les options de recherche. Les options activent la recherche à l'aide d'expressions régulières. |

## Méthodes

| Nom | La description |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_2)(float) | Applique la taille de la police pour tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments de la ou des pages ont été absorbés. Sinon, cela fonctionne de la même manière avec la boucle. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments)(Font) | Applique la police pour tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments de la ou des pages ont été absorbés. Sinon, cela fonctionne de la même manière avec la boucle. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments#applyforallfragments_1)(Font, float) | Applique la police et la taille de tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments de la ou des pages ont été absorbés. Sinon, cela fonctionne de la même manière avec la boucle. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext)(Document) | Supprime tout le texte du document. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_1)(Page) | Supprime tout le texte de la page spécifiée. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext#removealltext_2)(Page, Rectangle) | Supprime le texte à l'intérieur du rectangle spécifié de la page spécifiée. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset)() | Efface la collection TextFragments de ce[`TextFragmentAbsorber`](../textfragmentabsorber) objet. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit)(Document) | Effectue une recherche sur le document spécifié. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_1)(Page) | Effectue une recherche sur la page spécifiée. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit#visit_2)(XForm) | Effectue une recherche sur l'objet de formulaire spécifié. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit)(XForm) | Extrait le texte sur le XForm spécifié. |

### Remarques

Le[`TextFragmentAbsorber`](../textfragmentabsorber) objet est essentiellement utilisé dans le scénario de recherche de texte. Lorsque la recherche est terminée, les occurrences sont représentées par[`TextFragment`](../textfragment) objets que le[`TextFragments`](./textfragments) collection contient. Le[`TextFragment`](../textfragment) L'objet donne accès au texte de l'occurrence de recherche, aux propriétés du texte et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc.).

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

* class [TextAbsorber](../textabsorber)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
