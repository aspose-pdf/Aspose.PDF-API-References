---
title: "Énumération LoadOptions.PageSizeAdjustmentModes"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes enum. ATTENTION La fonctionnalité est implémentée mais n’est pas encore exposée dans l’API publique en raison d’un problème bloquant dans la couche OSHARED détecté pour le document d’exemple. Représente le mode d’utilisation de la taille de page pendant la conversion. Les formats comme HTML, EPUB, etc. ont généralement une mise en page fluide, ce qui permet d’ajuster à la taille de page requise. Mais parfois le contenu spécifie des positions horizontales ou une taille qui ne permet pas d’insérer le contenu dans la taille de page requise. Dans ce cas nous pouvons définir ce qui doit être fait, c’est‑à‑dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du PDF résultant."
type: docs
weight: 6280
url: /fr/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

ATTENTION ! La fonctionnalité est implémentée mais n’est pas encore exposée dans l’API publique en raison d’un problème bloquant dans la couche OSHARED détecté pour le document d’exemple. Représente le mode d’utilisation de la taille de page pendant la conversion. Les formats (comme HTML, EPUB, etc.) ont généralement une mise en page fluide, ce qui permet d’ajuster à la taille de page requise. Mais parfois le contenu spécifie des positions horizontales ou une taille qui ne permet pas d’insérer le contenu dans la taille de page requise. Dans ce cas nous pouvons définir ce qui doit être fait (c’est‑à‑dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du PDF résultant).

```csharp
public enum PageSizeAdjustmentModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | Dans ce mode, les pages résultantes auront la taille de page requise définie dans LoadOptions, quel que soit le fait que le contenu après conversion dépasse ou non les limites de la page. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Ce mode définit ce comportement : après l’obtention du résultat de conversion et la détection du fait qu’une partie du contenu a été tronquée, la largeur de la zone d’affichage est agrandie pour s’adapter au contenu et la conversion est répétée. Ce mode permet d’obtenir moins de pages dans le résultat dans ce cas, mais nécessite un rendu répété (et donc plus de temps de traitement). |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


