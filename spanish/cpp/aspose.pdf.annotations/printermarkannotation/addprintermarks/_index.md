---
title: "Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks método"
linktitle: "AddPrinterMarks"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks método. Añade las marcas de la impresora a la página especificada en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr\<Aspose::Pdf::Page\>\&, PrinterMarksKind) method


Agrega marcas de impresora a la página especificada.

```cpp
static void Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr<Aspose::Pdf::Page> &page, PrinterMarksKind marksKind)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | const System::SharedPtr\\<Aspose::Pdf::Page\\>\\& | La página a la que se añadirán las marcas de la impresora. |
| marksKind | PrinterMarksKind | El tipo de marcas de la impresora a añadir. |
## Observaciones



Este método añade varios tipos de marcas de la impresora basándose en los indicadores [PrinterMarksKind](../../printermarkskind/) proporcionados. Si se proporciona [PrinterMarksKind::None](../../printermarkskind/), no se añaden marcas.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Class [PrinterMarkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr\<Document\>\&, PrinterMarksKind) method


Agrega marcas de impresora a todas las páginas del documento especificado.

```cpp
static void Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr<Document> &document, PrinterMarksKind marksKind)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | const System::SharedPtr\<Document\>\& | El documento al que se añadirán las marcas de la impresora. |
| marksKind | PrinterMarksKind | El tipo de marcas de la impresora a añadir. |
## Observaciones



Este método añade varios tipos de marcas de la impresora basándose en los indicadores [PrinterMarksKind](../../printermarkskind/) proporcionados. Si se proporciona [PrinterMarksKind::None](../../printermarkskind/), no se añaden marcas.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Class [PrinterMarkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
