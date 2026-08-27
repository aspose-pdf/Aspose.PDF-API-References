---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Options d'enregistrement pour l'exportation au format SVG"
type: docs
weight: 4720
url: /fr/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

Options d'enregistrement pour l'exportation au format SVG

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) pendant la conversion pour la gestion personnalisée des fichiers d'images externes référencés créés (comme les BMP ou JPEG incorporés) incorporés dans le SVG enregistré. Cette stratégie doit traiter les ressources et renvoyer une chaîne représentant l'URI souhaitée de la ressource enregistrée dans le SVG généré. Si le traitement de ce fichier ou de celui‑ci, pour une raison quelconque, doit être effectué par le code du convertisseur lui‑même, et non par du code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo'. Cela indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s'il n'y avait aucun code personnalisé externe. |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | Spécifie si la sortie sera créée sous forme d'une archive zip unique. Veuillez vous référer au commentaire des options 'TreatTargetFileNameAsDirectory' pour voir les règles de nommage des fichiers svg des pages d'un document source multipage, qui s'appliquent également à l'ensemble de fichiers de sortie compressés. |
| [isScaleToPixels](#isScaleToPixels--) | Spécifie s'il faut mettre à l'échelle le document de sortie des points typographiques aux pixels. |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | Cette option définit si le répertoire cible sera créé (s'il n'existe pas encore) avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie lui‑même. Ainsi, ce répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci‑dessous). Si non, les fichiers de sortie des pages autres que la première seront créés exactement dans le répertoire demandé comme fichier de sortie principal, mais porteront le suffixe _[2...n] dans le nom de fichier, suffixe défini par le numéro de page, par ex. si vous définissez le fichier de sortie "C:\\AsposeTests\\output.svg" et que la sortie contiendra plusieurs fichiers svg de pages, alors les fichiers des pages seront également créés dans le répertoire "C:\\AsposeTests\\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg' etc. |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | Spécifie si la sortie sera créée sous forme d'une archive zip unique. Veuillez vous référer au commentaire des options 'TreatTargetFileNameAsDirectory' pour voir les règles de nommage des fichiers svg des pages d'un document source multipage, qui s'appliquent également à l'ensemble de fichiers de sortie compressés. |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) pendant la conversion pour la gestion personnalisée des fichiers d'images externes référencés créés (comme les BMP ou JPEG incorporés) incorporés dans le SVG enregistré. |
| [setScaleToPixels](#setScaleToPixels-boolean-) | Spécifie s'il faut mettre à l'échelle le document de sortie des points typographiques aux pixels. |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | Cette option définit si le répertoire cible sera créé (s'il n'existe pas encore) avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie lui‑même. Ainsi, ce répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci‑dessous). Si non, les fichiers de sortie des pages autres que la première seront créés exactement dans le répertoire demandé comme fichier de sortie principal, mais porteront le suffixe _[2...n] dans le nom de fichier, suffixe défini par le numéro de page, par ex. si vous définissez le fichier de sortie "C:\\AsposeTests\\output.svg" et que la sortie contiendra plusieurs fichiers svg de pages, alors les fichiers des pages seront également créés dans le répertoire "C:\\AsposeTests\\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg' etc. |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

Constructeur

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) pendant la conversion pour la gestion personnalisée des fichiers d'images externes référencés créés (comme les BMP ou JPEG incorporés) incorporés dans le SVG enregistré. Cette stratégie doit traiter les ressources et renvoyer une chaîne représentant l'URI souhaitée de la ressource enregistrée dans le SVG généré. Si le traitement de ce fichier ou de celui‑ci, pour une raison quelconque, doit être effectué par le code du convertisseur lui‑même, et non par du code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo'. Cela indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s'il n'y avait aucun code personnalisé externe.

**Returns:**
Instance EmbeddedImagesSavingStrategy

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

Spécifie si la sortie sera créée sous forme d'une archive zip unique. Veuillez vous référer au commentaire des options 'TreatTargetFileNameAsDirectory' pour voir les règles de nommage des fichiers svg des pages d'un document source multipage, qui s'appliquent également à l'ensemble de fichiers de sortie compressés.

**Returns:**
valeur booléenne

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

Spécifie s'il faut mettre à l'échelle le document de sortie des points typographiques aux pixels.

**Returns:**
valeur booléenne

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

Cette option définit si le répertoire cible sera créé (s'il n'existe pas encore) avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie lui‑même. Ainsi, ce répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci‑dessous). Si non, les fichiers de sortie des pages autres que la première seront créés exactement dans le répertoire demandé comme fichier de sortie principal, mais porteront le suffixe _[2...n] dans le nom de fichier, suffixe défini par le numéro de page, par ex. si vous définissez le fichier de sortie "C:\\AsposeTests\\output.svg" et que la sortie contiendra plusieurs fichiers svg de pages, alors les fichiers des pages seront également créés dans le répertoire "C:\\AsposeTests\\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg' etc.

**Returns:**
valeur booléenne

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

Spécifie si la sortie sera créée sous forme d'une archive zip unique. Veuillez vous référer au commentaire des options 'TreatTargetFileNameAsDirectory' pour voir les règles de nommage des fichiers svg des pages d'un document source multipage, qui s'appliquent également à l'ensemble de fichiers de sortie compressés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| compressOutputToZipArchive |  | valeur booléenne |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) pendant la conversion pour la gestion personnalisée des fichiers d'images externes référencés créés (comme les BMP ou JPEG incorporés) incorporés dans le SVG enregistré.

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

Spécifie s'il faut mettre à l'échelle le document de sortie des points typographiques aux pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleToPixels |  | valeur booléenne |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

Cette option définit si le répertoire cible sera créé (s'il n'existe pas encore) avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie lui‑même. Ainsi, ce répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci‑dessous). Si non, les fichiers de sortie des pages autres que la première seront créés exactement dans le répertoire demandé comme fichier de sortie principal, mais porteront le suffixe _[2...n] dans le nom de fichier, suffixe défini par le numéro de page, par ex. si vous définissez le fichier de sortie "C:\\AsposeTests\\output.svg" et que la sortie contiendra plusieurs fichiers svg de pages, alors les fichiers des pages seront également créés dans le répertoire "C:\\AsposeTests\\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg' etc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | valeur booléenne |
