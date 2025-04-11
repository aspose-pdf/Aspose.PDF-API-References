---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Enum ImageDeleteAction d'Aspose.Pdf. Action effectuée avec l'objet image lorsque l'image est supprimée de la collection. Si l'objet image est supprimé
type: docs
weight: 5870
url: /fr/net/aspose.pdf/imagedeleteaction/
---
## Énumération ImageDeleteAction

Action effectuée avec l'objet image lorsque l'image est supprimée de la collection. Si l'objet image est supprimé

```csharp
public enum ImageDeleteAction
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| KeepContents | `0` | L'image sera supprimée de la collection. Si le contenu de la page contient des références à l'image, elles ne seront pas supprimées. Le document peut devenir invalide. |
| None | `1` | L'image sera supprimée de la collection et du contenu de la page, mais l'objet image ne sera pas supprimé. La taille du fichier ne sera pas réduite. |
| ForceDelete | `2` | L'image sera supprimée de la collection et l'objet image sera supprimé du document. Si d'autres références sur le même objet existent, le document peut être corrompu. |
| Check | `3` | L'image sera supprimée de la collection et l'objet image sera supprimé uniquement s'il n'existe pas d'autres références à l'image depuis d'autres pages. Cela peut nécessiter plus de temps par rapport à l'option ForceDelete. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)