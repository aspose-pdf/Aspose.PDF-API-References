---
title: "System::Xml::XmlReader::Create metod"
linktitle: "Skapa"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlReader::Create metod. Skapar en ny XmlReader-instans med den angivna strömmen och standardinställningar i C++."
type: docs
weight: 7700
url: /sv/cpp/system.xml/xmlreader/create/
---
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) method


Skapar en ny [XmlReader](../) instans med den angivna strömmen och standardinställningar.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML-data. [XmlReader](../) skannar de första byten i strömmen och letar efter ett byte order mark eller annat tecken på kodning. När kodningen har bestämts används den för att fortsätta läsa strömmen, och bearbetningen fortsätter med att tolka indata som en ström av (Unicode) tecken. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) method


Skapar en ny [XmlReader](../)-instans med den angivna strömmen och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML-data. [XmlReader](../) skannar de första byten i strömmen och letar efter ett byte order mark eller annat tecken på kodning. När kodningen har bestämts används den för att fortsätta läsa strömmen, och bearbetningen fortsätter med att tolka indata som en ström av (Unicode) tecken. |
| settings | const SharedPtr\<XmlReaderSettings\>\& | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Skapar en ny [XmlReader](../)-instans med den angivna strömmen, inställningarna och kontextinformationen för parsning.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML-data. [XmlReader](../) skannar de första byten i strömmen och letar efter ett byte order mark eller annat tecken på kodning. När kodningen har bestämts används den för att fortsätta läsa strömmen, och bearbetningen fortsätter med att tolka indata som en ström av (Unicode) tecken. |
| settings | SharedPtr\<XmlReaderSettings\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | Den kontextinformation som krävs för att tolka XML-fragmentet. Kontextinformationen kan inkludera [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsscope, den aktuella **xml:lang**- och **xml:space**-scopen, bas-URI och dokumenttypdefinition. Detta värde kan vara **nullptr**. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method


Skapar en ny [XmlReader](../)-instans med den angivna strömmen, bas-URI och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML-data. [XmlReader](../) skannar de första byten i strömmen och letar efter ett byte order mark eller annat tecken på kodning. När kodningen har bestämts används den för att fortsätta läsa strömmen, och bearbetningen fortsätter med att tolka indata som en ström av (Unicode) tecken. |
| settings | SharedPtr\<XmlReaderSettings\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| baseUri | const String\& | Bas-URI för den entitet eller det dokument som läses. Detta värde kan vara **nullptr**. **[Security](../../../system.security/) Note** Bas-URI används för att lösa den relativa URI:n för XML-dokumentet. Använd inte en bas-URI från en opålitlig källa. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) method


Skapar en ny [XmlReader](../)-instans genom att använda den angivna textläsaren.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const SharedPtr\\<IO::TextReader\\>\\& | Textläsaren som XML-data ska läsas från. En textläsare returnerar en ström av Unicode-tecken, så den kodning som anges i XML-deklarationen används inte av XML-läsaren för att avkoda datastreamen. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) method


Skapar en ny [XmlReader](../)-instans genom att använda den angivna textläsaren och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const SharedPtr\\<IO::TextReader\\>\\& | Textläsaren som XML-data ska läsas från. En textläsare returnerar en ström av Unicode-tecken, så den kodning som anges i XML-deklarationen används inte av XML-läsaren för att avkoda datastreamen. |
| settings | const SharedPtr\<XmlReaderSettings\>\& | Inställningarna för den nya [XmlReader](../). Detta värde kan vara **nullptr**. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Skapar en ny [XmlReader](../)-instans genom att använda den angivna textläsaren, inställningarna och kontextinformationen för parsning.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const SharedPtr\\<IO::TextReader\\>\\& | Textläsaren som XML-data ska läsas från. En textläsare returnerar en ström av Unicode-tecken, så den kodning som anges i XML-deklarationen används inte av XML-läsaren för att avkoda datastreamen. |
| settings | SharedPtr\<XmlReaderSettings\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | Den kontextinformation som krävs för att tolka XML-fragmentet. Kontextinformationen kan inkludera [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsscope, den aktuella **xml:lang**- och **xml:space**-scopen, bas-URI och dokumenttypdefinition. Detta värde kan vara **nullptr**. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) method


Skapar en ny [XmlReader](../)-instans genom att använda den angivna textläsaren, inställningarna och bas-URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const SharedPtr\<IO::TextReader\>\& | Textläsaren som XML-data ska läsas från. En textläsare returnerar en ström av Unicode-tecken, så den kodning som anges i XML-deklarationen används inte av [XmlReader](../) för att avkoda datastreamen. |
| settings | SharedPtr\<XmlReaderSettings\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| baseUri | const String\& | Bas-URI för den entitet eller det dokument som läses. Detta värde kan vara **nullptr**. **[Security](../../../system.security/) Note** Bas-URI används för att lösa den relativa URI:n för XML-dokumentet. Använd inte en bas-URI från en opålitlig källa. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) method


Skapar en ny [XmlReader](../)-instans genom att använda den angivna XML-läsaren och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läsare | const SharedPtr\<XmlReader\>\& | Objektet som du vill använda som den underliggande XML-läsaren. |
| settings | SharedPtr\<XmlReaderSettings\> | Inställningarna för den nya [XmlReader](../)-instansen. Konformitetsnivån för [XmlReaderSettings](../../xmlreadersettings/)-objektet måste antingen matcha konformitetsnivån för den underliggande läsaren, eller så måste den sättas till [ConformanceLevel::Auto](../../conformancelevel/). |

### ReturnValue

Ett objekt som omsluter det angivna [XmlReader](../)-objektet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&) method


Skapar en ny [XmlReader](../)-instans med angiven URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const String\& | URI:n för filen som innehåller XML-data. Klassen [XmlUrlResolver](../../xmlurlresolver/) används för att konvertera sökvägen till en kanonisk datarepresentation. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) method


Skapar en ny [XmlReader](../)-instans genom att använda den angivna URI:n och inställningarna.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const String\& | URI för filen som innehåller XML‑data. Objektet [XmlResolver](../../xmlresolver/) på objektet [XmlReaderSettings](../../xmlreadersettings/) används för att konvertera sökvägen till en kanonisk datarepresentation. Om värdet XmlReaderSettings::get_XmlResolver är **nullptr**, används ett nytt [XmlUrlResolver](../../xmlurlresolver/)‑objekt. |
| settings | const SharedPtr\<XmlReaderSettings\>\& | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) method


Skapar en ny [XmlReader](../)‑instans genom att använda den angivna URI:n, inställningarna och kontextinformationen för parsning.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputUri | const String\& | URI för filen som innehåller XML‑data. Objektet [XmlResolver](../../xmlresolver/) på objektet [XmlReaderSettings](../../xmlreadersettings/) används för att konvertera sökvägen till en kanonisk datarepresentation. Om värdet XmlReaderSettings::get_XmlResolver är **nullptr**, används ett nytt [XmlUrlResolver](../../xmlurlresolver/)‑objekt. |
| settings | SharedPtr\<XmlReaderSettings\> | Inställningarna för den nya [XmlReader](../)-instansen. Detta värde kan vara **nullptr**. |
| inputContext | const SharedPtr\<XmlParserContext\>\& | Den kontextinformation som krävs för att tolka XML-fragmentet. Kontextinformationen kan inkludera [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsscope, den aktuella **xml:lang**- och **xml:space**-scopen, bas-URI och dokumenttypdefinition. Detta värde kan vara **nullptr**. |

### ReturnValue

Ett objekt som används för att läsa XML-data i strömmen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
