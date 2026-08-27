---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Action qui est effectuée avec l'objet image lorsque l'image est supprimée de la collection. Si l'objet image est supprimé"
type: docs
weight: 2290
url: /fr/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

Action qui est effectuée avec l'objet image lorsque l'image est supprimée de la collection. Si l'objet image est supprimé

## Champs

| Champ | Description |
| --- | --- |
| [Check](#Check) | L’image sera supprimée de la collection et l’objet image ne sera supprimé que s’il n’existe aucune autre référence à l’image provenant d’autres pages. Cela peut prendre plus de temps comparé à l’option ForceDelete. |
| [ForceDelete](#ForceDelete) | L’image sera supprimée de la collection et l’objet image sera supprimé du document. Si d’autres références au même objet existent, le document peut être corrompu. |
| [KeepContents](#KeepContents) | L’image sera supprimée de la collection. Si le contenu de la page contient des références à l’image, elles ne seront pas supprimées. Le document peut devenir invalide. |
| [None](#None) | L’image sera supprimée de la collection et du contenu de la page, mais l’objet image ne sera pas supprimé. La taille du fichier ne sera pas réduite. |

### Check {#Check}
```
public static final int Check
```

L’image sera supprimée de la collection et l’objet image ne sera supprimé que s’il n’existe aucune autre référence à l’image provenant d’autres pages. Cela peut prendre plus de temps comparé à l’option ForceDelete.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

L’image sera supprimée de la collection et l’objet image sera supprimé du document. Si d’autres références au même objet existent, le document peut être corrompu.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

L’image sera supprimée de la collection. Si le contenu de la page contient des références à l’image, elles ne seront pas supprimées. Le document peut devenir invalide.

### None {#None}
```
public static final int None
```

L’image sera supprimée de la collection et du contenu de la page, mais l’objet image ne sera pas supprimé. La taille du fichier ne sera pas réduite.
