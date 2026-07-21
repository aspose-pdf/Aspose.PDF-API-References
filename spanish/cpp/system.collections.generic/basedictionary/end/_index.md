---
title: "System::Collections::Generic::BaseDictionary::end método"
linktitle: "end"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::BaseDictionary::end método. Devuelve un iterador al KVPair-wrapper para el elemento clave-valor que sigue al último elemento del contenedor. Implementado al estilo C# - el iterador debe devolver el objeto KVPair con la interfaz get_Key() y get_Value(). Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido en C++."
type: docs
weight: 1100
url: /es/cpp/system.collections.generic/basedictionary/end/
---
## BaseDictionary::end method


Devuelve un iterador al KVPair-wrapper para el elemento clave-valor que sigue al último elemento del contenedor. Implementado al estilo C# - el iterador debe devolver el KVPair-object con la interfaz get_Key() y get_Value(). Este elemento actúa como un marcador de posición; intentar acceder a él produce un comportamiento indefinido.

```cpp
const_iterator System::Collections::Generic::BaseDictionary<Map>::end() const noexcept
```


### ReturnValue

Un iterador que apunta al elemento teórico colocado después del elemento final de la colección.

## Ver también

* Typedef [const_iterator](../const_iterator/)
* Class [BaseDictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
