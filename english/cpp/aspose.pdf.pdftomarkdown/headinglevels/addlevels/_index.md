---
title: Aspose::Pdf::PdfToMarkdown::HeadingLevels::AddLevels method
linktitle: AddLevels
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfToMarkdown::HeadingLevels::AddLevels method. Adds heading levels. Font size collection should be sorted by decreasing size in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.pdftomarkdown/headinglevels/addlevels/
---
## HeadingLevels::AddLevels method


Adds heading levels. Font size collection should be sorted by decreasing size.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::PdfToMarkdown::HeadingLevels::AddLevels(System::SharedPtr<System::Collections::Generic::ICollection<double>> fontSizes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fontSizes | System::SharedPtr\<System::Collections::Generic::ICollection\<double\>\> | Values should be sorted in decreasing order. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fontSizes</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Values should be sorted in decreasing order.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If the value is not sorted or the value is less than one.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [HeadingLevels](../)
* Namespace [Aspose::Pdf::PdfToMarkdown](../../)
* Library [Aspose.PDF for C++](../../../)
