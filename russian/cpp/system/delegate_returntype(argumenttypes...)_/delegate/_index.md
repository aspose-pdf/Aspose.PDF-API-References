---
title: "System::Delegate< ReturnType(ArgumentTypes...)>::Delegate метод"
linktitle: "Delegate"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Delegate< ReturnType(ArgumentTypes...)>::Delegate метод. Конструктор по умолчанию. Создаёт объект delegate, который не указывает ни на что в C++."
type: docs
weight: 100
url: /ru/cpp/system/delegate_returntype(argumenttypes...)_/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() method


Конструктор по умолчанию. Создаёт объект делегата, который не указывает ни на что.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## См. также

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) method




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## См. также

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) method


Конструктор перемещения копии. Перехватывает владение сущностью, на которую указывает указанный делегат.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| o | Delegate\&& | Объект Delegate, из которого перемещается указываемая сущность |

## См. также

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) method


Конструктор. Создаёт делегат из указанного объекта‑функции.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


| Параметр | Описание |
| --- | --- |
| T | Тип функционального объекта, принимаемого конструктором в качестве аргумента |

| Параметр | Тип | Описание |
| --- | --- | --- |
| functor_tag | int | Заглушечное целочисленное значение; этот аргумент используется для разрешения неоднозначности |
| functor | T\& | Объект-функция, на который будет указывать вновь созданный делегат |

## См. также

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) method


Конструктор перемещения. Создаёт делегат из указанного объекта‑функции.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


| Параметр | Описание |
| --- | --- |
| T | Тип функционального объекта, принимаемого конструктором в качестве аргумента |

| Параметр | Тип | Описание |
| --- | --- | --- |
| functor_tag | long | Заглушечное целочисленное значение; этот аргумент используется для разрешения неоднозначности |
| functor | T\&& | Объект-функция, на который будет указывать вновь созданный делегат |

## См. также

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) method


Конструктор. Создаёт делегат, указывающий на указанный нестатический метод указанного объекта.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который конструктор принимает в качестве аргумента |
| ClassType | Тип объекта, принимаемого конструктором в качестве аргумента |

| Параметр | Тип | Описание |
| --- | --- | --- |
| член | MemberType ClassType::* | Указатель на нестатический метод, на который будет указывать вновь созданный делегат |
| obj | ClassType * | Указатель на метод-член объекта, на который будет указывать вновь созданный делегат |

## См. также

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) method


Конструктор. Создаёт делегат, указывающий на указанный нестатический метод указанного объекта.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


| Параметр | Описание |
| --- | --- |
| MemberType | Тип нестатического метода, который конструктор принимает в качестве аргумента |
| ClassType | Тип объекта, принимаемого конструктором в качестве аргумента |

| Параметр | Тип | Описание |
| --- | --- | --- |
| член | MemberType MemberClass::* | Указатель на нестатический метод, на который будет указывать вновь созданный делегат |
| obj | const SharedPtr\<ClassType\>\& | Указатель shared‑pointer на метод‑член объекта, на который будет указывать вновь созданный делегат |

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) method


Создаёт объект делегата, указывающий на объект функции std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


| Параметр | Описание |
| --- | --- |
| R | Тип возвращаемого значения объекта‑функции, принимаемого конструктором в качестве аргумента |
| Аргументы | Список аргументов объекта‑функции, принимаемого конструктором в качестве аргумента |

| Параметр | Тип | Описание |
| --- | --- | --- |
| f | std::function\<R(Args...)\> | Объект‑функция, на который будет указывать вновь созданный объект делегата |

## См. также

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) method


Конструктор. Создаёт делегат из указанного указателя на объект‑функцию, созданный с помощью std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


| Параметр | Описание |
| --- | --- |
| Эта | Тип объекта‑функции, сгенерированного std::bind() и принимаемого конструктором в качестве аргумента |

| Параметр | Тип | Описание |
| --- | --- | --- |
| функция | T | Указатель на "bind expression" — указатель на функцию, сгенерированный std::bind() — на который будет указывать вновь созданный экземпляр Delegate |

## См. также

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) method


Конструктор. Создаёт объект делегата из указанного указателя на свободную функцию или статический метод.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


| Параметр | Описание |
| --- | --- |
| Эта | Тип указателя на функцию или статический метод, принимаемого конструктором в качестве аргумента |

| Параметр | Тип | Описание |
| --- | --- | --- |
| функция | T | Указатель на функцию или статический метод, на который будет указывать вновь созданный экземпляр Delegate |

## См. также

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
