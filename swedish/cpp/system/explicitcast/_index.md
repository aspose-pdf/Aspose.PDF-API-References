---
title: "System::ExplicitCast metod"
linktitle: "ExplicitCast"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ExplicitCast method. Kastar källtypen till resultattypen med en explicit typkonvertering. Används när käll- och resultattyperna är desamma i C++."
type: docs
weight: 19000
url: /sv/cpp/system/explicitcast/
---
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används när käll- och resultattyperna är desamma.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Enum [Base64FormattingOptions](../base64formattingoptions/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används när en enkel konstruktorliknande konvertering behövs.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för undantagsomslag.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Typedef [Exception](../exception/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för att kasta ett objekt till ett undantag.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används när både källan och resultatet är smarta pekare (utan explicit [SmartPtr<...>](../smartptr/) i resultattypen).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används när både källan och resultatet är smarta pekare (med explicit [SmartPtr<...>](../smartptr/) i resultattypen).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för att avpaketera ett objekt till en nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för att paketera en nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för att avpaketera ett nullable-objekt.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för enum-paketering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för att kopiera värdetyper till heapen när värdetypen bör refereras som en smart pekare (i generiska typer begränsade med ett gränssnitt men specialiserade med en struktur som implementerar detta gränssnitt).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för att hämta gränssnitt från värdetyper.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för vanlig paketering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för [System::String](../string/) paketering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för att avpaketera gränssnitt.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för vanlig avpaketering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för nullptr-konvertering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(const Source\&) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används för konvertering mellan arrayer.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::ExplicitCast(Source) method


Kastar källtypen till resultattypen med en explicit typkonvertering. Används när en rå pekare kastas till en smart pekare.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


| Parameter | Beskrivning |
| --- | --- |
| Källa | Källtypen. |
| Resultat | Resultattypen. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | Source | [Object](../object/) att kasta. |

### ReturnValue

Resultatet av casten.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
