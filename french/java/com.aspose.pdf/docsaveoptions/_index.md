---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Options d'enregistrement pour l'exportation au format Doc"
type: docs
weight: 1030
url: /fr/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Options d'enregistrement pour l'exportation au format Doc

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Ce gestionnaire peut être utilisé pour gérer les événements de progression de conversion, par exemple il peut être utilisé pour afficher une barre de progression ou des messages concernant le nombre actuel de pages traitées, un exemple de code du gestionnaire qui affiche la progression sur la console est : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | Obtenir le format de sortie |
| [getImageResolutionX](#getImageResolutionX--) | Résolution X des images converties. |
| [getImageResolutionY](#getImageResolutionY--) | Résolution Y des images converties. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | Ce paramètre est utilisé pour regrouper les lignes de texte en paragraphes. Détermine à quelle distance peuvent être séparées deux lignes de texte relatives. Spécifié en centaines de pour cent de la hauteur des lignes de texte. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | Définit le chemin (nom de fichier ou nom de répertoire) pour stocker les données temporaires lors de la conversion en mode d'enregistrement en mémoire. |
| [getMode](#getMode--) | Mode de reconnaissance. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | Dans les PDF, les mots peuvent être représentés en interne par des opérateurs qui affichent les mots en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter les mots, il faut parfois détecter des groupes de caractères indépendants qui sont en fait des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) qui doit être considéré comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source. (la présence d'un espace vide d'au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents). Il est normalisé à la taille de la police : 1,0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne modifie rien dans le document résultant. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | Est utilisé pour les sauts de paragraphe ou de ligne. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Obtient ou définit la conversion pour les polices Type3. Dans les polices Type 3, les glyphes sont définis par des flux d'opérateurs graphiques. Cela signifie que dans la sortie DOC/DOCX nous voyons des images au lieu du texte. Définissez ce drapeau sur true pour convertir les polices Type3 en TTF et obtenir du texte dans le fichier résultant. |
| [isRecognizeBullets](#isRecognizeBullets--) | Active la reconnaissance des puces. |
| [isReSaveFonts](#isReSaveFonts--) | Obtient ou définit la procédure de resauvegarde des polices. Si elle est définie sur true, nous rechargeons les polices à chaque page pour éviter l'influence des propriétés de police précédentes et charger la police nouvellement créée à partir de zéro. Définissez cette option sur false si vous souhaitez améliorer les performances. La valeur par défaut est true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | Utiliser les sauts de paragraphe ou de ligne |
| [setBatchSize](#setBatchSize-int-) | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Obtient ou définit la conversion pour les polices Type3. Dans les polices Type 3, les glyphes sont définis par des flux d'opérateurs graphiques. Cela signifie que dans la sortie DOC/DOCX nous voyons des images au lieu du texte. Définissez ce drapeau sur true pour convertir les polices Type3 en TTF et obtenir du texte dans le fichier résultant. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | Définir le format de sortie |
| [setImageResolutionX](#setImageResolutionX-int-) | Résolution X des images converties. |
| [setImageResolutionY](#setImageResolutionY-int-) | Résolution Y des images converties. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | Ce paramètre est utilisé pour regrouper les lignes de texte en paragraphes. Détermine à quelle distance peuvent être séparées deux lignes de texte relatives. Spécifié en centaines de pour cent de la hauteur des lignes de texte. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | Définit le chemin (nom de fichier ou nom de répertoire) pour stocker les données temporaires lors de la conversion en mode d'enregistrement en mémoire. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | Mode de reconnaissance. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | Active la reconnaissance des puces. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | Dans les PDF, les mots peuvent être représentés en interne par des opérateurs qui affichent les mots en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter les mots, il faut parfois détecter des groupes de caractères indépendants qui sont en fait des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) qui doit être considéré comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source. (la présence d'un espace vide d'au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents). Il est normalisé à la taille de la police : 1,0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne modifie rien dans le document résultant. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | Obtient ou définit la procédure de resauvegarde des polices. Si elle est définie sur true, nous rechargeons les polices à chaque page pour éviter l'influence des propriétés de police précédentes et charger la police nouvellement créée à partir de zéro. Définissez cette option sur false si vous souhaitez améliorer les performances. La valeur par défaut est true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

Constructeur

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination.

**Returns:**
valeur int

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Ce gestionnaire peut être utilisé pour gérer les événements de progression de conversion, par ex. il peut être utilisé pour afficher une barre de progression ou des messages concernant le nombre actuel de pages traitées, exemple de code du gestionnaire qui affiche la progression dans la console est : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
Instance ConversionProgressEventHandler

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

Obtenir le format de sortie

**Returns:**
Élément DocFormat @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

Résolution X des images converties.

**Returns:**
valeur int

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

Résolution Y des images converties.

**Returns:**
valeur int

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

Ce paramètre est utilisé pour regrouper les lignes de texte en paragraphes. Détermine à quelle distance peuvent être séparées deux lignes de texte relatives. Spécifié en centaines de pour cent de la hauteur des lignes de texte.

**Returns:**
Valeur flottante

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

Définit le chemin (nom de fichier ou nom de répertoire) pour stocker les données temporaires lors de la conversion en mode d'enregistrement en mémoire.

**Returns:**
valeur String

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

Mode de reconnaissance.

**Returns:**
Valeur RecognitionMode @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

Dans les PDF, les mots peuvent être représentés en interne par des opérateurs qui affichent les mots en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter les mots, il faut parfois détecter des groupes de caractères indépendants qui sont en fait des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) qui doit être considéré comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source. (la présence d'un espace vide d'au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents). Il est normalisé à la taille de la police : 1,0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne modifie rien dans le document résultant.

**Returns:**
Proximité relative

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

Est utilisé pour les sauts de paragraphe ou de ligne.

**Returns:**
valeur booléenne.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Obtient ou définit la conversion pour les polices Type3. Dans les polices Type 3, les glyphes sont définis par des flux d'opérateurs graphiques. Cela signifie que dans la sortie DOC/DOCX nous voyons des images au lieu du texte. Définissez ce drapeau sur true pour convertir les polices Type3 en TTF et obtenir du texte dans le fichier résultant.

**Returns:**
valeur booléenne

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

Active la reconnaissance des puces.

**Returns:**
valeur booléenne

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

Obtient ou définit la procédure de resauvegarde des polices. Si elle est définie sur true, nous rechargeons les polices à chaque page pour éviter l'influence des propriétés de police précédentes et charger la police nouvellement créée à partir de zéro. Définissez cette option sur false si vous souhaitez améliorer les performances. La valeur par défaut est true;

**Returns:**
valeur booléenne

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

Utiliser les sauts de paragraphe ou de ligne

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Obtient ou définit la conversion pour les polices Type3. Dans les polices Type 3, les glyphes sont définis par des flux d'opérateurs graphiques. Cela signifie que dans la sortie DOC/DOCX nous voyons des images au lieu du texte. Définissez ce drapeau sur true pour convertir les polices Type3 en TTF et obtenir du texte dans le fichier résultant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
Définir le format de sortie

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

Résolution X des images converties.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

Résolution Y des images converties.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

Ce paramètre est utilisé pour regrouper les lignes de texte en paragraphes. Détermine à quelle distance peuvent être séparées deux lignes de texte relatives. Spécifié en centaines de pour cent de la hauteur des lignes de texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
Définit le chemin (nom de fichier ou nom de répertoire) pour stocker les données temporaires lors de la conversion en mode d'enregistrement en mémoire.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
Mode de reconnaissance.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

Active la reconnaissance des puces.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

Dans les PDF, les mots peuvent être représentés en interne par des opérateurs qui affichent les mots en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter les mots, il faut parfois détecter des groupes de caractères indépendants qui sont en fait des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) qui doit être considéré comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source. (la présence d'un espace vide d'au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents). Il est normalisé à la taille de la police : 1,0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne modifie rien dans le document résultant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Proximité relative |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

Obtient ou définit la procédure de resauvegarde des polices. Si elle est définie sur true, nous rechargeons les polices à chaque page pour éviter l'influence des propriétés de police précédentes et charger la police nouvellement créée à partir de zéro. Définissez cette option sur false si vous souhaitez améliorer les performances. La valeur par défaut est true;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
