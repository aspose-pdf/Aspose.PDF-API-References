---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextFragmentAbsorber. Représente un objet absorbeur de fragments de texte. Effectue une recherche de texte et fournit un accès aux résultats de recherche via la collection TextFragments
type: docs
weight: 10950
url: /fr/net/aspose.pdf.text/textfragmentabsorber/
---
## Classe TextFragmentAbsorber

Représente un objet absorbeur de fragments de texte. Effectue une recherche de texte et fournit un accès aux résultats de recherche via la collection [`TextFragments`](./textfragments/).

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Initialise une nouvelle instance de `TextFragmentAbsorber` qui effectue la recherche de tous les segments de texte du document ou de la page. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Initialise une nouvelle instance de la classe `TextFragmentAbsorber` pour l'objet de classe System.Text.RegularExpressions.Regex spécifié. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Initialise une nouvelle instance de la classe `TextFragmentAbsorber` pour la phrase de texte spécifiée. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Initialise une nouvelle instance de la classe `TextFragmentAbsorber` avec des options d'édition de texte, qui effectue la recherche de tous les segments de texte du document ou de la page. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Initialise une nouvelle instance de la classe `TextFragmentAbsorber` pour la phrase de texte spécifiée et les options d'édition de texte. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Initialise une nouvelle instance de la classe `TextFragmentAbsorber` pour la phrase de texte spécifiée et les options de recherche de texte. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | Initialise une nouvelle instance de la classe `TextFragmentAbsorber` pour la phrase de texte spécifiée et les options de recherche de texte. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Initialise une nouvelle instance de la classe `TextFragmentAbsorber` pour la phrase de texte spécifiée et les options d'édition de texte. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Initialise une nouvelle instance de la classe `TextFragmentAbsorber` pour la phrase de texte spécifiée et les options de recherche de texte. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Initialise une nouvelle instance de la classe `TextFragmentAbsorber` pour la phrase de texte spécifiée, les options de recherche de texte et les options d'édition de texte. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | Liste des objets [`TextExtractionError`](../textextractionerror/). Elle contient des informations sur les erreurs trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true; et cela peut diminuer les performances. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Obtient ou définit les options d'extraction de texte. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | La valeur indique si des erreurs ont été trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true; et cela peut diminuer les performances. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Obtient ou définit la phrase que le `TextFragmentAbsorber` recherche dans le document ou la page PDF. |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | Obtient un dictionnaire des occurrences de recherche présentées avec la classe System.Text.RegularExpressions.Regex comme clé et [`TextFragment`](../textfragment/) comme valeur. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Obtient le texte extrait que le [`TextAbsorber`](../textabsorber/) extrait du document ou de la page PDF. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Obtient ou définit les options d'édition de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Obtient la collection des occurrences de recherche présentées avec des objets [`TextFragment`](../textfragment/). |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Obtient ou définit les options de remplacement de texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Obtient ou définit les options de recherche. Les options permettent la recherche à l'aide d'expressions régulières. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Applique la taille de police à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire à un parcours. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Applique la police à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire à un parcours. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Applique la police et la taille à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire à un parcours. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Supprime tout le texte du document. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Supprime tout le texte de la page spécifiée. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Supprime le texte à l'intérieur du rectangle spécifié de la page spécifiée. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Efface la collection TextFragments de cet objet `TextFragmentAbsorber`. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Effectue une recherche sur le document spécifié. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Effectue une recherche sur la page spécifiée. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Effectue une recherche sur l'objet de formulaire spécifié. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Extrait le texte sur le XForm spécifié. |

## Remarques

L'objet `TextFragmentAbsorber` est principalement utilisé dans le scénario de recherche de texte. Lorsque la recherche est terminée, les occurrences sont représentées par des objets [`TextFragment`](../textfragment/) que la collection [`TextFragments`](./textfragments/) contient. L'objet [`TextFragment`](../textfragment/) fournit un accès au texte des occurrences de recherche, aux propriétés du texte, et permet d'éditer le texte et de changer l'état du texte (police, taille de police, couleur, etc.).

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

* classe [TextAbsorber](../textabsorber/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)