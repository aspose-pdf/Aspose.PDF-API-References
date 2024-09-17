---
title: Aspose::Pdf::Text::FontCollection::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::FontCollection::idx_get method. Gets the font element at the specified index in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.text/fontcollection/idx_get/
---
## FontCollection::idx_get(int32_t) method


Gets the font element at the specified index.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Font> Aspose::Pdf::Text::FontCollection::idx_get(int32_t index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | Index within the collection. |

### ReturnValue

[Font](../../font/) object.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>index</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Index within the collection.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Font](../../font/)
* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontCollection::idx_get(System::String) method


Gets font from the collection by font name. Exception is thrown if font was not found.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Font> Aspose::Pdf::Text::FontCollection::idx_get(System::String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | System::String | Name of the font. |

### ReturnValue

Found font.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>name</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of the font.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Font](../../font/)
* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
