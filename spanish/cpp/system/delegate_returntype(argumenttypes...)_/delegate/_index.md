---
title: "System::Delegate< ReturnType(ArgumentTypes...)>::Delegate método"
linktitle: "Delegado"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Delegate< ReturnType(ArgumentTypes...)>::Delegate método. Constructor predeterminado. Construye el objeto delegado que no apunta a nada en C++."
type: docs
weight: 100
url: /es/cpp/system/delegate_returntype(argumenttypes...)_/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() method


Constructor por defecto. Construye el objeto delegate que no apunta a nada.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Ver también

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) method




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Ver también

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) method


Constructor de copia móvil. Toma la propiedad de una entidad apuntada por el delegate especificado.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | Delegate\&& | El objeto Delegate del cual mover la entidad apuntada |

## Ver también

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) method


Constructor. Construye un delegate a partir del objeto función especificado.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función aceptado por el constructor como argumento |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functor_tag | int | Un valor entero ficticio; este argumento se usa para resolver ambigüedades |
| functor | T\& | Un objeto función al que apuntará el delegado recién construido |

## Ver también

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) method


Constructor de movimiento. Construye un delegate a partir del objeto función especificado.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función aceptado por el constructor como argumento |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functor_tag | long | Un valor entero ficticio; este argumento se usa para resolver ambigüedades |
| functor | T\&& | Un objeto función al que apuntará el delegado recién construido |

## Ver también

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) method


Constructor. Construye un delegate que apunta al método no estático especificado del objeto especificado.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que el constructor acepta como argumento |
| ClassType | El tipo del objeto aceptado por el constructor como argumento |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| miembro | MemberType ClassType::* | Un puntero al método no estático al que apuntará el delegado recién creado |
| obj | ClassType * | Un puntero a un método miembro de objeto al que apuntará el delegado recién creado |

## Ver también

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) method


Constructor. Construye un delegate que apunta al método no estático especificado del objeto especificado.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que el constructor acepta como argumento |
| ClassType | El tipo del objeto aceptado por el constructor como argumento |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| miembro | MemberType MemberClass::* | Un puntero al método no estático al que apuntará el delegado recién creado |
| obj | const SharedPtr\<ClassType\>\& | Un puntero fragmentado a un método miembro de objeto que será apuntado por el delegado recién creado |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) method


Construye un objeto delegate que apunta a un objeto función std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


| Parámetro | Descripción |
| --- | --- |
| R | El tipo de retorno del objeto función aceptado por el constructor como argumento |
| Args | La lista de argumentos del objeto función aceptado por el constructor como argumento |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Un objeto función al que será apuntado por el objeto delegado recién creado |

## Ver también

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) method


Constructor. Construye un delegate a partir del puntero especificado al objeto función generado por std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


| Parámetro | Descripción |
| --- | --- |
| El | Tipo del objeto función generado por std::bind() aceptado por el constructor como argumento |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| función | T | Puntero a una "expresión bind" - un puntero a función generado por std::bind() - que será apuntado por la instancia Delegate recién creada |

## Ver también

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) method


Constructor. Construye un objeto delegate a partir del puntero especificado a una función libre o método estático.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


| Parámetro | Descripción |
| --- | --- |
| El | Tipo del puntero a función o método estático aceptado por el constructor como argumento |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| función | T | Puntero a una función o a un método estático que será apuntado por la instancia Delegate recién creada |

## Ver también

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
