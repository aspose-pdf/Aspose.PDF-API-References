---
title: "System::SmartPtr::SmartPtr konstruktor"
linktitle: "SmartPtr"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::SmartPtr::SmartPtr-konstruktorn. Konverterar typ av refererad array genom att skapa en ny array av annan typ. Användbart om det i C# finns en array-typkonvertering som inte stöds i C++."
type: docs
weight: 100
url: /sv/cpp/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructor


Konverterar typ av refererad array genom att skapa en ny array av annan typ. Användbart om det i C# finns en array‑typcast som inte stöds i C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Beskrivning |
| --- | --- |
| Y | Typ av källarray. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const SmartPtr\<Array\<Y\>\>\& | Pekare till array att skapa en kopia av, men med annan typ av element. |
| läge | SmartPtrMode | Pekarläge. |

## Se även

* Class [SmartPtr](../)
* Class [Array](../../array/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructor


Skapar en [SmartPtr](../) som delar ägandinformation med det ursprungliga värdet av ptr, men håller en orelaterad och ohanterad pekare p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const SmartPtr\<P\>\& | En annan smart pekare för att dela ägandet från. |
| p | Pointee_ * | Pekare till ett objekt att hantera. |
| läge | SmartPtrMode | Pekarläge. |

## Se även

* Class [SmartPtr](../)
* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructor


Kopierar och konstruerar [SmartPtr](../)-objekt. Båda pekarna pekar på samma objekt efteråt. Utför typkonvertering om det är tillåtet.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Beskrivning |
| --- | --- |
| Q | Typ av objekt som pekas på av x. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const SmartPtr\<Q\>\& | Pekare till kopia. |
| läge | SmartPtrMode | Pekarläge. |

## Se även

* Class [SmartPtr](../)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) constructor


Kopierar och konstruerar [SmartPtr](../)-objekt. Båda pekarna pekar på samma objekt efteråt.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const SmartPtr_\& | Pekare till kopia. |
| läge | SmartPtrMode | Pekarläge. |

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(const Y\&) constructor


Initierar tom array. Används för att översätta vissa C#‑kodkonstruktioner.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


| Parameter | Beskrivning |
| --- | --- |
| Y | Platshållare för typen EmptyArrayInitializer. |

## Se även

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructor


Skapar [SmartPtr](../) som pekar på specificerat objekt, eller konverterar rå pekare till [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | Pointee_ * | Pointee. |
| läge | SmartPtrMode | Pekarläge. |

## Se även

* Typedef [Pointee_](../pointee_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) constructor


Flyttar och konstruerar [SmartPtr](../)-objekt. Effektivt byter två pekare plats, om de har samma läge. x kan vara oanvändbar efter anropet.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | SmartPtr_\&& | Pekare att flytta. |
| läge | SmartPtrMode | Pekarläge. |

## Se även

* Typedef [SmartPtr_](../smartptr_/)
* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(SmartPtrMode) constructor


Skapar [SmartPtr](../)-objekt i önskat läge.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge | SmartPtrMode | Pekarläge. |

## Se även

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor


Skapar nullpekare [SmartPtr](../)-objekt i önskat läge.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge | std::nullptr_t | Pekarläge. |

## Se även

* Enum [SmartPtrMode](../../smartptrmode/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
