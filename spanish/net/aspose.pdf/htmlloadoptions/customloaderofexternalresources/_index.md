---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlLoadOptions. A veces es necesario evitar el uso del cargador interno de recursos externos como imágenes o CSS y proporcionar un método personalizado que obtenga los recursos solicitados de algún lugar. Por ejemplo, durante el uso de Aspose.PDF en la nube, el acceso directo a los archivos referenciados es imposible; en tal caso, se debe utilizar algún código personalizado colocado en un método especial, y el delegado que se refiere a ese método debe ser asignado a este atributo.
type: docs
weight: 100
url: /es/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## Campo HtmlLoadOptions.CustomLoaderOfExternalResources

A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados de algún lugar. Por ejemplo, durante el uso de Aspose.PDF en la nube, el acceso directo a los archivos referenciados es imposible: en tal caso, se debe utilizar algún código personalizado colocado en un método especial, y el delegado que se refiere a ese método debe ser asignado a este atributo.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### Ver También

* delegado [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* clase [HtmlLoadOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)