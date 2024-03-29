---
title: Duration
second_title: Referencia de API de Aspose.PDF para .NET
description: Obtiene la duración de visualización de la página establecida. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve -1 si no se define la duración.
type: docs
weight: 110
url: /es/net/aspose.pdf/page/duration/
---
## Page.Duration property

Obtiene la duración de visualización de la página establecida. Este es el tiempo en segundos que la página se mostrará durante la presentación. Devuelve -1 si no se define la duración.

```csharp
public double Duration { get; set; }
```

### Ejemplos

El ejemplo demuestra cómo obtener la duración de la página

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Ver también

* class [Page](../../page)
* espacio de nombres [Aspose.Pdf](../../page)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
