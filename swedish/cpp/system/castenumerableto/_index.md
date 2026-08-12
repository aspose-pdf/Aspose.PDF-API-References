---
title: "System::CastEnumerableTo metod"
linktitle: "CastEnumerableTo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::CastEnumerableTo metod. Utför den explicita omvandlingen av element i det angivna enumerable‑objektet till en annan typ i C++."
type: docs
weight: 16000
url: /sv/cpp/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) method


Utför den explicita omvandlingen av element i det angivna enumerable‑objektet till en annan typ.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


| Parameter | Beskrivning |
| --- | --- |
| Till | Typen att statiskt kasta elementen i enumerable‑objektet till |
| From | Typen av enumerable‑objekt |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enumerable | const From\& | Enumerable‑objekt som innehåller elementen som ska kastas |

### ReturnValue

En pekare till en ny samling som innehåller element av typen **To** som är ekvivalenta med elementen i **enumerable**

## Se även

* Class [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::CastEnumerableTo(const From\&) method


Utför den explicita omvandlingen av element i det angivna enumerable‑objektet till en annan typ.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


| Parameter | Beskrivning |
| --- | --- |
| Till | Typen att statiskt kasta elementen i enumerable‑objektet till |
| From | Typen av enumerable‑objekt |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enumerable | const From\& | är en arvtagare av Enumerable‑objekt med definierad get_Count‑metod och som innehåller elementen som ska kastas |

### ReturnValue

En pekare till en ny samling som innehåller element av typen **To** som är ekvivalenta med elementen i **enumerable**

## Se även

* Class [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
