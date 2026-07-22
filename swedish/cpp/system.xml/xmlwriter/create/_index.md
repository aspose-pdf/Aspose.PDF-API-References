---
title: "System::Xml::XmlWriter::Create metod"
linktitle: "Skapa"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlWriter::Create metod. Skapar en ny XmlWriter‑instans med den angivna strömmen i C++."
type: docs
weight: 3700
url: /sv/cpp/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) method


Skapar en ny [XmlWriter](../)‑instans med den angivna strömmen.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const SharedPtr\<IO::Stream\>\& | Strömmen som du vill skriva till. [XmlWriter](../) skriver XML 1.0‑textsyntax och lägger till den i den angivna strömmen. |

### ReturnValue

Ett [XmlWriter](../)‑objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) method


Skapar en ny [XmlWriter](../)‑instans med strömmen och [XmlWriterSettings](../../xmlwritersettings/)‑objektet.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const SharedPtr\<IO::Stream\>\& | Strömmen som du vill skriva till. [XmlWriter](../) skriver XML 1.0‑textsyntax och lägger till den i den angivna strömmen. |
| settings | SharedPtr\<XmlWriterSettings\> | Det [XmlWriterSettings](../../xmlwritersettings/)‑objekt som används för att konfigurera den nya [XmlWriter](../)‑instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)‑metoden bör du använda XslCompiledTransform::get_OutputSettings‑värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)‑objekt med korrekta inställningar. Detta säkerställer att det skapade [XmlWriter](../)‑objektet har rätt utdatainställningar. |

### ReturnValue

Ett [XmlWriter](../)‑objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) method


Skapar en ny [XmlWriter](../)‑instans med den angivna TextWriter.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const SharedPtr\<IO::TextWriter\>\& | TextWriter:n som du vill skriva till. [XmlWriter](../) skriver XML 1.0‑textsyntax och lägger till den i den angivna TextWriter. |

### ReturnValue

Ett [XmlWriter](../)‑objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) method


Skapar en ny [XmlWriter](../)‑instans med TextWriter och [XmlWriterSettings](../../xmlwritersettings/)‑objekten.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const SharedPtr\<IO::TextWriter\>\& | TextWriter:n som du vill skriva till. [XmlWriter](../) skriver XML 1.0‑textsyntax och lägger till den i den angivna TextWriter. |
| settings | SharedPtr\<XmlWriterSettings\> | Det [XmlWriterSettings](../../xmlwritersettings/)‑objekt som används för att konfigurera den nya [XmlWriter](../)‑instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)‑metoden bör du använda XslCompiledTransform::get_OutputSettings‑värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)‑objekt med korrekta inställningar. Detta säkerställer att det skapade [XmlWriter](../)‑objektet har rätt utdatainställningar. |

### ReturnValue

Ett [XmlWriter](../)‑objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) method


Skapar en ny [XmlWriter](../)‑instans med den angivna [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const SharedPtr\<Text::StringBuilder\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) som du ska skriva till. Innehåll som skrivs av [XmlWriter](../) läggs till i [Text::StringBuilder](../../../system.text/stringbuilder/). |

### ReturnValue

Ett [XmlWriter](../)‑objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) method


Skapar en ny [XmlWriter](../)‑instans med [Text::StringBuilder](../../../system.text/stringbuilder/) och [XmlWriterSettings](../../xmlwritersettings/)‑objekten.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const SharedPtr\<Text::StringBuilder\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) som du ska skriva till. Innehåll som skrivs av [XmlWriter](../) läggs till i [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | SharedPtr\<XmlWriterSettings\> | Det [XmlWriterSettings](../../xmlwritersettings/)‑objekt som används för att konfigurera den nya [XmlWriter](../)‑instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)‑metoden bör du använda XslCompiledTransform::get_OutputSettings‑värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)‑objekt med korrekta inställningar. Detta säkerställer att det skapade [XmlWriter](../)‑objektet har rätt utdatainställningar. |

### ReturnValue

Ett [XmlWriter](../)‑objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) method


Skapar en ny [XmlWriter](../)‑instans med det angivna [XmlWriter](../)‑objektet.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const SharedPtr\<XmlWriter\>\& | [XmlWriter](../)‑objektet som du vill använda som underliggande skribent. |

### ReturnValue

Ett [XmlWriter](../)‑objekt som är omslutet runt det angivna [XmlWriter](../)‑objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) method


Skapar en ny [XmlWriter](../)‑instans med de angivna [XmlWriter](../)‑ och [XmlWriterSettings](../../xmlwritersettings/)‑objekten.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| output | const SharedPtr\<XmlWriter\>\& | [XmlWriter](../)‑objektet som du vill använda som underliggande skribent. |
| settings | SharedPtr\<XmlWriterSettings\> | Det [XmlWriterSettings](../../xmlwritersettings/)‑objekt som används för att konfigurera den nya [XmlWriter](../)‑instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)‑metoden bör du använda XslCompiledTransform::get_OutputSettings‑värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)‑objekt med korrekta inställningar. Detta säkerställer att det skapade [XmlWriter](../)‑objektet har rätt utdatainställningar. |

### ReturnValue

Ett [XmlWriter](../)‑objekt som är omslutet runt det angivna [XmlWriter](../)‑objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const String\&) method


Skapar en ny [XmlWriter](../)‑instans med det angivna filnamnet.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | const String\& | Filen som du vill skriva till. [XmlWriter](../) skapar en fil på den angivna sökvägen och skriver till den i XML 1.0‑textsyntax. **outputFileName** måste vara en filsökväg. |

### ReturnValue

Ett [XmlWriter](../)‑objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) method


Skapar en ny [XmlWriter](../)-instans med filnamnet och [XmlWriterSettings](../../xmlwritersettings/)-objektet.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFileName | const String\& | Filen som du vill skriva till. [XmlWriter](../) skapar en fil på den angivna sökvägen och skriver till den i XML 1.0‑textsyntax. **outputFileName** måste vara en filsökväg. |
| settings | SharedPtr\<XmlWriterSettings\> | Det [XmlWriterSettings](../../xmlwritersettings/)‑objekt som används för att konfigurera den nya [XmlWriter](../)‑instansen. Om detta är **nullptr** används ett [XmlWriterSettings](../../xmlwritersettings/) med standardinställningar. Om [XmlWriter](../) används med XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>)‑metoden bör du använda XslCompiledTransform::get_OutputSettings‑värdet för att erhålla ett [XmlWriterSettings](../../xmlwritersettings/)‑objekt med korrekta inställningar. Detta säkerställer att det skapade [XmlWriter](../)‑objektet har rätt utdatainställningar. |

### ReturnValue

Ett [XmlWriter](../)‑objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
