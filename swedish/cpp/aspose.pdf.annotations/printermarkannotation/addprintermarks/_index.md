---
title: "Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks metod"
linktitle: "AddPrinterMarks"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks method. Lägger till skrivarens markeringar på den angivna sidan i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr\<Aspose::Pdf::Page\>\&, PrinterMarksKind) method


Lägger till skrivarens markeringar på den angivna sidan.

```cpp
static void Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr<Aspose::Pdf::Page> &page, PrinterMarksKind marksKind)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Sidan som skrivarens markeringar ska läggas till på. |
| marksKind | PrinterMarksKind | Typen av skrivarens markeringar att lägga till. |
## Anmärkningar



Denna metod lägger till olika typer av skrivarens markeringar baserat på de angivna [PrinterMarksKind](../../printermarkskind/) flaggorna. Om [PrinterMarksKind::None](../../printermarkskind/) anges, läggs inga markeringar till.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Class [PrinterMarkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr\<Document\>\&, PrinterMarksKind) method


Lägger till skrivarens markeringar på alla sidor i det angivna dokumentet.

```cpp
static void Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr<Document> &document, PrinterMarksKind marksKind)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | const System::SharedPtr\<Document\>\& | Dokumentet som skrivarens markeringar ska läggas till i. |
| marksKind | PrinterMarksKind | Typen av skrivarens markeringar att lägga till. |
## Anmärkningar



Denna metod lägger till olika typer av skrivarens markeringar baserat på de angivna [PrinterMarksKind](../../printermarkskind/) flaggorna. Om [PrinterMarksKind::None](../../printermarkskind/) anges, läggs inga markeringar till.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Class [PrinterMarkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
