---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Manchmal ist es notwendig, die Verwendung des internen Laders für externe Ressourcen wie Bilder oder CSS zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwoher abruft. Zum Beispiel ist während der Verwendung von Aspose.Pdf in der Cloud der direkte Zugriff auf referenzierte Dateien unmöglich, und es sollte ein benutzerdefinierter Code in eine spezielle Methode eingefügt werden. Dieser Delegate definiert die Signatur einer solchen benutzerdefinierten Methode.
type: docs
weight: 6160
url: /de/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy-Delegate

Manchmal ist es notwendig, die Verwendung des internen Laders für externe Ressourcen (wie Bilder oder CSS) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwoher abruft. Zum Beispiel ist während der Verwendung von Aspose.Pdf in der Cloud der direkte Zugriff auf referenzierte Dateien unmöglich, und es sollte ein benutzerdefinierter Code in eine spezielle Methode eingefügt werden. Dieser Delegate definiert die Signatur einer solchen benutzerdefinierten Methode.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceURI | String | Ressourcen-URI. |

### Rückgabewert

ResourceLoadingResult-Objekt.

### Siehe auch

* Klasse [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)