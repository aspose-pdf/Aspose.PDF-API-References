---
title: Aspose::Pdf::Text::TableAbsorber::Remove method
linktitle: Remove
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TableAbsorber::Remove method. Removes an AbsorbedTable from the page in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.text/tableabsorber/remove/
---
## TableAbsorber::Remove method


Removes an [AbsorbedTable](../../absorbedtable/) from the page.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Text::TableAbsorber::Remove(System::SharedPtr<AbsorbedTable> table)
```


| Parameter | Type | Description |
| --- | --- | --- |
| table | System::SharedPtr\<AbsorbedTable\> | [AbsorbedTable](../../absorbedtable/) to remove. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>table</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_absorbed_table" kindref="compound">AbsorbedTable</ref> to remove.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

Please take into account it changes TableList collection. In case removing/replacing tables in loop please use copy of TableList collection. 
## See Also

* Class [AbsorbedTable](../../absorbedtable/)
* Class [TableAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
