---
title: "LoadOptions.ResourceLoadingStrategy"
linktitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Il est parfois nécessaire d'éviter l'utilisation du chargeur interne des ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit."
type: docs
weight: 2830
url: /fr/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un endroit. Par exemple, lors de l'utilisation d'Aspose.PDf dans le cloud, l'accès direct aux fichiers référencés est impossible, et du code personnalisé placé dans une méthode spéciale doit être utilisé. Ce délégué définit la signature d'une telle méthode personnalisée.

## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
