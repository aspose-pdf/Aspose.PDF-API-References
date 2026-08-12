---
title: "Espacio de nombres System::Collections"
linktitle: "System::Collections"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el espacio de nombres System::Collections en C++."
type: docs
weight: 2900
url: /es/cpp/system.collections/
---



## Clases

| Clase | Descripción |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) de bits que pueden ser accedidos por índice. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [BitArrayPtr](./bitarrayptr/) | Puntero a [BitArray](./bitarray/). Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe ser asignado en la pila y pasado a funciones ya sea por valor o por referencia constante. |
| [CollectionBase](./collectionbase/) | Proporciona una clase base abstracta para una colección fuertemente tipada. |
| [ICollection](./icollection/) | Define la interfaz de colección no genérica. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) es la interfaz base para todas las colecciones no genéricas que pueden enumerarse. |
| [IEnumerator](./ienumerator/) | Interfaz del enumerador que puede usarse para iterar a través de algunos elementos. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Wrapper que crea una implementación no genérica de [IEnumerator](./ienumerator/) sobre el iterador genérico [IEnumeratorImplRefType](./ienumeratorimplreftype/) - envoltorio para los tipos de referencia. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Wrapper que crea una implementación no genérica de [IEnumerator](./ienumerator/) sobre el iterador genérico [IEnumeratorImplRefType](./ienumeratorimplreftype/) - envoltorio para los tipos de valor. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Representa una colección no genérica de objetos que pueden ser accedidos individualmente por índice. |
| [IListImplRefType](./ilistimplreftype/) | Stub que implementa la interfaz [System::Collections::IList](./ilist/) sobre el objeto [System::Collections::Generic::List](../system.collections.generic/list/) Implementación para tipos de referencia. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub que implementa la interfaz [System::Collections::IList](./ilist/) sobre el objeto [System::Collections::Generic::List](../system.collections.generic/list/) Implementación para tipos de valor. |
| [IListWrapper](./ilistwrapper/) | Interfaz para soportar la conversión de colecciones genéricas a no genéricas. |
| [Invalidatable](./invalidatable/) | Clase que permite rastrear el estado de sus descendientes a través de objetos [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | Clase que implementa rastreadores de objetos [Invalidatable](./invalidatable/). |
