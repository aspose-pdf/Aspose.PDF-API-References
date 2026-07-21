---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::connect método"
linktitle: "conectar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::connect método. Añade el delegado especificado a la colección en C++."
type: docs
weight: 400
url: /es/cpp/system/multicastdelegate_returntype(argumenttypes...)_/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) method


Agrega el delegado especificado a la colección.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | Callback | El delegado a agregar a la colección |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) method


Agrega el método no estático especificado del objeto especificado a la colección de delegados.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que se va a añadir a la colección de delegados |
| ClassType | El tipo del método del objeto que se va a añadir al delegado |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| miembro | MemberType ClassType::* | Un puntero al método no estático del objeto especificado |
| obj | ClassType * | Un puntero a un método miembro de objeto que se va a añadir a la colección de delegados |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Agrega el método no estático especificado del objeto especificado a la colección de delegados.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que se va a añadir a la colección de delegados |
| ClassType | El tipo del método del objeto que se va a añadir a la colección de delegados |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| miembro | MemberType ClassType::* | Un puntero al método no estático del objeto especificado |
| obj | const SharedPtr\<ClassType\>\& | Un puntero compartido a un método miembro de objeto que se va a añadir a la colección de delegados |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) method


Agrega el objeto MulticastDelegate especificado a la colección de delegados.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | MulticastDelegate\& | Una instancia de la clase MulticastDelegate para añadir a la colección de delegados |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) method


Añade el objeto función especificado a la colección de delegados. El objeto función se convierte al tipo de delegado [Callback](../callback/) antes de ser añadido a la colección.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


| Parámetro | Descripción |
| --- | --- |
| R | El tipo de retorno del objeto función que se va a añadir a la colección |
| Args | La lista de argumentos del objeto función que se va a añadir a la colección |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| f | std::function\<R(Args...)> | El objeto función que se va a añadir a la colección |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
