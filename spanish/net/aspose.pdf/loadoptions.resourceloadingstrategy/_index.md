---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: A veces es necesario evitar el uso del cargador interno de recursos externos como imágenes o CSS y proporcionar un método personalizado que obtenga los recursos solicitados de algún lugar. Por ejemplo, durante el uso de Aspose.Pdf en la nube, el acceso directo a los archivos referenciados es imposible y se debe utilizar algún código personalizado en un método especial. Este delegado define la firma de dicho método personalizado.
type: docs
weight: 6160
url: /es/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## Delegate LoadOptions.ResourceLoadingStrategy

A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados de algún lugar. Por ejemplo, durante el uso de Aspose.Pdf en la nube, el acceso directo a los archivos referenciados es imposible, y se debe utilizar algún código personalizado en un método especial. Este delegado define la firma de dicho método personalizado.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceURI | String | URI del recurso. |

### Valor de Retorno

Objeto ResourceLoadingResult.

### Véase También

* clase [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* clase [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)