---
title: "System::Default-metod"
linktitle: "Standard"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Default-metod. Returnerar referensen till den enda standardkonstruktade instansen av undantagstypen i C++."
type: docs
weight: 16700
url: /sv/cpp/system/default/
---
## System::Default() method


Returnerar referensen till den enda standardkonstruktade instansen av undantagstypen.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen vars instans returneras |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Default() method


Returnerar referensen till den enda standardkonstruktade instansen av den icke-undantagstypen.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen vars instans returneras |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
