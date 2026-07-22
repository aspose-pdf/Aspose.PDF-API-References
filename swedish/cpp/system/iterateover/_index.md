---
title: "System::IterateOver‑metod"
linktitle: "IterateOver"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IterateOver‑metod. Denna funktionsegenskap omsluter ett enumerable (eller iterable) objekt så att det kan användas med range‑based for‑loop. Detta överlagring för Enumerable‑this med standardmåltyp i C++."
type: docs
weight: 23900
url: /sv/cpp/system/iterateover/
---
## System::IterateOver(const Enumerable *) method


Denna funktionsegenskap omsluter ett enumerable (eller iterable) objekt så att det kan användas med range‑based for‑loop. Detta överlagring för Enumerable‑this med standardmåltyp.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(const Enumerable *) method


Denna funktionsegenskap omsluter ett enumerable (eller iterable) objekt så att det kan användas med range‑based for‑loop. Detta överlagring för Enumerable utan begin(), end()-metoder med måltypargument för (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Måltypen, den måste returneras från iteratorn |
| Enumerable | Typen av ett omslutet objekt |

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Denna funktionsegenskap omsluter ett enumerable (eller iterable) objekt så att det kan användas med range‑based for‑loop. Detta överlagring för Enumerable utan begin(), end()-metoder med måltypargument för (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Måltypen, den måste returneras från iteratorn |
| Enumerable | Typen av ett omslutet objekt |

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Denna funktionsegenskap omsluter ett enumerable (eller iterable) objekt så att det kan användas med range‑based for‑loop. Detta överlagring för Enumerable utan begin(), end()-metoder med standardmåltypargument för (auto& value : IterateOver(enumerable)) analogt med följande C#‑kod foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Denna funktionsegenskap omsluter ett enumerable (eller iterable) objekt så att det kan användas med range‑based for‑loop. Detta överlagring för Enumerable med begin(), end()-metoder med standardmåltypargument för (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Denna funktionsegenskap omsluter ett enumerable (eller iterable) objekt så att det kan användas med range‑based for‑loop. Detta överlagring för Enumerable med begin(), end()-metoder med måltyp samma som original‑value_type för iteratorn.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |
| T | Måltypen som måste returneras från iteratorn |

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Denna funktionsegenskap omsluter ett enumererbart (eller itererbart) objekt så att det kan användas med range‑baserad for‑loop. Denna överlagring för Enumerable med begin()‑ och end()‑metoder med olika måltyp och original‑value_type för iteratorn.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parameter | Beskrivning |
| --- | --- |
| Enumerable | Typen av ett omslutet objekt |
| T | Måltypen som måste returneras från iteratorn |

## Se även

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
