---
title: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::connect метод"
linktitle: "соединить"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::MulticastDelegate< ReturnType(ArgumentTypes...)>::connect метод. Добавляет указанный делегат в коллекцию в C++."
type: docs
weight: 400
url: /ru/cpp/system/multicastdelegate_returntype(argumenttypes...)_/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) method


Добавляет указанный делегат в коллекцию.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | Callback | Делегат для добавления в коллекцию |

### ReturnValue

Ссылка на себя

## См. также

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) method


Добавляет указанный нестатический метод указанного объекта в коллекцию делегатов.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который будет добавлен в коллекцию делегатов |
| ClassType | Тип метода объекта, который будет добавлен в делегат |

| Параметр | Тип | Описание |
| --- | --- | --- |
| член | MemberType ClassType::* | Указатель на нестатический метод указанного объекта |
| obj | ClassType * | Указатель на метод‑член объекта, который будет добавлен в коллекцию делегатов |

### ReturnValue

Ссылка на себя

## См. также

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Добавляет указанный нестатический метод указанного объекта в коллекцию делегатов.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который будет добавлен в коллекцию делегатов |
| ClassType | Тип метода объекта, который будет добавлен в коллекцию делегатов |

| Параметр | Тип | Описание |
| --- | --- | --- |
| член | MemberType ClassType::* | Указатель на нестатический метод указанного объекта |
| obj | const SharedPtr\<ClassType\>\& | Разделяемый указатель на метод‑член объекта, который будет добавлен в коллекцию делегатов |

### ReturnValue

Ссылка на себя

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) method


Добавляет указанный объект MulticastDelegate в коллекцию делегатов.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | MulticastDelegate\& | Экземпляр класса MulticastDelegate для добавления в коллекцию делегатов |

### ReturnValue

Ссылка на себя

## См. также

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) method


Добавляет указанный функциональный объект в коллекцию делегатов. Функциональный объект преобразуется в тип делегата [Callback](../callback/) перед добавлением в коллекцию.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


| Параметр | Описание |
| --- | --- |
| R | Тип возвращаемого значения функционального объекта, который добавляется в коллекцию |
| Аргументы | Список аргументов функционального объекта, который добавляется в коллекцию |

| Параметр | Тип | Описание |
| --- | --- | --- |
| f | std::function\<R(Args...)\> | Функциональный объект для добавления в коллекцию |

### ReturnValue

Ссылка на себя

## См. также

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
