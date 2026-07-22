---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks‑metod"
linktitle: "SplitToBulks"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks method. Delar upp Pdf-filen i flera dokument. Dokumenten kan vara enkelsidiga eller flersidiga i C++."
type: docs
weight: 5900
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## PdfFileEditor::SplitToBulks(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\&) method


Delar upp [Pdf](../../../aspose.pdf/) filen i flera dokument. Dokumenten kan vara enkelsidiga eller flersidiga.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::ArrayPtr<int32_t>> &numberOfPage)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Inmatnings-PDF-ström. |
| numberOfPage | const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\& | Start- och slut sida för varje dokument. |

### ReturnValue

Utdata-PDF-strömmar, varje ström buffrar ett PDF-dokument.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToBulks(const System::String\&, const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\&) method


Delar upp [Pdf](../../../aspose.pdf/) filen i flera dokument. Dokumenten kan vara enkelsidiga eller flersidiga.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(const System::String &inputFile, const System::ArrayPtr<System::ArrayPtr<int32_t>> &numberOfPage)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | const System::String\& | Indata-PDF-fil. |
| numberOfPage | const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\& | Array som innehåller en array av double-element, som är start- och slut sidor för dokumentet. |

### ReturnValue

Utdata-PDF-strömmar, varje ström buffrar ett PDF-dokument.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
