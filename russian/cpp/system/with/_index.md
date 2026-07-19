---
title: "Метод System::With"
linktitle: "With"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::With. Клонирует ссылочную запись и применяет к ней инициализирующий функтор в C++."
type: docs
weight: 44900
url: /ru/cpp/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) method


Клонирует ссылочную запись и применяет к ней инициализирующий функтор.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


| Параметр | Описание |
| --- | --- |
| T | Тип записи для клонирования. |
| A | Тип инициализирующего функтора. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| запись | const SharedPtr\<T\>\& | Умный указатель на объект для клонирования и инициализации. |
| инициализатор | const A\& | Функтор инициализации применяется к клону записи. |

### ReturnValue

Умный указатель на клонированную запись.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::With(const T\&, const A\&) method


Копирует структуру записи и применяет к ней функтор инициализации.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


| Параметр | Описание |
| --- | --- |
| T | Тип записи для копирования. |
| A | Тип инициализирующего функтора. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| запись | const T\& | Запись для копирования и инициализации. |
| инициализатор | const A\& | Функтор инициализации применяется к копии записи. |

### ReturnValue

Скопированная запись.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
