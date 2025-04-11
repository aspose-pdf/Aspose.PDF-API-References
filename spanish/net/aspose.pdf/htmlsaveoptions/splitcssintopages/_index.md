---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: Propiedad HtmlSaveOptions. Cuando se selecciona el modo multipágina, es decir, SplitIntoPages es verdadero, entonces este atributo define si se debe crear un archivo CSS separado para cada página HTML resultante. Por defecto, este atributo es falso, por lo que se creará un gran CSS común para todas las páginas creadas. El tamaño total de todos los CSS generados en este modo (un CSS por página) suele ser mucho mayor que el tamaño de un gran archivo CSS, porque en el primer caso las clases CSS son duplicados en varios archivos CSS para cada página. Por lo tanto, esta configuración es peor y debe usarse solo cuando esté interesado en el procesamiento futuro de cada página HTML de forma independiente y, por lo tanto, el tamaño del CSS de cada página tomada por separado es el problema más crítico.
type: docs
weight: 190
url: /es/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## Propiedad HtmlSaveOptions.SplitCssIntoPages

Cuando se selecciona el modo multipágina (es decir, 'SplitIntoPages' es 'true'), entonces este atributo define si se debe crear un archivo CSS separado para cada página HTML resultante. Por defecto, este atributo es falso, por lo que se creará un gran CSS común para todas las páginas creadas. El tamaño total de todos los CSS generados en este modo (un CSS por página) suele ser mucho mayor que el tamaño de un gran archivo CSS, porque en el primer caso las clases CSS son duplicados en varios archivos CSS para cada página. Por lo tanto, esta configuración es peor y debe usarse solo cuando esté interesado en el procesamiento futuro de cada página HTML de forma independiente y, por lo tanto, el tamaño del CSS de cada página tomada por separado es el problema más crítico.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Ver También

* clase [HtmlSaveOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)