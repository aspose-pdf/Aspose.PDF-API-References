---
title: "System::StaticCastArray‑metod"
linktitle: "StaticCastArray"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::StaticCastArray‑metod. Utför kastning av element i den angivna arrayen till en annan typ. Överskuggning för fall där From är SmartPtr‑objekt i C++."
type: docs
weight: 44600
url: /sv/cpp/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Utför kastning av element i den angivna arrayen till en annan typ. Överskuggning för fall där From är [SmartPtr](../smartptr/) objekt.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Parameter | Beskrivning |
| --- | --- |
| Till | Typen att kasta elementen i den angivna arrayen till |
| From | Typen av element i array-elementen som ska kastas |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| från | const System::SharedPtr\<System::Array\<From\>\>\& | Delad pekare till arrayen som innehåller elementen som ska kastas |

### ReturnValue

En pekare till en ny array som innehåller element av typen **To** motsvarande elementen i **from**

## Deprecated
Tillagd för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Utför kastning av element i den angivna arrayen till en annan typ. Överskuggning för fall där From är Boxable och To är [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Parameter | Beskrivning |
| --- | --- |
| Till | Typen att kasta elementen i den angivna arrayen till |
| From | Typen av element i array-elementen som ska kastas |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| från | const System::SharedPtr\<System::Array\<From\>\>\& | Delad pekare till arrayen som innehåller elementen som ska kastas |

### ReturnValue

En pekare till en ny array som innehåller element av typen **To** motsvarande elementen i **from**

## Deprecated
Tillagd för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
