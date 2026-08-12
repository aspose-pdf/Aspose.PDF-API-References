---
title: "Aspose::Pdf::DocSaveOptions::set_RelativeHorizontalProximity método"
linktitle: "set_RelativeHorizontalProximity"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::DocSaveOptions::set_RelativeHorizontalProximity método. En PDF las palabras pueden estar representadas internamente con operadores que imprimen palabras al imprimir independientemente sus letras o sílabas. Por lo tanto, para detectar palabras a veces necesitamos detectar grupos de caracteres independientes que en realidad son palabras. Esta configuración define el ancho del espacio entre los elementos de texto (letras, sílabas) que debe considerarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (La presencia de un espacio vacío al menos de este ancho entre letras indica que los elementos textuales pertenecen a palabras diferentes). Está normalizado al tamaño de fuente: 1.0 significa el 100 % del supuesto tamaño de fuente de la palabra. ¡ATENCIÓN! Se usa solo en casos en que el PDF de origen contiene fuentes específicas de uso raro para las que no se puede calcular un valor óptimo a partir de la fuente. Así, en la gran mayoría de los casos este parámetro no cambia nada en el documento resultante en C++."
type: docs
weight: 2400
url: /es/cpp/aspose.pdf/docsaveoptions/set_relativehorizontalproximity/
---
## DocSaveOptions::set_RelativeHorizontalProximity method


En [Pdf](../../) las palabras pueden estar representadas internamente con operadores que imprimen palabras al imprimir independientemente sus letras o sílabas. Por lo tanto, para detectar palabras a veces necesitamos detectar grupos de caracteres independientes que en realidad son palabras. Esta configuración define el ancho del espacio entre los elementos de texto (letras, sílabas) que debe considerarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (La presencia de un espacio vacío al menos de este ancho entre letras indica que los elementos textuales pertenecen a palabras diferentes). Está normalizado al tamaño de fuente: 1.0 significa el 100 % del supuesto tamaño de fuente de la palabra. ¡ATENCIÓN! Se usa solo en casos en que el PDF de origen contiene fuentes específicas de uso raro para las que no se puede calcular un valor óptimo a partir de la fuente. Así, en la gran mayoría de los casos este parámetro no cambia nada en el documento resultante.

```cpp
void Aspose::Pdf::DocSaveOptions::set_RelativeHorizontalProximity(float value)
```

## Ver también

* Class [DocSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
