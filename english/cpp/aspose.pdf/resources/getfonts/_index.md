---
title: Aspose::Pdf::Resources::GetFonts method
linktitle: GetFonts
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Resources::GetFonts method. Returns fonts collection. If resources don''t contain fonts entry it will be created in depends of CreateIfAbsent flag in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf/resources/getfonts/
---
## Resources::GetFonts method


Returns fonts collection. If resources don't contain fonts entry it will be created in depends of CreateIfAbsent flag.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Text::FontCollection> Aspose::Pdf::Resources::GetFonts(bool CreateIfAbsent)
```


| Parameter | Type | Description |
| --- | --- | --- |
| CreateIfAbsent | bool | If this flag is true then fonts will be created if this entry is absent. |

### ReturnValue

Fonts collection.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>CreateIfAbsent</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If this flag is true then fonts will be created if this entry is absent.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FontCollection](../../../aspose.pdf.text/fontcollection/)
* Class [Resources](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
