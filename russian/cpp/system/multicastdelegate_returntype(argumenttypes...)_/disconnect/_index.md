---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect метод"
linktitle: "отключить"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect метод. Удаляет указанный делегат из коллекции делегатов в C++."
type: docs
weight: 500
url: /ru/cpp/system/multicastdelegate_returntype(argumenttypes...)_/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) method


Удаляет указанный делегат из коллекции делегатов.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | Callback | Делегат, который нужно удалить из коллекции |

### ReturnValue

Ссылка на себя

## См. также

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) method


Удаляет указанный нестатический метод указанного объекта из коллекции делегатов.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который должен быть удалён из коллекции делегатов |
| ClassType | Тип метода объекта, который должен быть удалён из коллекции делегатов |

| Параметр | Тип | Описание |
| --- | --- | --- |
| член | MemberType ClassType::* | Указатель на нестатический метод указанного объекта |
| obj | ClassType * | Указатель на метод‑член объекта, который должен быть удалён из коллекции делегатов |

### ReturnValue

Ссылка на себя

## См. также

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Удаляет указанный нестатический метод указанного объекта из коллекции делегатов.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который должен быть удалён из коллекции делегатов |
| ClassType | Тип метода объекта, который должен быть удалён из коллекции делегатов |

| Параметр | Тип | Описание |
| --- | --- | --- |
| член | MemberType ClassType::* | Указатель на нестатический метод указанного объекта |
| obj | const SharedPtr\<ClassType\>\& | Разделяемый указатель на метод‑член объекта, который должен быть удалён из коллекции делегатов |

### ReturnValue

Ссылка на себя

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) method


Удаляет указанный объект MulticastDelegate из коллекции делегатов.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | MulticastDelegate\& | Экземпляр класса MulticastDelegate для удаления из коллекции делегатов |

### ReturnValue

Ссылка на себя

## См. также

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
