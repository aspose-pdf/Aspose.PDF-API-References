---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes comme des images ou des CSS et de fournir une méthode personnalisée qui obtiendra les ressources demandées d'ailleurs. Par exemple, lors de l'utilisation d'Aspose.Pdf dans le cloud, l'accès direct aux fichiers référencés est impossible et un code personnalisé placé dans une méthode spéciale doit être utilisé. Ce délégué définit la signature de cette méthode personnalisée.
type: docs
weight: 6160
url: /fr/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes (comme des images ou des CSS) et de fournir une méthode personnalisée qui obtiendra les ressources demandées d'ailleurs. Par exemple, lors de l'utilisation d'Aspose.Pdf dans le cloud, l'accès direct aux fichiers référencés est impossible, et un code personnalisé placé dans une méthode spéciale doit être utilisé. Ce délégué définit la signature de cette méthode personnalisée.

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