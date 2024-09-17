---
title: Aspose::Pdf::Document::LoadFrom method
linktitle: LoadFrom
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::LoadFrom method. Loads a file, converting it to PDF in C++.'
type: docs
weight: 9200
url: /cpp/aspose.pdf/document/loadfrom/
---
## Document::LoadFrom method


Loads a file, converting it to PDF.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Document::LoadFrom(System::String filename, System::SharedPtr<LoadOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| filename | System::String | The path to the file to open. |
| options | System::SharedPtr\<LoadOptions\> | The load options. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>filename</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The path to the file to open.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The load options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>PdfException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If the file cannot be loaded.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>FileNotFoundException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If the file is not found.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
