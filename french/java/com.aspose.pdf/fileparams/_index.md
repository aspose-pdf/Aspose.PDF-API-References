---
title: "FileParams"
linktitle: "FileParams"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Définit un dictionnaire de paramètres de fichier intégré qui doit contenir des informations supplémentaires spécifiques au fichier."
type: docs
weight: 1490
url: /fr/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

Définit un dictionnaire de paramètres de fichier intégré qui doit contenir des informations supplémentaires spécifiques au fichier.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | Constructeur de la classe FileParams. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCheckSum](#getCheckSum--) | Une chaîne de 16 octets qui est la somme de contrôle des octets du fichier intégré non compressé. La somme de contrôle est calculée en appliquant l'algorithme standard de hachage MD5 aux octets du flux du fichier intégré. |
| [getCreationDate](#getCreationDate--) | Obtient la date et l'heure de création du fichier intégré. |
| [getModDate](#getModDate--) | Obtient la date et l'heure de la dernière modification du fichier intégré. |
| [getSize](#getSize--) | La taille du fichier intégré non compressé, en octets. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Définit la date et l'heure de création du fichier intégré. |
| [setModDate](#setModDate-java.util.Date-) | Définit la date et l'heure de la dernière modification du fichier intégré. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
Constructeur de la classe FileParams.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

Une chaîne de 16 octets qui est la somme de contrôle des octets du fichier intégré non compressé. La somme de contrôle est calculée en appliquant l'algorithme standard de hachage MD5 aux octets du flux du fichier intégré.

**Returns:**
valeur String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Obtient la date et l'heure de création du fichier intégré.

**Returns:**
Objet Date

### getModDate {#getModDate--}
```
public Date getModDate()
```

Obtient la date et l'heure de la dernière modification du fichier intégré.

**Returns:**
Objet Date

### getSize {#getSize--}
```
public int getSize()
```

La taille du fichier intégré non compressé, en octets.

**Returns:**
valeur int

### setCreationDate {#setCreationDate-java.util.Date-}
Définit la date et l'heure de création du fichier intégré.

### setModDate {#setModDate-java.util.Date-}
Définit la date et l'heure de la dernière modification du fichier intégré.
