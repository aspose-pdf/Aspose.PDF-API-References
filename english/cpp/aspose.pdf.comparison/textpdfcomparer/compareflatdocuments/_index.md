---
title: Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments method
linktitle: CompareFlatDocuments
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments method. Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## TextPdfComparer::CompareFlatDocuments(System::SharedPtr\<Document\>, System::SharedPtr\<Document\>, System::SharedPtr\<ComparisonOptions\>) method


Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Diff::DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments(System::SharedPtr<Document> document1, System::SharedPtr<Document> document2, System::SharedPtr<ComparisonOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | System::SharedPtr\<Document\> | First document. |
| document2 | System::SharedPtr\<Document\> | Second document. |
| options | System::SharedPtr\<ComparisonOptions\> | [Comparison](../../) options. |

### ReturnValue

List of changes.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>First document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>document2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Second document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_comparison" kindref="compound">Comparison</ref> options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## TextPdfComparer::CompareFlatDocuments(System::SharedPtr\<Document\>, System::SharedPtr\<Document\>, System::SharedPtr\<ComparisonOptions\>, System::String) method


Compares two documents page by page. The result is saved in a PDF file. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<Diff::DiffOperation>>> Aspose::Pdf::Comparison::TextPdfComparer::CompareFlatDocuments(System::SharedPtr<Document> document1, System::SharedPtr<Document> document2, System::SharedPtr<ComparisonOptions> options, System::String resultPdfDocumentPath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document1 | System::SharedPtr\<Document\> | First document. |
| document2 | System::SharedPtr\<Document\> | Second document. |
| options | System::SharedPtr\<ComparisonOptions\> | [Comparison](../../) options. |
| resultPdfDocumentPath | System::String | Path to the pdf file to save the comparison results. |

### ReturnValue

List of changes.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>document1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>First document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>document2</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Second document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_comparison" kindref="compound">Comparison</ref> options.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>resultPdfDocumentPath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to the pdf file to save the comparison results.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DiffOperation](../../../aspose.pdf.comparison.diff/diffoperation/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ComparisonOptions](../../comparisonoptions/)
* Class [TextPdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
