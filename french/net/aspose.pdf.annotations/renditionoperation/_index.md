---
title: "Enum RenditionOperation"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Annotations.RenditionOperation enum. L'opération à effectuer lorsque l'action est déclenchée"
type: docs
weight: 2540
url: /fr/net/aspose.pdf.annotations/renditionoperation/
---
## RenditionOperation enumeration

L'opération à exécuter lorsque l'action est déclenchée.

```csharp
public enum RenditionOperation
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| PlayStop | `0` | Si aucune rendition n'est associée à l'annotation, lire la rendition spécifiée, en l'associant à l'annotation. Si une rendition est déjà associée à l'annotation, elle doit être arrêtée, et la nouvelle rendition doit être associée à l'annotation. |
| Stop | `1` | Arrêter toute rendition en cours de lecture associée à l'annotation. |
| Pause | `2` | Mettre en pause toute rendition en cours de lecture associée à l'annotation. |
| Resume | `3` | Reprendre toute rendition en cours de lecture associée à l'annotation. |
| PlayResume | `4` | Lire la rendition spécifiée, en l'associant à l'annotation. Si une rendition est déjà associée à l'annotation, reprendre la rendition si elle est en pause. |
| Undefined | `-1` | Opération non définie. |

### Voir aussi

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


