---
title: "Aspose::Pdf::Document::Convert metod"
linktitle: "Konvertera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document::Convert metod. Konverterar dokumentet med angivna konverteringsalternativ i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf/document/convert/
---
## Document::Convert(const System::SharedPtr\<PdfFormatConversionOptions\>\&) method


Konvertera dokumentet med angivna konverteringsalternativ.

```cpp
bool Aspose::Pdf::Document::Convert(const System::SharedPtr<PdfFormatConversionOptions> &options)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | const System::SharedPtr\<PdfFormatConversionOptions\>\& | uppsättning alternativ för att konvertera PDF-dokument |

### ReturnValue

Resultatet av operationen

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) method


Konvertera dokumentet och spara fel i den angivna strömmen.

```cpp
bool Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format, ConvertErrorAction action)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström där kommentarerna kommer att lagras. |
| format | Aspose::Pdf::PdfFormat | [Pdf](../../) format. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |

### ReturnValue

Resultatet av operationen

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) method


Konvertera dokumentet och spara fel i den angivna filen.

```cpp
bool Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström där kommentarerna kommer att lagras. |
| format | Aspose::Pdf::PdfFormat | PDF-formatet. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |
| transparencyAction | ConvertTransparencyAction | Åtgärd för bildmaskerade objekt |

### ReturnValue

Resultatet av operationen

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Enum [ConvertTransparencyAction](../../converttransparencyaction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) method


Konvertera dokumentet och spara fel i den angivna filen.

```cpp
bool Aspose::Pdf::Document::Convert(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format, ConvertErrorAction action)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Sökväg till filen där kommentarerna kommer att lagras. |
| format | Aspose::Pdf::PdfFormat | PDF-formatet. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |

### ReturnValue

Resultatet av operationen

## Se även

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) method


Konvertera dokumentet och spara fel i den angivna filen.

```cpp
bool Aspose::Pdf::Document::Convert(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Sökväg till filen där kommentarerna kommer att lagras. |
| format | Aspose::Pdf::PdfFormat | PDF-formatet. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |
| transparencyAction | ConvertTransparencyAction | Åtgärd för bildmaskerade objekt |

### ReturnValue

Resultatet av operationen

## Se även

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Enum [ConvertTransparencyAction](../../converttransparencyaction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Document::CallBackGetHocr, bool) method


Identifiera bilder i dokumentet och lägg till hocr-strängar ovanpå dem.

```cpp
bool Aspose::Pdf::Document::Convert(Document::CallBackGetHocr callback, bool flattenImages=false)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | Document::CallBackGetHocr | Åtgärd för bilder som kommer att bearbetas av hocr-igenkänning. |
| flattenImages | bool | [Text](../../../aspose.pdf.text/) i pdf-bilder kan målas med hjälp av maskmekaniken, i så fall måste bilderna plattas ut. |

### ReturnValue

Operationens resultat. Om det inte finns några bilder i dokumentet returneras [false](../).

## Se även

* Typedef [CallBackGetHocr](../callbackgethocr/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Document::CallBackGetHocrWithPage, bool) method


Identifiera bilder i dokumentet och lägg till hocr-strängar ovanpå dem.

```cpp
bool Aspose::Pdf::Document::Convert(Document::CallBackGetHocrWithPage callback, bool flattenImages=false)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | Document::CallBackGetHocrWithPage | Åtgärd för bilder som kommer att bearbetas av hocr-igenkänning. |
| flattenImages | bool | [Text](../../../aspose.pdf.text/) i pdf-bilder kan målas med hjälp av maskmekaniken, i så fall måste bilderna plattas ut. |

### ReturnValue

Operationens resultat. Om det inte finns några bilder i dokumentet returneras [false](../).

## Se även

* Typedef [CallBackGetHocrWithPage](../callbackgethocrwithpage/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Fixup, const System::SharedPtr\<System::IO::Stream\>\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) method


Konvertera dokumentet genom att tillämpa [Fixup](../../fixup/).

```cpp
bool Aspose::Pdf::Document::Convert(Fixup fixup, const System::SharedPtr<System::IO::Stream> &outputLog, bool onlyValidation=false, const System::ArrayPtr<System::SharedPtr<System::Object>> &parameters=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixup | Fixup | Typen [Fixup](../../fixup/). |
| outputLog | const System::SharedPtr\<System::IO::Stream\>\& | Logg för processen. |
| onlyValidation | bool | Endast dokumentvalidering. |
| parameters | const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\& | Egenskaper för [Fixup](../../fixup/) som inte kan ställas in. |

### ReturnValue

Operationens resultat.

## Se även

* Enum [Fixup](../../fixup/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Fixup, const System::String\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) method


Konvertera dokumentet genom att tillämpa [Fixup](../../fixup/).

```cpp
bool Aspose::Pdf::Document::Convert(Fixup fixup, const System::String &outputLog, bool onlyValidation=false, const System::ArrayPtr<System::SharedPtr<System::Object>> &parameters=nullptr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixup | Fixup | Typen [Fixup](../../fixup/). |
| outputLog | const System::String\& | Logg för processen. |
| onlyValidation | bool | Endast dokumentvalidering. |
| parameters | const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\& | Egenskaper för [Fixup](../../fixup/) som inte kan ställas in. |

### ReturnValue

Operationens resultat.

## Se även

* Enum [Fixup](../../fixup/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) method


Konverterar strömmen i källformat till en ström i destinationsformat.

```cpp
static void Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &srcStream, const System::SharedPtr<LoadOptions> &loadOptions, const System::SharedPtr<System::IO::Stream> &dstStream, System::SharedPtr<SaveOptions> saveOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcStream | const System::SharedPtr\<System::IO::Stream\>\& | Källströmmen. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | Formatet för källströmmen. |
| dstStream | const System::SharedPtr\<System::IO::Stream\>\& | Måldataströmmen. |
| saveOptions | System::SharedPtr\<SaveOptions\> | Formatet för målfilen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) method


Konverterar strömmen i källformat till destinationsfil i destinationsformat.

```cpp
static void Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &srcStream, const System::SharedPtr<LoadOptions> &loadOptions, const System::String &dstFileName, System::SharedPtr<SaveOptions> saveOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcStream | const System::SharedPtr\<System::IO::Stream\>\& | Källströmmen. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | Formatet för källströmmen. |
| dstFileName | const System::String\& | Målfilsnamnet. |
| saveOptions | System::SharedPtr\<SaveOptions\> | Formatet för målfilen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [String](../../../system/string/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) method


Konverterar källfilen i källformat till en ström i destinationsformat.

```cpp
static void Aspose::Pdf::Document::Convert(const System::String &srcFileName, const System::SharedPtr<LoadOptions> &loadOptions, const System::SharedPtr<System::IO::Stream> &dstStream, System::SharedPtr<SaveOptions> saveOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | const System::String\& | Källfilnamnet. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | Formatet för källfilen. |
| dstStream | const System::SharedPtr\<System::IO::Stream\>\& | Måldataströmmen. |
| saveOptions | System::SharedPtr\<SaveOptions\> | Måldataströmmens format. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) method


Konverterar källfilen i källformat till destinationsfil i destinationsformat.

```cpp
static void Aspose::Pdf::Document::Convert(const System::String &srcFileName, const System::SharedPtr<LoadOptions> &loadOptions, const System::String &dstFileName, System::SharedPtr<SaveOptions> saveOptions)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | const System::String\& | Källfilnamnet. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | Formatet för källfilen. |
| dstFileName | const System::String\& | Målfilsnamnet. |
| saveOptions | System::SharedPtr\<SaveOptions\> | Formatet för målfilen. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
