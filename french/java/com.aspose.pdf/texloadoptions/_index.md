---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de chargement/importation d'un fichier TeX dans un document PDF."
type: docs
weight: 4870
url: /fr/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

Représente les options de chargement/importation d'un fichier TeX dans un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | Crée les options de chargement par défaut pour convertir un fichier TeX en document PDF. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getDateTime](#getDateTime--) | Obtient/definit une certaine valeur pour les primitives date/heure comme l'année, le mois, le jour et l'heure. |
| [getInputDirectory](#getInputDirectory--) | Obtient/definit le répertoire d'entrée TeX. |
| [getJobName](#getJobName--) | Obtient/definit le nom du travail. |
| [getLoadResult](#getLoadResult--) | Obtient le résultat du chargement et de la compilation TeX - tout s'est-il déroulé sans problème ou y a-t-il eu des commentaires/erreurs. |
| [getNoLigatures](#getNoLigatures--) | Obtient/definit un indicateur qui annule les ligatures dans toutes les polices. |
| [getOutputDirectory](#getOutputDirectory--) | Obtient/definit le répertoire de sortie TeX. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | Obtient/definit un indicateur qui permet de rasteriser les formules mathématiques. |
| [getRepeat](#getRepeat--) | Obtient/definit l'indicateur indiquant s'il est nécessaire d'exécuter le travail TeX deux fois dans le cas, par exemple, où il y a des références dans le(s) fichier(s) TeX d'entrée. En général, ce comportement est utile lorsque le moteur collecte certaines données pendant le processus de composition et les stocke dans un fichier auxiliaire lors du premier passage. Et lors du deuxième passage, le moteur utilise d'une manière ou d'une autre ces données. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | Obtient/definit le répertoire d'entrée requis par TeX. L'entrée requise est constituée des fichiers qui sont d'une manière ou d'une autre inclus dans le fichier .tex principal, par ex., les packages pour lesquels il n'existe pas de prise en charge intégrée. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | Obtient/definit l'indicateur indiquant s'il faut afficher la sortie du terminal sur la console. |
| [getSubsetFonts](#getSubsetFonts--) | Obtient/definit le drapeau indiquant s’il faut sous‑ensemble les polices dans le fichier de sortie ou non. |
| [setDateTime](#setDateTime-java.util.Date-) | Obtient/definit une certaine valeur pour les primitives date/heure comme l'année, le mois, le jour et l'heure. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Obtient/definit le répertoire d'entrée TeX. |
| [setJobName](#setJobName-java.lang.String-) | Obtient/definit le nom du travail. |
| [setNoLigatures](#setNoLigatures-boolean-) | Obtient/definit un indicateur qui annule les ligatures dans toutes les polices. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | Obtient/definit le répertoire de sortie TeX. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | Obtient/definit un indicateur qui permet de rasteriser les formules mathématiques. |
| [setRepeat](#setRepeat-boolean-) | Obtient/definit l'indicateur indiquant s'il est nécessaire d'exécuter le travail TeX deux fois dans le cas, par exemple, où il y a des références dans le(s) fichier(s) TeX d'entrée. En général, ce comportement est utile lorsque le moteur collecte certaines données pendant le processus de composition et les stocke dans un fichier auxiliaire lors du premier passage. Et lors du deuxième passage, le moteur utilise d'une manière ou d'une autre ces données. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Obtient/definit le répertoire d'entrée requis par TeX. L'entrée requise est constituée des fichiers qui sont d'une manière ou d'une autre inclus dans le fichier .tex principal, par ex., les packages pour lesquels il n'existe pas de prise en charge intégrée. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | Obtient/definit l'indicateur indiquant s'il faut afficher la sortie du terminal sur la console. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Obtient/definit le drapeau indiquant s’il faut sous‑ensemble les polices dans le fichier de sortie ou non. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

Crée les options de chargement par défaut pour convertir un fichier TeX en document PDF.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

Obtient/definit une certaine valeur pour les primitives date/heure comme l'année, le mois, le jour et l'heure.

**Returns:**
Instance Date

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

Obtient/definit le répertoire d'entrée TeX.

**Returns:**
ITeXInputDirectory instance

### getJobName {#getJobName--}
```
public final String getJobName()
```

Obtient/definit le nom du travail.

**Returns:**
valeur String

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

Obtient le résultat du chargement et de la compilation TeX - tout s'est-il déroulé sans problème ou y a-t-il eu des commentaires/erreurs.

**Returns:**
TeXLoadResult élément

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

Obtient/definit un indicateur qui annule les ligatures dans toutes les polices.

**Returns:**
valeur booléenne

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

Obtient/definit le répertoire de sortie TeX.

**Returns:**
ITeXOutputDirectory instance

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

Obtient/definit un indicateur qui permet de rasteriser les formules mathématiques.

**Returns:**
valeur booléenne

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

Obtient/definit l'indicateur indiquant s'il est nécessaire d'exécuter le travail TeX deux fois dans le cas, par exemple, où il y a des références dans le(s) fichier(s) TeX d'entrée. En général, ce comportement est utile lorsque le moteur collecte certaines données pendant le processus de composition et les stocke dans un fichier auxiliaire lors du premier passage. Et lors du deuxième passage, le moteur utilise d'une manière ou d'une autre ces données.

**Returns:**
valeur booléenne

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

Obtient/definit le répertoire d'entrée requis par TeX. L'entrée requise est constituée des fichiers qui sont d'une manière ou d'une autre inclus dans le fichier .tex principal, par ex., les packages pour lesquels il n'existe pas de prise en charge intégrée.

**Returns:**
ITeXInputDirectory instance

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

Obtient/definit l'indicateur indiquant s'il faut afficher la sortie du terminal sur la console.

**Returns:**
valeur booléenne

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

Obtient/definit le drapeau indiquant s’il faut sous‑ensemble les polices dans le fichier de sortie ou non.

**Returns:**
valeur booléenne

### setDateTime {#setDateTime-java.util.Date-}
Obtient/definit une certaine valeur pour les primitives date/heure comme l'année, le mois, le jour et l'heure.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Obtient/definit le répertoire d'entrée TeX.

### setJobName {#setJobName-java.lang.String-}
Obtient/definit le nom du travail.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

Obtient/definit un indicateur qui annule les ligatures dans toutes les polices.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
Obtient/definit le répertoire de sortie TeX.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

Obtient/definit un indicateur qui permet de rasteriser les formules mathématiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

Obtient/definit l'indicateur indiquant s'il est nécessaire d'exécuter le travail TeX deux fois dans le cas, par exemple, où il y a des références dans le(s) fichier(s) TeX d'entrée. En général, ce comportement est utile lorsque le moteur collecte certaines données pendant le processus de composition et les stocke dans un fichier auxiliaire lors du premier passage. Et lors du deuxième passage, le moteur utilise d'une manière ou d'une autre ces données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Obtient/definit le répertoire d'entrée requis par TeX. L'entrée requise est constituée des fichiers qui sont d'une manière ou d'une autre inclus dans le fichier .tex principal, par ex., les packages pour lesquels il n'existe pas de prise en charge intégrée.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

Obtient/definit l'indicateur indiquant s'il faut afficher la sortie du terminal sur la console.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Obtient/definit le drapeau indiquant s’il faut sous‑ensemble les polices dans le fichier de sortie ou non.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
