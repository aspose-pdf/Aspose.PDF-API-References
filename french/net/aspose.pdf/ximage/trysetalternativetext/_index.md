---
title: "XImage.TrySetAlternativeText"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode XImage. Définit le texte alternatif pour un XImage sur la page"
type: docs
weight: 180
url: /fr/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

Définit le texte alternatif pour un XImage sur la page.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alternativeText | String | Le texte alternatif à spécifier. |
| page | Page | Page où le XImage est situé. |

### Valeur de retour

Vrai si alternativeText pour le XImage est défini. Faux si alternativeText pour le XImage n'est pas défini.

## Remarques

La méthode renvoie false dans les cas suivants : - Le XImage n'est pas trouvé sur la page spécifiée. - Le XImage apparaît plusieurs fois sur la page avec différents éléments structurels, rendant ambigu l'instance qui doit recevoir le texte alternatif.

### Voir aussi

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


