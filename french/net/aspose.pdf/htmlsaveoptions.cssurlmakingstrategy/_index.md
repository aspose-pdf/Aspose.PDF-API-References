---
title: "Délégué HtmlSaveOptions.CssUrlMakingStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Vous pouvez affecter à cette propriété le délégué créé à partir d'une méthode personnalisée qui implémente la création de l'URL du CSS référencé dans le document HTML généré. Par ex., si vous souhaitez rendre le CSS référencé dans le HTML, par ex., sous la forme otherPage.ASPXCssIDzjjkklj alors une telle stratégie personnalisée doit renvoyer otherPage.ASPXCssIDzjjkklj"
type: docs
weight: 5730
url: /fr/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegate

Vous pouvez affecter à cette propriété le délégué créé à partir d'une méthode personnalisée qui implémente la création de l'URL du CSS référencé dans le document HTML généré. Par ex., si vous souhaitez rendre le CSS référencé dans le HTML, par ex., sous la forme "otherPage.ASPX?CssID=zjjkklj", alors une telle stratégie personnalisée doit renvoyer "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | représente un ensemble de données pouvant être utilisées pour la génération de l'URL du CSS |

### Valeur de retour

doit renvoyer une chaîne qui représente l'URL du CSS ou le modèle d'URL

### Voir aussi

* class [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


