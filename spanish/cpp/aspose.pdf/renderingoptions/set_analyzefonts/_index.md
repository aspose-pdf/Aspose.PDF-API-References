---
title: "Aspose::Pdf::RenderingOptions::set_AnalyzeFonts método"
linktitle: "set_AnalyzeFonts"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::RenderingOptions::set_AnalyzeFonts método. Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos: en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.pdf/renderingoptions/set_analyzefonts/
---
## RenderingOptions::set_AnalyzeFonts method


Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. El algoritmo de sustitución de fuentes sigue estos pasos:

```cpp
void Aspose::Pdf::RenderingOptions::set_AnalyzeFonts(bool value)
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
