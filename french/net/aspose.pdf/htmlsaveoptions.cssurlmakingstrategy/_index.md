---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Vous pouvez assigner à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente la création de l'URL du CSS référencé dans le document HTML généré. Par exemple, si vous souhaitez faire référence au CSS dans HTML par exemple comme "otherPage.ASPXCssIDzjjkklj", alors cette stratégie personnalisée doit retourner "otherPage.ASPXCssIDzjjkklj"
type: docs
weight: 5600
url: /fr/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## Délégué HtmlSaveOptions.CssUrlMakingStrategy

Vous pouvez assigner à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente la création de l'URL du CSS référencé dans le document HTML généré. Par exemple, si vous souhaitez faire référence au CSS dans HTML par exemple comme "otherPage.ASPX?CssID=zjjkklj", alors cette stratégie personnalisée doit retourner "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | représente un ensemble de données qui peut être utilisé pour la génération de l'URL du CSS |

### Valeur de retour

doit retourner une chaîne qui représente l'URL du CSS ou le modèle de l'URL

### Voir aussi

* classe [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)