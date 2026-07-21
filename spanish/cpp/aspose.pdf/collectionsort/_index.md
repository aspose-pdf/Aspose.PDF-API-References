---
title: "Aspose::Pdf::CollectionSort clase"
linktitle: "CollectionSort"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::CollectionSort clase. Representa una clase para una definición de ordenación de colección en C++."
type: docs
weight: 2700
url: /es/cpp/aspose.pdf/collectionsort/
---
## CollectionSort class


Representa una clase para una definición de ordenación de colección.

```cpp
class CollectionSort : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CollectionSort](./collectionsort/)() | Crea una instancia de la clase de ordenación de colección. |
| [CollectionSort](./collectionsort/)(const System::SharedPtr\<Engine::Data::IPdfDictionary\>\&) | Crea una instancia de la clase de ordenación de colección. |
| [get_A](./get_a/)() const | Obtiene el valor de ordenación. Si el valor es un booleano, especifica si el procesador PDF interactivo debe ordenar los elementos de la colección en orden ascendente (true) o descendente (false). Si el valor es una matriz, cada elemento de la matriz será un valor booleano que especifica si la entrada en el mismo índice de la matriz S debe ordenarse en forma ascendente o descendente. Si el número de entradas en la matriz A es mayor que el número de entradas en la matriz S, las entradas adicionales en la matriz A se ignorarán. Si el número de entradas en la matriz A es menor que el número de entradas en la matriz S, se asumirá que las entradas faltantes en la matriz A son true. Valor predeterminado: **true** |
| [get_S](./get_s/)() const | Obtiene el nombre o los nombres de los campos que el procesador PDF interactivo debe usar para ordenar los elementos de la colección. Si el valor es un nombre, identifica un campo descrito en el diccionario de la colección principal. Si el valor es una matriz, cada elemento de la matriz será un nombre que identifica un campo descrito en el diccionario de la colección principal. La forma de matriz se utilizará para permitir que campos adicionales contribuyan al ordenamiento, donde cada campo adicional se usará para romper empates. Más específicamente, si varios diccionarios de elementos de colección tienen el mismo valor para el primer campo nombrado en la matriz, los valores de los campos sucesivos nombrados en la matriz se usarán para ordenar, hasta que se determine un orden único o hasta que se agoten los campos nombrados. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
