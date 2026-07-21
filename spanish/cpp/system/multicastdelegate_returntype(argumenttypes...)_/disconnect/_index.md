---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect método"
linktitle: "disconnect"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect método. Elimina el delegado especificado de la colección de delegados en C++."
type: docs
weight: 500
url: /es/cpp/system/multicastdelegate_returntype(argumenttypes...)_/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) method


Elimina el delegado especificado de la colección de delegados.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | Callback | El delegado a eliminar de la colección |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) method


Elimina el método no estático especificado del objeto especificado de la colección de delegados.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que se debe eliminar de la colección de delegados |
| ClassType | El tipo del método de objeto que se debe eliminar de la colección de delegados |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| miembro | MemberType ClassType::* | Un puntero al método no estático del objeto especificado |
| obj | ClassType * | Un puntero a un método miembro de objeto que se debe eliminar de la colección de delegados |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Elimina el método no estático especificado del objeto especificado de la colección de delegados.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


| Parámetro | Descripción |
| --- | --- |
| MemberType | El tipo del método no estático que se debe eliminar de la colección de delegados |
| ClassType | El tipo del método de objeto que se debe eliminar de la colección de delegados |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| miembro | MemberType ClassType::* | Un puntero al método no estático del objeto especificado |
| obj | const SharedPtr\<ClassType\>\& | Un puntero compartido a un método miembro de objeto que se debe eliminar de la colección de delegados |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) method


Elimina el objeto MulticastDelegate especificado de la colección de delegados.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | MulticastDelegate\& | Una instancia de la clase MulticastDelegate para eliminar de la colección de delegados |

### ReturnValue

Una referencia al propio objeto

## Ver también

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
