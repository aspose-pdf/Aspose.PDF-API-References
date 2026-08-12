---
title: "System::setter_decrement_wrap método"
linktitle: "setter_decrement_wrap"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::setter_decrement_wrap método. El traductor traduce las expresiones de predecremento de C# que apuntan a la propiedad de una instancia que tiene setter y getter definidos, en una invocación de esta función (sobrecarga para getter const) en C++."
type: docs
weight: 38700
url: /es/cpp/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) method


El traductor traduce las expresiones de predecremento de C# que apuntan a la propiedad de una instancia que tiene setter y getter definidos, en una invocación de esta función (sobrecarga para getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de la propiedad. |
| Host | - clase de la instancia a modificar |
| HostConstGet | - Host mismo, o su tipo base, donde está definido el getter de la propiedad |
| HostSet | - Host mismo, o su tipo base, donde está definido el setter de la propiedad |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Host *const | Instancia para la que se llamarán los getters y setters. |
| pGetter | T(HostConstGet::*)() const | Puntero a función que apunta a la función getter de la propiedad |
| pSetter | void(HostSet::*)(T) | Puntero a función que apunta a la función setter de la propiedad |

### ReturnValue

El valor de la propiedad antes de incrementarla

## Ver también

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


El traductor traduce las expresiones de predecremento de C# que apuntan a la propiedad de una instancia que tiene setter y getter definidos, en una invocación de esta función (sobrecarga para getter no const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de la propiedad. |
| Host | - clase de la instancia a modificar |
| HostGet | - Host mismo, o su tipo base, donde está definido el getter de la propiedad |
| HostSet | - Host mismo, o su tipo base, donde está definido el setter de la propiedad |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | Host *const | Instancia para la que se llamarán los getters y setters. |
| pGetter | T(HostGet::*)() | Puntero a función que apunta a la función getter de la propiedad |
| pSetter | void(HostSet::*)(T) | Puntero a función que apunta a la función setter de la propiedad |

### ReturnValue

El valor de la propiedad antes de incrementarla

## Ver también

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_decrement_wrap(T(*)(), void(*)(T)) method


El traductor traduce las expresiones de predecremento de C# que apuntan a la propiedad de una clase que tiene setter y getter definidos, en una invocación de esta función.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de la propiedad |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pGetter | T(*)() | Puntero a función que apunta a la función libre del getter de la propiedad |
| pSetter | void(*)(T) | Puntero a función que apunta a la función libre del setter de la propiedad |

### ReturnValue

El valor de la propiedad antes de incrementarla

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
