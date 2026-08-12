---
title: "System::IO::StreamReader::StreamReader konstruktor"
linktitle: "StreamReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::StreamReader::StreamReader konstruktor. Skapar en instans av StreamReader-objektet som läser tecken från den angivna underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek 1024 byte i C++."
type: docs
weight: 100
url: /sv/cpp/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor


Skapar en instans av [StreamReader](../)-objektet som läser tecken från den angivna underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek 1024 byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const SharedPtr\<Stream\>\& | Den underliggande strömmen att läsa tecken från |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor


Skapar en instans av [StreamReader](../)-objekt som läser tecken från den angivna underliggande strömmen med UTF-8-kodning och en buffert med standardstorlek på 1024 byte. En parameter anger om byte order mark-detektering ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const SharedPtr\<Stream\>\& | Den underliggande strömmen att läsa tecken från |
| detectEncodingFromByteOrderMarks | bool | True för att leta efter byte order marks i början av strömmen, annars - false |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor


Skapar en instans av [StreamReader](../)-objekt som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffert med standardstorlek på 1024 byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const SharedPtr\<Stream\>\& | Den underliggande strömmen att läsa tecken från |
| encoding | const EncodingPtr\& | Kodningen att använda |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor


Skapar en instans av [StreamReader](../)-objekt som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffert med standardstorlek på 1024 byte. En parameter anger om byte order mark-detektering ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const SharedPtr\<Stream\>\& | Den underliggande strömmen att läsa tecken från |
| encoding | const EncodingPtr\& | Kodningen att använda |
| detectEncodingFromByteOrderMarks | bool | True för att leta efter byte order marks i början av strömmen, annars - false |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor


Skapar en instans av [StreamReader](../)-objekt som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffert med den angivna storleken. En parameter anger om byte order mark-detektering ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const SharedPtr\<Stream\>\& | Den underliggande strömmen att läsa tecken från |
| encoding | const EncodingPtr\& | Kodningen att använda |
| detectEncodingFromByteOrderMarks | bool | True för att leta efter byte order marks i början av strömmen, annars - false |
| bufferSize | int | Den minsta storleken på bufferten i byte |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&) constructor


Skapar en instans av [StreamReader](../)-objekt som läser tecken från den angivna filen med UTF-8-kodning och en buffert med standardstorlek på 4096 byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const System::String\& | Sökvägen till filen att läsa tecken från |

## Se även

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, bool) constructor


Skapar en instans av [StreamReader](../)-objekt som läser tecken från den angivna filen med UTF-8-kodning och en buffert med standardstorlek på 4096 byte. En parameter anger om byte order mark-detektering ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const System::String\& | Sökvägen till filen att läsa tecken från |
| detectEncodingFromByteOrderMarks | bool | True för att leta efter byte order marks i början av filen, annars - false |

## Se även

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor


Skapar en instans av [StreamReader](../)-objekt som läser tecken från den angivna filen med den angivna kodningen och en buffert med standardstorlek på 4096 byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const System::String\& | Sökvägen till filen att läsa tecken från |
| encoding | const EncodingPtr\& | Kodningen att använda |

## Se även

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor


Skapar en instans av [StreamReader](../)-objekt som läser tecken från den angivna underliggande strömmen med den angivna kodningen och en buffert med standardstorlek på 4096 byte. En parameter anger om byte order mark-detektering ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const System::String\& | Sökvägen till filen att läsa tecken från |
| encoding | const EncodingPtr\& | Kodningen att använda |
| detectEncodingFromByteOrderMarks | bool | True för att leta efter byte order marks i början av filen, annars - false |

## Se även

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor


Skapar en instans av [StreamReader](../)-objekt som läser tecken från den angivna filen med den angivna kodningen och en buffert med den angivna storleken. En parameter anger om byte order mark-detektering ska vara aktiverad.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const System::String\& | Sökvägen till filen att läsa tecken från |
| encoding | const EncodingPtr\& | Kodningen att använda |
| detectEncodingFromByteOrderMarks | bool | True för att leta efter byte order marks i början av filen, annars - false |
| bufferSize | int | Den minsta storleken på bufferten i byte |

## Se även

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
