---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SaveOptions. Le type SaveOptions maintient un niveau d'abstraction sur les options de sauvegarde individuelles
type: docs
weight: 9870
url: /fr/net/aspose.pdf/saveoptions/
---
## Classe SaveOptions

Le type SaveOptions maintient un niveau d'abstraction sur les options de sauvegarde individuelles

```csharp
public abstract class SaveOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de conversion de PDF vers d'autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format de sauvegarde des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continue soit Abort. Continue est l'action par défaut et l'opération de sauvegarde continue, cependant l'utilisateur peut également retourner Abort dans ce cas l'opération de sauvegarde doit cesser. |

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)