---
title: "Police"
linktitle: "Police"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente l'objet police. </p> <hr> <pre> L'exemple montre comment rechercher du texte sur la première page et modifier la police de la première occurrence recherchée. // Open document Document doc."
type: docs
weight: 1650
url: /fr/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> Représente l'objet police. </p> <hr> <pre> L'exemple montre comment rechercher du texte sur la première page et modifier la police de la première occurrence trouvée. // Ouvrir le document Document doc = new Document(\"input.pdf\"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences du texte \"hello world\" // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Créer la police et la marquer pour être incorporée Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Modifier la police de la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Enregistrer le document doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## Méthodes

| Méthode | Description |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | Détermine si la police contient les caractères spécifiés |
| [getActualFontName](#getActualFontName--) | <p> Obtient le nom réel de la police de l'objet {@code Font} s'il est initialisé. Même lorsque la police est substituée ou possède un nom interne pour le pdf. Ou une chaîne vide si la police n'est pas initialisée. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | Mesure le point d'ascension maximal. |
| [getBaseFont](#getBaseFont--) | Obtient la valeur BaseFont de l'objet police PDF. Aussi connue sous le nom de nom PostScript de la police. |
| [getDecodedFontName](#getDecodedFontName--) | Parfois, les polices PDF (généralement les polices chinoises/japonaises/coréennes) peuvent avoir un nom de police spécifique. Ce nom est la valeur de la propriété PDF de police "BaseFont" et parfois cette propriété peut être représentée sous forme hexadécimale. Si l'on lit ce nom directement, il peut apparaître sous une forme non lisible. Pour obtenir une forme lisible, il est nécessaire de décoder le nom de la police selon les règles spécifiques à cette police. Cette propriété renvoie le nom de police décodé, utilisez‑la donc dans les cas où vous rencontrez un {@code FontName} non lisible. Si la propriété {@code FontName} a une forme lisible, cette propriété sera identique à {@code FontName}, vous pouvez donc l'utiliser dans tous les cas où vous devez obtenir le nom de la police sous une forme lisible. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | Mesure le point de descente maximal. |
| [getFontName](#getFontName--) | <p> Obtient le nom de la police de l'objet {@code Font}. </p> |
| [getFontOptions](#getFontOptions--) | Propriétés utiles pour ajuster le comportement des polices |
| [getIFont](#getIFont--) | <p> Objet police système. </p> <hr> <p> À usage interne uniquement </p> |
| [getIPdfFont](#getIPdfFont--) | <p> Objet police PDF. </p> <hr> <p> À usage interne uniquement </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | Un objectif de cette méthode - renvoyer la description de l'erreur si une tentative d'intégration de la police a échoué. S'il n'y a aucun cas d'erreur, elle renvoie une chaîne vide. |
| [getType](#getType--) | Le nom du type de police |
| [isAccessible](#isAccessible--) | <p> Obtient une indication si la police est présente (installée) dans le système. </p> |
| [isEmbedded](#isEmbedded--) | <p> Obtient une valeur indiquant si la police est intégrée. Une police basée sur IFont sera automatiquement sous‑ensemble et intégrée </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> Obtient une valeur indiquant si la police est un sous‑ensemble. Une police basée sur IFont sera automatiquement sous‑ensemble et intégrée </p> <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | Mesure la chaîne. |
| [save](#save-java.io.OutputStream-) | Enregistre la police dans le flux. Notez que la police est enregistrée au format TTF intermédiaire destiné à être utilisé uniquement dans une copie convertie du document original. Le fichier de police n'est pas destiné à être utilisé en dehors du contexte du document original. |
| [setEmbedded](#setEmbedded-boolean-) | Définit une valeur indiquant si la police est intégrée. Une police basée sur IFont sera automatiquement sous‑ensemble et intégrée |
| [setSubset](#setSubset-boolean-) | Définit une valeur indiquant si la police est un sous‑ensemble. Une police basée sur IFont sera automatiquement sous‑ensemble et intégrée |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
Détermine si la police contient les caractères spécifiés

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> Obtient le nom réel de la police de l'objet {@code Font} s'il est initialisé. Même lorsque la police est substituée ou possède un nom interne pour le pdf. Ou une chaîne vide si la police n'est pas initialisée. </p>

**Returns:**
Valeur chaîne <hr> <pre> L'exemple montre comment rechercher du texte sur la première page et afficher le nom réel de la police de la première occurrence de texte. // Ouvrir le document Document doc = new Document(@"D:\Tests\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Afficher le nom réel de la police de la première occurrence de texte System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
Mesure le point d'ascension maximal.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

Obtient la valeur BaseFont de l'objet police PDF. Aussi connue sous le nom de nom PostScript de la police.

**Returns:**
valeur String

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

Parfois, les polices PDF (généralement les polices chinoises/japonaises/coréennes) peuvent avoir un nom de police spécifique. Ce nom est la valeur de la propriété PDF de police "BaseFont" et parfois cette propriété peut être représentée sous forme hexadécimale. Si l'on lit ce nom directement, il peut apparaître sous une forme non lisible. Pour obtenir une forme lisible, il est nécessaire de décoder le nom de la police selon les règles spécifiques à cette police. Cette propriété renvoie le nom de police décodé, utilisez‑la donc dans les cas où vous rencontrez un {@code FontName} non lisible. Si la propriété {@code FontName} a une forme lisible, cette propriété sera identique à {@code FontName}, vous pouvez donc l'utiliser dans tous les cas où vous devez obtenir le nom de la police sous une forme lisible.

**Returns:**
valeur String

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
Mesure le point de descente maximal.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> Obtient le nom de la police de l'objet {@code Font}. </p>

**Returns:**
Valeur chaîne <hr> <pre> L'exemple montre comment rechercher du texte sur la première page et afficher le nom de la police de la première occurrence de texte. // Ouvrir le document Document doc = new Document(@"D:\Tests\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Afficher le nom de la police de la première occurrence de texte System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

Propriétés utiles pour ajuster le comportement des polices

**Returns:**
Objet IFontOptions

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> Objet police système. </p> <hr> <p> À usage interne uniquement </p>

**Returns:**
Objet IFont

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> Objet police PDF. </p> <hr> <p> À usage interne uniquement </p>

**Returns:**
Objet IPdfFont

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

Un objectif de cette méthode - renvoyer la description de l'erreur si une tentative d'intégration de la police a échoué. S'il n'y a aucun cas d'erreur, elle renvoie une chaîne vide.

**Returns:**
Description de l'erreur

### getType {#getType--}
```
public String getType()
```

Le nom du type de police

**Returns:**
Objet String

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> Obtient une indication si la police est présente (installée) dans le système. </p>

**Returns:**
Valeur booléenne <hr> <pre> L'exemple montre comment rechercher du texte sur la première page et obtenir la valeur indiquant si la police est installée dans le système. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Afficher la valeur IsSubset de la police de la première occurrence de texte if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println("la police est installée dans le système"); </pre> <hr> <p> Certaines opérations ne sont pas disponibles avec les polices qui n'ont pas pu être trouvées dans le système. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> Obtient une valeur indiquant si la police est incorporée. La police basée sur IFont sera automatiquement sous-ensemble et incorporée </p> <hr> <pre> L'exemple suivant montre comment trouver une police, la marquer comme incorporée, rechercher du texte sur la page du document et remplacer la police du texte. // Créer la police et la marquer comme incorporée com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // ouvrir le document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf"); // créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world" com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // changer la police pour la première occurrence de texte absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // enregistrer le document doc.save("D:\\Tests\\output.pdf"); </pre>

**Returns:**
Valeur booléenne @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> Obtient une valeur indiquant si la police est un sous-ensemble. La police basée sur IFont sera automatiquement sous-ensemble et incorporée </p> <hr> <pre> L'exemple montre comment rechercher du texte sur la première page et obtenir la valeur indiquant si la police est un sous-ensemble. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet TextFragmentAbsorber pour trouver toutes les occurrences de texte "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(absorber); // Afficher la valeur IsSubset de la police de la première occurrence de texte if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("la police est un sous-ensemble"); </pre>

**Returns:**
Valeur booléenne @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
Mesure la chaîne.

### save {#save-java.io.OutputStream-}
Enregistre la police dans le flux. Notez que la police est enregistrée au format TTF intermédiaire destiné à être utilisé uniquement dans une copie convertie du document original. Le fichier de police n'est pas destiné à être utilisé en dehors du contexte du document original.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

Définit une valeur indiquant si la police est intégrée. Une police basée sur IFont sera automatiquement sous‑ensemble et intégrée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

Définit une valeur indiquant si la police est un sous‑ensemble. Une police basée sur IFont sera automatiquement sous‑ensemble et intégrée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
