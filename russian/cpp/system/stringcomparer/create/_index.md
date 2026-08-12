---
title: "System::StringComparer::Create метод"
linktitle: "Создать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::StringComparer::Create метод. Создаёт сравниватель, специфичный для культуры, в C++."
type: docs
weight: 100
url: /ru/cpp/system/stringcomparer/create/
---
## StringComparer::Create method


Создаёт сравниватель, специфичный для культуры.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| культура | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Культура, для которой создаётся сравниватель. |
| ignoreCase | bool | Нужно ли, чтобы сравниватель игнорировал регистр. |

### ReturnValue

Указатель на только что созданный объект сравнивателя.

## См. также

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [StringComparer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
