---
title: "System::Delegate< ReturnType(ArgumentTypes...)>::Delegate metod"
linktitle: "Delegate"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Delegate< ReturnType(ArgumentTypes...)>::Delegate metod. Standardkonstruktor. Skapar delegate-objektet som inte pekar på något i C++."
type: docs
weight: 100
url: /sv/cpp/system/delegate_returntype(argumenttypes...)_/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() method


Standardkonstruktor. Skapar delegatobjektet som inte pekar på någonting.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Se även

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) method




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Se även

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) method


Flyttkopieringskonstruktor. Tar äganderätten till en entitet som pekas på av den angivna delegaten.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | Delegate\&& | Delegate-objektet att flytta den pekade entiteten från |

## Se även

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) method


Konstruktor. Skapar en delegat från det angivna funktionsobjektet.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjekt som accepteras av konstruktorn som ett argument |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functor_tag | int | Ett dummy heltalsvärde; detta argument används för att lösa tvetydighet |
| functor | T\& | Ett funktionsobjekt som den nykonstruerade delegaten kommer att peka på |

## Se även

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) method


Flyttkonstruktor. Skapar en delegat från det angivna funktionsobjektet.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av funktionsobjekt som accepteras av konstruktorn som ett argument |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functor_tag | long | Ett dummy heltalsvärde; detta argument används för att lösa tvetydighet |
| functor | T\&& | Ett funktionsobjekt som den nykonstruerade delegaten kommer att peka på |

## Se även

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) method


Konstruktor. Skapar en delegat som pekar på den angivna icke-statiska metoden för det angivna objektet.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```


| Parameter | Beskrivning |
| --- | --- |
| MemberType | Typen av den icke-statiska metoden som konstruktorn accepterar som argument |
| ClassType | Typen av objektet som konstruktorn accepterar som argument |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| medlem | MemberType ClassType::* | En pekare till den icke-statiska metoden som den nysskapade delegaten kommer att peka på |
| obj | ClassType * | En pekare till ett objektmedlemsmetod som den nysskapade delegaten kommer att peka på |

## Se även

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) method


Konstruktor. Skapar en delegat som pekar på den angivna icke-statiska metoden för det angivna objektet.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| MemberType | Typen av den icke-statiska metoden som konstruktorn accepterar som argument |
| ClassType | Typen av objektet som konstruktorn accepterar som argument |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| medlem | MemberType MemberClass::* | En pekare till den icke-statiska metoden som den nysskapade delegaten kommer att peka på |
| obj | const SharedPtr\<ClassType\>\& | En delad pekare till ett objektmedlemsmetod som den nysskapade delegaten kommer att peka på |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) method


Skapar ett delegatobjekt som pekar på ett std::function-funktionsobjekt.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```


| Parameter | Beskrivning |
| --- | --- |
| R | Returtypen för funktionsobjektet som konstruktorn accepterar som argument |
| Argument | Argumentlistan för funktionsobjektet som konstruktorn accepterar som argument |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| f | std::function\<R(Args...)\> | Ett funktionsobjekt som den nysskapade delegatobjektet ska peka på |

## Se även

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) method


Konstruktor. Skapar en delegat från den angivna pekaren till funktionsobjektet som genererats av std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```


| Parameter | Beskrivning |
| --- | --- |
| Den | Typen av funktionsobjektet som genererats av std::bind() och som konstruktorn accepterar som argument |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funktion | T | Pekare till ett "bind-uttryck" - en funktionspekare genererad av std::bind() - som den nysskapade Delegate-instansen kommer att peka på |

## Se även

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) method


Konstruktor. Skapar ett delegatobjekt från den angivna pekaren till en fri funktion eller statisk metod.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```


| Parameter | Beskrivning |
| --- | --- |
| Den | Typen av funktions- eller statisk metodpekare som konstruktorn accepterar som argument |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funktion | T | Pekare till en funktion eller en statisk metod som den nysskapade Delegate-instansen kommer att peka på |

## Se även

* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
