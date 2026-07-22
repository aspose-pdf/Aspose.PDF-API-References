---
title: "Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet‑metod"
linktitle: "MakeBooklet"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet‑metod. Skapar en häfte från PDF‑filen och lagrar den i HttpResponse i C++."
type: docs
weight: 3300
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Skapar en häfte från PDF‑filen och lagrar den i HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Indataström för dokumentet. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Önskad sidstorlek. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Array av sidnummer som kommer att placeras till vänster. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Array av sidnummer som kommer att placeras till höger. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse-objekt. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Skapar en häfte från källfilen och lagrar resultatet i HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Indataström för dokumentet. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Önskad sidstorlek i utdatafilen. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Response-objekt där resultatet kommer att sparas. |

### ReturnValue

Sant om häften byggdes framgångsrikt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Skapar en häfte från InputStream till outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Inmatnings-pdf-ström. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | utdata-pdf-ström. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Skapar ett anpassat häfte från firstInputStream till outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsströmmen. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | utdata-pdf-ström. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | De vänstra sidorna. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | De högra sidorna. |

### ReturnValue

boolesk – Sant för lyckat, annars falskt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) method


Skapar en häfte från inmatningsströmmen och sparar resultatet i output‑strömmen.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Inmatnings-PDF-ström. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | utdata-pdf-ström. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Sidstorleken för utdata-pdf-filen. |

### ReturnValue

Sant om operationen lyckades.


## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Skapar en häfte från firstInputStream till outputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Inmatningsströmmen. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | utdata-pdf-ström. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Sidstorleken för utdata-pdf-filen. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | De vänstra sidorna. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | De högra sidorna. |

### ReturnValue

boolesk – Sant för lyckat, annars falskt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Skapar en häfte från källfilen och lagrar resultatet i HttpResponse‑objekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg till källfil. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Önskad sidstorlek. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | Array av sidnummer som ska placeras till vänster. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | Array av sidnummer som ska placeras till höger. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse‑objekt där resultatet kommer att lagras. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Skapar en häfte från källfilen och lagrar resultatet i HttpResponse‑objekt.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg till källfil. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Önskad sidstorlek i utdatafilen. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | HttpResponse‑objekt där resultatet kommer att lagras. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::String\&) method


Skapar en häfte från inmatningsfilen till utdatafilen.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::String &outputFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg och namn för inmatnings-pdf-fil. |
| outputFile | const System::String\& | Sökväg och namn för utdata-pdf-fil. |

### ReturnValue

boolesk – Sant för lyckat, annars falskt.

## Se även

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Skapar ett anpassat häfte från firstInputFile till outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Inmatningsfilen. |
| outputFile | const System::String\& | Sökväg och namn för utdata-pdf-fil. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | De vänstra sidorna i häftet. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | De högra sidorna i häftet. |

### ReturnValue

boolesk – Sant för lyckat, annars falskt.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::String\&, const System::SharedPtr\<PageSize\>\&) method


Skapar en häfte från inputFile till outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Sökväg och namn för inmatnings-pdf-fil. |
| outputFile | const System::String\& | Sökväg och namn för utdata-pdf-fil. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Sidstorleken för utdata-pdf-filen. |

### ReturnValue

Sant om operationen lyckades.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(const System::String\&, const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<int32_t\>\&) method


Skapar ett anpassat häfte från firstInputFile till outputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(const System::String &inputFile, const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::ArrayPtr<int32_t> &leftPages, const System::ArrayPtr<int32_t> &rightPages)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Inmatningsfilen. |
| outputFile | const System::String\& | Sökväg och namn för utdata-pdf-fil. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Sidstorleken för utdata-pdf-filen. |
| leftPages | const System::ArrayPtr\<int32_t\>\& | De vänstra sidorna. |
| rightPages | const System::ArrayPtr\<int32_t\>\& | De högra sidorna. |

### ReturnValue

boolesk – Sant för lyckat, annars falskt.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
