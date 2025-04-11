---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: Propiedad RenderingOptions. Reemplaza fuentes según sea necesario para garantizar que todos los caracteres en el texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: 1. Si el usuario establece explícitamente la propiedad DefaultFontName, verifica si la fuente especificada puede mostrar los caracteres deseados. 2. Si no se establece ninguna fuente definida por el usuario, busca entre las fuentes añadidas a través de FontRepository.Sources. 3. Analiza el texto para identificar su alfabeto o escritura y sugiere nombres de fuentes en consecuencia. Intenta localizar y usar estas fuentes del sistema. 4. Como alternativa, busca en el sistema cualquier fuente capaz de mostrar los caracteres requeridos.
type: docs
weight: 20
url: /es/net/aspose.pdf/renderingoptions/analyzefonts/
---
## Propiedad RenderingOptions.AnalyzeFonts

Reemplaza fuentes según sea necesario para garantizar que todos los caracteres en el texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: 1. Si el usuario establece explícitamente la propiedad DefaultFontName, verifica si la fuente especificada puede mostrar los caracteres deseados. 2. Si no se establece ninguna fuente definida por el usuario, busca entre las fuentes añadidas a través de !:FontRepository.Sources. 3. Analiza el texto para identificar su alfabeto o escritura y sugiere nombres de fuentes en consecuencia. Intenta localizar y usar estas fuentes del sistema. 4. Como alternativa, busca en el sistema cualquier fuente capaz de mostrar los caracteres requeridos.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Ver También

* clase [RenderingOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)