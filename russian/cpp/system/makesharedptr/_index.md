---
title: "System::MakeSharedPtr метод"
linktitle: "MakeSharedPtr"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::MakeSharedPtr метод. Преобразует обычный указатель в умный указатель. Перегрузка для const‑указателей. Полезно, например, при использовании ''this'' переменной в методах C#, переводимых как const в C++."
type: docs
weight: 25600
url: /ru/cpp/system/makesharedptr/
---
## System::MakeSharedPtr(const X *) method


Преобразует обычный указатель в умный указатель. Перегрузка для const‑указателей. Полезно, например, при использовании 'this' переменной в методах C#, переводимых как const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


| Параметр | Описание |
| --- | --- |
| X | Тип указываемого. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| p | const X * | Обычный указатель на объект. |

### ReturnValue

Разделяемый умный указатель на объект.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::MakeSharedPtr(X *) method


Преобразует обычный указатель в умный указатель.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


| Параметр | Описание |
| --- | --- |
| X | Тип указываемого. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| p | X * | Обычный указатель на объект. |

### ReturnValue

Разделяемый умный указатель на объект.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
