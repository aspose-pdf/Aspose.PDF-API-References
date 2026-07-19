---
title: "Метод System::Ref"
linktitle: "Ref"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Ref. Обёртка, обеспечивающая работу Ref(std::ref(DynamicWeakPtr)) в C++."
type: docs
weight: 37400
url: /ru/cpp/system/ref/
---
## System::Ref(const std::reference_wrapper\<T\>\&) method


Обёртка, обеспечивающая работу Ref(std::ref(DynamicWeakPtr)).

```cpp
template<typename T> decltype(Ref(std::declval<T &>())) System::Ref(const std::reference_wrapper<T> &wrapper)
```


| Параметр | Описание |
| --- | --- |
| T | Ссылаемый тип. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| обёртка | const std::reference_wrapper\<T\>\& | std-обёртка для развёртывания. |

### ReturnValue

Тип ссылки, определённый в [System](../)::, а не в std.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) method


Создаёт ссылку на объект [DynamicWeakPtr](../dynamicweakptr/). Используется транслятором при передаче аргументов функции по ссылке.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


| Параметр | Описание |
| --- | --- |
| T | Тип указываемого. |
| trunkMode | Режим самого умного указателя. |
| weakLeafs | Индексы шаблонных аргументов, для которых необходимо вызвать метод SetTemplateWeakPtr. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\& | Умный указатель для создания ссылки на. |

### ReturnValue

Ссылка умного указателя.

## См. также

* Class [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Ref(T\&) method


Вспомогательная функция для получения ссылок на объекты. Используется для гарантии того, что [System::DynamicWeakPtr](../dynamicweakptr/) обновляет ссылочный объект после присваиваний.

```cpp
template<typename T> T & System::Ref(T &value)
```


| Параметр | Описание |
| --- | --- |
| T | Тип для создания ссылки на. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T\& | Значение для создания ссылки на. |

### ReturnValue

Ссылка на значение, переданное в эту функцию.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
