---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents method"
linktitle: "TryResizeContents"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents method. Ändrar storlek på innehållet i sidor i dokumentet. Om en sida krymps läggs tomma marginaler till runt sidan. Resultatet sparas i HttpResponse-objektet i C++."
type: docs
weight: 6900
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## PdfFileEditor::TryResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Ändrar storlek på innehållet i sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Ström av källfil. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidor som ska ändras storlek på. |
| parametrar | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parametrar för storleksändring. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse-objekt där resultatet sparas. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryResizeContents är som metoden ResizeContents, förutom att TryResizeContents‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Ändrar storlek på innehållet i dokumentets sidor.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Ström med källdokument. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Ström med destinationsdokumentet. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidindex. |
| parametrar | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parametrar för storleksändring. |

### ReturnValue

Returnerar true om lyckat.
## Anmärkningar



Metoden TryResizeContents är som metoden ResizeContents, förutom att TryResizeContents‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::SharedPtr\<System::IO::Stream\>\& | Ström som innehåller källdokumentet. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Ström där det resulterande dokumentet kommer att sparas. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidindex. Om null bearbetas alla dokumentets sidor. |
| newWidth | double | Ny bredd på sidinnehållet i standardenhetsmått. |
| newHeight | double | Ny höjd på sidinnehållet i standardenhetsmått. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryResizeContents är som metoden ResizeContents, förutom att TryResizeContents‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Ändrar storlek på innehållet i sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::String &source, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::String\& | Sökväg till källfil. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidor som ska ändras storlek på. |
| parametrar | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parametrar för storleksändring. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse-objekt där resultatet sparas. |

### ReturnValue

Sant om operationen slutfördes framgångsrikt; annars falskt.
## Anmärkningar



Metoden TryResizeContents är som metoden ResizeContents, förutom att TryResizeContents‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Ändrar storlek på innehållet i sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const System::String\& | Sökväg till källdokument. |
| destination | const System::String\& | Sökväg till destinationsdokument. |
| sidor | const System::ArrayPtr\<int32_t\>\& | Array av sidindex (sidindex börjar från 1). |
| parametrar | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parametrar för sidstorleksändring. |

### ReturnValue

true om storleksändringen lyckades.
## Anmärkningar



Metoden TryResizeContents är som metoden ResizeContents, förutom att TryResizeContents‑metoden inte kastar ett undantag om operationen misslyckas.
## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
