---
title: "Метод System::Runtime::InteropServices::Marshal::SecureStringToGlobalAllocAnsi"
linktitle: "SecureStringToGlobalAllocAnsi"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Runtime::InteropServices::Marshal::SecureStringToGlobalAllocAnsi. Копирует содержимое указанной защищённой строки в неуправляемую память, преобразуя её в ANSI‑формат в C++."
type: docs
weight: 1400
url: /ru/cpp/system.runtime.interopservices/marshal/securestringtoglobalallocansi/
---
## Marshal::SecureStringToGlobalAllocAnsi method


Копирует содержимое указанной secure string в неуправляемую память, преобразуя в формат ANSI.

```cpp
static IntPtr System::Runtime::InteropServices::Marshal::SecureStringToGlobalAllocAnsi(const SharedPtr<Security::SecureString> &s)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const SharedPtr\<Security::SecureString\>\& | Защищённая строка. |

### ReturnValue

Адрес в неуправляемой памяти.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SecureString](../../../system.security/securestring/)
* Class [Marshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.PDF for C++](../../../)
