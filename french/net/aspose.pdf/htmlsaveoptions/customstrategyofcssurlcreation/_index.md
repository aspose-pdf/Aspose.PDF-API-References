---
title: CustomStrategyOfCssUrlCreation
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ce champ peut contenir une méthode personnalisée qui renvoie lURL ou le modèle dURL si la génération multipage est activée - voir les détails ci-dessous du sujet CSS car il doit être mis dans le résultat généré HTML. Fe si vous voulez que le convertisseur mette une URL spécifique au lieu de standard Nom du fichier CSS dans le CSS généré alors vous devez simplement créer et mettre dans cette propriété method qui génère lURL souhaitable. Si le drapeau SplitCssIntoPages est défini alors cette stratégie personnalisée le cas échéant doit renvoyer non pas lURL exacte du CSS mais plutôt le modèle La chaîne that après remplacement de lespace réservé par le numéro de page avec la fonction string.Format à lintérieur du convertisseur peut être résolue en URL pour lURL CSS de telle ou telle page. Exemples de chaîne de retour attendue dans ce cas  SomeTargetLocation-page_0.css../PartHandlers/GetCss.aspxDocumentId45654ampCssPage0
type: docs
weight: 250
url: /fr/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

Ce champ peut contenir une méthode personnalisée qui renvoie l'URL (ou le modèle d'URL si la génération multipage est activée - voir les détails ci-dessous) du sujet CSS, car il doit être mis dans le résultat généré HTML. Fe si vous voulez que le convertisseur mette une URL spécifique au lieu de standard Nom du fichier CSS dans le CSS généré, alors vous devez simplement créer et mettre dans cette propriété method qui génère l'URL souhaitable. Si le drapeau 'SplitCssIntoPages' est défini, alors cette stratégie personnalisée (le cas échéant) doit renvoyer non pas l'URL exacte du CSS mais plutôt le modèle La chaîne that (après remplacement de l'espace réservé par le numéro de page avec la fonction string.Format() à l'intérieur du convertisseur) peut être résolue en URL pour l'URL CSS de telle ou telle page. Exemples de chaîne de retour attendue dans ce cas : 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Voir également

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* espace de noms [Aspose.Pdf](../../htmlsaveoptions)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->