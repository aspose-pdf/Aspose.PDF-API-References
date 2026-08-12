---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryDelete‑metod"
linktitle: "TryDelete"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryDelete‑metod. Tar bort sidor som anges av ett nummerarray från indatafilen och sparar som en ny Pdf‑fil i C++."
type: docs
weight: 6400
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/trydelete/
---
## PdfFileEditor::TryDelete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Tar bort sidor som anges av en talarray från inmatningsfilen, sparar som en ny [Pdf](../../../aspose.pdf/) fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Indata filström. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Index för sida utanför inmatningsfilen. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdatafilström. |

### ReturnValue

True vid lyckat resultat, annars false.
## Anmärkningar



TryDelete‑metoden är som Delete‑metoden, men TryDelete‑metoden kastar inte ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryDelete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Raderar angivna sidor från dokumentet och sparar resultatet i HttpResponse‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Källdokumentström. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array med sidnummer som kommer att tas bort. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse-objekt |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryDelete‑metoden är som Delete‑metoden, men TryDelete‑metoden kastar inte ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryDelete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Raderar angivna sidor från dokumentet och lagrar resultatet i HttpResponse‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg till källfilen. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Array med sidnummer som måste tas bort. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Svarobjekt där resultatdokumentet kommer att lagras. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryDelete‑metoden är som Delete‑metoden, men TryDelete‑metoden kastar inte ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryDelete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Tar bort sidor som anges av en talarray från inmatningsfilen, sparar som en ny [Pdf](../../../aspose.pdf/) fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg till indatafil. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Index för sida utanför inmatningsfilen. |
| outputFile | const System::String\& | Sökväg till utdatafil. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryDelete‑metoden är som Delete‑metoden, men TryDelete‑metoden kastar inte ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
