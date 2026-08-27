---
title: "Délégué LoadOptions.ResourceLoadingStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Parfois il est nécessaire d'éviter l'utilisation du chargeur interne des ressources externes comme les images ou les CSS et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit. Par exemple, lors de l'utilisation d'Aspose.Pdf dans le cloud, l'accès direct aux fichiers référencés est impossible et du code personnalisé placé dans une méthode spéciale doit être utilisé. Ce délégué définit la signature d'une telle méthode personnalisée."
type: docs
weight: 6300
url: /fr/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

Parfois il est nécessaire d'éviter l'utilisation du chargeur interne des ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit. Par exemple, lors de l'utilisation d'Aspose.Pdf dans le cloud, l'accès direct aux fichiers référencés est impossible, et du code personnalisé placé dans une méthode spéciale doit être utilisé. Ce délégué définit la signature d'une telle méthode personnalisée.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| resourceURI | String | URI de la ressource. |

### Valeur de retour

Objet ResourceLoadingResult.

### Voir aussi

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


