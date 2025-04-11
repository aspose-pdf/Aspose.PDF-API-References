---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: Champ HtmlSaveOptions. Ce champ peut contenir une méthode personnalisée qui retourne une URL ou un modèle d'URL si la génération multipage est activée - voir les détails ci-dessous du sujet CSS tel qu'il doit être mis dans le HTML généré. Par exemple, si vous souhaitez que le convertisseur mette une URL spécifique au lieu du nom de fichier CSS standard dans le CSS généré, vous devez simplement créer et mettre dans cette propriété une méthode qui génère l'URL souhaitée. Si le drapeau 'SplitCssIntoPages' est activé, alors cette stratégie personnalisée (le cas échéant) doit retourner non pas l'URL exacte du CSS mais plutôt une chaîne modèle qui (après substitution du placeholder avec le numéro de page avec la fonction string.Format() à l'intérieur du convertisseur) peut être résolue en URL pour le CSS de cette ou cette page. Des exemples de chaîne de retour attendue dans ce cas sont : 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')
type: docs
weight: 300
url: /fr/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## Champ HtmlSaveOptions.CustomStrategyOfCssUrlCreation

Ce champ peut contenir une méthode personnalisée qui retourne une URL (ou un modèle d'URL si la génération multipage est activée - voir les détails ci-dessous) du sujet CSS tel qu'il doit être mis dans le HTML généré. Par exemple, si vous souhaitez que le convertisseur mette une URL spécifique au lieu du nom de fichier CSS standard dans le CSS généré, vous devez simplement créer et mettre dans cette propriété une méthode qui génère l'URL souhaitée. Si le drapeau 'SplitCssIntoPages' est activé, alors cette stratégie personnalisée (le cas échéant) doit retourner non pas l'URL exacte du CSS mais plutôt une chaîne modèle qui (après substitution du placeholder avec le numéro de page avec la fonction string.Format() à l'intérieur du convertisseur) peut être résolue en URL pour le CSS de cette ou cette page. Des exemples de chaîne de retour attendue dans ce cas sont : 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Voir aussi

* délégué [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* classe [HtmlSaveOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)