---
title: "Aspose::Pdf::Facades::PdfFileEditor::Insert metod"
linktitle: "Infoga"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::Insert metod. Infogar sidor från en annan fil i den inmatade Pdf-filen i C++."
type: docs
weight: 3200
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/insert/
---
## PdfFileEditor::Insert(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Infogar sidor från en annan fil i den inmatade [Pdf](../../../aspose.pdf/) filen.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t insertLocation, const System::SharedPtr<System::IO::Stream> &portStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsström för [Pdf](../../../aspose.pdf/) filen. |
| insertLocation | int32_t | Infogningsposition i inmatningsfilen. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström av [Pdf](../../../aspose.pdf/) fil för sidor. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Sidnumret för den importerade i portFile. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdataström |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Infogar dokumentet i ett annat dokument och lagrar resultatet i ett svarsobjekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t insertLocation, const System::SharedPtr<System::IO::Stream> &portStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström med källdokument |
| insertLocation | int32_t | Plats där annat dokument kommer att infogas. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | [Document](../../../aspose.pdf/document/) som ska infogas. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array av sidnummer i det andra dokumentet som ska infogas. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Svarobjekt där resultatet kommer att lagras. |

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
## PdfFileEditor::Insert(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Infogar sidor från en annan fil i den inmatade [Pdf](../../../aspose.pdf/) filen.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t insertLocation, const System::SharedPtr<System::IO::Stream> &portStream, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsström för [Pdf](../../../aspose.pdf/) filen. |
| insertLocation | int32_t | Infogningsposition i inmatningsfilen. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström av [Pdf](../../../aspose.pdf/) fil för sidor. |
| startPage | int32_t | Från vilken sida att börja. |
| endPage | int32_t | Till vilken sida att sluta. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdataström |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(const System::String\&, int32_t, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Infogar innehållet i filen i källfilen och lagrar resultatet i ett HttpResponse‑objekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::String &inputFile, int32_t insertLocation, const System::String &portFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Källfilnamn. |
| insertLocation | int32_t | [Page](../../../aspose.pdf/page/) nummer där den andra filen kommer att infogas. |
| portFile | const System::String\& | Sökväg till fil som ska infogas. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array av sidnummer i källfilen som ska infogas. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Svarobjekt där resultatet kommer att lagras. |

### ReturnValue

true om infogning lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(const System::String\&, int32_t, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Infogar sidor från en annan fil i den inmatade [Pdf](../../../aspose.pdf/) filen.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::String &inputFile, int32_t insertLocation, const System::String &portFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Inmatnings [Pdf](../../../aspose.pdf/) fil. |
| insertLocation | int32_t | Infogningsposition i inmatningsfilen. |
| portFile | const System::String\& | Sidor från [Pdf](../../../aspose.pdf/) filen. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Sidnumret för den importerade i portFile. |
| outputFile | const System::String\& | Utdata [Pdf](../../../aspose.pdf/) fil. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Insert(const System::String\&, int32_t, const System::String\&, int32_t, int32_t, const System::String\&) method


Infogar sidor från en annan fil i [Pdf](../../../aspose.pdf/)-filen på en position.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Insert(const System::String &inputFile, int32_t insertLocation, const System::String &portFile, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Inmatnings [Pdf](../../../aspose.pdf/) fil. |
| insertLocation | int32_t | Position i indatafilen. |
| portFile | const System::String\& | Porteringsfilen [Pdf](../../../aspose.pdf/). |
| startPage | int32_t | Startposition i portFile. |
| endPage | int32_t | Slutposition i portFile. |
| outputFile | const System::String\& | Utdata [Pdf](../../../aspose.pdf/) fil. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
