---
title: "Aspose::Pdf::Facades::PdfFileEditor::Extract metod"
linktitle: "Extrahera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::Extract metod. Extraherar sidor som anges av ett nummerarray, sparar som en ny Pdf-fil i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/extract/
---
## PdfFileEditor::Extract(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Extraherar sidor som anges av ett nummerarray, sparar som en ny [Pdf](../../../aspose.pdf/) fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Extract(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Indata filström. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Index för sida utanför inmatningsfilen. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdatafilström. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Extract(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Extraherar angivna sidor från källfilen och lagrar resultatet i HttpResponse‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Extract(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström för källdokumentet. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array av sidnummer som kommer att extraheras. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse‑objekt där resultatet kommer att lagras. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Extract(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Extraherar sidor från inmatningsfilen, sparar som en ny [Pdf](../../../aspose.pdf/) fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Extract(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Indata filström. |
| startPage | int32_t | Startsidnummer. |
| endPage | int32_t | Slutsidnummer. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdata [Pdf](../../../aspose.pdf/) filström. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Extract(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Extraherar angivna sidor från källfilen och lagrar resultatet i HttpResponse‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Extract(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg till källfil. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array av sidnummer som kommer att extraheras. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse‑objekt där resultatet kommer att lagras. |

### ReturnValue

true om sidor extraherades framgångsrikt.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Extract(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Extraherar sidor som anges av nummerarray, sparar som en ny PDF‑fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Extract(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg till indatafil. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Index för sida utanför inmatningsfilen. |
| outputFile | const System::String\& | Sökväg till utdatafil. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Extract(const System::String\&, int32_t, int32_t, const System::String\&) method


Extraherar sidor från inmatningsfilen, sparar som en ny [Pdf](../../../aspose.pdf/) fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Extract(const System::String &inputFile, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Inmatnings [Pdf](../../../aspose.pdf/) filsökväg. |
| startPage | int32_t | Startsidnummer. |
| endPage | int32_t | Slutsidnummer. |
| outputFile | const System::String\& | Utdata [Pdf](../../../aspose.pdf/) filsökväg. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
