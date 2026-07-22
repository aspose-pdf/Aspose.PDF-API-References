---
title: "Aspose::Pdf::Facades::PdfFileEditor::Append metod"
linktitle: "Append"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::Append metod. Lägger till sidor som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams-dokumentens sidor i intervallet startPage till endPage i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/append/
---
## PdfFileEditor::Append(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Lägger till sidor som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams‑dokumentens sidor i intervallet startPage till endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &portStreams, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Indata [Pdf](../../../aspose.pdf/) ström. |
| portStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Dokument att kopiera sidor från. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) börjar i portStreams-dokument. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) slutar i portStreams-dokument. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdata [Pdf](../../../aspose.pdf/) ström. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Lägger till dokument i källdokumentet och sparar resultatet i response‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &portStreams, int32_t startPage, int32_t endPage, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller källdokumentet. |
| portStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Array av strömmar med dokument som ska bifogas. |
| startPage | int32_t | Start sida för bifogad sida. |
| endPage | int32_t | Slut sida för bifogade sidor. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Svarobjekt där dokumentet kommer att sparas. |

### ReturnValue

true om operationen lyckades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Lägger till sidor, som väljs från portStream inom intervallet startPage till endPage, i portStream i slutet av firstInputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &portStream, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Indata filström. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | Sidor från [Pdf](../../../aspose.pdf/) filström. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) börjar i portFile-ström. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) slutar i portFile-ström. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdata [Pdf](../../../aspose.pdf/) filström. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::String\&, const System::ArrayPtr\<System::String\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Lägger till dokument i källdokumentet och sparar resultatet i HttpResponse‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::String &inputFile, const System::ArrayPtr<System::String> &portFiles, int32_t startPage, int32_t endPage, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Namn på fil som innehåller källdokumentet. |
| portFiles | const System::ArrayPtr\<System::String\>\& | Array av filnamn som innehåller bifogade dokument. |
| startPage | int32_t | Start sida för bifogade sidor. |
| endPage | int32_t | Slut sida för bifogade sidor. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Svarobjekt där dokumentet kommer att sparas. |

### ReturnValue

sant om operationen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::String\&, const System::ArrayPtr\<System::String\>\&, int32_t, int32_t, const System::String\&) method


Lägger till sidor som väljs från portFiles‑dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles‑dokumentens sidor i intervallet startPage till endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::String &inputFile, const System::ArrayPtr<System::String> &portFiles, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Inmatnings [Pdf](../../../aspose.pdf/) fil. |
| portFiles | const System::ArrayPtr\<System::String\>\& | Dokument att kopiera sidor från. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) börjar i portFiles-dokument. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) slutar i portFiles-dokument. |
| outputFile | const System::String\& | Utdata [Pdf](../../../aspose.pdf/) dokument. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::String\&, const System::String\&, int32_t, int32_t, const System::String\&) method


Lägger till sidor som väljs från portFile inom intervallet startPage till endPage, i portFile i slutet av firstInputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::String &inputFile, const System::String &portFile, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Inmatnings [Pdf](../../../aspose.pdf/) fil. |
| portFile | const System::String\& | Sidor från [Pdf](../../../aspose.pdf/) fil. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) startar i portFile. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) slutar i portFile. |
| outputFile | const System::String\& | Utdata [Pdf](../../../aspose.pdf/) dokument. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
