---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate method"
linktitle: "TryConcatenate"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate method. Konkatenar dokument i C++."
type: docs
weight: 6300
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&, const System::SharedPtr\<Document\>\&) method


Sammanfogar dokument.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::SharedPtr<Document>> &src, const System::SharedPtr<Document> &dest)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const System::ArrayPtr\<System::SharedPtr\<Document\>\>\& | Array av källdokument. |
| dest | const System::SharedPtr\<Document\>\& | Destinationsdokument. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryConcatenate‑metoden är som Concatenate‑metoden, förutom att TryConcatenate‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Sammanfogar filer.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Array av strömmar som ska sammanfogas. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström där resultatfilen kommer att lagras. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryConcatenate‑metoden är som Concatenate‑metoden, förutom att TryConcatenate‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Sammanfogar filer och lagrar resultatet i HttpResponse‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStream, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Strömarray som innehåller filer att sammanfoga. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Svarobjekt/ |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryConcatenate‑metoden är som Concatenate‑metoden, förutom att TryConcatenate‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::String\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Sammanfogar filer och sparar resultatet i HttpResposnse‑objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::String> &inputFiles, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Array av filer att sammanfoga. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Svarobjekt. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryConcatenate‑metoden är som Concatenate‑metoden, förutom att TryConcatenate‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::ArrayPtr\<System::String\>\&, const System::String\&) method


Sammanfogar filer till en fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::ArrayPtr<System::String> &inputFiles, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Array av filer att sammanfoga. |
| outputFile | const System::String\& | Namn på utdatafil. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryConcatenate‑metoden är som Concatenate‑metoden, förutom att TryConcatenate‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Slår samman två [Pdf](../../../aspose.pdf/) dokument till ett nytt [Pdf](../../../aspose.pdf/) dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två [Pdf](../../../aspose.pdf/) dokumenten kommer att producera resultatsdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::SharedPtr<System::IO::Stream> &firstInputStream, const System::SharedPtr<System::IO::Stream> &secInputStream, const System::SharedPtr<System::IO::Stream> &blankPageStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Den första [Pdf](../../../aspose.pdf/) strömmen. |
| secInputStream | const System::SharedPtr\<System::IO::Stream\>\& | Den andra [Pdf](../../../aspose.pdf/) strömmen. |
| blankPageStream | const System::SharedPtr\<System::IO::Stream\>\& | Den [Pdf](../../../aspose.pdf/) strömmen med tom sida. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdata [Pdf](../../../aspose.pdf/) ström. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryConcatenate‑metoden är som Concatenate‑metoden, förutom att TryConcatenate‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::String\&, const System::String\&, const System::String\&, const System::String\&) method


Slår samman två [Pdf](../../../aspose.pdf/) dokument till ett nytt [Pdf](../../../aspose.pdf/) dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två [Pdf](../../../aspose.pdf/) dokumenten kommer att producera resultatsdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::String &firstInputFile, const System::String &secInputFile, const System::String &blankPageFile, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | const System::String\& | Första filen. |
| secInputFile | const System::String\& | Andra filen. |
| blankPageFile | const System::String\& | PDF-fil med tom sida. |
| outputFile | const System::String\& | Resultatfil. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryConcatenate‑metoden är som Concatenate‑metoden, förutom att TryConcatenate‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryConcatenate(const System::String\&, const System::String\&, const System::String\&) method


Sammanfogar två filer.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryConcatenate(const System::String &firstInputFile, const System::String &secInputFile, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | const System::String\& | Första filen att sammanfoga. |
| secInputFile | const System::String\& | Andra filen att sammanfoga. |
| outputFile | const System::String\& | Utdatafil. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



TryConcatenate‑metoden är som Concatenate‑metoden, förutom att TryConcatenate‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
