---
title: "System::Ref metod"
linktitle: "Ref"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Ref metod. Omslag för att säkerställa att Ref(std::ref(DynamicWeakPtr)) fungerar i C++."
type: docs
weight: 37400
url: /sv/cpp/system/ref/
---
## System::Ref(const std::reference_wrapper\<T\>\&) method


Omslag för att säkerställa att Ref(std::ref(DynamicWeakPtr)) fungerar.

```cpp
template<typename T> decltype(Ref(std::declval<T &>())) System::Ref(const std::reference_wrapper<T> &wrapper)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Refererad typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| omslag | const std::reference_wrapper\<T\>\& | std‑omslag för att avpaketera. |

### ReturnValue

Referenstyp definierad i [System](../):: snarare än i std.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) method


Skapar referens till [DynamicWeakPtr](../dynamicweakptr/)‑objektet. Används av översättaren när funktionsargument skickas som referens.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Pekartyp. |
| trunkMode | Läge för smartpekaren själv. |
| weakLeafs | Index för mallargument som SetTemplateWeakPtr‑metoden måste anropas för. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\& | Smartpekare för att skapa referens till. |

### ReturnValue

Smartpekare‑referens.

## Se även

* Class [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Ref(T\&) method


Hjälpfunktion för att erhålla referenser till objekt. Används för att garantera att [System::DynamicWeakPtr](../dynamicweakptr/) uppdaterar det refererade objektet efter tilldelningar.

```cpp
template<typename T> T & System::Ref(T &value)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ att skapa referens till. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | T\& | Värde att skapa referens till. |

### ReturnValue

Referens till värdet som skickas till denna funktion.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
