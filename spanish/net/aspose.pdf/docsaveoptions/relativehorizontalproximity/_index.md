---
title: DocSaveOptions.RelativeHorizontalProximity
second_title: Aspose.PDF for .NET API Reference
description: Propiedad DocSaveOptions. En PDF, las palabras pueden ser representadas internamente con operadores que imprimen palabras imprimiendo independientemente sus letras o sílabas. Por lo tanto, para detectar palabras, a veces necesitamos detectar grupos de caracteres independientes que de hecho son palabras. Esta configuración define el ancho del espacio entre elementos de texto que deben ser tratados como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. La presencia de un espacio vacío, al menos con este ancho entre letras, significa que los elementos textuales pertenecen a diferentes palabras. Está normalizado al tamaño de fuente - 1.0 significa 100% del tamaño de fuente de la supuesta palabra. ¡ATENCIÓN! Se utiliza solo en casos en que el PDF de origen contiene fuentes específicas poco utilizadas para las cuales no se puede calcular un valor óptimo a partir de la fuente. Por lo tanto, en la gran mayoría de los casos, este parámetro no cambia nada en el documento resultante.
type: docs
weight: 120
url: /es/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## Propiedad DocSaveOptions.RelativeHorizontalProximity

En PDF, las palabras pueden ser representadas internamente con operadores que imprimen palabras imprimiendo independientemente sus letras o sílabas. Por lo tanto, para detectar palabras, a veces necesitamos detectar grupos de caracteres independientes que de hecho son palabras. Esta configuración define el ancho del espacio entre elementos de texto (letras, sílabas) que deben ser tratados como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (La presencia de un espacio vacío, al menos con este ancho entre letras, significa que los elementos textuales pertenecen a diferentes palabras). Está normalizado al tamaño de fuente - 1.0 significa 100% del tamaño de fuente de la supuesta palabra. ¡ATENCIÓN! Se utiliza solo en casos en que el PDF de origen contiene fuentes específicas poco utilizadas para las cuales no se puede calcular un valor óptimo a partir de la fuente. Por lo tanto, en la gran mayoría de los casos, este parámetro no cambia nada en el documento resultante.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### Ver También

* clase [DocSaveOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)