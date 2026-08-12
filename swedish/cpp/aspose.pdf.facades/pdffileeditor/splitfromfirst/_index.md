---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst metod"
linktitle: "SplitFromFirst"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst-metod. Delar från början till angiven plats och sparar den främre delen i utdata‑ström i C++."
type: docs
weight: 5800
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## PdfFileEditor::SplitFromFirst(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Delar från början till angiven plats, och sparar den främre delen i utdata Stream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Käll [Pdf](../../../aspose.pdf/) filström. |
| location | int32_t | Delningspunkten. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Utdatafil Stream. |

### ReturnValue

True vid lyckat resultat, annars false.
## Anmärkningar



Strömmarna stängs INTE efter denna operation.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitFromFirst(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Delar dokumentet från början till angiven plats och lagrar resultatet i HttpResponse-objekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(const System::SharedPtr<System::IO::Stream> &inputStream, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Ström för källdokumentet. |
| location | int32_t | Delningspunkten. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse‑objekt där resultatet kommer att lagras. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitFromFirst(const System::String\&, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Delar dokumentet från första sidan till platsen och sparar resultatet i HttpResponse-objekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(const System::String &inputFile, int32_t location, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Källfilnamn. |
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
## PdfFileEditor::SplitFromFirst(const System::String\&, int32_t, const System::String\&) method


Delar [Pdf](../../../aspose.pdf/) fil från första sidan till angiven plats och sparar den främre delen som en ny fil.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::SplitFromFirst(const System::String &inputFile, int32_t location, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Käll [Pdf](../../../aspose.pdf/) fil. |
| location | int32_t | Delningspunkten. |
| outputFile | const System::String\& | Utdata [Pdf](../../../aspose.pdf/) fil. |

### ReturnValue

True vid lyckat resultat, annars false.

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
