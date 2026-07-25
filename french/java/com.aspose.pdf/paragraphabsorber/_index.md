---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente un objet absorbeur des objets de structure de page tels que les sections et les paragraphes. Effectue la recherche de sections et de paragraphes de texte et fournit un accès pour.</p>"
type: docs
weight: 3470
url: /fr/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> Représente un objet absorbeur des objets de structure de page tels que les sections et les paragraphes. Effectue une recherche de sections et de paragraphes de texte et fournit un accès aux rectangles et aux polygones qui les décrivent dans l'espace de coordonnées du texte. Effectue également une recherche de segments de texte et fournit un accès aux résultats de recherche via les collections {@code TextFragments} regroupées par éléments de structure. </p> L'exemple montre comment trouver le premier segment de texte de chaque paragraphe sur la première page du document PDF et le mettre en surbrillance. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Lorsque la recherche est terminée, la collection {@code ParagraphAbsorber.PageMarkups} contiendra des objets {@code PageMarkup} qui représentent la structure de la page par des collections de {@code MarkupSection} et {@code MarkupParagraph}. L'objet {@code TextFragment} fournit un accès au texte de l'occurrence recherchée, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc.).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | Initialise une nouvelle instance de {@code ParagraphAbsorber} qui effectue la recherche de sections/paragraphes du document ou de la page. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> Initialise une nouvelle instance de {@code ParagraphAbsorber} qui effectue la recherche de sections/paragraphes du document ou de la page. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | Initialise une nouvelle instance de {@code ParagraphAbsorber} qui effectue la recherche de sections/paragraphes du document ou de la page. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | Initialise une nouvelle instance de {@code ParagraphAbsorber} qui effectue la recherche de sections/paragraphes du document ou de la page. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | Obtient la collection de {@code PageMarkup} qui ont été absorbés. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | Obtient les ParagraphAbsorberOptions. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles pour des éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour celles divisées verticalement (colonnes). </p><hr> L'augmentation de cette valeur peut entraîner une légère diminution des performances sans changements visibles dans le résultat de la recherche. La diminution de cette valeur peut conduire à une détermination incorrecte des paragraphes dans les sections. Nous ne recommandons pas de définir une valeur inférieure à la valeur par défaut si vous ne souhaitez obtenir que des éléments « rough » de la structure de la page. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Obtient ou définit les TextReplaceOptions. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | Définit les ParagraphAbsorberOptions. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles pour des éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour celles divisées verticalement (colonnes). </p><hr> L'augmentation de cette valeur peut entraîner une légère diminution des performances sans changements visibles dans le résultat de la recherche. La diminution de cette valeur peut conduire à une détermination incorrecte des paragraphes dans les sections. Nous ne recommandons pas de définir une valeur inférieure à la valeur par défaut si vous ne souhaitez obtenir que des éléments « rough » de la structure de la page. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Obtient ou définit les TextReplaceOptions. |
| [visit](#visit-com.aspose.pdf.Document-) | Effectue la recherche de sections et de paragraphes sur le {@link Document} spécifié. |
| [visit](#visit-com.aspose.pdf.Page-) | Effectue la recherche sur la {@code Page} spécifiée. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

Initialise une nouvelle instance de {@code ParagraphAbsorber} qui effectue la recherche de sections/paragraphes du document ou de la page.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> Initialise une nouvelle instance de {@code ParagraphAbsorber} qui effectue la recherche de sections/paragraphes du document ou de la page. </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sectionsSearchDepth |  | Nombre de recherches séquentielles pour des éléments de structure plus fins qui seront effectuées. <hr> Voir la propriété {@code ParagraphAbsorber.SectionsSearchDepth} pour plus d'indications sur le paramètre. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
Initialise une nouvelle instance de {@code ParagraphAbsorber} qui effectue la recherche de sections/paragraphes du document ou de la page.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
Initialise une nouvelle instance de {@code ParagraphAbsorber} qui effectue la recherche de sections/paragraphes du document ou de la page.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

Obtient la collection de {@code PageMarkup} qui ont été absorbés.

**Returns:**
Liste d'instances PageMarkup

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

Obtient les ParagraphAbsorberOptions.

**Returns:**
Instance de ParagraphAbsorberOptions

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles pour des éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour celles divisées verticalement (colonnes). </p><hr> L'augmentation de cette valeur peut entraîner une légère diminution des performances sans changements visibles dans le résultat de la recherche. La diminution de cette valeur peut conduire à une détermination incorrecte des paragraphes dans les sections. Nous ne recommandons pas de définir une valeur inférieure à la valeur par défaut si vous ne souhaitez obtenir que des éléments « rough » de la structure de la page.

**Returns:**
valeur int

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

Obtient ou définit les TextReplaceOptions.

**Returns:**
Instance de TextReplaceOptions

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente.

**Returns:**
valeur booléenne

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
Définit les ParagraphAbsorberOptions.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles pour des éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour celles divisées verticalement (colonnes). </p><hr> L'augmentation de cette valeur peut entraîner une légère diminution des performances sans changements visibles dans le résultat de la recherche. La diminution de cette valeur peut conduire à une détermination incorrecte des paragraphes dans les sections. Nous ne recommandons pas de définir une valeur inférieure à la valeur par défaut si vous ne souhaitez obtenir que des éléments « rough » de la structure de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Obtient ou définit les TextReplaceOptions.

### visit {#visit-com.aspose.pdf.Document-}
Effectue la recherche de sections et de paragraphes sur le {@link Document} spécifié.

### visit {#visit-com.aspose.pdf.Page-}
Effectue la recherche sur la {@code Page} spécifiée.
