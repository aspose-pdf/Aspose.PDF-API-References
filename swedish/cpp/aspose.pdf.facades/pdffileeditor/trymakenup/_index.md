---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp metod"
linktitle: "TryMakeNUp"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp metod. Skapar N-Up-dokument från flera inmatnings-PDF-strömmar till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, som är en kombination av sidor i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är true och staplas vertikalt om isSidewise är false i C++."
type: docs
weight: 6800
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## PdfFileEditor::TryMakeNUp(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::SharedPtr\<System::IO::Stream\>\&, bool) method


Skapar ett N-Up‑dokument från de flera inmatade PDF‑strömmarna till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, vilka är kombinationer av sidor i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &inputStreams, const System::SharedPtr<System::IO::Stream> &outputStream, bool isSidewise)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Inmatnings [Pdf](../../../aspose.pdf/) strömmar. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdata-pdf-ström. |
| isSidewise | bool | Staplingssätt, true för horisontellt och false för vertikalt. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::ArrayPtr\<System::String\>\&, const System::String\&, bool) method


Skapar ett N-Up‑dokument från de flera inmatade PDF‑filerna till outputFile. Varje sida i outputFile kommer att innehålla flera sidor, vilka är kombinationer av sidor i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::ArrayPtr<System::String> &inputFiles, const System::String &outputFile, bool isSidewise)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFiles | const System::ArrayPtr\<System::String\>\& | Inmatningsfiler [Pdf](../../../aspose.pdf/). |
| outputFile | const System::String\& | Sökväg och namn för utdata-pdf-fil. |
| isSidewise | bool | Staplingssätt, true för horisontellt och false för vertikalt. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Skapar ett N-Up‑dokument från de två inmatade PDF‑strömmarna till outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &firstInputStream, const System::SharedPtr<System::IO::Stream> &secondInputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputStream | const System::SharedPtr\<System::IO::Stream\>\& | första inmatningsströmmen. |
| secondInputStream | const System::SharedPtr\<System::IO::Stream\>\& | andra inmatningsströmmen. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdata-pdf-ström. |

### ReturnValue

true om operationen slutfördes framgångsrikt; annars false
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) method


Skapar ett N-Up‑dokument från inmatningsströmmen och sparar resultatet i output‑strömmen.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, int32_t x, int32_t y)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Inmatnings-pdf-ström. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdata-pdf-ström. |
| x | int32_t | Antal kolumner. |
| y | int32_t | Antal rader. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&) method


Skapar ett N-Up‑dokument från den första inmatningsströmmen till output‑strömmen.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Inmatnings-pdf-ström. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdata-pdf-ström. |
| x | int32_t | Antal kolumner. |
| y | int32_t | Antal rader. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Sidstorleken för utdata-pdf-filen. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Skapar ett N-up‑dokument och lagrar resultatet i ett HttpResponse‑objekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström för källdokumentet. |
| x | int32_t | Antal kolumner. |
| y | int32_t | Antal rader. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Storlek på [Page](../../../aspose.pdf/page/) i resultatfilen. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse‑objekt där resultatet kommer att lagras. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Skapar N-up-dokument och lagrar resultatet i HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t x, int32_t y, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström för inmatningsdokumentet. |
| x | int32_t | Antal kolumner. |
| y | int32_t | Antal rader. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse där resultatet kommer att lagras. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, const System::String\&, const System::String\&) method


Skapar ett N-Up‑dokument från de två inmatade PDF‑filerna till outputFile. Varje sida i outputFile kommer att innehålla två sidor, en sida från den första inmatningsfilen och en annan från den andra inmatningsfilen. De två sidorna staplas horisontellt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &firstInputFile, const System::String &secondInputFile, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstInputFile | const System::String\& | första inmatningsfilen. |
| secondInputFile | const System::String\& | andra inmatningsfilen. |
| outputFile | const System::String\& | Sökväg och namn för utdata-pdf-fil. |

### ReturnValue

true om operationen slutfördes framgångsrikt; annars false
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, const System::String\&, int32_t, int32_t) method


Skapar ett N-Up‑dokument från firstInputFile till outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, const System::String &outputFile, int32_t x, int32_t y)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg och namn för inmatnings-pdf-fil. |
| outputFile | const System::String\& | Sökväg och namn för utdata-pdf-fil. |
| x | int32_t | Antal kolumner. |
| y | int32_t | Antal rader. |

### ReturnValue

true om operationen slutfördes framgångsrikt; annars false.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, const System::String\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&) method


Skapar ett N-Up‑dokument från inmatningsfilen till outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, const System::String &outputFile, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg och namn för inmatnings-pdf-fil. |
| outputFile | const System::String\& | Sökväg och namn för utdata-pdf-fil. |
| x | int32_t | Antal kolumner. |
| y | int32_t | Antal rader. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Sidstorleken för utdata-pdf-filen. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, int32_t, int32_t, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Skapar ett N-up‑dokument och lagrar resultatet i ett HttpResponse‑objekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, int32_t x, int32_t y, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg till källfil. |
| x | int32_t | Antal kolumner. |
| y | int32_t | Antal rader. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Storlek på [Page](../../../aspose.pdf/page/) i resultatfilen. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse‑objekt där resultatet kommer att lagras. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(const System::String\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Skapar N-up-dokument och lagrar resultatet i HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(const System::String &inputFile, int32_t x, int32_t y, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Källfilnamn. |
| x | int32_t | Antal kolumner. |
| y | int32_t | Antal rader. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse‑objekt där resultatet kommer att lagras. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryMakeNUp är som metoden MakeNUp, men TryMakeNUp kastar inte ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
