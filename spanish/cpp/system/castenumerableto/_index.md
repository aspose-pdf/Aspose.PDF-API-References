---
title: "Método System::CastEnumerableTo"
linktitle: "CastEnumerableTo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::CastEnumerableTo. Realiza el casting explícito de los elementos del objeto enumerable especificado a un tipo diferente en C++."
type: docs
weight: 16000
url: /es/cpp/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) method


Realiza el casting explícito de los elementos del objeto enumerable especificado a un tipo diferente.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que se deben castear estáticamente los elementos del objeto enumerable |
| From | El tipo del objeto enumerable |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enumerable | const From\& | Objeto enumerable que contiene los elementos a castear |

### ReturnValue

Un puntero a una nueva colección que contiene elementos del tipo **To** equivalentes a los elementos de **enumerable**

## Ver también

* Class [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::CastEnumerableTo(const From\&) method


Realiza el casting explícito de los elementos del objeto enumerable especificado a un tipo diferente.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que se deben castear estáticamente los elementos del objeto enumerable |
| From | El tipo del objeto enumerable |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enumerable | const From\& | es heredero del objeto Enumerable con el método get_Count definido y que contiene los elementos a castear |

### ReturnValue

Un puntero a una nueva colección que contiene elementos del tipo **To** equivalentes a los elementos de **enumerable**

## Ver también

* Class [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
