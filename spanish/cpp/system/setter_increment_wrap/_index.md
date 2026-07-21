---
title: "Método System::setter_increment_wrap"
linktitle: "setter_increment_wrap"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::setter_increment_wrap. El traductor traduce las expresiones de incremento de C#''s que apuntan a la propiedad de la clase'' que tiene setter y getter definidos, en una invocación de esta función en C++."
type: docs
weight: 39800
url: /es/cpp/system/setter_increment_wrap/
---
## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


El traductor traduce las expresiones de incremento de C#'s que apuntan a la propiedad de la clase' que tiene setter y getter definidos, en una invocación de esta función.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de la propiedad |
| Host | - clase de la instancia a modificar |
| HostGet | - Host mismo, o su tipo base, donde está definido el getter de la propiedad |
| HostSet | - Host mismo, o su tipo base, donde está definido el setter de la propiedad |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Host *const | Un puntero a un objeto cuya propiedad será incrementada |
| pGetter | T(HostGet::*)() | Puntero a función que apunta al método getter de la propiedad |
| pSetter | void(HostSet::*)(T) | Puntero a función que apunta al método setter de la propiedad |

### ReturnValue

El valor incrementado de la propiedad

## Ver también

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_increment_wrap(T(*)(), void(*)(T)) method


El traductor traduce las expresiones de incremento de C#'s que apuntan a la propiedad de la clase' que tiene setter y getter definidos, en una invocación de esta función.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de la propiedad |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pGetter | T(*)() | Puntero a función que apunta a la función libre del getter de la propiedad |
| pSetter | void(*)(T) | Puntero a función que apunta a la función libre del setter de la propiedad |

### ReturnValue

El valor incrementado de la propiedad

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
