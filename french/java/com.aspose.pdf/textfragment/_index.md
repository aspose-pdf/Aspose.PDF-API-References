---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente un fragment de texte PDF. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte ainsi que sa police. // Open document."
type: docs
weight: 5110
url: /fr/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> Représente un fragment de texte PDF. </p> <hr> <pre> L'exemple montre comment trouver du texte sur la première page du document PDF et remplacer le texte ainsi que sa police. // Open document Document doc = new Document("input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("output.pdf"); </pre> <hr> <pre> En quelques mots, l'objet {@code TextFragment} contient une liste d'objets {@code TextSegment}. En détail : Le texte du document PDF dans {@code com.aspose.pdf} est représenté par deux objets de base : {@code TextFragment} et {@code TextSegment} Les différences entre eux sont principalement dépendantes du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte "hello world" pour le manipuler, changer ses propriétés, etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> La représentation physique du texte PDF est très complexe. Le texte "hello world" peut être composé de plusieurs segments de texte physiquement indépendants. Le modèle de texte Aspose.Pdf établit essentiellement que l'objet {@code TextFragment} fournit un ensemble d'opérations logiques unique sur l'ensemble d'objets {@code TextSegment} physiques qui représente la requête de l'utilisateur. Dans le scénario de recherche de texte, {@code TextFragment} est la représentation logique du texte "hello world", et la collection d'objets {@code TextSegment} représente tous les segments physiques qui construisent l'objet texte "hello world". Ainsi, {@code TextFragment} se rapproche de la représentation logique du texte. Et {@code TextSegment} se rapproche de la représentation physique du texte. Évidemment, chaque objet {@code TextSegment} peut avoir sa propre police, couleur et propriétés de positionnement. {@code TextFragment} offre un moyen simple de modifier le texte avec ses propriétés : définir la police, la taille de police, la couleur de police, etc. Par ailleurs, les objets {@code TextSegment} sont accessibles et les utilisateurs peuvent manipuler les objets {@code TextSegment} de manière indépendante. <p> Notez que la modification des propriétés de TextFragment peut modifier la collection interne {@code Segments} car TextFragment est un objet agrégé et il peut réarranger les segments internes ou les fusionner en un seul segment. Si votre exigence est de laisser la collection {@code Segments} inchangée, veuillez modifier les segments internes individuellement. </p>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextFragment](#TextFragment--) | Initialise une nouvelle instance de l'objet {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-) | Initialise une nouvelle instance de l'objet {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Initialise une nouvelle instance de l'objet {@code TextFragment}. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | Initialise une nouvelle instance de l'objet {@code TextFragment}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clone le fragment avec tous les segments. |
| [deepClone](#deepClone--) | Clone le fragment. |
| [getBaselinePosition](#getBaselinePosition--) | Obtient la position du texte pour le texte, représenté par l'objet {@code TextFragment}. Le YIndent de la structure Position représente la coordonnée de ligne de base du fragment de texte. |
| [getEndNote](#getEndNote--) | Obtient la note de fin de paragraphe (pour la génération de PDF uniquement). |
| [getFootNote](#getFootNote--) | Obtient la note de bas de page du paragraphe (pour la génération de PDF uniquement). |
| [getForm](#getForm--) | Obtient l'objet formulaire qui contient le TextFragment. La valeur peut être nulle si l'objet TextFragment n'appartient à aucun formulaire. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtient un alignement horizontal du fragment de texte. |
| [getPage](#getPage--) | Obtient la page qui contient le TextFragment. La valeur peut être nulle si l'objet TextFragment n'appartient à aucune page. |
| [getPosition](#getPosition--) | <p> Obtient la position du texte pour le texte, représenté par l'objet {@code TextFragment}. </p> |
| [getRectangle](#getRectangle--) | Obtient le rectangle du TextFragment |
| [getReplaceOptions](#getReplaceOptions--) | Obtient les options de remplacement du texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long. |
| [getSegments](#getSegments--) | <p> Obtient les segments de texte pour le {@code TextFragment} actuel. </p> |
| [getText](#getText--) | <p> Obtient l'objet texte {@code string} que représente l'objet {@code TextFragment}. </p> |
| [getTextEditOptions](#getTextEditOptions--) | Obtient ou définit les options d'édition du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [getTextState](#getTextState--) | <p> Obtient ou définit l'état du texte pour le texte que représente l'objet {@code TextFragment}. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtient un alignement vertical du fragment de texte. |
| [getWrapLinesCount](#getWrapLinesCount--) | Obtient le nombre de lignes d'enveloppe pour ce paragraphe (pour la génération de PDF uniquement). |
| [isolateTextSegments](#isolateTextSegments-int-int-) | Obtient les {@code TextSegment}(s) représentant la partie spécifiée du texte {@code TextFragment}. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Définit la position du texte pour le texte, représenté par l'objet {@code TextFragment}. Le YIndent de la structure Position représente la coordonnée de ligne de base du fragment de texte. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | Définit la note de fin de paragraphe (pour la génération de PDF uniquement). |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | Définit la note de bas de page du paragraphe (pour la génération de PDF uniquement). |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit un alignement horizontal du fragment de texte. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Définit le lien hypertexte du fragment |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> Définit la position du texte pour le texte, représenté par l'objet {@code TextFragment}. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Obtient le rectangle du TextFragment |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Représenter la méthode setSegments |
| [setText](#setText-java.lang.String-) | <p> Définit l'objet texte {@code string} que représente l'objet {@code TextFragment}. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Obtient ou définit les options d'édition du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Définit un alignement vertical du fragment de texte. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | Définit le nombre de lignes d'enveloppe pour ce paragraphe (uniquement pour la génération de PDF) |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

Initialise une nouvelle instance de l'objet {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-}
Initialise une nouvelle instance de l'objet {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
Initialise une nouvelle instance de l'objet {@code TextFragment}.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
Initialise une nouvelle instance de l'objet {@code TextFragment}.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clone le fragment avec tous les segments.

**Returns:**
L'objet cloné

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone le fragment.

**Returns:**
L'objet cloné

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Obtient la position du texte pour le texte, représenté par l'objet {@code TextFragment}. Le YIndent de la structure Position représente la coordonnée de ligne de base du fragment de texte.

**Returns:**
Valeur de position

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

Obtient la note de fin de paragraphe (pour la génération de PDF uniquement).

**Returns:**
Valeur de la note

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

Obtient la note de bas de page du paragraphe (pour la génération de PDF uniquement).

**Returns:**
Valeur de la note

### getForm {#getForm--}
```
public XForm getForm()
```

Obtient l'objet formulaire qui contient le TextFragment. La valeur peut être nulle si l'objet TextFragment n'appartient à aucun formulaire.

**Returns:**
Valeur XForm

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtient un alignement horizontal du fragment de texte.

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

Obtient la page qui contient le TextFragment. La valeur peut être nulle si l'objet TextFragment n'appartient à aucune page.

**Returns:**
objet Page

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> Obtient la position du texte pour le texte, représenté par l'objet {@code TextFragment}. </p>

**Returns:**
Valeur de position <hr> <pre> L'exemple montre comment visualiser le placement d'un texte, représenté par l'objet {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // View text and placement info of first text occurrence TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle du TextFragment

**Returns:**
objet Rectangle

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

Obtient les options de remplacement du texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long.

**Returns:**
Instance de TextReplaceOptions

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> Obtient les segments de texte pour le {@code TextFragment} actuel. </p>

**Returns:**
Valeur de TextSegmentCollection <hr> <pre> L'exemple montre comment parcourir tous les objets {@code TextSegment} à l'intérieur de {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Navigate all text segments and out their text and placement info for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> En quelques mots, les objets {@code TextSegment} sont des enfants de l'objet {@code TextFragment}. Les utilisateurs avancés peuvent accéder directement aux segments pour réaliser des scénarios d'édition de texte plus complexes. Pour plus de détails, veuillez consulter la description de l'objet {@code TextFragment}. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> Obtient l'objet texte {@code string} que représente l'objet {@code TextFragment}. </p>

**Returns:**
Valeur de chaîne <hr> <pre> L'exemple montre comment rechercher un texte et remplacer la première occurrence représentée par l'objet {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

Obtient ou définit les options d'édition du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police.

**Returns:**
Instance de TextEditOptions

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> Obtient ou définit l'état du texte pour le texte que représente l'objet {@code TextFragment}. </p>

**Returns:**
Objet TextFragmentState <hr> <pre> L'exemple montre comment modifier la couleur du texte et la taille de police du texte avec l'objet {@code TextState}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Fournit un moyen de modifier les propriétés suivantes du texte : Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtient un alignement vertical du fragment de texte.

**Returns:**
Valeur int @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

Obtient le nombre de lignes d'enveloppe pour ce paragraphe (pour la génération de PDF uniquement).

**Returns:**
valeur int

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

Obtient les {@code TextSegment}(s) représentant la partie spécifiée du texte {@code TextFragment}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex |  | Position dans le texte à partir de laquelle les nouveaux {@code TextSegment}(s) commenceront. |
| longueur |  | Longueur du texte qui sera isolé dans les {@code TextSegment}(s). |

**Returns:**
{@code TextSegmentCollection} contenant des segments de texte représentant une sous‑chaîne de texte commençant à une position spécifiée et ayant une longueur spécifiée.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Définit la position du texte pour le texte, représenté par l'objet {@code TextFragment}. Le YIndent de la structure Position représente la coordonnée de ligne de base du fragment de texte.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
Définit la note de fin de paragraphe (pour la génération de PDF uniquement).

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
Définit la note de bas de page du paragraphe (pour la génération de PDF uniquement).

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit un alignement horizontal du fragment de texte.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Définit le lien hypertexte du fragment

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> Définit la position du texte pour le texte, représenté par l'objet {@code TextFragment}. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Obtient le rectangle du TextFragment

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
Représenter la méthode setSegments

### setText {#setText-java.lang.String-}
<p> Définit l'objet texte {@code string} que représente l'objet {@code TextFragment}. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Obtient ou définit les options d'édition du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Définit un alignement vertical du fragment de texte.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

Définit le nombre de lignes d'enveloppe pour ce paragraphe (uniquement pour la génération de PDF)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
