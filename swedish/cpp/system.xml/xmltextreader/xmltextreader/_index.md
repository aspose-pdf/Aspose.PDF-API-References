---
title: "System::Xml::XmlTextReader::XmlTextReader‑konstruktor"
linktitle: "XmlTextReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlTextReader::XmlTextReader‑konstruktor. Initierar en ny instans av XmlTextReader‑klassen med den angivna strömmen i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna strömmen.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML‑data att läsa. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna strömmen och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML‑data att läsa. |
| nt | const SharedPtr\<XmlNameTable\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna strömmen, [XmlNodeType](../../xmlnodetype/), och [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFragment | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML‑fragmentet att tolka. |
| fragType | XmlNodeType | [XmlNodeType](../../xmlnodetype/) för XML‑fragmentet. Detta bestämmer också vad fragmentet kan innehålla. |
| context | const SharedPtr\<XmlParserContext\>\& | Den [XmlParserContext](../../xmlparsercontext/) i vilken **xmlFragment** ska analyseras. Detta inkluderar den [XmlNameTable](../../xmlnametable/) som ska användas, kodning, namnrymdens omfattning, den aktuella **xml:lang**, och **xml:space**-omfattningen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const SharedPtr\\<IO::TextReader\\>\\& | TextReader‑objektet som innehåller XML‑data att läsa. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna TextReader och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const SharedPtr\\<IO::TextReader\\>\\& | TextReader‑objektet som innehåller XML‑data att läsa. |
| nt | const SharedPtr\<XmlNameTable\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna filen.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const String\& | URL:en för filen som innehåller XML‑data. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. |

## Se även

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna URL:en och strömmen.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const String\& | URL:en som ska användas för att lösa upp externa resurser. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. |
| inmatning | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML‑data att läsa. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna URL:en, strömmen och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const String\& | URL:en som ska användas för att lösa upp externa resurser. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. Om **url** är **nullptr**, sätts **BaseURI** till [String::Empty](../../../system/string/empty/). |
| inmatning | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML‑data att läsa. |
| nt | const SharedPtr\<XmlNameTable\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna URL:en och TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const String\& | URL:en som ska användas för att lösa upp externa resurser. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. |
| inmatning | const SharedPtr\\<IO::TextReader\\>\\& | TextReader‑objektet som innehåller XML‑data att läsa. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna URL:en, TextReader och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const String\& | URL:en som ska användas för att lösa upp externa resurser. [XmlTextReader::get_BaseURI](../get_baseuri/) sätts till detta värde. Om **url** är **nullptr**, sätts **BaseURI** till [String::Empty](../../../system/string/empty/). |
| inmatning | const SharedPtr\\<IO::TextReader\\>\\& | TextReader‑objektet som innehåller XML‑data att läsa. |
| nt | const SharedPtr\<XmlNameTable\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna filen och [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const String\& | URL:en för filen som innehåller XML‑data att läsa. |
| nt | const SharedPtr\<XmlNameTable\>\& | [XmlNameTable](../../xmlnametable/) att använda. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initierar en ny instans av klassen [XmlTextReader](../) med den angivna strängen, [XmlNodeType](../../xmlnodetype/), och [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFragment | const String\& | Strängen som innehåller XML‑fragmentet att analysera. |
| fragType | XmlNodeType | [XmlNodeType](../../xmlnodetype/) för XML‑fragmentet. Detta bestämmer också vad fragmentsträngen kan innehålla. |
| context | const SharedPtr\<XmlParserContext\>\& | Den [XmlParserContext](../../xmlparsercontext/) i vilken **xmlFragment** ska analyseras. Detta inkluderar den [XmlNameTable](../../xmlnametable/) som ska användas, kodning, namnrymdens omfattning, den aktuella **xml:lang**, och **xml:space**-omfattningen. |

## Se även

* Class [String](../../../system/string/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
