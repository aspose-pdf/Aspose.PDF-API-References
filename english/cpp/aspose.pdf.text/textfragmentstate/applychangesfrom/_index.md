---
title: Aspose::Pdf::Text::TextFragmentState::ApplyChangesFrom method
linktitle: ApplyChangesFrom
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFragmentState::ApplyChangesFrom method. Applies settings from another textState in C++.'
type: docs
weight: 4700
url: /cpp/aspose.pdf.text/textfragmentstate/applychangesfrom/
---
## TextFragmentState::ApplyChangesFrom method


Applies settings from another textState.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Text::TextFragmentState::ApplyChangesFrom(System::SharedPtr<TextState> textState) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| textState | System::SharedPtr\<TextState\> | [Text](../../) state object. |
## Remarks


Only those properties will be copied that were changed explicitly. 

<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>textState</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_text" kindref="compound">Text</ref> state object.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [TextState](../../textstate/)
* Class [TextFragmentState](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
