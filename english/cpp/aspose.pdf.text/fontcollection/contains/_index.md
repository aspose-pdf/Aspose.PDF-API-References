---
title: Aspose::Pdf::Text::FontCollection::Contains method
linktitle: Contains
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::FontCollection::Contains method. Checks if font exists in font collection in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.text/fontcollection/contains/
---
## FontCollection::Contains(const System::String\&) const method


Checks if font exists in font collection.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Text::FontCollection::Contains(const System::String &name) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const System::String\& | [Font](../../font/) name. |

### ReturnValue

True in case collection contains the font with specified name.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>name</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_font" kindref="compound">Font</ref> name.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontCollection::Contains(const System::SharedPtr\<Font\>\&) const method


Determines whether the collection contains a specific value.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Text::FontCollection::Contains(const System::SharedPtr<Font> &item) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::SharedPtr\<Font\>\& | The object to locate in the collection |

### ReturnValue

true if item is found in the collection; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>item</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The object to locate in the collection</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Font](../../font/)
* Class [FontCollection](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
