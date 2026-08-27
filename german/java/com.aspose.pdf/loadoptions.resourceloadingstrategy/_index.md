---
title: "LoadOptions.ResourceLoadingStrategy"
linktitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Manchmal ist es notwendig, die Verwendung des internen Laders externer Ressourcen (wie Bilder oder CSS-Dateien) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwo abruft."
type: docs
weight: 2830
url: /de/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

Manchmal ist es notwendig, die Verwendung des internen Laders externer Ressourcen (wie Bilder oder CSS-Dateien) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwo bezieht. Zum Beispiel ist bei der Verwendung von Aspose.PDf in der Cloud der direkte Zugriff auf referenzierte Dateien unmöglich, und benutzerdefinierter Code, der in eine spezielle Methode eingefügt wird, sollte verwendet werden. Dieser Delegat definiert die Signatur einer solchen benutzerdefinierten Methode.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
