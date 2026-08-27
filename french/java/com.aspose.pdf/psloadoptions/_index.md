---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de chargement/importation du fichier .mht dans un document PDF."
type: docs
weight: 4060
url: /fr/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

Représente les options de chargement/importation du fichier .mht dans un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | Crée des options de chargement pour convertir du PostScript en document PDF avec un chemin de base vide. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | Obtient les chemins des dossiers de polices. Les dossiers contenant des polices supplémentaires pour la conversion. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | Spécifie s'il faut enregistrer les polices non TrueType au format TTF. Cela réduit considérablement le volume du document résultant lors de la conversion PS vers PDF et augmente la vitesse de conversion des fichiers PS contenant une grande quantité de texte en polices non TrueType vers n'importe quel format de sortie. Cependant, il y a un léger décalage vertical du texte lors de la conversion d'un fichier PostScript en image. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | Spécifie s'il faut enregistrer les polices non TrueType au format TTF. Cela réduit considérablement le volume du document résultant lors de la conversion PS vers PDF et augmente la vitesse de conversion des fichiers PS contenant une grande quantité de texte en polices non TrueType vers n'importe quel format de sortie. Cependant, il y a un léger décalage vertical du texte lors de la conversion d'un fichier PostScript en image. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | Définit les chemins des dossiers de polices. Les dossiers contenant des polices supplémentaires pour la conversion. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

Crée des options de chargement pour convertir du PostScript en document PDF avec un chemin de base vide.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

Obtient les chemins des dossiers de polices. Les dossiers contenant des polices supplémentaires pour la conversion.

**Returns:**
tableau de valeurs String

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

Spécifie s'il faut enregistrer les polices non TrueType au format TTF. Cela réduit considérablement le volume du document résultant lors de la conversion PS vers PDF et augmente la vitesse de conversion des fichiers PS contenant une grande quantité de texte en polices non TrueType vers n'importe quel format de sortie. Cependant, il y a un léger décalage vertical du texte lors de la conversion d'un fichier PostScript en image.

**Returns:**
valeur booléenne

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

Spécifie s'il faut enregistrer les polices non TrueType au format TTF. Cela réduit considérablement le volume du document résultant lors de la conversion PS vers PDF et augmente la vitesse de conversion des fichiers PS contenant une grande quantité de texte en polices non TrueType vers n'importe quel format de sortie. Cependant, il y a un léger décalage vertical du texte lors de la conversion d'un fichier PostScript en image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
Définit les chemins des dossiers de polices. Les dossiers contenant des polices supplémentaires pour la conversion.
