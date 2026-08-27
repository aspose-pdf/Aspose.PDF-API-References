---
title: "Classe SaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.SaveOptions class. Le type SaveOptions maintient un niveau d'abstraction sur les options de sauvegarde individuelles"
type: docs
weight: 10020
url: /fr/net/aspose.pdf/saveoptions/
---
## SaveOptions class

Le type SaveOptions maintient le niveau d'abstraction sur les options d'enregistrement individuelles

```csharp
public abstract class SaveOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


