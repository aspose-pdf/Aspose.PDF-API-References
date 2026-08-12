---
title: "Clase System::Index"
linktitle: "Index"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Index. Representa un índice en una colección. El índice puede ser desde el inicio o desde el final. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 4100
url: /es/cpp/system/index/
---
## Index class


Representa un índice en una colección. El índice puede ser desde el inicio o desde el final. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(const Index\&) const | Determina si la instancia actual y el [Index](./) especificado representan la misma posición. |
| static [FromEnd](./fromend/)(int32_t) | Crea un [Index](./) que es relativo al final de la colección. |
| static [get_End](./get_end/)() | Obtiene un objeto [Index](./) que representa el final de una colección. |
| [get_IsFromEnd](./get_isfromend/)() const | Obtiene un valor que indica si el índice es desde el final. |
| static [get_Start](./get_start/)() | Obtiene un objeto [Index](./) que representa el inicio de una colección. |
| [get_Value](./get_value/)() const | Obtiene el valor del índice. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el índice actual. |
| [GetOffset](./getoffset/)(int32_t) const | Convierte el [Index](./) actual en un desplazamiento desde el inicio de una colección con la longitud especificada. |
| [Index](./index/)() | Construye una instancia que representa el inicio de una colección. |
| [Index](./index/)(int32_t) | Construye una instancia que representa la posición especificada desde el inicio de una colección. |
| [Index](./index/)(int32_t, bool) | Construye una instancia que representa el índice especificado. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
