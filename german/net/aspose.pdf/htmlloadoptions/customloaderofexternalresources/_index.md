---
title: CustomLoaderOfExternalResources
second_title: Aspose.PDF für .NET-API-Referenz
description: Manchmal ist es notwendig die Verwendung des internen Ladeprogramms für externe Ressourcen wie Bilder oder CSS zu vermeiden und eine benutzerdefinierte Methode bereitzustellen die angeforderte Ressourcen von irgendwoher erhält. Beispielsweise ist während der Verwendung von von Aspose.PDF in der Cloud kein direkter Zugriff auf referenzierte Dateien möglich In diesem Fall sollte ein benutzerdefinierter Code put in eine spezielle Methode verwendet werden und ein Delegierter der auf diese Methode verweist sollte diesem Attribut zugewiesen werden.
type: docs
weight: 90
url: /de/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources field

Manchmal ist es notwendig, die Verwendung des internen Ladeprogramms für externe Ressourcen (wie Bilder oder CSS) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die angeforderte Ressourcen von irgendwoher erhält. Beispielsweise ist während der Verwendung von von Aspose.PDF in der Cloud kein direkter Zugriff auf referenzierte Dateien möglich: In diesem Fall sollte ein benutzerdefinierter Code put in eine spezielle Methode verwendet werden, und ein Delegierter, der auf diese Methode verweist, sollte diesem Attribut zugewiesen werden.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Siehe auch

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy)
* class [HtmlLoadOptions](../../htmlloadoptions)
* namensraum [Aspose.Pdf](../../htmlloadoptions)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
