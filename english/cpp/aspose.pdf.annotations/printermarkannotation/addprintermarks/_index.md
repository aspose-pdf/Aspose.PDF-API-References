---
title: Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks method
linktitle: AddPrinterMarks
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks method. Adds printer''s marks to all pages in the specified document in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## PrinterMarkAnnotation::AddPrinterMarks(System::SharedPtr\<Document\>, PrinterMarksKind) method


Adds printer's marks to all pages in the specified document.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks(System::SharedPtr<Document> document, PrinterMarksKind marksKind)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | System::SharedPtr\<Document\> | The document to which the printer's marks will be added. |
| marksKind | PrinterMarksKind | The kind of printer's marks to add. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document to which the printer's marks will be added.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>marksKind</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The kind of printer's marks to add.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Thrown when the <emphasis>document</emphasis>  is null.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

This method adds various types of printer's marks based on the provided [PrinterMarksKind](../../printermarkskind/) flags. If [PrinterMarksKind::None](../../printermarkskind/) is provided, no marks are added. 
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Class [PrinterMarkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## PrinterMarkAnnotation::AddPrinterMarks(System::SharedPtr\<Aspose::Pdf::Page\>, PrinterMarksKind) method


Adds printer's marks to the specified page.

```cpp
static ASPOSE_PDF_SHARED_API void Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks(System::SharedPtr<Aspose::Pdf::Page> page, PrinterMarksKind marksKind)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | The page to which the printer's marks will be added. |
| marksKind | PrinterMarksKind | The kind of printer's marks to add. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page to which the printer's marks will be added.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>marksKind</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The kind of printer's marks to add.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Thrown when the <emphasis>page</emphasis>  is null.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

This method adds various types of printer's marks based on the provided [PrinterMarksKind](../../printermarkskind/) flags. If [PrinterMarksKind::None](../../printermarkskind/) is provided, no marks are added. 
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Class [PrinterMarkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
