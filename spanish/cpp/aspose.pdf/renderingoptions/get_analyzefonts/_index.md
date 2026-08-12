---
title: "Aspose::Pdf::RenderingOptions::get_AnalyzeFonts método"
linktitle: "get_AnalyzeFonts"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::RenderingOptions::get_AnalyzeFonts método. Sustituye fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/renderingoptions/get_analyzefonts/
---
## RenderingOptions::get_AnalyzeFonts method


Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos:

```cpp
bool Aspose::Pdf::RenderingOptions::get_AnalyzeFonts() const
```

## Observaciones


1. Si el usuario establece explícitamente la propiedad DefaultFontName, verifique si la fuente especificada puede mostrar los caracteres deseados.
1. Si no se ha establecido una fuente definida por el usuario, busque entre las fuentes añadidas a través de [FontRepository::Sources](../).
1. Analice el texto para identificar su alfabeto o escritura y sugiera nombres de fuentes en consecuencia. Intente localizar y usar esas fuentes del sistema.
1. Como alternativa, busque en el sistema cualquier fuente capaz de mostrar los caracteres requeridos.


## Ver también

* Class [RenderingOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
