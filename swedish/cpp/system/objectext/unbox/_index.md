---
title: "System::ObjectExt::Unbox metod"
linktitle: "Unbox"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt::Unbox metod. Avpaketerar värdetyper efter konvertering till Object. Implementation för enum‑typer i C++."
type: docs
weight: 1500
url: /sv/cpp/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Avpaketerar värdetyper efter konvertering till [Object](../../object/). Implementation för enum‑typer.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | [Enum](../../enum/) typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) att avpaketera. |

### ReturnValue

[Enum](../../enum/) value.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Avpaketerar värdetyper efter konvertering till [Object](../../object/). Implementation för icke‑enum‑ och icke‑nullbara typer.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) att avpaketera. |

### ReturnValue

Avpaketerat värde.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Avpaketerar värdetyper efter konvertering till [Object](../../object/). Implementation för icke‑enum‑ och icke‑nullbara typer.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Värdetyp. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) att avpaketera. |

### ReturnValue

Avpaketerat värde.

## Se även

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Packar upp strängvärden.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) att avpaketera |

### ReturnValue

[String](../../string/) representation of boxed string, can be null if boxed string was null.

## Se även

* Class [String](../../string/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(E) method


Packar upp enum-typer till heltal.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Destinationens heltalstyp. |
| E | Källenum‑typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e | E | Värde att avpaketera. |

### ReturnValue

Heltalsrepresentation av enum.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::Unbox(E) method


Konverterar enum-typer.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


| Parameter | Beskrivning |
| --- | --- |
| T | Målenum‑typ. |
| E | Källenum‑typ. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e | E | Värde att avpaketera. |

### ReturnValue

Konverterat enum‑värde.

## Se även

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
