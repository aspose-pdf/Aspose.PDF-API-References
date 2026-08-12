---
title: "Clase System::Range"
linktitle: "Range"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Range. Representa un rango con un índice de inicio y fin. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 5500
url: /es/cpp/system/range/
---
## Range class


Representa un rango con un índice de inicio y fin. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [EndAt](./endat/)(const Index\&) | Crea un rango que comienza al inicio de la colección y termina en el índice final especificado. |
| [Equals](./equals/)(const Range\&) const | Determina si el rango actual es igual al rango especificado. |
| static [get_All](./get_all/)() | Devuelve un [Range](./) que representa toda la colección. |
| [get_End](./get_end/)() const | Obtiene el índice de Fin. |
| [get_Start](./get_start/)() const | Obtiene el índice de Inicio. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el rango actual. |
| [GetOffsetAndLength](./getoffsetandlength/)(int32_t) const | Calcula el desplazamiento inicial basado en cero y la longitud para la longitud de colección especificada. |
| [Range](./range/)() | Construye un rango vacío. |
| [Range](./range/)(const Index\&, const Index\&) | Construye un [Range](./) a partir de los índices de inicio y fin especificados. |
| static [StartAt](./startat/)(const Index\&) | Crea un rango que comienza en el índice de inicio especificado y se extiende hasta el final de la colección. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
