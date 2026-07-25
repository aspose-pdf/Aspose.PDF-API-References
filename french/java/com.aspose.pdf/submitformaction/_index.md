---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe qui décrit l'action submit-form."
type: docs
weight: 4690
url: /fr/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

Classe qui décrit l'action submit-form.

## Champs

| Champ | Description |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | Si défini, toutes les valeurs de champ soumises représentant des dates seront converties au format standard. |
| [EMBED_FORM](#EMBED_FORM) | Si défini, l'entrée F du FDF soumis doit être une spécification de fichier contenant un flux de fichier intégré représentant le fichier PDF à partir duquel le FDF est soumis. |
| [EXCL_F_KEY](#EXCL_F_KEY) | Si défini, le FDF soumis doit exclure l'entrée F. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | Si défini, il doit inclure uniquement les annotations de balisage dont l'entrée T correspond au nom de l'utilisateur actuel. |
| [EXCLUDE](#EXCLUDE) | Si désactivé, le tableau Fields spécifie quels champs inclure dans la soumission. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | Si défini, les noms et valeurs des champs seront soumis au format Formulaire HTML. |
| [GET_METHOD](#GET_METHOD) | Si défini, les noms et valeurs des champs seront soumis à l'aide d'une requête HTTP GET. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | Si défini, le fichier FDF soumis doit inclure toutes les annotations de balisage du document PDF sous-jacent. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | Si défini, le fichier FDF soumis doit inclure le contenu de toutes les mises à jour incrémentielles. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | Si défini, tous les champs désignés par le tableau Fields et le drapeau Inclure/Exclure seront soumis. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | Si défini, les coordonnées du clic de souris qui a déclenché l'action submit-form seront transmises dans les données du formulaire. |
| [SUBMIT_PDF](#SUBMIT_PDF) | Si défini, le document doit être soumis en PDF, en utilisant le type de contenu MIME application/pdf. |
| [XFDF](#XFDF) | Si défini, les noms et valeurs des champs seront soumis au format XFDF. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | Initialise l'objet SubmitFormAction. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFlags](#getFlags--) | Obtient les indicateurs de l'action de soumission |
| [getUrl](#getUrl--) | URL de destination. |
| [setFlags](#setFlags-int-) | Définit les indicateurs de l'action de soumission |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | URL de destination. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

Si défini, toutes les valeurs de champ soumises représentant des dates seront converties au format standard.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

Si défini, l'entrée F du FDF soumis doit être une spécification de fichier contenant un flux de fichier intégré représentant le fichier PDF à partir duquel le FDF est soumis.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

Si défini, le FDF soumis doit exclure l'entrée F.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

Si défini, il doit inclure uniquement les annotations de balisage dont l'entrée T correspond au nom de l'utilisateur actuel.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

Si désactivé, le tableau Fields spécifie quels champs inclure dans la soumission.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

Si défini, les noms et valeurs des champs seront soumis au format Formulaire HTML.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

Si défini, les noms et valeurs des champs seront soumis à l'aide d'une requête HTTP GET.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

Si défini, le fichier FDF soumis doit inclure toutes les annotations de balisage du document PDF sous-jacent.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

Si défini, le fichier FDF soumis doit inclure le contenu de toutes les mises à jour incrémentielles.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

Si défini, tous les champs désignés par le tableau Fields et le drapeau Inclure/Exclure seront soumis.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

Si défini, les coordonnées du clic de souris qui a déclenché l'action submit-form seront transmises dans les données du formulaire.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

Si défini, le document doit être soumis en PDF, en utilisant le type de contenu MIME application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```

Si défini, les noms et valeurs des champs seront soumis au format XFDF.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

Initialise l'objet SubmitFormAction.

### getFlags {#getFlags--}
```
public int getFlags()
```

Obtient les indicateurs de l'action de soumission

**Returns:**
valeur int

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

URL de destination.

**Returns:**
PolylineAnnotation

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Définit les indicateurs de l'action de soumission

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
URL de destination.
