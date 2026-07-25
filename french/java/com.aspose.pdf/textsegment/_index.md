---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente un segment de texte PDF. </p> <hr> <pre> L'exemple montre comment changer la couleur du texte et la taille de police du texte avec l'objet {@code TextState} de {@code"
type: docs
weight: 5300
url: /fr/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Représente un segment de texte PDF. </p> <hr> <pre> L'exemple montre comment modifier la couleur du texte et la taille de police du texte avec l'objet {@code TextState} de l'objet {@code TextSegment}. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get(1).accept(absorber); // Modifier la couleur de premier plan du premier segment de texte de la première occurrence de texte absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Modifier la taille de police du premier segment de texte de la première occurrence de texte absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> En quelques mots, les objets {@code TextSegment} sont des enfants de l'objet {@code TextFragment}. En détail : Le texte d'un document PDF dans {@code Aspose.Pdf} est représenté par deux objets de base : {@code TextFragment} et {@code TextSegment} Les différences entre eux sont principalement dépendantes du contexte. Considérons le scénario suivant. L'utilisateur recherche le texte \"hello world\" pour le manipuler, modifier ses propriétés, etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> La représentation physique du texte PDF est très complexe. Le texte \"hello world\" peut être composé de plusieurs segments de texte physiquement indépendants. Le modèle de texte Aspose.PDF établit essentiellement que l'objet {@code TextFragment} fournit un ensemble d'opérations logiques unique sur l'ensemble d'objets {@code TextSegment} physiques qui représentent la requête de l'utilisateur. Dans le scénario de recherche de texte, {@code TextFragment} est la représentation logique du texte \"hello world\", et la collection d'objets {@code TextSegment} représente tous les segments physiques qui constituent l'objet texte \"hello world\". Ainsi, {@code TextFragment} se rapproche de la représentation logique du texte. Et {@code TextSegment} se rapproche de la représentation physique du texte. Évidemment, chaque objet {@code TextSegment} peut avoir sa propre police, couleur et propriétés de positionnement. {@code TextFragment} offre un moyen simple de modifier le texte avec ses propriétés : définir la police, la taille de police, la couleur de police, etc. Pendant ce temps, les objets {@code TextSegment} sont accessibles et les utilisateurs peuvent manipuler les objets {@code TextSegment} de manière indépendante. </p>

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> Crée l'objet TextSegment. </p> <hr> <pre> L'exemple montre comment créer un objet fragment de texte, ajouter un segment de texte à la collection de fragments de texte et l'ajouter à la page Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> Crée l'objet TextSegment. </p> <hr> <pre> L'exemple montre comment créer un objet fragment de texte, ajouter un segment de texte à la collection de fragments de texte et l'ajouter à la page Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | Obtient la position du texte, représentée par l'objet {@code TextSegment}. Le YIndent de la structure Position représente la coordonnée de la ligne de base du segment de texte. |
| [getCharacters](#getCharacters--) | Obtient la collection d'objets CharInfo qui représentent les informations sur les caractères du segment de texte. |
| [getEndCharIndex](#getEndCharIndex--) | Obtient l'index du caractère de fin du segment actuel dans l'opérateur d'affichage du texte (Tj, TJ). |
| [getHyperlink](#getHyperlink--) | Obtient ou définit le lien hypertexte du segment (pour le générateur PDF). |
| [getPosition](#getPosition--) | Obtient la position du texte, représentée par l'objet {@code TextSegment}. |
| [getRectangle](#getRectangle--) | Obtient le rectangle du TextSegment |
| [getStartCharIndex](#getStartCharIndex--) | Obtient l'index du caractère de début du segment actuel dans l'opérateur d'affichage du texte (Tj, TJ). |
| [getText](#getText--) | Obtient l'objet texte {@code string} que représente l'objet {@code TextSegment}. |
| [getTextEditOptions](#getTextEditOptions--) | Obtient les options de modification du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [getTextState](#getTextState--) | <p> Obtient ou définit l'état du texte pour le texte que représente l'objet {@code TextSegment}. </p> <hr> <p> Fournit un moyen de modifier les propriétés suivantes du texte : Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Définit la position du texte, représentée par l'objet {@code TextSegment}. Le YIndent de la structure Position représente la coordonnée de la ligne de base du segment de texte. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Obtient ou définit le lien hypertexte du segment (pour le générateur PDF). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Définit la position du texte, représentée par l'objet {@code TextSegment}. |
| [setText](#setText-java.lang.String-) | Définit l'objet texte {@code string} que représente l'objet {@code TextSegment}. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Définit les options de modification du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> Définit l'état du texte pour le texte que représente l'objet {@code TextSegment}. </p> <hr> <p> Fournit un moyen de modifier les propriétés suivantes du texte : Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | Définit l'objet texte {@code string} que représente l'objet {@code TextSegment} avec mise à jour supprimée. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> Crée l'objet TextSegment. </p> <hr> <pre> L'exemple montre comment créer un objet fragment de texte, ajouter un segment de texte à la collection de fragments de texte et l'ajouter à la page Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> Crée l'objet TextSegment. </p> <hr> <pre> L'exemple montre comment créer un objet fragment de texte, ajouter un segment de texte à la collection de fragments de texte et l'ajouter à la page Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Obtient la position du texte, représentée par l'objet {@code TextSegment}. Le YIndent de la structure Position représente la coordonnée de la ligne de base du segment de texte.

**Returns:**
Valeur de position

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

Obtient la collection d'objets CharInfo qui représentent les informations sur les caractères du segment de texte.

**Returns:**
Objet CharInfoCollection

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

Obtient l'index du caractère de fin du segment actuel dans l'opérateur d'affichage du texte (Tj, TJ).

**Returns:**
valeur int

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

Obtient ou définit le lien hypertexte du segment (pour le générateur PDF).

**Returns:**
Objet Hyperlink

### getPosition {#getPosition--}
```
public Position getPosition()
```

Obtient la position du texte, représentée par l'objet {@code TextSegment}.

**Returns:**
Valeur de position

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle du TextSegment

**Returns:**
objet Rectangle

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

Obtient l'index du caractère de début du segment actuel dans l'opérateur d'affichage du texte (Tj, TJ).

**Returns:**
valeur int

### getText {#getText--}
```
public String getText()
```

Obtient l'objet texte {@code string} que représente l'objet {@code TextSegment}.

**Returns:**
valeur String

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Obtient les options de modification du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police.

**Returns:**
Valeur TextEditOptions

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> Obtient ou définit l'état du texte pour le texte que représente l'objet {@code TextSegment}. </p> <hr> <p> Fournit un moyen de modifier les propriétés suivantes du texte : Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
Valeur TextState

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Définit la position du texte, représentée par l'objet {@code TextSegment}. Le YIndent de la structure Position représente la coordonnée de la ligne de base du segment de texte.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Obtient ou définit le lien hypertexte du segment (pour le générateur PDF).

### setPosition {#setPosition-com.aspose.pdf.Position-}
Définit la position du texte, représentée par l'objet {@code TextSegment}.

### setText {#setText-java.lang.String-}
Définit l'objet texte {@code string} que représente l'objet {@code TextSegment}.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Définit les options de modification du texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> Définit l'état du texte pour le texte que représente l'objet {@code TextSegment}. </p> <hr> <p> Fournit un moyen de modifier les propriétés suivantes du texte : Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
Définit l'objet texte {@code string} que représente l'objet {@code TextSegment} avec mise à jour supprimée.
