---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Champ HtmlSaveOptions. Ce champ peut contenir une méthode personnalisée qui renvoie une URL ou un modèle d'URL si la génération multipage est activée, voir les détails ci‑dessus concernant le CSS qui doit être inséré dans le HTML généré. Par ex., si vous souhaitez que le convertisseur place une URL spécifique à la place du nom de fichier CSS standard dans le CSS généré, vous devez simplement créer et affecter à cette propriété une méthode qui génère l'URL souhaitée. Si le drapeau SplitCssIntoPages est défini, alors cette stratégie personnalisée, le cas échéant, doit renvoyer non pas l'URL exacte du CSS mais plutôt une chaîne modèle qui, après substitution du placeholder par le numéro de page à l'aide de la fonction string.Format du convertisseur, peut être résolue en URL pour le CSS de telle ou telle page. Des exemples de chaîne de retour attendue dans ce cas sont SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0"
type: docs
weight: 300
url: /fr/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

Ce champ peut contenir une méthode personnalisée qui renvoie l’URL (ou le modèle d’URL si la génération multipage est activée – voir les détails ci‑dessous) du CSS concerné tel qu’il doit être inséré dans le HTML résultant généré. Par ex., si vous souhaitez que le convertisseur place une URL spécifique à la place du nom de fichier CSS standard dans le CSS généré, vous devez simplement créer et affecter à cette propriété une méthode qui génère l’URL souhaitée. Si le drapeau 'SplitCssIntoPages' est défini, alors cette stratégie personnalisée (le cas échéant) doit renvoyer non pas l’URL exacte du CSS mais plutôt une chaîne modèle qui (après substitution du paramètre par le numéro de page avec la fonction string.Format() du convertisseur) peut être résolue en URL pour le CSS de cette page ou de cette autre page. Exemples de chaînes de retour attendues dans ce cas : 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Voir aussi

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


