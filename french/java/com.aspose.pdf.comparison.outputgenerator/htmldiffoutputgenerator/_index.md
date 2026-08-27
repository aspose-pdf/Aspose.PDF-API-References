---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour générer une représentation HTML des différences de texte. Les sauts de ligne supprimés sont indiqués par le signe - paragraphe."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Représente une classe pour générer une représentation HTML des différences de texte. Les sauts de ligne supprimés sont indiqués par le signe - paragraphe.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Crée une instance de la classe {@link HtmlDiffOutputGenerator}. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Crée une instance de la classe {@link HtmlDiffOutputGenerator}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [generateOutput1](#generateOutput1-java.util.List-) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Méthode interne |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Obtient et définit la chaîne de style CSS pour l'opération Delete. Exemple : color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Obtient et définit la chaîne de style CSS pour l'opération Equal. Exemple : color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Obtient et définit la chaîne de style CSS pour l'opération Insert. Exemple : color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Obtenez ou définissez le style text-decoration: line-through pour l'opération delete. La valeur par défaut est {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Obtient et définit la chaîne de style CSS pour l'opération Delete. Exemple : color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Obtient et définit la chaîne de style CSS pour l'opération Equal. Exemple : color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Obtient et définit la chaîne de style CSS pour l'opération Insert. Exemple : color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Obtenez ou définissez le style text-decoration: line-through pour l'opération delete. La valeur par défaut est {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Crée une instance de la classe {@link HtmlDiffOutputGenerator}.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Crée une instance de la classe {@link HtmlDiffOutputGenerator}.

### generateOutput {#generateOutput-java.util.List-}
Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier.

### generateOutput1 {#generateOutput1-java.util.List-}
Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Méthode interne

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Obtient et définit la chaîne de style CSS pour l'opération Delete. Exemple : color: #003300; background-color: #ccff66;

**Returns:**
valeur String

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Obtient et définit la chaîne de style CSS pour l'opération Equal. Exemple : color: #003300; background-color: #ccff66;

**Returns:**
valeur String

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Obtient et définit la chaîne de style CSS pour l'opération Insert. Exemple : color: #003300; background-color: #ccff66;

**Returns:**
valeur String

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Obtenez ou définissez le style text-decoration: line-through pour l'opération delete. La valeur par défaut est {@code False}.

**Returns:**
valeur booléenne

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Obtient et définit la chaîne de style CSS pour l'opération Delete. Exemple : color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Obtient et définit la chaîne de style CSS pour l'opération Equal. Exemple : color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Obtient et définit la chaîne de style CSS pour l'opération Insert. Exemple : color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Obtenez ou définissez le style text-decoration: line-through pour l'opération delete. La valeur par défaut est {@code False}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
