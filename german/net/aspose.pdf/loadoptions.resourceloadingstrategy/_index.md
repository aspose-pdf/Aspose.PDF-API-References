---
title: LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF für .NET-API-Referenz
description: Manchmal ist es notwendig die Verwendung des internen Ladeprogramms externer Ressourcen wie Bilder oder CSS zu vermeiden und eine benutzerdefinierte Methode bereitzustellen die angeforderte Ressourcen von irgendwoher erhält. Beispielsweise ist während der Verwendung von von Aspose.Pdf in der Cloud kein direkter Zugriff auf referenzierte Dateien möglich und es sollte ein benutzerdefinierter Code verwendet werden der in die Methode special eingefügt wird. Dieser Delegierte definiert die Signatur einer solchen benutzerdefinierten Methode.
type: docs
weight: 3990
url: /de/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

Manchmal ist es notwendig, die Verwendung des internen Ladeprogramms externer Ressourcen (wie Bilder oder CSS) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die angeforderte Ressourcen von irgendwoher erhält. Beispielsweise ist während der Verwendung von von Aspose.Pdf in der Cloud kein direkter Zugriff auf referenzierte Dateien möglich, und es sollte ein benutzerdefinierter Code verwendet werden, der in die Methode special eingefügt wird. Dieser Delegierte definiert die Signatur einer solchen benutzerdefinierten Methode.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceURI | String | Ressourcen-URI. |

### Rückgabewert

ResourceLoadingResult-Objekt.

### Siehe auch

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult)
* class [LoadOptions](../loadoptions)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
