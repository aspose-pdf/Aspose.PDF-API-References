---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente un objet absorbeur de fragments de texte. Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>."
type: docs
weight: 5120
url: /fr/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> Représente un objet absorbeur de fragments de texte. Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte et sa police. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte et la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> L'objet {@code TextFragmentAbsorber} est essentiellement utilisé dans un scénario de recherche de texte. Lorsque la recherche est terminée, les occurrences sont représentées par des objets {@code TextFragment} que contient la collection {@code TextFragmentAbsorber.TextFragments}. L'objet {@code TextFragment} fournit l'accès au texte de l'occurrence recherchée, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc). </p>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer un objet TextFragmentAbsorber TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Configurer l'absorbeur pour rechercher toutes les occurrences du texte "hello world" absorber.setPhrase ( "hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Effectue une recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | Applique la taille de police à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire à une itération. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | Applique la police à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire à une itération. |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | Applique la police et la taille à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire à une itération. |
| [getErrors](#getErrors--) | Liste d'objets {@code TextExtractionError}. Elle contient des informations sur les erreurs trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut réduire les performances. |
| [getExtractionOptions](#getExtractionOptions--) | Obtient les options d'extraction de texte. |
| [getPhrase](#getPhrase--) | <p> Obtient la phrase que {@code TextFragmentAbsorber} recherche dans le document PDF ou la page. </p> |
| [getRegexResults](#getRegexResults--) | Obtient le dictionnaire des occurrences de recherche présentées avec la classe System.Text.RegularExpressions.Regex comme clé et {@link TextFragment} comme valeur. L'exemple montre comment trouver du texte avec un tableau d'expressions régulières sur la première page du document PDF. // Ouvrir le document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Créez l'objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Obtenir les résultats Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | Obtient le texte extrait que le {@code TextAbsorber} extrait du document PDF ou de la page. |
| [getTextEditOptions](#getTextEditOptions--) | Obtient les options de modification du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [getTextFragments](#getTextFragments--) | <p> Obtient la collection d'occurrences de recherche présentées avec des objets {@code TextFragment}. </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Obtient les options de remplacement du texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long. |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Obtient les options de recherche. Les options permettent la recherche à l'aide d'expressions régulières. </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | La valeur indique si des erreurs ont été trouvées lors de l'extraction du texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances. |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | Supprime tout le texte du document. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | Supprime tout le texte de la page spécifiée. |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Supprime le texte à l'intérieur du rectangle spécifié de la page spécifiée. |
| [reset](#reset--) | Efface la collection TextFragments de cet objet {@code TextFragmentAbsorber}. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Définit les options d'extraction du texte. |
| [setPhrase](#setPhrase-java.lang.String-) | <p> Définit la phrase que le {@code TextFragmentAbsorber} recherche dans le document PDF ou sur la page. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Définit les options de modification du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> Définit la collection d'occurrences de recherche présentées avec des objets {@code TextFragment}. </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Définit les options de remplacement du texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Définit les options de recherche. Les options permettent la recherche à l'aide d'expressions régulières. </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Effectue une recherche sur le document spécifié. </p> <hr> <pre> L'exemple montre comment trouver du texte dans un document PDF et remplacer le texte de toutes les occurrences de recherche. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour changer la police du texte du document Font font = FontRepository.findFont("Arial"); // Créez l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page absorber.visit(doc); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Effectue une recherche sur la page spécifiée. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Trouver la police qui sera utilisée pour changer la police du texte du document Font font = FontRepository.findFont("Arial"); // Créez l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page absorber.visit(doc.getPages().get(1)); // Modifier le texte de toutes les occurrences de recherche for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Enregistrer le document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | Effectue une recherche sur l'objet formulaire spécifié. |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> Initialise une nouvelle instance de {@code TextFragmentAbsorber} qui effectue la recherche de tous les segments de texte du document ou de la page. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection {@code TextFragmentAbsorber.TextFragments}. </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

Applique la taille de police à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire à une itération.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize |  | Taille de la police du texte. |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
Applique la police à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire à une itération.

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
Applique la police et la taille à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire à une itération.

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Liste d'objets {@code TextExtractionError}. Elle contient des informations sur les erreurs trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut réduire les performances.

**Returns:**
Liste d'objets TextExtractionError

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

Obtient les options d'extraction de texte.

**Returns:**
Objet TextExtractionOptions

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> Obtient la phrase que {@code TextFragmentAbsorber} recherche dans le document PDF ou la page. </p>

**Returns:**
Valeur de chaîne <hr> <pre> L'exemple montre comment effectuer plusieurs recherches de texte et réaliser des remplacements de texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello\"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( \"Hi\"); // search another word and replace it absorber.setPhrase ( \"world\"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( \"John\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

Obtient le dictionnaire des occurrences de recherche présentées avec la classe System.Text.RegularExpressions.Regex comme clé et {@link TextFragment} comme valeur. L'exemple montre comment trouver du texte avec un tableau d'expressions régulières sur la première page du document PDF. // Ouvrir le document Document doc = new Document("input.pdf"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Créez l'objet TextFragmentAbsorber qui recherche tous les mots commençant par 'h' et se terminant par 'o' en utilisant une expression régulière. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Obtenir les résultats Dictionary results = absorber.getRegexResults();

**Returns:**
Instance de Dictionary

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

Obtient le texte extrait que le {@code TextAbsorber} extrait du document PDF ou de la page.

**Returns:**
Valeur de chaîne L'exemple montre comment extraire le texte de toutes les pages du document PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Obtient les options de modification du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police.

**Returns:**
Objet TextEditOptions

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> Obtient la collection d'occurrences de recherche présentées avec des objets {@code TextFragment}. </p>

**Returns:**
Objet TextFragmentCollection <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer toutes les occurrences trouvées par du nouveau texte. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( \"hi world\"); } // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Obtient les options de remplacement du texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long.

**Returns:**
Valeur de TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Obtient les options de recherche. Les options permettent la recherche à l'aide d'expressions régulières. </p>

**Returns:**
Objet TextSearchOptions <hr> <pre> L'exemple montre comment effectuer une recherche de texte à l'aide d'une expression régulière. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // make the absorber to search all words starting 'h' and ending 'o' using regular expression. absorber.setPhrase ( \"h\\w*?o\"); absorber.setTextSearchOptions ( new TextSearchOptions(true)); // we should find \"hello\" word and replace it with \"Hi\" doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( \"Hi\"); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

La valeur indique si des erreurs ont été trouvées lors de l'extraction du texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances.

**Returns:**
valeur booléenne

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
Supprime tout le texte du document.

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
Supprime tout le texte de la page spécifiée.

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Supprime le texte à l'intérieur du rectangle spécifié de la page spécifiée.

### reset {#reset--}
```
public void reset()
```

Efface la collection TextFragments de cet objet {@code TextFragmentAbsorber}.

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
Définit les options d'extraction du texte.

### setPhrase {#setPhrase-java.lang.String-}
<p> Définit la phrase que le {@code TextFragmentAbsorber} recherche dans le document PDF ou sur la page. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Définit les options de modification du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police.

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> Définit la collection d'occurrences de recherche présentées avec des objets {@code TextFragment}. </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Définit les options de remplacement du texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Définit les options de recherche. Les options permettent la recherche à l'aide d'expressions régulières. </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Effectue une recherche sur le document spécifié. </p> <hr> <pre> L'exemple montre comment trouver du texte dans un document PDF et remplacer le texte de toutes les occurrences de recherche. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Appliquer l'absorbeur à la première page absorber.visit(doc); // Modifier le texte de la première occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Effectue une recherche sur la page spécifiée. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Trouver la police qui sera utilisée pour modifier la police du texte du document Font font = FontRepository.findFont("Arial"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Appliquer l'absorbeur à la première page absorber.visit(doc.getPages().get(1)); // Modifier le texte de toutes les occurrences de recherche for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
Effectue une recherche sur l'objet formulaire spécifié.
