---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: Champ HtmlLoadOptions. Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes comme les images ou les CSS et de fournir une méthode personnalisée qui obtiendra les ressources demandées d'ailleurs. Par exemple, lors de l'utilisation d'Aspose.PDF dans le cloud, l'accès direct aux fichiers référencés est impossible : dans ce cas, un code personnalisé placé dans une méthode spéciale doit être utilisé, et un délégué qui fait référence à cette méthode doit être assigné à cet attribut.
type: docs
weight: 100
url: /fr/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## Champ HtmlLoadOptions.CustomLoaderOfExternalResources

Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui obtiendra les ressources demandées d'ailleurs. Par exemple, lors de l'utilisation d'Aspose.PDF dans le cloud, l'accès direct aux fichiers référencés est impossible : dans ce cas, un code personnalisé placé dans une méthode spéciale doit être utilisé, et un délégué qui fait référence à cette méthode doit être assigné à cet attribut.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Voir aussi

* délégué [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* classe [HtmlLoadOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)