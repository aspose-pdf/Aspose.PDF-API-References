---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: HtmlLoadOptions-Feld. Manchmal ist es notwendig, die Verwendung des internen Ladeprogramms für externe Ressourcen wie Bilder oder CSS zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die angeforderte Ressourcen von irgendwoher abruft. Zum Beispiel ist während der Verwendung von Aspose.PDF in der Cloud der direkte Zugriff auf referenzierte Dateien unmöglich: In diesem Fall sollte benutzerdefinierter Code in eine spezielle Methode eingefügt werden, und der Delegierte, der auf diese Methode verweist, sollte diesem Attribut zugewiesen werden.
type: docs
weight: 100
url: /de/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources-Feld

Manchmal ist es notwendig, die Verwendung des internen Ladeprogramms für externe Ressourcen (wie Bilder oder CSS) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die angeforderte Ressourcen von irgendwoher abruft. Zum Beispiel ist während der Verwendung von Aspose.PDF in der Cloud der direkte Zugriff auf referenzierte Dateien unmöglich: In diesem Fall sollte benutzerdefinierter Code in eine spezielle Methode eingefügt werden, und der Delegierte, der auf diese Methode verweist, sollte diesem Attribut zugewiesen werden.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Siehe auch

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)