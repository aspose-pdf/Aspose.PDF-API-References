---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd-metod"
linktitle: "SplitToEnd"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd-metod. Delar från angiven plats och sparar den bakre delen som en ny filström i C++."
type: docs
weight: 6000
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/splittoend/
---
## PdfFileEditor::SplitToEnd(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Delar från angiven plats, och sparar den bakre delen som en ny fil Stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Käll [Pdf](../../../aspose.pdf/) filström. |
| location | int32_t | Delningspositionen. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdata [Pdf](../../../aspose.pdf/) filström. |

### ReturnValue

True vid lyckat resultat, annars false.
## Anmärkningar



Strömmarna stängs INTE efter denna operation om inte CloseConcatedStreams anges.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToEnd(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Delar från angiven plats, och sparar den bakre delen i HttpResponse-objekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Källdokumentström. |
| location | int32_t | Delningspunkt. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse-objekt. |

### ReturnValue

true om delning lyckades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToEnd(const System::String\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Delar från angiven plats, och sparar den bakre delen i HttpResponse-objekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(const System::String &inputFile, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | källfilnamn. |
| location | int32_t | Delningspunkt. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse-objekt. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToEnd(const System::String\&, int32_t, const System::String\&) method


Delar från platsen, och sparar den bakre delen som en ny fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitToEnd(const System::String &inputFile, int32_t location, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Käll [Pdf](../../../aspose.pdf/) fil. |
| location | int32_t | Delningspositionen. |
| outputFile | const System::String\& | Utdata [Pdf](../../../aspose.pdf/) filsökväg. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
