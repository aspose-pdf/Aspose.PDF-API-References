---
title: "Énum ImageDeleteAction"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.ImageDeleteAction enum. Action effectuée sur l’objet image lorsque l’image est retirée de la collection. Si l’objet image est retiré"
type: docs
weight: 6000
url: /fr/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enumeration

Action effectuée avec l'objet image lorsque l'image est supprimée de la collection. Si l'objet image est supprimé

```csharp
public enum ImageDeleteAction
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| KeepContents | `0` | L’image sera retirée de la collection. Si le contenu de la page contient des références à l’image, elles ne seront pas supprimées. Le document peut devenir invalide. |
| None | `1` | L'image sera supprimée de la collection et du contenu de la page, mais l'objet image ne sera pas supprimé. La taille du fichier ne sera pas réduite. |
| ForceDelete | `2` | L'image sera supprimée de la collection et l'objet image sera supprimé du document. Si d'autres références sur le même objet existent, le document peut être corrompu. |
| Check | `3` | L'image sera supprimée de la collection et l'objet image ne sera supprimé que s'il n'existe aucune autre référence à l'image depuis d'autres pages. Cela peut nécessiter plus de temps comparé à l'option ForceDelete. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


