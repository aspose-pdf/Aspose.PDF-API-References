---
title: "System::setter_increment_wrap-metod"
linktitle: "setter_increment_wrap"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::setter_increment_wrap-metod. Översättaren översätter C#'s inkrementuttryck som riktar sig mot en klass' egenskap som har både setter och getter definierade, till ett anrop av denna funktion i C++."
type: docs
weight: 39800
url: /sv/cpp/system/setter_increment_wrap/
---
## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


Översättaren översätter C#'s inkrementuttryck som riktar sig mot en klass' egenskap som har både setter och getter definierade, till ett anrop av denna funktion.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen på egenskapen |
| Host | - klass av instans som ska modifieras |
| HostGet | - Host själv, eller dess basklass, där egenskapens getter är definierad |
| HostSet | - Host själv, eller dess basklass, där egenskapens setter är definierad |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | Host *const | En pekare till ett objekt vars egenskap ska inkrementeras. |
| pGetter | T(HostGet::*)() | Funktionspekare som pekar på egenskapens getter‑metod. |
| pSetter | void(HostSet::*)(T) | Funktionspekare som pekar på egenskapens setter‑metod. |

### ReturnValue

Det inkrementerade värdet av egenskapen.

## Se även

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_increment_wrap(T(*)(), void(*)(T)) method


Översättaren översätter C#'s inkrementuttryck som riktar sig mot en klass' egenskap som har både setter och getter definierade, till ett anrop av denna funktion.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen på egenskapen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pGetter | T(*)() | Funktionspekare som pekar på egenskapens fristående getter-funktion |
| pSetter | void(*)(T) | Funktionspekare som pekar på egenskapens fristående setter-funktion |

### ReturnValue

Det inkrementerade värdet av egenskapen.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
