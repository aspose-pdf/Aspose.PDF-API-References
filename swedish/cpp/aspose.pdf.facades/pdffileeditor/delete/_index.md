---
title: "Aspose::Pdf::Facades::PdfFileEditor::Delete method"
linktitle: "Ta bort"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::Delete method. Tar bort sidor som anges av en talarray från inmatningsfilen, sparar som en ny Pdf-fil i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/delete/
---
## PdfFileEditor::Delete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Tar bort sidor som anges av en talarray från inmatningsfilen, sparar som en ny [Pdf](../../../aspose.pdf/) fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
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
## PdfFileEditor::Delete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Raderar angivna sidor från dokumentet och sparar resultatet i HttpResponse‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Källdokumentström. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array med sidnummer som kommer att tas bort. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse-objekt |

### ReturnValue

True om operationen lyckades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Raderar angivna sidor från dokumentet och lagrar resultatet i HttpResponse‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg till källfilen. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array med sidnummer som måste tas bort. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Svarobjekt där resultatdokumentet kommer att lagras. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Tar bort sidor som anges av en talarray från inmatningsfilen, sparar som en ny [Pdf](../../../aspose.pdf/) fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
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
