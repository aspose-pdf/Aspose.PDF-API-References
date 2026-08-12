---
title: "Método System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode"
linktitle: "ObtenerCódigoHash"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode. Obtiene el código hash de un tipo arbitrario. Llama a Object::GetHashCode() para hacerlo en C++."
type: docs
weight: 100
url: /es/cpp/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode method


Obtiene el código hash de un tipo arbitrario. Llama a [Object::GetHashCode()](../../../system/object/gethashcode/) para hacerlo.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo para el cual obtener el código hash. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<T\> const\& | [Object](../../../system/object/) del cual obtener información. |

### ReturnValue

Valor del código hash calculado por la implementación objetivo.

## Ver también

* Class [SmartPtr](../../../system/smartptr/)
* Class [RuntimeHelpers](../)
* Namespace [System::Runtime::CompilerServices](../../)
* Library [Aspose.PDF for C++](../../../)
