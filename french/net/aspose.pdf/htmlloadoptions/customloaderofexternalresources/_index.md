---
title: "HtmlLoadOptions.CustomLoaderOfExternalResources"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "HtmlLoadOptions champ. Parfois il est nécessaire d'éviter l'utilisation du chargeur interne des ressources externes comme les images ou les CSS et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit. Par exemple, lors de l'utilisation d'Aspose.PDF dans le cloud, l'accès direct aux fichiers référencés est impossible ; dans ce cas, du code personnalisé placé dans une méthode spéciale doit être utilisé et le délégué qui fait référence à cette méthode doit être assigné à cet attribut."
type: docs
weight: 100
url: /fr/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources field

Il arrive parfois qu’il soit nécessaire d’éviter l’utilisation du chargeur interne des ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un emplacement. Par exemple, lors de l’utilisation d’Aspose.PDF dans le cloud, l’accès direct aux fichiers référencés est impossible : dans ce cas, du code personnalisé placé dans une méthode spéciale doit être utilisé, et le délégué qui fait référence à cette méthode doit être assigné à cet attribut.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Voir aussi

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


