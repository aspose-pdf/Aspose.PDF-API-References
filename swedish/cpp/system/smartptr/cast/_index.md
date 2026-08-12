---
title: "System::SmartPtr::Cast metod"
linktitle: "Cast"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::SmartPtr::Cast metod. Kastar pekaren till dess egen typ i C++."
type: docs
weight: 400
url: /sv/cpp/system/smartptr/cast/
---
## SmartPtr::Cast() const method


Kastar pekare till dess egen typ.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parameter | Beskrivning |
| --- | --- |
| Y | Måltyp för det pekade objektet. |
| Check | Flaggor för att kasta undantag om ingen kastning är tillgänglig. |

### ReturnValue

Pekare av ändrad typ som alltid är i delat läge.

## Se även

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::Cast() const method


Kastar pekare till basklass med static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parameter | Beskrivning |
| --- | --- |
| Y | Måltyp för det pekade objektet. |
| Check | Flaggor för att kasta undantag om ingen kastning är tillgänglig. |

### ReturnValue

Pekare av ändrad typ som alltid är i delat läge.

## Se även

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::Cast() const method


Kastar pekare till avledd typ med dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parameter | Beskrivning |
| --- | --- |
| Y | Måltyp för det pekade objektet. |
| Check | Flaggor för att kasta undantag om ingen kastning är tillgänglig. |

### ReturnValue

Pekare av ändrad typ som alltid är i delat läge. Kastar InvalidCastException om ingen konvertering är tillgänglig.

## Se även

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SmartPtr::Cast() const method


Kastar pekare till avledd typ med dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


| Parameter | Beskrivning |
| --- | --- |
| Y | Måltyp för det pekade objektet. |
| Check | Flaggor för att kasta undantag om ingen kastning är tillgänglig. |

### ReturnValue

Pekare av ändrad typ som alltid är i delat läge. Returnerar nullptr om ingen konvertering är tillgänglig.

## Se även

* Class [SmartPtr](../)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
