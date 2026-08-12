---
title: "Método Aspose::Pdf::CollectionSort::get_S"
linktitle: "get_S"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::CollectionSort::get_S. Obtiene el nombre o los nombres de los campos que el procesador interactivo de PDF debe usar para ordenar los elementos de la colección. Si el valor es un nombre, identifica un campo descrito en el diccionario de la colección padre. Si el valor es una matriz, cada elemento de la matriz debe ser un nombre que identifica un campo descrito en el diccionario de la colección padre. La forma de matriz se utilizará para permitir que campos adicionales contribuyan al ordenamiento, donde cada campo adicional se usará para desempatar. Más específicamente, si varios diccionarios de elementos de colección tienen el mismo valor para el primer campo nombrado en la matriz, los valores de los campos sucesivos nombrados en la matriz se usarán para ordenar, hasta que se determine un orden único o hasta que se agoten los campos nombrados en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf/collectionsort/get_s/
---
## CollectionSort::get_S method


Obtiene el nombre o los nombres de los campos que el procesador PDF interactivo debe usar para ordenar los elementos de la colección. Si el valor es un nombre, identifica un campo descrito en el diccionario de la colección principal. Si el valor es una matriz, cada elemento de la matriz será un nombre que identifica un campo descrito en el diccionario de la colección principal. La forma de matriz se utilizará para permitir que campos adicionales contribuyan al ordenamiento, donde cada campo adicional se usará para romper empates. Más específicamente, si varios diccionarios de elementos de colección tienen el mismo valor para el primer campo nombrado en la matriz, los valores de los campos sucesivos nombrados en la matriz se usarán para ordenar, hasta que se determine un orden único o hasta que se agoten los campos nombrados.

```cpp
const System::ArrayPtr<System::String> & Aspose::Pdf::CollectionSort::get_S() const
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [CollectionSort](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
