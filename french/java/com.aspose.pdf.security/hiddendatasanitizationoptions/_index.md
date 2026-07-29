---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les options de configuration pour la désinfection des données cachées dans un document."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

Représente les options de configuration pour la désinfection des données cachées dans un document.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [all](#all--) | Crée une nouvelle instance de la classe {@link HiddenDataSanitizationOptions} avec toutes les options définies pour la désinfection. Cela inclut l'activation de la suppression des annotations, JavaScript, métadonnées, pièces jointes, index de recherche, informations privées, l'aplatissement des formulaires et des calques, tout en désactivant l'option de conversion des pages en images. Des configurations optionnelles comme {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) ou {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) peuvent être modifiées manuellement après l'obtention de l'instance, car elles ne sont pas actives par défaut. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | Obtient l'option de conversion des pages en images. Si cette option est activée, l'option ImageCompressionOptions sera ignorée. L'option doit être activée manuellement lors de l'utilisation de la méthode {@code #All()} si elle est requise. La conversion des pages en images se produira après le nettoyage des principales données cachées, qui sont contrôlées par d'autres options. |
| [getFlattenForms](#getFlattenForms--) | Obtient une valeur indiquant si les formulaires du document doivent être aplatis pendant le processus de désinfection. L'aplatissement des formulaires convertit les champs de formulaire interactifs en contenu statique, les rendant non modifiables ou remplissables. |
| [getFlattenLayers](#getFlattenLayers--) | Obtient l'option d'aplatissement des calques dans le document PDF. Lorsqu'elle est activée, tous les calques du document sont fusionnés en un seul calque, supprimant leur structure séparée. Cette option est utile pour désinfecter les documents en simplifiant leur contenu et en garantissant qu'aucune donnée cachée ne réside dans les calques. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Obtient l'option de conversion d'image du document. L'option doit être activée manuellement lors de l'utilisation de la méthode {@code #All()} si elle est requise. |
| [getImageDpi](#getImageDpi--) | Obtient l'option de résolution des images de page pendant la conversion. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | Obtient une valeur indiquant s'il faut supprimer les annotations du document. Lorsqu'elle est activée, toutes les annotations présentes dans le document seront supprimées pendant le processus de désinfection. Des annotations de rédaction seront appliquées. |
| [getRemoveAttachments](#getRemoveAttachments--) | Obtient l'option de suppression de tous les fichiers joints du document. Lorsqu'elle est activée, elle garantit que toutes les pièces jointes du PDF sont éliminées pendant le processus de désinfection. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | Obtient une valeur indiquant si le JavaScript et les actions associées doivent être supprimés du document. Cette option est utile pour éliminer les vulnérabilités de sécurité potentielles introduites par les scripts intégrés. |
| [getRemoveMetadata](#getRemoveMetadata--) | Obtient une option de suppression des métadonnées du document. Si elle est définie sur true, les métadonnées telles que les propriétés du document et les informations de métadonnées supplémentaires intégrées seront supprimées pendant la désinfection. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | Obtient une valeur indiquant si l'index de recherche et les informations privées doivent être supprimés du document. Active la suppression des index de recherche intégrés et des données privées afin d'améliorer la sécurité et la confidentialité du document. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | Définit l'option de conversion des pages en images. Si cette option est activée, l'option ImageCompressionOptions sera ignorée. L'option doit être activée manuellement lors de l'utilisation de la méthode {@code #All()} si elle est requise. La conversion des pages en images se produira après le nettoyage des principales données cachées, qui sont contrôlées par d'autres options. |
| [setFlattenForms](#setFlattenForms-boolean-) | Définit une valeur indiquant si les formulaires du document doivent être aplatis pendant le processus de désinfection. L'aplatissement des formulaires convertit les champs de formulaire interactifs en contenu statique, les rendant non modifiables ou remplissables. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | Définit l'option d'aplatissement des calques dans le document PDF. Lorsqu'elle est activée, tous les calques du document sont fusionnés en un seul calque, supprimant leur structure séparée. Cette option est utile pour désinfecter les documents en simplifiant leur contenu et en garantissant qu'aucune donnée cachée ne réside dans les calques. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Définit l'option de conversion d'image du document. L'option doit être activée manuellement lors de l'utilisation de la méthode {@code #All()} si elle est requise. |
| [setImageDpi](#setImageDpi-int-) | Définit l'option de résolution des images de page pendant la conversion. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | Définit une valeur indiquant s'il faut supprimer les annotations du document. Lorsqu'elle est activée, toutes les annotations présentes dans le document seront supprimées pendant le processus de désinfection. Des annotations de rédaction seront appliquées. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | Définit l'option de suppression de tous les fichiers joints du document. Lorsqu'elle est activée, elle garantit que toutes les pièces jointes du PDF sont éliminées pendant le processus de désinfection. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | Définit une valeur indiquant si le JavaScript et les actions associées doivent être supprimés du document. Cette option est utile pour éliminer les vulnérabilités de sécurité potentielles introduites par les scripts intégrés. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | Définit une option pour supprimer les métadonnées du document. Si elle est définie sur true, les métadonnées telles que les propriétés du document et les informations de métadonnées supplémentaires intégrées seront supprimées lors de la désinfection. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | Définit une valeur indiquant si l'index de recherche et les informations privées doivent être supprimés du document. Active la suppression des index de recherche intégrés et des données privées afin d'améliorer la sécurité et la confidentialité du document. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

Crée une nouvelle instance de la classe {@link HiddenDataSanitizationOptions} avec toutes les options définies pour la désinfection. Cela inclut l'activation de la suppression des annotations, JavaScript, métadonnées, pièces jointes, index de recherche, informations privées, l'aplatissement des formulaires et des calques, tout en désactivant l'option de conversion des pages en images. Des configurations optionnelles comme {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) ou {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) peuvent être modifiées manuellement après l'obtention de l'instance, car elles ne sont pas actives par défaut.

**Returns:**
Une instance {@link HiddenDataSanitizationOptions} avec toutes les options de désinfection préconfigurées.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

Obtient l'option de conversion des pages en images. Si cette option est activée, l'option ImageCompressionOptions sera ignorée. L'option doit être activée manuellement lors de l'utilisation de la méthode {@code #All()} si elle est requise. La conversion des pages en images se produira après le nettoyage des principales données cachées, qui sont contrôlées par d'autres options.

**Returns:**
l'option de conversion des pages en images.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

Obtient une valeur indiquant si les formulaires du document doivent être aplatis pendant le processus de désinfection. L'aplatissement des formulaires convertit les champs de formulaire interactifs en contenu statique, les rendant non modifiables ou remplissables.

**Returns:**
une valeur indiquant si les formulaires du document doivent être aplatis pendant le processus de désinfection.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

Obtient l'option d'aplatissement des calques dans le document PDF. Lorsqu'elle est activée, tous les calques du document sont fusionnés en un seul calque, supprimant leur structure séparée. Cette option est utile pour désinfecter les documents en simplifiant leur contenu et en garantissant qu'aucune donnée cachée ne réside dans les calques.

**Returns:**
l'option d'aplatir les calques du document PDF.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Obtient l'option de conversion d'image du document. L'option doit être activée manuellement lors de l'utilisation de la méthode {@code #All()} si elle est requise.

**Returns:**
l'option de conversion d'image du document.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

Obtient l'option de résolution des images de page pendant la conversion.

**Returns:**
l'option de résolution des images de page lors de la conversion.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

Obtient une valeur indiquant s'il faut supprimer les annotations du document. Lorsqu'elle est activée, toutes les annotations présentes dans le document seront supprimées pendant le processus de désinfection. Des annotations de rédaction seront appliquées.

**Returns:**
une valeur indiquant s'il faut supprimer les annotations du document.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

Obtient l'option de suppression de tous les fichiers joints du document. Lorsqu'elle est activée, elle garantit que toutes les pièces jointes du PDF sont éliminées pendant le processus de désinfection.

**Returns:**
l'option de suppression de tous les fichiers joints du document.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

Obtient une valeur indiquant si le JavaScript et les actions associées doivent être supprimés du document. Cette option est utile pour éliminer les vulnérabilités de sécurité potentielles introduites par les scripts intégrés.

**Returns:**
une valeur indiquant si le JavaScript et les actions associées doivent être supprimés du document.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

Obtient une option de suppression des métadonnées du document. Si elle est définie sur true, les métadonnées telles que les propriétés du document et les informations de métadonnées supplémentaires intégrées seront supprimées pendant la désinfection.

**Returns:**
une option pour supprimer les métadonnées du document.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

Obtient une valeur indiquant si l'index de recherche et les informations privées doivent être supprimés du document. Active la suppression des index de recherche intégrés et des données privées afin d'améliorer la sécurité et la confidentialité du document.

**Returns:**
une valeur indiquant si l'index de recherche et les informations privées doivent être supprimés du document.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

Définit l'option de conversion des pages en images. Si cette option est activée, l'option ImageCompressionOptions sera ignorée. L'option doit être activée manuellement lors de l'utilisation de la méthode {@code #All()} si elle est requise. La conversion des pages en images se produira après le nettoyage des principales données cachées, qui sont contrôlées par d'autres options.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | l'option de conversion des pages en images. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

Définit une valeur indiquant si les formulaires du document doivent être aplatis pendant le processus de désinfection. L'aplatissement des formulaires convertit les champs de formulaire interactifs en contenu statique, les rendant non modifiables ou remplissables.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | une valeur indiquant si les formulaires du document doivent être aplatis pendant le processus de désinfection. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

Définit l'option d'aplatissement des calques dans le document PDF. Lorsqu'elle est activée, tous les calques du document sont fusionnés en un seul calque, supprimant leur structure séparée. Cette option est utile pour désinfecter les documents en simplifiant leur contenu et en garantissant qu'aucune donnée cachée ne réside dans les calques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | l'option d'aplatir les calques du document PDF. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Définit l'option de conversion d'image du document. L'option doit être activée manuellement lors de l'utilisation de la méthode {@code #All()} si elle est requise.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

Définit l'option de résolution des images de page pendant la conversion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | l'option de résolution des images de page lors de la conversion. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

Définit une valeur indiquant s'il faut supprimer les annotations du document. Lorsqu'elle est activée, toutes les annotations présentes dans le document seront supprimées pendant le processus de désinfection. Des annotations de rédaction seront appliquées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | une valeur indiquant s'il faut supprimer les annotations du document. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

Définit l'option de suppression de tous les fichiers joints du document. Lorsqu'elle est activée, elle garantit que toutes les pièces jointes du PDF sont éliminées pendant le processus de désinfection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | l'option de suppression de tous les fichiers joints du document. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

Définit une valeur indiquant si le JavaScript et les actions associées doivent être supprimés du document. Cette option est utile pour éliminer les vulnérabilités de sécurité potentielles introduites par les scripts intégrés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | une valeur indiquant si le JavaScript et les actions associées doivent être supprimés du document. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

Définit une option pour supprimer les métadonnées du document. Si elle est définie sur true, les métadonnées telles que les propriétés du document et les informations de métadonnées supplémentaires intégrées seront supprimées lors de la désinfection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | une option pour supprimer les métadonnées du document. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

Définit une valeur indiquant si l'index de recherche et les informations privées doivent être supprimés du document. Active la suppression des index de recherche intégrés et des données privées afin d'améliorer la sécurité et la confidentialité du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | une valeur indiquant si l'index de recherche et les informations privées doivent être supprimés du document. |
