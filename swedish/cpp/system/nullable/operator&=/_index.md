---
title: "System::Nullable::operator&= metod"
linktitle: "operator&="
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Nullable::operator&= metod. Tillämpar operator&=() på värdet som representeras av det aktuella objektet med det angivna värdet som ett högersidig argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system/nullable/operator&=/
---
## Nullable::operator&= method


Tillämpar [operator&=()](./) på värdet som representeras av det aktuella objektet med det angivna värdet som ett högersidig argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


| Parameter | Beskrivning |
| --- | --- |
| T1 | Mallparametern för att få SFINAE att fungera. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | bool | Ett booleskt värde som används som ett högersidigt värde för [operator&=()](./) som tillämpas på värdet som representeras av det aktuella objektet. |

### ReturnValue

En referens till sig själv.

## Se även

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
