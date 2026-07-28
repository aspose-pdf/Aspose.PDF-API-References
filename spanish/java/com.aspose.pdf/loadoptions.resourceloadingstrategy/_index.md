---
title: "LoadOptions.ResourceLoadingStrategy"
linktitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados desde algún lugar."
type: docs
weight: 2830
url: /es/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado, que obtenga los recursos solicitados desde algún lugar. Por ejemplo, durante el uso de Aspose.PDf en la nube el acceso directo a los archivos referenciados es imposible, y se debe usar algún código personalizado colocado en un método especial. Este delegado define la firma de dicho método personalizado.

## Métodos

| Método | Descripción |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
